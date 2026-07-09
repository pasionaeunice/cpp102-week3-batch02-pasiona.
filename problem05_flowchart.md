flowchart TD
    A([Start]) --> B[/Price1 × Quantity1/]
    B --> C[/Price2 × Quantity2/]
    C --> D[/Price3 × Quantity3/]
    D --> E["sum = (Price1 × Quantity1) + (Price2 × Quantity2) + (Price3 × Quantity3)"]
    E --> F[/Display sum/]
    F --> G([End])