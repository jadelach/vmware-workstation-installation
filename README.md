# Guide : Installation de VMware Workstation Pro (Usage Personnel)
Ce tutoriel explique comment télécharger, configurer et installer **VMware Workstation Pro** gratuitement depuis l'acquisition par Broadcom.

---
## Inscription sur le portail Broadcom

1. Ouvrez votre navigateur et rendez-vous sur le Broadcom Support Portal.
![image1](images\01-site-broadcom.png)

2. En haut à droite de la page, cliquez sur le bouton Register pour lancer l'inscription.
![image2](images\02-bouton-register.png)

3. Entrez ensuite votre adresse e-mail, complétez le petit captcha de sécurité pour prouver que vous n'êtes pas un robot, et cliquez sur Next.

4. Broadcom va vous envoyer un code de vérification par mail. Allez vite jeter un œil à votre boîte de réception, copiez ce code, puis collez-le sur le site avant de cliquer sur Verify & Continue.

5. Il ne vous reste plus qu'à remplir vos informations de base (comme votre nom et votre mot de passe), à accepter les conditions d'utilisation, et à cliquer sur Create Account.

6. Une fois que le compte de base est créé, le site vous propose d'ajouter d'autres services. Ne vous embêtez pas avec ça pour l'instant : cliquez simplement sur I'll do it later (Je le ferai plus tard).

7. Maintenant que notre compte est prêt, retournez sur support.broadcom.com. En haut à droite, sélectionnez Support Portal et connectez-vous si ce n'est pas déjà fait en cliquant sur Login.

8. Une fois connecté, repérez le menu déroulant en haut de la page et choisissez la division VMware Cloud Foundation. C'est ici que se cachent les logiciels VMware.

9. Dans le menu de gauche, cliquez sur My Downloads. Vous allez voir apparaître un lien hypertexte intitulé 'Free Software Downloads available HERE' (Téléchargements de logiciels gratuits disponibles ICI). Cliquez dessus !

10. Dans la barre de recherche qui s'affiche, tapez simplement 'workstation' et cliquez sur le résultat de recherche correspondant. On cherche la ligne VMware Workstation Pro 17.0 for Windows (ou pour Linux si vous êtes sur cet OS). Choisissez la version de votre choix ; pour ma part, je sélectionne la plus récente pour avoir toutes les dernières nouveautés.

**Attention, voici le piège qui bloque beaucoup de monde ! Avant de pouvoir cocher la case de téléchargement, vous devez impérativement cliquer sur le lien des Terms and Conditions (Termes et conditions). Prenez le temps de l'ouvrir, puis revenez sur la page : la case sera enfin débloquée et vous pourrez la cocher.**

Allez ensuite tout au bout à droite de la ligne. Vous allez y trouver un petit nuage avec une flèche vers le bas. Cliquez dessus.

Avant de lancer le téléchargement, Broadcom va vous demander de remplir un formulaire de profil de livraison pour des raisons de conformité commerciale (le fameux Trade Compliance).

Remplissez honnêtement vos informations personnelles (votre adresse, votre ville et votre code postal). Pour l'onglet obligatoire Company (Entreprise), vu que nous l'utilisons à la maison de manière privée, écrivez simplement 'Personal Use' (Usage personnel) ou 'Home Lab'.

Acceptez les termes de conformité en bas, cliquez sur Submit, et voilà ! Le téléchargement se lance automatiquement. Vous retrouverez le fichier d'installation soit dans le dossier 'Téléchargements' de votre explorateur de fichiers, soit directement en haut à droite dans les téléchargements de votre navigateur web.

Double-cliquez sur le logiciel téléchargé pour lancer l'assistant d'installation. Acceptez le contrat de licence et avancez.

Durant le processus, l'assistant va vous proposer deux options importantes à cocher.

La première est 'Install Windows Hypervisor Platform automatically'. Cochez-la absolument ! Cela permet à VMware de cohabiter correctement avec les fonctionnalités de virtualisation de Windows (comme Hyper-V ou WSL2) sans créer de conflits de performance.

La seconde option est 'Add VMware Workstation console into system path'. Cochez-la également. Cela permet d'ajouter les outils de commande VMware dans les variables d'environnement de votre système, ce qui s'avère super pratique si vous souhaitez plus tard lancer ou contrôler vos machines virtuelles directement depuis un terminal ou un script.

À l'étape suivante, je vous conseille de laisser cochée la première option pour vérifier la présence de mises à jour automatiques au démarrage, mais vous pouvez décocher la seconde option, sauf si vous tenez absolument à envoyer des données anonymes pour participer au programme d'amélioration de VMware.

Choisissez ensuite si vous voulez un raccourci sur votre bureau et/ou dans votre menu Démarrer, puis cliquez sur Install.

(Optionnel si pertinent à l'écran) : Lors du tout premier lancement après l'installation, le logiciel vous demandera si vous avez une clé ou si vous l'utilisez pour un usage personnel. Sélectionnez bien l'usage personnel pour l'activer gratuitement à vie!

Et voilà, c’est tout ! Vous avez désormais un VMware Workstation Pro officiel, complet, performant et surtout 100 % gratuit pour toutes vos futures expérimentations
