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
        string productType
        string profileType
        double price
        int layoutSize
        string connectionType
        string caseMaterial
        bool hotSwappable
        bool knob
        bool wristRest
        bool screen
        bool lightingType
        bool adjustableFeet
        string mountingType
        double tentingAngle
        string keycapMaterial
        double batterySize
        
    }
    Users ||--o{ Keyboards : "owns"
```

