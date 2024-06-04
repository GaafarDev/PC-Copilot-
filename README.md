# PC-Copilot-



```mermaid
erDiagram
    Users ||--o{ Admins : "inherits"
    Users ||--o{ Visitors : "inherits"
    Users {
        int id
        string name
        string email
        string password
    }
    Admins {
        int admin_id
        string admin_specific_field
    }
    Visitors {
        int visitor_id
        string visitor_specific_field
    }
    Keyboards {
        int id
        string brand
        string model
    }
    Users ||--o{ Keyboards : "owns"
```
