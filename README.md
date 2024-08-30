# Projeto de IoT - Comunicação entre Sensores, API e Node-RED

Este projeto foi realizado no checkpoint 04 da matéria de **Edge Computing & Computer Systems**, ministrada pelo professor **Yan Gabriel Coelho**.
Construimos uma solução de IoT que abrange todos os conceitos de comunicação entre sensores, uma API externa, e o uso do Node-RED. Abaixo você encontrará a documentação completa, imagens do circuito e dashboards.

## Integrantes

- **Hellen Aparecida Moura Silva** - RM 559008
- **Alexia Ramalho Izidio dos Santos** - RM 558385

## Descrição do Projeto

Este projeto consiste em:
1. **Leitura de um sensor ultrassônico**: Um único código em Arduino é utilizado para ler um sensor ultrassônico a cada 3000ms. Os valores lidos são disponibilizados na porta serial e são exibidos tanto no console de depuração (DEBUG) quanto em um dashboard criado no Node-RED.
2. **Dashboards de cidades diferentes usando API OpenWeatherMap**: Dois dashboards no Node-RED que mostram informações meteorológicas de São Bernardo e Itaquera usando a API do OpenWeatherMap. As informações incluem:
   - Temperatura atual (em Fahrenheit)
   - Pressão
   - Nível do mar
   - Nuvens

## Componentes Utilizados

- **Sensor Ultrassônico**: Sensor para medir a distância e refletir essa informação no Node-RED.
- **Node-RED**: Utilizado para criar o dashboard e visualizar os dados do sensor e da API do OpenWeatherMap.
- **API OpenWeatherMap**: API externa para obter informações meteorológicas de diferentes cidades.
- **Protoboard**: Utilizada para montagem dos circuitos eletrônicos de forma prática e sem necessidade de solda.
- **Fios de Conexão**: Utilizados para conectar os componentes na protoboard e ao Arduino.

. **Dashboards**:
   - Acesse os dashboards através do Node-RED para visualizar as leituras do sensor e as informações meteorológicas das duas cidades.

## Imagens e Arquivos

### 1. Imagem do Circuito (Físico)

![Imagem do Circuito](link_para_imagem_do_circuito)

**Descrição dos Componentes**:
- Sensor Ultrassônico: Modelo XYZ
- Arduino: Modelo UNO R3
- Fios de Conexão
- Protoboard

### 2. Imagem do Circuito (Simulado)
![img2](https://github.com/user-attachments/assets/86e41754-eb9a-4122-9ec3-bae0d33b6ba1)


### 3. Fluxo Node-RED (.JSON)

Link para o arquivo JSON: [node-red-flow.json](link_para_arquivo_json)

### 4. Dashboards (Capturas de Tela)

- **Dashboard de Dados do Sensor Ultrassônico**:
  ![Dashboard Sensor](link_para_dashboard_sensor)

- **Dashboards das Cidades**:
  - Cidade 1: ![Dashboard Cidade 1](link_para_dashboard_cidade1)
  - Cidade 2: ![Dashboard Cidade 2](link_para_dashboard_cidade2)


### 3.Código ultrassonico 

![codeEDGE](https://github.com/user-attachments/assets/3bd2f8c1-0c38-4f1b-83e1-976eb45f70c8)


## Como Executar

1. Certifique-se de ter o Arduino IDE instalado para programar o Arduino.
2. Carregue o código fornecido no Arduino e conecte o dispositivo ao computador.
3. Importe e configure o fluxo no Node-RED.
4. Abra os dashboards no navegador para visualizar os dados.

## Considerações Finais

Este projeto demonstra a integração de sensores de hardware com softwares de automação e APIs externas, proporcionando uma experiência prática em IoT e visualização de dados.

Se tiver dúvidas, entre em contato com qualquer um dos integrantes do projeto.
