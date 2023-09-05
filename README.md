# ESP32_ESPNOW_RSSI

This works on two ESP32s and is partly based on the examples from the ESP32 course by [Sara & Rui Santos](https://randomnerdtutorials.com)

The idea is to read digital inputs and temperature from the "transmitter" and pass them to the "receiver" by using Espressif's ESP_NOW protocol and then display the receiving result on LEDs and an OLED display.

There is a particular LED that indicates if the receiver "listens" to the transmitter (when it is on) and I added a last line to the OLED with the RSSI data of the received packet.

I have tested it in the field and indeed when I move away from the "transmitter" the RSSI value increases (as it should be) and when I get closer, it decreases.

This code contains copied and pasted parts taken from the ESP32 Espressif forum, based on the idea of ​​https://www.esp32.com/viewtopic.php?t=13889 and partially modified.

I hope my code is understandable...

If you find this information useful and interesting, invite me for a coffee!!!
https://cafecito.app/marce_ferra

If you found this information useful and interesting, buy me a cafecito!!!
https://www.buymeacoffee.com/marceferra
