```mermaid
graph TD
    %% Define Node Colors
    classDef primordial fill:#222,stroke:#fff,stroke-width:2px,color:#fff;
    classDef soul fill:#444,stroke:#fff,color:#fff;
    classDef etada fill:#666,stroke:#fff,color:#fff,stroke-width:2px;
    classDef result fill:#f9f,stroke:#333,color:#000;
    classDef limitation fill:#ff9,stroke:#333,color:#000;

    %% --- THE DUALITY --- %%
    ANU["ANU <br/>(Stasis / The Everything)"]
    PADOMAY["PADOMAY <br/>(Change / The Void)"]
    class ANU,PADOMAY primordial;

    ANU_I_EL["Anui-El <br/>(Soul of Anu)"]
    SITHIS["Sithis <br/>(Soul of Padomay)"]
    class ANU_I_EL,SITHIS soul;

    ANU --> ANU_I_EL
    PADOMAY --> SITHIS

    %% --- THE AURBIS --- %%
    AURBIS["The AURBIS <br/>(The Gray Maybe)"]
    ANU_I_EL ==> AURBIS
    SITHIS ==> AURBIS
    class AURBIS result;

    %% --- THE ET'ADA --- %%
    ETADA["Et'Ada <br/>(Original Spirits)"]
    AURBIS --> ETADA
    class ETADA etada;

    %% --- THE GREAT SCHISM --- %%
    AEDRA["AEDRA <br/>('Our Ancestors')"]
    DAEDRA["DAEDRA <br/>('Not Our Ancestors')"]
    MAGNAGE["MAGNA GE <br/>(The Star-Orphans)"]

    ETADA -->|Sacrificed| AEDRA
    ETADA -->|Refused| DAEDRA
    ETADA -->|Fled| MAGNAGE

    %% --- THE AEDRIC SUBSET --- %%
    DIVINES["The Eight DIVINES <br/>(The Spokes)"]
    EHLNOFEY_POOL["EHLNOFEY <br/>(Lesser Aedra Pool)"]

    AEDRA -->|"Structural (Partial)"| DIVINES
    AEDRA -->|"Remaining in Mundus"| EHLNOFEY_POOL

    PLANETS["Planets <br/>(Infinite Bodies)"]
    DIVINES --> PLANETS
    class PLANETS limitation;

    %% --- THE EHLNOFEY SPLIT --- %%
    EARTHBONES["The EARTH BONES <br/>(Natural Laws)"]
    MORTAL_SUPER["The Ancestors <br/>(Mortal Precursors)"]

    EHLNOFEY_POOL -->|"Total Sacrifice (Physics)"| EARTHBONES
    EHLNOFEY_POOL -->|"Gradual Descent (Mind)"| MORTAL_SUPER

    LAWS["PHYSICS <br/>(Gravity, Time, Nature)"]
    EARTHBONES --> LAWS
    class LAWS limitation;

    %% --- THE MORTAL CLASSIFICATION --- %%
    MEN["MEN <br/>(Wandering Ehlnofey)"]
    MER["MER <br/>(Old Ehlnofey)"]
    BESTIAL["Other Mortal Stocks"]

    MORTAL_SUPER --> MEN
    MORTAL_SUPER --> MER
    MORTAL_SUPER --> BESTIAL
    class MEN,MER,BESTIAL result;
    
```
# Deity Specification & Hierarchy Table

This table categorizes the spirits of the Aurbis based on their level of sacrifice, current agency, and metaphysical role in maintaining the Mundus.

| Entity Class | Category | Sub-gradient | Sacrifice Nature | Current Status |
| :--- | :--- | :--- | :--- | :--- |
| **Primal Forces** | Anu / Padomay | 0 (Source) | None | Non-sentient cosmic constants. |
| **The Souls** | Anui-El / Sithis | 1 | None | The "Wills" of the Primal Forces. |
| **The Et'Ada** | Original Spirits | 2 | Variable | The collective pool of all gods. |
| **Daedra** | Princes / Lords | 2 | **None** | Sovereign; active in Oblivion. |
| **Magna Ge** | Star-Orphans | 2 | **Aborted** | Distant; reside in Aetherius. |
| **The Divines** | Greater Aedra | 3 | **Partial** | Comatose; The **Eight Spokes** (Planets). |
| **Ehlnofey** | Lesser Aedra | 3 | **Residual** | The starting "pool" of spirits on Nirn. |
| **Earth Bones** | Natural Laws | 4 (from Ehlnofey) | **Total** | Non-sentient; **The Laws of Physics**. |
| **Mortals** | Men / Mer | 4 (from Ehlnofey) | **Biological** | Sentient; The **Ancestors** of Nirn. |

---

## Glossary of Hierarchy Terms

* **Sub-gradient:** The "distance" from the original source. Each step down (from [[Et'Ada]] to Mortal) involves a loss of power but a gain in defined, stable identity.
* **Structural (The Divines):** These spirits gave just enough of themselves to build the "[[Aurbis|Wheel]]," but kept their minds and names.
* **Foundational (Earth Bones):** These spirits gave everything. They are the gravity that holds your players to the ground and the air they breathe.
* **Biological (Mortals):** These spirits chose to shrink in power so they could keep their individuality. They didn't become the "Laws," they became the "Inhabitants."
* 