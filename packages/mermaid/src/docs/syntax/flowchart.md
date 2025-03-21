<!DOCTYPE html>
<html>
<head>
    <title>Diagrama de Flujo - Estimulación Muscular</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/10.0.2/mermaid.min.js"></script>
</head>
<body>
    <div class="mermaid">
        graph TD;
            A[Inicio] --> B[Colocar guantes de nitrilo];
            B --> C[Preparación del biomodelo];
            C --> D[Sedación del biomodelo];
            D --> E[Colocación sobre la tabla y sujeción];
            E --> F[Disección de la pata trasera];
            F --> G[Identificación del nervio ciático y músculo gastrocnemio];
            G --> H[Hidratación con solución Ringer 37°C];
            H --> I[Verificación de la respuesta contráctil];
            I --> J[Preparación del circuito eléctrico];
            J --> K[Colocar electrodo negativo cerca del nervio/músculo];
            K --> L[Colocar electrodo positivo en posición adecuada];
            L --> M[Verificar circuito cerrado];
            M --> N[Aplicar estímulo eléctrico];
            N --> O[Iniciar con 0.1V, aumentar 1V cada 10s hasta 10V];
            O --> P[Medir intensidad de contracción (0-5)];
            P --> Q[Aplicar estímulos mecánicos];
            Q --> R[Comprimir con pinza (ligero, mediano, fuerte)];
            R --> S[Clasificar respuesta contráctil];
            S --> T[Aplicar estímulos térmicos];
            T --> U[Usar Ringer a 4°C y 44°C];
            U --> V[Clasificar respuesta contráctil];
            V --> W[Aplicar estímulos de escalera, tetania y fatiga];
            W --> X[Aumentar voltaje cada 10s hasta fatiga muscular];
            X --> Y[Machacamiento del nervio];
            Y --> Z[Machacar nervio hasta la mitad y estimular];
            Z --> AA[Observar respuesta muscular];
            AA --> AB[Fin];
    </div>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
