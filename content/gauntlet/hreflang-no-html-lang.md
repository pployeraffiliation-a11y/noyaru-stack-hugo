+++
url = "/gauntlet/hreflang-no-html-lang/"
title = 'Test hreflang declare sans attribut lang sur html'
html_attrs = 'lang="fr"'
raw_head = '''
  <!-- FAMILLE VISEE : hreflang_defined_but_html_lang_missing — hreflang declare mais «html» sans attribut lang. -->
  <meta name="viewport" content="width=device-width" />
  <title>Test hreflang declare sans attribut lang sur html</title>
  <meta name="description" content="Page de test hreflang declare correctement mais dont la balise html ne porte aucun attribut lang, afin d'isoler cette anomalie precise au crawl." />
  <link rel="canonical" href="https://noyaru-stack-hugo.netlify.app/gauntlet/hreflang-no-html-lang/" />
  <link rel="alternate" hreflang="fr" href="https://noyaru-stack-hugo.netlify.app/gauntlet/hreflang-no-html-lang/" />
  <link rel="alternate" hreflang="en" href="https://noyaru-stack-hugo.netlify.app/gauntlet/hreflang-to-non-canonical/" />
  <link rel="alternate" hreflang="x-default" href="https://noyaru-stack-hugo.netlify.app/gauntlet/hreflang-no-html-lang/" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="Test hreflang declare sans attribut lang sur html" />
  <meta property="og:description" content="Page de test hreflang declare correctement mais dont la balise html ne porte aucun attribut lang, afin d'isoler cette anomalie precise au crawl." />
  <meta property="og:url" content="https://noyaru-stack-hugo.netlify.app/gauntlet/hreflang-no-html-lang/" />
  <meta property="og:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Test hreflang declare sans attribut lang sur html" />
  <meta name="twitter:description" content="Page de test hreflang declare correctement mais dont la balise html ne porte aucun attribut lang, afin d'isoler cette anomalie precise au crawl." />
  <meta name="twitter:image" content="https://noyaru-stack-hugo.netlify.app/og.png" />
'''
raw_body = '''
  <h1>Parcours d'obstacles</h1>
  <p>Cette page appartient au parcours d'obstacles de la fixture. Elle sert a provoquer UNE anomalie et une seule.</p>
  <p><a href="/">Retour a l accueil</a></p>
'''
+++
