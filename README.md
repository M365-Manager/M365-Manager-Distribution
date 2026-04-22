Note: This README is available in both English and French. / Ce README est disponible en anglais et en français.

# 🇬🇧 English Version

## ⚡ M365 Manager - SaaS Synchronization
**M365 Manager** is a standalone desktop application designed to automate and secure the management of Microsoft 365 (Entra ID) accounts for educational institutions and businesses.

Fully data-agnostic, the tool allows you to synchronize a local database (Excel `.xlsx` or CSV file) with your Microsoft Azure tenant via the Graph API, featuring an intelligent identity conflict resolution system.

---

## 🌟 Key Features
- **Native Excel & CSV Support:** Read your data files directly without manual conversion.
- **Dynamic Mapping & Official Lexicon:** Column mapping interface using official Microsoft Entra ID vocabulary.
- **4-Step Simulation Workflow (Dry Run):**
  1. 🔍 **Accounts to review:** Manual resolution of namesake conflicts (Holistic O(N²) Algorithm).
  2. 📝 **Updates:** Precise visualization of differences and modifications (First names, Last names, Departments, etc.).
  3. ✨ **Creations:** Automatic generation of new accounts with standardized email address creation (UPN).
  4. 🗑️ **Deletions:** Secure transfer of obsolete accounts to the Entra ID recycle bin (30-day Soft-Delete).
- **Alias Protection (Zero Loss):** Automatic preservation of old email addresses by Microsoft during name changes.
- **Asynchronous Cloud Execution:** Ultra-fast and secure deployment without freezing the interface.

---

## 🚀 Installation & Download
The application requires **no Python installation** or dependencies on your machine. It is provided as a ready-to-use compiled executable.

1. Go to the **[Releases](../../releases/latest)** section located on the right side of this page.
2. Download the **`main.exe`** (or `M365-Manager.exe`) file.
3. Place the file in the folder of your choice and double-click to launch it.

> [!WARNING]  
> **Windows Security Warning (SmartScreen)**  
> As a recently compiled independent software, this program does not hold a commercial signing certificate. Upon the first launch, **Windows Defender SmartScreen** will block the application as a precaution with a blue screen.
> 
> **To launch the application:**
> 1. Click on **"More info"** (the small underlined text).
> 2. A new button will appear at the bottom. Click on **"Run anyway"**.
> 3. The application will start instantly, and Windows will not ask you again.

---

## ⚙️ Initial Configuration (Azure)
Upon the first launch, the application will prompt you to configure your Microsoft access credentials. You will need your:
- **Tenant ID**
- **Client ID** (Application ID registered on the Azure Portal)

These parameters will be securely stored locally in a `config.json` file created next to the executable.

---

## ©️ Intellectual Property and License
This software is a proprietary work. The source code is closed and natively compiled.
It is strictly forbidden to reverse-engineer, decompile, resell, or modify this software.

Please refer to the `LICENSE.txt` file for the exact terms of the End User License Agreement (EULA).

<br>
<hr>
<br>

# 🇫🇷 Version Française

## ⚡ M365 Manager - Synchronisation SaaS
**M365 Manager** est une application bureau autonome (Stand-alone) conçue pour automatiser et sécuriser la gestion des comptes Microsoft 365 (Entra ID) au sein des établissements scolaires et des entreprises. 

Totalement agnostique, l'outil permet de synchroniser une base de données locale (Fichier Excel `.xlsx` ou CSV) avec votre locataire Microsoft Azure via l'API Graph, en proposant un système de résolution intelligente des conflits d'identité.

---

## 🌟 Fonctionnalités Principales
- **Support Natif Excel & CSV :** Lisez vos fichiers de données directement sans conversion manuelle.
- **Mappage Dynamique & Lexique Officiel :** Interface de liaison des colonnes utilisant le vocabulaire officiel de Microsoft Entra ID.
- **Workflow de Simulation en 4 Étapes (Dry Run) :**
  1. 🔍 **Comptes à vérifier :** Résolution manuelle des conflits d'homonymes (Algorithme Holistique O(N²)).
  2. 📝 **Mises à jour :** Visualisation précise des différences et modifications (Prénoms, Noms, Départements, etc.).
  3. ✨ **Créations :** Génération automatique des nouveaux comptes avec création d'adresses e-mail normalisées (UPN).
  4. 🗑️ **Suppressions :** Envoi sécurisé des comptes obsolètes vers la corbeille Entra ID (Soft-Delete 30 jours).
- **Protection des Alias (Zero Loss) :** Conservation automatique par Microsoft des anciennes adresses e-mails lors des changements de noms.
- **Exécution Cloud Asynchrone :** Déploiement ultra-rapide et sécurisé sans figer l'interface.

---

## 🚀 Installation & Téléchargement
L'application ne nécessite **aucune installation de Python** ou de dépendances sur votre machine. Elle est fournie sous la forme d'un exécutable compilé prêt à l'emploi.

1. Rendez-vous dans la section **[Releases](../../releases/latest)** située à droite de cette page.
2. Téléchargez le fichier **`main.exe`** (ou `M365-Manager.exe`).
3. Placez le fichier dans le dossier de votre choix et double-cliquez pour le lancer.

> [!WARNING]  
> **Avertissement de sécurité Windows (SmartScreen)**  
> En tant que logiciel indépendant récemment compilé, ce programme ne possède pas de certificat de signature commercial. Lors du premier lancement, **Windows Defender SmartScreen** bloquera l'application par précaution avec un écran bleu.
> 
> **Pour lancer l'application :**
> 1. Cliquez sur **"Informations complémentaires"** (le petit texte souligné).
> 2. Un nouveau bouton va apparaître en bas. Cliquez sur **"Exécuter quand même"**.
> 3. L'application démarrera instantanément et Windows ne vous le demandera plus.

---

## ⚙️ Configuration Initiale (Azure)
Lors du premier lancement, l'application vous demandera de configurer vos accès Microsoft. Vous aurez besoin de :
- **Tenant ID** (Identifiant du locataire)
- **Client ID** (Identifiant de l'application enregistrée sur Azure Portal)

Ces paramètres seront sauvegardés de manière sécurisée et locale dans un fichier `config.json` créé à côté de l'exécutable.

---

## ©️ Propriété Intellectuelle et Licence
Ce logiciel est une œuvre propriétaire. Le code source est fermé et compilé nativement.
Il est strictement interdit de rétro-concevoir (reverse-engineer), décompiler, revendre ou modifier ce logiciel. 

Veuillez consulter le fichier `LICENSE.txt` pour les termes exacts de la licence utilisateur final (EULA).
