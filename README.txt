V7.1 – admin munkamenet kezelés javítás

Ha a Supabase admin session lejár, az oldal most automatikusan:
- törli a lejárt böngésző-sessiont
- visszavisz az admin belépéshez
- kiírja, hogy újra be kell jelentkezni

Nem marad bent a dashboardon ADMIN_SESSION_REQUIRED hibaüzenettel.
