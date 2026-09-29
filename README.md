# Comvio Leady – instalace

Appka na týmové obvolávání firem od **Comvio** (dříve LeadRadar). Tady jsou jen instalačky – přihlašovací údaje ti dá administrátor.

## Stažení

| Počítač | Instalačka |
|---|---|
| **Mac** (Apple Silicon i Intel) | [**Comvio-Leady-Mac.dmg**](https://github.com/comvioapp-collab/leadradar-releases/releases/latest/download/Comvio-Leady-Mac.dmg) |
| **Windows** 10 / 11 | [**Comvio-Leady-Windows.exe**](https://github.com/comvioapp-collab/leadradar-releases/releases/latest/download/Comvio-Leady-Windows.exe) |

## Instalace

### Mac

1. Otevři stažený **Comvio-Leady-Mac.dmg** a přetáhni ikonu **Comvio Leady** do složky **Aplikace**.
2. Spusť Comvio Leady ze složky Aplikace. Poprvé se objeví hláška, že *Apple nemohl ověřit, že Comvio Leady neobsahuje malware* – klikni **Hotovo**.
   (Appka není v Apple App Storu, proto to hlášení. Je to jednorázové.)
3. Otevři **Nastavení systému → Soukromí a zabezpečení**, sjeď dolů k hlášce o Comvio Leady a klikni **Přesto otevřít**. Potvrď heslem nebo Touch ID.
4. Hotovo – příště už se appka otevírá normálně.

> Tip pro pokročilé: místo kroků 2–3 jde v Terminálu spustit `xattr -cr "/Applications/Comvio Leady.app"`.

### Windows

1. Spusť stažený **Comvio-Leady-Windows.exe**.
2. Když se objeví modré okno **Systém Windows ochránil váš počítač**, klikni **Další informace** → **Přesto spustit**. (Jednorázové – appka zatím není podepsaná certifikátem.)
3. Appka se sama nainstaluje (bez administrátorských práv), vytvoří zástupce na ploše a spustí se.

## Přihlášení

Přihlas se e-mailem a heslem, které ti poslal administrátor. Zaškrtni **Zapamatovat heslo** a příště tě appka přihlásí sama. Heslo si můžeš změnit v appce v **Nastavení → Můj účet**.

## Aktualizace

Stahují se samy. Když je nová verze připravená, objeví se nahoře fialový pruh **Aktualizovat teď**. Když na něj neklikneš, nainstaluje se sama, až bude počítač 5 minut v klidu, nebo při zavření appky.

Kdo měl nainstalovaný **LeadRadar**, nic nového instalovat nemusí – appka se sama aktualizuje a přejmenuje na Comvio Leady (na Macu po zavření appky).

## Něco nefunguje?

- **Mac hlásí, že je appka poškozená** → v Terminálu spusť `xattr -cr "/Applications/Comvio Leady.app"` a otevři ji znovu.
- **Nejde se přihlásit** → zkontroluj e-mail a heslo, případně napiš administrátorovi (může ti heslo nastavit znovu).
- **Appka píše „Nejde se připojit“ nebo „Obnovuji spojení s databází“** → zkontroluj internet, appka se připojí sama.
