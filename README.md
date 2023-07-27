# RasspberryPi-Smart-IDS

Ce travail vise à découvrir les systèmes de détection d’intrusion et leur fonctionnement lors de la surveillance d’un réseau.
Pour étudier de près cet outil de surveillance, une solution simple et efficace sera proposée en combinant le célèbre nano-ordinateur : le Raspberry Pi et le fameux système de détection d’intrusion : Suricata. 
Il est vrai que cette solution concerne les petits réseaux mais elle peut s’étendre après aux réseaux à grande échelle on remplacant le Raspberry PI par un serveur.
Ensuite, on examinera l’impact de l’intelligence artificielle et les techniques de Machine Learning sur ces systèmes qui peuvent devenir plus intelligents et plus performants. En essayant finalement de construire un modèle basé ces nouvelles technologies pour une atteindre un niveau élevé de sécurité réseau.

Il est vrai qu’il peut être difficile de détecter les attaques zero-day par Suricata, puisque c’est un IDS basé principalement sur les signatures, et il se peut que ces derniers ne sont pas répertoriées dans sa base de données de signatures comme déjà expliqué précédemment. Pour faire face à cette problématique, nous envisageons de créer un modèle de machine learning qui complètera Suricata. Ce modèle pourra nous permettre de construire un IDS basé sur anomalies, qui va etre par la suite combiné avec suricata pour une détection plus avancée des anomalies.

Nous avons utilisé l’ensemble de données CICIDS2017 ( https://www.kaggle.com/datasets/cicdataset/cicids2017 ) proposé par l’institut canadien de cybersécurité. Il contient à la fois des attaques bénignes et des attaques récentes qui sont similaires aux données réelles capturées sous la forme de fichiers PCAP.
