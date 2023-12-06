# Common Crawl Data Base
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

<p>Le « Common Crawl Data Set » (plus souvent appelé « Common Crawl ») est un jeu de données extrêmement riche, proposé au public par une organisation éponyme à but non-lucratif d’origine américaine. Les archives incorporées dans ce jeu remontent jusqu’à 2008, et il est mis à jour à une fréquence mensuelle. Le code permettant le traitement de ses données est open source, et depuis 2012, Amazon Web Services permet également l’accès au Common Crawl à travers son « public data set ».<p>
  
<p><img src="https://24pm.com/images/2023/04/21/chat-gpt-data-sources.jpg"/></p>

<p>Ce jeu de données est considéré comme l’un des plus conséquents au monde, et est composé à plus ou moins 46% de documents anglophones. Le Common Crawl a notamment été utilisé pour entraîner le grand modèle de langage GPT-3 d’Open AI.<p>
 
<p>En vue des nombreuses controverses autour de ce jeu de données, notamment liées à son utilisation de site protégés ou des inégalités linguistiques dans ses sources, le présent site cherche à contribuer à l’analyse critique de son contenu.<p>

<h2 id="Aperçu de Common Crawl">Aperçu de Common Crawl</h2>

<h3 id="L'histoire de Common Crawl">L'histoire de Common Crawl</h3>

<p>La base de données "Common Crawl" a été lancée en 2008 par Gil Elbaz, fondateur de la société de technologie de la publicité Applied Semantics, et par d'autres acteurs majeurs du domaine de la technologie et de la recherche. Elle a été créée dans le but de collecter et d'archiver des données provenant de milliards de pages web à travers le monde.
 
Au fil des années, cette initiative a pris de l'ampleur, atteignant des dimensions impressionnantes. En 2021, la base de données "Common Crawl" avait indexé et stocké plus de 100 milliards de pages web, totalisant des pétaoctets d'informations. Ce corpus de données massif est continuellement mis à jour à travers des crawls réguliers du web, permettant ainsi d'offrir un accès à jour et étendu à des chercheurs, des développeurs et des organisations dans le monde entier.
 
Cette ressource considérable a joué un rôle essentiel dans le développement de nombreuses technologies, notamment dans le domaine de l'intelligence artificielle, du traitement du langage naturel, de la recherche en sciences sociales, et bien d'autres. La base de données "Common Crawl" est devenue un pilier fondamental pour la recherche et l'innovation, offrant un accès libre et ouvert à des quantités massives de données web pour des applications variées.</p>

<center>
<iframe width="400" height="315" seamless="" frameborder="0" scrolling="no" src="https://i.insider.com/51685809eab8ea1d71000001?width=750&format=jpeg&auto=webp"></iframe>
</center>

<p>Pour plus d'informations sur cette base de données, découvrez cette base de données vous même: <a href="https://commoncrawl.org/overview">Site Officiel: Common Crawl</a>.</p>

<h3 id="Gestionnaire">Gestionnaire</h3>

<p>L’équipe de l’organisation comporte une vingtaine d’individus, dont neuf sont actifs dans le ‘Advisory Board’. A la tête du Common Crawl se trouve le fondateur, Gil Elbaz, suivi de Rich Skrenta, le directeur exécutif, ainsi qui Greg Lindahl, le directeur technique en chef. Parmi les ingénieurs se trouvent Sebastian Nagel, Julien Nioche, ou encore Paul Lazar.<p>
  
<p>La liste complète des gestionnaires du Common Crawl est disponible <a href="https://commoncrawl.org/team">Ici</a>.<p> 
 
<p>Nous sommes honorés d’avoir pu nous entretenir avec le Directeur Executif, Rich Skrenta, au sujet de ce projet.<p>

<h3 id="Financement">Financement</h3>

<p> Au-delà du financement par la fondation personnelle de Gil Elbaz, la base de données "Common Crawl" tire ses financements de différentes sources. Les subventions provenant de fondations philanthropiques comme la Fondation Bill & Melinda Gates, la Fondation Alfred P. Sloan et la Fondation Gordon & Betty Moore jouent un rôle majeur dans le financement à long terme de l'initiative. Ces subventions sont généralement allouées pour des projets spécifiques visant à améliorer les capacités de collecte de données, à développer de nouvelles technologies d'indexation ou à rendre les données plus accessibles aux utilisateurs finaux.<p>

