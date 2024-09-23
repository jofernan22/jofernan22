- 👋 Hi, I’m @jofernan22
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
jofernan22/jofernan22 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
graph TD
    A[Inicio] --> B[Inscripción de Estudiantes]
    B --> C{Evaluación Inicial}
    C -->|Nivel Determinado| D[Asignación a Cursos]
    C -->|Nivel No Claro| E[Evaluación Adicional]
    E --> C
    D --> F[Desarrollo de Clases]
    F --> G[Actividades Culturales]
    G --> H{Evaluación Continua}
    H -->|Progreso Satisfactorio| I[Continuar con el programa]
    H -->|Progreso Insuficiente| J[Tutoría Adicional]
    J --> F
    I --> K{Fin del Programa?}
    K -->|Sí| L[Certificación]
    K -->|No| F

    subgraph Responsables e Involucrados
    B1[Personal Administrativo]
    C1[Equipo Docente]
    D1[Coordinador Académico]
    F1[Equipo Docente]
    G1[Equipo Docente y Global Program Coordinator]
    H1[Equipo Docente]
    L1[Director del Centro]
    end

    B -.-> B1
    C -.-> C1
    D -.-> D1
    F -.-> F1
    G -.-> G1
    H -.-> H1
    L -.-> L1

    classDef default fill:#f9f9f9,stroke:#333,stroke-width:2px;
    classDef process fill:#3498DB,stroke:#2C3E50,stroke-width:2px,color:#ffffff;
    classDef decision fill:#FF9900,stroke:#2C3E50,stroke-width:2px,color:#ffffff;
    classDef responsible fill:#E6F3FF,stroke:#2C3E50,stroke-width:1px,color:#2C3E50;

    class A,B,D,E,F,G,I,J,L process;
    class C,H,K decision;
    class B1,C1,D1,F1,G1,H1,L1 responsible;

