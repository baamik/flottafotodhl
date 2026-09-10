Flottafotó V11.0.5 – Valid ZIP Fix

A V11.0.4-ben a streaming ZIP válasz letöltődött, de a ZIP központi könyvtára
nem minden esetben jutott el érvényesen a klienshez, ezért a Windows hibás ZIP-nek látta.

V11.0.5:
- admin-weekly-export Edge Function v3
- a ZIP most teljesen elkészül a szerveren, és csak utána kerül HTTP válaszba
- STORE mód: a már tömörített fotókat nem tömörítjük újra
- minden storage fájl letöltése ellenőrzött
- Content-Length beállítva
- PK ZIP aláírás ellenőrzött a szerveren
- aktuális és korábbi hetek támogatása megmarad
- frontend funkciók változatlanok

JavaScript syntax check: OK