<p>En outre, "Common Crawl" reçoit des soutiens financiers substantiels de la National Science Foundation (NSF) aux États-Unis et de l'Union européenne, à travers des programmes de financement de la recherche ou des initiatives liées à l'innovation technologique. Ces fonds contribuent à la réalisation des crawls réguliers, à l'infrastructure serveur et au développement d'outils pour l'analyse des données. L'organisation établit également des partenariats avec des entreprises technologiques majeures (comme Digital Pebble, DuckDuck Go ou ML Commons), offrant des accès privilégiés à la base de données en échange de soutien financier ou de ressources matérielles pour l'infrastructure informatique.<p>

<h3 id="Sources">Sources</h3>

<p>Common Crawl" collecte des données en utilisant des robots d'indexation sur une variété de sources en ligne accessibles au public, telles que des sites web publics, des forums et des réseaux sociaux. Ces robots parcourent le web en suivant les liens hypertextes pour enregistrer le contenu des pages. Ils sont supposés respecter les directives d'exclusion des robots (fichiers robots.txt) pour limiter la collecte selon les indications des sites visités.
 
L'initiative utilise également des méthodes d'échantillonnage pour tenter de garantir une représentation variée dans son index. Cependant, les données collectées peuvent être influencées par des biais inhérents au web, tels que des régions géographiques sur-représentées ou des secteurs d'activité plus fréquemment indexés. Ces pratiques de collecte soulèvent des préoccupations concernant la qualité, la neutralité et la représentativité des données extraites, pouvant potentiellement impacter la fiabilité des informations fournies pour la recherche et le développement.<p>

<p> Pour aller plus loin:<p>
<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/AicEmIeuuLw" title="Getting Started" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

<h1 id="Méthodologie de l'enquête">Méthodologie de l'enquête</h1>

<p>Dans le cadre de nos recherches afin de trouver une base de données pertinente sur laquelle enquêter, nous avons pris connaissance dans un article du Washington Post intitulé « Inside the secret list of websites that make AI like ChatGPT sound smart ». Cet article qui a été publié en avril 2023 a pour but d’éclaircir les sources d’informations de l’IA, afin de comprendre comment elle est construite, mais également comment elle est influencée lorsqu’elle répond aux utilisateurs. À ces fins, le Washington Post a donc décidé d’analyser l'un de ces ensembles de données afin de révéler les types de sites web qui entrent dans les données d'une IA.<p>

<p>Souhaitant faire notre propre avis sur la question, nous avons décidé de nous concentrer sur la base de données Common Crawl, qui comme indiqué précédemment a été utilisée pour entraîner le modèle de langage GPT-3 développé par Open AI, qui lors de son annonce en 2020 était plus gros modèle de langage jamais entraîné avec 175 milliards de paramètres.<p>
 
<p>Nous nous sommes donc interrogés sur comment Common Crawl est constituée, par qui elle a été créée, dans quel but et enfin quelles sont ses limites et ses enjeux.<p> 
 
<p>Ainsi, afin de répondre à ces questions, nous avons décidé de diriger notre enquête sur deux axes. D’une part, de manière plus théorique, nous avons tenté de comprendre la structure, le fonctionnement et l’utilité de cette base de données en interviewant trois personnes impliquées à leur façon dans l’utilisation de Common Crawl ou de l’IA de manière plus générale à travers les bases de données.<p>
 
<p>Pour cela, nous avons eu la chance de pouvoir interviewer, Rich Skrenta, l'executive director actuel de Common Crawl, François Yvon, grand chercheur en matière de Large Langage Model et Margaux Vulliet journaliste reconnue en média et tech, qui a déjà effectué des enquêtes afin de découvrir les bases de données utilisées pour former les IA.<p> 
 
<p>Dans un deuxième axe et de manière plus pratique, nous avons nous même tenter d’analyser la base de données de Common Crawl en utilisant la méthodologie présentée ci-dessous.<p> 

<h2 id="Interviews">Interviews</h2>

<h3 id="Une interview avec l'executive director actuel de Common Crawl : Rich Skrenta">Une interview avec l'executive director actuel de Common Crawl : Rich Skrenta</h3>

