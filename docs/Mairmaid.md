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