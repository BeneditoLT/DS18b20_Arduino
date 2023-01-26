O DS18B20 é um sensor de temperatura digital de alta precisão que utiliza a interface 1-Wire para se comunicar com o microcontrolador. Ele é capaz de medir temperaturas de -55°C a +125°C com uma precisão de ±0,5°C. Ele é projetado para ser usado em ambientes com baixa corrente e é resistente à água. Ele pode ser usado para medir a temperatura em uma ampla variedade de aplicações.


https://produto.mercadolivre.com.br/MLB-2643548686-sensor-temperatura-ds18b20-18b20-arduino-eletrokits-_JM




Para usar o sensor de temperatura DS18B20 com o Arduino, siga os seguintes passos:

1 - Comece baixando e instalando a biblioteca OneWire e DallasTemperature para o Arduino. Você pode fazer isso através do gerenciador de bibliotecas na interface do Arduino.
    ou travez dos links:
    
    https://github.com/PaulStoffregen/OneWire
    
    https://github.com/milesburton/Arduino-Temperature-Control-Library
    
    
2 - Conecte o sensor DS18B20 à sua placa Arduino. O sensor tem três pinos: VCC, GND e DQ. Conecte o pino VCC ao pino 3,3V ou 5V da sua placa Arduino, o pino GND ao pino GND da sua placa Arduino e o pino DQ ao pino digital de sua escolha (neste exemplo vou utilizar o pino 2).

3 - Abra o Arduino IDE e crie um novo sketch. No início do sketch, inclua as seguintes linhas de código para incluir as bibliotecas necessárias e criar as variáveis ​​necessárias:

![Captura de tela de 2023-01-26 10-55-45](https://user-images.githubusercontent.com/46333024/214854103-7f1479bb-04f1-4558-aa1c-ec0ef185c9e8.png)


4 - No setup() do seu sketch, adicione o seguinte código para inicializar o sensor e o monitor serial:


![Captura de tela de 2023-01-26 10-56-24](https://user-images.githubusercontent.com/46333024/214854580-5fcbe35b-0818-43fc-984c-5fd9befbd7f8.png)

5 - No loop() do seu sketch, adicione o seguinte código para ler a temperatura do sensor e imprimi-la no monitor serial:

 ![Captura de tela de 2023-01-26 10-56-47](https://user-images.githubusercontent.com/46333024/214854616-bebcfc7b-1917-4f13-8dc3-653cb6a3feb9.png)
 
6 - Faça upload do seu sketch para a placa Arduino e abra o monitor serial para ver a temperatura sendo exibida.

7 - Você também pode fazer ajustes no sketch para exibir a temperatura em Fahrenheit, incluir métodos de tratamento de erro, etc.

Lembre-se de verificar se você tem as portas serial corretas configuradas no seu computador antes de carregar o sketch e abrir o monitor serial.


![codigo](https://user-images.githubusercontent.com/46333024/214854651-6d7f674a-8f28-421b-8650-92dfa4af6d15.png)

![ds18b20_2](https://user-images.githubusercontent.com/46333024/214856681-41e5e658-c7ad-408c-9d35-342eab077b08.png)

