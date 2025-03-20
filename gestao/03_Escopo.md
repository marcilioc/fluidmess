1. Definição do escopo
    1. Ideia 
    - Desenvolver um sistema embarcado, capaz de monitorar e gerenciar a vazão de gás GLP, através da mediçâo da masa de seu botijão, haverá comunicacão com um servidor local onde rodará uma interface que irá gerar gráficos de consumo, alertar quando chegar na quantidade minima de gás cadastrada, trocará o botijão que está sendo tilizado e marcará o vazio para substituiçâo. Sensores de gás indicarão vazamentos pela linha.
    2. Validação
    - Por questôes de segurança e recursos monetários, este projeto será validado utilizando fluidos não infámaveis, no caso, a água.
    Utilizaremos dois galões para simular os butijões, agua para o gás e todo o resto será adapitado de acordo com as necessidades deste protótipo, por tanto não utilizaremos os sensores de gás.
2. Requisitos
    - Caracteristicas necesarias
        - Medição precisa
        - Comunicação por wifi
        - Servidor
        - aplicativo
        - controle e análise de Dados
        - Geração de graficos
        - Controle de Valvulas
    - Componentes mecânicos
       - MDF
       - Célula de carga por flexão
       - Válvulas solenoides
    - Coponentes eletronicos
       - Arduino
       - Esp32
       - MQTT
       - Módulo Relé
       - Regulador de tansão L8705C
    - Conhecimentos
       - Programaçãpo em linguagem C/C++ (Arduino)
       - Protocolo MQTT
       - Mecanica
       - Elétrica
       - Elétronica

3. Estrutura Analítica do Projeto - EAP
    - Hierárquia
        - Capitão ==> Caio Marcilio
        - Co-capitão ==> Otaguro Neves
        - Gestor ==> João Victor
    - Tarefas
        - Grupo
           - Testes
           - construção eletro-eletronica
           - contrução mecânica
        - Marcilio
               - Programação
               - Protocolos
        - Otaguro
               - Pesquisa e compra de produtos
               - Responsavel pelas documentações
        - João Victor
               - Gestão
               - Desenhos
               - pesquisa sobre normas e materiais envolvendo GLP 