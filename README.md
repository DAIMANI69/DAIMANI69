graph TD
    A[Recepción de Legajos] --> B[Revisión Inicial]
    B --> C[Registro en Sistema]
    C --> D[Clasificación de Documentos]
    D --> E[Actualización Periódica]
    E --> F[Archivo o Destrucción de Documentos]

    %% Descripciones
    A -->|“Recepción de documentos físicos”| B
    B -->|“Verificación de datos”| C
    C -->|“Ingreso en base de datos”| D
    D -->|“Organización según criterios”| E
    E -->|“Actualización según cambios”| F
    F -->|“Archivo para conservar o destrucción”| F

    %% Añadir notas o comentarios
    subgraph Descripciones
      A[Recepción de Legajos]
      B[Revisión Inicial]
      C[Registro en Sistema]
      D[Clasificación de Documentos]
      E[Actualización Periódica]
      F[Archivo o Destrucción de Documentos]
    end

    note right of A
      Recepción de documentos por correo o en mano
    end

    note right of B
      Verificación de la integridad de los documentos
    end

    note right of C
      Registro en el sistema de gestión documental
    end

    note right of D
      Clasificación por tipo de documento
    end

    note right of E
      Revisión periódica de la validez de los documentos
    end

    note right of F
      Archivo en almacenamiento o destrucción segura
    end
    
