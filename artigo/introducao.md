# Introdução

## 1. Contexto

O Sistema de Monitoramento de Fluidos por Massa (SMFM) situa-se na grande área da **Internet das Coisas (IoT) aplicada a sistemas industriais de monitoramento e controle**, especificamente no domínio de instrumentação e automação para medição de massa e peso em tempo real. Este trabalho integra conceitos de engenharia eletrônica, sistemas embarcados, comunicação sem fio e desenvolvimento de software para criar uma solução completa de monitoramento remoto.

A importância desta área de pesquisa manifesta-se em múltiplas dimensões. Primeiro, do ponto de vista **econômico e industrial**: o mercado global de IoT industrial está projetado para crescer a uma taxa anual composta de 23,3% de 2025 a 2030, alcançando USD 1,693.44 bilhões até 2030, demonstrando a crescente demanda por soluções IoT em ambientes industriais. Segundo, do ponto de vista **tecnológico**: IoT está transformando balanças industriais em dispositivos inteligentes e conectados que permitem dados em tempo real, análises e manutenção preditiva. Terceiro, do ponto de vista **operacional**: sistemas de monitoramento de peso e massa são fundamentais em diversos setores industriais, desde controle de processos químicos até logística e gestão de estoque, onde a precisão e disponibilidade de dados em tempo real impactam diretamente na eficiência operacional e na tomada de decisões.

## 2. Lacuna Identificada

Apesar do crescimento significativo no desenvolvimento de sistemas IoT para monitoramento industrial, existem lacunas importantes que ainda não foram adequadamente abordadas na literatura e nas soluções comerciais disponíveis:

### 2.1 Limitações dos Sistemas Atuais

A revisão da literatura revela que a maioria dos projetos de sistemas de pesagem IoT são **prototípicos e de escala limitada**, focando principalmente em demonstrações conceituais com capacidades de carga reduzidas (tipicamente até 5kg) e aplicações domésticas ou semi-profissionais. Conforme observado nos estudos analisados, os sistemas existentes utilizam principalmente ESP8266 ou ESP32 com células de carga HX711 para aplicações básicas de pesagem, mas carecem de características essenciais para aplicações industriais robustas.

### 2.2 Gaps Específicos Identificados

**Ausência de sistemas multi-balança integrados**: Os sistemas atuais são predominantemente mono-balança, não oferecendo soluções para monitoramento simultâneo e coordenado de múltiplas estações de pesagem com controle centralizado e distribuído.

**Limitações na arquitetura de comunicação**: 74% das empresas pesquisadas já implantaram ou estão desenvolvendo uma estratégia de IIoT, porém os sistemas de pesagem IoT não acompanharam essa evolução, mantendo arquiteturas de comunicação simplificadas que não atendem aos requisitos de confiabilidade, escalabilidade e integração empresarial.

**Falta de framework unificado**: Não existe um framework abrangente que integre hardware, firmware, comunicação MQTT e interface de usuário em uma solução coesa e reutilizável para diferentes contextos industriais.

**Ausência de análise de desempenho e validação industrial**: A literatura carece de estudos que avaliem sistematicamente o desempenho, confiabilidade e aplicabilidade destes sistemas em ambientes industriais reais, com análise de métricas como latência, precisão, disponibilidade e robustez.

## 3. Estado da Arte/Técnica

### 3.1 Tecnologias de Sensoriamento

O estado atual da técnica em sensoriamento de peso para aplicações IoT baseia-se principalmente em **células de carga (load cells) com extensômetros** acopladas a amplificadores de precisão. As células de carga funcionam baseadas na deformação mecânica que gera uma variação na resistência elétrica, convertida em um sinal elétrico proporcional ao peso aplicado. O HX711 é um conversor analógico-digital (ADC) de alta precisão projetado para amplificar e digitalizar esses sinais fracos.

### 3.2 Plataformas de Microcontroladores

