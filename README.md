# Projeto de IoT - Comunicação entre Sensores, API e Node-RED

Este projeto foi realizado no checkpoint 04 da matéria de **Edge Computing & Computer Systems**, ministrada pelo professor **Yan Gabriel Coelho**.
Construimos uma solução de IoT que abrange todos os conceitos de comunicação entre sensores, uma API externa, e o uso do Node-RED. 

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
- **Arduino**: Utilizada para processar as informações.

. **Dashboards**:
   - Acesse os dashboards através do Node-RED para visualizar as leituras do sensor e as informações meteorológicas das duas cidades.

## Imagens e Arquivos

### 1. Imagem do Circuito (Físico)


![AD](https://github.com/user-attachments/assets/af1d4369-a9dc-4df2-a784-d93abb371ba5)

### 2. Fluxo Node-RED (.JSON)

![imagem](https://github.com/user-attachments/assets/de595fe5-99e7-4f71-8ec3-147d4893da31)

### 2.1 BIBLIOTECAS UTILIZADAS 
![bibliotecas](https://github.com/user-attachments/assets/dc859414-88c4-4fc1-9f80-6fa76d80f267)

### 2.2 FUNÇÃO UTILIZADA PARA CONVERTER PARA FAHRENHEIT:
![FSFGD](https://github.com/user-attachments/assets/7d592349-e333-42b0-9d58-870f49c9c68a)


### 3. Fluxo Node-RED (DASHBOARD - SÃO BERNARDO DO CAMPO)

![SAO BERNARDO](https://github.com/user-attachments/assets/767de49e-e82e-41f4-a247-f7cb6a13a010)

### 3.1 Fluxo Node-RED (DASHBOARD - DUBAI)

![DUBAI](https://github.com/user-attachments/assets/9b9a941f-17ff-4d31-8577-dc22231135a9)



### 4. Dashboards (Capturas de Tela)

- **Dashboard de Dados do Sensor Ultrassônico**:
  ![Dashboard Sensor](link_para_dashboard_sensor)



### 4.1 Código ultrassonico 

![image](https://github.com/user-attachments/assets/d830e8dd-5c8c-4279-9aa5-975da5a0823e)

