
# WemosGroveShield

Shield per Wemos D1 mini per collegare fino a 6 dispositivi Grove. || Simple shield to connect up to 6 Grove device to a Wemos D1 mini.

![wemos + wemos grove shield + wemos dht22 shield](https://lh3.googleusercontent.com/IFALWAMvwdYL3MG3jbF1V1DvBob4NftJKPoJILyIoyPP8xGxCnYcGC69xQ9UJdmoClr1VdT5sgC-Gr_bQU4i84TACmh_Ix7yOGzaTGgnmD3Lihv_z_XJgALvjk4tSnUcHnuPB9_Jn5s=w1483-h834-no "foto.jpg")

## Più informazioni || More info

Questo shield è predisposto per:
- collegamento di 6 connettori (preferibilmente a 90° [1] per permettere sovrapposizione di ulteriori shield)
- collegamento tramite connettori a vite di fonte esterna di tensione superiore a 5v, regolata da breakout board con MP1584EN [2]

Vengono pubblicati i piedini: A0, D1 (combinato con D2 per eventuale utilizzo della porta come I2C), D3, D5, D6, D7.
In questo modo vengono anche lasciati liberi i pin usati da shield ufficiali (es: il D4 usato dallo shield DHT22, o il D8 usato da relay shield, etc).
Abbiamo realizzato i primi prototipi con la nostra cirqoid (una cnc per pcb) e qualche test, abbiamo fatto fare un batch di pcb!

||

This shield allow you to connect:
- up to 6 connectors (better if the 90 degrees ones [1], so you can still use more shields on top of this)
- a voltage higher than 5v using a screw terminal, connected to a MP1584EN step-down module [2]

Used pins: A0, D1 (together with D2 on the same connector, so you can use it for I2C), D3, D4, D6, D7.
We have done the first prototypes with our Cirqoid (a cnc for pcb)and after a few test, we ordered a pcb batch!

![shield](https://lh3.googleusercontent.com/pA93-L_Z7GGnHA7peI-KIwlTrpuK8Iz-zYh9PnxkOZcFFdITsAEc2haMIVeeOdMEtkZtV9Kl7PtrClKk66CQ81POzDqpn34_8R7zQqVpBnfIMyqWe6oJ_l7Kx4ejRHccQ86MLjmAU3Y=w897-h505-no)

[1] https://www.seeedstudio.com/Grove---Universal-4-pin-connector-90%C2%B0%2810-PCs%29-p-790.html  
[2] https://www.amazon.it/Regolabile-Buck-Converter-Step-Pezzi/dp/B01MQGMOKI/ref=sr_1_4?rps=1&ie=UTF8&qid=1531129949&sr=8-4&keywords=MP1584EN  


## Authors
* **Mirco Piccin** -  [pictux](https://github.com/pictux)

