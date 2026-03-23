# TP Spring Security - Authentification de Base

Ce projet est une application web Spring Boot démontrant la mise en place d'une couche de sécurité avec **Spring Security** et **Thymeleaf**.

## Fonctionnalités
* **Formulaire de connexion personnalisé** avec CSS moderne.
* **Authentification en mémoire** (In-Memory Authentication).
* **Gestion des accès** : Accès restreint aux pages `/home` pour les utilisateurs connectés.
* **Déconnexion sécurisée** avec redirection.
* **Protection CSRF** activée par défaut.

## Technologies utilisées
* **Java 17**
* **Spring Boot 3.x**
* **Spring Security**
* **Thymeleaf** (Moteur de template)
* **Maven** (Gestionnaire de dépendances)

## Video demo 



https://github.com/user-attachments/assets/4ff6c47b-5abd-44ee-bdf6-7ab1227cd180



## Lien du tp 

http://localhost:8080/login?error

## Architecture de tp 


<img width="521" height="923" alt="Screenshot 2026-03-23 022906" src="https://github.com/user-attachments/assets/d99b69ba-b80b-4c7b-bf8b-c5b4d5841bb0" />
<img width="535" height="954" alt="Screenshot 2026-03-23 022918" src="https://github.com/user-attachments/assets/c3cace59-fe00-4122-9b74-982513f1f133" />


## Prérequis
* JDK 17 ou supérieur.
* Maven installé (ou utiliser le wrapper `./mvnw`).
* IntelliJ IDEA ou tout autre IDE Java.

## Identifiants par défaut
| Utilisateur | Mot de passe | Rôle |
| :--- | :--- | :--- |
| **admin** | **1234** | ADMIN |

## Structure du projet
* `SecurityConfig.java` : Configuration des règles de sécurité et des utilisateurs.
* `HomeController.java` : Gestion des routes (Login, Home).
* `login.html` : Interface de connexion.
* `home.html` : Page d'accueil après succès.
* `style.css` : Design de l'interface.
