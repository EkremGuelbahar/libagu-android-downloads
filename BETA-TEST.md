# Libagu Produktions-Beta: Testanleitung

Stand: 17. September 2026. Customer **0.8.0**, Business **0.5.0**.

Diese Beta ist für benannte Tester bestimmt und verwendet echte E-Mail-Zustellung.
Bitte nur eigene Daten und klar als Test erkennbare Termine im freigegebenen
Testsalon verwenden. Die APK-Dateien selbst sind öffentlich abrufbar.

## Installation

1. [Aktuellen Release öffnen](https://github.com/EkremGuelbahar/libagu-android-downloads/releases/tag/android-production-beta-vc200000011).
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

## Business: Salon einrichten und testen

1. **Inhaber-Konto:** Der Inhaber registriert sich selbst und bestätigt seine E-Mail. Ein vorhandenes Kundenkonto kann weiterverwendet werden. Ohne Einladung ist noch kein Salon zugeordnet.
2. **Salon anlegen:** Ekrem öffnet im Browser [Salons verwalten](https://termine.libagu.de/?login=1&panel=salons#admin), meldet sich mit seinem Betreiberkonto an und trägt Salonname, dauerhafte Adresse und verifizierte Inhaber-E-Mail ein.
3. **Einladung annehmen:** Der Inhaber öffnet seinen persönlichen E-Mail-Link und meldet sich mit dem vorgesehenen Konto an. Der Link gilt sieben Tage und ist einmalig. Auch Spam und eigene Ordner prüfen. Bei Versandfehler kann Ekrem den angezeigten Link persönlich weitergeben. Keine Passwörter teilen.
4. **Business öffnen:** Anmelden bzw. **Zugriff erneut prüfen**. Bei mehreren Salons den richtigen unter **Salon** wählen.
5. **Einrichten:** Die Liste unter **Salon** abarbeiten: Kontaktdaten, Leistungen/Preise, buchbares Team mit zugeordneten Leistungen, Öffnungs- und Arbeitszeiten. Ein Teamprofil allein ist noch kein Login; ein Salon-Admin allein ist noch kein buchbarer Friseur.
6. **Teamzugänge:** Unter **Salon → Zugänge im Browser verwalten** bestehende verifizierte Konten einladen. Für Friseur und lesenden Zugang das richtige Teamprofil auswählen. Die Einladung stellt diese Verbindung bei Annahme her.
7. **Buchung testen:** Über **Buchungsseite testen** eine eindeutig bezeichnete Testbuchung erstellen. Preise, Zeiten, Person und Bestätigungsmail prüfen.
8. **Veröffentlichen:** Erst nach korrekter Einrichtung und Test **In Kunden-App veröffentlichen** bestätigen. Der Salon erscheint danach in der Kunden-App. **Verbergen** entfernt ihn aus der Suche, storniert aber nichts und sperrt den direkten Buchungslink nicht.
9. **Tagesbetrieb:** Angemeldete Kundenbuchung und manuelle Buchung, Verschieben, Storno, abgeschlossene Termine und Kalenderaktualisierung testen. Eine Zeitänderung informiert den Kunden erst nach bewusstem Versand der Änderungsmail.
10. **Sonderfälle:** Ungespeicherten manuellen Termin beim Zurückgehen behalten/verwerfen, schnelle Doppelabsendung, abgelaufene/zurückgezogene Einladung, falsches Einladungskonto, große Schrift, Hell/Dunkel und Android-Systemtasten prüfen.

Für Rollentests getrennte Browserprofile/Konten verwenden: Salon-Admins verwalten ihren Salon; Rezeption verwaltet seine Termine; Friseure bearbeiten nur Termine ihres Teamprofils; lesende Zugänge dürfen eigene zugeordnete Termine nur ansehen. Andere Salons bleiben gesperrt.

Vergangene Termine werden automatisch als vergangen angezeigt. Das bestätigt weder Anwesenheit noch Bezahlung. Nur tatsächlich erbrachte Leistungen als abgeschlossen markieren; der angezeigte Leistungswert ist kein Zahlungsnachweis.

## Fehler melden

Über **Beta-Feedback** in der App oder an `info@libagu.de`: Gerät,
Android-Version, App-Version, Uhrzeit, Erwartung und Beobachtung nennen.
Screenshots vor dem Teilen auf personenbezogene Daten prüfen. Keine Passwörter,
persönlichen Verwaltungslinks, fremden Kontaktdaten oder Gesundheitsdaten senden.
