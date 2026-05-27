```mermaid
    gitGraph
        commit
        commit
        branch develop
        checkout develop
        commit
        commit
        branch feature
        checkout feature
        commit
        commit
        checkout develop
        merge feature
        commit
        checkout main
        merge develop
        commit
```

erDiagram
          CUSTOMER }|..|{ DELIVERY-ADDRESS : has
          CUSTOMER ||--o{ ORDER : places
          CUSTOMER ||--o{ INVOICE : "liable for"
          DELIVERY-ADDRESS ||--o{ ORDER : receives
          INVOICE ||--|{ ORDER : covers
          ORDER ||--|{ ORDER-ITEM : includes
          PRODUCT-CATEGORY ||--|{ PRODUCT : contains
          PRODUCT ||--o{ ORDER-ITEM : "ordered in"
