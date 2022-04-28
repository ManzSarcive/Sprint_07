(site)
http://armougom-thomas.sprint-07-a.sc1lgvu9627.universe.wf/


(figma)
https://www.figma.com/proto/jNVFtXsf8DYAlwRFiyCeLz/Sprint_07?node-id=4%3A179&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=4%3A179

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