<p> Rich Skrenta est un programmeur informatique américain et entrepreneur de la Silicon Valley qui a créé le moteur de recherche internet Blekko. Avant de travailler pour Common Crawl, Rich Skrenta a travaillé chez Meta notamment comme « web crawler » et a créé « a search engine » qu’il a ensuite revendu avant de se consacrer entièrement à la mission de Common Crawl.
  
Lorsque l'on aborde la question complexe du fonctionnement et l’utilisation d’une telle base de données, il est essentiel de donner la parole à ceux qui sont directement impliqués dans la recherche de solutions. Ainsi pour comprendre l'origine, le fonctionnement, ainsi que les objectifs de ce projet, nous avons eu le privilège de mener une interview approfondie avec Rich Skrenta, l’executive director actuel de Common Crawl, le 29 novembre 2023 à travers Googlemeet. Rich Skrenta nous a expliqué leur ambition de créer une archive du web gratuite et ouverte au public pour le développement de la recherche et de l'innovation.<p> 

<p> Lisez <a href="https://docs.google.com/document/d/1gImgfNDMJy7MSOjAxG5pAyQ96xYE2cH6J7mhCl1aaEc/edit">le résumé de l'interview</a> pour en apprendre plus sur cette entretien ou découvrez en plus sur son parcours <a href="https://commoncrawl.org/team/rich-skrenta-director">Site Officiel de Common Crawl</a> pour en apprendre plus.</p>

<center>
<iframe width="400" height="315" seamless="" frameborder="0" scrolling="no" src="https://assets-global.website-files.com/647b1c7a9990bad2048d3711/6480671ff32d469e9cea78d9_rich-skrenta-300x300-1.jpg"></iframe>
</center>

<h3 id="Une interview avec un rechercheur: François Yvon">Une interview avec un rechercheur : François Yvon</h3>

<p> Ensuite, pour mieux comprendre la valeur d'une base de données comme common crawl sur un plan pratique d'entrainement d'IA et ses limites techniques, nous avons eu le plaisir d’interviewer François Yvon, un spécialiste du traitement automatique des langues, un domaine à la frontière entre l’IA, l’informatique et la linguistique. François Yvon est actuellement directeur de recherche Centre national de la recherche scientifique (CNRS) et exerce ses fonctions dans l'équipe MLIA (Machine Learning & Deep Learning for Imformation Access) de l'Institut des systèmes intelligents et de robotique (ISIR - CNRS/Sorbonne Université). 
  
Ses activités de recherche couvrent un large spectre de thématiques en traitement automatique des langues, de la morphologie computationnelle à la fouille de textes et les méthodes d'apprentissage structurées. Il se concentre aujourd'hui sur les traitements multilingues, à ces fins il a été impliqué dans le développement de BLOOM également appelé BigScience Large Open-science Open-access Multilingual language Model qui est un modèle linguistique de grande taille basé sur un transformateur. Il a été créé par des chercheurs en intelligence artificielle afin de fournir un modèle linguistique gratuit à grande échelle accessible au public. Parmis beaucoup d'autres informations, François Yvon nous a aidé à comprendre les limites actuelles des programmes comme Common Crawl notamment liés à la surreprésentation de l'anglais par rapport aux autres langues dans le monde.<p>

<p> Lisez la <a href="https://docs.google.com/document/d/1gImgfNDMJy7MSOjAxG5pAyQ96xYE2cH6J7mhCl1aaEc/edit">Transcription mot pour mot de l'interview</a> ou découvrez en plus sur son parcours <a href="https://www.isir.upmc.fr/personnel/yvon/">Site ISIR</a> pour en apprendre plus.</p>

<center>
<iframe width="400" height="315" seamless="" frameborder="0" scrolling="no" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQi0ruYyiFkOC7668NChNMG3cGa_UFsQ4ILysYwLj14Cd6mdTlz"></iframe>
</center>

<h3 id="Une interview avec une journaliste: Margaux Vulliet">Une interview avec une journalise : Margaux Vulliet</h3>

<p> Enfin, pour avoir un regard journalistique critique qui peut éclairer sur les enjeux sociétaux et juridiques d'utilisation de Common Crawl, nous avons également eu le plaisir d’interviewer Margaux Vulliet, une journaliste spécialisée en technologie, qui a écrit l’article « De Chatgpt à bard : voilà à quoi ressemblent les bases de données utilisées pour former les IA » pour BMTV en avril 2023.<p>
  
