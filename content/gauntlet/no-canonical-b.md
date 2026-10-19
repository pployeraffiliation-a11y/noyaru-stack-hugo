+++
url = "/gauntlet/no-canonical-b/"
title = 'Deux pages jumelles sans canonical declare'
html_attrs = ' lang="fr"'
raw_head = '''
  <!-- FAMILLE VISEE : duplicate_pages_without_canonical — jumelle de no-canonical-a. -->
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/no-canonical-a/" />
  <meta name="viewport" content="width=device-width" />
  <title>Deux pages jumelles sans canonical declare</title>
  <meta name="description" content="Page jumelle B du parcours d'obstacles : contenu identique a no-canonical-a, sans balise canonical, pour declencher la detection des pages dupliquees." />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Deux pages jumelles sans canonical declare" />
  <meta property="og:description" content="Page jumelle B du parcours d'obstacles : contenu identique a no-canonical-a, sans balise canonical, pour declencher la detection des pages dupliquees." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/no-canonical-a/" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Deux pages jumelles sans canonical declare" />
  <meta name="twitter:description" content="Page jumelle B du parcours d'obstacles : contenu identique a no-canonical-a, sans balise canonical, pour declencher la detection des pages dupliquees." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Parcours d'obstacles : pages jumelles</h1>
  <p>Cette page du parcours traite le cas « pages jumelles ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
  <p><a href="/">Retour a l accueil</a></p>
'''
+++
