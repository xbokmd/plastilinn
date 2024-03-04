alias:: completion
icon:: ▶️
- #question Is the block completed?
- ### Extreme completion (>>>>>)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name ">>>>>"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### High completion (>>>>)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name ">>>>"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Medium completion (>>>)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name ">>>"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Moderate completion (>>)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name ">>"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Low completion (>)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name ">"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
)
