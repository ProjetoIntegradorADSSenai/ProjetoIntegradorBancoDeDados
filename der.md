```mermaid
erDiagram
    Peca ||--o{ Separacao : "contém"
    Peca {
        id INT PK
        tipo VARCHAR
    }
    Separacao {
        id INT PK
        id_peca INT FK
        horario_inicial TIMESTAMP
        horario_fim TIMESTAMP
    }
```
