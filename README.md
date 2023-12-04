# CommonCrawlDataBase
<html lang="en-US">
  <head>
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=640">

    <link rel="stylesheet" href="/enquete_vie_sociale_donnees/assets/css/style.css?v=39b2f396028652f545ffc90253542ea003d51d72" media="screen">
    <link rel="stylesheet" href="/enquete_vie_sociale_donnees/assets/css/mobile.css" media="handheld, only screen and (max-device-width:640px)">
    <link rel="stylesheet" href="/enquete_vie_sociale_donnees/assets/css/non-screen.css" media="handheld, only screen and (max-device-width:640px)">

    <script src="/enquete_vie_sociale_donnees/assets/js/modernizr.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ=" crossorigin="anonymous"></script>
    <script src="/enquete_vie_sociale_donnees/assets/js/headsmart.min.js"></script>
    <script>
      $(document).ready(function () {
        $('#main_content').headsmart()
      })
    </script>

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>La_base_de_données_Common_Crawl</title>
<meta name="generator" content="Jekyll v3.9.3" />
<meta property="og:title" content="enquete_vie_sociale_donnees" />
<meta property="og:locale" content="en_US" />
<link rel="canonical" href="https://jphcoi.github.io/enquete_vie_sociale_donnees/" />
<meta property="og:url" content="https://jphcoi.github.io/enquete_vie_sociale_donnees/" />
<meta property="og:site_name" content="enquete_vie_sociale_donnees" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="enquete_vie_sociale_donnees" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"enquete_vie_sociale_donnees","name":"enquete_vie_sociale_donnees","url":"https://jphcoi.github.io/enquete_vie_sociale_donnees/"}</script>
<!-- End Jekyll SEO tag -->


<!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/enquete_vie_sociale_donnees/favicon.ico" -->

<!-- end custom head snippets -->

  </head>

  <body>
    <a id="forkme_banner" href="https://github.com/jphcoi/enquete_vie_sociale_donnees">View on GitHub</a>
    <div class="shell">

      <header>
        <span class="ribbon-outer">
          <span class="ribbon-inner">
            <h1></h1>
            <h2></h2>
          </span>
          <span class="left-tail"></span>
          <span class="right-tail"></span>
        </span>
      </header>


        <div id="no-downloads">
          <span class="inner">
          </span>
        </div>



      <span class="banner-fix"></span>


      <section id="main_content">
        <script async="" src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<h1 id="La-vie-sociale-des-données : Common Crawl">La vie sociale des données: Common Crawl</h1>

<h2 id="introduction">Introduction</h2>

<h3 id="Overview de la base de données">Overview de la base de données</h3>

<p>Nous verrons d'abord l'histoire de cette base de données avant d'expliquer son fonctionnement</p>

<p><img src="https://24pm.com/images/2023/04/21/chat-gpt-data-sources.jpg"/></p>

<p>Cette base de données a été créé par Gil Elbaz en Californie dans la Sillicon Valley en 2008 et a été utilisé pour la première fois par Amazon en 2011. Common Crawl est une non-profit organization toujours actuellement dirigé par Gil Elbaz avec l'aide de Rich Skirenta, Greg Lindhal et Sébastien Nagel. En 2020, cette base de données a été utilisé pour entraîner le modèle linguistique GPT-3 de l'Open AI</p>

<h3 id="Son principe">Son principe</h3>

<p>Common Crawl est un projet qui vise à créer et à fournir un accès gratuit et ouvert à un vaste ensemble de données web. L'objectif principal de Common Crawl est de promouvoir l'accessibilité et l'utilisation des données du web pour la recherche et l'innovation. Voici quelques points clés à connaître sur Common Crawl. Common Crawl collecte des données et permet un accès libre et gratuit au public ce qui est notamment important pour les développeurs.</p>

<iframe width="624" height="386" seamless="" frameborder="0" scrolling="no" src="https://pbs.twimg.com/media/F2iG1hUXIAEEm3_.png"></iframe>

<p>Pour plus d'informations sur cette base de données, découvrez cette base de données vous même:<a href="https://commoncrawl.org/overview">Site Officiel: Common Crawl</a>.</p>

<h1 id="Interviews">Interviews</h1>
<h2 id="Rich Skrenta">Rich Skrenta</h2>
<h3 id="Une interview avec l'executive director actuel de Common Crawl">Une interview avec l'executive director actuel de Common Crawl</h3>

