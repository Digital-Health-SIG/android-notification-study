# Studie zur Untersuchung des Verhaltens von Android Apps

## Aufgabe als Studienteilnehmer

#### 1. Schreiben sie eine Email mit **ihrem Namen** an **robert.kahry@uni-ulm.de**, Betreff: **An Studie teilnehmen**


#### 2. Laden sie die [LAMP App] herunter. 
  + klicken sie auf Einstellungen (oben rechts) in der App und erlauben: 
    + Benachrichtigungen lesen
    + Autostart
    
    
#### 3. Laden sie die Test App herunter (siehe .apk oben)
  + erlaube der App in den Einstellungen ihres Gerätes:
    + Benachrichtigungen senden
    + Autostart
    
    
#### 4. Sobald sie eine Email von **robert.kahry@uni-ulm.de** erhalten können sie sich mit dem in der Email enthaltenen QR-Code in der [LAMP App] für die Studie anmelden.
  + Die LAMP App brauchen sie für den Rest der Studie nicht zu beachten
  
  
#### 5. Öffnen sie die Test App und drücken sie auf **"Los geht's"**

+ Sie sind jetzt Studienteilnehmer! Vielen Dank für ihre Teilnahme!
+ Sie erhalten ab jetzt für 14 Tage jeden Tag zu unterschiedlichen Zeiten **eine** Benachrichtigung von der Test App.
+ Klicken sie die Benachrichtigungen an und beantworten sie die Fragen , drücken sie danach auf **"Fertig"**.
  + Die Antworten auf die Fragen werden nur lokal in der App gespeichert und niemandem gesendet, die App soll nur eine einfache Mental-Health-App simulieren.
  Sie können auch sofort auf **"Fertig"** klicken ohne die Fragen ehrlich zu beantworten.
  + Danach können sie die App wieder schließen
  
+ nach 15 Tagen können sie die Apps wieder deinstallieren

# Motivation der Studie

Das Smartphone-Betriebssystem Android besitzt viele Funktionen, 
um die Batterienutzung des Smartphones zu reduzieren und die Sicherheit und Privatsphäre des Nutzers zu gewährleisten. 
Leider wurde in Studien beobachtet, dass diese Funktionen die Funktionalität von Apps einschränken können. 
Ziel dieser Studie ist es zu untersuchen, ob und inwiefern Apps durch diese Funktionen während der Studiendauer eingeschränkt werden.

Dafür wurde die Test App geschrieben. Sie stellt eine App dar, für die eine zeitliche Ausführung ihrer Prozesse sehr wichtig ist. Dies ist in vielen Apps der Fall,
besonders in Health-Apps ist es häufig so, dass zu bestimmten Zeiten Sensoren bestimmte Daten sammeln sollen oder Benachrichtigungen den Nutzer erreichen sollen.
In Studien wurde herausgefunden, dass das Betriebssystem Android durch Funktionen wie :
  + Doze Mode
  + App Standby
  + Background Execution Limits
  + Limited access to sensors in background
  + App Standby Buckets
  
die Akku sparen und die Privatsphäre des Nutzers verbessern sollen, Apps eingeschränkt oder sogar komplett verhindert werden.
Viele Smartphone Hersteller fügen mittlerweile auch noch weitere Funktionen hinzu, die Apps noch weiter einschränken. 
Dies ist für manche Apps natürlich ein großes Problem.


Die Test App sendet täglich eine Benachrichtigung. Klickt man auf diese öffnet sich ein Fragebogen. Der Fragebogen besteht aus 3 Fragen aus dem PHQ-9 Fragebogen der AOK 
zur Diagnose von Depressionen. Die Test App soll damit eine Health-App darstellen. Die durchschnittlichen Antworten findet man auf der Statistiken Seite der App. 
Sie können die Fragen z.B. aus Eigeninteresse ernst beantworten (nehmen sie die Ergebnisse dabei nicht zu ernst), oder auch nicht. 
Wichtig ist nur, dass sie die Benachrichtigungen anklicken und den Fragebogen beantworten (ob ernst oder nicht ist egal). 

Die LAMP App ist eine App die Informationen über Benachrichtigungen und über das Gerät selbst erfasst. 
Diese werden an einen Server gesendet um später ausgewertet zu werden.
In diesem Fall ist die Ankuftszeit der Benachrichtigungen, und ob diese überhaupt auftauchen interessant. 
Es wird ebenfalls das Gerätemodell, Status der Energiesparfunktion und ein paar weitere Daten erfasst. Es werden dabei keine vertraulichen Nutzerdaten gesammelt. 
Die Benachrichtigungen der Test App sind die **einzigen** die von der LAMP App erfasst werden.

Die Studie läuft als Teil einer Bachelorarbeit von mir, Robert Kahry.

Bei Fragen und Problemen können sie sich gerne an mich wenden: robert.kahry@uni-ulm.de
  
  
  
[LAMP App]: https://github.com/Digital-Health-SIG/lamp-android-app
