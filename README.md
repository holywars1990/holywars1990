```mermaid
graph TD
    A[¿Cuándo no existen los límites?]

    %% Principales casos en los que los límites no existen
    A --> B1[1. Cuando f(x) tiende a valores distintos por cada lado]
    B1 --> B1A[Ejemplo: f(x) se acerca a 2 por la izquierda y a 3 por la derecha]

    A --> B2[2. Cuando f(x) crece o decrece sin límite]
    B2 --> B2A[Ejemplo: f(x) tiende a infinito positivo o negativo]

    A --> B3[3. Cuando f(x) oscila sin tender a un valor fijo]
    B3 --> B3A[Ejemplo: f(x) = sin(1/x), oscila entre -1 y 1]

    %% Simplificación de expresiones
    A --> C[Formas de simplificar expresiones]
    C --> C1[1. Factorización]
    C1 --> C1A[Ejemplo: factores comunes, diferencia de cuadrados]
    C --> C2[2. Trinomios]
    C2 --> C2A[Ejemplo: trinomios de la forma ax^2 + bx + c]

    %% Límites cuando x tiende a cero o infinito
    A --> D[Límites cuando x tiende a 0 o infinito]
    D --> D1[Ejemplos de casos]
    D1 --> D1A[Cuando x → 0 o x → ∞, el límite puede ser 0 o infinito]

    %% Resolución de formas indeterminadas
    A --> E[Resolución de formas indeterminadas]
    E --> E1[1. Indeterminación 0/0]
    E1 --> E1A[Resolución mediante factorización o simplificación]
    E --> E2[2. Indeterminación ∞/∞]
    E2 --> E2A[Resolución mediante simplificación de términos]
