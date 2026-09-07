# Unser Familienbuch

[Familienbuch öffnen](https://mpusceddu.github.io/familienbuch-pages/)

Statische Ausgabe für GitHub Pages. Dieses Repository enthält die öffentliche Anmeldeseite sowie **verschlüsselte** Familieninhalte und Bilder.

Die Inhalte werden erst nach Eingabe des Familienpassworts im Browser entschlüsselt. Das Passwort und unverschlüsselte Quelldaten sind nicht Teil dieses Repositorys.

Die Website ist für den Familienkreis bestimmt. Die Bereitstellung bedeutet keine Erlaubnis, Familieninhalte oder Bilder weiterzuverwenden.

## Aufbau

- Statische Anwendung mit lokalem Entschlüsseln über Web Crypto (AES-GCM-256, PBKDF2-SHA256).
- Neue zufällige Schlüsselableitung und eindeutige zufällige Initialisierungswerte je Veröffentlichung und Datei.
- Bilder werden bei Bedarf entschlüsselt. Schließen oder Neuladen erfordert eine erneute Eingabe.
- Keine externe Anmeldung, keine Werbe- oder Analyse-Dienste.

Verschlüsselte Dateien können öffentlich heruntergeladen werden. Deshalb ist ein langes, zufällig erzeugtes Familienpasswort erforderlich. Ein Passwortwechsel schützt neue Veröffentlichungen; bereits kopierte alte Fassungen lassen sich mit ihrem damaligen Passwort weiterhin öffnen.

Der bearbeitbare Quellcode und die Dokumentation werden separat im privaten Projekt gepflegt.
