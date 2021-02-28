# MapReduce_K-means
Implémentation de l'algorithme de clustering k-means utilisant le framework MapReduce (Hadoop version 3.1.3).

Compiler et construire .jar
======

Pour éxecuter vos programmes Hadoop Java, il faudra générer un .jar, puis le copier sur la
machine virtuelle pour l’exécuter sur Hadoop, en premier lieu il faut faire une connexion
SSH avec machine virtuelle, en utilisant un outil très connu c’est PuTTY, deuxièmement
pour transférer votre fichiers qui existent dans votre machine physique vers votre machine
virtuelle il faut utiliser WinSCP.

 ### 1) Utilisation de PuTTY:
 
 
PuTTY : est un émulateur de terminal doublé d'un client pour les protocoles SSH, Telnet, rlogin, et TCP brut. Il permet également des connexions directes par liaison série RS-232. À l'origine disponible uniquement pour Windows, il est à présent porté sur diverses plates-formes Unix.
Après l’installation de PuTTY, lancer l’émulateur et une fenêtre sera déclenché :

<img style="display:inline;" src="https://www.mediafire.com/convkey/a1e7/zmdtmwd5qini1svzg.jpg">

*	Pour connecter avec votre machine virtuelle, il faut taper adresse ip de la machine virtuelle et Port (c'est par défaut =22)

### 2) Utilisation de WinSCP :

<p style="text-align=justify"> WinSCP : est un client SFTP graphique pour Windows. Il utilise SSH et est open source. Le protocole SCP est également supporté. Le but de ce programme est de permettre la copie sécurisée de fichiers entre un ordinateur local et un ordinateur distant.
Quand on ouvre WinSCP, il déclenche une fenêtre de connexion, il suffit d’entrer l’adresse ip de votre machine virtuelle et port (qui est par défault =2), aussi nom de l’utilisateur = mbds, et password = password. </p>

