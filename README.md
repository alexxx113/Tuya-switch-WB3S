# Tuya switch WB3S WB2S WB2L

<p>
Configure tuya switch OpenBK7231T
</p>
<img src="https://github.com/Alexxx113/Tuya-switch-WB3S-WB2S-WB2L/blob/main/IMG_20220716_015555.jpg" alt="альтернативный текст" />
<p></p>
<b>Flashing for BK7231T</b>

<p>remove smd components</p>
<img src="https://github.com/Alexxx113/Tuya-switch-WB3S-WB2S-WB2L/blob/main/firmware%20remowe.jpg" alt="альтернативный текст" />
<p></p>
<p>Go to pages firmware instruction</p>


<a name="идентификатор">[OpenBK7231T_App]https://github.com/openshwprojects/OpenBK7231T_App</a>

<p></p>
<p>connect uart 3.3v !!!!</p>
<img src="https://github.com/Alexxx113/Tuya-switch-WB3S-WB2S-WB2L/blob/main/firmware uart contacts.jpg" alt="альтернативный текст" />

<p></p>
<p>configure module:</p>
<p></p>
<p>P1 wifi_led_n 0</p>
<p>P9 rel 1</p>
<p>P10 btn 1</p>

<p>if you want add temp sensor:</p>
<p>P23 adc 2</p>
<p>NTC thermistor a B value of 3950 100k</p>
<p>resistor 20k</p>

