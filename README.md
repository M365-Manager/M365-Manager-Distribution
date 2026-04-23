Note: This README is available in both English and French. / Ce README est disponible en anglais et en français.

# 🇬🇧 English Version

## ⚡ EntraSync - Excel to Entra ID Provisioning
*M365 Manager is now EntraSync!*

**EntraSync** is a standalone desktop application designed to automate and secure the management of Microsoft 365 (Entra ID) accounts. It intelligently bridges the gap between your local database (Excel/CSV) and your Microsoft Azure tenant.

---

## 🌟 Key Features
- **Native Excel & CSV Support:** Read data directly without conversion.
- **4-Step Simulation (Dry Run):** Review namesake conflicts (O(N²) Algorithm), updates, creations, and safe deletions.
- **Asynchronous Execution:** Fast deployment without freezing the UI.

---

## ⚙️ Azure Configuration (Required Permissions)
To use EntraSync, you must register an application on the Azure Portal with the following Microsoft Graph API (Application) permissions:
- **User.ReadWrite.All** (To create/update/delete users)
- **Directory.ReadWrite.All** (To manage directory objects and group memberships)

---

## 🚀 Installation
1. Go to the **[Releases](../../releases/latest)** section.
2. Download **`EntraSync-v1.0.0.exe`** (or the `.zip` file for Mac/Windows).
3. **Security Note:** Windows SmartScreen may block the launch. Click "More info" then "Run anyway".

---

## ©️ Intellectual Property and License
This software is a proprietary work. The source code is closed and natively compiled.
It is strictly forbidden to reverse-engineer, decompile, resell, or modify this software.

Please refer to the `LICENSE.txt` file for the exact terms of the End User License Agreement (EULA).

<br>
<hr>
<br>

# 🇫🇷 Version Française

## ⚡ EntraSync - Synchronisation Excel vers Entra ID
*M365 Manager devient EntraSync !*

**EntraSync** est une application bureau autonome conçue pour automatiser et sécuriser la gestion des comptes Microsoft 365 (Entra ID). Elle fait le pont intelligemment entre votre base locale (Excel/CSV) et votre locataire Azure.

---

## 🌟 Fonctionnalités Principales
- **Support Natif Excel & CSV :** Lecture directe sans conversion.
- **Workflow en 4 Étapes (Dry Run) :** Résolution des homonymes (Algorithme O(N²)), visualisation des mises à jour, créations et suppressions sécurisées.
- **Exécution Asynchrone :** Déploiement rapide sans figer l'interface.

---

## ⚙️ Configuration Azure (Permissions requises)
Vous devez enregistrer une application sur le portail Azure avec les permissions Microsoft Graph API (Application) suivantes :
- **User.ReadWrite.All** (Pour créer/modifier/supprimer les utilisateurs)
- **Directory.ReadWrite.All** (Pour gérer les objets de l'annuaire)

---

## 🚀 Installation
1. Rendez-vous dans la section **[Releases](../../releases/latest)**.
2. Téléchargez **`EntraSync-v1.0.0.exe`** (ou le fichier `.zip` pour Mac/Windows).
3. **Note de sécurité :** Windows SmartScreen peut bloquer le lancement. Cliquez sur "Informations complémentaires" puis "Exécuter quand même".

---

## ©️ Propriété Intellectuelle et Licence
Ce logiciel est une œuvre propriétaire. Le code source est fermé et compilé nativement.
Il est strictement interdit de rétro-concevoir (reverse-engineer), décompiler, revendre ou modifier ce logiciel. 

Veuillez consulter le fichier `LICENSE.txt` pour les termes exacts de la licence utilisateur final (EULA).
