Flottafotó V11.0.1 – layout hotfix

Hiba oka:
A régi adminDash elem adminLayout grid maradt, és ezen BELÜL kapott helyet az új V11 adminLayout.
Ez két egymásba ágyazott gridet hozott létre, ezért a teljes V11 felület a régi bal oldali ~250px-es oszlopba szorult.

Javítás:
- a külső, régi adminLayout osztály eltávolítva az adminDash wrapperről;
- az új V11 layout most közvetlenül a teljes viewport szélességét használja;
- funkciókhoz/backendhez nem nyúltunk;
- JavaScript syntax check: OK.
