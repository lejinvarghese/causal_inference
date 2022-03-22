# Flow Diagrams

## Instrumental Variables

    - Unmeasured Confounders `U`
    - Measured confounders `X`
    - Treament `A`
    - Outcome `Y `

    ```mermaid
            flowchart LR;
                A --> Y;
                U --> A;
                U --> Y;
                X --> A;
                X --> Y;
    ```

    ```mermaid
            flowchart LR;
                A --> Y;
                Z --> A;
                X --> A;
                X --> Y;
    ```
