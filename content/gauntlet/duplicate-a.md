+++
url = "/gauntlet/duplicate-a/"
title = 'Deux pages avec des titres similaires pour le test de SEO'
html_attrs = ' lang="fr"'
raw_head = '''
  <!-- FAMILLE VISEE : duplicate_titles + duplicate_meta_descriptions — jumelle de duplicate-b : meme titre ET meme description. -->
  <meta name="viewport" content="width=device-width" />
  <title>Deux pages avec des titres similaires pour le test de SEO</title>
  <meta name="description" content="Cette page traite d'un parcours d'obstacles, illustrant un cas spécifique pour la famille visée au crawl." />
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-a/" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Deux pages avec des titres similaires pour le test de SEO" />
  <meta property="og:description" content="Deux pages qui portent exactement la meme meta description, afin de declencher la famille des doublons." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/duplicate-a/" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Deux pages avec des titres similaires pour le test de SEO" />
  <meta name="twitter:description" content="Deux pages qui portent exactement la meme meta description, afin de declencher la famille des doublons." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Parcours d'obstacles : duplicate a</h1>
  <p>Cette page du parcours traite le cas « duplicate a ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
  <p><a href="/">Retour a l accueil</a></p>
'''
+++
