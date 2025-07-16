<h1 align="center" style="font-weight: bold;">Todo Notepad Pipeline</h1>

<h2 id="technologies">Les objectifs de chaque étape:</h2>

<h3>Le build :</h3>

1. Set up JDK 21 : permet de télécharger le JDK sur la machine ubuntu-latest
2. Project's checkout : permet de scanner et de copier l'intégralité du projet
3. Cache local Maven repository: permet de créer un répertoire cache avec les dépendances nécessaires à l'utilisation de l'application
4. Install dependencies : installation des dépendance Maven
5. App build : build de l'app dans un .jar
6. Upload built artifact : téléchargement du .jar sur GitHub
7. Github Release: ajout de la release sur github
