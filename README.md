# Projeto de IoT - Comunicação entre Sensores, API e Node-RED

Este projeto envolve a construção de uma solução de IoT que abrange todos os conceitos de comunicação entre sensores, uma API externa, e o uso do Node-RED. Abaixo você encontrará a documentação completa, imagens do circuito, fluxos, dashboards, e as instruções para replicar o projeto.

## Integrantes

- **Hellen Aparecida Moura Silva** - RM 559008
- **Alexia Ramalho Izidio dos Santos** - RM 558385

## Descrição do Projeto

Este projeto consiste em:
1. **Leitura de um sensor ultrassônico**: Um único código em Arduino é utilizado para ler um sensor ultrassônico a cada 3000ms. Os valores lidos são disponibilizados na porta serial e são exibidos tanto no console de depuração (DEBUG) quanto em um dashboard criado no Node-RED.
2. **Dashboards de cidades diferentes usando API OpenWeatherMap**: Dois dashboards no Node-RED que mostram informações meteorológicas de duas cidades diferentes usando a API do OpenWeatherMap. As informações incluem:
   - Temperatura atual (em Fahrenheit)
   - Pressão
   - Nível do mar
   - Nuvens

## Componentes Utilizados

- **Sensor Ultrassônico**: Sensor para medir a distância e refletir essa informação no Node-RED.
- **Node-RED**: Utilizado para criar o dashboard e visualizar os dados do sensor e da API do OpenWeatherMap.
- **API OpenWeatherMap**: API externa para obter informações meteorológicas de diferentes cidades.

## Instruções de Configuração

1. **Montagem do Circuito**: Siga o diagrama de montagem física ou simulada do circuito. Certifique-se de conectar o sensor ultrassônico corretamente ao Arduino.
2. **Código Arduino**:
   - Faça o upload do código `sensor-ultrassonico.ino` para o Arduino.
   - O código lê o sensor ultrassônico a cada 3000ms e envia os dados para a porta serial.

3. **Configuração do Node-RED**:
   - Importe o fluxo `node-red-flow.json` para o Node-RED.
   - Configure a API Key do OpenWeatherMap no fluxo importado.
   - Certifique-se de que o Node-RED está configurado para ler os dados da porta serial correta do Arduino.

4. **Dashboards**:
   - Acesse os dashboards através do Node-RED para visualizar as leituras do sensor e as informações meteorológicas das duas cidades.

## Imagens e Arquivos

### 1. Imagem do Circuito (Físico/Simulado)

![Imagem do Circuito](link_para_imagem_do_circuito)

**Descrição dos Componentes**:
- Sensor Ultrassônico: Modelo XYZ
- Arduino: Modelo UNO R3
- Fios de Conexão
- Protoboard

### 2. Fluxo Node-RED (.JSON)

Link para o arquivo JSON: [node-red-flow.json](link_para_arquivo_json)

### 3. Dashboards (Capturas de Tela)

- **Dashboard de Dados do Sensor Ultrassônico**:
  ![Dashboard Sensor](link_para_dashboard_sensor)

- **Dashboards das Cidades**:
  - Cidade 1: ![Dashboard Cidade 1](link_para_dashboard_cidade1)
  - Cidade 2: ![Dashboard Cidade 2](link_para_dashboard_cidade2)

## Como Executar

1. Certifique-se de ter o Arduino IDE instalado para programar o Arduino.
2. Carregue o código fornecido no Arduino e conecte o dispositivo ao computador.
3. Importe e configure o fluxo no Node-RED.
4. Abra os dashboards no navegador para visualizar os dados.

## Considerações Finais

Este projeto demonstra a integração de sensores de hardware com softwares de automação e APIs externas, proporcionando uma experiência prática em IoT e visualização de dados.

Se tiver dúvidas, entre em contato com qualquer um dos integrantes do projeto.
