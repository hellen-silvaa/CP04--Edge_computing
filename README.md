# Projeto de IoT - Comunicação entre Sensores, API e Node-RED

Este projeto foi realizado no checkpoint 04 da matéria de **Edge Computing & Computer Systems**, ministrada pelo professor **Yan Gabriel Coelho**.
Construimos uma solução de IoT que abrange todos os conceitos de comunicação entre sensores, uma API externa, e o uso do Node-RED. Abaixo você encontrará a documentação completa, imagens do circuito e dashboards.

## Integrantes

- **Hellen Aparecida Moura Silva** - RM 559008
- **Alexia Ramalho Izidio dos Santos** - RM 558385

## Descrição do Projeto

Este projeto consiste em:
1. **Leitura de um sensor ultrassônico**: O Arduino foi utilizado para ler um sensor ultrassônico a cada 2000ms. Os valores lidos são disponibilizados na porta serial e são exibidos tanto no console de depuração (DEBUG) quanto em um dashboard criado no Node-RED.
   
2. **Dashboards de cidades diferentes usando API OpenWeatherMap**: Dois dashboards no Node-RED que mostram informações meteorológicas de São Bernardo do Campo e Dubai usando a API do OpenWeatherMap. As informações incluem:
   - Temperatura atual (em Fahrenheit)
   - Pressão
   - Nível do mar
   - Nuvens
   - Nível da terra

## Componentes Utilizados

- **Sensor Ultrassônico**: Sensor para medir a distância e imprimir essa informação no Node-RED.
- **Node-RED**: Utilizado para criar o dashboard e visualizar os dados do sensor e da API do OpenWeatherMap.
- **API OpenWeatherMap**: API externa para obter informações meteorológicas de diferentes cidades.
- **Protoboard**: Utilizada para montagem do circuito.
- **Fios de Conexão**: Utilizados para conectar os componentes na protoboard e ao Arduino.

. **Dashboards**:
   - Acesse os dashboards através do Node-RED para visualizar as leituras do sensor e as informações meteorológicas das duas cidades.

## Imagens e Arquivos

### 1. Imagem do Circuito (Físico)

![Imagem do Circuito](link_para_imagem_do_circuito)



### 2. Fluxo Node-RED (.JSON)

![image](https://github.com/user-attachments/assets/4d65ed69-e76e-44df-989e-7b4990a8d0c0)

### 2. Fluxo Node-RED (DASHBOARD )

### 3.1 BIBLIOTECAS UTILIZADAS 
![bibliotecas](https://github.com/user-attachments/assets/dc859414-88c4-4fc1-9f80-6fa76d80f267)



### 4. Dashboards (Capturas de Tela)

- **Dashboard de Dados do Sensor Ultrassônico**:
  ![Dashboard Sensor](link_para_dashboard_sensor)

- **Dashboards das Cidades**:
  - Cidade 1: ![Dashboard Cidade 1](link_para_dashboard_cidade1)
  - Cidade 2: ![Dashboard Cidade 2](link_para_dashboard_cidade2)


### 3.Código ultrassonico 

![image](https://github.com/user-attachments/assets/d830e8dd-5c8c-4279-9aa5-975da5a0823e)





## Considerações Finais

Este projeto demonstra a integração de sensores de hardware com softwares de automação e APIs externas, proporcionando uma experiência prática em IoT e visualização de dados.
