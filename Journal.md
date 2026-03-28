# Resolution week 1 - Hardware
I tried to use Capacitors and Diodes to build a circuit that has 6 leds that light up seqentually. Why? Becouse i couldn think of anything else.

## 14.3.2026
Firstly i followed the tutorial.
Once i was done with the tutorial i started looking for interesting circuits that used RC timing, after i saw a few of them i started experimenting in falstad, first just with one led, but it didnt work since i was putting the resistor in series with the C, but when i put the resistor in parallel with the C it worked, after i got it working with 1 led I tried doing it with 2 leds or 'cells' but that didnt work anymore since the C from the second LED just started powering the first LED so i had to use diodes to prevent that from happening. Since I made it work with 2 leds i used 3 leds to form 3 'cells'.
> The diodes will prevent the capacitor from powering the previous Led while the capacitor acts as both a power bank and a delay.

<img width="600" height="339" alt="EmPau" src="https://github.com/user-attachments/assets/dc2ace11-b4f5-46c7-b828-78f68e88df9b" />  

> In the end i had a Chain of 3 Leds turning on seqentually but it didnt look the best.

### Time spent: 1.5 H

## 15.3.2026
> Since i was tired yesterday i had to stop.

I expanded from 3 to 6 leds for a better look, i reordered stuff so it looks cleaner and less like spaghetti. And edited the Capacitor values :
  - LED 1 : 10 uF
  - Led 2 : 50 uF
  - LED 3 : 100 uF
  - LED 4 : 150 Uf
  - LED 5 : 200 uF
  - LED 6 : 300 uF

I chose these values since they looked the best to me.
<img width="1097" height="603" alt="screen" src="https://github.com/user-attachments/assets/e82f49f8-dd61-45bf-9e1d-a73b906f0ef9" />
### Time spent: 0.5 H
