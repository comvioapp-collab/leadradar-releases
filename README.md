# LeadRadar – instalace

Appka na týmové obvolávání firem od **Comvio**. Tady jsou jen instalačky – přihlašovací údaje ti dá administrátor.

## Stažení

| Počítač | Instalačka |
|---|---|
| **Mac** (Apple Silicon i Intel) | [**LeadRadar-Mac.dmg**](https://github.com/comvioapp-collab/leadradar-releases/releases/latest/download/LeadRadar-Mac.dmg) |
| **Windows** 10 / 11 | [**LeadRadar-Windows.exe**](https://github.com/comvioapp-collab/leadradar-releases/releases/latest/download/LeadRadar-Windows.exe) |

## Instalace

### Mac

1. Otevři stažený **LeadRadar-Mac.dmg** a přetáhni ikonu **LeadRadar** do složky **Aplikace**.
2. Spusť LeadRadar ze složky Aplikace. Poprvé se objeví hláška, že *Apple nemohl ověřit, že LeadRadar neobsahuje malware* – klikni **Hotovo**.
   (Appka není v Apple App Storu, proto to hlášení. Je to jednorázové.)
3. Otevři **Nastavení systému → Soukromí a zabezpečení**, sjeď dolů k hlášce o LeadRadaru a klikni **Přesto otevřít**. Potvrď heslem nebo Touch ID.
4. Hotovo – příště už se LeadRadar otevírá normálně.

> Tip pro pokročilé: místo kroků 2–3 jde v Terminálu spustit `xattr -cr /Applications/LeadRadar.app`.

### Windows

1. Spusť stažený **LeadRadar-Windows.exe**.
2. Když se objeví modré okno **Systém Windows ochránil váš počítač**, klikni **Další informace** → **Přesto spustit**. (Jednorázové – appka zatím není podepsaná certifikátem.)
3. Appka se sama nainstaluje (bez administrátorských práv), vytvoří zástupce na ploše a spustí se.

## Přihlášení

Přihlas se e-mailem a heslem, které ti poslal administrátor. Heslo si můžeš změnit v appce v **Nastavení → Můj účet**.

## Aktualizace

Stahují se samy. Když je nová verze připravená, objeví se v levém panelu **Nová verze – Restartovat a aktualizovat**. Když na tlačítko neklikneš, aktualizace se nainstaluje při příštím zavření appky.

## Něco nefunguje?

- **Mac hlásí, že je appka poškozená** → v Terminálu spusť `xattr -cr /Applications/LeadRadar.app` a otevři ji znovu.
- **Nejde se přihlásit** → zkontroluj e-mail a heslo, případně napiš administrátorovi (může ti heslo nastavit znovu).
- **Appka píše „Obnovuji spojení s databází“** → zkontroluj internet, appka se připojí sama.
