
\```mermaid
graph LR
    Users["Users<br/>(SSH / Web Portal)"] --> Login["Login Node"]
    Login --> Scheduler["Job Scheduler<br/>(Slurm)"]
    Login --> Storage[("Shared Storage")]
    Scheduler --> C1["Compute Node"]
    Scheduler --> C2["Compute Node"]
    Scheduler --> C3["Compute Node"]
    Storage --> C1
    Storage --> C2
    Storage --> C3
\```
