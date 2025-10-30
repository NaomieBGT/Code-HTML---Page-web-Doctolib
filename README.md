Confirmation de rendez-vous - Modèle Doctolib
----------------------------------------------
Ce projet contient une maquette HTML d’e-mail de confirmation de rendez-vous, inspirée du style Doctolib.
L’objectif est de proposer un design d’e-mail clair, professionnel et compatible avec la plupart des clients de messagerie.
----------------------------------------------
Contenu du projet

index.html : Page principale contenant le modèle d’e-mail

Structure basée sur des balises <table> pour garantir la compatibilité e-mail

Éléments inclus :

Logo Doctolib

Message de rappel personnalisé

Boutons d’action (« Voir mon rendez-vous », « Ouvrir le centre d’aide »)

Pied de page avec mentions légales

Aperçu
--------------------------------------------
Exemple d’affichage :

"Bonjour Naomie, votre rendez-vous avec le Dr Dupont est prévu le 5 novembre à 14h."
L’e-mail contient un bouton cliquable et un visuel rappelant les communications officielles de Doctolib.

Comment visualiser

Télécharger le fichier index.html

L’ouvrir dans un navigateur web (double-clique sur le fichier)

Le rendu affichera l’e-mail tel qu’il apparaîtrait dans une boîte de réception

Objectif
---------
Ce modèle peut être utilisé :

Pour des tests d’intégration d’e-mails HTML

Dans un projet d’apprentissage du design d’e-mails responsives

Comme base pour des notifications automatiques dans une application web

Licence
-------
Projet libre d’utilisation à des fins éducatives.
© 2025 - Créé par NaomieBGT
-----------------------------------------------
README (English)
Appointment Confirmation — Doctolib-Inspired Template

This project contains an HTML email template inspired by Doctolib’s communication style.
It demonstrates how to build a clean, professional, and email-compatible layout for appointment reminders.

Project Content

index.html: Main file containing the email layout

Table-based structure for email compatibility

Includes:
----------
Doctolib logo

Personalized reminder message

Call-to-action buttons ("View my appointment", "Open help center")

Footer with copyright notice

Preview
--------
Example message:

"Hello Naomie, your appointment with Dr. Dupont is scheduled for November 5 at 2 PM."
The email includes a clickable button and visuals inspired by Doctolib’s design.

How to View
---------------------------------------------
Download the index.html file

Open it in your web browser (double-click the file)

The layout will display as it would appear in an email inbox

Purpose

This template can be used for:

HTML email integration testing

Learning responsive email design

Creating automated notification systems in web applications

License

Free for educational and personal use.
© 2025 — Created by NaomieBGT
------------------------------------------------------
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Confirmation rendez-vous Doctolib</title>
<link rel="icon" type="image/png" href="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzPzCkr1hsWyW2mhNapG5PwLLAMWgrkzg9SA&s">
</head>
  <body style="font-family: Arial; background-color: #f8f9fa; margin: 0; padding: 0;">
    <table align="center" width="600" style="background: white; border-radius: 8px; overflow: hidden;">
      <tr>
        <td style="background-color: #0d6efd; color: white; padding: 20px; text-align: center;">
          <h1>Rappel Rendez-Vous</h1>
        </td>
      </tr>
      <tr>
        <td style="padding: 20px; text-align: center;">
          <img src="https://latestlogo.com/wp-content/uploads/2024/02/doctolib-logo.png" alt="Doctolib" width="100" />
          <h2>Votre prochain rendez-vous approche !</h2>
          <p>Bonjour Naomie,</p>
          <p>Votre rendez-vous avec le Dr Dupont est prévu le <strong>5 novembre à 14h</strong>.</p>
          <a href="#" style="background-color: #0d6efd; color: white; text-decoration: none; padding: 10px 20px; border-radius: 4px;">Voir mon rendez-vous</a>
        </td>
      </tr>
      <tr>
        <td style="background-color: #f1f1f1; padding: 10px; text-align: center; font-size: 12px;">
          © 2025 Doctolib. Tous droits réservés.
	    </td>
      </tr>
	  <tr>
	    <td style="padding: 15px; text-align: center;">
			  <img src ="https://tse1.mm.bing.net/th/id/OIP.EJFpYGq4iKM1uwKKCq-zwwHaFt?pid=ImgDet&w=474&h=365&rs=1&o=7&rm=3" width="350"/>
		   <p><strong>Des question?</strong> Consultez notre Centre d'aide ou contactez-nous</p>
	  <a href="#" style="background-color: #0d6efd; color: white; text-decoration: none; padding: 10px 20px; border-radius: 4px;">Ouvrir le centre d'aide</a>
        </td>
      </tr>
    </table>
  </body>
</html>
