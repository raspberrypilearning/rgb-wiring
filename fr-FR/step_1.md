Tu auras besoin de :

+ Un Raspberry Pi Pico
+ Une LED RVB à cathode commune
+ 3 x résistances
+ 8 x fils de liaison prise-prise

**Remarque :** Tu dois fixer des résistances aux trois broches plus courtes de la LED RVB. La broche la plus longue est pour la **masse** et ne nécessite pas de résistance.

**Regarde :** Ta LED RVB a quatre broches. Tourne ta LED RVB de sorte que la broche **GND** la plus longue soit la deuxième à partir de la gauche. Remarque comment les broches indiquent **R** pour **rouge**, puis **GND**, puis **G** pour **vert (green)** et enfin **B** pour **bleu**. Cela t'aidera à te souvenir de ce que fait chaque broche.

![Une illustration d'une LED RVB.](images/rgb-led-legs.png)

**Branchement :** Câbler ta LED RVB

+ Relie la broche **R** à **GP1**
+ Relie **GND** à la broche **GND**
+ Relie **G** à la broche **GP2**
+ Relie **B** à la broche **GP3**

![Un schéma d'un Raspberry Pi Pico relié à une LED RVB.](images/rgb-led-diagram.png)
