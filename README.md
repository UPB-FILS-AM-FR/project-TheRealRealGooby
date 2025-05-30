MASINUTA CU TELECOMANDA BLUETOOTH CU MOD AUTONOM DE EVITARE AL OBSTACOLELOR

Bucur Gabriel

Proiectul meu va fi o masinuta cu telecomanda care poate fi controlata din telefon, prin bluetooth sau autonom printr-un sistem de evitare al obstacolelor (modul de control manual/autonom va fi semnalat printr-un LED de pe masinuta).
Am optat pentru acest tip de proiect deoarece consider ca ar necesita o constructie mai antrenanta si mai dinamica a unei jucarii distractive, care mi-ar solidifica bazele programarii microprocesoarelor. De asemenea, fiind un proiect 
comun la nivelul de incepator, voi avea

Arhitectura proiectului:
1. Mod manual (joystick)
Comenzile sunt trimise prin Bluetooth (de pe telefon):

F = Înainte

B = Înapoi

L = Viraj stânga

R = Viraj dreapta

S = Stop

2. Mod autonom (evitarea obstacolelor)
Activare: trimiți caracterul V

Dezactivare: trimiți caracterul v

În mod autonom:

Dacă obstacolul este mai departe de 10 cm → mașina merge înainte

Dacă obstacolul e mai aproape → se oprește, virează dreapta, apoi continuă

Conexiuni fizice
--Motoare și driver L298N
ENA → pin digital 8 Arduino

IN1 → pin 4

IN2 → pin 5

IN3 → pin 6

IN4 → pin 7

ENB → pin 9

Driver alimentat de baterii (6V), GND comun cu Arduino

--Senzor HC-SR04
Trig → pin digital 11

Echo → pin digital 10

VCC → 5V de la Arduino

GND → GND Arduino

--Modul Bluetooth HC-05
TX → pin 0 (RX Arduino)

RX → pin 1 (TX Arduino)

VCC → 5V

GND → GND Arduino

Componente:
Kit Plusivo Microcontroller Starter – conține un Arduino, fire, rezistențe, LED-uri și alte componente necesare pentru prototipare și testare. - 75RON

Șasiu cu roți, suport baterii AA și motoare galbene – baza mecanică a mașinuței, cu motoare pentru deplasare și loc pentru alimentare. - 50RON

Modul Driver Motoare Dual L298N – controlează direcția și viteza motoarelor de curent continuu. - 11RON

Suport pentru senzorul ultrasonic HC-SR04 – permite montarea stabilă a senzorului de distanță pe mașinuță. - 5RON

Senzor ultrasonic HC-SR04 – detectează obstacole în fața mașinii măsurând distanța până la ele. - inclus in kit-ul Plusivo Microcontroller Starter

Modul Bluetooth HC-05 cu adaptor – permite controlul mașinuței de pe telefon prin conexiune Bluetooth. - 28RON

Suport pentru 4 baterii AA – asigură alimentarea electrică a întregului sistem mobil. - inclus in sasiul cu roti

Libraries:
Pentru programarea componentelor hardware NU AM FOLOSIT BIBLIOTECI EXTERNE ci doar BIBLIOTECA STANDARD Arduino.h

Bibliografie:
https://www.youtube.com/watch?v=eNxc_FnlDY0&t=354s
https://www.youtube.com/watch?v=zYl6MCKW5Ec
https://www.youtube.com/watch?v=A33Dxrkd-WQ
https://chat.deepseek.com/
