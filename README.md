```mermaid
sequenceDiagram

participant Route
participant View
participant Controller
participant Modele


activate View
View->>Route: Notify Login
deactivate View
Route->>Controller: verification
activate Controller
Controller-->>Modele: Verif Login:password
Modele->>Modele:Checking si ok
deactivate Controller
Modele -->>Controller: Acceptation
Controller->>View:Validation
Activate View
View->>View:CreatePost
Controller-->>Modele: Verification
View->>Modele: Ajout database
deactivate View
Activate Modele
Modele-->>View: Update Page
deactivate Modele
```