<p>Lisez <a href="https://docs.google.com/document/d/1gImgfNDMJy7MSOjAxG5pAyQ96xYE2cH6J7mhCl1aaEc/edit">le résume de l'interview</a> ou découvrez en plus sur son parcours <a href="https://www.medianes.org/author/margaux/">Site Personnel</a> pour en apprendre plus.</p>

<center>
<iframe width="400" height="315" seamless="" frameborder="0" scrolling="no" src="https://www.medianes.org/content/images/size/w320/2023/11/photoMV.jpg"></iframe>
</center>

<h1 id="Méthodologie d'extraction de données">Méthodologie d'extraction des données</h1>

<p>Pour le deuxième volet de notre analyse, nous avons tenté d’aller au contact même de la base de données et d’en extraire par nous-mêmes certaines informations. Pour cela nous avons concentré notre analyse sur le crawl d’octobre 2023 (CC-MAIN-2023-40).<p>

<p>Pour chaque crawl, Common Crawl met plusieurs types de fichiers à disposition, dont certains (notamment les fichiers WARC, qui regroupent toute l’information) pèsent près de 98 To. Même le fichier Columnar URL index files qui organise certains indicateurs en colonnes (url, domaine, langue etc…), réduisant ainsi la taille et facilitant l’analyse, pèse près de 300 Go. Très vite, le poids de ces fichiers est devenu une véritable difficulté. N’étant pas dotés d’ordinateurs à mémoire vive et de puissance de calcul suffisantes, le traitement des fichiers prenait parfois plusieurs minutes puis finissait par échouer voire échouait.<p> 

<p>Pour contourner ce problème, nous avons décidé d’utiliser Athena, une plateforme d’analyse de données fournie par Amazon Web Services (AWS). Athena ne requiert ni création d’un serveur pour analyser les données, ni de les télécharger au préalable. En effet, les crawls sont stockés sur les serveurs d’Amazon, il suffit donc simplement de diriger Athena vers la source des données pour être en mesure de les analyser. Ce sont des avantages considérables pour des étudiants en droit ayant des connaissances limitées en informatique et programmation.<p> 

<p>Athena utilise un langage de type SQL (Structured Query Language) pour analyser les données et en extraire les informations intéressantes. Premièrement, nous avons tenté une analyse langagière en dénombrant les sites web contenus dans le crawl par domaine (par exemple: .com, .org, .fr, etc.) et par langues. L’objectif de cette analyse est de comparer la représentation des différentes langues dans le crawl d’octobre 2023 avec les études sur la proportion des langues dans l’ensemble du web.<p> 

<p>Nous avons ensuite décidé de concentrer notre analyse sur les sites web en français pour comprendre sur quoi se fonderait un LLM francophone utilisant un crawl pour ses données d'entraînement. Pour cela, nous avons extrait la liste des domaines les plus représentés dans les sites francophones, en nous limitant à ceux qui apparaissent au moins 100 fois. À titre d’illustration, nous avons pu déterminer que le domaine cnrs.fr apparaît 361 559 fois.<p> 

<p>Enfin, nous avons également extrait 500 urls francophone aléatoires afin de les examiner un par un et de les catégoriser en fonction du type de site web (blog, presse, site de vente…) et du sujet traité (commercial, scientifique, information, culture…). Définir de telles catégories et le niveau de détail s’est révélé ardu étant donné la diversité des contenus. Nous nous sommes donc arrêtés sur celles présentées à la page suivante, qui nous permettent d’obtenir une première vue d’ensemble du type de sites francophones inclues dans le crawl d’octobre 2023.<p> 

<p>Nous avons d'abord catégorisé les sites url par sujets:</p>

<head>
  <title>Les Sujets</title>
  <meta charset= "utf-8">
  <link rel="stylesheet"href="cours.css">
</head>

