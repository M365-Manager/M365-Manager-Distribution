Note: This README is available in both English and French. / Ce README est disponible en anglais et en français.

# 🇬🇧 English Version

## ⚡ EntraSync - Excel to Entra ID Provisioning
**EntraSync** is a standalone desktop application designed to automate and secure the management of Microsoft 365 (Entra ID) accounts. It intelligently bridges the gap between your local database (Excel/CSV) and your Microsoft Azure tenant.

---

## 🌟 Key Features
- **Native Excel & CSV Support:** Read data directly without conversion.
- **4-Step Simulation (Dry Run):** Review namesake conflicts (O(N²) Algorithm), updates, creations, and safe deletions.
- **Asynchronous Execution:** Fast deployment without freezing the UI.

---

## ⚙️ Azure Configuration (Step-by-Step Guide)
Upon the first launch, the application will prompt you for a **Tenant ID** and a **Client ID**. To obtain these, you must register the application in your Azure Portal. 

Follow these simple steps:

1. **Register the Application:**
   - Go to the **Azure Portal** > **Microsoft Entra ID** > **App registrations**.
   - Click **New registration**. Name it `EntraSync` (or anything you like) and click **Register**.
2. **Configure Authentication:**
   - Go to **Authentication** (left menu) > **Add a platform** > **Mobile and desktop applications**.
   - Check the box for `http://localhost` and click **Configure**.
   - Scroll down to "Advanced settings" and ensure **Allow public client flows** is set to **Yes**.
3. **Grant API Permissions:**
   - Go to **API permissions** > **Add a permission** > **Microsoft Graph** > **Delegated permissions**.
   - Search for and check: `User.ReadWrite.All` and `Directory.ReadWrite.All`.
   - Click **Add permissions**.
   - ⚠️ **Crucial:** Click the **Grant admin consent for [Your Organization]** button to authorize these permissions globally.
4. **Get your IDs:**
   - Go to **Overview** (left menu).
   - Copy the **Application (client) ID** and the **Directory (tenant) ID**. Paste them into the EntraSync application!

---

## 🚀 Installation
1. Go to the **[Releases](../../releases/latest)** section.
2. Download **`EntraSync-Windows.zip`** (or Mac).
3. Extract the `.zip` file and double-click the `.exe` to launch.
4. **Security Note:** Windows SmartScreen may block the launch. Click "More info" then "Run anyway".

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
**EntraSync** est une application bureau autonome conçue pour automatiser et sécuriser la gestion des comptes Microsoft 365 (Entra ID). Elle fait le pont intelligemment entre votre base locale (Excel/CSV) et votre locataire Azure.

---

## 🌟 Fonctionnalités Principales
- **Support Natif Excel & CSV :** Lecture directe sans conversion.
- **Workflow en 4 Étapes (Dry Run) :** Résolution des homonymes (Algorithme O(N²)), visualisation des mises à jour, créations et suppressions sécurisées.
- **Exécution Asynchrone :** Déploiement rapide sans figer l'interface.

---

## ⚙️ Configuration Azure (Guide étape par étape)
Lors du premier lancement, l'application vous demandera un **Tenant ID** (ID de locataire) et un **Client ID** (ID d'application). Pour les obtenir, vous devez déclarer l'application sur votre portail Azure.

Voici la marche à suivre :

1. **Créer l'Application :**
   - Allez sur le **Portail Azure** > **Microsoft Entra ID** > **Inscriptions d'applications** (*App registrations*).
   - Cliquez sur **Nouvelle inscription**. Nommez-la `EntraSync` et cliquez sur **S'inscrire**.
2. **Configurer l'Authentification :**
   - Allez dans **Authentification** (menu de gauche) > **Ajouter une plateforme** > **Applications mobiles et de bureau**.
   - Cochez la case `http://localhost` et cliquez sur **Configurer**.
   - Plus bas, dans "Paramètres avancés", passez **Autoriser les flux clients publics** sur **Oui**.
3. **Accorder les Permissions API :**
   - Allez dans **Autorisations de l'API** > **Ajouter une autorisation** > **Microsoft Graph** > **Autorisations déléguées**.
   - Cherchez et cochez : `User.ReadWrite.All` et `Directory.ReadWrite.All`.
   - Cliquez sur **Ajouter des autorisations**.
   - ⚠️ **Crucial :** Cliquez sur le bouton **Accorder un consentement d'administrateur pour [Votre Organisation]** pour valider les droits.
4. **Récupérer vos identifiants :**
   - Allez dans **Vue d'ensemble** (menu de gauche).
   - Copiez l'**ID d'application (client)** et l'**ID d'annuaire (locataire)**. Ce sont ces deux codes qu'il faut coller dans EntraSync !

---

## 🚀 Installation
1. Rendez-vous dans la section **[Releases](../../releases/latest)**.
2. Téléchargez le fichier **`EntraSync-Windows.zip`** (ou Mac).
3. Extrayez le fichier `.zip` et double-cliquez sur l'application.
4. **Note de sécurité :** Windows SmartScreen peut bloquer le lancement. Cliquez sur "Informations complémentaires" puis "Exécuter quand même".

---

## ©️ Propriété Intellectuelle et Licence
Ce logiciel est une œuvre propriétaire. Le code source est fermé et compilé nativement.
Il est strictement interdit de rétro-concevoir (reverse-engineer), décompiler, revendre ou modifier ce logiciel. 

Veuillez consulter le fichier `LICENSE.txt` pour les termes exacts de la licence utilisateur final (EULA).