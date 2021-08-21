# Esp32Mega
Sistema de Automação de Médio Porte com 64 portas configuráveis como entrada ou saída.
<br>
Este projeto foi pensado para pessoas interessadas em montar sua própria automação residencial ou industrial, porém com pouca prática em confecção de placas.
<p>
O Sistema completo conta com uma placa principal (CPU), oito placas optoacopladoras para proteção da CPU e placas para conexão com módulos de 8 relés.
  

 <h3> Principais características: </h3>
 - 8 módulos com 8 portas configuráveis como entrada ou saída (multiplo de 8), ou seja, 64 portas disponíveis para automação;
 <br> - Fácil programação via Arduino IDE (utiliza um ESP32 e aum Arduino Mega);
 <br> - Controle via WIFI ou Bluetooth (de acordo com a programação do usuário);
 <br> - Testado com MQTT e acesso via OpenHab e Homeassistant;
 <br> - Fácil implementação de controle por comando de voz (Alexa e Google Home);
 <br> - Sistema de RF 433 MHz disponível para controle de portões e cortinas automáticas;
 <br> - Fácil manutenção pois todas as conexões dos cabos utilizam conectores RJ45;
 <br> - Controladores (ESP32 e Arduino Mega Pro) conectados por encaixe na CPU;
 
<h2> Placa finalizada </h2>
  <img src="https://github.com/Packduino/Esp32Mega/blob/main/Sistema_ok.png" alt="Sistema Completo" width="600" height="600">
<h2> Projetos dos PCBs </h2>
<table border="1">
    <tr>
        <td>Placa</td>
        <td>Projeto</td>
        <td>PCB Pronto</td>
    </tr>
    <tr>
        <td>CPU</td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_CPU_clean.png" alt="CPU 3D" width="400" height="400"></td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_CPU_foto.png" alt="CPU REAL" width="400" height="400"></td>
    </tr>
    <tr>
        <td>Opto Acoplador</td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_OPTO_clean.png" alt="OPTO 3D" width="200" height="130"></td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_OPTO_foto.png" alt="OPTO REAL" width="200" height="130"></td>
    </tr>
    <tr>
        <td>Conector Relé</td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_RELE_clean.png" alt="OPTO 3D" width="200" height="200"></td>
        <td><img src="https://github.com/Packduino/Esp32Mega/blob/main/Esp32Mega_RELE_FOTO.png" alt="OPTO REAL" width="200" height="200"></td>
    </tr>
</table>
