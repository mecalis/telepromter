## Telepromter adatok elemzése - 3. Dataklub Házi Adatelemző Verseny

Az adatelemző verseny a Dataklub (dataklub.hu) szervezésében jött létre.
Az adatokat a Telepromter nevű, budapesti székhelyű IOS/Android alkalmazás ügyvezetője biztosította. A verseny során ~4 millió sororos felhasználói log alapján kellett minél jelentősebb **üzleti értéket** előállítani a Telepromter számára. Habár nem volt meghatározva célirányosan, hogy mi számít üzleti értéknek, de az elemzésnek tartalmaznia kellett a próbaidőszakot elkezdő felhasználók fizetős ügyfelekké vagy lemorzsolódó felhasználókká válásának elemzését (**Churn analyzis**). 

### A versenyről:
A verseny kettő fordulóból állt:
1. online forduló: a versenyzőknek 8 hetük volt az elemzésük elkészítésére. A szervezők kiválasztották a 10 legígéretesebb beadott pályamunkát, majd a Telepromter ügyvezetőjével közösen megnevezték a 3 döntős versenyzőt.
2. forduló: a 3 döntősnek élő szóban kellett egy 12 perces prezentáci során előadniuk az elemzésüket egy 6 fős data science zsűri és közel 70 főnyi érdeklődő előtt, majd minden zsűri kérdéseket tehetett fel az előadás tartalmával kapcsolatban.

A döntő során az elemzésem a megtisztelő 🥈 **2. helyet** érte el.

### Elért eredmények:
Az elemzés során feltártam: 
- feltártam a szűk keresztmetszeteket (**bottleneck**)
- a népszerű, motiváló és a várakozásokkal ellentétben kevésbé "érdekes" funkciókat az alkalmazásban, amik az adatok alapján **befolyásolhatják a felhasználók döntését**
- az egyes országok és régiók közötti különbségeket
- a felhasználók eltérő alkalmazás használatát
- az összefüggéseket a jövedelmi szintek és az előfizetési hajlandóság között, mely során rámutattam mely régiókban maradhattak **potenciális új előfizetők**


