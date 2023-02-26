# 12v-actuators-pcb
 Carte "pneuma" du robot l'équipe Goldorak

## Specs composants carte actionneurs 12V
- Fuse holder keystone 3557-2
- D2PAK for p-channel mosfet ( https://fr.rs-online.com/web/p/transistors-mosfet/7105014 )
- STM32 uC: STM32F042K6 MCU sur carte de développement compatible pinout Arduino Nano
- 3 esc modules on board 15A
- 2 esc 35 off-board signal + alim, connecteur imposé
- Capteurs de pression, double emprunte
- Passer le 12V au pont en H, connecteur imposé
- Entrée NTC 100k piston compresseur -> uC

## Specs générales
- Tout doit être en Français de préférence
- Passer de Batt\_12V\_P à PWR12 avec fusible + arrêt d'urgence
- 5V fourni en externe (a découpler) + common mode choke?
- Échéance du draft le dimanche 26 février

## Taille de la PCB (estimation)

![estimation de la taille de la pcb pneuma](./images/estimation_taille_pcb.png)

_Dimensions en mm_

## Place dans l'architecture générale

![carte pneuma dans l'architecture générale](./images/goldorak_elec_architecture.jpeg)
