# "Einstieg in Linux" Workshop

Workshop zu Installation und erste Schritte in Linux am [CoderDojo Potsdam](https://coderdojopotsdam.github.io/).

In der ersten Iteration des Workshops, in 2026, haben wir [Linux Mint mit Xfce](https://www.linuxmint.com/download.php) genutzt. Wir haben uns für Mint entschieden, um den Umstieg von anderen Betriebssystemen, wie z. B. Windows-Systemen, möglichst einfach zu gestalten. Wir haben uns für Xfce als Oberfläche entschieden, da diese besonders ressourcenschonend ist. Wenn ihr Linux zu Hause ausprobieren möchtet, ist euer Gerät vermutlich etwas neuer als unsere Laptops und ihr könnt gerne auch eine andere Oberfläche wählen.


## Hinweise zu der Installation

* Folie 3: Bios-Bootauswahl öffnen: bei unseren Laptops ist es die F12-Taste. Das ist aber von Gerät zu Gerät unterschiedlich. Recherchiert also ggf. für euer Gerät, welche Taste es ist.

* Folie 5: um Linux einfach mal auszuprobieren müsst ihr es nicht sofort installieren. In dem Live-System, in dem ihr euch nach dem Start befindet, könnt ihr alles erst einmal ausprobieren. Beachtet jedoch, dass beim Herunterfahren alle Installationen oder Konfigurationen die ihr gemacht habt wieder weg sind. Auch werden keine Dateien dauerhaft gespeichert.

* Folie 10: 
    * Achtung! Wir haben im Workshop einfach die komplette Festplatte gelöscht und dann Linux installiert, da wir wissen, dass auf den Geräten nichts gespeichert ist, was wir ggf. in der Zukunft brauchen. Überlegt bei eurem Gerät, ob es das ist was ihr möchtet. Wenn ihr zu Linux umsteigen möchtet behaltet ggf. zunächst das andere Betriebssystem eine Zeit lang parallel.
    * LVM steht für _logical volume manager_ und erlaubt es, Partitionen am laufenden System zu ändern, z. B. die Größe der Partition zu ändern. Zudem erlaubt es euch die Partitionen zu verschlüsseln. Im Workshop haben wir das nicht eingerichtet, da wir es nicht benötigen - im Dojo installieren wir bei Bedarf einfach neu. Für den Heimgebrauch sind beide Features aber durchaus interessant.
    

## Hinweise zur Nutzung des Terminals

Im Workshop haben wir recht viel Zeit im Terminal verbracht. Takeaway sollte hier nicht sein, dass man Linux nicht grafisch nutzen kann - im Gegenteil. Hierzu haben wir ja auch extra Linux mit einer grafischen Oberfläche installiert. Was ihr hingegen mitnehmen solltet: es gibt viele kleine Programme, die jedes für sich eine konkrete Aufgabe erfüllen und die auch kombiniert werden können. Die Programme zur Dateiverwaltung haben wir im Workshop genutzt, da sie einfach zu verstehen sind und das Ergebnis sichtbar und nachvollziehbar ist. Außerdem können viele der Programme direkt in [bash](https://en.wikibooks.org/wiki/Bash_Shell_Scripting) eingebunden werden, dem Linux-Pendant zur Automatisierung mit [batch](https://de.wikibooks.org/wiki/Batch-Programmierung) unter Windows. Wenn ihr also jetzt schon Skripte nutzt, um einige Aufgaben automatisiert durchzuführen, könnt ihr diese vermutlich mit wenigen Änderungen auch unter Linux nutzen.

