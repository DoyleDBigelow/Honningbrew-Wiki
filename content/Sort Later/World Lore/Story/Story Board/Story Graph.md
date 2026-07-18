This is a proto on how to do this will fill out later
```mermaid
graph TD
A[Peisoners on Thalmor ship] --> B[Pirates free adventurers]
B --> C[Run in with Thalmor]
C --> D[]
 --> [Julianos Artifact]
 --> [Arkay Artifact]
 --> [Mara Artifact]
```

```mermaid

stateDiagram-v2
    [*] --> Escape_Thalmor_Ship
    Escape_Thalmor_Ship --> Bravil_Safehouse: Staff of Magnus Retrieved
    
    state Bravil_Safehouse {
        [*] --> Psijic_Contact
        Psijic_Contact --> Act_1_The_Anchors
    }

    state Act_1_The_Anchors {
        direction LR
        Aedric_Artifact_1 --> Aedric_Artifact_2
        Aedric_Artifact_2 --> Throat_of_the_World_Falls: The Fixed Point
    }

    Throat_of_the_World_Falls --> Clockwork_City_Search: Reality Destabilizes
    
    state Clockwork_City_Search {
        [*] --> Hermaeus_Mora_Deal
        Hermaeus_Mora_Deal --> Enter_Clockwork_City: Trade Elder Scroll
        Enter_Clockwork_City --> Retrieve_Clockwork_Heart
    }

    Retrieve_Clockwork_Heart --> The_Numidium_Arrival: The 5th Era Rift
    
    state Act_3_The_Rewriting {
        [*] --> Secure_Totem_of_Tiber_Septim
        Secure_Totem_of_Tiber_Septim --> Install_McGuffins_in_Walk_Brass
        Install_McGuffins_in_Walk_Brass --> Final_Decision
    }

    state Final_Decision {
        Rewrite_Aedric_Code --> [*]: Success
        Fail_to_Stabilize --> [*]: 5th Era Chaos
    }
    
    ```