## What this about
This repository contains the design files for my 18650 and single cell Li-Po charger which also consists of load-shring circuitry, and a buck/boost converter (3.3V/5.0V, 500mA output) with very low quiescent current (20uA).

![18650 battery charger PCB with load sharing and buck/boost converter](https://www.e-tinkers.com/wp-content/uploads/2025/08/18650_battery_charger_PCB.jpg)

## The motivation
All the 18650 battery chargers that can be found from AliExpress have serious design faults, and the 18650 battery is safer to be used with the protection circuit permanently attached to it. With the modification added to 18650, the commercial available battery holders for 18650 no longer fit. So I decided to design my own charger with custom 18650 battery holder to fit the modified battery, and add a low quiescent current buck/boost converter with 3.3V/5V output that I can used for my electronic projects.

![add protection circuit permanently to 18650 battery](https://www.e-tinkers.com/wp-content/uploads/2025/08/add_protection_circuit_permanently_to_18650_battery.png)

## The design goals
1. On-board 18650 battery holder able to fit standard 18650 and modified one;
2. USB Type C power input port;
3. Capable to charge either 18650 battery and Li-Po battery (via JST connector);
4. Battery Protection for standard 18650 battery;
5. Load-sharing circuitry so it can power the load while charging;
6. Boost/Buck converter capable to deliver 500mA power with either 3.3V or 5V output;
7. Low quiescent current for IoT application.

Read more in details about the design considerations from my [blog post](https://www.e-tinkers.com/2025/08/design-my-own-tp4056-li-ion-charger-and-iot-power-supply-subsystem/).

