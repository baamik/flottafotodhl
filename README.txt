Flottafotó V8.1 – QR javítás

A hiba oka a két QR JavaScript-könyvtár ütközése volt.
A rendszer most egységesen a már meglévő qrcodejs könyvtárat használja.

Ellenőrizve az adatbázisban:
- 65/65 felhasználónak van QR-tokenje
- 50/50 járműnek van QR-tokenje

Teendő:
index.html csere -> Commit changes -> Vercel.
Utána QR-kódok fül -> dolgozó vagy jármű kiválasztása.
