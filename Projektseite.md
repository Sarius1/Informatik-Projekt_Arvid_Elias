

# Projektseite

1. Einleitung
2. StarlogoTNG
3. Projektentwicklung
4. Vorstellung des Projekts
5. Der Code
6. Kritik
7. Fazit/Aussicht für die Zukunft
8. Quellen
9. Eigenständigkeitserklärung


# Einleitung

Krankheiten und Pandemien sind ein fester Bestandteil eines jeden Ökosystems. Gerade in den letzten Jahren hatten wir ein vermehrtes auftreten solcher gesehen.
Im Jahr 2019 wurde das neue Virus, das Coronavirus entdeckt und die Welt geriet ins stocken. Ganze Länder und Infrastrukturen wurden lahmgelegt. Niemand wusste, wie man richtig in einer solchen Situation reagieren sollte. Dementsprechend haben wir es uns zur Aufgabe gemacht, solche Problematiken vorzubeugen. Wir haben mithilfe des Programms #StarlogoTNG Pandemien simuliert. Der zuschauer kann mithilfe verschiedener Graphen den Verlauf der Pandemie erbicken. Zudem gibt es verschiedene Slider um eine möglichst präzises Ergebnis zu erzielen.Um die Idee in die Tat umzusetzen mussten wir uns jedoch zuerst mit den verschiedenen Programmen auseinandersetzen. Wir beide hatten nämlich kaum Erfahrungen in diesem Bereich und wollten mithilfe dieses Projektes ein grobes aber allumfassendes Verständnis für das codieren bekommen. Als Einstieg wurde uns daher StarlogoTNG empfohlen

# StarlogoTNG

