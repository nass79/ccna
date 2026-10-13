# Day 6

---

Durant cette vidéo, on a appris à analyser le fonctionnement des switches et à observer la communication entre plusieurs appareils avec **Cisco Packet Tracer** :

**PING :** Permet de vérifier si un appareil peut communiquer avec un autre sur le réseau.

**ARP REQUEST :** Message diffusé sur le réseau local pour trouver l'adresse MAC correspondant à une adresse IP.

**ARP REPLY :** Réponse qui permet à l'appareil demandeur de connaître l'adresse MAC recherchée.

**ICMP ECHO REQUEST :** Message envoyé par la commande ping pour vérifier si un appareil est joignable.

**ICMP ECHO REPLY :** Réponse envoyée par l'appareil destinataire pour confirmer la réception du ping.

**UNICAST :** Message envoyé à un seul destinataire.

**BROADCAST :** Message envoyé à tous les appareils du réseau local concerné.

**MAC ADDRESS TABLE :** Table utilisée par le switch pour associer les adresses MAC aux ports correspondants.

**SHOW MAC ADDRESS-TABLE :** Commande Cisco qui permet d'afficher la table MAC du switch.

**CLEAR MAC ADDRESS-TABLE DYNAMIC :** Commande qui permet de supprimer les adresses MAC dynamiques apprises par le switch.

On a utilisé le mode **Simulation** de Cisco Packet Tracer pour observer les messages ARP et ICMP lors d'un ping entre deux PC.

On a également vérifié les tables MAC des switches pour identifier les appareils connectés à leurs ports, puis supprimé les adresses MAC dynamiques.