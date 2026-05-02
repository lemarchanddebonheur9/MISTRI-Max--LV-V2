🤖 MISTRI-MaX

Votre Intelligence Artificielle Personnelle pour Développer des Projets Numériques avec des Équipes d'Agents

Créé par Le Marchand de Bonheur (Le Pont des Savoirs - E.A.G.1)
Inspiré par les travaux de Laurent Voanh



🌟 Fonctionnalités

✅ Multi-Agents : Orchestration d'équipes d'agents IA pour des workflows complexes.
✅ RAG Avancé : Recherche vectorielle avec Orama + mistral-embed (1024 dimensions).
✅ Upload de Fichiers : Support des PDF, DOCX, XLSX, CSV, TXT, MD (avec lazy loading).
✅ Streaming SSE : Réception token par token avec curseur néon animé.
✅ Mémoire Persistante : Historique des conversations stocké en localStorage.
✅ Sécurité Renforcée : DOMPurify, CSP, chiffrement AES-GCM pour les API keys.
✅ Suivi des Coûts : Compteur de tokens et coût estimé par modèle Mistral.
✅ Export des Conversations : Markdown, HTML, ZIP (avec JSZip).
✅ Accessibilité : ARIA labels, prefers-reduced-motion, focus visible.
✅ Design Cyber : Thème futuriste avec couleurs néon et animations fluides.



🚀 Démarrage Rapide





Télécharger le fichier [mistrimax.html](mistrimax.html).



Ouvrir dans un navigateur moderne (Chrome, Firefox, Edge).



Configurer votre clé API Mistral :

 // Dans le code, remplacez par votre clé :
 MISTRI_MAX_CONFIG.apiKey = "votre-clé-api-mistral";



Commencer à chatter avec MISTRI-MaX !



🛠️ Architecture





Frontend : HTML5, CSS3, JavaScript (ES6+).



Backend : Aucune dépendance serveur (100% client-side).



Dépendances :





Bootstrap 5.3.3 (UI).



Orama (RAG vectoriel).



DOMPurify (sécurité XSS).



JSZip (export ZIP).



Papa Parse (CSV).



SheetJS (XLSX).



Mammoth (DOCX).



pdf.js (PDF).



📂 Structure du Projet

mistrimax.html    # Fichier principal (single-file)
README.md         # Documentation



🔧 Configuration

Clé API Mistral

MISTRI-MaX utilise l'API Mistral pour les modèles de langage. Vous devez :





Obtenir une clé API sur Mistral AI.



La stocker dans localStorage sous la clé MISTRI_MAX_API_KEY :

 localStorage.setItem('MISTRI_MAX_API_KEY', 'votre-clé');

Modèles Disponibles

Les modèles sont chargés dynamiquement depuis l'API Mistral. En cas d'échec, une liste hardcodée est utilisée :





mistral-tiny



mistral-small-2508



mistral-medium-2508



voxtral-mini-tts-2603



devstral-2-2512



🎨 Personnalisation

Thème

MISTRI-MaX utilise un thème cyber avec des couleurs néon. Vous pouvez modifier les variables CSS dans le <head> :

:root {
  --cyan: #00e5ff;    /* Couleur principale */
  --neon: #00ff9d;    /* Couleur secondaire */
  --void: #020509;    /* Fond sombre */
}

Comportement





Température : Ajustez MISTRI_MAX_CONFIG.temperature (0.0 à 1.0).



Tokens Max : Modifiez MISTRI_MAX_CONFIG.maxTokens.



🔒 Sécurité





CSP : Content Security Policy stricte pour éviter les attaques XSS.



DOMPurify : Nettoyage de tout contenu HTML injecté.



Chiffrement : Les clés API sont chiffrées avec AES-GCM (WebCrypto).



Validation : Toutes les entrées utilisateur sont validées.



📜 Licence

Open Source - Libre d'utilisation, de modification et de distribution.
Inspiré par les travaux open-source de Laurent Voanh.



🙏 Remerciements





Mistral AI pour les modèles de langage.



Laurent Voanh pour l'inspiration architecturale.



Le Pont des Savoirs - E.A.G.1 pour le soutien.



📧 Contact

Pour toute question ou collaboration :





Le Marchand de Bonheur créateur de  www.etheravolt.fr



GitHub : [À venir] (lien vers votre dépôt)