Na indústria, o **ESP32** emergiu como a plataforma dominante para aplicações IoT de monitoramento, oferecendo conectividade Wi-Fi/Bluetooth integrada, processamento dual-core e capacidades de comunicação robustas. A arquitetura ESP32 permite implementação de sistemas de pesagem digital com precisão adequada para aplicações industriais, suportando comunicação sem fio e interfaces de usuário avançadas.

### 3.3 Protocolos de Comunicação IoT

O protocolo **MQTT (Message Queuing Telemetry Transport)** estabeleceu-se como padrão de facto para comunicação IoT industrial devido à sua eficiência em ambientes com largura de banda limitada e sua arquitetura publish-subscribe que facilita a escalabilidade. Sistemas avançados utilizam MQTT em arquiteturas distribuídas com Node-RED para roteamento de dados entre diferentes plataformas de monitoramento.

### 3.4 Tendências Tecnológicas Emergentes

As tendências de IIoT para 2025 incluem edge computing para análise de dados local, integração de inteligência artificial para manutenção preditiva, e desenvolvimento de protocolos padronizados para melhor integração com sistemas existentes. Adicionalmente, quase metade dos profissionais está integrando aplicações de Machine Learning e AI em suas estratégias de IIoT.

### 3.5 Limitações dos Sistemas Comerciais

Os sistemas comerciais disponíveis, embora tecnicamente avançados, apresentam limitações significativas: alto custo de implementação, dependência de plataformas proprietárias, dificuldade de customização para aplicações específicas, e falta de flexibilidade para integração com sistemas legados.

## 4. Propósito (Objetivo)

### 4.1 Objetivo Principal

Este trabalho tem como objetivo **desenvolver, implementar e validar um sistema IoT integrado para monitoramento de fluidos por massa**, abrangendo desde a concepção do hardware até a implementação da interface de usuário, criando um framework completo e escalável para aplicações industriais de monitoramento de peso em tempo real.

### 4.2 Objetivos Específicos

**Desenvolvimento de arquitetura hardware/firmware**: Projetar e implementar um sistema baseado em ESP32 e células de carga HX711 capaz de gerenciar múltiplas estações de pesagem com comunicação MQTT robusta e confiável.

**Criação de framework de software**: Desenvolver uma solução de software completa incluindo firmware embarcado otimizado, sistema de comunicação MQTT, e interface de usuário Python/PyQt5 para monitoramento e controle remoto.

**Validação experimental**: Realizar testes extensivos de desempenho, precisão, latência e confiabilidade do sistema em cenários que simulem condições industriais reais.

**Análise comparativa**: Avaliar o sistema desenvolvido em relação a soluções existentes, quantificando melhorias em termos de custo-benefício, flexibilidade, e capacidades técnicas.

### 4.3 Contribuições para a Academia

**Contribuição metodológica**: Apresentação de uma metodologia integrada para desenvolvimento de sistemas IoT industriais de monitoramento, desde a concepção do hardware até a validação experimental, que pode ser replicada e adaptada para outras aplicações similares.

**Contribuição técnica**: Desenvolvimento de um framework open-source completo que preenche a lacuna identificada entre protótipos acadêmicos e soluções comerciais, oferecendo uma alternativa flexível e customizável para implementação em diferentes contextos industriais.

**Contribuição científica**: Análise quantitativa e qualitativa abrangente do desempenho de sistemas IoT de pesagem industrial, fornecendo dados empíricos sobre métricas de performance que podem orientar futuras pesquisas e desenvolvimentos na área.

**Contribuição para a formação**: Criação de um material educacional prático que integra conceitos teóricos de IoT, sistemas embarcados, comunicação sem fio e desenvolvimento de software, contribuindo para a formação de profissionais na área de engenharia eletrônica e sistemas IoT industriais.

O desenvolvimento deste sistema contribui para o avanço do conhecimento na área de IoT industrial, oferecendo uma solução prática, validada e documentada que pode servir como base para futuras pesquisas e desenvolvimentos comerciais no setor de automação e monitoramento industrial.

---

### Referências
[Referências da Introdução](../trabalho_academico/referencias_introducao.md)