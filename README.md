# avanade
Java Restful API Criada para a Avanade

## Diagrama de classes

...mermaid
classDiagram
    class Customer {
        +String name
        +Account account
        +Feature[] features
        +SweetOrder order_for_sweets
        +News[] news
    }

    class Account {
        +String client
        +String credit
        +String debt
    }

    class Feature {
        +String icon
        +String description
    }

    class SweetOrder {
        +String cake
    }

    class News {
        +String icon
        +String description
    }

    Customer --> Account
    Customer --> Feature
    Customer --> SweetOrder
    Customer --> News
...
