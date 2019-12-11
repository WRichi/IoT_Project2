# Story: Project02 Plant Control



### Neulich beim Wirt

Heinz: "Grüß dich Harald! Wie läuft die Gartenarbeit?"

Harald: "Grüß dich Heinz! Ich hatte eine richtig gute Ernte letztes Jahr."

Heinz: "Wirklich? Ich leider nicht. Die ganze Gärtnerei geht sich bei mir zeitlich nicht aus. Bei mir sind viel zu viel Pflanzen gestorben. Wie machst du das?"

Harald: "Ich habe mir dieses Jahr das neue IoT-System Plant-Control zugelegt."

Heinz: "Oha! Was ist denn das?"

Harald: "Das ist ein intelligentes System für mein Gewächshaus. Das kümmert sich um alle meine Pflanzen von ganz alleine. Zum Beispiel werden die Pflanzen automatisch gegossen, wenn sie zu trocken sind oder die Klimaanlage wird eingeschaltet, wenn es zu heiß oder zu kalt für die Pflanzen wird."

Heinz: "Das klingt aber super! Kann man sich die Daten auch irgendwo anschauen?"

Harald: "Ja! Es gibt ein Web-Interface auf dem alles angezeigt wird, wie zum Beispiel Temperatur, Luftfeuchtigkeit, Status der Pflanzen, Tankfüllmenge und vieles mehr."

Heinz: "Das klingt echt cool! Gibt es auch Security-Features?"

Harald: "Ja, man kann sein Gewächshaus mit einem RFID-Chip absichern, mit dem kann man zum Beispiel die Türe aufsperren. Zusätzlich gibt es einen Alarm, falls ein Brand erkannt wird."

Heinz: "Das ist ja der Wahnsinn! Das muss ich sofort haben! Das werde ich mir nächste Woche gleich bestellen! Dann geht es meinen Pflanzen endlich wieder gut."

Harald: "Du, Heinz. Wenn du Lust hast kannst du gerne mitkommen, dann kann ich dir alles zeigen."

Heinz: "Wirklich? Das wäre toll! Da komme ich gleich mit."



### Bei Harald zu Hause

Zuerst zeigt Harald uns das Dashboard, um uns einen guten Überblick über das ganze System zu geben. Das Dashboard ist in 4 Gruppen unterteilt. Environment, Plants, Pipes und Tank. In der Environment-Gruppe wird die Temperatur, Luftfeuchtigkeit und der Feuer-Status angezeigt. In der Plants-Gruppe wird der Feuchtigkeitsstatus jeder Pflanze angezeigt. Die Pipes-Gruppe zeigt an, ob gerade eine Bewässerung läuft oder nicht und diese können auch manuell ein- oder ausgeschaltet werden. Die Tank-Gruppe zeigt den Füllstand des Wassertanks, welcher für die Bewässerung notwendig ist, an.

Nachdem wir einen Überblick über das ganze System bekommen haben, betritt Harald sein Gewächshaus. Dabei muss er einen RFID-Chip an die Tür halten, damit sich diese auch öffnet. Sonst bleibt sie geschlossen.

Im Gewächshaus angekommen, zeigt Harald uns seine Pflanzen, welche alle mit einem Feuchtigkeitssensor ausgestattet sind. Die Sensoren kommunizieren mit dem System und sagen diesem, falls die Pflanzen gegossen werden müssen oder nicht. Sobald eine Pflanze zu trocken wird, wird ein Relay geschaltet, welches die Bewässerung der Pflanze in Gang setzt. Das Wasser dafür kommt aus dem hauseigenen Wassertank. Die Füllmenge des Wassertanks wird mit einer LED angezeigt. Wenn die LED grün ist, ist der Wassertank gut gefüllt. Ist sie gelb, ist weniger als die Hälfte im Tank und wenn sie rot ist, ist kaum noch Wasser vorhanden und der Wassertank sollte so schnell wie möglich wieder aufgefüllt werden.

Außerdem wird permanent die Temperatur und die Luftfeuchtigkeit im Gewächshaus gemessen. Ist es entweder zu kalt oder zu warm, wird die Klimaanlage passend dazu eingeschaltet. Dadurch ist die Temperatur immer perfekt für die Pflanzen automatisch geregelt.

Zum Schluss zeigt uns Harald noch seinen Feueralarm. Dieser ist nicht nur laut, sondern schickt auch eine Nachricht an Harald, falls ein Feuer in seinem Gewächshaus ausgebrochen sei.