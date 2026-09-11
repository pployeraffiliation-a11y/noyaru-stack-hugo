+++
url = "/gauntlet/duplicate-a/"
title = 'Deux pages qui portent exactement le meme titre pour le test'
html_attrs = ' lang="fr"'
raw_head = '''
  <!-- FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions — jumelle de duplicate-b : meme titre ET meme description. -->
  <meta name="viewport" content="width=device-width" />
  <title>Deux pages qui portent exactement le meme titre pour le test</title>
  <meta name="description" content="Page A du parcours d'obstacles : elle expose une meta description propre et unique pour differencier cette page de sa jumelle duplicate-b." />
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-a/" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Deux pages qui portent exactement le meme titre pour le test" />
  <meta property="og:description" content="Page A du parcours d'obstacles : elle expose une meta description propre et unique pour differencier cette page de sa jumelle duplicate-b." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-a/" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Deux pages qui portent exactement le meme titre pour le test" />
  <meta name="twitter:description" content="Page A du parcours d'obstacles : elle expose une meta description propre et unique pour differencier cette page de sa jumelle duplicate-b." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Parcours d'obstacles</h1>
  <p>Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
  <p><a href="/">Retour a l accueil</a></p>
'''
+++
