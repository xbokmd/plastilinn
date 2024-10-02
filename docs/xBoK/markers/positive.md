alias:: positive
icon:: 🟢

- ### Extreme positive (+++++)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "+++++"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### High positive (++++)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "++++"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Medium positive (+++)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "+++"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Moderate positive (++)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "++"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Low positive (+)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "+"]
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
