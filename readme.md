## Planificació del projecte (Gantt)
```mermaid
gantt
    title Cronograma de Proyecto Web
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m
    tickInterval 1day

    section Investigación
    Definir alcance          :done,    des1, 2026-04-20, 2d
    Análisis de competencia  :active,  des2, after des1, 3d

    section Diseño
    Wireframes               :         des3, 2026-04-25, 4d
    Prototipo alta fidelidad :crit,    des4, after des3, 5d

    section Desarrollo
    Frontend                 :         dev1, 2026-05-02, 7d
    Backend                  :         dev2, after des4, 7d

    section Lanzamiento
    QA y Pruebas             :         rel1, after dev1, 3d
    Publicación              :         rel2, 2026-05-15, 1d
    ```