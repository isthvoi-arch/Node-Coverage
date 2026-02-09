```mermaid
flowchart TD
    LookIntoNode[Look into the nodes and current drop capacity for each nodes]
        --> CheckDemand[Review historical ride data<br/>for that area to understand demand]
    CheckDemand
        --> CheckLocation[Check physical location<br/>to assess how many scooters fit]
    CheckLocation
        --> DecideCount[Decide appropriate scooter count<br/>based on demand and space]
    DecideCount
        --> AdjustCapacity[Adjust node capacity number]
    AdjustCapacity
        --> Publish[Publish]
