!SLIDE bullets incremental
#Die Schulungsnotebooks
Verwendungszwecke:

* Den Unterlagen folgen
* Die Virtuellen Maschinen hosten

!SLIDE bullets incremental
#Virtualbox
* Virtualbox starten
[Bild von virtualbox]
* 'jenkins-master' starten

~~~SECTION:notes~~~

TODO: Wie Virtualbox starten?
TODO: Bild von virtualbox mit den 2 maschinen

~~~ENDSECTION~~~

!SLIDE bullets incremental
#jenkins-master
* Entweder im Virtualbox Fester arbeiten...
* ...oder per ssh auf die Maschine verbinden

    @@@ sh
    ssh jenkins@171.16.32.10
    Passwort: icinga

~~~SECTION:notes~~~

TODO: Richtige Daten eintragen
Wer im Fenster arbeiten möchte braucht auch jenkins:icinga

~~~ENDSECTION~~~

!SLIDE bullets
#root werden
* Der Benutzer 'jenkins' hat geringe Berechtigungen
  - Wir brauchen ihn aber später noch
* 'root' hat volle Kontrolle über die Box

   @@@ sh
   sudo -i
   Passwort: icinga