<p> Common Crawl est une organisation non lucrative (a non-profit organisation) qui a été créé en 2007 par Gil Elbaz dans la Silicon Valley et qui a été utilisé pour la première fois par Amazon en 2011. Elle est toujours dirigée aujourd’hui par son créateur Gil Elbaz avec Rich Skrenta comme Executive Director. En 2017/2018, cette base de données a connu une reconnaissance extraordinaire lors du développement des LLM (Large Language Models). Lorsque l'on aborde la question complexe du fonctionnement et l’utilisation d’une telle base de données, il est essentiel de donner la parole à ceux qui sont directement impliqués dans la recherche de solutions. Dans cette optique, nous avons eu le privilège de mener une interview approfondie avec Rich Skrenta, l’executive director actuel de Common Crawl, le 29 novembre 2023 à travers Googlemeet.
Avant de travailler pour Common Crawl, Rich Skrenta a travaillé chez Meta notamment comme « web crawler » et a créé « a search engine » qu’il a ensuite revendu avant de se consacrer entièrement à la mission de Common Crawl.<p> 
<p> D’après Rich Skrenta, l’objectif de Common crawl est de fournir à tout le monde un accès gratuit et ouvert à l’ensemble des données du web. Le but concret étant de créer une archive du web (« make an archive of the web » - Rich Skrenta). L’activité principale des programmeurs de cette organisation est donc de répertorier le plus de liens url possible du web. Le projet est principalement financé par la fondation de Gil Elbaz depuis son lancement et a récemment développé des opportunités de donations pour obtenir des fonds extérieurs plus importants. Néanmoins, Rich Skrenta a appuyé sur le fait que cette base de données est gratuite et qu’elle doit rester gratuitement accessible à tout le monde parce qu’ils souhaitent promouvoir l’accessibilité et l’utilisation des données du web pour la recherche et l’innovation.<p> 
<p> Pour cela, tous les mois, l’organisation « crawl » environ 3 à 5 milliards de pages internet et les classent dans un dossier, une fois ce dossier rempli, ils en font un nouveau (« We look at pages to crawl, then break it down to extend the number of url to open and keep crawling until reaching the url frontier that helps crawl the pages that you have not crawled yet » - Rich Skrenta). Il faut noter qu’environ 50% des url sont nouveaux alors que les autres 50% sont des anciens qu’ils analysent pour toutes nouvelles updates. Après quoi, les dossiers sont accessibles par tout le monde. Les programmeurs de Common Crawl n’organisent pas eux-mêmes les sites url par dates ou thèmes, ils collectent simplement les sites, mais un programme peut être lancer pour les catégoriser. Il est par exemple possible d’obtenir seulement les sites internet en français.<p> 
<p>Néanmoins, dans cette sélection, Common Crawl ne sélectionne que des informations ouvertes au public sur internet et ne demande pas d’accéder aux cookies, de se connecter à une page, « or bypass gates » pour obtenir les informations. Ainsi, seulement les informations déjà publiquement accessibles sont utilisées.<p>
<p>Dans l’optique du rôle qu’il souhaite jouer, l’organisation ne se juge pas comme ayant la responsabilité de filtrer les informations du web, au contraire. L’objectif principal est d’être le plus représentatif possible de toutes les informations disponibles sur internet. Il n’y a donc pas de filtre sur le contenu des url pour limiter les contenus illicites, racistes, ou toute autre forme de « hate speech » (« There is no semantic content-based filtering currently » - Rich Skrenta). Même s’il est important d’utiliser les données de manière responsable, l’organisation ne considère pas que cela est son rôle. De plus, il serait extrêmement difficile pour eux de catégoriser ce qui est considéré comme raciste, extrémiste, « hate speech », etc. Cela ressort plus du rôle des chercheurs qui utilisent cette base de données d’après Rich Skrenta. Au contraire, l’organisation souhaite pouvoir donner accès à ce genre d’informations pour les personnes qui effectuent des recherches sur ces domaines. Rich Skrenta a malgré tout indiqué que cela est un problème que les utilisateurs de leur base de données, notamment pour les LLM, doivent régler et gérer.<p>
<p>De même, leur rôle n’est pas d’entraîner l’IA (« to train the AI ») pour filtrer ces informations et réutiliser leurs données de manière responsable ou raisonnable notamment parce qu’il y a trop de manière d’interpréter le web (« there is too many different ways to interpret the web which is what research is for »). 
Le problème actuel est plutôt la représentativité des langues. Actuellement, même si Common Crawl a déjà archivé des url dans environ 230 langues, environ 58% des sites internet déjà récoltés par Common Crawl sont en anglais. Certains programmeurs, notamment en Indonésie, ont contacté Common Crawl pour demander un travail plus inclusif des autres langues présentes sur le web.<p>

<p>Regardez l'intégralité de l'interview <a href="https://www.ipefdakar.org/IMG/pdf/l_interview_conseils.pdf">Rich Skrenta's Interview</a> ou découvrez en plus sur son parcours <a href="https://commoncrawl.org/team/rich-skrenta-director">Site Officiel de Common Crawl</a> pour en apprendre plus.</p>

<h2 id="François Yvon">François Yvon</h2>
<h3 id="Une interview avec un chercheur acadèmique">Une interview avec un chercheur acadèmique</h3>

