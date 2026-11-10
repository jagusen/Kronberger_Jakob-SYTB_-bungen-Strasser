

## Konfiguration W10-2

### Schritt 1

1.  Starte VmWare Player und drücke auf `Create new virtual machine`

2. Im Anschluss wählst folgenden Punkt: `Install Operating System later`

3. Windows 10 wählen 

4. Jetzt nennst du das Laufwerk `W10-2` und nach dem richtigen Ordner suchen 

5. Hardware Einstellungen: 
- `HDD: 40GB RAM`  
- `CPU = 2 Kerne`  
- `das Netzwerk muss auf Custom eingestellt sein und auf VMNet 0 sein`

6. Klicke auf folgende Einstellung: `CD/DVD/SATA` und wähle den letzten Punkt: `Use ISO Image File` und wähle anschließend deine ISO File aus 

### Schritt 2 

1. Starte die VM und stelle die `Währung` , die `Zeit` und das `Tastaturlayout` auf Deutsch 

2. Wähle bei der Anmeldung unten links folgende Auswahl: `Join Domain instead` 

3. Melde dich an: 
- `User: sysadmin`  
- `Passwort: Win#Sys#admin10` 
- die darauffolgenden Fragen alle mit `NO` beantworten

### Schritt 3(Netzwerkeinstellungen)

1. Gehe in die Netzwerkadaptereinstellungen und stell die IP auf `192.168.6.12` , die Subnetzmaske normal auf `255.255.255.0` , das Gateway auf `192.168.6.254`. Die Adresse des DNS Servers ist `1.1.1.1` , bei alternative DNS einfach nichts schreiben

2. Im Anschluss habe ich noch ORF gepingt um alles zu testen 

### Schritt 4(Display-Einstellungen)

1. Jetzt stellst du die Display auflösung auf eine passende Größe `(1440 x 900)`

2. Jetzt nur noch 4 Programme installieren `(Google-Chrome , Java - Runtime , Putty und Adobe)`


