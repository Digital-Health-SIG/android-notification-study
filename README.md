# Studie zur Untersuchung des Verhaltens von Android Apps

## Aufgabe als Studienteilnehmer

#### 1. Schreiben Sie eine Email mit **ihrem Namen** an [**robert.kahry@uni-ulm.de**](mailto:robert.kahry@uni-ulm.de?subject=An%20Studie%20teilnehmen), Betreff: **An Studie teilnehmen**


#### 2. Laden Sie sich die [LAMP App] herunter und installieren Sie letztere
- ein Tutorial zur Installation von APKs finden Sie hier: [https://www.heise.de/tipps-tricks/Externe-Apps-APK-Dateien-bei-Android-installieren-so-klappt-s-3714330.html](https://www.heise.de/tipps-tricks/Externe-Apps-APK-Dateien-bei-Android-installieren-so-klappt-s-3714330.html)
    
    
#### 3. Laden Sie die [Glück App] herunter (auf manchen Geräten wird diese als Happiness App bezeichnet)
  + erlauben Sie der App in den Einstellungen ihres Gerätes:
    + Benachrichtigungen senden
    + Autostart
    
    
#### 4. Sobald Sie eine Email von **robert.kahry@uni-ulm.de** erhalten können Sie sich mit dem in der Email enthaltenen QR-Code in der [LAMP App] für die Studie anmelden.
  + erlauben Sie der App die Berechtigungen die Sie verlangt
  + Die LAMP App brauchen Sie für den Rest der Studie nicht weiter zu beachten
  
  
#### 5. Öffnen Sie die Glück App und drücken Sie auf **"Los geht's"** (auf manchen Geräten wird diese als Happiness App bezeichnet)

+ Sie sind jetzt Studienteilnehmer! Vielen Dank für ihre Teilnahme!
+ Sie erhalten ab jetzt für 14 Tage jeden Tag zu unterschiedlichen Zeiten **eine** Benachrichtigung von der Glück App.
+ Klicken Sie die Benachrichtigungen an und beantworten Sie die Fragen , drücken Sie danach auf **"Fertig"**.
  + Die Antworten auf die Fragen werden nur lokal in der App gespeichert und niemandem gesendet, die App soll nur eine einfache Mental-Health-App simulieren.
  Sie können auch sofort auf **"Fertig"** klicken ohne die Fragen ehrlich zu beantworten.
  + Danach können Sie die App wieder schließen
  
+ nach 15 Tagen können Sie die Apps wieder deinstallieren

# Hintergrund zur Studie

Das Smartphone-Betriebssystem Android besitzt viele Funktionen, 
um die Batterienutzung des Smartphones zu reduzieren und die Sicherheit und Privatsphäre des Nutzers zu gewährleisten. 
Leider wurde in Studien beobachtet, dass diese Funktionen die Funktionalität von Apps einschränken können. 
Ziel dieser Studie ist es zu untersuchen, ob und inwiefern Apps durch diese Funktionen während der Studiendauer eingeschränkt werden.

Dafür wurde die Glück App geschrieben. Sie stellt eine App dar, für die eine zeitliche Ausführung ihrer Prozesse sehr wichtig ist. Dies ist in vielen Apps der Fall,
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


Die Glück App sendet täglich eine Benachrichtigung. Klickt man auf diese öffnet sich ein Fragebogen. Der Fragebogen besteht aus 3 Fragen aus dem PHQ-9 Fragebogen 
zur Diagnose von Depressionen. Die Glück App soll damit eine Health-App darstellen. Die durchschnittlichen Antworten findet man auf der Statistiken Seite der App. 
Sie können die Fragen z.B. aus Eigeninteresse ernst beantworten (nehmen Sie die Ergebnisse dabei nicht zu ernst), oder auch nicht. 
Wichtig ist nur, dass Sie die Benachrichtigungen anklicken und den Fragebogen beantworten (ob ernst oder nicht ist egal). 

Die LAMP App ist eine App die Informationen über Benachrichtigungen und über das Gerät selbst erfasst. 
Diese werden an einen Server gesendet um später ausgewertet zu werden.
In diesem Fall ist die Ankuftszeit der Benachrichtigungen, und ob diese überhaupt auftauchen interessant. 
Es wird ebenfalls das Gerätemodell, Status der Energiesparfunktion und ein paar weitere Daten erfasst. Es werden dabei keine vertraulichen Nutzerdaten gesammelt. 
Die Benachrichtigungen der Glück App sind die **einzigen** die von der LAMP App erfasst werden.

Die Studie läuft als Teil einer Bachelorarbeit von Robert Kahry.

Bei Fragen und Problemen können Sie sich gerne an mich wenden: [**robert.kahry@uni-ulm.de**](mailto:robert.kahry@uni-ulm.de?subject=Studie)
  
  
  
[LAMP App]: https://github.com/Digital-Health-SIG/android-notification-study/raw/main/LAMP_20220708.apk
[Glück App]:  https://github.com/Digital-Health-SIG/android-notification-study/raw/main/glück-app.apk
