alias:: negative
icon:: 🔴

- ### Extreme negative (-----)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "-----"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### High negative (----)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "----"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Medium negative (---)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "---"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Moderate negative (--)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "--"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Low negative (-)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "-"]
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