<body>
  <table>
    <tr>
      <td>Sujet</td>
      <td>Définition/exemple</td>
    </tr>
    <tr>
      <td>Développement personnel</td>
      <td>Développement personnel</td>
    </tr>
    <tr>
      <td>Commercial</td>
      <td>L'oject premier est de vendre un bien ou un service</td>
    </tr>
    <tr>
      <td>Culture</td>
      <td>Tout ce qui est a trait à des évènements artistiques, historiques, évènementiel,etc.</td>
    </tr>
    <tr>
      <td>Information</td>
      <td>Articles d'information ou d'association</td>
    </tr>
    <tr>
      <td>Professionnel</td>
      <td>Description d'une entreprise (ex: site d'un cabinet d'avocats)</td>
    </tr>
    <tr>
      <td>Académique</td>
      <td>Journaux académique, recherche (ex: Cairn)</td>
    </tr>
    <tr>
      <td>Administration</td>
      <td>En référence à des sites pubilcs ou des démarches administratives</td>
    </tr>
    <tr>
      <td>Légal</td>
      <td>En référence à des sites traitant de droit</td>
    </tr>
    <tr>
      <td>Illicite</td>
      <td>pornographie, sites complotistes, extrêmes</td>
    </tr>
    <tr>
      <td>Politique/religieux</td>
      <td>Partis politiques ou promotion de religions</td>
    </tr>
    <tr>
      <td>Sport</td>
      <td>Associations sportives, sites de sport</td>
    </tr>
    <tr>
      <td>Economie/Finance</td>
      <td>Banque de France, sites boursiers</td>
    </tr>
    <tr>
      <td>Science/Statistique</td>
      <td>Insee, publications scientifiques</td>
    </tr>
    <tr>
      <td>Autre</td>
      <td>tout le reste</td>
    </tr>
  </table>
</body>

<p>Nous avons ensuite catégorisé les sites url par types:</p>

<table>
  <tr>
    <td>Listes des types</td>
  </tr>
  <tr>
    <td>Site de vente</td>
  </tr>
  <tr>
    <td>Encyclopédie</td>
  </tr>
  <tr>
    <td>Évenementiel</td>
  </tr>
  <tr>
    <td>Presse</td>
  </tr>
  <tr>
    <td>Journal Académique</td>
  </tr>
  <tr>
    <td>Site d'identification</td>
  </tr>
  <tr>
    <td>Site personnel</td>
  </tr>
  <tr>
    <td>Associatif</td>
  </tr>
  <tr>
    <td>Site de vente</td>
  </tr>
  <tr>
    <td>Vidéos/Photos</td>
  </tr>
  <tr>
    <td>Forum</td>
  </tr>
  <tr>
    <td>Recherche</td>
  </tr>
  <tr>
    <td>Annuaire</td>
  </tr>
  <tr>
    <td>Autre</td>
  </tr>
</table>

<p>Exemple d'une requête SQL pour trouver les domaines francophones représentés plus de 100 fois: <p>

<h2 id="Le processus">Le processus</h2>

<h3 id="Première étape: Création de la base de données">Première étape: Création de la base de données</h3>

<p>CREATE DATABASE ccindex;<p>
  
<h3 id="Deuxième étape: Création du tableau contenant les valeurs et synchronisation avec les données Common Crawl">Deuxième étape: création du tableau contenant les valeurs et les synchronisation avec les données Common Crawl</h3>

<p>CREATE EXTERNAL TABLE IF NOT EXISTS ccindex (<p>
<p>url_surtkley &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host_name&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host_tld&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host__2nd_last_part&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host__3rd_last_part&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host__4th_last_part&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host__5th_last_part&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host__registry_suffix&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host_registered_domain&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host_private_suffix&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host_private_domain&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>url_host_name_reversed&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>
<p>url_host_private_domain&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>  
<p>url_protocol&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>  
<p>url_port&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;INT<p> 
<p>url_path&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>url_query&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>fetch_time&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>fetch_status&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;TIMESTAMP<p>
<p>fetch_redirect&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;SMALLINT<p> 
<p>content_digest&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p>  
<p>content_mime_type&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>content_mime_detected&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>content_charset&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>content_languages&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>content_truncated&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>warc_record_offset&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;INT<p> 
<p>warc_record_length&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;INT<p> 
<p>warc_segment&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING)<p> 
<p>PARTITIONED BY (&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; <p>
<p>crawl&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING<p> 
<p>subset&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;STRING)<p>   
<p>STORED AS parquet&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<p>     
<p>LOCATION 's3://commoncrawl/cc-index/table/cc-main/warc/';<p>

<h3 id="Troisième étape: Dénombrement des domaines francophones représentées plus de 100 fois">Troisième étape: Dénombrement des domaines francophones représentées plus de 100 fois</h3>

<p>SELECT COUNT(*) AS count,<p>
       <p>url_host_registered_domain<p>
