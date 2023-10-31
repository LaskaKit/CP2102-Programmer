![LaskaKit CP2102 Programmer](https://github.com/LaskaKit/CP2102-Programmer/raw/main/img/LaskaKit-CP2102-Programmer-1.jpg)

# Univerzální programátor s USB-UART převodníkem CP2102 určený k nahrávání firmware (nejen) do vývojových stavebnic LaskaKit. 

Pokud hledáš jednoduchý a levný programátor - USB-UART převodník - který můžeš použít s tvou či naší deskou s ESP32, ESP8266 nebo ESP32-C3, pak bys neměl přehlédnout právě tento. Tento převodník však můžete použít i pro desky jako je Arduino Mini, Mini Pro a to díky přepínači mezi 5V a 3.3V napájením, který na programátoru máme.

Programátor je založen na známém a odzkoušeném čipu CP2102. Na desce je také přepínač, kterým volíš jak napětí na pinu VCC, tak logickou úroveň sběrnice. Přepínač můžeš přepnout buď na 5V či 3.3V. Dalším přepínač umožňuje úplně vypnout odpojit napětí od VCC pinu.

![LaskaKit CP2102 Programmer](https://github.com/LaskaKit/CP2102-Programmer/raw/main/img/LaskaKit-CP2102-Programmer-3.jpg)

S naším programátorem se také vyhneš neustálemu problému s hledáním vhodného kabelu. Buď použiješ kabel s microUSB konektorem nebo USB-C - prostě to, co máš po ruce.

CP2102 programátor má pinout stejný jako mají všechny naše vývojové desky programovatelné v Arduino IDE/PlatformIO aj. Můžeš jej ale použít i samostatně s tvou vlastní deskou či deskou jiného výrobce. 

Programátor má tři indikační LED - první signalizuje připojené napájení, druhá komunikaci na RX a třetí komunikaci na TX lince UART sběrnice. 

Maximální výstupní proud při přepnutí 3.3V výstupu je 500mA, což je dostatečný proud pro napájení nejrůznějších desek od Arduino Uno až po desky s ESP32 či ESP8266.

Kromě UART sběrnice a napájení jsou na konektoru k dispozici i piny DTR a RTS, ty se běžně používají pro přepnutí Wi-Fi a Bluetooth modulů ESP32 a ESP8266 do bootloader módu.

Instalační soubor najdeš na https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers

K zakoupení je na naší stránce https://www.laskakit.cz/prevodnik-6pin-microusb-ttl-uart--cp2102--dtr-pin/
