# Architektura aplikace
###### V rámci aplikace eFyzika se používá určité architektury a systému funkčnosti aplikace. 

### Technické řešení aplikace
* Visual Basic a standartní uživatelské rozhraní Windows Forms
* Metro UI framework pro vykreslení GUI
* MySQL Connect pro .NET pro připojení k MySQL databázi

### Serverové řešení aplikace
* GitHub projekt jako hlavní webová stránka aplikace a hosting pro data (soubory a instalace)
* Linuxový Ubuntu server s běžící MySQL databází jako aplikační databázi

### Cloudová infrastruktura
Pro maximální úsporu v rámci celé aplikace je v co největší míře využíváno hostování na GitHubu. Databáze běží na vlastním serveru na Forpsi Cloudu. Image serveru je v repozitáři. Aplikace je díky cloudovému VPS serveru a GitHubu škálovatelná a cloudová. Zvládne i velmi vysokou zátěž. Infrastruktura se sama zvětšuje či zmenšuje podle toho jak sama potřebuje.
