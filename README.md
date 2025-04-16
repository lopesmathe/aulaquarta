# 1. Qual material utilizar no encapsulamento do sensor?
Para garantir durabilidade e precisão, recomenda-se o uso de aço inoxidável ou plástico ABS com proteção IP65. Esses materiais oferecem resistência à corrosão, proteção contra poeira e respingos de água, sendo ideais para ambientes industriais ou externos. Além disso, é crucial utilizar materiais isolantes adequados entre o sensor e o encapsulamento para evitar interferências e garantir a precisão das medições. ​
Usinainfo
Sensor-Technology

2. Qual sensor de temperatura será ideal (NTC, PT100, DS18B20)?
PT100: Oferece alta precisão e estabilidade, sendo ideal para aplicações industriais que exigem medições precisas.

DS18B20: Sensor digital de fácil integração, adequado para aplicações que não requerem alta precisão.

NTC: Termistores NTC são sensíveis e econômicos, mas menos precisos e estáveis em comparação com os anteriores.​

A escolha depende dos requisitos específicos de precisão, faixa de temperatura e ambiente de operação.​

3. Qual tecnologia de comunicação será usada (Wi-Fi, LoRa, NB-IoT)?
Wi-Fi: Adequado para ambientes com infraestrutura de rede existente, porém com maior consumo de energia.

LoRa: Ideal para longas distâncias e baixo consumo energético, mas com menor taxa de transmissão de dados.

NB-IoT: Oferece ampla cobertura e baixo consumo, sendo adequado para aplicações que exigem comunicação em áreas remotas.​

A escolha deve considerar a disponibilidade de infraestrutura, distância de transmissão e requisitos de consumo energético.​

4. Como será feita a leitura da resistência interna da bateria?
A leitura pode ser realizada utilizando um circuito de medição de tensão em carga e em repouso, calculando a resistência interna com base na diferença de tensão e corrente. É essencial garantir que o circuito de medição não interfira no funcionamento normal da bateria.​

5. Qual microcontrolador oferece o melhor custo-benefício (ESP32, STM32)?
ESP32: Oferece conectividade Wi-Fi e Bluetooth integrada, sendo ideal para aplicações que requerem comunicação sem fio e baixo custo.

STM32: Possui diversas variantes com diferentes recursos, adequado para aplicações que exigem maior controle e precisão. ​
Wikipédia, a enciclopédia livre

A escolha depende dos requisitos específicos de conectividade, processamento e custo do projeto.​

6. Qual será a frequência de leitura ideal?
A frequência de leitura deve equilibrar a necessidade de atualização dos dados e o consumo de energia. Para aplicações gerais, uma leitura a cada 5 minutos pode ser suficiente. Em ambientes críticos, leituras mais frequentes podem ser necessárias.​

7. Como definir e aplicar os limites (Gross Margin) de alerta?
Os limites de alerta devem ser definidos com base nos requisitos operacionais do ambiente monitorado. É importante considerar as tolerâncias dos sensores e as variações normais do ambiente para evitar alarmes falsos.​

8. Qual será a autonomia energética do sensor? Terá bateria própria?
A autonomia depende do consumo energético do sensor e da capacidade da bateria. Utilizar baterias de lítio de alta capacidade e implementar modos de economia de energia no microcontrolador pode aumentar significativamente a autonomia.​

9. Quais medidas de segurança serão aplicadas na comunicação?
Implementar criptografia de dados, autenticação de dispositivos e protocolos seguros de comunicação (como HTTPS ou MQTT com TLS) são medidas essenciais para garantir a segurança dos dados transmitidos.​

10. Qual será o tempo mínimo de durabilidade exigido por sensor?
A durabilidade esperada deve ser de pelo menos 5 anos, considerando a qualidade dos componentes, proteção adequada contra fatores ambientais e manutenção preventiva regular.​

11. Qual será a infraestrutura do banco de dados?
A infraestrutura pode ser baseada em servidores locais ou em nuvem, dependendo dos requisitos de acesso e escalabilidade. Bancos de dados relacionais (como MySQL) ou não relacionais (como MongoDB) podem ser utilizados conforme a necessidade de estruturação dos dados.​

12. Como será o fluxo de atualização e manutenção dos sensores em campo?
Implementar atualizações de firmware over-the-air (OTA) permite a manutenção remota dos sensores. Além disso, é importante estabelecer um cronograma de manutenção preventiva para verificar o funcionamento e a calibração dos sensores.​

13. A caixa da bateria já possui algum tipo de ventilação ou isolamento térmico?
A presença de ventilação ou isolamento térmico na caixa da bateria é crucial para manter a temperatura operacional adequada dos componentes internos, evitando superaquecimento e garantindo a precisão das medições.​

14. Qual é o espaço físico disponível dentro da caixa para instalação do sensor?
O espaço disponível deve ser suficiente para acomodar o sensor, a bateria e o microcontrolador, garantindo também a circulação de ar adequada para medições precisas de temperatura e umidade.​

15. A bateria possui terminais de teste ou será necessário adaptar o circuito de medição?
Se a bateria não possui terminais de teste, será necessário adaptar o circuito de medição para permitir a verificação da tensão e resistência interna sem comprometer a integridade da bateria.​

16. Existe risco de interferência eletromagnética no local (proximidade com transmissores, antenas, etc.)?
A proximidade com fontes de interferência eletromagnética pode afetar a precisão das medições e a comunicação do sensor. Nesses casos, é recomendável
