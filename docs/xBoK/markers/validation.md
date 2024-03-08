alias:: validation
icon:: 🟰
- #question Have I verified this in the real world?
- #question Is this a fact I have experimentally verified?
- #question Is this a statement I can prove with objective facts and data?
- ### Extreme validation (=====)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "====="]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### High validation (====)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "===="]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Medium validation (===)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "==="]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Moderate validation (==)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "=="]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Low validation (=)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "="]
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
