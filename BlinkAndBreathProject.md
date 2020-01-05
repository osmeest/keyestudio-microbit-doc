# Clignote et respire

# Aperçu

Dans ce projet, nous combinons les project [2](LedBlinkProject.md) et [3](BreathProject.md). Vous apprendrez comment controler la LED du module pour la faire clignoter deux fois, puis la faire respirer deux fois, de manière répétitive. Cette fois, nous utiliserons le module LED 3W, qui a une haute  This time we use keyestudio 3W LED module, which has high brightness and can be used as illumination.

## Composants nécessaires
- carte micro:bit
- carte de connexion keyestudio micro:bit Sensor Shield v2
- cable USB
- module keyestudio LED 3W
- 3 cable jumper Dupont

## Introduction aux composants

### Module keyestudio LED 3W

Ce module LED a une très haute luminosité car la lampe qu'il inclut a une puissance de 3W. Vous pouvez utiliser ce module pour vos projets Arduino ou d'autres projets, idéal pour les robots et les applications de recherche et secours. Par exemple, les robots intelligents peuvent utiliser ce module à des fins d'illumination.
Notez que la lumière émise par ce module ne doit pas être dirigée vers des yeux humains pour des raisons de sécurité.

![Module LED 3W](images/3wLedModule.png)

#### Specifications

- Température de couleur: 6000~7000K
- Flux lumineux: 180~210lm
- Courant: 700~750mA
- Puissance: 3W
- Angle d'illumination: 140 degree
- Température de fonctionnement: -50~80°C / de stockage: -50~100°C
- Module LED haute puissance, contrôlé par port I/O de microcontroleur
- Type de port de contrôle: numérique
- Tension d'alimentation: 3.3~5V

## Cablage du circuit

Insérez la carte micro:bit dans le Sensor Shield.
Ensuite, connectez le module LED au Sensor Shield, connectez la pin S au port S0, la pin + au port V1 et la pin - au port GND.

![Circuit](images/BlinkAndBreathCircuit.png)

## Code du programme

![Code](images/BlinkAndBreathCode.png)

## Résultats

Une fois le cablage terminé et le circuit alimenté, envoyez le programme au micro:bit, vous devriez voir la LED du module clignoter deux fois, puis "respirer" deux fois, répétitivement.

![Résultats](images/BlinkAndBreathResult.png)
