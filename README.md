# 🚀 Orbus Virement App - Système de Validation de Factures & Virements

## 📝 Présentation du projet
Ce projet est une solution d'entreprise (B2B) sécurisée conçue pour automatiser et simplifier le flux de validation des demandes de virements et de régularisation de factures. Elle permet à la direction générale (DG) de valider ou rejeter des transactions en temps réel, garantissant une réactivité optimale et une traçabilité complète des flux financiers.

> **Note :** Pour des raisons de confidentialité et de propriété intellectuelle (Gaindé 2000), le code source de ce projet est maintenu privé. Ce dépôt sert de vitrine technique pour présenter l'architecture et l'interface de la solution.

---

## 📸 Captures d'écran & Démo

### Interface Mobile (Application Salariés & Approbations DG)
Voici à quoi ressemble l'application native développée pour le suivi en déplacement :

<img width="300" height="350" alt="Screenshot_20260604_160957_Gallery" src="https://github.com/user-attachments/assets/97aff9d9-ccd1-4a5e-b00e-407e89e72835" />
<img width="300" height="350" alt="Screenshot_20260604_155943_Gallery" src="https://github.com/user-attachments/assets/b4481ad9-19b3-42de-89a4-0920e9b8983c" />
<img width="300" height="350" alt="Screenshot_20260604_155854_Gallery" src="https://github.com/user-attachments/assets/bd15766b-28fd-4d99-a393-dcbd1d92fae5" />
<img width="300" height="350" alt="Screenshot_20260604_155702_Gallery" src="https://github.com/user-attachments/assets/2544b0b1-d387-4539-95f4-4c31b443af93" />
<img width="300" height="350" alt="Screenshot_20260604_155648_Gallery" src="https://github.com/user-attachments/assets/bfe8643b-e800-49ce-9f48-1bf3ad80b55c" />
<img width="300" height="350" alt="Screenshot_20260604_161026_Gallery" src="https://github.com/user-attachments/assets/5e37be8e-b915-490d-957f-d7b619b4dd72" />
*Légende : Écran de validation rapide pour le DG avec options d'approbation/rejet.*

### Tableau de Bord Web (Administration)
Le dashboard web permet le suivi complet des régularisations de factures :
 <img width="823" height="772" alt="2" src="https://github.com/user-attachments/assets/980ce75c-dad4-40ad-8dda-7b8961123675" />
<img width="1563" height="702" alt="5" src="https://github.com/user-attachments/assets/6e82766e-3115-461b-b522-5dd054af7b29" />
<img width="1885" height="850" alt="4" src="https://github.com/user-attachments/assets/b0e22e85-4eba-4e04-b1c1-b0a6a4fce256" />
<img width="1905" height="1021" alt="3" src="https://github.com/user-attachments/assets/a68ecba5-23cb-41e5-934a-893d521468f3" />
<img width="1067" height="883" alt="7" src="https://github.com/user-attachments/assets/52428c1d-fed8-4e75-b818-70553db92da0" />
<img width="1563" height="630" alt="6" src="https://github.com/user-attachments/assets/82959dbc-116c-4d85-8161-34f2717b2afb" />


*Légende : Vue d'ensemble des statistiques financières et des dossiers en attente.*

---

## 🛠️ Stack Technique & Architecture

La solution repose entièrement sur l'écosystème **.NET**, choisi pour sa robustesse, sa sécurité et sa capacité à partager le code métier entre les différentes plateformes :

*   **Back-end :** API REST sécurisée avec **.NET Core** (Architecture en couches, Entity Framework Core).
*   **Front-end Web :** Tableau de bord dynamique développé avec **Blazor** pour une expérience utilisateur fluide sans JavaScript.
*   **Application Mobile :** Application native multiplateforme développée avec **.NET MAUI** (Android / iOS).

---

## ✨ Fonctionnalités Clés
*   **Workflow d'approbation sécurisé :** Notifications en temps réel pour la direction lors d'une nouvelle demande de régularisation.
*   **Gestion des statuts :** Traitement instantané (Validation / Rejet avec motif).
*   **Sécurité :** Chiffrement des données financières et authentification renforcée.

 
