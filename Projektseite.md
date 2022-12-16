

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

StarlogoTNG ist ein Programm, welches einem die vereinfachte Form des Coden lehrt. Es handelt sich hierbei nämlich um die Form des Blockcode. DIes bedeutet, dass man nicht wie bei anderen Sprachen wie Python oder Java den herrkömmlichen Code benutzt, sondern mit verschiedenen Blöcken arbeitet. Diese Blöcke haben einzelen Aufgaben und teilen so den Code sichtbar auf. Mithilfe des Blockcodes, soll es StarlogoTNG den Benutzern das Coden lehren und Verständnisbarrieren minimieren. Durch direkte §-D Darstellung im Nebenfenster kann man ve´rschiedene Blöcke schnell in Ihrer Funktion nachvollziehen und kann ein direktes Ergebnis beobachten. (vgl. Quelle 1) Zudem kann man hier das Logo von StarlogoTNG sehen. StarlogoTNG wurde von Mitchel Resnick, Eric Klopfer und anderen des MIT (Massachusetts Institute of Technology) im Jahr 2010 Programmiert und veröffentlicht.
 <details>
  <summary>StarlogoTNG Logo   </summary>
  

![image](https://user-images.githubusercontent.com/111464150/207951571-53d6bd6a-3917-4d70-a869-4920e97b57cb.png)
</details>
<details>
  <summary>MIT Logo   </summary>
  
![image](https://user-images.githubusercontent.com/111464150/207953054-184b39a4-c768-4bdd-ba75-efd8c553aa3b.png)

</details>


# Projektentwicklung
Wie ich es bereits in der Einleitung erwähnt habe, hatten wir keine nennenswerte Erfahrungen mit dem Programmieren. Dadurch hat sich auch die Entwicklung unseres Projekts als problematisch herausgestellt. Bevor wir mit unserem Projekt starten konnten, mussten wir uns zuerst die Grundlagen des Programmierens erarbeiten. Dazu hatten wir verschiedene Lerneinheiten von Herr Buhl bekommen, welche mir mit dem Programm bearbeiten konnten. Jedoch war uns bereits schnell klar, dass wir etwas schaffen wollten, was zum allgemeinwohl unserer Gesellschaft beiträgt. Wir wollten etwas schaffen, wovon jeder profitieren kann. Mit dem Hinblick auf die letzten Jahre und durch die Unterstützung der Lerneinheiten hatten wir uns auf das Programmieren der Pandemie geeinigt.
.
# Vorstellung des Projekts
Wie bereits erwähnt, hatten wir uns für das Programmieren einer Pandemie entschieden. Jedoch waren wir uns noch nicht klar, welches Ausmaß diese annehmen sollte. Da StarlogoTNG ein bereits altes Programm ist und dadurch gewisse Kapazitäten gegeben waren, wurden wir leider etwas eingeschränkt. Dies ändert jedoch nicht an der Vielfältigkeit unseres Projektes. Allein der Blick auf die Startseite zeigt, das es unglaublich viele, einstellbare Variablen zum Anpassen gibt. Zudem gibt es viele Graphen, die den Verlauf der Pandemie tracken und bspw. den Gesunden-, Kranken- und Ärzteanteil zeigen.
# Der Code
Da StarlogoTNG den Blockcode verwendet haben wir auch nur eben diesen verwendet. Beim Blockcode hatten wir verschiedene Variablen und Blöcke welche jeweils eine einzigartige Funktion haben. 

Setup-Block

Bei StarlogoTNG beginnt ein jeder Code mit dem Setup Block.
  <details>
  <summary>setup   </summary>
  

![image](https://user-images.githubusercontent.com/111464150/207886335-a2dfe999-7ef5-4abf-b083-cbb4927b824e.png)
</details>
In unserem  Setupblock kreieren wir vier verschiedene Agenten: den Menschen, den Arzt, das Geld und das Krankenhaus. Im Setupblock für den Menschen ist zuallererst die Anzahl angeben. Zudem wird die Population direkt in Gesunde und Kranke aufgeteilt. Die Gesunden sind Blau und die Kranken sind rot. Dadurch kann man es ersichtlich machen, welcher Anteil der Population krank ist und welcher gesund ist. Zudem wird der Kontostand  aller Menschen auf null gesetzt. 
Beik Setupblock des Arztes kann man erkennen, dass zuerst 1 Arzt existiert. DIeser ist gesund und kann nicht krank werden.
Das Geld wurde ebenfalls als immun programmiert und auf halbe größe gesetzt.

run-once-Block

Der nächste Block ist der Run Once Block. Dieser wird nur am Anfang ausgeführt und eben nur ein Mal.
  <details>
  <summary>run once Block    </summary>
  

![image](https://user-images.githubusercontent.com/111464150/207889797-2787a940-d53a-44e6-a6b0-0b69e961315f.png)
</details>

Mit dem run once Block haben wir den Herd angegeben. Der Herd bestimmt den Ausbruch der Krankheit und grenzt Ihn von anfang an in einem bestimmten Bereich ein. Dadurch beginnt der Start der Krankheit in einem bestimmten Radius.

forever-Block

Der nächste Block ist der forever Block
  <details>
  <summary>forever Block </summary>
  

![image](https://user-images.githubusercontent.com/111464150/207893005-cc4294b6-0110-4819-ba97-7c770bac52b0.png)
</details>
Der forever Block hat Schleifen für die Agenten Mensch und Arzt. Jedoch haben wir in den forever Block Procedures eingefügt. Dadurch gewinnt unser Programm ein Gewisses Maß an übersichtlichkeit
Fangen wir zuerst mit den Procedures für den Menschen an: Mensch Bewegung und Genesen.
  <details>
  <summary> Procedure für Mensch </summary>
  

![image](https://user-images.githubusercontent.com/111464150/207967440-48965e90-2a0b-4a1d-85e6-68e7049370fd.png)
</details>
In der ersten Procedure, wird die Bewegung des Menschen angegeben. Man kann sehen, dass das Movement der Agenten random ist, bis der Agent krank ist. Ab diesem Zeitraum gibt es eine Reichweite. Wenn er diese überschreitet, stirbt er.
Das zweite Procedure gibt den Gensungsvorgang des Menschens an. Dieser gibt jedoch lediglich eine einstellbare Wahrscheinlichkeit für die Genseung an. Mithilfe eines Sliders kann man diese einstellen
 <details>
  <summary>  Slider für Heilungswahrscheinlichkeit </summary>
  

![image](https://user-images.githubusercontent.com/111464150/207968298-6e08b8e5-f1f4-4acd-a2d7-14d8337acee1.png)
</details>

Der andere Teil der forever-Funktion beschäftigt sich mit der Bewegung des Arztes. Der dazugehörige Code ist hier einzusehen:
 <details>
  <summary>   Arzt Bewegung  </summary>
  

![image](https://user-images.githubusercontent.com/111464150/207968689-6a3c968d-db64-4600-a853-fa5255380beb.png)
</details>

Die Bewegung des Arztes zu programmieren war schwer und hat uns einige Zeit gekostet. Häufig sind unerklärliche Fehler aufgetreten, welche behoben werden mussten.
Mit diesem Block haben wir die Bewegung des Arztes programmiert. Und zwar besitzt der Arzt einen gewissen Radius, in welchem er Kranke Agenten riechen kann. Von denen sucht er sich einen Agenten aus und bestimmt dessen Nummer. Der Arzt weiß somit die X- und Y-Koordinaten des Kranken und verfolgt diesen. Durch eine höhere Geschwindigkeit holt er die Kranken ein. Bei Berührung werden die Kranken Agenten automatisch gesund. Sobald er seinen Patienten geheilt hat oder dieser zuvor verstorben ist, sucht sich der Arzt einen neuen kranken Agenten. Wenn am Ende alle geheilt sind und es keine Kranken mehr gibt, sagen alle Ärzte "Alle geheilt"

Collision-Blöcke

Ein weiterer wichtiger Block sind die Collision-Blöcke.
Collision-Blöcke beschreiben, was bei einem zusammentreffen Zweier Agenten passiert. Dabei haben wir vier verschiedene Collision-Blöcke.
Der erste ist der Collisionblock Mensch-Mensch.
 <details>
  <summary> Collisionblock Mensch-Mensch     </summary>
  

![image](https://user-images.githubusercontent.com/111464150/207971087-7f4d7b6b-ac7a-42bd-bbf5-384f15b59e7f.png)
</details>
Dabei handelt es sich um eine Collision zwischen einem kranken und einem gesunden Patienten. Mit dem if-Block wird gechecked, ob der der Agent gesund ist. Wenn dies der Fall ist und mit einem Kranken kollidiert hat er eine random Ansteckungswahrscheinlichkeit. DIese kann man mithilfe eines Silders festlegen. Falls der Fall zutrifft und der Agent krank wird, ändert man mit dem Block set istKrank = true seinen Staus. Für die Optik ändert sich auch die Farbe des Agenten auf Rot

Der zweite Collision Block beschäftigt sich mit der Kollision eines Kranken Agenten und dem Krankenhaus
 <details>
  <summary> Collisionblock Kranker Agent-Krankenhaus     </summary>
  

![image](https://user-images.githubusercontent.com/111464150/208060775-be87c3ac-cd2a-48dc-bb02-aed423437673.png)
</details>
Dabei wird geprüpft, ob der Agent Krank ist. Wenn dies der Fall ist, werden die Patienten in das Krankenhaus reingelassen. Jedoch gibt es einen gewissen Einlass, welcher sich pro Agent um einen vermindert. Wenn dieser auf null ist, werden nur noch Agenten in das Krankenhaus gelassen, welche 3 oder mehr Coins aufgesammelt haben. Auf beide Weisen werden die Agenten geheilt und auf die Farbe blau umgeändert.

Die nächste Collision ist eine kurze und beschreibt  das kollidieren zwischen einem Agenten und dem Geld
<details>
  <summary> Collisionblock  Agent-Geld     </summary>
  

![image](https://user-images.githubusercontent.com/111464150/208061435-3fceb7af-30c2-43a6-9c76-38f0dfb87cdc.png)
</details>

In dem Block wird lediglich angegeben. das der Geldblock beim berühren verschwindet und die Geldanzahl des jeweiligen Agenten sich um einen erhöht.







# Kritik

Da wir zuallererst die Grundlagen des Programmierens erlernen mussten, war uns weniger Zeit gegeben, als denen, die bereits ein breites Verständnis zum Programmieren hatten.Denoch denken wir, das manche Abläufe nicht ganz geschmeidig Laufen und noch verbessert werden können. Ein Beispiel ist das "Spawnen" der Coins, also des Geldes. Das Geld wird benötigt, damit die Kranke im Krankenhaus genesen können. Dabei wird von Agenten das Geld "gespawnt". Im echten Leben ist dies natürlich nicht so. Auch haben wir Ärzte die kranken Patienten hinterherlaufen-
VIDEO
Im der Realität wären Ärzte in einer Pandemie ein hoch geschätztes Gut, wodurch Patienten eher zu Ihnen laufen sollten. DIes haben wir jedoch durch das Krankenhaus dargestellt, in welchem sich auch Kranke Agenten heilen lassen können
# Ausicht für die Zukunft/ Fazit

Wir denken, dass mithilfe dieses Projektes viele Menschen die Auswirkungen von Krankheiten besser verstehen können. Sie können lernen, Pandemie und Krankheitsverläufe besser nachvollziehen zu können. Sie können lernen, verschiedene Wechselwirkungen innerhalb einer Pandemie zu verstehen. Wir hoffen, dass mithilfe unserer Simulation helfen können, ihr verhalten in einer solchen Situation besser einzuschätzen.

# Quellen

https://education.mit.edu/project/starlogo-tng/#:~:text=StarLogo%20TNG%20is%20a%20downloadable%20programming%20environment%20that,3D%20games%20and%20simulations%20for%20understanding%20complex%20systems

https://education.mit.edu/starlogo-tng-download/

https://education.mit.edu/project/starlogo-tng/
 

# Eigenständigkeitserklärung
Hiermit erkläre ich, dass ich die vorliegende Arbeit selbstständig verfasst und keine anderen als die angegebenen Quellen und Hilfsmittel benutzt habe.
Alle sinngemäß und wörtlich übernommenen Textstellen aus fremden Quellen wurden kenntlich gemacht.

Elias Michno und Arvid Böse
