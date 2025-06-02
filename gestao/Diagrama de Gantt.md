

``` mermaid
%%{init: {'theme': 'base', 'themeVariables': {'taskBkgColor': '#4CAF50', 'taskBorderColor': '#388E3C', 'sectionBkgColor': '#FFEB3B', 'altSectionBkgColor': '#FFC107'}}}%%
gantt
    title Cronograma
    dateFormat  YYYY-MM-DD
    section Protótipo
    Compra de materiais         :active, 2025-05-01, 60d
    Código base                 :done, 2025-05-01, 20d
    Modularização do código     :active, 2025-05-21, 40d
    Projeto da estrutura        :done, 2025-05-15, 15d
    Montagem balança_1          :done, 2025-06-01, 10d
    Montagem balança_2          :active, 2025-06-01, 10d
    section Testes
    Teste com 1 balança          :, 2025-06-11, 7d
    Teste com 2 balanças         :, 2025-06-15, 7d
    Banco de dados               :, 2025-06-11, 14d
    interface                    :, 2025-06-11, 14d

    section Documentação
    Artigo de TCC                     :2025-06-19, 30d
```
