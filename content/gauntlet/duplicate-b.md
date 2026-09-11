+++
url = "/gauntlet/duplicate-b/"
title = 'Deux pages qui portent exactement le meme titre pour le test'
html_attrs = ' lang="fr"'
raw_head = '''
  <!-- FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions — jumelle de duplicate-a. -->
  <meta name="viewport" content="width=device-width" />
  <title>Deux pages qui portent exactement le meme titre pour le test</title>
  <meta name="description" content="Page B jumelle du test de doublons : elle illustre une meta description initialement identique a sa jumelle A, ici rendue unique." />
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-b/" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Deux pages qui portent exactement le meme titre pour le test" />
  <meta property="og:description" content="Page B jumelle du test de doublons : elle illustre une meta description initialement identique a sa jumelle A, ici rendue unique." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-b/" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Deux pages qui portent exactement le meme titre pour le test" />
  <meta name="twitter:description" content="Page B jumelle du test de doublons : elle illustre une meta description initialement identique a sa jumelle A, ici rendue unique." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Parcours d'obstacles</h1>
  <p>Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
  <p><a href="/">Retour a l accueil</a></p>
'''
+++
