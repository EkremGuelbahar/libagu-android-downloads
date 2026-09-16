# Libagu Produktions-Beta: Testanleitung

Stand: 16. September 2026. Customer **0.8.0**, Business **0.4.3**.

Diese Beta ist für benannte Tester bestimmt und verwendet echte E-Mail-Zustellung.
Bitte nur eigene Daten und klar als Test erkennbare Termine im freigegebenen
Testsalon verwenden. Die APK-Dateien selbst sind öffentlich abrufbar.

## Installation

1. [Aktuellen Release öffnen](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/tag/android-production-beta-vc200000010).
2. `libagu-beta.apk` für Kunden oder `libagu-business-beta.apk` für Salon und Team laden.
3. Die vorhandene Produktions-Beta direkt aktualisieren, nicht vorher deinstallieren.
4. Eine eventuell erteilte Browserfreigabe für unbekannte Apps danach deaktivieren.

Ein GitHub-, Expo- oder Entwicklerkonto ist zum Herunterladen nicht erforderlich.

## Kundenablauf testen

1. Mit eigener erreichbarer E-Mail registrieren. Passwortanforderungen und
   Passwortwiederholung während der Eingabe prüfen.
2. E-Mail bestätigen. Bei fehlender Mail auch Spam/Junk und eigene Ordner prüfen.
3. Anmelden, Profil öffnen, Profilbild hinzufügen und entfernen.
4. Eine Buchung anfangen. Ins Profil oder zu Termine wechseln, anschließend
   **Angefangene Buchung fortsetzen** antippen. Eingaben und Auswahl bleiben erhalten.
   Der Entwurf gilt während dieses App-Besuchs; Abmelden oder App-Beendigung entfernt ihn.
5. Angemeldet einen Testtermin buchen; im optionalen Hinweis `TEST` angeben.
   Er muss ohne Linkeingabe unter **Termine** erscheinen.
6. Termin verschieben und stornieren. Stornierte Termine stehen im **Verlauf**.
   Nach Ablauf wird kein Abhaken durch den Kunden verlangt. Nur der Salon
   bestätigt die tatsächliche Wahrnehmung.
7. Erinnerungen aus-/einschalten: Die Einstellung gilt für neue Kontobuchungen.
   Buchungsbestätigungen und Änderungsmails bleiben davon unabhängig.
8. CSV-Terminübersicht im Profil testen. Die vollständige Datenkopie ist
   zusätzlich als JSON verfügbar; beides sind keine Zahlungsbelege.
9. Passwort vergessen, Passwortwechsel und Abmelden prüfen.
10. Gestensteuerung und Android-Systemtasten, größere Schrift sowie Hell/Dunkel testen.

Gastbuchungen bleiben über die Bestätigungsmail verwaltbar. Ein Link muss nicht
manuell eingefügt werden, um neue angemeldete Buchungen im Konto zu sehen.
Kontolöschung nur mit einem dafür vorgesehenen eigenen Testkonto prüfen.

## Business-Test

Ein Admin muss den Tester einem Testsalon und einer Rolle zuweisen. Keine Konten
oder Passwörter teilen. Kalender, Terminstatus, Verschieben, Öffnungszeiten und
Teamverwaltung nur im zugewiesenen Testkontext prüfen.

## Fehler melden

Über **Beta-Feedback** in der App oder an `info@libagu.de`: Gerät,
Android-Version, App-Version, Uhrzeit, Erwartung und Beobachtung nennen.
Screenshots vor dem Teilen auf personenbezogene Daten prüfen. Keine Passwörter,
persönlichen Verwaltungslinks, fremden Kontaktdaten oder Gesundheitsdaten senden.
