+++
url = "/gauntlet/duplicate-a/"
title = 'Titre unique pour la page duplicate-a'
html_attrs = ' lang="fr"'
raw_head = '''
  <!-- FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions — jumelle de duplicate-b : meme titre ET meme description. -->
  <meta name="viewport" content="width=device-width" />
  <title>Titre unique pour la page duplicate-a</title>
  <meta name="description" content="Page du parcours d'obstacles : elle est correcte partout sauf sur un point precis, afin que la famille visee soit la seule a se declencher au crawl." />
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-a/" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Titre unique pour la page duplicate-a" />
  <meta property="og:description" content="Deux pages qui portent exactement la meme meta description, afin de declencher la famille des doublons." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-a/" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Titre unique pour la page duplicate-a" />
  <meta name="twitter:description" content="Deux pages qui portent exactement la meme meta description, afin de declencher la famille des doublons." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Parcours d'obstacles</h1>
  <p>Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
  <p><a href="/">Retour a l accueil</a></p>
'''
+++
