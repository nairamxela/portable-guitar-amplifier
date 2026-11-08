# System Block Diagram

```mermaid
flowchart LR
    G[Guitar Input] --> P[Pre-Amplifier]
    P --> T[Tone Control]
    T --> D[Distortion Circuit]
    D --> A[Power Amplifier]
    A --> S[Loudspeaker]

    U[USB-C 5V] --> C[Charging Circuit]
    C <--> B[Battery]
    B --> M[Power Management]
    U --> M
    M --> P
    M --> D
    M --> A
    M --> T