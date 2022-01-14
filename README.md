# app-salaire
Évaluation Ansible &amp; Jenkins

Vous êtes engagé en tant qualité d’ingénieur DevOps Freelance. Votre client a besoin d'une application de gestion de salaire de ses employés. Le client possède déjà le code PHP de l'application. Cette dernière étant développée en PHP. Vous devez donc déployer un serveur web avec son module PHP et la communication avec une base de données afin de conserver les données.


Il souhaite pouvoir déployer cette application avec les outils Ansible et Jenkins, à partir d'un dépôt GIT. Et ainsi pouvoir reproduire la procédure.
Votre mission est alors la mise en œuvre d'un Pipeline Jenkins depuis d'un dépôt git. Ce pipeline doit permettre le déploiement de l'application Web de gestion des salaires avec l'outil Ansible.


Vous devez alors fournir :

    - Un dépôt GIT nommé : app-salaire.
        Ce dernier doit contenir : 
            - Le fichier Jenkins de pipeline, 
            - les rôles Ansible (Rôles Apache, php, mariadb),
            - le code php (https://github.com/ludovic-tech/app-php),
            - la procédure documentée en format PDF.


Application Web : web.votre- prenom.form.
Serveur de BDD : db.votre-prenom.form.


L'environnement du client est sous Linux CentOS 7.
Le déploiement de l'application avec Ansible, utilise les noms de serveurs et non pas les adresses IP. 
Le déploiement de l'application avec Ansible doit s'exécuter en tant qu'utilisateur non root.
