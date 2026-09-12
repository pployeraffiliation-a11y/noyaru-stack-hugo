+++
url = "/gauntlet/duplicate-a/"
title = 'Test de doublon de titre pour la page A'
html_attrs = ' lang="fr"'
raw_head = '''
  <!-- FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions — jumelle de duplicate-b : meme titre ET meme description. -->
  <meta name="viewport" content="width=device-width" />
  <title>Test de doublon de titre pour la page A</title>
  <meta name="description" content="Page de test pour démontrer une anomalie de SEO avec des titres et descriptions dupliqués." />
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-a/" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Test de doublon de titre pour la page A" />
  <meta property="og:description" content="Deux pages qui portent exactement la meme meta description, afin de declencher la famille des doublons." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-a/" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Test de doublon de titre pour la page A" />
  <meta name="twitter:description" content="Deux pages qui portent exactement la meme meta description, afin de declencher la famille des doublons." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Parcours d'obstacles</h1>
  <p>Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
  <p><a href="/">Retour a l accueil</a></p>
'''
+++
