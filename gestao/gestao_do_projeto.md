# Gestão do Projeto 

## Iniciação

1. Termo de Abertura do Projeto - TAP
   1. Projeto: Sistema de Monitoramento e Controle de Fluidos por Medidas Mássicas.
   2. Escopo: Desenvolver um protótipo para simular um sistema embarcado capaz de monitorar e gerenciar armazenamento de água através de uma interface remota que realiza medição por meio de células de carga e geração de gráficos e acionamento de alarmes de consumo e vazamentos, a fim de validar o conceito do projeto.
   3. Justificativa: Criar um sistema de medição e monitoramento para sistemas que trabalhem com fluidos, que utilize peso como grandeza de medição ao invés da pressão ou fluxo presente na linha do sistema, visando oferecer um sistema com um custo mais acessível em comparação ao que está no mercado.
   4. Recursos
      - Os integrantes do grupo;
      - ESP32, células de carga de flexão, MDF, tubos PVC, notebook, válvulas solenóide;
      - Valor estimado de R$500,00.
   5. Riscos
      - Falta de mercado para o produto final;
      - Custo de desenvolvimento elevado;
      - Não validação do protótipo.
   6. Objetos e metas:
      - Contrução de uma balança com precisão na casa das miligramas
      - Comunicação com um servidor
      - Monitoramento por aplicativo, em aparelos móveis
      - Fornecer maxima segurança, com base nas normas técnicas dos Bombeiros e nas legislações da ANP e INMETRO

2. Identificação das Partes Interessadas
   - O grupo (Caio, João e Matheus);
   - Professor orientador (José William);
   - Instituição de ensino (IFSP);
   - Estabelecimentos de médio e grande porte que realizam o consumo de gás GLP.

3. Análise SWOT (Equipe, Instituição)
   - SWOT da Instituição (IFSP)
      - Forças
         - Biblioteca
         - Acesso à ajuda do corpo docente
         - Networking com outros alunos
         - Acesso à dispositivos e ferramentas (corte à laser, impressoras 3D, etc)
         - Acesso à softwares de engenharia (Ultimate Cura, Fusion 360, Matlab, etc)
         - Acesso à materiais e ferramentas (MDF, componentes eletrônicos, ferramentas, etc)
         - Acesso à equipamentos (Notebooks. osciloscópios, geradores de função, etc)
         - Espaço produtivo para reunião dos integrantes do grupo
      - Fraquezas
         - Acesso à internet para pesquisas e desenvolvimento
         - Falta do Pacote Office para softwares de documentação e cálculo 
      - Oportunidades
         - Networking com empresas e empreendedores
      - Ameças
         - Muitas vezes faz-se necessário estar na instituição para reunir o grupo
         - O tempo dentro da instituição é pequeno no período noturno
         - Apenas dois dias da semana são considerados certos de presença do grupo na instituição
   - SWOT Caio
      - Forças
         - Boa comunicação oral e escrita
         - Experiência e conhecimento em programação de diversos tipos (Python, C/C++, Javascript...)
         - Conhecimento em versionamento de código
         - Conhecimento em gerenciamento de atividades (Scrum)
         - Experiência de trabalho em projetos científicos
      - Fraquezas
         - Pouca habilidade com desenhos mecânicos em CAD 2D/3D
         - 
      - Oportunidades
         - Aprendizado na construção de artigos científicos e divulgação
         - Networking com professores, alunos e empresas da área
         - Aprimoramento das habilidades de documentação técnica 
      - Ameaças
         - Falta de tempo disponível devido ao trabalho e outras responsabilidades pessoais
         - Divisão de responsabilidades com outros projetos acadêmicos (Drone Skybotz)
   - SWOT João
      - Forças
         - Determinação
         - Curiosidade
         - Tempo Livre
         - Criatividade
         - Desenho/projeto
      - Fraquezas
         - Disciplina
         - Memória para atividades planejadas
         - Memória para conteúdos aprendidos que vêm a ser necessários 
      - Oportunidades
         - Prática em diversas áreas de conhecimento relacionadas ao curso
         - Produto comerciável
         - Criação de uma empresa
         - Inovação no mercado
         - Adquirir experiência em vendas
         - Obter networking com personalidades influentes
      - Ameaças
         - Problemas com atenção
         - Problemas com foco 
   - SWOT Matheus
      - Forças
         - Conhecimento em desenho técnico e modelagem CAD
         - Bom trabalho em grupo
      - Fraquezas
         - Deficiência em conhecimento em C/C++ e programação em Arduíno
         - Deficiência em conhecimento relacionado a documentação de projetos
      - Oportunidades
         - Aprimoramento dos conhecimentos relacionados a programação, eletrônica e documentação de projetos
      - Ameaças
         - Ausência de tempo devido a compromissos pessoais e trabalho
