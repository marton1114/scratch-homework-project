# Scratch-project

Ez a Scratch projekt a Programozási nyelvek 1. c. tantárgy első beadandója. 

Az én ötletem az volt, hogy egy robotot készítek ami a decimális számokat binárissá alakítja. Mivel ennek a megvalósításához elég egy sprite is, úgy döntöttem, hogy a robot felajánlja, hogy a létrejött biteket ledobolja egy kongán.

A program egy kérdés blokkal kezdődik, amit egy broadcast blokk előz meg. A megoldásomban több ilyen is megtalálható, ezeket azért használtam így, hogy párhuzamosan tudjak két utasítást elvégezni. Jelen esetben a program egyszerre jeleníti meg a kérdést és indítja el a hangfelvételt. Ezt egy hagyományos szzámrendszer átalakító követi, ami a számot folyamatosan kettővel osztja, majd a maradékot megszorozza 10 hatványaival, hogy a szám ne legyen fordított sorrendben. Ahogy megkapott egy számjegyet le is játszik egy hangot attól függően, hogy az egy 1-es vagy 0-ás.
Ezt üjra egy broadcast és egy kérdéses blokk követi, aminek egy igen vagy egy nem választ adhatunk meg. Ha igent gépelünk be akkor a program jelet küld a kongának, amia a létrejött bináris számot lejátssza a legkisebb helyiértéktől. Ezt úgy éri el, hogy leellenőrzi az utolsó számjegyet, majd a hangfelvétel után levágja azt, amíg a szám 0 nem lesz.
A konga minden számjegynél visszaküld egy jelet a robotnak is, hogy jelezze mikor kell mozgatnia a kezét.
Ha a második kérdésnél nemet válaszolunk akkor egy ":(" üzenettel bezáródik a program.

A robot programja:
![](Képernyőfelvétel%20(53).png)
A konga programja:
![](Képernyőfelvétel%20(54).png)

Link a kész projekthez:
https://scratch.mit.edu/projects/492920256/fullscreen/
