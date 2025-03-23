1. Definição do escopo
    1. Ideia 
    - Desenvolver um sistema embarcado, capaz de monitorar e gerenciar a vazão de gás GLP, através da mediçâo da massa de um botijão,  comunicacão com um servidor local ou central onde está instalada uma interface que gera gráficos de consumo, alertas de quantidade mínima definida por usuário, substituição do botijão consumido por outro cheio via acionamento de válvulas e marcação para substituição do dispositivo vazio por indicadores remotos e locais, sensoreamento de gás para indicação de vazamentos pela linha e monitoramento contínuo para análises de falhas.
    2. Validação
    - Por questões de segurança e quantidade de recursos disponíveis, este projeto será validado utilizando fluidos não inflamáveis. No caso deste protótipo, a água. Utilizaremos dois galões de quantidades simbólicas para simular os botijões, com a água para gerar o fluxo necessário para variação de massa e garantir o monitoramento. Todo o resto do sistema será adaptado de acordo com as necessidades deste protótipo, por tanto não utilizaremos os sensores de gás.
2. Requisitos
    - Características necessárias 
        - Medição de massa com precisão de miligramas
        - Comunicação MQTT via WiFi
        - Servidor local para infraestrutura (Banco de Dados, broker MQTT)
        - Interface desktop para monitoramento e acionamento
        - Controle e análise de Dados (Geração de gráficos, estatísticas de consumo)
        - Controle de válvulas para acionamento de dispositivos
    - Componentes mecânicos
       - MDF (Necessário revisão estrutural)
       - Célula de carga por flexão
       - Válvulas solenoides
    - Coponentes eletronicos
       - ESP32
       - Módulos Relé
       - Regulador de tensão LM7805C
    - Conhecimentos
       - Programação em linguagem C/C++ (ESP32)
       - Programação em Javascript (ReactJS, ferramentas JS)
       - Protocolo MQTT
       - Mecânica
       - Elétrica
       - Eletrônica

3. Estrutura Analítica do Projeto - EAP
    - Hierarquia
        - Capitão ==> Caio Marcilio
        - Co-capitão ==> Matheus Yuji
        - Gestor ==> João Victor
    - Tarefas
        - Grupo
           - Testes do protótipo
           - construção eletroeletrônica
           - construção mecânica
        - Caio
            - Programação (firmware, software)
            - Protocolos de comunicação
        - Matheus Yuji
            - Pesquisa e compra de produtos
            - Responsável pelas documentações
        - João Victor
            - Gestão
            - Desenhos
            - Pesquisa sobre normas e materiais envolvendo GLP 

[Gestão do projeto](gestao_do_projeto.md)