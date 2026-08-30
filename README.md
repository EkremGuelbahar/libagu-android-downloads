# Libagu Android Testbuilds

Dieses Repository verteilt signierte Android-Testbuilds von **Libagu** und
**Libagu Business**. Der Quellcode bleibt im privaten Repository
`EkremGuelbahar/libagu-mobile`.

## Download

- [Libagu fuer Kundinnen und Kunden](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/latest/download/libagu-staging.apk)
- [Libagu Business fuer Salon und Team](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/latest/download/libagu-business-staging.apk)
- [Pruefsummen des aktuellen Builds](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/latest/download/SHA256SUMS.txt)

Die APKs verbinden sich ausschliesslich mit der isolierten Libagu-
Stagingumgebung. Dort duerfen nur synthetische Testdaten verwendet werden.

## Closed Beta mit echten Tester-E-Mails

Der folgende klar gekennzeichnete Prerelease ist ausschließlich für benannte
Tester vorgesehen und verbindet sich mit der produktiven Libagu-API:

- [Closed-Beta-Downloadseite](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/tag/android-production-beta-vc200000003)
- [Libagu Closed Beta](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/download/android-production-beta-vc200000003/libagu-beta.apk)
- [Libagu Business Closed Beta](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/download/android-production-beta-vc200000003/libagu-business-beta.apk)
- [Prüfsummen](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/download/android-production-beta-vc200000003/SHA256SUMS.txt)
- [Anleitung und Testgrenzen](BETA-TEST.md)

Ein GitHub-, Expo- oder Entwicklerkonto ist zum Herunterladen nicht nötig.
Customer-Tester registrieren sich mit ihrer eigenen verifizierten E-Mail.
Business-Zugriff wird niemals automatisch vergeben, sondern durch einen Admin
an einen Testsalon gebunden. Die APK-Datei selbst ist öffentlich und darf keine
Secrets enthalten; Zugriffe werden serverseitig über Identität, Rollen und
Salon-Mitgliedschaften geschützt.

## Installation

1. Den passenden Link auf dem Android-Geraet oeffnen und die APK laden.
2. Android erlaubt die Installation gegebenenfalls erst nach einer einmaligen
   Freigabe fuer den verwendeten Browser.
3. APK installieren und die Freigabe fuer unbekannte Apps danach wieder
   deaktivieren.
4. Bei einem neuen Build denselben Link erneut oeffnen. Android aktualisiert
   die vorhandene App, wenn sie mit dem unveraenderten Libagu-Schluessel
   signiert wurde.

Android kann bei einer direkten APK-Installation einen Warnhinweis anzeigen,
weil die Datei nicht aus dem Play Store stammt. Vor der Installation kann die
Datei mit `SHA256SUMS.txt` aus demselben Release verifiziert werden.

## Sicherheitsrahmen

- Keine produktiven Kundendaten verwenden.
- APKs nicht als offiziellen Store-Release weitergeben.
- Keystores, Kennwoerter und der private Quellcode befinden sich nicht in
  diesem Repository.
- Jeder Release nennt den exakten Quell-Commit und den Android-Versionscode.

## Neuen Teststand bauen

Der Build wird unter **Actions** manuell gestartet. Als `source_ref` ist `main`,
ein Tag oder ein vollstaendiger 40-Zeichen-Commit-SHA zulaessig.
