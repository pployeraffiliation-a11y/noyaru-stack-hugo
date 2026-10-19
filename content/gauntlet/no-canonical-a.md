+++
url = "/gauntlet/no-canonical-a/"
title = 'Deux pages jumelles sans canonical declare'
html_attrs = ' lang="fr"'
raw_head = '''
  <!-- FAMILLE VISEE : duplicate_pages_without_canonical — jumelle de no-canonical-b, aucune des deux ne declare de canonical. -->
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/no-canonical-a/" />
  <meta name="viewport" content="width=device-width" />
  <title>Deux pages jumelles sans canonical declare</title>
  <meta name="description" content="Premiere page jumelle sans canonical declare : son contenu est identique a la seconde, ce qui permet de declencher la detection des doublons sans balise" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Deux pages jumelles sans canonical declare" />
  <meta property="og:description" content="Premiere page jumelle sans canonical declare : son contenu est identique a la seconde, ce qui permet de declencher la detection des doublons sans balise canonique." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/no-canonical-a/" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Deux pages jumelles sans canonical declare" />
  <meta name="twitter:description" content="Premiere page jumelle sans canonical declare : son contenu est identique a la seconde, ce qui permet de declencher la detection des doublons sans balise canonique." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Parcours d'obstacles : pages jumelles</h1>
  <p>Cette page du parcours traite le cas « pages jumelles ». Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
  <p><a href="/">Retour a l accueil</a></p>
'''
+++
