alias:: risk
icon:: 🔥
- #question Is this something I should prioritize ($$$$$)?
- #question Is this something urgent but not the most urgent ($)?
- ### Extreme risk (¡¡¡¡¡)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "¡¡¡¡¡"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### High risk (¡¡¡¡)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "¡¡¡¡"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Medium risk (¡¡¡)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "¡¡¡"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Moderate risk (¡¡)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "¡¡"]
      [?b :block/refs ?p]
      (not 
         [?b :block/refs [:block/name "plastilinn-internal"]]
      )
     ]
    :breadcrumb-show? false
    :table-view? false
    }
    #+END_QUERY
- ### Low risk (¡)
  - #minimal-query
    #+BEGIN_QUERY
    {:query [:find (pull ?b [*])
      :where
      [?p :block/name "¡"]
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
