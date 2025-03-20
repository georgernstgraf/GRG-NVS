# Übungen zu Subnetting

Denken Sie sorgfältig über Standardrouten in Subnetz-Umgebungen nach. Was kann passie-
ren, wenn ein Paket eintrifft, dessen Ziel ein nicht existentes Subnetz ist?

Vergleichen Sie Architekturen, die Subnetz-Adressierung und Router nutzen, um mehrere
Ethernet-Netzwerke zu verbinden, mit einer Architektur, die Bridges gemäß der Beschrei-
bung in Kapitel 2 nutzt. Unter welchen Umständen ist die eine oder andere
Architektur vorzuziehen?

Betrachten Sie eine Site, die sich dazu entschließt, eine Klasse-B-Netzwerkadresse
in Subnetze zu unterteilen, aber dann festlegt, dass manche physische Netzwerke
6 Bits des lokalen Abschnitts zur Identifizierung des physischen Netzwerks nutzen
werden, während andere 8 nutzen. Finden Sie eine Zuordnung der Hostadressen, die
zu zweideutigen Zieladressen führt.

Der Subnetz-Routing-Algorithmus in Abbildung 10.8 durchläuft die Einträge in der
Routing-Tabelle sequenziell, sodass ein Administrator die hostspezifischen Routen
vor netzwerk- oder subnetzspezifischen Adressen eintragen kann. Erfinden Sie eine
Datenstruktur,
welche die gleiche Flexibilität ermöglicht, aber mit Hashing für effiziente
Lookups sorgt
(diese Aufgabe würde von Dave Mills vorgeschlagen).

Obwohl man sehr viel Zeit darin investiert hat, Router-Operationen zu
beschleunigen, läuft
die Software für klassenlose Route-Lookups immer noch langsamer ab, als die Hashing-
Schemata, die für klassenbestimmten Lookups benutzt werden. Untersuchen Sie Daten-
strukturen und Lookup-Algorithmen, die schneller als ein binärer Trie ablaufen.

Ein binärer Trie nutzt ein Bit, um zwischen zwei Child-Knoten eines jeden durchlaufenen
Knotens zu wählen. Unter welchen Umständen führt ein Trie zu schnelleren/langsameren
Lookups?

Wenn alle Internet Service Provider auf die klassenlose Adressierung setzen und
ihren Kunden Adressen aus dem eigenen Adressblock zuordnen, welches Problem
entsteht, wenn ein Teilnehmer von einem Provider zu einem anderen wechselt?
Wenn Router, die Proxy-ARP verwenden, eine Tabelle von Hostadressen nutzen, um
zu entscheiden, ob sie auf ARP-Anforderungen antworten, muss die Routing-Tabelle
immer dann geändert werden, wenn einem dieser Netzwerke ein neuer Host hinzugefügt
wird. Erläutern Sie, wie IP-Adressen vergeben werden können, sodass Hosts hinzugefügt
werden können, ohne die Tabellen zu ändern. Tipp: Denken Sie an Subnetze.

Obwohl der Standard es zulässt, dass eine Subnetznummer aus lauter Nullen bestehen
kann, funktioniert die Software mancher Hersteller nicht richtig, wenn Sie das tun.
Versuchen Sie, ein Subnetz mit lauter Nullen am eigenen Standort einzurichten,
und stellen Sie fest, ob die Route korrekt propagiert wird.

Können transparente Router in Local Area-Netzwerken wie Ethernet eingesetzt werden?
Warum oder warum nicht?

Zeigen Sie, dass Proxy-ARP mit drei physischen Netzwerken benutzt werden kann, die
durch zwei Router aneinander angeschlossen sind.

Betrachten Sie die feste Subnetz-Partition einer Klasse-B-Netzwerknummer, die mindestens
76 Netzwerke zulässt. Wie viele Hosts kann es in jedem Netzwerk geben?

Gibt es jemals einen Sinn, eine Klasse-C-Netzwerkadresse in Subnetze zu unterteilen?
Warum oder warum nicht?

Eine Site, die ihre Klasse-B-Adresse durch die Nutzung des dritten Oktetts als physisches
Netzwerk in Subnetze aufteilen wollte, war enttäuscht, dass es nicht möglich war,
255 bzw. 256 Netzwerke einzurichten. Erläutern Sie dieses.

Entwerfen Sie ein Subnetz-Adressierungsschema für Ihre Organisation, davon ausgehend,
dass Ihnen eine Klasse-B-Adresse zur Verfügung steht.

Ist es vernünftig, dass ein Router sowohl Proxy-ARP als auch die
Subnetz-Adressierung verwendet? Wenn ja, erläutern Sie wie das geht. Wenn nicht,
erklären Sie warum nicht.

Begründen Sie die Aussage, dass jedes Netzwerk, das Proxy-ARP nutzt, für Spoofing-
Angriffe anfällig ist (d.h. dass sich eine beliebige Maschine für eine andere
Maschine ausgeben kann).

Können Sie eine nicht standardisierte Implementierung von ARP entwerfen, die
eine normale Nutzung ermöglicht, jedoch Proxy-ARP unterbindet?

Ein Hersteller hat sich dazu entschlossen, seine IP-Software in die Lage zu
versetzen, die Subnetz-Adressierung zu unterstützen, indem er eine einzige
Subnetzmaske für alle IP-Netzwerkadressen vergibt. Der Hersteller hat seine Standard-IP-Routing-Software
so modifiziert, dass die Überprüfung auf das Vorhandensein von Subnetzen zum
Sonderfall wurde. Finden Sie ein einfaches Beispiel, bei dem diese Implementierung
nicht richtig funktionieren kann (Tipp: Denken Sie an einen Multihomed-Host).

Beschreiben Sie die (seltener) Fälle, in denen die Subnetz-Implementierung aus
der letzten Aufgabe richtig funktionieren kann.

Lesen Sie den Standard, um mehr über Broadcasting in Subnetz-Umgebungen zu erfahren.
Können Sie Subnetz-Adresszuordnungen beschreiben, welche die Nutzung einer einzelnen
Broadcast-Adresse für alle Subnetze ermöglichen?
