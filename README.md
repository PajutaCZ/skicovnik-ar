# Skicovník AR

Česká instalovatelná PWA pro kreslení podle fotografie a obrazu z fotoaparátu.

## Aplikace

Spusťte [Skicovník AR](https://pajutacz.github.io/skicovnik-ar/) v prohlížeči. Na telefonu ji lze nainstalovat jako PWA. Kamera a instalace vyžadují HTTPS (nebo localhost).

Fotografie se zpracovávají pouze v prohlížeči; projekty jsou uloženy v IndexedDB zařízení.

## Ovládání

Vyberte fotografii a případně zapněte kameru. Předlohu posouvejte jedním prstem; dvěma prsty ji zvětšujte, zmenšujte a otáčejte. Zámek polohu chrání před nechtěným pohybem.

Ukládání projektů používá IndexedDB, drobná nastavení LocalStorage. Kamera potřebuje oprávnění prohlížeče. Svítilna se aktivuje jen na podporovaných zařízeních. Offline režim zpřístupní dříve načtené soubory aplikace; kamera potřebuje funkční zařízení a oprávnění.

## Rozsah této verze

Hotové jsou kamera a překrytí, dotykové posouvání/přiblížení/otočení, sedm režimů obrazu, mřížka, místní projekty, tisk A4, export PNG a základní offline instalace. Tisk A3 a přesné rozměry předlohy v centimetrech zatím nejsou součástí této verze.

## Nasazení

Aplikace je publikovaná na [GitHub Pages](https://pajutacz.github.io/skicovnik-ar/).