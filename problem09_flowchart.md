```mermaid
flowchart TD
A([Start]) --> B[/Input number/]
B --> C{number >= 0?}
C -- Yes --> D[/Display "Positive Balance"/]
C -- No --> E[/Display "Negative Balance"/]
D --> F([End])
E --> F
```
