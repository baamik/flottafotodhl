Flottafotó V11.0.3 – Runtime Fix

Javítva:
- QR kártyák eltűnésének oka: a V11.0.2 járműrajzoló függvénye rossz scope-ba került.
  Most globálisan elérhető, ezért a QR-kártyák renderelése újra működik.
- QR méretezés tovább erősítve, a kód nem lóghat ki a kártyából.
- Feltöltési fotók zoomjának oka: a kattintási esemény egy még nem létező `mm` változóra hivatkozott.
  A metaadat most előbb töltődik be, csak utána kötjük rá a fotó megnyitását.
- Fullscreen képnéző funkciók globálisan elérhetők.
- Egérgörgős zoom max. 800%, húzással mozgatás, ESC bezárás.
- Enteres admin belépés megmaradt.
- Backend/adatbázis nem változott.

Ellenőrzés:
- JavaScript syntax check: OK
