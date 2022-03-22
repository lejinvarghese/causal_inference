# Flow Diagrams

## Instrumental Variables

- Unmeasured Confounders `U`
- Measured Confounders `X`
- Treament `A`
- Outcome  `Y`

```mermaid
        flowchart LR;
            A --> Y;
            U --> A;
            U --> Y;
            X --> A;
            X --> Y;
```

- Instrumental Variable `Z`
- Measured Confounders `X`
- Treament `A`
- Outcome  `Y`

```mermaid
        flowchart LR;
            A --> Y;
            Z --> A;
            X --> A;
            X --> Y;
```
