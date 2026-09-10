Flottafotó V11.0.4 – Weekly Export Fix

Backend:
- admin-weekly-export Edge Function frissítve v2-re.
- JSZip helyett streaming ZIP készítés (fflate).
- Az export nem tartja egyszerre memóriában az összes fotót és a teljes ZIP-et.
- JPEG/HEIC képek újratömörítése megszűnt, így gyorsabb és kevésbé memóriaigényes.
- Korábbi és aktuális hetek ugyanazzal a p_week paraméterrel működnek.

Frontend:
- A heti letöltés most a backend valódi hibaüzenetét mutatja.
- Letöltés alatt a gomb 'Csomag készítése…' állapotot kap.
- A szerver által küldött ZIP-fájlnevet használja.

Ellenőrzés:
- Edge Function deploy: ACTIVE, version 2
- JavaScript syntax check: OK
