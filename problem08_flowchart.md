``` mermaid
flowchart TD
A([Start]) --> B[/Input amount/]
B --> C{number >= 1000?}
C -- Yes --> D[/Display "Eligible for Discount""/]
C -- No --> E[/Display "Not Eligible for Discount"/]
D --> F([End])
E --> F
```