5. 5W2H
   1. o que ?
      - Sistema de Monitoramento e Controle de Fluidos por Massa
   2. Por Que ?
      - O objetivo é desenvolver um sistema composto por uma base de medição, sensores, atuadores, uma central de controle e uma interface externa para garantir o monitoramento, controle e distribuição de diversos tipos de fluidos. Cada fluido possuirá um algoritmo próprio de calibração para garantia da eficiência do controle, além do monitoramento frequente e disposição dos dados para consultas e planejamento de consumo ao longo de qualquer período desejado. A parte de atuadores pode operar de acordo com a situação, seja essa de fornecimento ininterrupto, temporizado ou manual.
   3. Onde ?
      - Todo o projeto será desenvolvido nas instalações do IFSP Campus Salto, desde a projeção, prototipagem, testes e validações de sistema. Também ocorrerão pesquisas e desenvolvimentos fora do IFSP, reuniões online e presenciais.
   4. Quem
      - Caio Marcilio dos Santos, João Victor Gomes de Matos e Matheus Yuji Otaguro Neves compõe a equipe de desenvolvimento do projeto e contam com o auxílio dos professores do IFSP e possíveis fornecedores, consultoria de indústrias ou profissionais das áreas relacionadas ao projeto (enfermaria, química, restaurantes, etc)
   5. Quando ?
      - Espera-se que o protótipo seja desenvolvido ao longo do ano de 2024 com a fase inicial ocorrendo no primeiro trimestre, com o planejamento da execução, primeiras propostas de desenvolvimento e modelagem de componentes mecânicos e eletroeletrônicos. Para o segundo trimestre, ocorrerão os desenvolvimentos dos circuitos eletroeletrônicos, produção das peças mecânicas, compra de componentes, desenvolvimento de software de controle e testes iniciais de conceito. Para o segundo semestre do ano, iniciam-se os testes de integração de sistemas, validação de protótipo e todo o desenvolvimento do software de monitoramento (interface e bancos de dados). Mais ao fim do ano, no quarto trimestre, ocorrerão os testes finais de integração do sistema completo e validação.
   6. Como ?
      - A maior parte dos componentes mecânicos podem ser impressos em 3D ou cortados à laser no próprio IFSP, com ressalvas para algumas peças que podem ser compradas prontas como cases para eletrônica. A parte eletroeletrônica pode ser desenvolvida com protoboard no IFSP e depois comprada em PCB para validações mais precisas e eletrônica final. Toda a parte de software será desenvolvida com os computadores próprios ou do IFSP utilizando-se, principalmente de linguagens como Python, JavaScript, C/C++, SQL, etc
   7. Quanto vai  custar
      - Espera-se que o custo de desenvolvimento fique em torno de 600 reais ao longo do ano. Isso considerando a compra de componentes eletroeletrônicos, algumas partes mecânicas, produção das PCBs e materiais para impressão 3D e corte à laser

1. Plano de Gerenciamento do Projeto
   1. Coletar requisitos
      - Componentes mecânicos
         - MDF
         - Célula de carga
         - Válvulas solenoides
      - Coponentes eletronicos
         - Arduino
         - Esp32
         - MQTT
         - Módulo Relé
         - Regulador de tansão L8705C
      - Conhecimento em C++
      - Conhecimento em protocolo MQTT
      - Conhecimeno em mecanica
      - Conhecimanto em elétrica
      - Conhecimento em elétronica
   2. Criar a Estrutura Analítica do Projeto - EAP
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
3. Cronograma
   1. Definir as Atividades
   2. Sequenciar as Atividades
   3. Estimar duração das Atividades
   4. Desenvolver o Cronograma
4. Custos
5. Qualidade
6. Recursos
7. Comunicação
8. Riscos
9. Aquisições

## Execução

## Monitoramento e Controle

## Encerramento
