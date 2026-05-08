# Cahier des Charges : Projet "AutoGate Smart System" (Smart Garage Door)

## 1. Contexte du Projet
Dans le cadre de l'innovation domotique, ce projet vise à concevoir une solution de garage intelligent (Smart Garage Door) nommée "AutoGate". L'objectif est de remplacer le système d'ouverture classique par une solution connectée, sécurisée et pilotable à distance via smartphone ou interface web.

## 2. Objectifs Principaux
*   **Contrôle à distance :** Permettre l'ouverture et la fermeture de la porte de garage depuis n'importe où.
*   **Sécurité accrue :** Intégrer des notifications en temps réel si la porte reste ouverte anormalement longtemps.
*   **Historique :** Tracer les entrées et sorties (qui a ouvert, à quelle heure).

## 3. Spécifications Techniques
### 3.1. Matériel (Hardware)
*   Microcontrôleur : ESP32 ou Raspberry Pi Pico (avec module Wi-Fi intégré).
*   Capteurs : Capteurs magnétiques d'ouverture statique (Reed switch), capteur ultrason ou capteur de distance.
*   Actionneurs : Module relais 5V/12V pour déclencher le moteur de la porte.

### 3.2. Logiciel (Software)
*   **Backend :** Node.js ou Python (Flask/FastAPI) gérant l'API MQTT/REST.
*   **Frontend :** Dashboard HTML/CSS/JS (React ou Vanilla) pour le contrôle.
*   **Base de données :** SQLite ou Firebase pour stocker l'historique des accès.

## 4. Fonctionnalités Attendues
1.  **Interface de Dashboard :** Boutons visuels (Ouvrir/Fermer), affichage de l'état (Ouverte/Fermée) avec code couleur (Vert/Rouge).
2.  **Automatisation :** Planification d'horaires (ex: fermeture automatique à 22h00).
3.  **Alerte push :** Envoi d'un email ou notification sur smartphone lors des événements critiques.

## 5. Livrables et Planification
*   Semaine 1-2 : Étude de faisabilité et choix des composants.
*   Semaine 3-4 : Prototypage électronique et câblage.
*   Semaine 5-6 : Développement du Dashboard web et de l'API.
*   Semaine 7 : Tests d'intégration et corrections de bugs.
*   Semaine 8 : Livraison finale et soutenance.