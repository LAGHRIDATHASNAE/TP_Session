# TP_Session

Ce TP consiste à implémenter les fonctionnalités d'inscription, d'authentification et de changement de mot de passe tout en utilisant JSP et Hibernate.

Cet exercice a pour architecture:

ma.projet
1)classes(User,Client,Employe)
2)services(ClientService,EmployeService)
3)config(hibernate.cfg.xml)
4)util(HibernateUtil)
5)Test(Test --> plusieurs fichiers réparties, chaque entité a son fichier de test/ manipulation avec la base de données/ l'affichage composé des méthodes définies au niveau du couche service.
6)dao(IDao)
7)controllers(AuthentificationController.java,ClientController.java,DeconnexionController.java,PasswordController.java,UpdatePasswordController.java,VerificationController.java)

Pour base de données, veuillez créer la base de données : authentification


Concernant la couche présentation, voici une petite présentation des différentes interfaces de cette application:


1)InscriptionClient.jsp: Cette interface permet à l'utilisateur de s'inscrire et créer un nouveau compte:
![Capture d’écran (119)](https://github.com/LAGHRIDATHASNAE/TP_Session/assets/148015530/0fbd52d8-f941-4fff-8a40-d0095dc94773)

2)authentification.jsp: de se connecter
![Capture d’écran (122)](https://github.com/LAGHRIDATHASNAE/TP_Session/assets/148015530/38700206-e1fa-4a3b-91ee-8f252fc394ea)

3)Welcome.jsp: l'affichage de cette page avec le nom signifie que l'authentification est bien faite.
![Capture d’écran (121)](https://github.com/LAGHRIDATHASNAE/TP_Session/assets/148015530/3884c7d7-7e1e-4d90-acbf-dc635aad2a74)

4)updatepassword.jsp: Intégration d'email afin d'envoyer le code de vérification
![Capture d’écran (123)](https://github.com/LAGHRIDATHASNAE/TP_Session/assets/148015530/d36f5452-cd86-43e3-ac20-8067f7745378)

5)Verification.jsp: l'insertion de code de vérification
![Capture d’écran (124)](https://github.com/LAGHRIDATHASNAE/TP_Session/assets/148015530/ce233feb-4062-462a-a736-954b84749b14) 

6)updatemotddepasse.jsp: pour pouvoir modifier le mot de passe.
![Capture d’écran (125)](https://github.com/LAGHRIDATHASNAE/TP_Session/assets/148015530/aa621f24-e334-4215-8cca-410d870b9f8b)



    