<p>FROM "ccindex"."ccindex"<p>
<p>WHERE crawl = 'CC-MAIN-2023-40'<p>
  <p>AND subset = 'warc'<p>
  <p>AND url_host_tld = 'fr'<p>
<p>GROUP BY  url_host_registered_domain<p>
<p>HAVING (COUNT(*) >= 100)<p>
<p>ORDER BY  count DESC<p> 

<h3 id="Quatrième étape: Résultat obtenu">Quatrième étape: Résultat obtenu</h3>

<p> 5 premières lignes : 142792 = free.fr ; 418451 = lefigaro.fr ; 361559 = cnrs.fr ; 199026 = online.fr ; 165030 = orange.fr</p>

<p>Regardez <a href="https://docs.google.com/spreadsheets/d/1-1nmO2qQYdBU6d9_HH1OjAhMYWz4gSsP/edit#gid=1641676625">l'analyse des 500 url</a> pour avoir plus de détails.</p>

<h1 id="L'analyse des données">L'analyse des données</h1>

<h2 id="Nos résultats">Nos résultats</h2>

<p>ajouter la photo du graphisme </p>

.github/Picture1.png

<p>En analysant les cinq cents sites web utilisées par Common Crawl, nous avons pu noter qu’un quart des sites traitent d’un sujet commercial (26%), 17% traitent de sujets culturels face à seulement 5% en matière académique et 3% en matière politique/ religieuse mais aussi en sport. Également, 12% des sites fournissent des informations, 11% ont un objet professionnel, 9% portent sur l’Administration et 6% d’entre eux abordent le développement personnel. Enfin, avec un taux très faible, 2% des sites ont un objet illicite, 1% portent sur les sciences/statistiques et 1% également concernant l’économie et la finance. Enfin, sur ces cinq sites sélectionnés au hasard, aucun ne portait sur un sujet juridique. </p>

<p>ajouter la deuxième photo du graphisme</p>

<p>Concernant le type de documents proposés dans chaque site, la plupart de ces plateformes sont des sites de ventes (28%). Durant notre enquête, nous avons également trouvé de nombreux blogs (17%), puis dans une moindre mesure des presses (8%), des sites d’identification (6%), de recherche (6%), événementiel (6%) et associatif (6%). Les types de documents les moins représentés dans cet échantillon sont les forums, les vidéos/photos à hauteur de 4%. Puis les sites personnels et les journaux à 3% et enfin les annuaires et les encyclopédies qui correspondent à seulement 2% des tous ces sites.</p>

<h1 id="Les difficultés de Common Crawl">Les difficultés  de Common Crawl</h1>

<h2 id="Les limites">Les limites</h2>

<p>Common Crawl n'est pas sans limites. Internet étant un espace infini et en expansion constance, Common Crawl ne peut évidemment pas donner une représentation complète du web.</p>

<p>Une des premières limites de Common Crawl, est les langues. En effet, d’après Rich Senka, 58% des pages internet crawler sont en anglais ce qui empêche d’atteindre l’objectif d’avoir une représentation d’Internet dans sa diversité. Cette limite fait l’objet d’initiatives gouvernementales puisque l’Union Européenne et l’Indonésie se sont rapprochées de Common Crawl pour qu’il travaille à plus crawler leurs langues qu'elles soient nationales ou régionales.</p>

<p>Deuxièmement, la qualité du contenu crawler par Common Crawl. Comme nous avons nous-même pu l’observer, certaines pages sont redondantes ou mènent à des contenus illicites. Pour l’instant, les pages qui sont crawler par Common Crawl sont déterminées par un modèle mathématique qui donne un score à ces pages basées sur leur trafic. Par conséquent, certaines pages seront crawlées deux fois seulement parce que la date de l’article a changé. Ainsi, Common Crawl travaille à développer une indexation des pages web basé sur “harmonic centrality”, c'est-à-dire le nombre de liens qui mènent à une page. Par ailleurs, en crawlant des pages webs, Common Crawl prend connaissance de milliards d'autres liens qui mènent à d'autres pages internet, c'est ce qu'on appel la "URL Frontier". Dès lors, Common Crawl va tenter de sélectionner une partie de ces URLs pour les crawler le mois prochain et ainsi permettre une représentation plus qualitative du web.</p>

