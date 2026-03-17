# PrismLauncher Útmutató (Minecraft Szerver 1.21.1-hez)

Ez az útmutató segít a **PrismLauncher** beállításában Windows-on egy cracked Minecraft szerverhez Forge modokkal (1.21.1 verzió). Tartalmazza az offline fiók létrehozását.

## Előfeltételek
- Windows operációs rendszer
- Web böngésző
- [Accounts JSON fájl](https://github.com/Szatocs1/PrismLauncher/blob/main/accounts.json) (később letölthető)

## 1. lépés: PrismLauncher Letöltése és Telepítése
1. Nyisd meg ezt a linket: [https://prismlauncher.org/download/windows/](https://prismlauncher.org/download/windows/).
2. Töltsd le a **Windows Installer (.exe)** fájlt.
3. Futtasd az .exe fájlt.
4. Telepítésnél állítsd be a **Desktop**-ot a második lapon.
5. Engedélyezd az **Account Control**-ön (Yes/Igen).
6. A telepítés befejeződik, megnyílik a felület.
7. Állítsd be a nyelvet és kinézetet.
8. Hagyd ki a Microsoft fiók bejelentkezést.

## 2. lépés: Offline Fiók Beállítása
1. PrismLauncher-ben kattints a **Steve fejre** (jobb fent) → **Manage accounts**.
2. Nyomj **Win + R**-t, írd be: `%appdata%`, Enter.
3. Menj a `PrismLauncher` mappába.
4. Töltsd le az [accounts.json](https://github.com/Szatocs1/PrismLauncher/blob/main/accounts.json)-t:
   - Menj: https://github.com/Szatocs1/PrismLauncher
   - Kattints `accounts.json`-ra
   - **...** gombra (jobb fent) → **Download**
5. Húzd a letöltött `accounts.json`-t a `PrismLauncher` mappába (felülírás ha kéri).
6. Launcher-ben: Zárd be az **Accounts** fület.
7. Fiók kiválasztásnál: **OK**.
8. Hagyd figyelmen kívül a \"This account does not own Minecraft\" üzenetet → **Cancel**.
9. Steve fej → **Manage accounts** újra.
10. **Add Offline**:
     - Add meg a neved → **OK**.
     - Zárd be a launchert.
11. Ellenőrizd: `%appdata%\PrismLauncher`-ban legyen `metacache`, `prismLauncher`, `prismLauncher_update`. Ha nincs, értesíts (Szatocs).
12. Nyisd újra → Steve fej → **Manage accounts**.
13. **Add Offline** → Név → **OK**.
14. Válaszd ki → **Set Default**.

## 3. lépés: Instance Létrehozása
1. Főképernyő → **Add Instance**.
2. Keress **1.21.1**-re (Filter), válaszd **Forge** Mod Loadert.
3. **OK**. Megjelenik az instance.
4. Kattints rá → **Launch** (jobb oldalon).

## 4. lépés: Szerverhez Csatlakozás
Kérd el tőlem (Szatocs) a szerver címet privátban (nem publikus).

## Hibaelhárítás
- **Nincs metacache mappa (2.11)**: Újra töltsd le accounts.json-t, ellenőrizd útvonalat.
- **Fiók nem észlelve**: Indítsd újra a launchert JSON után.
- **Indítás sikertelen**: Ellenőrizd Forge 1.21.1-et; Java általában bundled.

## Megjegyzések
- Ez **cracked/offline fiókot** készít szerver játéshoz.
- Szerver Forge modokat használ—ne változtass verziót kompatibilitás nélkül.
- Probléma/kérdés: GitHub issue vagy Szatocs.

Sikeresen beállítottad! 🎮
