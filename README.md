# Libagu Android-Testbuilds

Hier findest du die geprüften Android-APKs für Libagu und Libagu Business.
Der Quellcode bleibt im privaten Repository `EkremGuelbahar/libagu-mobile`.

## Aktuelle Produktions-Beta

Customer **0.8.0**, Business **0.4.3**, Android **200000010**.
Für benannte Tester: echte E-Mail-Zustellung und produktive API. Bitte nur eigene
Daten und eindeutig als Test erkennbare Termine im freigegebenen Testsalon verwenden.

- [Libagu herunterladen](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/download/android-production-beta-vc200000010/libagu-beta.apk)
- [Libagu Business herunterladen](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/download/android-production-beta-vc200000010/libagu-business-beta.apk)
- [Release und Prüfsummen](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/tag/android-production-beta-vc200000010)
- [Testanleitung](BETA-TEST.md)

Neu: Buchung mit bleibender Navigation und fortsetzbarem Entwurf, aufgeräumtes
Profil, CSV-Terminübersicht, klarer Terminverlauf und Livefeedback beim Passwort.
Angemeldete Buchungen erscheinen automatisch unter **Termine**.

## Installieren oder aktualisieren

1. Den passenden APK-Link auf dem Android-Gerät öffnen.
2. Falls Android fragt, die Installation für diesen Browser einmalig erlauben.
3. APK installieren. Die vorhandene Produktions-Beta direkt aktualisieren;
   nicht vorher deinstallieren. Bei einem Paketkonflikt die Meldung an Ekrem geben.
4. Die Freigabe für unbekannte Apps danach wieder deaktivieren.

Zum Herunterladen ist kein GitHub-, Expo- oder Entwicklerkonto erforderlich.
Dies ist ein direkter APK-Testbuild und noch kein offizieller Play-Store-Release.
Die Prüfsumme steht im jeweiligen Release. Signierschlüssel, Passwörter und
privater Quellcode gehören nicht in dieses Repository.

Die APK-Dateien sind öffentlich abrufbar. Kunden verwenden ihre eigene verifizierte
E-Mail. Business-Zugriff erfordert zusätzlich eine zugewiesene Salonrolle.

## Isolierte Staging-Testbuilds

Diese separaten Apps verwenden ausschließlich synthetische Testdaten. Die
Staging-Links sind kein Update der Produktions-Beta:

- [Libagu Staging](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/latest/download/libagu-staging.apk)
- [Libagu Business Staging](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/latest/download/libagu-business-staging.apk)

## Wo werden neue Builds erstellt?

Im privaten Quellrepository unter
[Libagu Mobile → Actions](https://github.com/EkremGuelbahar/libagu-mobile/actions/workflows/android-production-internal.yml).
Dieses Downloadrepository stellt die fertigen APKs unter **Releases** bereit.
Seine älteren Actions-Läufe zeigen nicht die aktuellen Produktions-Builds.
