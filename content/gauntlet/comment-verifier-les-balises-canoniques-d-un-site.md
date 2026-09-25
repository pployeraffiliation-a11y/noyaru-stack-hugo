+++
url = "/gauntlet/comment-verifier-les-balises-canoniques-d-un-site/"
title = 'Comment verifier les balises canoniques d un site'
html_attrs = ' lang="fr"'
raw_head = '''
  <!-- PAGE DE CONTENU : guide sur la verification des balises canoniques. Page saine, sans anomalie volontaire. -->
  <meta name="viewport" content="width=device-width" />
  <title>Comment verifier les balises canoniques d'un site</title>
  <meta name="description" content="Guide pratique pour verifier les balises canoniques d'un site : ou les trouver, quelles erreurs surveiller et comment les controler a l'echelle du crawl." />
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/comment-verifier-les-balises-canoniques-d-un-site" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Comment verifier les balises canoniques d'un site" />
  <meta property="og:description" content="Guide pratique pour verifier les balises canoniques d'un site : ou les trouver, quelles erreurs surveiller et comment les controler a l'echelle du crawl." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/comment-verifier-les-balises-canoniques-d-un-site" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Comment verifier les balises canoniques d'un site" />
  <meta name="twitter:description" content="Guide pratique pour verifier les balises canoniques d'un site : ou les trouver, quelles erreurs surveiller et comment les controler a l'echelle du crawl." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Comment verifier les balises canoniques d'un site</h1>
  <p>La balise canonique indique aux moteurs de recherche quelle URL fait autorite quand plusieurs adresses affichent un contenu identique ou tres proche. Une balise mal posee peut faire ignorer la bonne page ou en dupliquer plusieurs. Verifier ces balises regulierement evite ces pertes.</p>

  <h2>Ou trouver la balise</h2>
  <p>La balise se place dans la section head du document, sous la forme d'un element link avec l'attribut rel egal a canonical et un attribut href pointant vers l'URL de reference. Pour l'inspecter, ouvrez le code source de la page dans le navigateur et recherchez la chaine rel="canonical".</p>

  <h2>Les controles a mener</h2>
  <ul>
    <li>Verifier qu'il existe une seule balise canonique par page : plusieurs declarations concurrentes se neutralisent.</li>
    <li>Confirmer que l'URL indiquee est absolue, avec le protocole et le domaine complets, plutot qu'un chemin relatif.</li>
    <li>S'assurer que l'URL cible repond bien en code 200 et non par une redirection ou une erreur.</li>
    <li>Controler la coherence entre la balise, le domaine reel et la version choisie (avec ou sans www, http ou https).</li>
    <li>Verifier qu'une page ne pointe pas sa canonique vers une page sans rapport thematique.</li>
  </ul>

  <h2>Le controle a l'echelle du site</h2>
  <p>Inspecter les pages une par une suffit pour un petit site, mais un crawl automatise devient necessaire des que le volume augmente. Un outil de crawl parcourt l'ensemble des URL, releve la balise canonique de chacune et signale les cas problematiques : canonique absente, canonique vers une page en erreur, ou canonique en boucle. Croisez ensuite ces resultats avec le sitemap pour reperer les incoherences.</p>

  <h2>Reagir aux anomalies</h2>
  <p>Quand une anomalie apparait, corrigez la source dans le modele ou le systeme de gestion de contenu plutot que page par page, car les balises sont souvent generees automatiquement. Relancez un controle apres correction pour confirmer que le probleme a disparu sur toutes les pages concernees.</p>

  <p><a href="/">Retour a l accueil</a></p>
'''
+++