<p>Troisièmement, au-delà de la qualité du crawl, son exhaustivité a aussi des limites, car Common Crawl se concentre seulement sur les pages web sans archiver des contenus photographiques et vidéographiques qui font partis de l’internet, d’autant plus avec le développement des réseaux sociaux et des memes. Ainsi, une partie du web qui contient des éléments socio-culturels, artistiques, politiques, et historiques n'est pas présente dans l’archive faite par Common Crawl chaque mois. Néanmoins, crawler des photos et des vidéos nécessiterait une capacité de stockage de données énormes, il y a donc aussi des limites physiques et financières à la capacité d'exhaustivité de Common Crawl.</p>

<p>Quatrièmement, Common Crawl ne procède pas à un “semantic-based filtering”, c'est-à- dire qu’il n y a pas de nettoyage des données pour éliminer les contenus haineux, illicites, ou redondants. Ainsi, le nettoyage de la base de données est laissé aux développeurs qui vont l’utiliser. Néanmoins, il est important de noter que la modération/filtrage de contenus et la détermination du caractère haineux ou illicite est une problématique dure à traiter, car cette caractérisation peut varier d’un pays à un autre et cela revient à ériger des entreprises privées en juge de la liberté d’expression.</p>

<h2 id="Les enjeux">Les enjeux</h2>

<p>Avec l'avènement de LLMs et d’intelligence artificielle comme ChatGPT qui utilise la base de données Common Crawl à 60% pour sourcer ses informations, la connaissance des limites des bases données d’indexation de pages web comme Common Crawl est cruciale pour mieux aborder ces outils.<p>

<p>La qualité et l’exhaustivité des contenus tant linguistiquement qu'en variété de contenus sont clés pour la création de LLMs qui soient basés sur une représentation proportionnée et qualitative d’Internet et donc des sociétés humaines.<p>

<p>La prévalence de l’anglais dans des crawlers comme Common Crawler ralenti le développement de LLMs dans d’autres langues comme le français. Ainsi, des bases de données comme common crawl revêtent un aspect stratégique dans la course au développement de LLMs et d’intelligences artificielles comme le démontre l’existence d’une initiative de l’Union européenne de créer un crawler/index de pages web pour s’affranchir d’entreprises américaines et avoir une autonomie stratégique dans le domaine.<p> 

<p>La qualité du contenu est aussi un enjeu important. En effet, un bot développé par Microsoft qui devait apprendre à faire la conversation en interagissant avec les utilisateurs de Twitter est devenu misogyne, raciste, antisémite, et xénophobe après une journée seulement d’interaction avec les utilisateurs de Twitter. Ainsi, le fait que Common Crawl recensent des sites avec des contenus illégaux, de nombreux sites commerciaux plutôt que des pages informatives, ou encore des blogs avec de nombreuses fautes d'orthographe, peut mener au développement de LLMs et des I.A qui reproduisent et exacerbent les limites de l’internet d’aujourd’hui. Dès lors, le nettoyage et le filtrage des bases de données sont essentiels pour développer des LLMs et I.A de qualités. Néanmoins, le filtrage et nettoyage des données ne sont jamais neutre ce qui peut mener à des systèmes biaisés.</p>

<h1 id="Pour aller plus loin">Pour aller plus loin</h1>

<h2 id="Updates via les réseaux sociaux">Updates via les réseaux sociaux</h2>

<p>Un effort constant de partager les nouveautés et les actualités de l'organisation avec le public notamment à travers twitter:</p>

<center>
<blockquote class="twitter-tweet">
  <a href="[https://twitter.com/commoncrawl/status/1671408229589581825?s=46&t=aj6GX9IxEIsWGRYl-HJUjg]"></a>
</blockquote>
</center>

<h2 id="Les premières interviews sur ce projet">Les premières interviews sur ce projet</h2>

<p>Écoutez vous même Gil Elbaz parler du projet lors du lancement de Common Crawl il y a plus de dix ans: </p>
<iframe width="425" height="350" src="https://www.youtube.com/watch?v=cjtZW6hR_o0" title="Starts up" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<p>Cette vidéo nous a été conseillé par Rich Skrenta</p>

      <footer>
        <span class="ribbon-outer">
          <span class="ribbon-inner">

          </span>
          <span class="left-tail"></span>
          <span class="right-tail"></span>
        </span>
  
        <span class="octocat"></span>
      </footer>