<p> Pour ce projet, nous avons eu l'honneur d'interviewer François Yvon, un chercheur en LLM (Large Language Models) qui n'utilise pas directement Common Crawl mais qui produit des modèles qui l'utilise. François Yvon travaille principalement sur tout ce qui concerne "le multilinguisme, la traduction automatique et les grands modèles." Il explique que le problème majeur actuellement était principalement sur la représentation de l'anglais par rapport aux autres langues. Pour une représentation plus juste et plus réaliste des informations présentent sur internet, il faudrait une essayer d’approcher les langues de manière plus égalitaire.<p>

<p>Regardez l'intégralité de l'interview <a href="file:///Users/marieseguy/Downloads/Document%20sans%20titre.pdf">Transcription de l'interview</a> ou découvrez en plus sur son parcours <a href="https://www.isir.upmc.fr/personnel/yvon/">Site ISIR</a> pour en apprendre plus.</p>
<h2 id="Margaux Vulliet">Margaux Vulliet</h2>
<h3 id="Une interview avec une journaliste médias et techn">Une interview avec une journaliste médias et tech</h3>
<p> Dans l’optique de notre étude sur Common Crawl, nous avons eu également le plaisir d’interviewer Margaux Vulliet, une journaliste spécialisée en technologie, qui a écrit l’article « De Chatgpt à bard : voilà à quoi ressemblent les bases de données utilisées pour former les IA » pour BMTV en avril 2023.<p>
<p>Margaux Vulliet a choisi d’écrire un article sur les bases de données comme Common Crawl parce que c’est un sujet d’actualité qui attire de plus en plus le public, notamment depuis la création de la dernière version gratuite et ouverte de chatgpt.<p>
<p>Margaux Vulliet a noté que l’un des problèmes principalement notés est le problème des droits d’auteur lié au manque de reconnaissance d’utilisation de certains articles. C’est pour cela que le New York Times par exemple a demandé bloquer l’accès aux utilisateurs de Common Crawl pour leur archive du web. L’autre problème de ces bases de données est l’omniprésence de sites internet américains ou anglophones qui explique que l’Union Européenne souhaite développer sa propre archive du web. Le ministre chargé du numérique, Jean-Noël Barrot, a d’ailleurs noté ce problème et pousse actuellement pour le développement d’un Common Crawl européen.<p>
<p>D’après ce qu’elle a pu constater lors de ces différentes recherches sur chatgpt, Margaux Vulliet a remarqué une peur, notamment dans le domaine du journalisme, de se faire remplacer par chatgpt ou l’intelligence artificielle. C’est déjà le cas dans certaines petites villes américaines où les IA affichent directement le résultat de match de sport aux communautés locales beaucoup plus rapidement qu’aucun journaliste ne pourrait le faire. D’un autre côté, Margaux Vulliet voit aussi une énorme aide en chatgpt qui permet d’analyser des centaines de documents en quelques secondes par rapport à des heures de travail pour un humain. De plus, comme chatgpt ne pourra jamais remplacer le journaliste de terrain, toute la partie enquête, mais peut aider avec la recherche et le développement d’idées, Margaux Vulliet voit plutôt l’IA comme un atout pour eux actuellement.<p>
<p> En revanche, Margaux Vulliet remarque un risque dans l’utilisation de chatgpt particulièrement liée à l’opacité de sa base de données et des informations que le logiciel fournit aux utilisateurs. Pour elle, les programmeurs de chatgpt ont déjà fait beaucoup d’efforts pour réduire les risques de racisme ou d’antisémitisme ou tout autre propos inquiétant que peut avoir chatgpt dès qu’ils ont eu vent du problème. Elle note que beaucoup d’IA répondent désormais qu’ils ne peuvent pas répondre à des sujets sensibles et parfois même dirige directement les utilisateurs vers des liens de soutien (par exemple des liens contre le suicide).<p>


<p>Regardez l'intégralité de l'interview <a href="https://www.ipefdakar.org/IMG/pdf/l_interview_conseils.pdf">documentation</a> ou découvrez en plus sur son parcours <a href="https://www.medianes.org/author/margaux/">Site Personnel</a> pour en apprendre plus.</p>

<h1 id="Updates via les réseaux sociaux">Updates via les réseaux sociaux</h1>
<p>Un effort constant de partager les nouveautés et les actualités de l'organisation avec le public notamment à travers twitter:</p>

<blockquote class="twitter-tweet">
  <a href="[https://twitter.com/commoncrawl/status/1671408229589581825?s=46&t=aj6GX9IxEIsWGRYl-HJUjg]"></a>
</blockquote>


      <footer>
        <span class="ribbon-outer">
          <span class="ribbon-inner">

          </span>
          <span class="left-tail"></span>
          <span class="right-tail"></span>
        </span>
        <p>Generated with <a href="https://pages.github.com">GitHub Pages</a> using Merlot</p>
        <span class="octocat"></span>
      </footer>
