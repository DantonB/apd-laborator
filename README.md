# APD – Laborator
Proiect de laborator pentru disciplina Achiziția și prelucrarea datelor.
Nod de achiziție a temperaturii bazat pe Arduino Uno.
EOF

## Autor
Burcea David Antoniu - G4LF341

## Hardware
Arduino Uno R3, senzor de temperatura TMP36

## Note
Parolele si cheile de acces nu ar trebui sa ajunga niciodata intr-un repository de GIT, deoarece, chiar daca acesta este privat, odata ce este urcat pe GITHUB sau prezent pe calculatorul personal, reprezinta un risc de securitate- iar statutul de repo privat pe GITHUB s-ar putea sa fie facut public sau nu 100% securizatPlatforma: Arduino Uno R3(ATmega328P)
Lab author: Burcea David

## Parametri
SENSOR_PIN A0 // intrarea analogică a senzorului
SAMPLE_PERIOD_MS 1000 // compromis: 1s (consum redus)
SERIAL_BAUD 19200 // viteza portului serial
LED_PIN 13 // LED de stare
BUTTON_PIN 2 // buton de pornire/oprire achizitie
Sistemul suporta doua moduri:
Comunicatie seriala la 115200 baud (mod rapid, recomandat)
Comunicatie seriala la 19200 baud (mod compatibilitate)

Modificare coleg

## Senzori utilizați
| Senzor | Interfață | Domeniu |
|---|---|---|
| TMP36 | Analogic (A0) | -40°C ... +125°C |
