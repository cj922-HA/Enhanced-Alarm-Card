# Enhanced-Alarm-Card


**Better Lovelace Alarm Control Panel Card for Home Assistant**

***[Pictures](https://github.com/cj922-HA/Enhanced-Alarm-Card#pictures) --- [Prerequisites](https://github.com/cj922-HA/Enhanced-Alarm-Card#prerequisites) --- [Setup](https://github.com/cj922-HA/Enhanced-Alarm-Card#setup)***
 - Works with *manual* or *manual_mqtt* alarm platforms.
 - Lovelace card that changes based on conditions.
 - Visible Countdown Timer
 - Keypad hidden when not needed.
 - Works based on automations, input_boolean, counter, and of course the manual alarm.

*Upfront note: I am not a coder by any means so forgive any inefficiencies in my methods* 

 ## Pictures
 ![enter image description here](https://i.imgur.com/82WhFjl.jpg)View when disarmed

![enter image description here](https://i.imgur.com/klq30pK.jpg)View when arming

![enter image description here](https://i.imgur.com/sxe6CnV.jpg)View once armed

![enter image description here](https://i.imgur.com/TkHWnN9.jpg)View when 'disarm' button pressed. Option to close keypad if decide not to disarm.

![enter image description here](https://i.imgur.com/vyMXp1A.jpg)View when alarm is triggered - during pending state

![enter image description here](https://i.imgur.com/vv8idb4.jpg)View when alarm is triggered - triggered state

## Prerequisites

 - [Stack In Card](https://github.com/custom-cards/stack-in-card) **
 - [Config Template Card](https://github.com/iantrich/config-template-card) **
 - [Gauge Card](https://github.com/custom-cards/gauge-card) **

***Available in [HACS](https://hacs.xyz/)*

## Setup

 1. Add prerequisite lovelace resources listed above.
 2. Add required items to configuration.yaml (see [here](https://github.com/cj922-HA/Enhanced-Alarm-Card/blob/master/configuration.yaml))
 3. Add automations to automations.yaml (see [here](https://github.com/cj922-HA/Enhanced-Alarm-Card/blob/master/automations.yaml))
 4. Add Lovelace card to your dashboard (see [here](https://github.com/cj922-HA/Enhanced-Alarm-Card/blob/master/Lovelace%20card.yaml))
