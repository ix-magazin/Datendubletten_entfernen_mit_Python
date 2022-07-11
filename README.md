# Datendubletten entfernen mit Python

Quellcode zum [Praxis-Artikel](https://www.heise.de/select/ix/2022/82212612504066891412) von Dr. Roland Pleger, erschienen auf Heise online(LINK) im [iX-Magazin 09/2022](https://www.heise.de/select/ix/2022/9). 

## iX-tract
- Doppeleinträge in Datenbanken und anderen Datenquellen aufgrund von Fehlern bei der Dateneingabe sind ein Ärgernis.
- Das Entfernen von Dubletten kann viel Handarbeit erfordern, will man keine ähnlichen Einträge aus Versehen automatisiert löschen.
- In Python helfen die Bibliotheken difflib, RapidFuzz und Record Linkage beim Erkennen von ähnlichen Wörtern oder Falschschreibungen.
- Für Pandas-Dataframes analysiert Record Linkage die Ähnlichkeit mehrerer Attributkombinationen und entfernt Dubletten auf Wunsch mit wenig Rechenaufwand