StarlogoTNG ist ein Programm, welches einem die vereinfachte Form des Coden lehrt. Es handelt sich hierbei nämlich um die Form des Blockcode. DIes bedeutet, dass man nicht wie bei anderen Sprachen wie Python oder Java den herrkömmlichen Code benutzt, sondern mit verschiedenen Blöcken arbeitet. Diese Blöcke haben einzelen Aufgaben und teilen so den Code sichtbar auf. Mithilfe des Blockcodes, soll es StarlogoTNG den Benutzern das Coden lehren und Verständnisbarrieren minimieren. Durch direkte §-D Darstellung im Nebenfenster kann man ve´rschiedene Blöcke schnell in Ihrer Funktion nachvollziehen und kann ein direktes Ergebnis beobachten. (vgl. https://education.mit.edu/project/starlogo-tng/#:~:text=StarLogo%20TNG%20is%20a%20downloadable%20programming%20environment%20that,3D%20games%20and%20simulations%20for%20understanding%20complex%20systems.)

# Projektentwicklung
Wie ich es bereits in der Einleitung erwähnt habe, hatten wir keine nennenswerte Erfahrungen mit dem Programmieren. Dadurch hat sich auch die Entwicklung unseres Projekts als problematisch herausgestellt. Bevor wir mit unserem Projekt starten konnten, mussten wir uns zuerst die Grundlagen des Programmierens erarbeiten. Dazu hatten wir verschiedene Lerneinheiten von Herr Buhl bekommen, welche mir mit dem Programm bearbeiten konnten. Jedoch war uns bereits schnell klar, dass wir etwas schaffen wollten, was zum allgemeinwohl unserer Gesellschaft beiträgt. Wir wollten etwas schaffen, wovon jeder profitieren kann. Mit dem Hinblick auf die letzten Jahre und durch die Unterstützung der Lerneinheiten hatten wir uns auf das Programmieren der Pandemie geeinigt.
.
# Vorstellung des Projekts
Wie bereits erwähnt, hatten wir uns für das Programmieren einer Pandemie entschieden. Jedoch waren wir uns noch nicht klar, welches Ausmaß diese annehmen sollte. Da StarlogoTNG ein bereits altes Programm ist und dadurch gewisse Kapazitäten gegeben waren, wurden wir leider etwas eingeschränkt. Dies ändert jedoch nicht an der Vielfältigkeit unseres Projektes. Allein der Blick auf die Startseite zeigt, das es unglaublich viele, einstellbare Variablen zum Anpassen gibt. Zudem gibt es viele Graphen, die den Verlauf der Pandemie tracken und bspw. den Gesunden-, Kranken- und Ärzteanteil zeigen.
# Der Code
Da StarlogoTNG den Blockcode verwendet haben wir auch nur eben diesen verwendet. Beim Blockcode hatten wir verschiedene Variablen und Blöcke welche jeweils eine einzigartige Funktion haben. 
Bei StarlogoTNG beginnt ein jder Code mit dem Setup Block
  <details>
  <summary>Startbildschirm Starlogo TNG</summary>
  

![image](https://user-images.githubusercontent.com/111464150/207886335-a2dfe999-7ef5-4abf-b083-cbb4927b824e.png)
</details>
In unserem  Setupblock kreieren wir vier verschiedene Agenten: den Menschen, den Arzt, das Geld und das Krankenhaus. Im Setupblock für den Menschen ist zuallererst die Anzahl angeben. Zudem wird die Population direkt in Gesunde und Kranke aufgeteilt. Die Gesunden sind Blau und die Kranken sind rot. Dadurch kann man es ersichtlich machen, welcher Anteil der Population krank ist und welcher gesund ist. Zudem wird der Kontostand  aller Menschen auf null gesetzt. 
Beik Setupblock des Arztes kann man erkennen, dass zuerst 1 Arzt existiert. DIeser ist gesund und kann nicht krank werden.
Das Geld wurde ebenfalls als immun programmiert und auf halbe größe gesetzt.

Der nächste Block ist der Run Once Block. Dieser wird nur am Anfang ausgeführt und eben nur ein Mal.
  <details>
  <summary>Startbildschirm Starlogo TNG</summary>
  

![image](https://user-images.githubusercontent.com/111464150/207889797-2787a940-d53a-44e6-a6b0-0b69e961315f.png)
</details>

Mit dem run once Block haben wir den Herd angegeben. Der Herd bestimmt den Ausbruch der Krankheit und grenzt Ihn von anfang an in einem bestimmten Bereich ein. Dadurch beginnt der Start der Krankheit in einem bestimmten Radius.

Der nächste Block ist der forever Block
  <details>
  <summary>Startbildschirm Starlogo TNG</summary>
  

![image](https://user-images.githubusercontent.com/111464150/207893005-cc4294b6-0110-4819-ba97-7c770bac52b0.png)
</details>
Der forever Block hat Schleifen für die Agenten Mensch und Arzt. Jedoch haben wir in den forever Block Procedures eingefügt. Dadurch gewinnt unser Programm ein Gewisses Maß an übersichtlichkeit





# Kritik

Da wir zuallererst die Grundlagen des Programmierens erlernen mussten, war uns weniger Zeit gegeben, als denen, die bereits ein breites Verständnis zum Programmieren hatten.
# Ausicht für die Zukunft/ Fazit

Wir denken, dass mithilfe dieses Projektes viele Menschen die Auswirkungen von Krankheiten besser verstehen können. Sie können lernen, Pandemie und Krankheitsverläufe besser nachvollziehen zu können. Sie können lernen, verschiedene Wechselwirkungen innerhalb einer Pandemie zu verstehen. Wir hoffen, dass mithilfe unserer Simulation helfen können, ihr verhalten in einer solchen Situation besser einzuschätzen.

# Quellen

https://education.mit.edu/starlogo-tng-download/
https://education.mit.edu/project/starlogo-tng/

# Eigenständigkeitserklärung
Hiermit erkläre ich, dass ich die vorliegende Arbeit selbstständig verfasst und keine anderen als die angegebenen Quellen und Hilfsmittel benutzt habe.
Alle sinngemäß und wörtlich übernommenen Textstellen aus fremden Quellen wurden kenntlich gemacht.

Elias Michno und Arvid Böse
