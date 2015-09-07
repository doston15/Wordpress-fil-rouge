# Wordpress-fil-rouge
Fil rouge wordpress

Choix de thémes
<!DOCTYPE html>
<!--[if IE 8]>
<html xmlns="http://www.w3.org/1999/xhtml" class="ie8 wp-toolbar"  lang="fr">
<![endif]-->
<!--[if !(IE 8) ]><!-->
<html xmlns="http://www.w3.org/1999/xhtml" class="wp-toolbar"  lang="fr">
<!--<![endif]-->
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<title>Gérer les thèmes &lsaquo; juniorp15 &#8212; WordPress</title>
<script type="text/javascript">
addLoadEvent = function(func){if(typeof jQuery!="undefined")jQuery(document).ready(func);else if(typeof wpOnload!='function'){wpOnload=func;}else{var oldonload=wpOnload;wpOnload=function(){oldonload();func();}}};
var ajaxurl = '/wp-admin/admin-ajax.php',
	pagenow = 'themes',
	typenow = '',
	adminpage = 'themes-php',
	thousandsSeparator = ' ',
	decimalPoint = ',',
	isRtl = 0;
</script>
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<link rel='stylesheet' id='all-css-0' href='https://s1.wp.com/wp-content/mu-plugins/smileyproject/smileyproject.css?m=1412325662g' type='text/css' media='all' />
<link rel='stylesheet' id='open-sans-css'  href='https://fonts.googleapis.com/css?family=Open+Sans%3A300italic%2C400italic%2C600italic%2C300%2C400%2C600&#038;subset=latin%2Clatin-ext&#038;ver=4.3' type='text/css' media='all' />
<link rel='stylesheet' id='all-css-2' href='https://s2.wp.com/_static/??-eJx9j0kOwjAMAD9EaoJ66AXxljgJNCWbYqeF3xNVomIR3LyM7TEsWbiofTWWQBOBUTQ6nSJ1wcWuVXbwiSjTWgJVeUPaDNvIEKrIvl5cJKCKpIvL7No+OCfv0/KPH9Nsi8CK6Nsp4ru33wYTATfDK6bbFmzUqrZKPpPfb2BlfvnzFI6y76XcD8NBTg/DxGds' type='text/css' media='all' />
<!--[if lte IE 7]>
<link rel='stylesheet' id='ie-css'  href='https://s2.wp.com/wp-admin/css/ie.min.css?m=1439796907g&#038;ver=4.3' type='text/css' media='all' />
<![endif]-->
<link rel='stylesheet' id='all-css-6' href='https://s1.wp.com/_static/??-eJyFUttuwyAM/aG5rFtUbQ/TvsV1WUKDAYHZ7evnJG2UCal9Aftwjq+YrwQukK8nWwyVYtTHKgPQYGncsQs7RR8mmGIQG8RwheRr70IxeFICHDHrO0WG1V9EzoQoTnVlNZpo52KK9Zbk6Xo3lCXqNafm4Rqc/IBg39vcAPf0tUhk9zspV/NWk5wOCnNCmc0BaWzb2PD7rNXEMD8hCXzEzPNo2YYK6OVuifY7xSy6gujospb/0K30Omm72Qx8tgPdsKPHPC7nSpu1l8+gjU/4O7/tu25/6B5fnl/Pf5wy0pY=' type='text/css' media='all' />
<style type="text/css">
#welcome .col1 {
	float: left;
	width: 50%;
}
.rtl #welcome .col1 {
	float:right;
}
#welcome .col3 {
	float: right;
	width: 50%;
	padding-bottom: 10px;
}
.rtl #welcome .col3 {
	float: left
}

#welcome .col3 h3 {
margin-bottom: 5px;
}
#welcome .col3 h4 {
margin-bottom: 5px;
}
#welcome .col3 ul {
margin-left: 15px;
}
.rtl #welcome .col3 ul {
	margin-left: 0;
	margin-right: 15px;
}
#welcome .col3 li {
list-style: circle;
}
#welcome #welcome-video {
	padding: 10px 0;
}
#welcome #welcome-video {
	text-align: center;
}
#welcome-video .video-player {
	margin: auto;
}
#are-you-new {
	font-weight: bold;
}
#are-you-new {
	text-decoration: underline;
	background: #eee;
	padding: 3px 10px;
	border-radius: 15px;
}
a#are-you-new:hover {
	text-decoration: none !important;
	background: #ccc;
}
div.hide-links {
	float: right;
	margin-bottom: 8px;
}
.rtl div.hide-links {
	float:left;
}
div.hide-links a {
	padding-left: 8px;
}
.rtl div.hide-links a {
	padding-left: 0;
	padding-right: 8px;
}
</style>
		<script id="tmpl-sorting" type="text/template">
			<span data-sort="trending" class="theme-sort-order">Trending</span>
			<span data-sort="popular" class="theme-sort-order">Populaire</span>
			<span data-sort="newest" class="theme-sort-order">Nouveaut&eacute;s</span>

			<div class="theme-nature">
				<span data-nature="all">Tous</span>
				<span data-nature="free">Gratuit</span>
				<span data-nature="premium">Premium</span>
							</div>
		</script>

		<script id="tmpl-wpcom-theme" type="text/template">
			<# if ( data.screenshot[0] ) { #>
				<div class="theme-screenshot">
					<img src="{{ data.screenshot[0] }}" alt="" />
				</div>
			<# } else { #>
				<div class="theme-screenshot blank"></div>
			<# } #>
			<span class="more-details" id="{{ data.id }}-action">Détails du thème</span>
			<div class="theme-author">Par {{{ data.author }}}</div>

			<# if ( data.active ) { #>
				<h3 class="theme-name" id="{{ data.id }}-name">
					<span>Actif :</span> {{ data.name }}				</h3>
			<# } else { #>
				<h3 class="theme-name" id="{{ data.id }}-name">{{{ data.name }}}</h3>
			<# } #>

			<# if ( data.premium ) { #>
				<# if ( data.premium.purchased ) { #>
					<span class="theme-price purchased">
						Achet&eacute;					</span>
				<# } else { #>
					<span class="theme-price">
						{{{ data.premium.price }}}
					</span>
				<# } #>
			<# } #>

			<div class="theme-actions">

			<# if ( data.active ) { #>
				<# if ( data.actions.customize ) { #>
					<a class="button button-primary customize load-customize hide-if-no-customize" href="{{ data.actions.customize }}">Personnaliser</a>
				<# } #>
			<# } else { #>

				<# if ( data.premium && !data.premium.purchased ) { #>
					<a class="button button-primary activate" href="{{{ data.actions.purchase }}}">Acheter</a>
				<# } else { #>
					<a class="button button-primary activate" href="{{{ data.actions.activate }}}">Activer</a>
				<# } #>

				<a class="button button-secondary load-customize hide-if-no-customize" href="{{{ data.actions.customize }}}">Aperçu</a>
			<# } #>

			</div>

			<# if ( data.hasUpdate ) { #>
				<div class="theme-update">Mise à jour disponible</div>
			<# } #>
		</script>

				<script id="tmpl-wpcom-theme-single" type="text/template">
			<div class="theme-backdrop"></div>
			<div class="theme-wrap">
				<div class="theme-header">
					<button class="left dashicons dashicons-no"><span class="screen-reader-text">Affichier le thème précédent</span></button>
					<button class="right dashicons dashicons-no"><span class="screen-reader-text">Afficher le thème suivant</span></button>
					<button class="close dashicons dashicons-no"><span class="screen-reader-text">Fermer la fenêtre de détails du dialogue</span></button>
				</div>
				<div class="theme-about">
					<div class="theme-screenshots">
					<# if ( data.screenshot[0] ) { #>
						<div class="screenshot"><img src="{{ data.screenshot[0] }}" alt="" /></div>
					<# } else { #>
						<div class="screenshot blank"></div>
					<# } #>
					</div>

					<div class="theme-info">
						<# if ( data.active ) { #>
							<span class="current-label">Thème actuel</span>
						<# } #>
						<h3 class="theme-name">{{{ data.name }}}<span class="theme-version">Version&nbsp;: {{ data.version }}</span></h3>
						<h4 class="theme-author">Par {{{ data.authorAndUri }}}</h4>

						<# if ( data.hasUpdate ) { #>
						<div class="theme-update-message">
							<h4 class="theme-update">Mise à jour disponible</h4>
							{{{ data.update }}}
						</div>
						<# } #>
						<p class="theme-description">{{{ data.description }}}</p>

						<# if ( data.parent ) { #>
							<p class="parent-theme">This is a child theme of <strong>{{{ data.parent }}}</strong>.</p>
						<# } #>

						<# if ( data.tags ) { #>
							<p class="theme-tags"><span>Mots-clés&nbsp;:</span> {{{ data.tags }}}</p>
						<# } #>
					</div>
				</div>

				<div class="theme-actions">
					<div class="active-theme">
						<a href="{{{ data.actions.customize }}}" class="button button-primary customize load-customize hide-if-no-customize">Personnaliser</a>
						<a class='button button-secondary' href='widgets.php'>Widgets</a> <a class='button button-secondary' href='nav-menus.php'>Menus</a> <a class='button button-secondary' href='themes.php?page=https://juniorp15.wordpress.com/wp-admin/customize.php?autofocus%5Bsection%5D=colors_manager_tool'>Arrière-plan</a> <a class='button button-secondary hide-if-no-customize' href='customize.php?autofocus[control]=background_image'>Arrière-plan</a> <a class='button button-secondary' href='themes.php?page=custom-background'>Arrière-plan</a> <a class='button button-secondary' href='themes.php?page=mobile-options'>Portable</a>					</div>
					<div class="inactive-theme">
						<# if ( data.actions.activate ) { #>
							<# if ( data.premium && !data.premium.purchased ) { #>
								<a href="{{{ data.actions.purchase }}}" class="button button-primary">
									Acheter									<span class="price">{{{ data.premium.price }}}</span>
								</a>
							<# } else { #>
								<a href="{{{ data.actions.activate }}}" class="button button-primary">Activer</a>
							<# } #>
						<# } #>

						<a href="{{{ data.actions.customize }}}" class="button button-secondary load-customize hide-if-no-customize">Aperçu</a>
						<# if ( data.demoUrl ) { #>
						<a href="{{{ data.demoUrl }}}" class="button button-secondary" target="_blank">Démo</a>
						<# } #>
					</div>

					<# if ( ! data.active && data.actions['delete'] ) { #>
						<a href="{{{ data.actions['delete'] }}}" class="button button-secondary delete-theme">Supprimer </a>
					<# } #>
				</div>
			</div>
		</script>
		<script type="text/javascript">
if (window.top !== window.self) {
    window.top.location.href = window.self.location.href; }
</script><script type='text/javascript'>
/* <![CDATA[ */
var userSettings = {"url":"\/","uid":"93895094","time":"1441657208","secure":"1"};
var userSettings = {"url":"\/","uid":"93895094","time":"1441657209","secure":"1"};
/* ]]> */
</script>
<script type='text/javascript' src='https://s0.wp.com/_static/??-eJyFUNkOwjAM+yFKxSl4QHxL12VVRi+alGl/T8cljgFSpCi2W8eRXRTotc01kGxLHTOk/tamLU3kL4FwaJJimDr0d7EOnsGzdFlEmw16kpQr0gkjYyhTE6wN3bu8fB0DsQMiZWDMOTNaenZ6WYuCn38jKX559BL2jyqj1CGNRh0swILm+b2PqVRdwMdNdHAue+ResDIG0gfw454d1gaYJJwKUSVkGFa4ouJiM5ajAagrpQ+F27vdbLnYblazxXrdngH2qcAB'></script>
<link rel="shortcut icon" type="image/x-icon" href="https://s2.wp.com/i/favicon.ico" sizes="16x16 24x24 32x32 48x48" />
<link rel="icon" type="image/x-icon" href="https://s2.wp.com/i/favicon.ico" sizes="16x16 24x24 32x32 48x48" />
<link rel="apple-touch-icon-precomposed" href="https://s0.wp.com/i/webclip.png" />
<style type="text/css" media="print">#wpadminbar { display:none; }</style>
<meta name="application-name" content="juniorp15" /><meta name="msapplication-window" content="width=device-width;height=device-height" /><meta name="msapplication-tooltip" content="Articles de l&#039;auteur, gestion des commentaires et gestion juniorp15." /><meta name="msapplication-task" content="name=Ecrire un article;action-uri=https://juniorp15.wordpress.com/wp-admin/post-new.php;icon-uri=https://s2.wp.com/i/icons/post.ico" /><meta name="msapplication-task" content="name=Modérer les commentaires;action-uri=https://juniorp15.wordpress.com/wp-admin/edit-comments.php?comment_status=moderated;icon-uri=https://s0.wp.com/i/icons/comment.ico" /><meta name="msapplication-task" content="name=Envoi d&#039;un nouveau média;action-uri=https://juniorp15.wordpress.com/wp-admin/media-new.php;icon-uri=https://s2.wp.com/i/icons/media.ico" /><meta name="msapplication-task" content="name=Stats du Site;action-uri=https://juniorp15.wordpress.com/wp-admin/index.php?page=stats;icon-uri=https://s1.wp.com/i/icons/stats.ico" />	<link id="wp-admin-canonical" rel="canonical" href="https://juniorp15.wordpress.com/wp-admin/themes.php" />
	<script>
		if ( window.history.replaceState ) {
			window.history.replaceState( null, null, document.getElementById( 'wp-admin-canonical' ).href + window.location.hash );
		}
	</script>
<script type="text/javascript">var _wpColorScheme = {"icons":{"base":"#999","focus":"#00a0d2","current":"#fff"}};</script>

<style type="text/css" media="screen">

#polldaddy-error.error{
	border-radius:6px;
	margin-left:5px;
	margin-right:2%;
	background-color:#FFC;
	background:url('/wp-content/admin-plugins/post-flair/polldaddy/img/error-gray.png') no-repeat 3px 3px, -moz-linear-gradient(top, #FFF, #FFC);
	background:url('/wp-content/admin-plugins/post-flair/polldaddy/img/error-gray.png') no-repeat 3px 3px, -webkit-linear-gradient(top, #FFF, #FFC);
	margin-top:14px;
	border:1px #cccccc solid;
	padding:3px 5px 3px 40px;
}


h2#polldaddy-header, h2#poll-list-header{
	padding-left:38px;
	background:url('/wp-content/admin-plugins/post-flair/polldaddy/img/pd-wp-icon-gray-lrg.png') no-repeat 0 9px;
	margin-bottom: 14px; 
}

@media only screen and (-moz-min-device-pixel-ratio: 1.5), only screen and (-o-min-device-pixel-ratio: 3/2), only screen and (-webkit-min-device-pixel-ratio: 1.5), only screen and (min-device-pixel-ratio: 1.5) {

	#adminmenu .menu-icon-feedback:hover div.wp-menu-image,
	#adminmenu .menu-icon-feedback.wp-has-current-submenu div.wp-menu-image,
	#adminmenu .menu-icon-feedback.current div.wp-menu-image {
		background: url('/wp-content/admin-plugins/post-flair/polldaddy/img/grunion-menu-hover-2x.png') no-repeat 7px 7px !important;
		background-size: 15px 16px !important;
	}

	#adminmenu .menu-icon-feedback div.wp-menu-image {
		background: url('/wp-content/admin-plugins/post-flair/polldaddy/img/grunion-menu-2x.png') no-repeat 7px 7px !important;
		background-size: 15px 16px !important;
	}
	
	
	h2#polldaddy-header, h2#poll-list-header{
		background:url('/wp-content/admin-plugins/post-flair/polldaddy/img/pd-wp-icon-gray-lrg@2x.png') no-repeat 0 9px;
		background-size: 31px 31px;
	}
}	

	
	
</style>
	<style type="text/css">
		#wp-content-editor-tools {
			height: auto;
		}
				.wp-editor-container {
			clear: both;
		}
			</style>
<style type="text/css" id="syntaxhighlighteranchor"></style>
</head>
<body class="wp-admin wp-core-ui no-js  mp6  admin-color-mp6 legacy-color-fresh themes-php auto-fold admin-bar branch-4-3 version-4-3 admin-color-fresh locale-fr multisite no-customize-support no-svg">
<script type="text/javascript">
	document.body.className = document.body.className.replace('no-js','js');
</script>

	<script type="text/javascript">
		(function() {
			var request, b = document.body, c = 'className', cs = 'customize-support', rcs = new RegExp('(^|\\s+)(no-)?'+cs+'(\\s+|$)');

			request = true;

			b[c] = b[c].replace( rcs, ' ' );
			b[c] += ( window.postMessage && request ? ' ' : ' no-' ) + cs;
		}());
	</script>
	
<div id="wpwrap">

<div id="adminmenumain" role="navigation" aria-label="Menu principal">
<a href="#wpbody-content" class="screen-reader-shortcut">Aller au contenu principal</a>
<a href="#wp-toolbar" class="screen-reader-shortcut">Aller à la barre d&rsquo;outils</a>
<div id="adminmenuback"></div>
<div id="adminmenuwrap">
<ul id="adminmenu">


	<li class="wp-first-item wp-has-submenu wp-not-current-submenu menu-top menu-top-first menu-icon-dashboard" id="menu-dashboard">
	<a href='index.php' class="wp-first-item wp-has-submenu wp-not-current-submenu menu-top menu-top-first menu-icon-dashboard" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-dashboard'><br /></div><div class='wp-menu-name'>Tableau de bord</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Tableau de bord</li><li class="wp-first-item"><a href='index.php' class="wp-first-item">Accueil</a></li><li><a href='index.php?page=my-comments'>Mes Commentaires</a></li><li><a href='index.php?page=stats'>Stats du Site</a></li><li><a href='index.php?page=my-blogs'>Mes Blogs</a></li><li><a href='index.php?page=subscriptions'>Mes abonnements</a></li><li><a href='index.php?page=akismet-stats'>Statistiques Akismet</a></li><li><a href='index.php?page=omnisearch'>Omnisearch</a></li></ul></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top toplevel_page_paid-upgrades menu-top-last" id="toplevel_page_paid-upgrades">
	<a href='paid-upgrades.php' class="wp-has-submenu wp-not-current-submenu menu-top toplevel_page_paid-upgrades menu-top-last" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-cart'><br /></div><div class='wp-menu-name'>Boutique</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Boutique</li><li class="wp-first-item"><a href='paid-upgrades.php' class="wp-first-item">Boutique</a></li><li><a href='themes.php?type=premium&ref=store'>Thèmes Premium</a></li><li><a href='paid-upgrades.php?page=domains'>Mes Domaines</a></li><li><a href='paid-upgrades.php?page=my-upgrades'>Mes Extensions</a></li><li><a href='paid-upgrades.php?page=billing-history'>Mes paiements</a></li></ul></li>
	<li class="wp-not-current-submenu wp-menu-separator" aria-hidden="true"><div class="separator"></div></li>
	<li class="wp-has-submenu wp-not-current-submenu open-if-no-js menu-top menu-icon-post menu-top-first" id="menu-posts">
	<a href='edit.php' class="wp-has-submenu wp-not-current-submenu open-if-no-js menu-top menu-icon-post menu-top-first" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-post'><br /></div><div class='wp-menu-name'>Articles</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Articles</li><li class="wp-first-item"><a href='edit.php' class="wp-first-item">Tous les articles</a></li><li><a href='post-new.php'>Ajouter</a></li><li><a href='edit-tags.php?taxonomy=category'>Catégories</a></li><li><a href='edit-tags.php?taxonomy=post_tag'>Mots-clés</a></li><li><a href='post-new.php?cap#cap'>Copier un Article</a></li></ul></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-media" id="menu-media">
	<a href='upload.php' class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-media" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-media'><br /></div><div class='wp-menu-name'>Médias</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Médias</li><li class="wp-first-item"><a href='upload.php' class="wp-first-item">Bibliothèque</a></li><li><a href='media-new.php'>Ajouter</a></li></ul></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-links" id="menu-links">
	<a href='link-manager.php' class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-links" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-links'><br /></div><div class='wp-menu-name'>Liens</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Liens</li><li class="wp-first-item"><a href='link-manager.php' class="wp-first-item">Tous les liens</a></li><li><a href='link-add.php'>Ajouter</a></li><li><a href='edit-tags.php?taxonomy=link_category'>Catégories de liens</a></li></ul></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-page" id="menu-pages">
	<a href='edit.php?post_type=page' class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-page" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-page'><br /></div><div class='wp-menu-name'>Pages</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Pages</li><li class="wp-first-item"><a href='edit.php?post_type=page' class="wp-first-item">Toutes les pages</a></li><li><a href='post-new.php?post_type=page'>Ajouter</a></li><li><a href='edit-tags.php?taxonomy=post_tag&amp;post_type=page'>Mots-clés</a></li><li><a href='post-new.php?post_type=page&cap#cap'>Copier une Page</a></li></ul></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-jetpack-portfolio" id="menu-posts-jetpack-portfolio">
	<a href='edit.php?post_type=jetpack-portfolio' class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-jetpack-portfolio" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-portfolio'><br /></div><div class='wp-menu-name'>Portfolio</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Portfolio</li><li class="wp-first-item"><a href='edit.php?post_type=jetpack-portfolio' class="wp-first-item">Tous les Projets</a></li><li><a href='post-new.php?post_type=jetpack-portfolio'>Ajouter</a></li><li><a href='edit-tags.php?taxonomy=post_tag&amp;post_type=jetpack-portfolio'>Mots-clés</a></li><li><a href='edit-tags.php?taxonomy=jetpack-portfolio-type&amp;post_type=jetpack-portfolio'>Types de projet</a></li><li><a href='edit-tags.php?taxonomy=jetpack-portfolio-tag&amp;post_type=jetpack-portfolio'>Tags de Projet</a></li></ul></li>
	<li class="wp-not-current-submenu menu-top menu-icon-comments" id="menu-comments">
	<a href='edit-comments.php' class="wp-not-current-submenu menu-top menu-icon-comments" ><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-comments'><br /></div><div class='wp-menu-name'>Commentaires <span class='awaiting-mod count-0'><span class='pending-count'>0</span></span></div></a></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top toplevel_page_feedback menu-top-last" id="toplevel_page_feedback"><a href='admin.php?page=polls' class="wp-has-submenu wp-not-current-submenu menu-top toplevel_page_feedback menu-top-last" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-feedback'><br /></div><div class='wp-menu-name'>Retours</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Retours</li><li class="wp-first-item"><a href='admin.php?page=polls' class="wp-first-item">Sondages</a></li><li><a href='edit.php?post_type=feedback'>Retours</a></li></ul></li>
	<li class="wp-not-current-submenu wp-menu-separator" aria-hidden="true"><div class="separator"></div></li>
	<li class="wp-has-submenu wp-has-current-submenu wp-menu-open menu-top menu-icon-appearance menu-top-first" id="menu-appearance">
	<a href='themes.php' class="wp-has-submenu wp-has-current-submenu wp-menu-open menu-top menu-icon-appearance menu-top-first" ><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-appearance'><br /></div><div class='wp-menu-name'>Apparence</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Apparence</li><li class="wp-first-item current"><a href='themes.php' class="wp-first-item current">Thèmes</a></li><li class="hide-if-no-customize"><a href='customize.php?return=%2Fwp-admin%2Fthemes.php' class="hide-if-no-customize">Personnaliser</a></li><li><a href='widgets.php'>Widgets</a></li><li><a href='nav-menus.php'>Menus</a></li><li class="hide-if-no-customize"><a href='customize.php?return=%2Fwp-admin%2Fthemes.php&#038;autofocus%5Bcontrol%5D=header_image' class="hide-if-no-customize">En-tête</a></li><li class="hide-if-no-customize"><a href='https://juniorp15.wordpress.com/wp-admin/customize.php?autofocus%5Bsection%5D=colors_manager_tool' class="hide-if-no-customize">Arrière-plan</a></li><li><a href='themes.php?page=custom-background'>Arrière-plan</a></li><li><a href='themes.php?page=mobile-options'>Portable</a></li></ul></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-users" id="menu-users">
	<a href='users.php' class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-users" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-users'><br /></div><div class='wp-menu-name'>Utilisateurs</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Utilisateurs</li><li class="wp-first-item"><a href='users.php' class="wp-first-item">Tous les utilisateurs</a></li><li><a href='users.php?page=wpcom-invite-users'>Inviter</a></li><li><a href='users.php?page=grofiles-editor'>Mon Profil</a></li><li><a href='users.php?page=grofiles-user-settings'>Param.Personnels</a></li></ul></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-tools" id="menu-tools">
	<a href='tools.php' class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-tools" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-tools'><br /></div><div class='wp-menu-name'>Outils</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Outils</li><li class="wp-first-item"><a href='tools.php' class="wp-first-item">Outils disponibles</a></li><li><a href='import.php'>Importer</a></li><li><a href='tools.php?page=delete-blog'>Supprimer mon site</a></li><li><a href='tools.php?page=export-choices'>Exporter</a></li></ul></li>
	<li class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-settings menu-top-last" id="menu-settings">
	<a href='options-general.php' class="wp-has-submenu wp-not-current-submenu menu-top menu-icon-settings menu-top-last" aria-haspopup="true"><div class="wp-menu-arrow"><div></div></div><div class='wp-menu-image dashicons-before dashicons-admin-settings'><br /></div><div class='wp-menu-name'>Réglages</div></a>
	<ul class='wp-submenu wp-submenu-wrap'><li class='wp-submenu-head' aria-hidden='true'>Réglages</li><li class="wp-first-item"><a href='options-general.php' class="wp-first-item">Général</a></li><li><a href='options-writing.php'>Écriture</a></li><li><a href='options-reading.php'>Lecture</a></li><li><a href='options-discussion.php'>Discussion</a></li><li><a href='options-media.php'>Médias</a></li><li><a href='options-general.php?page=sharing'>Partage</a></li><li><a href='options-general.php?page=polls&#038;action=options'>Sondages</a></li><li><a href='options-general.php?page=adcontrol'>AdControl</a></li><li><a href='options-general.php?page=email_post_changes'>Options Notifications</a></li><li><a href='options-general.php?page=openidserver'>OpenID</a></li><li><a href='options-general.php?page=webhooks'>Webhooks</a></li></ul></li><li id="collapse-menu" class="hide-if-no-js"><div id="collapse-button"><div></div></div><span>Réduire le menu</span></li></ul>
</div>
</div>
<div id="wpcontent">


<div id="wpbody" role="main">

<div id="wpbody-content" aria-label="Contenu principal" tabindex="0">
		<div id="screen-meta" class="metabox-prefs">

			<div id="contextual-help-wrap" class="hidden no-sidebar" tabindex="-1" aria-label="Onglet d&rsquo;aide contextuelle">
				<div id="contextual-help-back"></div>
				<div id="contextual-help-columns">
					<div class="contextual-help-tabs">
						<ul>
						
							<li id="tab-link-overview" class="active">
								<a href="#tab-panel-overview" aria-controls="tab-panel-overview">
									Vue d&rsquo;ensemble								</a>
							</li>
						
							<li id="tab-link-customize-preview-themes">
								<a href="#tab-panel-customize-preview-themes" aria-controls="tab-panel-customize-preview-themes">
									Aperçu et personnalisation								</a>
							</li>
						
							<li id="tab-link-wpcom-feedback">
								<a href="#tab-panel-wpcom-feedback" aria-controls="tab-panel-wpcom-feedback">
									Obtenir de l&#039;aide								</a>
							</li>
												</ul>
					</div>

					
					<div class="contextual-help-tabs-wrap">
						
							<div id="tab-panel-overview" class="help-tab-content active">
								<p>Cet écran est utilisé pour gérer vos thèmes installés. En dehors des thèmes par défaut inclus dans votre installation de WordPress, les thèmes sont conçus et développés par des tiers.</p><p>Depuis cet écran, vous pouvez&nbsp;:</p><ul><li>Survolez out touchez pour voir les boutons Activer et Prévisualisation</li><li>Cliquez sur le thème pour voir le nom du thème, sa version, son auteur, sa description, ses mots-clés et le bouton Supprimer.</li><li>Cliquez sur Personnaliser pour le thème actuel ou Prévisualisation pour n&rsquo;importe quel autre thème pour voir la prévisualisation</li></ul><p>Le thème actuel est affiché en étant mis en avant en tant que premier thème.</p><p>La recherche parmi les thèmes installés se fait sur leurs noms, leurs descriptions, leurs auteurs et leurs étiquettes. <span id="live-search-desc">The search results will be updated as you type.</span></p>							</div>
						
							<div id="tab-panel-customize-preview-themes" class="help-tab-content">
								<p>Touchez ou survolez n&rsquo;importe quel thème puis cliquez sur le bouton Prévisualisation pour voir une prévisualisation de ce thème et changer les options du thème dans un vie séparée et plein écran. Vous pouvez également trouver un bouton Prévisualisation au bas de l&rsquo;écran de détails du thème. Tout thème installé peut être prévisualisé et personnalisé de cette manière.</p><p>Le thème en cours de prévisualisation est totalement interactif &mdash; naviguez sur les différentes pages pour voir comment le thème affiche vos articles, archives et autres pages. Les réglages peuvent différer selon les fonctionnalités pour lesquelles le thème a été conçu. Pour valider les nouveaux réglages et activer le thème en un seul coup, cliquez sur le bouton "Enregistrer et activer" en haut du menu.</p><p>Lors de la prévisualisation sur de petits écrans, vous pouvez utiliser l&rsquo;icône de réduction en bas à gauche du panneau. Cela cachera le panneau, vous donnant ainsi plus de place pour prévisualiser le site avec le nouveau thème. Pour ramener le panneau, cliquez à nouveau sur l&rsquo;icône de réduction.</p>							</div>
						
							<div id="tab-panel-wpcom-feedback" class="help-tab-content">
								<div id="quicklookup"><p>Choisissez une Cat&eacute;gorie:</p><ul class="supportcats"><li><a onclick="fbshow('appearance')">Apparence</a></li>
<li><a onclick="fbshow('comments')">Commentaires</a></li>
<li><a onclick="fbshow('configuration')">Configuration</a></li>
<li><a onclick="fbshow('general')">Généraux</a></li>
<li><a onclick="fbshow('languages')">Langues</a></li>
<li><a onclick="fbshow('links')">Liens</a></li>
<li><a onclick="fbshow('media')">Média</a></li>
<li><a onclick="fbshow('following')">Abonnements</a></li>
<li><a onclick="fbshow('tools')">Outils</a></li>
<li><a onclick="fbshow('policies-safety')">Politiques et Sécurité</a></li>
<li><a onclick="fbshow('traffic')">Trafic</a></li>
<li><a onclick="fbshow('upgrades')">Extensions</a></li>
<li><a onclick="fbshow('users')">Utilisateurs</a></li>
<li><a onclick="fbshow('widgets-sidebars')">Widgets &amp; Sidebars</a></li>
<li><a onclick="fbshow('writing-editing')">Rédiger et Modifier</a></li>
</ul><br class="clear" /></div><style>#contextual-help-wrap div.hbl_pal_main_width {width: 100% !important;}</style><p><div id="olark-box-container"></div></p>							</div>
											</div>
				</div>
			</div>
				</div>
				<div id="screen-meta-links">
					<div id="contextual-help-link-wrap" class="hide-if-no-js screen-meta-toggle">
			<button type="button" id="contextual-help-link" class="button show-settings" aria-controls="contextual-help-wrap" aria-expanded="false">Aide</button>
			</div>
				</div>
		<div id="welcome" class="updated" style="display: none">
<div id="blog-is-yours" class="col1">
<h2>Bienvenue sur WordPress.com !</h2>
<p>Vous vous trouvez à présent dans le « tableau de bord » de votre blog. Vous pouvez rédiger de nouveaux articles et contrôler un grand nombre de fonctionnalités et de paramètres majeurs.</p>

<p>Vous seul pouvez voir l'adresse de votre tableau de bord, qui se trouve à l'emplacement suivant :<br />
<a dir="ltr" href="https://juniorp15.wordpress.com/wp-admin/">juniorp15.wordpress.com/wp-admin/</a></p>
				<p>Vous avez des questions techniques ? <a class="support" href="http://support.wordpress.com/" target="_blank">Nos pages de documentation sont disponibles&nbsp;24 heures/24 et 7 jours/7</a></p>
</div>

<div class="col3">

<h3>Ressources utiles&nbsp;:</h3>
<h4>Dans votre tableau de bord :</h4>
<ul>
	<li><a href="/wp-admin/post-new.php" class="resource-post" target="_blank">Ecrire un article</a></li>
	<li><a href="/wp-admin/options-general.php" class="resource-settings" target="_blank">Paramètres Généraux</a></li>
	<li><a class="resource-profile" href="/wp-admin/profile.php" target="_blank">Votre profil</a></li>
	<li><a href="/wp-admin/options-general.php" class="resource-themes" target="_blank">Choisissez votre thème</a></li>
	<li><a class="resource-upgrades" href="/wp-admin/paid-upgrades.php" target="_blank">Boutique des Extensions: Dynamisez votre blog</a></li>
	<li><a class="elsewhere-tv" href="http://wordpress.tv/" target="_blank">WordPress.tv</a></li>
</ul>

</div>

<div class="clear"></div>
<div class="hide-links">
	<a id="close-welcome-screen" href="#" title="Fermer cet écran">Fermer cet écran</a>
</div>
<div class="clear"></div>
</div>
	    <div class="updated tip-email-verify" id="wpcom-tip">
	        <p><strong>Entrez votre adresse email</strong>Afin de publier un article, s'il vous plaît vérifier votre adresse email en cliquant sur le lien dans l'email de confirmation que nous avons envoyé à philippejuniors7@gmx.com.<br/><a href="" id="resend-verifyemail" data-nonce="90934a1f91">Renvoyer email</a> | <a target="_blank" href="//wordpress.com/settings/account/">Mettre à jour l'adresse email</a></p>
	    </div>
	    		<script>
			jQuery( '#resend-verifyemail' ).on( 'click', function(e) {
				var link = jQuery(e.target);

				e.preventDefault();

				var r = jQuery.ajax( {
					type: 'POST',
					url: '/wp-admin/admin-ajax.php',
					data: {
						'action': 'resend_verify_email',
						'_wpnonce': link.data( 'nonce' )
					}
				} );

				setTimeout( function() {
					link.hide();
					link.after( '<strong id="email-sent">Email Envoy&eacute;</strong>' );
				}, 200 );

				setTimeout( function() {
					jQuery( "strong#email-sent" ).hide().remove();
					link.show();
				}, 4000 );
			} );
		</script>
	
<div class="wrap">
	<h1>Thèmes		<span class="title-count theme-count">361</span>
		</h1>

<div class="theme-browser">
	<div class="themes">

<div class="theme active" tabindex="0" aria-describedby="pub/sketch-action pub/sketch-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/sketch/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sketch-action">Détails du thème</span>
	<div class="theme-author">Par WordPress.com</div>

			<h3 class="theme-name" id="pub/sketch-name">
			<span>Actif :</span> Sketch		</h3>
	
	<div class="theme-actions">

						<a class="button button-primary customize load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsketch">Personnaliser</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/independent-publisher-action pub/independent-publisher-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/independent-publisher/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/independent-publisher-action">Détails du thème</span>
	<div class="theme-author">Par Raam Dev</div>

			<h3 class="theme-name" id="pub/independent-publisher-name">Independent Publisher</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Findependent-publisher&amp;_wpnonce=6908cb3aa0">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Findependent-publisher">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/colinear-action pub/colinear-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/colinear/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/colinear-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/colinear-name">Colinear</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcolinear&amp;_wpnonce=0477230b00">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcolinear">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/paulie-action premium/paulie-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/paulie/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/paulie-action">Détails du thème</span>
	<div class="theme-author">Par SiloCreativo</div>

			<h3 class="theme-name" id="premium/paulie-name">Paulie</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/paulie&#038;ref=themesphp&#038;_wpnonce=0026281ea1">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpaulie">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/exhibit-action premium/exhibit-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/exhibit/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/exhibit-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/exhibit-name">Exhibit</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/exhibit&#038;ref=themesphp&#038;_wpnonce=894ed5665a">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fexhibit">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/blask-action pub/blask-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/blask/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/blask-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/blask-name">Blask</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fblask&amp;_wpnonce=a82ca99499">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fblask">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/huesos-action premium/huesos-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/huesos/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/huesos-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/huesos-name">Huesos</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/huesos&#038;ref=themesphp&#038;_wpnonce=f766bbf2d9">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fhuesos">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/blink-action premium/blink-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/blink/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/blink-action">Détails du thème</span>
	<div class="theme-author">Par Codestag</div>

			<h3 class="theme-name" id="premium/blink-name">Blink</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/blink&#038;ref=themesphp&#038;_wpnonce=47f2b99ce2">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fblink">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/lovecraft-action pub/lovecraft-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/lovecraft/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/lovecraft-action">Détails du thème</span>
	<div class="theme-author">Par Anders Noren</div>

			<h3 class="theme-name" id="pub/lovecraft-name">Lovecraft</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Flovecraft&amp;_wpnonce=cf211c4584">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Flovecraft">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/maisha-action premium/maisha-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/maisha/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/maisha-action">Détails du thème</span>
	<div class="theme-author">Par Anariel Design</div>

			<h3 class="theme-name" id="premium/maisha-name">Maisha</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/maisha&#038;ref=themesphp&#038;_wpnonce=48cff94dd0">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmaisha">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/publication-action pub/publication-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/publication/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/publication-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/publication-name">Publication</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fpublication&amp;_wpnonce=037c9ac45f">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fpublication">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/appetite-action premium/appetite-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/appetite/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/appetite-action">Détails du thème</span>
	<div class="theme-author">Par Tasko</div>

			<h3 class="theme-name" id="premium/appetite-name">Appetite</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/appetite&#038;ref=themesphp&#038;_wpnonce=5ce581b027">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fappetite">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/franklin-action pub/franklin-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/franklin/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/franklin-action">Détails du thème</span>
	<div class="theme-author">Par Michael Burrows</div>

			<h3 class="theme-name" id="pub/franklin-name">Franklin</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ffranklin&amp;_wpnonce=b140354a2b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ffranklin">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/libretto-action pub/libretto-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/libretto/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/libretto-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/libretto-name">Libretto</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Flibretto&amp;_wpnonce=e1daaa0742">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Flibretto">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/edda-action pub/edda-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/edda/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/edda-action">Détails du thème</span>
	<div class="theme-author">Par Mel Choyce</div>

			<h3 class="theme-name" id="pub/edda-name">Edda</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fedda&amp;_wpnonce=a589503be6">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fedda">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/monet-action premium/monet-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/monet/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/monet-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/monet-name">Monet</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/monet&#038;ref=themesphp&#038;_wpnonce=f4eb20142b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmonet">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/p2-breathe-action pub/p2-breathe-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/p2-breathe/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/p2-breathe-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/p2-breathe-name">P2</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fp2-breathe&amp;_wpnonce=3197d50eeb">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fp2-breathe">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/mellow-action premium/mellow-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/mellow/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/mellow-action">Détails du thème</span>
	<div class="theme-author">Par ThemeTrust</div>

			<h3 class="theme-name" id="premium/mellow-name">Mellow</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/mellow&#038;ref=themesphp&#038;_wpnonce=982e1a54af">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmellow">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/libre-action pub/libre-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/libre/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/libre-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/libre-name">Libre</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Flibre&amp;_wpnonce=3afd800e10">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Flibre">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/baskerville-action pub/baskerville-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/baskerville/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/baskerville-action">Détails du thème</span>
	<div class="theme-author">Par Anders Norén</div>

			<h3 class="theme-name" id="pub/baskerville-name">Baskerville</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbaskerville&amp;_wpnonce=9eb79d2325">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbaskerville">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/argent-action pub/argent-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/argent/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/argent-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/argent-name">Argent</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fargent&amp;_wpnonce=8c745467c5">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fargent">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/christopher-action premium/christopher-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/christopher/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/christopher-action">Détails du thème</span>
	<div class="theme-author">Par SiloCreativo</div>

			<h3 class="theme-name" id="premium/christopher-name">Christopher</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/christopher&#038;ref=themesphp&#038;_wpnonce=7dd6f70139">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fchristopher">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/demand-action premium/demand-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/demand/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/demand-action">Détails du thème</span>
	<div class="theme-author">Par Press75</div>

			<h3 class="theme-name" id="premium/demand-name">Demand</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/demand&#038;ref=themesphp&#038;_wpnonce=141959cf70">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fdemand">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/gateway-action pub/gateway-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/gateway/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/gateway-action">Détails du thème</span>
	<div class="theme-author">Par Rescue Themes</div>

			<h3 class="theme-name" id="pub/gateway-name">Gateway</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fgateway&amp;_wpnonce=48542eb4cf">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fgateway">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/romero-action premium/romero-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/romero/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/romero-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/romero-name">Romero</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/romero&#038;ref=themesphp&#038;_wpnonce=652b0efd26">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fromero">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/apostrophe-action pub/apostrophe-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/apostrophe/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/apostrophe-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/apostrophe-name">Apostrophe</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fapostrophe&amp;_wpnonce=86cf0ee35c">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fapostrophe">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/twentyten-action pub/twentyten-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/twentyten/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/twentyten-action">Détails du thème</span>
	<div class="theme-author">Par the WordPress team</div>

			<h3 class="theme-name" id="pub/twentyten-name">Twenty Ten</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftwentyten&amp;_wpnonce=6033710e84">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftwentyten">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/coherent-action pub/coherent-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/coherent/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/coherent-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/coherent-name">Coherent</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcoherent&amp;_wpnonce=589eb772dc">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcoherent">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/boardwalk-action pub/boardwalk-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/boardwalk/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/boardwalk-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/boardwalk-name">Boardwalk</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fboardwalk&amp;_wpnonce=4c7477413a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fboardwalk">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/cerauno-action pub/cerauno-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/cerauno/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/cerauno-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/cerauno-name">Cerauno</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcerauno&amp;_wpnonce=38f19ba9e0">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcerauno">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/curator-action premium/curator-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/curator/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/curator-action">Détails du thème</span>
	<div class="theme-author">Par ThemeZilla</div>

			<h3 class="theme-name" id="premium/curator-name">Curator</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/curator&#038;ref=themesphp&#038;_wpnonce=d705ff5c81">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcurator">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/obsidian-action premium/obsidian-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/obsidian/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/obsidian-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/obsidian-name">Obsidian</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/obsidian&#038;ref=themesphp&#038;_wpnonce=8e49d956fe">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fobsidian">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/canard-action pub/canard-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/canard/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/canard-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/canard-name">Canard</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcanard&amp;_wpnonce=afa71da3ea">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcanard">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/snaps-action pub/snaps-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/snaps/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/snaps-action">Détails du thème</span>
	<div class="theme-author">Par Graph Paper Press</div>

			<h3 class="theme-name" id="pub/snaps-name">Snaps</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsnaps&amp;_wpnonce=7443c40b48">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsnaps">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/encore-action premium/encore-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/encore/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/encore-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/encore-name">Encore</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/encore&#038;ref=themesphp&#038;_wpnonce=1fbf0c9910">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fencore">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/atlas-action premium/atlas-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/atlas/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/atlas-action">Détails du thème</span>
	<div class="theme-author">Par Nudge Themes</div>

			<h3 class="theme-name" id="premium/atlas-name">Atlas</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/atlas&#038;ref=themesphp&#038;_wpnonce=b5b9732ded">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fatlas">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/twentytwelve-action pub/twentytwelve-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/twentytwelve/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/twentytwelve-action">Détails du thème</span>
	<div class="theme-author">Par the WordPress team</div>

			<h3 class="theme-name" id="pub/twentytwelve-name">Twenty Twelve</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftwentytwelve&amp;_wpnonce=8b7d41c8b5">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftwentytwelve">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/penscratch-action pub/penscratch-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/penscratch/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/penscratch-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/penscratch-name">Penscratch</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fpenscratch&amp;_wpnonce=4f53ee048e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fpenscratch">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/ecto-action pub/ecto-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/ecto/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/ecto-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/ecto-name">Ecto</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fecto&amp;_wpnonce=ada0397ee9">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fecto">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/edin-action pub/edin-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/edin/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/edin-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/edin-name">Edin</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fedin&amp;_wpnonce=f3a45471f8">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fedin">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/twentyfourteen-action pub/twentyfourteen-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/twentyfourteen/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/twentyfourteen-action">Détails du thème</span>
	<div class="theme-author">Par the WordPress team</div>

			<h3 class="theme-name" id="pub/twentyfourteen-name">Twenty Fourteen</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftwentyfourteen&amp;_wpnonce=9391a8d237">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftwentyfourteen">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/chateau-action pub/chateau-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/chateau/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/chateau-action">Détails du thème</span>
	<div class="theme-author">Par Ignacio Ricci</div>

			<h3 class="theme-name" id="pub/chateau-name">Chateau</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fchateau&amp;_wpnonce=e624232389">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fchateau">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/cubic-action pub/cubic-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/cubic/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/cubic-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/cubic-name">Cubic</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcubic&amp;_wpnonce=8f2d621955">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcubic">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/soho-action premium/soho-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/soho/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/soho-action">Détails du thème</span>
	<div class="theme-author">Par Viva Themes</div>

			<h3 class="theme-name" id="premium/soho-name">Soho</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/soho&#038;ref=themesphp&#038;_wpnonce=74440b9a8e">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fsoho">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/twentythirteen-action pub/twentythirteen-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/twentythirteen/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/twentythirteen-action">Détails du thème</span>
	<div class="theme-author">Par the WordPress team</div>

			<h3 class="theme-name" id="pub/twentythirteen-name">Twenty Thirteen</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftwentythirteen&amp;_wpnonce=14939bcf5a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftwentythirteen">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/caldwell-action premium/caldwell-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/caldwell/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/caldwell-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/caldwell-name">Caldwell</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/caldwell&#038;ref=themesphp&#038;_wpnonce=64c9a48166">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcaldwell">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/ryu-action pub/ryu-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/ryu/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/ryu-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/ryu-name">Ryu</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fryu&amp;_wpnonce=3c7c533191">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fryu">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/mood-action premium/mood-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/mood/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/mood-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/mood-name">Mood</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/mood&#038;ref=themesphp&#038;_wpnonce=7b2262bdf9">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmood">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/twentyfifteen-action pub/twentyfifteen-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/twentyfifteen/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/twentyfifteen-action">Détails du thème</span>
	<div class="theme-author">Par the WordPress team</div>

			<h3 class="theme-name" id="pub/twentyfifteen-name">Twenty Fifteen</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftwentyfifteen&amp;_wpnonce=940cbc193b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftwentyfifteen">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/huntt-action premium/huntt-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/huntt/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/huntt-action">Détails du thème</span>
	<div class="theme-author">Par Themes Kingdom</div>

			<h3 class="theme-name" id="premium/huntt-name">Huntt</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/huntt&#038;ref=themesphp&#038;_wpnonce=fdd0c87985">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fhuntt">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/afterlight-action pub/afterlight-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/afterlight/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/afterlight-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/afterlight-name">Afterlight</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fafterlight&amp;_wpnonce=64553dde81">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fafterlight">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/patch-action premium/patch-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/patch/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/patch-action">Détails du thème</span>
	<div class="theme-author">Par PixelGrade</div>

			<h3 class="theme-name" id="premium/patch-name">Patch</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/patch&#038;ref=themesphp&#038;_wpnonce=263cfa62a6">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpatch">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/cols-action pub/cols-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/cols/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/cols-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/cols-name">Cols</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcols&amp;_wpnonce=ba71681adf">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcols">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/twentyeleven-action pub/twentyeleven-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/twentyeleven/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/twentyeleven-action">Détails du thème</span>
	<div class="theme-author">Par the WordPress team</div>

			<h3 class="theme-name" id="pub/twentyeleven-name">Twenty Eleven</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftwentyeleven&amp;_wpnonce=c15708276d">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftwentyeleven">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/minnow-action pub/minnow-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/minnow/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/minnow-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/minnow-name">Minnow</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fminnow&amp;_wpnonce=cd427c9b9b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fminnow">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/hermes-action premium/hermes-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/hermes/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/hermes-action">Détails du thème</span>
	<div class="theme-author">Par Tasko</div>

			<h3 class="theme-name" id="premium/hermes-name">Hermes</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/hermes&#038;ref=themesphp&#038;_wpnonce=0cb345acfb">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fhermes">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/eighties-action pub/eighties-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/eighties/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/eighties-action">Détails du thème</span>
	<div class="theme-author">Par Justin Kopepasah</div>

			<h3 class="theme-name" id="pub/eighties-name">Eighties</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Feighties&amp;_wpnonce=1b74483720">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Feighties">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/shrake-action premium/shrake-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/shrake/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/shrake-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/shrake-name">Shrake</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/shrake&#038;ref=themesphp&#038;_wpnonce=883860f564">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fshrake">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sequential-action pub/sequential-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/sequential/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sequential-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/sequential-name">Sequential</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsequential&amp;_wpnonce=e2f743004e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsequential">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/hyalite-action premium/hyalite-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/hyalite/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/hyalite-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/hyalite-name">Hyalite</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/hyalite&#038;ref=themesphp&#038;_wpnonce=5c3af39bf3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fhyalite">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/intergalactic-action pub/intergalactic-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/intergalactic/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/intergalactic-action">Détails du thème</span>
	<div class="theme-author">Par WordPress.com</div>

			<h3 class="theme-name" id="pub/intergalactic-name">Intergalactic</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fintergalactic&amp;_wpnonce=4620317839">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fintergalactic">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/cyanotype-action pub/cyanotype-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/cyanotype/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/cyanotype-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/cyanotype-name">Cyanotype</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcyanotype&amp;_wpnonce=a20818ec9f">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcyanotype">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/veeva-action premium/veeva-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/veeva/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/veeva-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/veeva-name">Veeva</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/veeva&#038;ref=themesphp&#038;_wpnonce=75e10fd5e1">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fveeva">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/dicot-action premium/dicot-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/dicot/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/dicot-action">Détails du thème</span>
	<div class="theme-author">Par DesignOrbital</div>

			<h3 class="theme-name" id="premium/dicot-name">Dicot</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/dicot&#038;ref=themesphp&#038;_wpnonce=c406d6d40c">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fdicot">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sela-action pub/sela-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/sela/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sela-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/sela-name">Sela</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsela&amp;_wpnonce=f5f68142b8">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsela">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/goran-action pub/goran-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/goran/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/goran-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/goran-name">Goran</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fgoran&amp;_wpnonce=de982b8f0a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fgoran">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/onigiri-action premium/onigiri-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/onigiri/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/onigiri-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="premium/onigiri-name">Onigiri</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/onigiri&#038;ref=themesphp&#038;_wpnonce=05d0de0389">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fonigiri">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/reddle-action pub/reddle-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/reddle/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/reddle-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/reddle-name">Reddle</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Freddle&amp;_wpnonce=b6f1b4e412">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Freddle">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/candela-action premium/candela-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/candela/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/candela-action">Détails du thème</span>
	<div class="theme-author">Par DesignOrbital</div>

			<h3 class="theme-name" id="premium/candela-name">Candela</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/candela&#038;ref=themesphp&#038;_wpnonce=c959818ab3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcandela">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/carmela-action premium/carmela-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/carmela/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/carmela-action">Détails du thème</span>
	<div class="theme-author">Par SiloCreativo</div>

			<h3 class="theme-name" id="premium/carmela-name">Carmela</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/carmela&#038;ref=themesphp&#038;_wpnonce=2961cab980">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcarmela">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/kelly-action pub/kelly-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/kelly/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/kelly-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/kelly-name">Kelly</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fkelly&amp;_wpnonce=a5280c6dad">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fkelly">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/fortune-action premium/fortune-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/fortune/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/fortune-action">Détails du thème</span>
	<div class="theme-author">Par Tasko</div>

			<h3 class="theme-name" id="premium/fortune-name">Fortune</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/fortune&#038;ref=themesphp&#038;_wpnonce=95ff2a6a59">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Ffortune">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/nucleare-action pub/nucleare-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/nucleare/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/nucleare-action">Détails du thème</span>
	<div class="theme-author">Par CrestaProject</div>

			<h3 class="theme-name" id="pub/nucleare-name">Nucleare</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fnucleare&amp;_wpnonce=5cb8a72178">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fnucleare">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/nowell-action premium/nowell-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/nowell/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/nowell-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/nowell-name">Nowell</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/nowell&#038;ref=themesphp&#038;_wpnonce=787db2a365">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fnowell">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/hemingway-rewritten-action pub/hemingway-rewritten-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/hemingway-rewritten/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/hemingway-rewritten-action">Détails du thème</span>
	<div class="theme-author">Par Anders Noren</div>

			<h3 class="theme-name" id="pub/hemingway-rewritten-name">Hemingway Rewritten</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fhemingway-rewritten&amp;_wpnonce=a727750692">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fhemingway-rewritten">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/bindery-action premium/bindery-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/bindery/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/bindery-action">Détails du thème</span>
	<div class="theme-author">Par Pixel Union</div>

			<h3 class="theme-name" id="premium/bindery-name">Bindery</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/bindery&#038;ref=themesphp&#038;_wpnonce=d6e7f87ceb">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbindery">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/gazette-action pub/gazette-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/gazette/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/gazette-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/gazette-name">Gazette</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fgazette&amp;_wpnonce=4f4903e525">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fgazette">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/hew-action pub/hew-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/hew/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/hew-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/hew-name">Hew</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fhew&amp;_wpnonce=7b28e3de5e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fhew">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/swell-action premium/swell-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/swell/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/swell-action">Détails du thème</span>
	<div class="theme-author">Par ThemeTrust.com</div>

			<h3 class="theme-name" id="premium/swell-name">Swell</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/swell&#038;ref=themesphp&#038;_wpnonce=c67f646085">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fswell">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/album-action premium/album-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/album/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/album-action">Détails du thème</span>
	<div class="theme-author">Par Press75</div>

			<h3 class="theme-name" id="premium/album-name">Album</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/album&#038;ref=themesphp&#038;_wpnonce=ab4aa06e00">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Falbum">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sobe-action pub/sobe-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/sobe/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sobe-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/sobe-name">Sobe</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsobe&amp;_wpnonce=36353269c2">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsobe">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/purpose-action premium/purpose-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/purpose/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/purpose-action">Détails du thème</span>
	<div class="theme-author">Par Organic Themes</div>

			<h3 class="theme-name" id="premium/purpose-name">Purpose</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/purpose&#038;ref=themesphp&#038;_wpnonce=b09b244086">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpurpose">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/illustratr-action pub/illustratr-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/illustratr/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/illustratr-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/illustratr-name">Illustratr</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fillustratr&amp;_wpnonce=66201a7f7b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fillustratr">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/together-action pub/together-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/together/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/together-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/together-name">Together</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftogether&amp;_wpnonce=c2e77b0f53">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftogether">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/tonal-action pub/tonal-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/tonal/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/tonal-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/tonal-name">Tonal</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftonal&amp;_wpnonce=9e3861eff2">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftonal">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/big-brother-action pub/big-brother-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/big-brother/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/big-brother-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/big-brother-name">Big Brother</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbig-brother&amp;_wpnonce=dd97942089">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbig-brother">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/beacon-action premium/beacon-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/beacon/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/beacon-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/beacon-name">Beacon</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/beacon&#038;ref=themesphp&#038;_wpnonce=f9bce6b12f">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbeacon">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/hexa-action pub/hexa-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/hexa/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/hexa-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/hexa-name">Hexa</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fhexa&amp;_wpnonce=0383190e22">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fhexa">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/mayer-action premium/mayer-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/mayer/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/mayer-action">Détails du thème</span>
	<div class="theme-author">Par Pressware</div>

			<h3 class="theme-name" id="premium/mayer-name">Mayer</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/mayer&#038;ref=themesphp&#038;_wpnonce=bfc66c34ea">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmayer">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/suidobashi-action premium/suidobashi-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/suidobashi/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/suidobashi-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="premium/suidobashi-name">Suidobashi</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/suidobashi&#038;ref=themesphp&#038;_wpnonce=2198b128da">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fsuidobashi">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/lyretail-action pub/lyretail-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/lyretail/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/lyretail-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/lyretail-name">Lyretail</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Flyretail&amp;_wpnonce=3d008d26d4">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Flyretail">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/satellite-action pub/satellite-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/satellite/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/satellite-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/satellite-name">Satellite</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsatellite&amp;_wpnonce=a5764e582e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsatellite">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/espied-action pub/espied-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/espied/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/espied-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/espied-name">Espied</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fespied&amp;_wpnonce=3ab10d475a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fespied">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/capoverso-action pub/capoverso-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/capoverso/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/capoverso-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/capoverso-name">Capoverso</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcapoverso&amp;_wpnonce=093ab0c29e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcapoverso">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/vagabond-action premium/vagabond-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/vagabond/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/vagabond-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/vagabond-name">Vagabond</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/vagabond&#038;ref=themesphp&#038;_wpnonce=0d7ef154fa">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fvagabond">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/wilson-action pub/wilson-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/wilson/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/wilson-action">Détails du thème</span>
	<div class="theme-author">Par Anders Noren</div>

			<h3 class="theme-name" id="pub/wilson-name">Wilson</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fwilson&amp;_wpnonce=780f0ac57f">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fwilson">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/saga-action pub/saga-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/saga/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/saga-action">Détails du thème</span>
	<div class="theme-author">Par Justin Tadlock</div>

			<h3 class="theme-name" id="pub/saga-name">Saga</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsaga&amp;_wpnonce=8e15178ae2">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsaga">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/largo-action premium/largo-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/largo/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/largo-action">Détails du thème</span>
	<div class="theme-author">Par UpThemes</div>

			<h3 class="theme-name" id="premium/largo-name">Largo</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/largo&#038;ref=themesphp&#038;_wpnonce=57448dc754">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Flargo">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/radcliffe-action pub/radcliffe-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/radcliffe/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/radcliffe-action">Détails du thème</span>
	<div class="theme-author">Par Anders Norén</div>

			<h3 class="theme-name" id="pub/radcliffe-name">Radcliffe</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fradcliffe&amp;_wpnonce=b45c4fde80">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fradcliffe">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/zuki-action premium/zuki-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/zuki/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/zuki-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="premium/zuki-name">Zuki</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/zuki&#038;ref=themesphp&#038;_wpnonce=65b5294b5a">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fzuki">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/resonar-action pub/resonar-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/resonar/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/resonar-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/resonar-name">Resonar</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fresonar&amp;_wpnonce=39d9486aee">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fresonar">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/worldview-action premium/worldview-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/worldview/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/worldview-action">Détails du thème</span>
	<div class="theme-author">Par UpThemes</div>

			<h3 class="theme-name" id="premium/worldview-name">Worldview</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/worldview&#038;ref=themesphp&#038;_wpnonce=6aa29dbd5f">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fworldview">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/lingonberry-action pub/lingonberry-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/lingonberry/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/lingonberry-action">Détails du thème</span>
	<div class="theme-author">Par Anders Noren</div>

			<h3 class="theme-name" id="pub/lingonberry-name">Lingonberry</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Flingonberry&amp;_wpnonce=646c9836b4">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Flingonberry">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/hive-action premium/hive-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/hive/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/hive-action">Détails du thème</span>
	<div class="theme-author">Par PixelGrade</div>

			<h3 class="theme-name" id="premium/hive-name">Hive</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/hive&#038;ref=themesphp&#038;_wpnonce=e3f9bf5cea">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fhive">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/museum-action pub/museum-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/museum/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/museum-action">Détails du thème</span>
	<div class="theme-author">Par Kelly Dwan &amp; Mel Choyce</div>

			<h3 class="theme-name" id="pub/museum-name">Museum</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmuseum&amp;_wpnonce=b46994874a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmuseum">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/mirror-action premium/mirror-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/mirror/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/mirror-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/mirror-name">Mirror</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/mirror&#038;ref=themesphp&#038;_wpnonce=9457ecd6a3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmirror">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/harmonic-action pub/harmonic-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/harmonic/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/harmonic-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/harmonic-name">Harmonic</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fharmonic&amp;_wpnonce=7c030e8cd7">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fharmonic">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/solar-action premium/solar-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/solar/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/solar-action">Détails du thème</span>
	<div class="theme-author">Par Themes Kingdom</div>

			<h3 class="theme-name" id="premium/solar-name">Solar</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/solar&#038;ref=themesphp&#038;_wpnonce=54cdea7446">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fsolar">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/scrawl-action pub/scrawl-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/scrawl/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/scrawl-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/scrawl-name">Scrawl</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fscrawl&amp;_wpnonce=b922856772">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fscrawl">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/broadsheet-action premium/broadsheet-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/broadsheet/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/broadsheet-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/broadsheet-name">Broadsheet</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/broadsheet&#038;ref=themesphp&#038;_wpnonce=aeca7bd18b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbroadsheet">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/spirit-action pub/spirit-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/spirit/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/spirit-action">Détails du thème</span>
	<div class="theme-author">Par Caroline Moore</div>

			<h3 class="theme-name" id="pub/spirit-name">Spirit</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fspirit&amp;_wpnonce=4e1e978a29">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fspirit">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/editor-action pub/editor-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/editor/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/editor-action">Détails du thème</span>
	<div class="theme-author">Par Array</div>

			<h3 class="theme-name" id="pub/editor-name">Editor</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Feditor&amp;_wpnonce=8db93f10d5">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Feditor">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/vision-action premium/vision-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/vision/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/vision-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/vision-name">Vision</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/vision&#038;ref=themesphp&#038;_wpnonce=d04fc01f4c">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fvision">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/mh-magazine-action premium/mh-magazine-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/mh-magazine/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/mh-magazine-action">Détails du thème</span>
	<div class="theme-author">Par MH Themes</div>

			<h3 class="theme-name" id="premium/mh-magazine-name">MH Magazine</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/mh-magazine&#038;ref=themesphp&#038;_wpnonce=75c3f41f14">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmh-magazine">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/nurture-action premium/nurture-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/nurture/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/nurture-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/nurture-name">Nurture</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/nurture&#038;ref=themesphp&#038;_wpnonce=9c3234f286">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fnurture">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/bosco-action pub/bosco-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/bosco/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/bosco-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/bosco-name">Bosco</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbosco&amp;_wpnonce=5c22c76252">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbosco">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/mystique-action pub/mystique-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/mystique/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/mystique-action">Détails du thème</span>
	<div class="theme-author">Par digitalnature</div>

			<h3 class="theme-name" id="pub/mystique-name">Mystique</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmystique&amp;_wpnonce=90ae0233c7">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmystique">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/ari-action pub/ari-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/ari/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/ari-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="pub/ari-name">Ari</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fari&amp;_wpnonce=e8dbcb8d29">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fari">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/dynamic-news-action premium/dynamic-news-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/dynamic-news/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/dynamic-news-action">Détails du thème</span>
	<div class="theme-author">Par ThemeZee</div>

			<h3 class="theme-name" id="premium/dynamic-news-name">Dynamic News</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/dynamic-news&#038;ref=themesphp&#038;_wpnonce=0125141d9d">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fdynamic-news">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/splendio-action pub/splendio-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/splendio/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/splendio-action">Détails du thème</span>
	<div class="theme-author">Par Design Disease</div>

			<h3 class="theme-name" id="pub/splendio-name">Splendio</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsplendio&amp;_wpnonce=dd9bd4445a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsplendio">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/plane-action pub/plane-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/plane/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/plane-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/plane-name">Plane</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fplane&amp;_wpnonce=18ccfbec21">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fplane">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/gridiculous-pro-action premium/gridiculous-pro-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/gridiculous-pro/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/gridiculous-pro-action">Détails du thème</span>
	<div class="theme-author">Par c.bavota</div>

			<h3 class="theme-name" id="premium/gridiculous-pro-name">Gridiculous Pro</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/gridiculous-pro&#038;ref=themesphp&#038;_wpnonce=a23ce9abe3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fgridiculous-pro">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/designfolio-action premium/designfolio-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/designfolio/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/designfolio-action">Détails du thème</span>
	<div class="theme-author">Par Press Coders</div>

			<h3 class="theme-name" id="premium/designfolio-name">Designfolio</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/designfolio&#038;ref=themesphp&#038;_wpnonce=98458cd40d">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fdesignfolio">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/ubud-action premium/ubud-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/ubud/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/ubud-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="premium/ubud-name">Ubud</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/ubud&#038;ref=themesphp&#038;_wpnonce=d42f1e399d">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fubud">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sidespied-action pub/sidespied-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/sidespied/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sidespied-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/sidespied-name">Sidespied</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsidespied&amp;_wpnonce=49a0196cc1">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsidespied">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/chronicle-action premium/chronicle-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/chronicle/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/chronicle-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/chronicle-name">Chronicle</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/chronicle&#038;ref=themesphp&#038;_wpnonce=04f559c192">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fchronicle">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/pocket-action premium/pocket-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/pocket/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/pocket-action">Détails du thème</span>
	<div class="theme-author">Par Array</div>

			<h3 class="theme-name" id="premium/pocket-name">Pocket</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/pocket&#038;ref=themesphp&#038;_wpnonce=2d74d167d3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpocket">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/choco-action pub/choco-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/choco/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/choco-action">Détails du thème</span>
	<div class="theme-author">Par CSSMayo</div>

			<h3 class="theme-name" id="pub/choco-name">Choco</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fchoco&amp;_wpnonce=38d5ce77b5">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fchoco">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/circa-action pub/circa-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/circa/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/circa-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/circa-name">Circa</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcirca&amp;_wpnonce=0703cbabd6">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcirca">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/oxygen-action pub/oxygen-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/oxygen/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/oxygen-action">Détails du thème</span>
	<div class="theme-author">Par AlienWP</div>

			<h3 class="theme-name" id="pub/oxygen-name">Oxygen</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Foxygen&amp;_wpnonce=829948ae36">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Foxygen">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/retro-mac-os-action pub/retro-mac-os-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/retro-mac-os/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/retro-mac-os-action">Détails du thème</span>
	<div class="theme-author">Par Stuart Brown</div>

			<h3 class="theme-name" id="pub/retro-mac-os-name">Retro MacOS</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fretro-mac-os&amp;_wpnonce=6e3eb68638">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fretro-mac-os">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/profile-action premium/profile-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/profile/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/profile-action">Détails du thème</span>
	<div class="theme-author">Par Organic Themes</div>

			<h3 class="theme-name" id="premium/profile-name">Profil</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/profile&#038;ref=themesphp&#038;_wpnonce=6390884c6b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fprofile">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/cocoa-action premium/cocoa-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/cocoa/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/cocoa-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="premium/cocoa-name">Cocoa</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/cocoa&#038;ref=themesphp&#038;_wpnonce=2550ca6ad3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcocoa">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/forever-action pub/forever-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/forever/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/forever-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/forever-name">Forever</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fforever&amp;_wpnonce=c6945b587c">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fforever">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/organization-action premium/organization-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/organization/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/organization-action">Détails du thème</span>
	<div class="theme-author">Par Organic Themes</div>

			<h3 class="theme-name" id="premium/organization-name">Organisation</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/organization&#038;ref=themesphp&#038;_wpnonce=f999203610">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Forganization">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/finder-action premium/finder-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/finder/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/finder-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/finder-name">Finder</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/finder&#038;ref=themesphp&#038;_wpnonce=8f54bbe554">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Ffinder">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/quadra-action pub/quadra-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/quadra/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/quadra-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/quadra-name">Quadra</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fquadra&amp;_wpnonce=434c5c9339">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fquadra">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/shine-on-action pub/shine-on-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/shine-on/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/shine-on-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/shine-on-name">Shine On</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fshine-on&amp;_wpnonce=032c7be853">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fshine-on">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/collections-action premium/collections-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/collections/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/collections-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/collections-name">Collections</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/collections&#038;ref=themesphp&#038;_wpnonce=57bdec50c9">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcollections">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/fictive-action pub/fictive-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/fictive/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/fictive-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/fictive-name">Fictive</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ffictive&amp;_wpnonce=e15ab8359d">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ffictive">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/puzzle-action premium/puzzle-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/puzzle/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/puzzle-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/puzzle-name">Puzzle</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/puzzle&#038;ref=themesphp&#038;_wpnonce=a196329659">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpuzzle">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/linen-action premium/linen-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/linen/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/linen-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/linen-name">Linen</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/linen&#038;ref=themesphp&#038;_wpnonce=e0d4a2988e">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Flinen">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/sixteen-nine-action premium/sixteen-nine-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/sixteen-nine/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/sixteen-nine-action">Détails du thème</span>
	<div class="theme-author">Par StudioPress</div>

			<h3 class="theme-name" id="premium/sixteen-nine-name">Sixteen Nine</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/sixteen-nine&#038;ref=themesphp&#038;_wpnonce=fedc986395">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fsixteen-nine">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/nexus-action premium/nexus-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/nexus/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/nexus-action">Détails du thème</span>
	<div class="theme-author">Par Elegant Themes</div>

			<h3 class="theme-name" id="premium/nexus-name">Nexus</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/nexus&#038;ref=themesphp&#038;_wpnonce=671142a36b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fnexus">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/babylog-action pub/babylog-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/babylog/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/babylog-action">Détails du thème</span>
	<div class="theme-author">Par Caroline Moore</div>

			<h3 class="theme-name" id="pub/babylog-name">Babylog</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbabylog&amp;_wpnonce=2ed43159de">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbabylog">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/adventure-action premium/adventure-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/adventure/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/adventure-action">Détails du thème</span>
	<div class="theme-author">Par Organic Themes</div>

			<h3 class="theme-name" id="premium/adventure-name">Adventure</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/adventure&#038;ref=themesphp&#038;_wpnonce=18c6c83284">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fadventure">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/infoway-action premium/infoway-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/infoway/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/infoway-action">Détails du thème</span>
	<div class="theme-author">Par InkThemes</div>

			<h3 class="theme-name" id="premium/infoway-name">InfoWay</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/infoway&#038;ref=themesphp&#038;_wpnonce=59a436de35">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Finfoway">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/next-saturday-action pub/next-saturday-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/next-saturday/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/next-saturday-action">Détails du thème</span>
	<div class="theme-author">Par Ian Mintz</div>

			<h3 class="theme-name" id="pub/next-saturday-name">Next Saturday</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fnext-saturday&amp;_wpnonce=17eb3eb235">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fnext-saturday">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/panel-action pub/panel-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/panel/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/panel-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/panel-name">Panel</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fpanel&amp;_wpnonce=595934a838">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fpanel">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/celsius-action pub/celsius-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/celsius/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/celsius-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/celsius-name">Celsius</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcelsius&amp;_wpnonce=9e32d8b526">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcelsius">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/adelle-action pub/adelle-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/adelle/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/adelle-action">Détails du thème</span>
	<div class="theme-author">Par BluChic</div>

			<h3 class="theme-name" id="pub/adelle-name">Adelle</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fadelle&amp;_wpnonce=276f62469a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fadelle">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/timepiece-action pub/timepiece-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/timepiece/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/timepiece-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/timepiece-name">Timepiece</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftimepiece&amp;_wpnonce=7ce642c069">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftimepiece">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/matala-action pub/matala-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/matala/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/matala-action">Détails du thème</span>
	<div class="theme-author">Par Matt Mullenweg</div>

			<h3 class="theme-name" id="pub/matala-name">Matala</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmatala&amp;_wpnonce=e93af0df75">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmatala">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/port-action premium/port-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/port/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/port-action">Détails du thème</span>
	<div class="theme-author">Par ThemeTrust</div>

			<h3 class="theme-name" id="premium/port-name">Port</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/port&#038;ref=themesphp&#038;_wpnonce=a5f95398a4">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fport">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/oslo-action premium/oslo-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/oslo/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/oslo-action">Détails du thème</span>
	<div class="theme-author">Par Pixel Union</div>

			<h3 class="theme-name" id="premium/oslo-name">Oslo</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/oslo&#038;ref=themesphp&#038;_wpnonce=497fdf9579">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Foslo">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/outspoken-action premium/outspoken-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/outspoken/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/outspoken-action">Détails du thème</span>
	<div class="theme-author">Par WPShower</div>

			<h3 class="theme-name" id="premium/outspoken-name">Outspoken</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/outspoken&#038;ref=themesphp&#038;_wpnonce=d03fc9ec8d">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Foutspoken">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/adaption-action pub/adaption-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/adaption/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/adaption-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/adaption-name">Adaption</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fadaption&amp;_wpnonce=9588f14a02">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fadaption">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="vip/partner-mlb-modern-action vip/partner-mlb-modern-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/vip/partner-mlb-modern/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="vip/partner-mlb-modern-action">Détails du thème</span>
	<div class="theme-author">Par MLB</div>

			<h3 class="theme-name" id="vip/partner-mlb-modern-name">MLB "Modern"</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=vip%2Fpartner-mlb-modern&amp;_wpnonce=8cbf4a7079">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=vip%2Fpartner-mlb-modern">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/little-story-action premium/little-story-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/little-story/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/little-story-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/little-story-name">Little Story</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/little-story&#038;ref=themesphp&#038;_wpnonce=41df301cfc">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Flittle-story">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/monster-action pub/monster-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/monster/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/monster-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/monster-name">Monster</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmonster&amp;_wpnonce=cb4aeb80c4">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmonster">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/expound-action pub/expound-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/expound/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/expound-action">Détails du thème</span>
	<div class="theme-author">Par Konstantin Kovshenin</div>

			<h3 class="theme-name" id="pub/expound-name">Expound</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fexpound&amp;_wpnonce=80e1bf62f1">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fexpound">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/photographer-action premium/photographer-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/photographer/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/photographer-action">Détails du thème</span>
	<div class="theme-author">Par Organic Themes</div>

			<h3 class="theme-name" id="premium/photographer-name">Photographer</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/photographer&#038;ref=themesphp&#038;_wpnonce=c7173211b6">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fphotographer">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/bouquet-action pub/bouquet-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/bouquet/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/bouquet-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/bouquet-name">Bouquet</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbouquet&amp;_wpnonce=502387be1b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbouquet">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/manifest-action pub/manifest-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/manifest/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/manifest-action">Détails du thème</span>
	<div class="theme-author">Par Jim Barraud</div>

			<h3 class="theme-name" id="pub/manifest-name">Manifest</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmanifest&amp;_wpnonce=411882a8d3">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmanifest">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/traveler-action premium/traveler-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/traveler/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/traveler-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/traveler-name">Traveler</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/traveler&#038;ref=themesphp&#038;_wpnonce=5380f87dc7">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Ftraveler">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/photolia-action premium/photolia-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/photolia/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/photolia-action">Détails du thème</span>
	<div class="theme-author">Par UpThemes</div>

			<h3 class="theme-name" id="premium/photolia-name">Photolia</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/photolia&#038;ref=themesphp&#038;_wpnonce=b08d39b8cd">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fphotolia">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/piano-black-action pub/piano-black-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/piano-black/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/piano-black-action">Détails du thème</span>
	<div class="theme-author">Par mono-lab</div>

			<h3 class="theme-name" id="pub/piano-black-name">Piano Black</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fpiano-black&amp;_wpnonce=d0aa1a76c2">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fpiano-black">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/isola-action pub/isola-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/isola/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/isola-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/isola-name">Isola</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fisola&amp;_wpnonce=9277a0824b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fisola">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/spun-action pub/spun-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/spun/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/spun-action">Détails du thème</span>
	<div class="theme-author">Par Caroline Moore</div>

			<h3 class="theme-name" id="pub/spun-name">Spun</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fspun&amp;_wpnonce=3b72c1645f">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fspun">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/opti-action premium/opti-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/opti/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/opti-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/opti-name">Opti</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/opti&#038;ref=themesphp&#038;_wpnonce=026a0aaff2">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fopti">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/motif-action pub/motif-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/motif/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/motif-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/motif-name">Motif</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmotif&amp;_wpnonce=0d5b5a3dd6">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmotif">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/lovebirds-action pub/lovebirds-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/lovebirds/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/lovebirds-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/lovebirds-name">Lovebirds</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Flovebirds&amp;_wpnonce=3528b1b45b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Flovebirds">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/pictorico-action pub/pictorico-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/pictorico/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/pictorico-action">Détails du thème</span>
	<div class="theme-author">Par WordPress.com</div>

			<h3 class="theme-name" id="pub/pictorico-name">Pictorico</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fpictorico&amp;_wpnonce=341278140e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fpictorico">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/dusk-to-dawn-action pub/dusk-to-dawn-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/dusk-to-dawn/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/dusk-to-dawn-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/dusk-to-dawn-name">Dusk To Dawn</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fdusk-to-dawn&amp;_wpnonce=41c21d5026">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fdusk-to-dawn">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/gridspace-action premium/gridspace-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/gridspace/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/gridspace-action">Détails du thème</span>
	<div class="theme-author">Par Graph Paper Press</div>

			<h3 class="theme-name" id="premium/gridspace-name">Gridspace</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/gridspace&#038;ref=themesphp&#038;_wpnonce=67e67a6092">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fgridspace">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/lens-action premium/lens-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/lens/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/lens-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/lens-name">Lens</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/lens&#038;ref=themesphp&#038;_wpnonce=16ce4bffed">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Flens">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/chunk-action pub/chunk-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/chunk/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/chunk-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/chunk-name">Chunk</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fchunk&amp;_wpnonce=10cec581ad">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fchunk">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/adventure-journal-action pub/adventure-journal-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/adventure-journal/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/adventure-journal-action">Détails du thème</span>
	<div class="theme-author">Par Contexture International</div>

			<h3 class="theme-name" id="pub/adventure-journal-name">Adventure Journal</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fadventure-journal&amp;_wpnonce=22c11a2382">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fadventure-journal">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/silesia-action pub/silesia-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/silesia/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/silesia-action">Détails du thème</span>
	<div class="theme-author">Par NattyWP</div>

			<h3 class="theme-name" id="pub/silesia-name">Silesia</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsilesia&amp;_wpnonce=dd42c2e9ad">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsilesia">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/publisher-action premium/publisher-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/publisher/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/publisher-action">Détails du thème</span>
	<div class="theme-author">Par Array</div>

			<h3 class="theme-name" id="premium/publisher-name">Publisher</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/publisher&#038;ref=themesphp&#038;_wpnonce=b131e2e523">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpublisher">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/pachyderm-action pub/pachyderm-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/pachyderm/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/pachyderm-action">Détails du thème</span>
	<div class="theme-author">Par Caroline Moore</div>

			<h3 class="theme-name" id="pub/pachyderm-name">Pachyderm</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fpachyderm&amp;_wpnonce=3fefd1469c">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fpachyderm">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/handmade-action premium/handmade-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/handmade/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/handmade-action">Détails du thème</span>
	<div class="theme-author">Par Obox Themes</div>

			<h3 class="theme-name" id="premium/handmade-name">Handmade</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/handmade&#038;ref=themesphp&#038;_wpnonce=63e4b949b4">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fhandmade">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/suits-action pub/suits-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/suits/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/suits-action">Détails du thème</span>
	<div class="theme-author">Par Theme Weaver</div>

			<h3 class="theme-name" id="pub/suits-name">Suits</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsuits&amp;_wpnonce=67aa8197d6">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsuits">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/something-fishy-action pub/something-fishy-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/something-fishy/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/something-fishy-action">Détails du thème</span>
	<div class="theme-author">Par Caroline Moore</div>

			<h3 class="theme-name" id="pub/something-fishy-name">Something Fishy</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsomething-fishy&amp;_wpnonce=0624d285a8">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsomething-fishy">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/chalkboard-action pub/chalkboard-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/chalkboard/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/chalkboard-action">Détails du thème</span>
	<div class="theme-author">Par Edward R. Jenkins</div>

			<h3 class="theme-name" id="pub/chalkboard-name">Chalkboard</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fchalkboard&amp;_wpnonce=3196aef9a2">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fchalkboard">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/san-kloud-action pub/san-kloud-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/san-kloud/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/san-kloud-action">Détails du thème</span>
	<div class="theme-author">Par Theme.fm</div>

			<h3 class="theme-name" id="pub/san-kloud-name">San Kloud</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsan-kloud&amp;_wpnonce=e112a382bc">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsan-kloud">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/pretty-young-thing-action premium/pretty-young-thing-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/pretty-young-thing/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/pretty-young-thing-action">Détails du thème</span>
	<div class="theme-author">Par StudioPress</div>

			<h3 class="theme-name" id="premium/pretty-young-thing-name">Pretty Young Thing</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/pretty-young-thing&#038;ref=themesphp&#038;_wpnonce=c8ccbad687">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpretty-young-thing">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/ascetica-action pub/ascetica-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/ascetica/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/ascetica-action">Détails du thème</span>
	<div class="theme-author">Par AlienWP</div>

			<h3 class="theme-name" id="pub/ascetica-name">Ascetica</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fascetica&amp;_wpnonce=0701409978">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fascetica">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/themorningafter-action pub/themorningafter-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/themorningafter/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/themorningafter-action">Détails du thème</span>
	<div class="theme-author">Par WooThemes</div>

			<h3 class="theme-name" id="pub/themorningafter-name">The Morning After</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fthemorningafter&amp;_wpnonce=d257d5a9f7">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fthemorningafter">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/highwind-action pub/highwind-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/highwind/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/highwind-action">Détails du thème</span>
	<div class="theme-author">Par James Koster</div>

			<h3 class="theme-name" id="pub/highwind-name">Highwind</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fhighwind&amp;_wpnonce=d1e4144698">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fhighwind">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/cheer-action pub/cheer-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/cheer/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/cheer-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/cheer-name">Cheer</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcheer&amp;_wpnonce=5362fd6c65">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcheer">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/triton-lite-action pub/triton-lite-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/triton-lite/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/triton-lite-action">Détails du thème</span>
	<div class="theme-author">Par Towfiq I.</div>

			<h3 class="theme-name" id="pub/triton-lite-name">Triton Lite</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftriton-lite&amp;_wpnonce=cc2b14baf0">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftriton-lite">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/misty-lake-action pub/misty-lake-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/misty-lake/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/misty-lake-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/misty-lake-name">Misty Lake</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmisty-lake&amp;_wpnonce=144a1da136">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmisty-lake">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/soundcheck-action premium/soundcheck-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/soundcheck/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/soundcheck-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/soundcheck-name">Soundcheck</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/soundcheck&#038;ref=themesphp&#038;_wpnonce=36d12117b6">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fsoundcheck">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/fiore-action pub/fiore-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/fiore/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/fiore-action">Détails du thème</span>
	<div class="theme-author">Par Caroline Moore</div>

			<h3 class="theme-name" id="pub/fiore-name">Fiore</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ffiore&amp;_wpnonce=4fe0d6df7a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ffiore">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/sweet-life-action premium/sweet-life-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/sweet-life/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/sweet-life-action">Détails du thème</span>
	<div class="theme-author">Par Anariel Design</div>

			<h3 class="theme-name" id="premium/sweet-life-name">Sweet Life</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/sweet-life&#038;ref=themesphp&#038;_wpnonce=99c3a8ea97">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fsweet-life">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/retro-fitted-action pub/retro-fitted-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/retro-fitted/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/retro-fitted-action">Détails du thème</span>
	<div class="theme-author">Par Justin Tadlock</div>

			<h3 class="theme-name" id="pub/retro-fitted-name">Retro-fitted</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fretro-fitted&amp;_wpnonce=6c8b0dcae9">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fretro-fitted">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/strange-little-town-action pub/strange-little-town-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/strange-little-town/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/strange-little-town-action">Détails du thème</span>
	<div class="theme-author">Par Minmin</div>

			<h3 class="theme-name" id="pub/strange-little-town-name">Strange Little Town</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fstrange-little-town&amp;_wpnonce=4765c8a620">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fstrange-little-town">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/gigawatt-action premium/gigawatt-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/gigawatt/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/gigawatt-action">Détails du thème</span>
	<div class="theme-author">Par Obox Themes</div>

			<h3 class="theme-name" id="premium/gigawatt-name">Gigawatt</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/gigawatt&#038;ref=themesphp&#038;_wpnonce=9eb7d35c73">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fgigawatt">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/vertigo-action pub/vertigo-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/vertigo/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/vertigo-action">Détails du thème</span>
	<div class="theme-author">Par Matthew Buchanan</div>

			<h3 class="theme-name" id="pub/vertigo-name">Vertigo</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fvertigo&amp;_wpnonce=efc1380d80">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fvertigo">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/book-lite-action pub/book-lite-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/book-lite/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/book-lite-action">Détails du thème</span>
	<div class="theme-author">Par Chandra Maharzan</div>

			<h3 class="theme-name" id="pub/book-lite-name">Book Lite</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbook-lite&amp;_wpnonce=bbea3ce561">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbook-lite">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/academica-action pub/academica-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/academica/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/academica-action">Détails du thème</span>
	<div class="theme-author">Par WPZOOM</div>

			<h3 class="theme-name" id="pub/academica-name">Academica</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Facademica&amp;_wpnonce=9a5124f917">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Facademica">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/crafty-action pub/crafty-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/crafty/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/crafty-action">Détails du thème</span>
	<div class="theme-author">Par CraftyCart</div>

			<h3 class="theme-name" id="pub/crafty-name">Crafty</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcrafty&amp;_wpnonce=31f731d578">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcrafty">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sunspot-action pub/sunspot-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/sunspot/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sunspot-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/sunspot-name">Sunspot</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsunspot&amp;_wpnonce=98db4c8e25">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsunspot">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/nuntius-action pub/nuntius-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/nuntius/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/nuntius-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/nuntius-name">Nuntius</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fnuntius&amp;_wpnonce=85a090910b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fnuntius">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/duet-action premium/duet-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/duet/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/duet-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/duet-name">Duet</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/duet&#038;ref=themesphp&#038;_wpnonce=c9c3fb3696">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fduet">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/avid-action premium/avid-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/avid/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/avid-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/avid-name">Avid</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/avid&#038;ref=themesphp&#038;_wpnonce=54358e742d">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Favid">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/shaan-action pub/shaan-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/shaan/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/shaan-action">Détails du thème</span>
	<div class="theme-author">Par Specky Geek</div>

			<h3 class="theme-name" id="pub/shaan-name">Shaan</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fshaan&amp;_wpnonce=f68c60dc9b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fshaan">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/parament-action pub/parament-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/parament/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/parament-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/parament-name">Parament</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fparament&amp;_wpnonce=806e52b654">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fparament">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/responsive-action pub/responsive-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/responsive/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/responsive-action">Détails du thème</span>
	<div class="theme-author">Par CyberChimps</div>

			<h3 class="theme-name" id="pub/responsive-name">Sensible</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fresponsive&amp;_wpnonce=c6841e7141">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fresponsive">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/fanwood-light-action pub/fanwood-light-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/fanwood-light/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/fanwood-light-action">Détails du thème</span>
	<div class="theme-author">Par DevPress</div>

			<h3 class="theme-name" id="pub/fanwood-light-name">Fanwood Light</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ffanwood-light&amp;_wpnonce=d59e42fc93">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ffanwood-light">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/studio-action premium/studio-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/studio/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/studio-action">Détails du thème</span>
	<div class="theme-author">Par Pixel Union</div>

			<h3 class="theme-name" id="premium/studio-name">Studio</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/studio&#038;ref=themesphp&#038;_wpnonce=ca86a69874">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fstudio">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/mixfolio-action pub/mixfolio-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/mixfolio/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/mixfolio-action">Détails du thème</span>
	<div class="theme-author">Par Graph Paper Press</div>

			<h3 class="theme-name" id="pub/mixfolio-name">Mixfolio</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmixfolio&amp;_wpnonce=b8261b9c81">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmixfolio">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/connect-action premium/connect-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/connect/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/connect-action">Détails du thème</span>
	<div class="theme-author">Par Organic Themes</div>

			<h3 class="theme-name" id="premium/connect-name">Se connecter</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/connect&#038;ref=themesphp&#038;_wpnonce=37a7ff5126">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fconnect">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/yoko-action pub/yoko-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/yoko/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/yoko-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="pub/yoko-name">Yoko</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fyoko&amp;_wpnonce=86a13934e7">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fyoko">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/skeptical-action pub/skeptical-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/skeptical/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/skeptical-action">Détails du thème</span>
	<div class="theme-author">Par WooThemes</div>

			<h3 class="theme-name" id="pub/skeptical-name">Skeptical</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fskeptical&amp;_wpnonce=5b87af0200">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fskeptical">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/moka-action premium/moka-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/moka/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/moka-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="premium/moka-name">Moka</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/moka&#038;ref=themesphp&#038;_wpnonce=199912bb92">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmoka">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/stay-action pub/stay-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/stay/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/stay-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/stay-name">Stay</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fstay&amp;_wpnonce=8737beabcd">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fstay">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/suburbia-action pub/suburbia-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/suburbia/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/suburbia-action">Détails du thème</span>
	<div class="theme-author">Par WPShower</div>

			<h3 class="theme-name" id="pub/suburbia-name">Suburbia</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsuburbia&amp;_wpnonce=61a0717f7e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsuburbia">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/hustle-express-action premium/hustle-express-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/hustle-express/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/hustle-express-action">Détails du thème</span>
	<div class="theme-author">Par WooThemes</div>

			<h3 class="theme-name" id="premium/hustle-express-name">Hustle Express</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/hustle-express&#038;ref=themesphp&#038;_wpnonce=ee529a6ae3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fhustle-express">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/typo-action pub/typo-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/typo/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/typo-action">Détails du thème</span>
	<div class="theme-author">Par Okay Themes</div>

			<h3 class="theme-name" id="pub/typo-name">Typo</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftypo&amp;_wpnonce=6f1333ece2">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftypo">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/runo-lite-action pub/runo-lite-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/runo-lite/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/runo-lite-action">Détails du thème</span>
	<div class="theme-author">Par La&amp;La</div>

			<h3 class="theme-name" id="pub/runo-lite-name">Runo Lite</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fruno-lite&amp;_wpnonce=4afa8a86fd">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fruno-lite">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/selecta-action pub/selecta-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/selecta/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/selecta-action">Détails du thème</span>
	<div class="theme-author">Par Obox Design</div>

			<h3 class="theme-name" id="pub/selecta-name">Selecta</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fselecta&amp;_wpnonce=156ecf340b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fselecta">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/elemin-action premium/elemin-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/elemin/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/elemin-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/elemin-name">Elemin</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/elemin&#038;ref=themesphp&#038;_wpnonce=061c905540">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Felemin">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/beach-action pub/beach-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/beach/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/beach-action">Détails du thème</span>
	<div class="theme-author">Par Gibbo and Automattic</div>

			<h3 class="theme-name" id="pub/beach-name">Beach</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbeach&amp;_wpnonce=523aba6d87">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbeach">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/ever-after-action pub/ever-after-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/ever-after/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/ever-after-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/ever-after-name">Ever After</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fever-after&amp;_wpnonce=d336001438">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fever-after">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sight-action pub/sight-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/sight/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sight-action">Détails du thème</span>
	<div class="theme-author">Par WPShower</div>

			<h3 class="theme-name" id="pub/sight-name">Sight</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsight&amp;_wpnonce=648d05f618">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsight">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/modern-news-action premium/modern-news-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/modern-news/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/modern-news-action">Détails du thème</span>
	<div class="theme-author">Par StudioPress</div>

			<h3 class="theme-name" id="premium/modern-news-name">Modern News</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/modern-news&#038;ref=themesphp&#038;_wpnonce=c6e3a680da">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmodern-news">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/blissful-blog-action pub/blissful-blog-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/blissful-blog/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/blissful-blog-action">Détails du thème</span>
	<div class="theme-author">Par Organic Themes</div>

			<h3 class="theme-name" id="pub/blissful-blog-name">Blissful Blog</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fblissful-blog&amp;_wpnonce=a565fd6c13">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fblissful-blog">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/tuned-balloon-action premium/tuned-balloon-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/tuned-balloon/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/tuned-balloon-action">Détails du thème</span>
	<div class="theme-author">Par Anariel Design</div>

			<h3 class="theme-name" id="premium/tuned-balloon-name">Tuned Balloon</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/tuned-balloon&#038;ref=themesphp&#038;_wpnonce=b3c2e72829">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Ftuned-balloon">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sidekick-action pub/sidekick-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/sidekick/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sidekick-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/sidekick-name">Sidekick</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsidekick&amp;_wpnonce=613b195a05">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsidekick">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/esquire-action pub/esquire-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/esquire/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/esquire-action">Détails du thème</span>
	<div class="theme-author">Par Matthew Buchanan</div>

			<h3 class="theme-name" id="pub/esquire-name">Esquire</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fesquire&amp;_wpnonce=66aad1f2b2">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fesquire">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/singl-action pub/singl-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/singl/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/singl-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/singl-name">Singl</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsingl&amp;_wpnonce=cde9fcec8d">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsingl">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/blaskan-action pub/blaskan-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/blaskan/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/blaskan-action">Détails du thème</span>
	<div class="theme-author">Par Per Sandstrom</div>

			<h3 class="theme-name" id="pub/blaskan-name">Blaskan</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fblaskan&amp;_wpnonce=d386192bad">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fblaskan">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/publish-action pub/publish-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/publish/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/publish-action">Détails du thème</span>
	<div class="theme-author">Par Konstantin Kovshenin</div>

			<h3 class="theme-name" id="pub/publish-name">Publier</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fpublish&amp;_wpnonce=689373c212">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fpublish">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/liquorice-action pub/liquorice-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/liquorice/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/liquorice-action">Détails du thème</span>
	<div class="theme-author">Par Nudge Design</div>

			<h3 class="theme-name" id="pub/liquorice-name">Liquorice</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fliquorice&amp;_wpnonce=1ca80250ed">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fliquorice">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/lifestyle-action premium/lifestyle-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/lifestyle/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/lifestyle-action">Détails du thème</span>
	<div class="theme-author">Par StudioPress</div>

			<h3 class="theme-name" id="premium/lifestyle-name">Lifestyle</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/lifestyle&#038;ref=themesphp&#038;_wpnonce=0ca9b97433">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Flifestyle">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/widely-action pub/widely-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/widely/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/widely-action">Détails du thème</span>
	<div class="theme-author">Par Themes Kingdom</div>

			<h3 class="theme-name" id="pub/widely-name">Widely</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fwidely&amp;_wpnonce=94ec6d4a7e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fwidely">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/quintus-action pub/quintus-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/quintus/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/quintus-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/quintus-name">Quintus</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fquintus&amp;_wpnonce=f4d00bbb78">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fquintus">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/portfolio-action premium/portfolio-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/portfolio/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/portfolio-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/portfolio-name">Portfolio</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/portfolio&#038;ref=themesphp&#038;_wpnonce=06b8da25a7">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fportfolio">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/the-columnist-action pub/the-columnist-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/the-columnist/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/the-columnist-action">Détails du thème</span>
	<div class="theme-author">Par Ben Martineau</div>

			<h3 class="theme-name" id="pub/the-columnist-name">The Columnist</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fthe-columnist&amp;_wpnonce=a59d668a1d">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fthe-columnist">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/arcade-action premium/arcade-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/arcade/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/arcade-action">Détails du thème</span>
	<div class="theme-author">Par c.bavota</div>

			<h3 class="theme-name" id="premium/arcade-name">Arcade</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/arcade&#038;ref=themesphp&#038;_wpnonce=8ef6f1a05c">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Farcade">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/eventbrite-event-action pub/eventbrite-event-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/eventbrite-event/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/eventbrite-event-action">Détails du thème</span>
	<div class="theme-author">Par Voce Platforms</div>

			<h3 class="theme-name" id="pub/eventbrite-event-name">Eventbrite Single Event</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Feventbrite-event&amp;_wpnonce=26aa8eadce">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Feventbrite-event">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/imbalance2-action pub/imbalance2-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/imbalance2/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/imbalance2-action">Détails du thème</span>
	<div class="theme-author">Par WPShower</div>

			<h3 class="theme-name" id="pub/imbalance2-name">Imbalance 2</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fimbalance2&amp;_wpnonce=c4ca0c23d6">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fimbalance2">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/writr-action pub/writr-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/writr/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/writr-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/writr-name">Writr</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fwritr&amp;_wpnonce=b69fd46dfb">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fwritr">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sorbet-action pub/sorbet-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/sorbet/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sorbet-action">Détails du thème</span>
	<div class="theme-author">Par WordPress.com</div>

			<h3 class="theme-name" id="pub/sorbet-name">Sorbet</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsorbet&amp;_wpnonce=0c726d7610">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsorbet">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/newsworthy-action pub/newsworthy-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/newsworthy/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/newsworthy-action">Détails du thème</span>
	<div class="theme-author">Par WPThemes NZ</div>

			<h3 class="theme-name" id="pub/newsworthy-name">Newsworthy</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fnewsworthy&amp;_wpnonce=a4b3c75203">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fnewsworthy">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/skylark-action pub/skylark-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/skylark/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/skylark-action">Détails du thème</span>
	<div class="theme-author">Par Blank Themes</div>

			<h3 class="theme-name" id="pub/skylark-name">Skylark</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fskylark&amp;_wpnonce=7dca7fc489">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fskylark">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/bonpress-action pub/bonpress-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/bonpress/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/bonpress-action">Détails du thème</span>
	<div class="theme-author">Par WPZOOM</div>

			<h3 class="theme-name" id="pub/bonpress-name">BonPress</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbonpress&amp;_wpnonce=844e376e12">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbonpress">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/ideation-and-intent-action pub/ideation-and-intent-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/ideation-and-intent/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/ideation-and-intent-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/ideation-and-intent-name">Ideation and Intent</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fideation-and-intent&amp;_wpnonce=c19c1af094">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fideation-and-intent">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/nishita-action pub/nishita-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/nishita/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/nishita-action">Détails du thème</span>
	<div class="theme-author">Par Brajeshwar</div>

			<h3 class="theme-name" id="pub/nishita-name">Nishita</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fnishita&amp;_wpnonce=9fcfc02df9">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fnishita">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/minimalizine-action pub/minimalizine-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/minimalizine/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/minimalizine-action">Détails du thème</span>
	<div class="theme-author">Par Rizqy Hidayat</div>

			<h3 class="theme-name" id="pub/minimalizine-name">Minimalizine</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fminimalizine&amp;_wpnonce=983f0b51cb">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fminimalizine">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/grisaille-action pub/grisaille-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/grisaille/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/grisaille-action">Détails du thème</span>
	<div class="theme-author">Par Nudge design</div>

			<h3 class="theme-name" id="pub/grisaille-name">Grisaille</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fgrisaille&amp;_wpnonce=c888f511a8">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fgrisaille">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/balloons-action pub/balloons-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/balloons/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/balloons-action">Détails du thème</span>
	<div class="theme-author">Par Moargh.de</div>

			<h3 class="theme-name" id="pub/balloons-name">Balloons</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fballoons&amp;_wpnonce=4f50c19fc6">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fballoons">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/my-life-action pub/my-life-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/my-life/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/my-life-action">Détails du thème</span>
	<div class="theme-author">Par Justin Tadlock</div>

			<h3 class="theme-name" id="pub/my-life-name">My Life</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmy-life&amp;_wpnonce=2d769acecc">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmy-life">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/hero-action pub/hero-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/hero/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/hero-action">Détails du thème</span>
	<div class="theme-author">Par Manishg</div>

			<h3 class="theme-name" id="pub/hero-name">Hero</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fhero&amp;_wpnonce=33c9e72df2">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fhero">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/flounder-action pub/flounder-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/flounder/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/flounder-action">Détails du thème</span>
	<div class="theme-author">Par Kelly Dwan &amp; Mel Choyce</div>

			<h3 class="theme-name" id="pub/flounder-name">Flounder</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fflounder&amp;_wpnonce=b2e5c35038">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fflounder">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/brand-new-day-action pub/brand-new-day-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/brand-new-day/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/brand-new-day-action">Détails du thème</span>
	<div class="theme-author">Par Caroline Moore</div>

			<h3 class="theme-name" id="pub/brand-new-day-name">Brand New Day</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbrand-new-day&amp;_wpnonce=22d07fefbb">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbrand-new-day">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/delicacy-action pub/delicacy-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/delicacy/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/delicacy-action">Détails du thème</span>
	<div class="theme-author">Par Aleksandra &#321;&#261;czek</div>

			<h3 class="theme-name" id="pub/delicacy-name">Delicacy</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fdelicacy&amp;_wpnonce=1190b19a4b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fdelicacy">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/yumblog-action premium/yumblog-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/yumblog/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/yumblog-action">Détails du thème</span>
	<div class="theme-author">Par UpThemes</div>

			<h3 class="theme-name" id="premium/yumblog-name">Yumblog</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/yumblog&#038;ref=themesphp&#038;_wpnonce=9a1ef61f00">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fyumblog">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/confit-action pub/confit-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/confit/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/confit-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/confit-name">Confit</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fconfit&amp;_wpnonce=18186606f6">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fconfit">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/fontfolio-action pub/fontfolio-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/fontfolio/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/fontfolio-action">Détails du thème</span>
	<div class="theme-author">Par Marios Lublinski</div>

			<h3 class="theme-name" id="pub/fontfolio-name">Fontfolio</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ffontfolio&amp;_wpnonce=1ee8a0c680">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ffontfolio">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/rusty-grunge-action pub/rusty-grunge-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/rusty-grunge/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/rusty-grunge-action">Détails du thème</span>
	<div class="theme-author">Par Christopher Wallace</div>

			<h3 class="theme-name" id="pub/rusty-grunge-name">Rusty Grunge</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Frusty-grunge&amp;_wpnonce=aea65a0576">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Frusty-grunge">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/p2-action pub/p2-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/p2/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/p2-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/p2-name">P2 Classic</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fp2&amp;_wpnonce=546ec3515a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fp2">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/visual-action pub/visual-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/visual/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/visual-action">Détails du thème</span>
	<div class="theme-author">Par Devin Price</div>

			<h3 class="theme-name" id="pub/visual-name">Visuel</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fvisual&amp;_wpnonce=451a73ea76">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fvisual">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/wedding-action premium/wedding-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/wedding/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/wedding-action">Détails du thème</span>
	<div class="theme-author">Par DesignOrbital</div>

			<h3 class="theme-name" id="premium/wedding-name">Mariage</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/wedding&#038;ref=themesphp&#038;_wpnonce=75baa6e269">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fwedding">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/blogum-action pub/blogum-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/blogum/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/blogum-action">Détails du thème</span>
	<div class="theme-author">Par WPShower</div>

			<h3 class="theme-name" id="pub/blogum-name">Blogum</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fblogum&amp;_wpnonce=36bacf9e4e">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fblogum">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/hatch-action pub/hatch-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/hatch/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/hatch-action">Détails du thème</span>
	<div class="theme-author">Par AlienWP</div>

			<h3 class="theme-name" id="pub/hatch-name">Hatch</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fhatch&amp;_wpnonce=39d0a05af7">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fhatch">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/truly-minimal-action pub/truly-minimal-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/truly-minimal/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/truly-minimal-action">Détails du thème</span>
	<div class="theme-author">Par FlareThemes</div>

			<h3 class="theme-name" id="pub/truly-minimal-name">Truly Minimal</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftruly-minimal&amp;_wpnonce=0f2da8cf48">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftruly-minimal">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/vintage-camera-action pub/vintage-camera-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/vintage-camera/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/vintage-camera-action">Détails du thème</span>
	<div class="theme-author">Par Caroline Moore</div>

			<h3 class="theme-name" id="pub/vintage-camera-name">Vintage Camera</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fvintage-camera&amp;_wpnonce=126c610468">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fvintage-camera">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/shelf-action premium/shelf-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/shelf/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/shelf-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/shelf-name">Shelf</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/shelf&#038;ref=themesphp&#038;_wpnonce=e25585220f">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fshelf">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/origin-action pub/origin-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/origin/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/origin-action">Détails du thème</span>
	<div class="theme-author">Par AlienWP</div>

			<h3 class="theme-name" id="pub/origin-name">Origin</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Forigin&amp;_wpnonce=91ac129970">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Forigin">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/bold-life-action pub/bold-life-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/bold-life/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/bold-life-action">Détails du thème</span>
	<div class="theme-author">Par jayhafling</div>

			<h3 class="theme-name" id="pub/bold-life-name">Bold Life</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbold-life&amp;_wpnonce=e4b1509631">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbold-life">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/fruit-shake-action pub/fruit-shake-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/fruit-shake/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/fruit-shake-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/fruit-shake-name">Fruit Shake</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ffruit-shake&amp;_wpnonce=afba9c810f">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ffruit-shake">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/basic-maths-action premium/basic-maths-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/basic-maths/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/basic-maths-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/basic-maths-name">Basic Maths</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/basic-maths&#038;ref=themesphp&#038;_wpnonce=2f4f925648">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbasic-maths">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/scrollider-express-action premium/scrollider-express-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/scrollider-express/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/scrollider-express-action">Détails du thème</span>
	<div class="theme-author">Par WooThemes</div>

			<h3 class="theme-name" id="premium/scrollider-express-name">Scrollider Express</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/scrollider-express&#038;ref=themesphp&#038;_wpnonce=069cf71e51">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fscrollider-express">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/untitled-action pub/untitled-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/untitled/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/untitled-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/untitled-name">Sans titre</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Funtitled&amp;_wpnonce=0b2f98393b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Funtitled">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/autofocus-action pub/autofocus-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/autofocus/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/autofocus-action">Détails du thème</span>
	<div class="theme-author">Par Allan Cole</div>

			<h3 class="theme-name" id="pub/autofocus-name">AutoFocus</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fautofocus&amp;_wpnonce=df234bf3ed">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fautofocus">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/forefront-action premium/forefront-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/forefront/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/forefront-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/forefront-name">Forefront</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/forefront&#038;ref=themesphp&#038;_wpnonce=928a7743ff">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fforefront">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/debut-action premium/debut-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/debut/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/debut-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/debut-name">Debut</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/debut&#038;ref=themesphp&#038;_wpnonce=0ecd629912">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fdebut">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/pink-touch-2-action pub/pink-touch-2-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/pink-touch-2/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/pink-touch-2-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/pink-touch-2-name">Pink Touch 2</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fpink-touch-2&amp;_wpnonce=3e9ed0d664">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fpink-touch-2">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/minimum-action premium/minimum-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/minimum/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/minimum-action">Détails du thème</span>
	<div class="theme-author">Par StudioPress</div>

			<h3 class="theme-name" id="premium/minimum-name">Minimum</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/minimum&#038;ref=themesphp&#038;_wpnonce=3bb56fc089">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fminimum">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/pinboard-action premium/pinboard-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/pinboard/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/pinboard-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/pinboard-name">Pinboard</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/pinboard&#038;ref=themesphp&#038;_wpnonce=5b8f886130">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpinboard">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sundance-action pub/sundance-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/sundance/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sundance-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/sundance-name">Sundance</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsundance&amp;_wpnonce=889428089b">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsundance">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/full-frame-action premium/full-frame-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/full-frame/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/full-frame-action">Détails du thème</span>
	<div class="theme-author">Par Graph Paper Press</div>

			<h3 class="theme-name" id="premium/full-frame-name">Full Frame</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/full-frame&#038;ref=themesphp&#038;_wpnonce=41e0ef632a">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Ffull-frame">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/mckinley-action pub/mckinley-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/mckinley/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/mckinley-action">Détails du thème</span>
	<div class="theme-author">Par ThemeTrust</div>

			<h3 class="theme-name" id="pub/mckinley-name">McKinley</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fmckinley&amp;_wpnonce=3d75fa0369">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fmckinley">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/personal-action premium/personal-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/personal/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/personal-action">Détails du thème</span>
	<div class="theme-author">Par Obox Themes</div>

			<h3 class="theme-name" id="premium/personal-name">Personal</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/personal&#038;ref=themesphp&#038;_wpnonce=44969c4dfe">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpersonal">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/mimbopro-action premium/mimbopro-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/mimbopro/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/mimbopro-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/mimbopro-name">Mimbo Pro</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/mimbopro&#038;ref=themesphp&#038;_wpnonce=a6bc0a9e6a">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmimbopro">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/on-a-whim-action premium/on-a-whim-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/on-a-whim/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/on-a-whim-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/on-a-whim-name">On a Whim</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/on-a-whim&#038;ref=themesphp&#038;_wpnonce=e9e616996f">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fon-a-whim">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/collective-action premium/collective-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/collective/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/collective-action">Détails du thème</span>
	<div class="theme-author">Par Organic Themes</div>

			<h3 class="theme-name" id="premium/collective-name">Collective</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/collective&#038;ref=themesphp&#038;_wpnonce=a49b9d149b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcollective">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/gallery-action premium/gallery-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/gallery/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/gallery-action">Détails du thème</span>
	<div class="theme-author">Par UpThemes</div>

			<h3 class="theme-name" id="premium/gallery-name">Galerie</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/gallery&#038;ref=themesphp&#038;_wpnonce=a02fa8c102">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fgallery">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/able-action pub/able-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/able/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/able-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/able-name">Able</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fable&amp;_wpnonce=cc55b9ba81">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fable">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/bushwick-action pub/bushwick-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/bushwick/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/bushwick-action">Détails du thème</span>
	<div class="theme-author">Par James Dinsdale and Automattic</div>

			<h3 class="theme-name" id="pub/bushwick-name">Bushwick</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fbushwick&amp;_wpnonce=b309ec4b6c">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fbushwick">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/zoren-action pub/zoren-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/zoren/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/zoren-action">Détails du thème</span>
	<div class="theme-author">Par Fabthemes</div>

			<h3 class="theme-name" id="pub/zoren-name">Zoren</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fzoren&amp;_wpnonce=b7e374999c">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fzoren">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/watson-action premium/watson-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/watson/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/watson-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/watson-name">Watson</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/watson&#038;ref=themesphp&#038;_wpnonce=2b4ebb4e16">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fwatson">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/sempress-action pub/sempress-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/sempress/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/sempress-action">Détails du thème</span>
	<div class="theme-author">Par Matthias Pfefferle</div>

			<h3 class="theme-name" id="pub/sempress-name">SemPress</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsempress&amp;_wpnonce=2897ffadfd">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsempress">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/anthem-action premium/anthem-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/anthem/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/anthem-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/anthem-name">Anthem</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/anthem&#038;ref=themesphp&#038;_wpnonce=d0597aee23">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fanthem">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/standard-action premium/standard-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/standard/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/standard-action">Détails du thème</span>
	<div class="theme-author">Par WooThemes</div>

			<h3 class="theme-name" id="premium/standard-name">Par défaut</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/standard&#038;ref=themesphp&#038;_wpnonce=bc9b89a2ef">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fstandard">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="vip/partner-mlb-fan-action vip/partner-mlb-fan-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/vip/partner-mlb-fan/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="vip/partner-mlb-fan-action">Détails du thème</span>
	<div class="theme-author">Par MLB</div>

			<h3 class="theme-name" id="vip/partner-mlb-fan-name">MLB "Fan"</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=vip%2Fpartner-mlb-fan&amp;_wpnonce=348b926f5d">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=vip%2Fpartner-mlb-fan">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/superhero-action pub/superhero-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/pub/superhero/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/superhero-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/superhero-name">Superhero</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsuperhero&amp;_wpnonce=a2b632db7f">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsuperhero">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/hum-action pub/hum-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/hum/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/hum-action">Détails du thème</span>
	<div class="theme-author">Par Daryl Koopersmith</div>

			<h3 class="theme-name" id="pub/hum-name">Hum</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fhum&amp;_wpnonce=2979db43c3">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fhum">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/eventbrite-venue-action pub/eventbrite-venue-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/eventbrite-venue/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/eventbrite-venue-action">Détails du thème</span>
	<div class="theme-author">Par Voce Platforms</div>

			<h3 class="theme-name" id="pub/eventbrite-venue-name">Eventbrite Multi Event</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Feventbrite-venue&amp;_wpnonce=d7ecd18e9f">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Feventbrite-venue">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/bloggy-action premium/bloggy-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/bloggy/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/bloggy-action">Détails du thème</span>
	<div class="theme-author">Par Anariel Design</div>

			<h3 class="theme-name" id="premium/bloggy-name">Bloggy</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/bloggy&#038;ref=themesphp&#038;_wpnonce=04b828a780">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbloggy">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/on-demand-action premium/on-demand-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/on-demand/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/on-demand-action">Détails du thème</span>
	<div class="theme-author">Par Press75</div>

			<h3 class="theme-name" id="premium/on-demand-name">On Demand</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/on-demand&#038;ref=themesphp&#038;_wpnonce=b98377a068">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fon-demand">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/snap-action premium/snap-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/snap/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/snap-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/snap-name">Snap</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/snap&#038;ref=themesphp&#038;_wpnonce=2c343e009a">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fsnap">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/comet-action pub/comet-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/comet/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/comet-action">Détails du thème</span>
	<div class="theme-author">Par Frostpress</div>

			<h3 class="theme-name" id="pub/comet-name">Comet</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fcomet&amp;_wpnonce=fc1d0f1c44">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fcomet">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/healthy-living-action premium/healthy-living-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/healthy-living/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/healthy-living-action">Détails du thème</span>
	<div class="theme-author">Par Anariel Design</div>

			<h3 class="theme-name" id="premium/healthy-living-name">Healthy Living</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/healthy-living&#038;ref=themesphp&#038;_wpnonce=f4e993501b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fhealthy-living">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/thestyle-action premium/thestyle-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/thestyle/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/thestyle-action">Détails du thème</span>
	<div class="theme-author">Par Elegant Themes</div>

			<h3 class="theme-name" id="premium/thestyle-name">TheStyle</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/thestyle&#038;ref=themesphp&#038;_wpnonce=4914cb6aaf">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fthestyle">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/trvl-action pub/trvl-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/pub/trvl/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/trvl-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/trvl-name">Trvl</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Ftrvl&amp;_wpnonce=256f8cba01">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Ftrvl">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="vip/partner-mlb-retro-action vip/partner-mlb-retro-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/vip/partner-mlb-retro/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="vip/partner-mlb-retro-action">Détails du thème</span>
	<div class="theme-author">Par MLB</div>

			<h3 class="theme-name" id="vip/partner-mlb-retro-name">MLB "Retro"</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=vip%2Fpartner-mlb-retro&amp;_wpnonce=8a3c35beb4">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=vip%2Fpartner-mlb-retro">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/tdeditor-action premium/tdeditor-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/tdeditor/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/tdeditor-action">Détails du thème</span>
	<div class="theme-author">Par Tasko</div>

			<h3 class="theme-name" id="premium/tdeditor-name">tdeditor</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/tdeditor&#038;ref=themesphp&#038;_wpnonce=30a2ab5f7b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Ftdeditor">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="pub/syntax-action pub/syntax-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/pub/syntax/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="pub/syntax-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="pub/syntax-name">Syntax</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=activate&amp;stylesheet=pub%2Fsyntax&amp;_wpnonce=3d4e3b2c8a">Activer</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=pub%2Fsyntax">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/photography-action premium/photography-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/photography/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/photography-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/photography-name">Photographie</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/photography&#038;ref=themesphp&#038;_wpnonce=141615168e">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fphotography">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/luscious-action premium/luscious-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/luscious/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/luscious-action">Détails du thème</span>
	<div class="theme-author">Par StudioPress</div>

			<h3 class="theme-name" id="premium/luscious-name">Luscious</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/luscious&#038;ref=themesphp&#038;_wpnonce=ed59e1225d">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fluscious">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/flora-and-fauna-action premium/flora-and-fauna-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/flora-and-fauna/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/flora-and-fauna-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/flora-and-fauna-name">Flora and Fauna</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/flora-and-fauna&#038;ref=themesphp&#038;_wpnonce=7e025f92e4">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fflora-and-fauna">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/massive-press-action premium/massive-press-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/massive-press/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/massive-press-action">Détails du thème</span>
	<div class="theme-author">Par Press75</div>

			<h3 class="theme-name" id="premium/massive-press-name">Massive Press</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/massive-press&#038;ref=themesphp&#038;_wpnonce=dccbb3ec46">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmassive-press">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/react-action premium/react-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/react/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/react-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/react-name">React</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/react&#038;ref=themesphp&#038;_wpnonce=29b68aaf5e">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Freact">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/blog-simple-action premium/blog-simple-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/blog-simple/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/blog-simple-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/blog-simple-name">Blog Simple</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/blog-simple&#038;ref=themesphp&#038;_wpnonce=0be1412d54">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fblog-simple">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/camera-action premium/camera-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/camera/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/camera-action">Détails du thème</span>
	<div class="theme-author">Par Array</div>

			<h3 class="theme-name" id="premium/camera-name">Appareil photo</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/camera&#038;ref=themesphp&#038;_wpnonce=cca14785b4">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcamera">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/isca-action premium/isca-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/isca/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/isca-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/isca-name">Isca</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/isca&#038;ref=themesphp&#038;_wpnonce=80c58c8ad2">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fisca">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/kiore-moana-action premium/kiore-moana-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/kiore-moana/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/kiore-moana-action">Détails du thème</span>
	<div class="theme-author">Par Elmastudio</div>

			<h3 class="theme-name" id="premium/kiore-moana-name">Kiore Moana</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/kiore-moana&#038;ref=themesphp&#038;_wpnonce=07b1b8b763">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fkiore-moana">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/alto-action premium/alto-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/alto/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/alto-action">Détails du thème</span>
	<div class="theme-author">Par Pixel Union</div>

			<h3 class="theme-name" id="premium/alto-name">Alto</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/alto&#038;ref=themesphp&#038;_wpnonce=8c8b7f1fb4">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Falto">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/atrium-action premium/atrium-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/atrium/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/atrium-action">Détails du thème</span>
	<div class="theme-author">Par Pixel Union</div>

			<h3 class="theme-name" id="premium/atrium-name">Atrium</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/atrium&#038;ref=themesphp&#038;_wpnonce=099971b529">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fatrium">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/designer-action premium/designer-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/designer/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/designer-action">Détails du thème</span>
	<div class="theme-author">Par Array</div>

			<h3 class="theme-name" id="premium/designer-name">Designer</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/designer&#038;ref=themesphp&#038;_wpnonce=ce7818f5ce">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fdesigner">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/magazine-action premium/magazine-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/magazine/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/magazine-action">Détails du thème</span>
	<div class="theme-author">Par StudioPress</div>

			<h3 class="theme-name" id="premium/magazine-name">Magazine</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/magazine&#038;ref=themesphp&#038;_wpnonce=2fc51189eb">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmagazine">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/the-parisian-action premium/the-parisian-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/the-parisian/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/the-parisian-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/the-parisian-name">The Parisian</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/the-parisian&#038;ref=themesphp&#038;_wpnonce=8457613930">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fthe-parisian">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/magnate-express-action premium/magnate-express-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/magnate-express/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/magnate-express-action">Détails du thème</span>
	<div class="theme-author">Par WooThemes</div>

			<h3 class="theme-name" id="premium/magnate-express-name">Magnate Express</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/magnate-express&#038;ref=themesphp&#038;_wpnonce=77b906de1b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmagnate-express">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/business-identity-action premium/business-identity-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/business-identity/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/business-identity-action">Détails du thème</span>
	<div class="theme-author">Par Professional Themes</div>

			<h3 class="theme-name" id="premium/business-identity-name">Business Identity</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/business-identity&#038;ref=themesphp&#038;_wpnonce=bfd714df26">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbusiness-identity">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/bailey-action premium/bailey-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/bailey/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/bailey-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/bailey-name">Bailey</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/bailey&#038;ref=themesphp&#038;_wpnonce=227dc06c9e">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbailey">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/traction-action premium/traction-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/traction/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/traction-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/traction-name">Traction</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/traction&#038;ref=themesphp&#038;_wpnonce=3d471f2f30">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Ftraction">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/basis-action premium/basis-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/basis/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/basis-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/basis-name">Basis</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/basis&#038;ref=themesphp&#038;_wpnonce=ed15f44489">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbasis">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/blocco-action premium/blocco-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/blocco/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/blocco-action">Détails du thème</span>
	<div class="theme-author">Par Press75</div>

			<h3 class="theme-name" id="premium/blocco-name">Blocco</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/blocco&#038;ref=themesphp&#038;_wpnonce=006b9dc9b3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fblocco">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/creative-action premium/creative-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/creative/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/creative-action">Détails du thème</span>
	<div class="theme-author">Par UpThemes</div>

			<h3 class="theme-name" id="premium/creative-name">Creative</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/creative&#038;ref=themesphp&#038;_wpnonce=21c495e0f3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcreative">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/ampersand-action premium/ampersand-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/ampersand/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/ampersand-action">Détails du thème</span>
	<div class="theme-author">Par Array</div>

			<h3 class="theme-name" id="premium/ampersand-name">Ampersand</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/ampersand&#038;ref=themesphp&#038;_wpnonce=b39977a8e7">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fampersand">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/funki-action premium/funki-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/funki/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/funki-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/funki-name">Funki</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/funki&#038;ref=themesphp&#038;_wpnonce=2baef223ff">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Ffunki">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/the-writer-action premium/the-writer-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/the-writer/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/the-writer-action">Détails du thème</span>
	<div class="theme-author">Par Obox Themes</div>

			<h3 class="theme-name" id="premium/the-writer-name">The Writer</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/the-writer&#038;ref=themesphp&#038;_wpnonce=b44b460ffc">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fthe-writer">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/just-desserts-action premium/just-desserts-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/just-desserts/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/just-desserts-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/just-desserts-name">Just Desserts</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/just-desserts&#038;ref=themesphp&#038;_wpnonce=34910659ed">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fjust-desserts">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/axon-action premium/axon-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/axon/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/axon-action">Détails du thème</span>
	<div class="theme-author">Par DesignOrbital</div>

			<h3 class="theme-name" id="premium/axon-name">Axon</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/axon&#038;ref=themesphp&#038;_wpnonce=5c415cb1c3">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Faxon">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/promenade-action premium/promenade-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/promenade/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/promenade-action">Détails du thème</span>
	<div class="theme-author">Par Cedaro</div>

			<h3 class="theme-name" id="premium/promenade-name">Promenade</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/promenade&#038;ref=themesphp&#038;_wpnonce=b1be756ba7">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpromenade">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/mina-olen-action premium/mina-olen-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/mina-olen/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/mina-olen-action">Détails du thème</span>
	<div class="theme-author">Par Foxnet</div>

			<h3 class="theme-name" id="premium/mina-olen-name">Mina Olen</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/mina-olen&#038;ref=themesphp&#038;_wpnonce=500276110c">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fmina-olen">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/wire-action premium/wire-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/wire/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/wire-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/wire-name">Wire</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/wire&#038;ref=themesphp&#038;_wpnonce=7dba5277fd">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fwire">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/creative-portfolio-action premium/creative-portfolio-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/creative-portfolio/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/creative-portfolio-action">Détails du thème</span>
	<div class="theme-author">Par Professional Themes</div>

			<h3 class="theme-name" id="premium/creative-portfolio-name">Creative Portfolio</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/creative-portfolio&#038;ref=themesphp&#038;_wpnonce=754a8368b1">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fcreative-portfolio">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/notebook-action premium/notebook-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/notebook/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/notebook-action">Détails du thème</span>
	<div class="theme-author">Par Tasko</div>

			<h3 class="theme-name" id="premium/notebook-name">Notebook</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/notebook&#038;ref=themesphp&#038;_wpnonce=3fe29eebba">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fnotebook">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/bromley-action premium/bromley-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/bromley/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/bromley-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/bromley-name">Bromley</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/bromley&#038;ref=themesphp&#038;_wpnonce=5917e3d003">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbromley">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/eight-action premium/eight-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/eight/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/eight-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/eight-name">Eight</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/eight&#038;ref=themesphp&#038;_wpnonce=778aee9c33">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Feight">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/oxford-action premium/oxford-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/oxford/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/oxford-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/oxford-name">Oxford</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/oxford&#038;ref=themesphp&#038;_wpnonce=81cd4b657d">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Foxford">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/blogly-action premium/blogly-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/blogly/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/blogly-action">Détails du thème</span>
	<div class="theme-author">Par ThemeFurnace</div>

			<h3 class="theme-name" id="premium/blogly-name">Blogly</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/blogly&#038;ref=themesphp&#038;_wpnonce=678cf7771b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fblogly">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/kent-action premium/kent-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/kent/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/kent-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/kent-name">Kent</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/kent&#038;ref=themesphp&#038;_wpnonce=794dda6a3e">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fkent">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/chalk-action premium/chalk-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/chalk/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/chalk-action">Détails du thème</span>
	<div class="theme-author">Par The Theme Foundry</div>

			<h3 class="theme-name" id="premium/chalk-name">Chalk</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/chalk&#038;ref=themesphp&#038;_wpnonce=1058e2c07b">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fchalk">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/poly-action premium/poly-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/poly/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/poly-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/poly-name">Poly</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/poly&#038;ref=themesphp&#038;_wpnonce=80e79f6742">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fpoly">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/simfo-action premium/simfo-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/simfo/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/simfo-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/simfo-name">Simfo</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/simfo&#038;ref=themesphp&#038;_wpnonce=b9e8d9a760">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fsimfo">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/awesome-action premium/awesome-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/awesome/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/awesome-action">Détails du thème</span>
	<div class="theme-author">Par Graph Paper Press</div>

			<h3 class="theme-name" id="premium/awesome-name">Awesome</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/awesome&#038;ref=themesphp&#038;_wpnonce=c7b78107be">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fawesome">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/bon-vivant-action premium/bon-vivant-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/bon-vivant/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/bon-vivant-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/bon-vivant-name">Bon Vivant</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/bon-vivant&#038;ref=themesphp&#038;_wpnonce=a9144fff02">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbon-vivant">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/bexley-action premium/bexley-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/bexley/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/bexley-action">Détails du thème</span>
	<div class="theme-author">Par Pro Theme Design</div>

			<h3 class="theme-name" id="premium/bexley-name">Bexley</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/bexley&#038;ref=themesphp&#038;_wpnonce=510f8e2648">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fbexley">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/delight-action premium/delight-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/delight/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/delight-action">Détails du thème</span>
	<div class="theme-author">Par CyberChimps Inc</div>

			<h3 class="theme-name" id="premium/delight-name">Delight</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/delight&#038;ref=themesphp&#038;_wpnonce=7f236e6d62">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fdelight">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/ladder-action premium/ladder-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/ladder/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/ladder-action">Détails du thème</span>
	<div class="theme-author">Par Viva Themes</div>

			<h3 class="theme-name" id="premium/ladder-name">Ladder</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/ladder&#038;ref=themesphp&#038;_wpnonce=1a9bda2fae">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fladder">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/antenna-action premium/antenna-name">
			<div class="theme-screenshot">
			<img src="https://i2.wp.com/s0.wp.com/wp-content/themes/premium/antenna/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/antenna-action">Détails du thème</span>
	<div class="theme-author">Par DesignOrbital</div>

			<h3 class="theme-name" id="premium/antenna-name">Antenna</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/antenna&#038;ref=themesphp&#038;_wpnonce=34b5691b5f">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fantenna">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/inspiration-laboratory-action premium/inspiration-laboratory-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/inspiration-laboratory/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/inspiration-laboratory-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/inspiration-laboratory-name">Inspiration Laboratory</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/inspiration-laboratory&#038;ref=themesphp&#038;_wpnonce=d8aad2b91f">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Finspiration-laboratory">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/espresso-action premium/espresso-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/espresso/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/espresso-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/espresso-name">Espresso</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/espresso&#038;ref=themesphp&#038;_wpnonce=3298d7c1ef">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fespresso">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/clear-news-action premium/clear-news-name">
			<div class="theme-screenshot">
			<img src="https://i1.wp.com/s0.wp.com/wp-content/themes/premium/clear-news/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/clear-news-action">Détails du thème</span>
	<div class="theme-author">Par Press75</div>

			<h3 class="theme-name" id="premium/clear-news-name">Clear News</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/clear-news&#038;ref=themesphp&#038;_wpnonce=21c0639059">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Fclear-news">Aperçu</a>
			
	</div>

	</div>
<div class="theme" tabindex="0" aria-describedby="premium/everyday-action premium/everyday-name">
			<div class="theme-screenshot">
			<img src="https://i0.wp.com/s0.wp.com/wp-content/themes/premium/everyday/screenshot.png?w=434" alt="" />
		</div>
		<span class="more-details" id="premium/everyday-action">Détails du thème</span>
	<div class="theme-author">Par Automattic</div>

			<h3 class="theme-name" id="premium/everyday-name">Everyday</h3>
	
	<div class="theme-actions">

	
							<a class="button button-primary activate" href="https://juniorp15.wordpress.com/wp-admin/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium/everyday&#038;ref=themesphp&#038;_wpnonce=c75788528d">Acheter</a>
		
					<a class="button button-primary load-customize hide-if-no-customize" href="https://juniorp15.wordpress.com/wp-admin/customize.php?theme=premium%2Feveryday">Aperçu</a>
			
	</div>

	</div>
	<br class="clear" />
	</div>
</div>
<div class="theme-overlay"></div>

<p class="no-themes">Aucun thème trouvé. Essayez une autre recherche.</p>

</div><!-- .wrap -->
<script id="tmpl-theme" type="text/template">
	<# if ( data.screenshot[0] ) { #>
		<div class="theme-screenshot">
			<img src="{{ data.screenshot[0] }}" alt="" />
		</div>
	<# } else { #>
		<div class="theme-screenshot blank"></div>
	<# } #>
	<span class="more-details" id="{{ data.id }}-action">Détails du thème</span>
	<div class="theme-author">Par {{{ data.author }}}</div>

	<# if ( data.active ) { #>
		<h3 class="theme-name" id="{{ data.id }}-name">
			<span>Actif :</span> {{{ data.name }}}		</h3>
	<# } else { #>
		<h3 class="theme-name" id="{{ data.id }}-name">{{{ data.name }}}</h3>
	<# } #>

	<div class="theme-actions">

	<# if ( data.active ) { #>
		<# if ( data.actions.customize ) { #>
			<a class="button button-primary customize load-customize hide-if-no-customize" href="{{ data.actions.customize }}">Personnaliser</a>
		<# } #>
	<# } else { #>
		<a class="button button-secondary activate" href="{{{ data.actions.activate }}}">Activer</a>
		<a class="button button-primary load-customize hide-if-no-customize" href="{{{ data.actions.customize }}}">Aperçu</a>
	<# } #>

	</div>

	<# if ( data.hasUpdate ) { #>
		<div class="theme-update">Mise à jour disponible</div>
	<# } #>
</script>

<script id="tmpl-theme-single" type="text/template">
	<div class="theme-backdrop"></div>
	<div class="theme-wrap">
		<div class="theme-header">
			<button class="left dashicons dashicons-no"><span class="screen-reader-text">Affichier le thème précédent</span></button>
			<button class="right dashicons dashicons-no"><span class="screen-reader-text">Afficher le thème suivant</span></button>
			<button class="close dashicons dashicons-no"><span class="screen-reader-text">Fermer la fenêtre de détails du dialogue</span></button>
		</div>
		<div class="theme-about">
			<div class="theme-screenshots">
			<# if ( data.screenshot[0] ) { #>
				<div class="screenshot"><img src="{{ data.screenshot[0] }}" alt="" /></div>
			<# } else { #>
				<div class="screenshot blank"></div>
			<# } #>
			</div>

			<div class="theme-info">
				<# if ( data.active ) { #>
					<span class="current-label">Thème actuel</span>
				<# } #>
				<h3 class="theme-name">{{{ data.name }}}<span class="theme-version">Version&nbsp;: {{ data.version }}</span></h3>
				<h4 class="theme-author">Par {{{ data.authorAndUri }}}</h4>

				<# if ( data.hasUpdate ) { #>
				<div class="theme-update-message">
					<h4 class="theme-update">Mise à jour disponible</h4>
					{{{ data.update }}}
				</div>
				<# } #>
				<p class="theme-description">{{{ data.description }}}</p>

				<# if ( data.parent ) { #>
					<p class="parent-theme">This is a child theme of <strong>{{{ data.parent }}}</strong>.</p>
				<# } #>

				<# if ( data.tags ) { #>
					<p class="theme-tags"><span>Mots-clés&nbsp;:</span> {{{ data.tags }}}</p>
				<# } #>
			</div>
		</div>

		<div class="theme-actions">
			<div class="active-theme">
				<a href="{{{ data.actions.customize }}}" class="button button-primary customize load-customize hide-if-no-customize">Personnaliser</a>
				<a class='button button-secondary' href='widgets.php'>Widgets</a> <a class='button button-secondary' href='nav-menus.php'>Menus</a> <a class='button button-secondary' href='themes.php?page=https://juniorp15.wordpress.com/wp-admin/customize.php?autofocus%5Bsection%5D=colors_manager_tool'>Arrière-plan</a> <a class='button button-secondary' href='themes.php?page=custom-background'>Arrière-plan</a> <a class='button button-secondary' href='themes.php?page=mobile-options'>Portable</a>			</div>
			<div class="inactive-theme">
				<# if ( data.actions.activate ) { #>
					<a href="{{{ data.actions.activate }}}" class="button button-secondary activate">Activer</a>
				<# } #>
				<a href="{{{ data.actions.customize }}}" class="button button-primary load-customize hide-if-no-customize">Aperçu</a>
			</div>

			<# if ( ! data.active && data.actions['delete'] ) { #>
				<a href="{{{ data.actions['delete'] }}}" class="button button-secondary delete-theme">Supprimer </a>
			<# } #>
		</div>
	</div>
</script>


<div class="clear"></div></div><!-- wpbody-content -->
<div class="clear"></div></div><!-- wpbody -->
<div class="clear"></div></div><!-- wpcontent -->

<div id="wpfooter" role="contentinfo">
	<script type="text/javascript"> jQuery("#wordads_menu_item").parent().hide(); </script>	<p id="footer-left" class="alignleft">
		<span id="footer-thankyou">Merci de contribuer à la réussite de <a href="http://wordpress.com/">WordPress</a></span> &bull; <a href="http://fr.support.wordpress.com/">Support</a> &bull; <a href="http://fr.forums.wordpress.com">Forums</a> 	</p>
	<p id="footer-upgrade" class="alignright">
			</p>
	<div class="clear"></div>
</div>
<script type="text/javascript">
	var _admin_pv_props = {
		from_page: 'themes',
		source: 'wp-admin',
		user_type: 'New User'
	};
	_tkq = window._tkq || [];
	_tkq.push( [ 'identifyUser', 93895094, 'doston15' ] );
	_tkq.push( [ 'recordEvent', 'wpcom_admin_page_view', _admin_pv_props ] );
</script>
<script src="//stats.wp.com/w.js?48" type="text/javascript" async defer></script>
<script type="text/javascript">
_stq = window._stq || [];
_stq.push(['raw', {
  host:document.location.host,
  ref:document.referrer,
  admin:1,
  blog:98715512,
  user_id:93895094,
  page:"themes.php"
}]);
</script>
<script type='text/javascript' src='//0.gravatar.com/js/gprofiles.js?ver=201537x'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var WPGroHo = {"my_hash":"197e43c46bc2be8e4938586790fe952d"};
/* ]]> */
</script>
<script type='text/javascript' src='https://s2.wp.com/wp-content/mu-plugins/gravatar-hovercards/wpgroho.js?m=1380573781g'></script>

	<script>
		//initialize and attach hovercards to all gravatars
		jQuery( document ).ready( function( $ ) {

			if (typeof Gravatar === "undefined"){
				return;
			}

			if ( typeof Gravatar.init !== "function" ) {
				return;
			}			

			Gravatar.profile_cb = function( hash, id ) {
				WPGroHo.syncProfileData( hash, id );
			};
			Gravatar.my_hash = WPGroHo.my_hash;
			Gravatar.init( 'body', '#wp-admin-bar-my-account' );
		});
	</script>

		<script type="text/javascript">
		(function() {
			var request, b = document.body, c = 'className', cs = 'customize-support', rcs = new RegExp('(^|\\s+)(no-)?'+cs+'(\\s+|$)');

			request = true;

			b[c] = b[c].replace( rcs, ' ' );
			b[c] += ( window.postMessage && request ? ' ' : ' no-' ) + cs;
		}());
	</script>
			<div id="wpadminbar" class="nojq nojs ltr">
						<div class="quicklinks" id="wp-toolbar" role="navigation" aria-label="Barre d&rsquo;outils" tabindex="0">
				<ul id="wp-admin-bar-root-default" class="ab-top-menu">
		<li id="wp-admin-bar-menu-toggle"><a class="ab-item"  href="#"><span class="ab-icon"></span><span class="screen-reader-text">Menu</span></a>		</li>
		<li id="wp-admin-bar-blog" class="menupop my-sites"><a class="ab-item"  aria-haspopup="true" href="https://wordpress.com/stats/juniorp15.wordpress.com">Mon site</a><div class="ab-sub-wrapper"><ul id="wp-admin-bar-blog-default" class="ab-submenu">
		<li id="wp-admin-bar-blog-info" class="current-site"><div class="ab-item ab-empty-item" ><div class="ab-site-icon"></div><span class="ab-site-title">juniorp15</span><span class="ab-site-description">juniorp15.wordpress.com</span></div>		</li>
		<li id="wp-admin-bar-new-site"><a class="ab-item"  href="https://signup.wordpress.com/signup/">+ Ajouter un nouveau site WordPress</a>		</li>
		<li id="wp-admin-bar-view-site" class="mb-icon"><a class="ab-item"  href="https://juniorp15.wordpress.com/">Afficher le site</a>		</li>
		<li id="wp-admin-bar-dashboard-top" class="mb-icon"><a class="ab-item"  href="https://juniorp15.wordpress.com/wp-admin/">Tableau de bord</a>		</li>
		<li id="wp-admin-bar-blog-stats" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/stats/juniorp15.wordpress.com">Stats </a>		</li>
		<li id="wp-admin-bar-comments" class="mb-icon"><a class="ab-item"  href="https://juniorp15.wordpress.com/wp-admin/edit-comments.php">Commentaires</a>		</li></ul><ul id="wp-admin-bar-publish" class="ab-submenu">
		<li id="wp-admin-bar-publish-header" class="ab-submenu-header"><div class="ab-item ab-empty-item" >Publier</div>		</li>
		<li id="wp-admin-bar-new-post" class="inline-action"><div class="ab-item ab-empty-item" ><a href="https://juniorp15.wordpress.com/wp-admin/edit.php?post_type=post" class="ab-item primary mb-icon" id="wp-admin-bar-edit-post">Articles</a><a href="https://wordpress.com/post/98715512/new" class="secondary" id="wp-admin-bar-new-post">Ajouter</a></div>		</li>
		<li id="wp-admin-bar-new-page" class="inline-action"><div class="ab-item ab-empty-item" ><a href="https://juniorp15.wordpress.com/wp-admin/edit.php?post_type=page" class="ab-item primary mb-icon" id="wp-admin-bar-edit-page">Pages</a><a href="https://wordpress.com/page/98715512/new" class="secondary" id="wp-admin-bar-new-page">Ajouter</a></div>		</li>
		<li id="wp-admin-bar-new-attachment" class="inline-action"><div class="ab-item ab-empty-item" ><a href="https://juniorp15.wordpress.com/wp-admin/upload.php" class="ab-item primary mb-icon" id="wp-admin-bar-edit-attachment">Médias</a><a href="https://juniorp15.wordpress.com/wp-admin/media-new.php" class="secondary" id="wp-admin-bar-new-attachment">Ajouter</a></div>		</li>
		<li id="wp-admin-bar-new-post-types" class="menupop mb-icon"><div class="ab-item ab-empty-item"  aria-haspopup="true">Nouveau</div><div class="ab-sub-wrapper"><ul id="wp-admin-bar-new-post-types-default" class="ab-submenu">
		<li id="wp-admin-bar-new-jetpack-portfolio"><a class="ab-item"  href="https://juniorp15.wordpress.com/wp-admin/post-new.php?post_type=jetpack-portfolio">Projet</a>		</li></ul></div>		</li></ul><ul id="wp-admin-bar-look-and-feel" class="ab-submenu">
		<li id="wp-admin-bar-look-and-feel-header" class="ab-submenu-header"><div class="ab-item ab-empty-item" >Présentation</div>		</li>
		<li id="wp-admin-bar-themes" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/design/juniorp15.wordpress.com">Thèmes</a>		</li>
		<li id="wp-admin-bar-customize" class="hide-if-no-customize mb-icon"><a class="ab-item"  href="https://juniorp15.wordpress.com/wp-admin/customize.php?return=https%3A%2F%2Fjuniorp15.wordpress.com%2Fwp-admin%2Fthemes.php">Personnaliser</a>		</li>
		<li id="wp-admin-bar-menus" class="mb-icon"><a class="ab-item"  href="https://juniorp15.wordpress.com/wp-admin/nav-menus.php">Menus</a>		</li></ul><ul id="wp-admin-bar-configuration" class="ab-submenu">
		<li id="wp-admin-bar-configuration-header" class="ab-submenu-header"><div class="ab-item ab-empty-item" >Configuration</div>		</li>
		<li id="wp-admin-bar-sharing" class="mb-icon"><a class="ab-item"  href="https://juniorp15.wordpress.com/wp-admin/options-general.php?page=sharing">Partage</a>		</li>
		<li id="wp-admin-bar-users-toolbar" class="mb-icon"><a class="ab-item"  href="https://juniorp15.wordpress.com/wp-admin/users.php">Utilisateurs</a>		</li>
		<li id="wp-admin-bar-blog-settings" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/settings/general/juniorp15.wordpress.com">Réglages</a>		</li>
		<li id="wp-admin-bar-upgrades" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/plans/juniorp15.wordpress.com">Options payantes</a>		</li></ul></div>		</li>
		<li id="wp-admin-bar-jumptotop-button-menu"><a class="ab-item"  href="#"><div id="jumptotop"><span class="noticon noticon-top"></span></div></a>		</li>
		<li id="wp-admin-bar-newdash" class="menupop"><a class="ab-item"  aria-haspopup="true" href="https://wordpress.com/">Lecteur</a><div class="ab-sub-wrapper"><ul id="wp-admin-bar-newdash-default" class="ab-submenu">
		<li id="wp-admin-bar-following"><a class="ab-item"  href="https://wordpress.com/"><svg class="gridicon gridicon__following" height="16px" width="16px" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g><path d="M11.944 17.083L7 12.056l1.648-1.676 3.296 3.352 8.3-7.385C18.445 3.722 15.425 2 12 2 6.477 2 2 6.477 2 12s4.477 10 10 10 10-4.477 10-10c0-1.212-.227-2.37-.622-3.444l-9.434 8.527z"/></g></svg> Abonné</a>		</li>
		<li id="wp-admin-bar-discover-freshly-pressed" class="mb-icon-spacer"><a class="ab-item"  href="https://wordpress.com/fresh/">Fraîchement Pressé</a>		</li>
		<li id="wp-admin-bar-discover-recommended-blogs" class="mb-icon-spacer"><a class="ab-item"  href="https://wordpress.com/recommendations/">Blogs recommandés</a>		</li></ul><ul id="wp-admin-bar-my-activity" class="ab-submenu">
		<li id="wp-admin-bar-my-activity-header" class="ab-submenu-header"><div class="ab-item ab-empty-item" >Mon Activité</div>		</li>
		<li id="wp-admin-bar-my-activity-my-comments" class="mb-icon-spacer"><a class="ab-item"  href="https://wordpress.com/activities/comments/">Mes commentaires</a>		</li>
		<li id="wp-admin-bar-my-activity-my-likes" class="mb-icon-spacer"><a class="ab-item"  href="https://wordpress.com/activities/likes/">Mes Likes</a>		</li></ul></div>		</li>
		<li id="wp-admin-bar-stats"><a class="ab-item"  href="https://wordpress.com/stats/juniorp15.wordpress.com"><div><script type='text/javascript'>var src;if(typeof(window.devicePixelRatio)=='undefined'||window.devicePixelRatio<2){src='/wp-includes/charts/admin-bar-hours-scale.php';}else{src='/wp-includes/charts/admin-bar-hours-scale-2x.php';}document.write('<img style=\'vertical-align: baseline\' src=\''+src+'\' alt=\'Stats\' title=\'Consultations du site par heure, pour ces 2 derniers jours. Cliquez pour accéder aux Statistiques Complètes.\' />');</script></div></a>		</li></ul><ul id="wp-admin-bar-top-secondary" class="ab-top-secondary ab-top-menu">
		<li id="wp-admin-bar-search" class="admin-bar-search"><div class="ab-item ab-empty-item" tabindex="-1">
		<form action="https://juniorp15.wordpress.com/wp-admin/admin.php" method="get" class="" id="adminbarsearch">
			<input type="hidden" name="page" value="omnisearch" />
			<input name="s" type="search" class="adminbar-input" id="adminbar-search" value="" placeholder="Rechercher Tout" />
							<input type="submit" class="adminbar-button" value="Recherche" />
					</form>

		<style>
				#adminbar-search::-webkit-input-placeholder,
				#adminbar-search:-moz-placeholder,
				#adminbar-search::-moz-placeholder,
				#adminbar-search:-ms-input-placeholder {
					text-shadow: none;
				}
			</style></div>		</li>
		<li id="wp-admin-bar-notes" class="menupop"><div class="ab-item ab-empty-item" ><span id="wpnt-notes-unread-count" class="wpnt-loading wpn-read">
						<span class="noticon noticon-notification"></span>
						</span></div><div id="wpnt-notes-panel2" style="display:none" lang="fr" dir="ltr"><div class="wpnt-notes-panel-header"><span class="wpnt-notes-header"></span><span class="wpnt-notes-panel-link"></span></div></div>		</li>
		<li id="wp-admin-bar-my-account" class="menupop with-avatar"><a class="ab-item"  aria-haspopup="true" href="https://wordpress.com/me/"><img alt='' src='https://1.gravatar.com/avatar/197e43c46bc2be8e4938586790fe952d?s=32&#038;d=mm&#038;r=G' class='avatar avatar-32' height='32' width='32' /></a><div class="ab-sub-wrapper"><ul id="wp-admin-bar-user-actions" class="ab-submenu">
		<li id="wp-admin-bar-user-info" class="user-info user-info-item"><div class="ab-item ab-empty-item" tabindex="-1"><img alt='' src='https://1.gravatar.com/avatar/197e43c46bc2be8e4938586790fe952d?s=128&#038;d=mm&#038;r=G' class='avatar avatar-128' height='128' width='128' /><span class="display-name">doston15</span><span class="username"><a class="at-username" href="http://gravatar.com/doston15">doston15</a>&nbsp;&middot;&nbsp;<a href="https://juniorp15.wordpress.com/wp-login.php?action=logout&amp;redirect_to=https%3A%2F%2Fwordpress.com%2F&amp;_wpnonce=a3010d6e0b">Déconnexion</a></span></div>		</li>
		<li id="wp-admin-bar-profile-header" class="ab-submenu-header"><div class="ab-item ab-empty-item" >Profil</div>		</li>
		<li id="wp-admin-bar-my-profile" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me">Mon Profil</a>		</li>
		<li id="wp-admin-bar-account-settings" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/account">Paramètres du compte</a>		</li>
		<li id="wp-admin-bar-billing" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/billing">Mes paiements</a>		</li>
		<li id="wp-admin-bar-security" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/security">Sécurité</a>		</li>
		<li id="wp-admin-bar-notifications" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/notifications">Notifications</a>		</li>
		<li id="wp-admin-bar-special-header" class="ab-submenu-header"><div class="ab-item ab-empty-item" >Spécial</div>		</li>
		<li id="wp-admin-bar-next-steps" class="mb-icon"><a class="ab-item"  href="https://wordpress.com/me/next">Étapes suivantes</a>		</li>
		<li id="wp-admin-bar-help" class="mb-icon"><a class="ab-item"  href="http://fr.support.wordpress.com/">Aide</a>		</li></ul></div>		</li>
		<li id="wp-admin-bar-ab-new-post"><a class="ab-item"  href="https://fr.wordpress.com/post/98715512/new/"></a>		</li>
		<li id="wp-admin-bar-store_link" class="admin-menu-store-link"><a class="ab-item"  href="https://wordpress.com/plans/?ref=go-pro"><span>Passez à la version Premium</span></a>		</li></ul>			</div>
						<a class="screen-reader-shortcut" href="https://juniorp15.wordpress.com/wp-login.php?action=logout&#038;_wpnonce=a3010d6e0b">Se déconnecter</a>
					</div>

		
<script type="text/javascript">
/* <![CDATA[ */
var clickDebugLink;

jQuery(document).ready( function($) {
	var single = false, w = 1000,
		supe = false;

	$(document.body).load(function(){ $('#wpadminbar img.grav-hashed').removeClass('grav-hashed'); }); // hack to hide the gravatar hovercard

	if ( single && supe )
		w = 1385;
	else if ( supe )
		w = 1200;

	// debug bar extra
	clickDebugLink = function( parent_id, obj ) {

		$('#'+parent_id).children('div').hide();

		document.getElementById( obj.href.substr( obj.href.indexOf( '#' ) + 1 ) ).style.display = 'block';
		$( obj.href.substr( obj.href.indexOf( '#' ) ) ).show()

		$(obj).parent().addClass('current').siblings('li').removeClass('current');

		return false;
	};

	$( '#wpadminbar #wp-admin-bar-shortlink' ).click( function() {
		$( '#adminbar-shortlink-input' ).select();
	});

	// skip tap-to-hover on site switcher for mobile
	if ( 'ontouchstart' in window ) {
		$('#wp-admin-bar-switch-site').on( 'touchstart', function( event ) {
			if ( $( window ).width() > 782 ) {
				return;
			}
			event.stopPropagation();
			$( event.target ).first( 'a' ).click();
		});
	}

});
/* ]]> */
</script>
	<div class="wpcom-bubble action-bubble">
		<div class="bubble-txt"></div>
	</div>
	<script type="text/javascript">function hideBubble() { jQuery('body').append( jQuery( 'div.wpcom-bubble' ).removeClass( 'fadein' ) ).off( 'click.bubble touchstart.bubble' ); jQuery(document).off( 'scroll.bubble' ); };</script>
		<script type="text/javascript">
	jQuery( '#wp-admin-bar-jumptotop-button-menu a' ).click( function( e ) {
		e.preventDefault();
		jQuery( 'html, body' ).animate( { scrollTop: 0 }, 'fast' );
	} );
	function hideShowTbJumpToTop() {
		var total_width = 0;
		// Calculate total width taken by li's minus our button to see if we it'll
		// overlap with other toolbar menus.
		jQuery( '#wp-admin-bar-root-default > li' ).each( function() {
			var self = jQuery( this );
			if ( 'wp-admin-bar-jumptotop-button-menu' != self.attr( 'id' ) )
				total_width += self.width();
		});
		if ( jQuery( '#wp-admin-bar-jumptotop-button-menu' ).position()['left'] - total_width < 10 ) {
			jQuery( '#jumptotop' ).animate( { 'top': '-50px' }, 'fast' );
		} else if (  jQuery( window ).scrollTop() >= 350 && parseInt( jQuery( '#jumptotop' ).css( 'top' ) ) < 0 ) {
			if ( jQuery( '#wp-admin-bar-jumptotop-button-menu' ).position()['left'] - total_width < 10 )
			   return;
			jQuery( '#jumptotop' ).animate( { 'top': 0 }, 'fast' );
		} else if (  jQuery( window ).scrollTop() < 1 && parseInt( jQuery( '#jumptotop' ).css( 'top' ) ) >= 0 ) {
			jQuery( '#jumptotop' ).animate( { 'top': '-50px' }, 'fast' );
		}
	}
	// handle on page load if auto scrolling to a position
	hideShowTbJumpToTop();
	// bind to scrolll event
	var jumpToTopTimer = null;
	jQuery( window ).scroll( function() {
		clearTimeout( jumpToTopTimer );
		jumpToTopTimer = setTimeout( jumpToTopRefresh, 150 );
	} );
	var jumpToTopRefresh = function() {
		hideShowTbJumpToTop();
	};
	</script>
		<div id="wp-auth-check-wrap" class="hidden">
	<div id="wp-auth-check-bg"></div>
	<div id="wp-auth-check">
	<div class="wp-auth-check-close" tabindex="0" title="Fermer"></div>
			<div id="wp-auth-check-form" data-src="https://juniorp15.wordpress.com/wp-login.php?interim-login=1"></div>
			<div class="wp-auth-fallback">
		<p><b class="wp-auth-fallback-expired" tabindex="0">La session a expiré</b></p>
		<p><a href="https://juniorp15.wordpress.com/wp-login.php" target="_blank">Veuillez vous reconnecter.</a>
		La page de connexion s&rsquo;ouvrira dans une nouvelle fenêtre. Après vous être connecté, vous pourrez la fermer et revenir à cette page.</p>
	</div>
	</div>
	</div>
	<link rel='stylesheet' id='screen-css-0' href='https://s1.wp.com/wp-content/mu-plugins/thx/wpcom-thx.css?m=1389987573g' type='text/css' media='screen' />
<script type='text/javascript'>
/* <![CDATA[ */
var commonL10n = {"warnDelete":"Vous \u00eates sur le point de supprimer d\u00e9finitivement les \u00e9l\u00e9ments s\u00e9lectionn\u00e9s.\n  \u00ab Annuler \u00bb pour abandonner, \u00ab OK \u00bb pour les supprimer.","dismiss":"Ignorer cet avertissement."};
var commonL10n = {"warnDelete":"Vous \u00eates sur le point de supprimer d\u00e9finitivement les \u00e9l\u00e9ments s\u00e9lectionn\u00e9s.\n  \u00ab Annuler \u00bb pour abandonner, \u00ab OK \u00bb pour les supprimer.","dismiss":"Ignorer cet avertissement."};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var thickboxL10n = {"next":"Suiv.\u00a0>","prev":"<\u00a0Pr\u00e9c.","image":"Image","of":"sur","close":"Fermer","noiframes":"Cette fonctionnalit\u00e9 requiert des iframes. Les iframes sont d\u00e9sactiv\u00e9es sur votre navigateur, ou alors il ne les accepte pas.","loadingAnimation":"https:\/\/s1.wp.com\/wp-includes\/js\/thickbox\/loadingAnimation.gif"};
var thickboxL10n = {"next":"Suiv.\u00a0>","prev":"<\u00a0Pr\u00e9c.","image":"Image","of":"sur","close":"Fermer","noiframes":"Cette fonctionnalit\u00e9 requiert des iframes. Les iframes sont d\u00e9sactiv\u00e9es sur votre navigateur, ou alors il ne les accepte pas.","loadingAnimation":"https:\/\/s1.wp.com\/wp-includes\/js\/thickbox\/loadingAnimation.gif"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var _wpUtilSettings = {"ajax":{"url":"\/wp-admin\/admin-ajax.php"}};
var _wpUtilSettings = {"ajax":{"url":"\/wp-admin\/admin-ajax.php"}};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var _wpThemeSettings = {"themes":[{"id":"pub\/sketch","name":"Sketch","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sketch\/screenshot.png?w=434"],"description":"A clean, responsive portfolio theme with options for a custom site logo, a featured content slider, and lots of room to share your work.","author":"WordPress.com","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">WordPress.com<\/a>","version":"1.1.5-wpcom","tags":"art, photography, portfolio, clean, minimal, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mod\u00e8le pleine largeur, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, artwork, Photoblogging, Curseur d'article, D\u00e9filement Infini, Mise en page fixe, Mise en page adaptable, site-logo, Images \u00e0 la Une","parent":false,"active":true,"trendingRank":64,"popularityRank":26,"launchDate":"2014-08-12","demoUrl":"https:\/\/sketchdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsketch&amp;_wpnonce=c13558e41b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsketch","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/independent-publisher","name":"Independent Publisher","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/independent-publisher\/screenshot.png?w=434"],"description":"Beautiful reader-focused theme with a clean and responsive layout, ideal for personal bloggers. It has great readability with a large font, and also provides full width post cover images, which are perfect to showcase your content.","author":"Raam Dev","authorAndUri":"<a href=\"http:\/\/raamdev.com\/\">Raam Dev<\/a>","version":"1.0.1-wpcom","tags":"Vert, Blanc, Clair, Mise en page adaptable, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":1,"popularityRank":288,"launchDate":"2015-08-12","demoUrl":"https:\/\/independentpublisherdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Findependent-publisher&amp;_wpnonce=6908cb3aa0","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Findependent-publisher","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/colinear","name":"Colinear","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/colinear\/screenshot.png?w=434"],"description":"Colinear &#8212; our update to the older Coraline &#8212; is a squeaky-clean theme featuring a custom menu, header, background, and layout options. Colinear supports featured images and six widget areas &#8212; up to three each in the sidebar and footer. Primarily designed for magazine-style sites, Colinear is a flexible theme that suits any personal blog, or content-rich site.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.0-wpcom","tags":"Noir, Bleu, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, fashion, food, journal, magazine, news, bright, clean, conservative, elegant, Clair, minimal, modern, simple","parent":false,"active":false,"trendingRank":2,"popularityRank":361,"launchDate":"2015-08-27","demoUrl":"https:\/\/colineardemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcolinear&amp;_wpnonce=0477230b00","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcolinear","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/paulie","name":"Paulie","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/paulie\/screenshot.png?w=434"],"description":"Paulie is a simple, clean and elegant WordPress blog theme that sports a unique and beautiful design. Perfect for people that just want to spread their stories in an easy way in WordPress.com.","author":"SiloCreativo","authorAndUri":"<a href=\"http:\/\/www.silocreativo.com\">SiloCreativo<\/a>","version":"1.1.1","tags":"Blanc, Noir, Clair, Une colonne, Deux colonnes, Images \u00e0 la Une, Mise en page adaptable, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Article mis en avant, \u00c9diteur de style, Support des langues RTL","parent":false,"active":false,"trendingRank":3,"popularityRank":338,"launchDate":"2015-08-25","demoUrl":"https:\/\/pauliedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpaulie&amp;_wpnonce=0026281ea1","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpaulie","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/paulie&#038;ref=themesphp&#038;_wpnonce=0026281ea1"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"premium\/exhibit","name":"Exhibit","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/exhibit\/screenshot.png?w=434"],"description":"Exhibit is the perfect theme for businesses big and small to exhibit their work. Acting as both a portfolio and a blog Exhibit allows you to show off your projects, and to keep your customers informed.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.0.3","tags":"Clair, Gris, Rouge, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, business, craft, design, photography, portfolio, clean, conservative, contemporary, formal, Clair, modern","parent":false,"active":false,"trendingRank":4,"popularityRank":353,"launchDate":"2015-08-18","demoUrl":"https:\/\/exhibitdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fexhibit&amp;_wpnonce=894ed5665a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fexhibit","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/exhibit&#038;ref=themesphp&#038;_wpnonce=894ed5665a"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/blask","name":"Blask","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/blask\/screenshot.png?w=434"],"description":"Blask is a modern portfolio theme focused on showcasing your work in a clean and minimal way.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/wordpress.com\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"art, design, portfolio, clean, modern, Clair, Gris, Blanc, two-column, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, site-logo, Menu personnalis\u00e9, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, professional, D\u00e9filement Infini, Mise en page adaptable, threaded-comments","parent":false,"active":false,"trendingRank":5,"popularityRank":335,"launchDate":"2015-08-04","demoUrl":"https:\/\/blaskdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fblask&amp;_wpnonce=a82ca99499","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fblask","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/huesos","name":"Huesos","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/huesos\/screenshot.png?w=434"],"description":"Huesos (Spanish for bones), as its name suggests, is a straightforward, content-focused theme built to provide the foundation for your online presence.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"1.2.0","tags":"Blanc, Clair, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, music, portfolio, video, clean, conservative, formal, Clair, minimal, simple","parent":false,"active":false,"trendingRank":6,"popularityRank":369,"launchDate":"2015-08-18","demoUrl":"https:\/\/huesosdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fhuesos&amp;_wpnonce=f766bbf2d9","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fhuesos","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/huesos&#038;ref=themesphp&#038;_wpnonce=f766bbf2d9"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/blink","name":"Blink","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/blink\/screenshot.png?w=434"],"description":"A beautiful blogging theme for those who have more to say.","author":"Codestag","authorAndUri":"<a href=\"https:\/\/codestag.com\/\">Codestag<\/a>","version":"1.0.0","tags":"Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Photoblogging, site-logo, Article mis en avant, threaded-comments, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":7,"popularityRank":269,"launchDate":"2015-07-30","demoUrl":"https:\/\/blinkdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fblink&amp;_wpnonce=47f2b99ce2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fblink","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/blink&#038;ref=themesphp&#038;_wpnonce=47f2b99ce2"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>55","purchased":false}},{"id":"pub\/lovecraft","name":"Lovecraft","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/lovecraft\/screenshot.png?w=434"],"description":"Lovecraft is a beautiful two-column theme for bloggers. It features a responsive design, great typography, a full-width header image (which is replaced with the post thumbnail on single posts\/pages), custom logo support, editor style support, and a full-width template.","author":"Anders Noren","authorAndUri":"<a href=\"http:\/\/www.andersnoren.se\">Anders Noren<\/a>","version":"1.15-wpcom","tags":"Gris, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me, Support des langues RTL, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, site-logo, blog, journal, conservative, elegant, Clair, professional, sophisticated","parent":false,"active":false,"trendingRank":8,"popularityRank":229,"launchDate":"2015-07-21","demoUrl":"https:\/\/lovecraftdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Flovecraft&amp;_wpnonce=cf211c4584","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Flovecraft","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/maisha","name":"Maisha","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/maisha\/screenshot.png?w=434"],"description":"Maisha is a versatile, easy-to-use theme inspired by beautiful &laquo;&nbsp;Virunga&nbsp;&raquo; movie. It offers variety of customization options, like six different blog layouts, two header layouts and five beautiful page templates. This opens tons of possibilities to build sites thatrange from a non-profit\/charity type sites to the premium blog sites and more. Maisha is fully responsive and will nicely adapt to any screen size while keeping readers focused on the most important, your content.","author":"Anariel Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/anariel-design\/\">Anariel Design<\/a>","version":"1.0","tags":"Noir, Orange, Blanc, Gris, Sombre, Clair, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, threaded-comments","parent":false,"active":false,"trendingRank":9,"popularityRank":316,"launchDate":"2015-07-30","demoUrl":"https:\/\/maishademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmaisha&amp;_wpnonce=48cff94dd0","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmaisha","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/maisha&#038;ref=themesphp&#038;_wpnonce=48cff94dd0"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>89","purchased":false}},{"id":"pub\/publication","name":"Publication","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/publication\/screenshot.png?w=434"],"description":"Publication is an elegant blog and magazine theme that features full-screen Featured Images. It\u2019s perfect for sites about fashion, food, travel, or design. With balanced typography, colors, and attention to detail, Publication helps you create visually stunning posts.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.2-wpcom","tags":"Noir, Orange, Blanc, Sombre, Clair, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, collaboration, food, gaming, Vacances, journal, magazine, news, clean, contemporary, elegant, geometric, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":10,"popularityRank":344,"launchDate":"2015-07-22","demoUrl":"https:\/\/publicationdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fpublication&amp;_wpnonce=037c9ac45f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fpublication","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/appetite","name":"Appetite","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/appetite\/screenshot.png?w=434"],"description":"Appetite is a clean, flexible and fully responsive WordPress theme with special features for restaurants and cafes. Also, this theme can be used for any other business sites.","author":"Tasko","authorAndUri":"<a href=\"http:\/\/tdwp.us\/\">Tasko<\/a>","version":"1.0","tags":"Noir, Mise en page adaptable, D\u00e9j\u00e0 accessible, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":11,"popularityRank":322,"launchDate":"2015-07-22","demoUrl":"https:\/\/appetitedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fappetite&amp;_wpnonce=5ce581b027","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fappetite","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/appetite&#038;ref=themesphp&#038;_wpnonce=5ce581b027"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>150","purchased":false}},{"id":"pub\/franklin","name":"Franklin","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/franklin\/screenshot.png?w=434"],"description":"Lightweight theme with a responsive layout designed for bloggers. Theme consists of a 2 column layout with a widget area on the right, as well as a widgetized footer.","author":"Michael Burrows","authorAndUri":"<a href=\"http:\/\/www.wpmultiverse.com\/\">Michael Burrows<\/a>","version":"1.0.1-wpcom","tags":"Vert, Blanc, Clair, Mise en page adaptable, Deux colonnes, Colonne lat\u00e9rale droite, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":12,"popularityRank":368,"launchDate":"2015-08-27","demoUrl":"https:\/\/franklindemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ffranklin&amp;_wpnonce=b140354a2b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ffranklin","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/libretto","name":"Libretto","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/libretto\/screenshot.png?w=434"],"description":"Libretto is a responsive one-column theme with classic styling and careful typographic details. It\u2019s ideally suited to showcasing longform writing interspersed with beautiful images and inspiring quotes.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.2-wpcom","tags":"Gris, Rouge, Argent, Blanc, Clair, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, design, design, fashion, food, hotel, journal, lifestream, Photoblogging, photography, clean, conservative, elegant, faded, formal, Clair, minimal, simple, sophisticated, traditional","parent":false,"active":false,"trendingRank":13,"popularityRank":327,"launchDate":"2015-07-16","demoUrl":"https:\/\/librettodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Flibretto&amp;_wpnonce=e1daaa0742","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Flibretto","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/edda","name":"Edda","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/edda\/screenshot.png?w=434"],"description":"With room for your big, beautiful photos and displaying elegant, classical type, Edda is built for dedicated writers and bloggers like you to showcase your work.","author":"Mel Choyce","authorAndUri":"<a href=\"http:\/\/choycedesign.com\">Mel Choyce<\/a>","version":"1.0.5-wpcom","tags":"Photoblogging, photography, blog, journal, lifestream, tumblelog, Sombre, formal, elegant, D\u00e9filement Infini, site-logo, Noir, Jaune, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page adaptable","parent":false,"active":false,"trendingRank":14,"popularityRank":340,"launchDate":"2015-07-09","demoUrl":"https:\/\/eddademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fedda&amp;_wpnonce=a589503be6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fedda","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/monet","name":"Monet","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/monet\/screenshot.png?w=434"],"description":"Monet is a delicate responsive portfolio theme targeted at photographers and other creatives. With crisp typography Monet is easy on the eye.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.3","tags":"Gris, Blanc, Clair, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, craft, design, food, gaming, Vacances, music, nature, outdoors, Photoblogging, photography, portfolio, scrapbooking, travel, tumblelog, wedding, artistic, bright, clean, conservative, contemporary, elegant, Clair, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":15,"popularityRank":304,"launchDate":"2015-06-30","demoUrl":"https:\/\/monetdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmonet&amp;_wpnonce=f4eb20142b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmonet","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/monet&#038;ref=themesphp&#038;_wpnonce=f4eb20142b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/p2-breathe","name":"P2","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/p2-breathe\/screenshot.png?w=434"],"description":"Communication is oxygen. P2 &laquo;&nbsp;Breathe&nbsp;&raquo; is the first o2-enabled theme.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Bleu, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Page d&rsquo;accueil personnalis\u00e9e, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, collaboration, lifestream, clean","parent":false,"active":false,"trendingRank":16,"popularityRank":365,"launchDate":"2015-06-18","demoUrl":"https:\/\/p2breathedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fp2-breathe&amp;_wpnonce=3197d50eeb","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fp2-breathe","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/mellow","name":"Mellow","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/mellow\/screenshot.png?w=434"],"description":"Un th\u00e8me portfolio minimaliste.","author":"ThemeTrust","authorAndUri":"<a href=\"https:\/\/themetrust.com\">ThemeTrust<\/a>","version":"1.0.4 - WPCom","tags":"business, portfolio, conservative, modern, professional, Noir, Blanc, Clair, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, site-logo, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page adaptable","parent":false,"active":false,"trendingRank":17,"popularityRank":351,"launchDate":"2015-06-30","demoUrl":"https:\/\/mellowdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmellow&amp;_wpnonce=982e1a54af","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmellow","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/mellow&#038;ref=themesphp&#038;_wpnonce=982e1a54af"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/libre","name":"Libre","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/libre\/screenshot.png?w=434"],"description":"A stylish, classic look for your personal blog or long-form writing site. The main navigation bar stays fixed to the top while your visitors read, keeping your most important content at hand, while three footer widget areas give your secondary content a comfortable home.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.3-wpcom","tags":"Clair, Noir, Blanc, Colonne lat\u00e9rale droite, Deux colonnes, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, \u00c9diteur de style, Mod\u00e8le pleine largeur, Mise en page adaptable, D\u00e9j\u00e0 accessible, D\u00e9filement Infini, site-logo, clean, minimal, conservative, traditional, professional, simple, blog, journal","parent":false,"active":false,"trendingRank":18,"popularityRank":305,"launchDate":"2015-07-01","demoUrl":"https:\/\/libredemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Flibre&amp;_wpnonce=3afd800e10","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Flibre","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/baskerville","name":"Baskerville","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/baskerville\/screenshot.png?w=434"],"description":"Baskerville is a dynamic grid-based theme for curators. It&rsquo;s the perfect way to showcase your posts, videos, images and galleries, and share your favorite quotes and links. Features responsive design, retina-ready assets, full-width header image, support for all post formats, site logo support, custom Dribbble widget, three page templates (including a contributors template), editor styling, and translation-ready code.","author":"Anders Nor\u00e9n","authorAndUri":"<a href=\"http:\/\/www.andersnoren.se\">Anders Nor\u00e9n<\/a>","version":"1.15-wpcom","tags":"Noir, Sombre, Blanc, Vert, Deux colonnes, Mise en page fluide, Mise en page adaptable, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, \u00c9diteur de style","parent":false,"active":false,"trendingRank":19,"popularityRank":164,"launchDate":"2015-07-07","demoUrl":"https:\/\/baskervilledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbaskerville&amp;_wpnonce=9eb79d2325","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbaskerville","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/argent","name":"Argent","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/argent\/screenshot.png?w=434"],"description":"Argent is a clean and modern portfolio theme, geared towards creative professionals like designers, artists, and photographers. With its simple homepage template featuring portfolio projects, Argent aims to draw viewers right at what matters most: your wonderful work.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.5-wpcom","tags":"business, portfolio, clean, modern, Noir, Gris, Blanc, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Sombre, industrial, professional, Images \u00e0 la Une, D\u00e9filement Infini, Mise en page adaptable, threaded-comments","parent":false,"active":false,"trendingRank":20,"popularityRank":250,"launchDate":"2015-06-17","demoUrl":"https:\/\/argentdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fargent&amp;_wpnonce=8c745467c5","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fargent","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/christopher","name":"Christopher","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/christopher\/screenshot.png?w=434"],"description":"christopher is a clean and responsive WordPress theme created for creative bloggers and authors to build an awesome magazine or personal blog. Topics such as photography, fashion, food, traveling to hobbies, crafts, tech or DIY will suit well.","author":"SiloCreativo","authorAndUri":"<a href=\"http:\/\/www.silocreativo.com\">SiloCreativo<\/a>","version":"1.0.4","tags":"Blanc, Noir, Clair, Une colonne, Deux colonnes, Mise en page adaptable, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Pr\u00eat \u00e0 \u00eatre traduit, Images \u00e0 la Une, \u00c9diteur de style, Support des langues RTL","parent":false,"active":false,"trendingRank":21,"popularityRank":321,"launchDate":"2015-07-02","demoUrl":"https:\/\/christopherdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fchristopher&amp;_wpnonce=7dd6f70139","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fchristopher","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/christopher&#038;ref=themesphp&#038;_wpnonce=7dd6f70139"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/demand","name":"Demand","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/demand\/screenshot.png?w=434"],"description":"A video centric theme with a unique content carousel to make your videos stand out and accessible.","author":"Press75","authorAndUri":"<a href=\"http:\/\/www.press75.com\/\">Press75<\/a>","version":"1.0","tags":"Dark, Gray, Two Columns, One Column, Responsive Layout, Custom Background, Custom Header, Custom Menu, Post Formats, Featured Images, Featured Image Header","parent":false,"active":false,"trendingRank":22,"popularityRank":328,"launchDate":"2015-05-27","demoUrl":"https:\/\/demanddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fdemand&amp;_wpnonce=141959cf70","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fdemand","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/demand&#038;ref=themesphp&#038;_wpnonce=141959cf70"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/gateway","name":"Gateway","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/gateway\/screenshot.png?w=434"],"description":"Gateway est un m\u00e9lange parfait de classe et d\u2019\u00e9l\u00e9gance. D\u2019une facture visuelle classique, il vous permet de personnaliser vos contenus. Renforcez l\u2019image de votre marque en ajoutant votre logo et une image d\u2019en-t\u00eate audacieuse et attrayante. Mettez en valeur vos meilleurs articles ou une vid\u00e9o gr\u00e2ce \u00e0 un mod\u00e8le sp\u00e9cial de page d&rsquo;accueil.","author":"Rescue Themes","authorAndUri":"<a href=\"https:\/\/rescuethemes.com\">Rescue Themes<\/a>","version":"1.1.3-wpcom","tags":"art, artwork, blog, business, design, conservative, elegant, professional, traditional, site-logo, D\u00e9filement Infini, Clair, Blanc, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Images \u00e0 la Une, Options du th\u00e8me, En-t\u00eate flexible, Menu personnalis\u00e9, Couleurs personnalis\u00e9es, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, Mod\u00e8le pleine largeur, Article mis en avant, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9","parent":false,"active":false,"trendingRank":23,"popularityRank":142,"launchDate":"2015-06-01","demoUrl":"https:\/\/gatewaydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fgateway&amp;_wpnonce=48542eb4cf","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fgateway","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/romero","name":"Romero","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/romero\/screenshot.png?w=434"],"description":"Romero is a WordPress theme designed for visual magazine sites. With full width featured images making your featured blog posts really stand out, it&rsquo;s ideal for video game sites, motoring magazines, and other topics that have large vibrant imagery.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.2.3","tags":"Bleu, Gris, Blanc, Clair, Une colonne, Deux colonnes, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, artwork, design, gaming, journal, magazine, music, news, sports, bright, clean, contemporary, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":24,"popularityRank":323,"launchDate":"2015-06-04","demoUrl":"https:\/\/romerodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fromero&amp;_wpnonce=652b0efd26","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fromero","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/romero&#038;ref=themesphp&#038;_wpnonce=652b0efd26"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/apostrophe","name":"Apostrophe","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/apostrophe\/screenshot.png?w=434"],"description":"Un th\u00e8me de magazine clair et pratique","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.6-wpcom","tags":"Noir, Bleu, Gris, Blanc, Clair, Deux colonnes, Une colonne, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, collaboration, design, fashion, food, magazine, travel, bright, clean, contemporary, Clair, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":25,"popularityRank":300,"launchDate":"2015-05-21","demoUrl":"https:\/\/apostrophedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fapostrophe&amp;_wpnonce=86cf0ee35c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fapostrophe","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/twentyten","name":"Twenty Ten","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/twentyten\/screenshot.png?w=434"],"description":"Le th\u00e8me de WordPress pour 2010. Il est beau, personnalisable, simple et lisible. Appropriez-le-vous gr\u00e2ce en personnalisant son menu, son image d&rsquo;en-t\u00eate et son image de fond. Twenty Ten dispose de six zones de widgets (deux dans la barre lat\u00e9rale, quatre en pied de page), et peut exploiter vos images de Une (minitatures pour galeries, et image d&rsquo;en-t\u00eate personnalis\u00e9 pour les articles et pages). Il int\u00e8gre une feuille de style pour l&rsquo;impression et pour l&rsquo;\u00e9diteur visuel, un style sp\u00e9cial pour les articles des cat\u00e9gories &laquo;&nbsp;Apart\u00e9s&nbsp;&raquo; et &laquo;&nbsp;Galerie&nbsp;&raquo;, et peut fonctionner sous la forme d&rsquo;une colonne seule, en enlevant la barre lat\u00e9rale.","author":"the WordPress team","authorAndUri":"<a href=\"https:\/\/wordpress.org\/\">the WordPress team<\/a>","version":"1.9-wpcom","tags":"Noir, Bleu, Blanc, Deux colonnes, Mise en page fixe, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Microformats, Support des langues RTL, \u00c9diteur de style, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, Format d&rsquo;article, En-t\u00eate flexible, D\u00e9filement Infini, blog, business, lifestream, bright, clean, elegant, formal, Clair, minimal, modern","parent":false,"active":false,"trendingRank":26,"popularityRank":1,"launchDate":"2010-04-26","demoUrl":"https:\/\/twentytendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftwentyten&amp;_wpnonce=6033710e84","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftwentyten","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/coherent","name":"Coherent","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/coherent\/screenshot.png?w=434"],"description":"Coherent is a simple, structured theme with full screen featured images and a sliding panel sidebar.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/wordpress.com\/themes\">Automattic<\/a>","version":"1.0.5-wpcom","tags":"Bleu, Blanc, Clair, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, journal, news, Photoblogging, photography, travel, clean, contemporary, elegant, Clair, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":27,"popularityRank":335,"launchDate":"2015-04-22","demoUrl":"https:\/\/coherentdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcoherent&amp;_wpnonce=589eb772dc","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcoherent","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/boardwalk","name":"Boardwalk","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/boardwalk\/screenshot.png?w=434"],"description":"Un th\u00e8me minimaliste avec un d\u00e9filement horizontal.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.6-wpcom","tags":"Clair, Gris, Vert, Blanc, Une colonne, Mise en page adaptable, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, design, fashion, food, Vacances, journal, nature, outdoors, Photoblogging, photography, travel, video, clean, conservative, contemporary, elegant, formal, minimal, modern, simple, sophisticated","parent":false,"active":false,"trendingRank":28,"popularityRank":28,"launchDate":"2015-01-08","demoUrl":"https:\/\/boardwalkdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fboardwalk&amp;_wpnonce=4c7477413a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fboardwalk","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/cerauno","name":"Cerauno","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/cerauno\/screenshot.png?w=434"],"description":"Cerauno is a polished, user-friendly magazine theme with plenty of customizable features. Add secondary content in up to five widget areas, brand your content with a Site Logo or Custom Header, and add Featured Images to grab your readers\u2019 attention.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"magazine, news, business, clean, conservative, Clair, minimal, traditional, Bleu, Blanc, Trois colonnes, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, site-logo, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page adaptable","parent":false,"active":false,"trendingRank":29,"popularityRank":275,"launchDate":"2015-06-10","demoUrl":"https:\/\/ceraunodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcerauno&amp;_wpnonce=38f19ba9e0","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcerauno","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/curator","name":"Curator","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/curator\/screenshot.png?w=434"],"description":"A theme for collecting internet things.","author":"ThemeZilla","authorAndUri":"<a href=\"http:\/\/www.themezilla.com\">ThemeZilla<\/a>","version":"1.0","tags":"Blanc, Rouge, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Microformats, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":30,"popularityRank":189,"launchDate":"2015-04-14","demoUrl":"https:\/\/curatordemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcurator&amp;_wpnonce=d705ff5c81","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcurator","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/curator&#038;ref=themesphp&#038;_wpnonce=d705ff5c81"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/obsidian","name":"Obsidian","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/obsidian\/screenshot.png?w=434"],"description":"The Obsidian theme, like the naturally occurring volcanic glass it&rsquo;s named after, possesses an inherent allure that&rsquo;s stylish in appearance and practical in purpose.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"1.0.5","tags":"Noir, Gris, Sombre, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Support des langues RTL, site-logo, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, business, fashion, music, portfolio, video, clean, contemporary, Sombre, elagant, futuristic, glamorous, minimal, modern, professional, sophisticated","parent":false,"active":false,"trendingRank":31,"popularityRank":109,"launchDate":"2015-05-20","demoUrl":"https:\/\/obsidiandemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fobsidian&amp;_wpnonce=8e49d956fe","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fobsidian","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/obsidian&#038;ref=themesphp&#038;_wpnonce=8e49d956fe"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/canard","name":"Canard","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/canard\/screenshot.png?w=434"],"description":"A flexible and versatile theme perfect for magazines, news sites, and blogs. It lets you highlight specific articles on the homepage and balances readability with a powerful use of photography \u2014 all in a layout that works on any device.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.4-wpcom","tags":"Rouge, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, collaboration, food, gaming, journal, magazine, news, clean, contemporary, elegant, geometric, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":32,"popularityRank":281,"launchDate":"2015-05-28","demoUrl":"https:\/\/canarddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcanard&amp;_wpnonce=afa71da3ea","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcanard","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/snaps","name":"Snaps","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/snaps\/screenshot.png?w=434"],"description":"A portfolio theme perfect for showcasing portrait images and galleries.","author":"Graph Paper Press","authorAndUri":"<a href=\"http:\/\/graphpaperpress.com\">Graph Paper Press<\/a>","version":"1.0.3-wpcom","tags":"Noir, Gris, Blanc, Sombre, Clair, Une colonne, Deux colonnes, Quatre colonnes, responsive-width, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Format d&rsquo;article, Pr\u00eat \u00e0 \u00eatre traduit, Photoblogging, photography, minimal, simple","parent":false,"active":false,"trendingRank":33,"popularityRank":217,"launchDate":"2015-05-28","demoUrl":"https:\/\/snapsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsnaps&amp;_wpnonce=7443c40b48","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsnaps","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/encore","name":"Encore","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/encore\/screenshot.png?w=434"],"description":"Encore takes a simple and organized approach to presenting your content with understated charm and undeniable appeal. You can display your music and videos in unique, gridded archives; showcase a playlist in a distinct, site-wide player; and much more. Deliver what your fans want with Encore.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"1.0.1","tags":"Ocre, Une colonne, Deux colonnes, Mise en page adaptable, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Microformats, Support des langues RTL, site-logo, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, education, journal, music, scrapbooking, video, wedding, clean, earthy, formal, Clair, minimal, playful, professional, retro, simple, tech","parent":false,"active":false,"trendingRank":35,"popularityRank":302,"launchDate":"2015-05-06","demoUrl":"https:\/\/encoredemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fencore&amp;_wpnonce=1fbf0c9910","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fencore","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/encore&#038;ref=themesphp&#038;_wpnonce=1fbf0c9910"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"premium\/atlas","name":"Atlas","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/atlas\/screenshot.png?w=434"],"description":"<code>Atlas<\/code> is a clean, crisp blog theme designed with readability in mind. Its subtle animations are there to delight your readers without distracting from your content or images.","author":"Nudge Themes","authorAndUri":"<a href=\"http:\/\/nudgethemes.com\/\">Nudge Themes<\/a>","version":"1.1.4","tags":"Blanc, Clair, art, artwork, blog, craft, design, fashion, journal, Photoblogging, photography, scrapbooking, artistic, clean, minimal, modern, simple, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fluide, Mise en page adaptable, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":43,"popularityRank":298,"launchDate":"2015-05-12","demoUrl":"https:\/\/atlasdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fatlas&amp;_wpnonce=b5b9732ded","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fatlas","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/atlas&#038;ref=themesphp&#038;_wpnonce=b5b9732ded"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"pub\/twentytwelve","name":"Twenty Twelve","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/twentytwelve\/screenshot.png?w=434"],"description":"Le th\u00e8me 2012 pour WordPress est extr\u00eamement flexible et s&rsquo;affiche impeccablement sur tout appareil. Il offre un mod\u00e8le de page d&rsquo;accueil avec ses propres widgets, une police d&rsquo;affichage en option, la mise en style des formats de publications pour les vues normales et en index, ainsi qu&rsquo;un mod\u00e8le facultatif de page sans sidebar. Rendez-le \u00e0 votre go\u00fbt avec un menu personnalis\u00e9, l&rsquo;image d&rsquo;en-t\u00eate qui vous plaira et un fond \u00e9galement choisi par vous.","author":"the WordPress team","authorAndUri":"<a href=\"https:\/\/wordpress.org\/\">the WordPress team<\/a>","version":"1.7","tags":"Clair, Gris, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, blog, business, journal, lifestream, professional, bright, clean, contemporary, elegant, minimal, modern, photography, simple, tumblelog","parent":false,"active":false,"trendingRank":34,"popularityRank":2,"launchDate":"2012-08-28","demoUrl":"https:\/\/twentytwelvedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftwentytwelve&amp;_wpnonce=8b7d41c8b5","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftwentytwelve","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/penscratch","name":"Penscratch","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/penscratch\/screenshot.png?w=434"],"description":"A clean, responsive writing theme with support for site logos, featured images, fancy pull quotes, and more.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.2-wpcom","tags":"blog, education, journal, school, Clair, simple, Gris, Blanc, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, \u00c9diteur de style, Format d&rsquo;article, clean, minimal, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mod\u00e8le pleine largeur, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Mise en page fixe, Mise en page adaptable, site-logo","parent":false,"active":false,"trendingRank":37,"popularityRank":22,"launchDate":"2014-10-15","demoUrl":"https:\/\/penscratchdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fpenscratch&amp;_wpnonce=4f53ee048e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fpenscratch","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/ecto","name":"Ecto","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/ecto\/screenshot.png?w=434"],"description":"Meet Ecto, a theme with a light color scheme, bold typography, and full-width images that draw readers straight to your content. Use it for blogs of all kinds.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/automattic.com\/\">Automattic<\/a>","version":"1.1.1-wpcom","tags":"Gris, Blanc, Clair, Une colonne, Deux colonnes, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, Photoblogging, clean, modern","parent":false,"active":false,"trendingRank":38,"popularityRank":260,"launchDate":"2015-04-23","demoUrl":"https:\/\/ectodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fecto&amp;_wpnonce=ada0397ee9","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fecto","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/edin","name":"Edin","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/edin\/screenshot.png?w=434"],"description":"Edin est un th\u00e8me moderne et adapt\u00e9 \u00e0 toutes les tailles de navigateurs, id\u00e9al pour les sites professionnels. Ce th\u00e8me vous aidera \u00e0 cr\u00e9er une forte et belle pr\u00e9sence en ligne pour votre entreprise.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.2-wpcom","tags":"Bleu, Gris, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, collaboration, design, food, hotel, portfolio, real-estate, school, bright, clean, conservative, elegant, formal, Clair, minimal, modern, professional, simple, sophisticated, traditional","parent":false,"active":false,"trendingRank":39,"popularityRank":9,"launchDate":"2014-07-31","demoUrl":"https:\/\/edindemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fedin&amp;_wpnonce=f3a45471f8","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fedin","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/twentyfourteen","name":"Twenty Fourteen","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/twentyfourteen\/screenshot.png?w=434"],"description":"En 2014, notre th\u00e8me par d\u00e9faut vous permet de cr\u00e9er un site magazine qui s&rsquo;adapte \u00e0 tous les \u00e9crans avec superbe design moderne. Mettez en avant votre contenu pr\u00e9f\u00e9r\u00e9 sur la page d&rsquo;accueil gr\u00e2ce \u00e0 une grille ou un diaporama. Utilisez les trois zones de widget pour personnaliser votre site web, et modifiez la mise en page de votre contenu gr\u00e2ce \u00e0 des mod\u00e8les pleine page et une page de contributeurs pour mettre vos auteurs en avant. Cr\u00e9er un site magazine avec WordPress n&rsquo;a jamais \u00e9t\u00e9 aussi facile.","author":"the WordPress team","authorAndUri":"<a href=\"https:\/\/wordpress.org\/\">the WordPress team<\/a>","version":"1.4","tags":"Noir, Vert, Blanc, Clair, Sombre, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9j\u00e0 accessible, Mise en page adaptable, D\u00e9filement Infini, Curseur d'article, design, food, journal, magazine, news, photography, portfolio, clean, contemporary, Sombre, elegant, modern, professional, sophisticated","parent":false,"active":false,"trendingRank":41,"popularityRank":4,"launchDate":"2013-11-20","demoUrl":"https:\/\/twentyfourteendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftwentyfourteen&amp;_wpnonce=9391a8d237","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftwentyfourteen","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/chateau","name":"Chateau","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/chateau\/screenshot.png?w=434"],"description":"Chateau est un th&egrave;me &eacute;pur&eacute; et minimaliste d&eacute;clin&eacute; en deux versions: clair ou sombre. Il dispose de l&rsquo;option d&rsquo;arri&egrave;re-plan, &agrave; personnaliser par l&rsquo;envoi d&rsquo;une image ou le choix d&rsquo;une couleur de fond, et poss&egrave;de six zones widget, dont une zone lat&eacute;rale et cinq en pied de page.","author":"Ignacio Ricci","authorAndUri":"<a href=\"http:\/\/ignacioricci.com\">Ignacio Ricci<\/a>","version":"1.0.4-wpcom","tags":"Noir, Blanc, Rouge, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, journal, news, professional, clean, Sombre, elegant, Clair, minimal, simple, sophisticated, traditional, Format d&rsquo;article, En-t\u00eate flexible","parent":false,"active":false,"trendingRank":41,"popularityRank":3,"launchDate":"2011-07-07","demoUrl":"https:\/\/chateaudemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fchateau&amp;_wpnonce=e624232389","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fchateau","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/cubic","name":"Cubic","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/cubic\/screenshot.png?w=434"],"description":"Un th\u00e8me minimaliste et carr\u00e9.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.3-wpcom","tags":"Clair, Bleu, Gris, Blanc, Une colonne, Mise en page adaptable, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, design, fashion, food, Vacances, journal, nature, outdoors, Photoblogging, photography, travel, video, clean, conservative, contemporary, elegant, formal, minimal, modern, simple, sophisticated","parent":"Boardwalk","active":false,"trendingRank":42,"popularityRank":19,"launchDate":"2015-01-15","demoUrl":"https:\/\/cubicdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcubic&amp;_wpnonce=8f2d621955","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcubic","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/soho","name":"Soho","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/soho\/screenshot.png?w=434"],"description":"Th\u00e8me moderne adaptable.","author":"Viva Themes","authorAndUri":"<a href=\"http:\/\/www.vivathemes.com\">Viva Themes<\/a>","version":"2.0","tags":"Clair, Noir, Blanc, Deux colonnes, Mise en page fluide, Mise en page adaptable, Options du th\u00e8me, Curseur d'article, design, business, photography, modern, elegant, minimal, simple, clean, Menu personnalis\u00e9, Images \u00e0 la Une, art, craft, portfolio, travel, artistic, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, \u00c9diteur de style, Pr\u00eat \u00e0 \u00eatre traduit, sophisticated, D\u00e9filement Infini, site-logo, blog, Photoblogging, nature","parent":false,"active":false,"trendingRank":43,"popularityRank":214,"launchDate":"2015-05-20","demoUrl":"https:\/\/sohodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fsoho&amp;_wpnonce=74440b9a8e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fsoho","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/soho&#038;ref=themesphp&#038;_wpnonce=74440b9a8e"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"pub\/twentythirteen","name":"Twenty Thirteen","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/twentythirteen\/screenshot.png?w=434"],"description":"Le th\u00e8me de WordPress pour 2013 nous ram\u00e8ne au blog, avec un grand nombre de formats d&rsquo;article, chacun s&rsquo;affichant \u00e0 sa propre mani\u00e8re, en toute beaut\u00e9. Vous y trouverez de nombreux d\u00e9tails de mise en page, \u00e0 commencer par le jeu de couleurs vives et les images d&rsquo;en-t\u00eate assorties, une superbe typographie et de belles ic\u00f4nes, et une mise en page flexible qui fonctionne sur toutes les tailles d&rsquo;\u00e9crans, grands ou petits.","author":"the WordPress team","authorAndUri":"<a href=\"https:\/\/wordpress.org\/\">the WordPress team<\/a>","version":"1.5","tags":"Noir, Marron, Orange, Ocre, Blanc, Jaune, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9j\u00e0 accessible, D\u00e9filement Infini, blog, journal, lifestream, tumblelog, abstract, bright, clean, colorful, flamboyant, playful, vibrant","parent":false,"active":false,"trendingRank":44,"popularityRank":6,"launchDate":"2013-04-24","demoUrl":"https:\/\/twentythirteendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftwentythirteen&amp;_wpnonce=14939bcf5a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftwentythirteen","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/caldwell","name":"Caldwell","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/caldwell\/screenshot.png?w=434"],"description":"Caldwell is a straightforward, no-frills WordPress theme for the discerning small business. Highlight what makes your company unique with large featured images and front page featured content blocks.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"2.1.0","tags":"Clair, Violet, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, design, food, Photoblogging, travel, bright, clean, colorful, conservative, contemporary, elegant, formal, Clair, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":44,"popularityRank":307,"launchDate":"2015-04-01","demoUrl":"https:\/\/caldwelldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcaldwell&amp;_wpnonce=64c9a48166","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcaldwell","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/caldwell&#038;ref=themesphp&#038;_wpnonce=64c9a48166"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>29","purchased":false}},{"id":"pub\/ryu","name":"Ryu","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/ryu\/screenshot.png?w=434"],"description":"Ryu est un th\u00e8me \u00e9pur\u00e9 pour les blogs personnels. Sa police de grande taille le rend d\u2019une grande lisibilit\u00e9 et sa mise en page sur une colonne est parfaite pour afficher de grandes images. Des widgets facultatifs sont propos\u00e9s sur le volet sup\u00e9rieur, de m\u00eame que des liens vers les m\u00e9dias sociaux et un champ de recherche. La couleur d\u2019arri\u00e8re-plan d\u2019une publication avec image s\u2019adapte automatiquement \u00e0 l\u2019image t\u00e9l\u00e9charg\u00e9e dans le billet.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.4.5-wpcom","tags":"Noir, Blanc, Clair, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, announcement, art, blog, design, fashion, food, journal, Photoblogging, photography, tumblelog, artistic, bright, clean, colorful, conservative, elegant, formal, Clair, minimal, modern, simple, sophisticated, traditional","parent":false,"active":false,"trendingRank":46,"popularityRank":7,"launchDate":"2013-03-28","demoUrl":"https:\/\/ryudemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fryu&amp;_wpnonce=3c7c533191","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fryu","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/mood","name":"Mood","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/mood\/screenshot.png?w=434"],"description":"Mood is a business theme with positive vibe, equipped with custom front page template, portfolio support, full-width featured images, and much more. Featuring a warm color scheme, clean layouts, and bold typography, Mood will help you build an inviting business or portfolio site.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"business, blog, journal, photography, portfolio, clean, modern, Marron, Rose, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, sophisticated, contemporary, Images \u00e0 la Une, D\u00e9filement Infini, Mise en page adaptable, threaded-comments","parent":false,"active":false,"trendingRank":47,"popularityRank":277,"launchDate":"2015-05-12","demoUrl":"https:\/\/mooddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmood&amp;_wpnonce=7b2262bdf9","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmood","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/mood&#038;ref=themesphp&#038;_wpnonce=7b2262bdf9"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>65","purchased":false}},{"id":"pub\/twentyfifteen","name":"Twenty Fifteen","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/twentyfifteen\/screenshot.png?w=434"],"description":"Notre th\u00e8me par d\u00e9faut pour 2015 est pur, centr\u00e9 sur le blog et con\u00e7u pour \u00eatre clair. Le typographie simple et directe de Twenty Fifteen est lisible sur une grand vari\u00e9t\u00e9 de tailles d&rsquo;\u00e9crans, et adapt\u00e9e \u00e0 de nombreuses langues. Nous l&rsquo;avons con\u00e7u avec la m\u00e9thode &laquo;&nbsp;le mobile avant tout&nbsp;&raquo;, ce qui signifie que votre contenu a une place centrale, qu&rsquo;importe si le visiteur utilise un t\u00e9l\u00e9phone, une tablette, un ordinateur portable ou un ordinateur de bureau.","author":"the WordPress team","authorAndUri":"<a href=\"https:\/\/wordpress.org\/\">the WordPress team<\/a>","version":"1.2","tags":"Noir, Bleu, Gris, Rose, Violet, Blanc, Jaune, Sombre, Clair, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fixe, Mise en page adaptable, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":48,"popularityRank":10,"launchDate":"2014-12-10","demoUrl":"https:\/\/twentyfifteendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftwentyfifteen&amp;_wpnonce=940cbc193b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftwentyfifteen","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/huntt","name":"Huntt","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/huntt\/screenshot.png?w=434"],"description":"Huntt &#8211; a premium WordPress Blog\/Magazine theme, created for numerous purposes and one goal \u2013 to make your beautiful content stand out, like it should. Huntt is a beautiful minimalistic WordPress multipurpose theme, made to put visual oriented content in the first place, without unnecessary clutter and noise. It is ideal for blogs\/magazines from which the inspiration came from, with content related to photography, graphic design, fashion, art, architecture, interior design and other creative fields. Huntt can also be used for other purposes, such as an agency or personal portfolio.","author":"Themes Kingdom","authorAndUri":"<a href=\"http:\/\/www.themeskingdom.com\">Themes Kingdom<\/a>","version":"1.0","tags":"Mise en page adaptable, Colonne lat\u00e9rale droite, Gris, Blanc, Clair, Deux colonnes, Trois colonnes, Quatre colonnes, Photoblogging, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Pr\u00eat \u00e0 \u00eatre traduit, Article mis en avant, Format d&rsquo;article, Support des langues RTL, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es","parent":false,"active":false,"trendingRank":49,"popularityRank":273,"launchDate":"2015-06-09","demoUrl":"https:\/\/hunttdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fhuntt&amp;_wpnonce=fdd0c87985","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fhuntt","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/huntt&#038;ref=themesphp&#038;_wpnonce=fdd0c87985"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/afterlight","name":"Afterlight","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/afterlight\/screenshot.png?w=434"],"description":"Afterlight is a monochromatic blog theme with an option for a full-screen background image. Add your favorite background image or color to lend your personal flair.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.2-wpcom","tags":"Blanc, Sombre, Une colonne, Mise en page fixe, Mise en page adaptable, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, journal, lifestream, travel, clean, contemporary, Sombre, minimal, modern, simple","parent":false,"active":false,"trendingRank":50,"popularityRank":227,"launchDate":"2015-04-30","demoUrl":"https:\/\/afterlightdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fafterlight&amp;_wpnonce=64553dde81","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fafterlight","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/patch","name":"Patch","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/patch\/screenshot.png?w=434"],"description":"An algorithmic design experiment that cleverly imagines the best layout for your content. Patch brings unity and balance to your beautiful crafted diversity.","author":"PixelGrade","authorAndUri":"<a href=\"http:\/\/pixelgrade.com\">PixelGrade<\/a>","version":"1.0-wpcom","tags":"Clair, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Mise en page adaptable, Menu personnalis\u00e9, Images \u00e0 la Une, \u00c9diteur de style, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, lifestream, magazine, news, scrapbooking, video, bright, clean, bold, geometric, minimal, modern, smart, adaptive","parent":false,"active":false,"trendingRank":51,"popularityRank":138,"launchDate":"2015-04-08","demoUrl":"https:\/\/patchdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpatch&amp;_wpnonce=263cfa62a6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpatch","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/patch&#038;ref=themesphp&#038;_wpnonce=263cfa62a6"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"pub\/cols","name":"Cols","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/cols\/screenshot.png?w=434"],"description":"Cols is a theme that reads like a book. With a minimal column layout and eye soothing design, this design makes your content novel.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"Noir, Clair, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Format d&rsquo;article, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, blog, journal, clean, modern, Jaune","parent":false,"active":false,"trendingRank":52,"popularityRank":111,"launchDate":"2014-10-22","demoUrl":"https:\/\/colsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcols&amp;_wpnonce=ba71681adf","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcols","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/twentyeleven","name":"Twenty Eleven","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/twentyeleven\/screenshot.png?w=434"],"description":"Le th&egrave;me 2011 pour WordPress est sophistiqu&eacute;, l&eacute;ger et adaptable. Faites-le v&ocirc;tre en personnalisant menu, image d&rsquo;en-t&ecirc;te et fond, puis allez plus loin dans les options disponibles: choisissez votre jeu de couleurs (clair ou sombre), d&eacute;finissez la couleurs de vos liens, et profitez des trois options de mise en page disponibles. Twenty Eleven est &eacute;quip&eacute; notamment d&rsquo;un mod&egrave;le de page au format vitrine vous permettant d&rsquo;exposer en page d&rsquo;accueil votre meilleur contenu. D&eacute;couvrez sa grande vari&eacute;t&eacute; de zones r&eacute;serv&eacute;es aux widgets, &agrave; savoir une zone lat&eacute;rale, trois zones en pied de page, et une zone d&eacute;di&eacute;e &agrave; la vitrine, et son widget &laquo;&nbsp;Ephemera&nbsp;&raquo; destin&eacute; &agrave; accueillir vos br&egrave;ves inteventions (soit vos articles au format Apart&eacute;, R&eacute;cent, Citation et Lien). Sont &eacute;galement compris des styles pour l&rsquo;impression et l&rsquo;&eacute;diteur admin, des options avanc&eacute;es pour les images (dont les en-t&ecirc;tes personnalis&eacute;es sur les articles et les pages, et de larges images sur les articles en &laquo;&nbsp;sticky&nbsp;&raquo;), et la prise en charge de six formats d&rsquo;articles.","author":"the WordPress team","authorAndUri":"<a href=\"https:\/\/wordpress.org\/\">the WordPress team<\/a>","version":"2.1","tags":"Sombre, Clair, Blanc, Noir, Gris, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Curseur d'article, blog, bright, clean, contemporary, elegant, minimal, modern, photography, simple, tumblelog","parent":false,"active":false,"trendingRank":51,"popularityRank":5,"launchDate":"2011-06-06","demoUrl":"https:\/\/twentyelevendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftwentyeleven&amp;_wpnonce=c15708276d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftwentyeleven","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/minnow","name":"Minnow","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/minnow\/screenshot.png?w=434"],"description":"Minnow is designed to put your social presence front and center by displaying your social links menu prominently below the site title and logo, so readers can easily find you on your favorite social networks.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.4-wpcom","tags":"blog, tumblelog, lifestream, music, journal, Clair, minimal, modern, clean, professional, simple, Blanc, Gris, Une colonne, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, D\u00e9filement Infini, \u00c9diteur de style, Format d&rsquo;article, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, threaded-comments, site-logo","parent":false,"active":false,"trendingRank":54,"popularityRank":53,"launchDate":"2014-10-22","demoUrl":"https:\/\/minnowdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fminnow&amp;_wpnonce=cd427c9b9b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fminnow","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/hermes","name":"Hermes","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/hermes\/screenshot.png?w=434"],"description":"Un th\u00e8me moderne et minimaliste, avec un design soign\u00e9.","author":"Tasko","authorAndUri":"<a href=\"http:\/\/tdwp.us\/\">Tasko<\/a>","version":"1.0","tags":"Noir, Mise en page adaptable, D\u00e9j\u00e0 accessible, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":55,"popularityRank":174,"launchDate":"2015-03-07","demoUrl":"https:\/\/hermesdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fhermes&amp;_wpnonce=0cb345acfb","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fhermes","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/hermes&#038;ref=themesphp&#038;_wpnonce=0cb345acfb"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/eighties","name":"Eighties","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/eighties\/screenshot.png?w=434"],"description":"Hello, my name is Eighties and I am a modern, progressively enhanced theme designed to keep your content front and center. My menu and sidebar are built to stay out of the way until a user wants to see them. When clicked, users get a nice, clean overlay. You can upload a custom header image or select to use the featured image of the post as the header image.","author":"Justin Kopepasah","authorAndUri":"<a href=\"http:\/\/kopepasah.com\/\">Justin Kopepasah<\/a>","version":"1.2.1-wpcom","tags":"Clair, Rouge, Blanc, Une colonne, Mise en page fixe, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, design, journal, lifestream, portfolio, photography, colorful, modern, playful, retro, Image d&rsquo;en-t\u00eate \u00e0 la Une, Article mis en avant, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":56,"popularityRank":24,"launchDate":"2014-09-02","demoUrl":"https:\/\/eightiesdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Feighties&amp;_wpnonce=1b74483720","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Feighties","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/shrake","name":"Shrake","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/shrake\/screenshot.png?w=434"],"description":"Shrake is a minimalistic micro-blogging theme focused on your content through simplicity in design, clean typography, and a focused layout. We designed it using a mobile-first approach, meaning your content takes center-stage, regardless of whether your visitors arrive by smartphone, tablet, laptop, or desktop computer. Featuring a unique fancy scroll experience, your logo and navigation is resized and remains visible as users scroll down the page.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"2.1.1","tags":"Clair, Blanc, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, featured-mages, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, clean, conservative, contemporary, elegant, formal, Clair, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":57,"popularityRank":356,"launchDate":"2015-03-12","demoUrl":"https:\/\/shrakedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fshrake&amp;_wpnonce=883860f564","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fshrake","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/shrake&#038;ref=themesphp&#038;_wpnonce=883860f564"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>19","purchased":false}},{"id":"pub\/sequential","name":"Sequential","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sequential\/screenshot.png?w=434"],"description":"Sequential est un th\u00e8me contemporain, net et multi-usage, id\u00e9al pour un business.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.1-wpcom","tags":"Clair, Violet, Blanc, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, collaboration, design, food, hotel, portfolio, real-estate, school, bright, clean, conservative, elegant, formal, Clair, minimal, modern, professional, simple, sophisticated, traditional","parent":false,"active":false,"trendingRank":58,"popularityRank":104,"launchDate":"2014-11-06","demoUrl":"https:\/\/sequentialdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsequential&amp;_wpnonce=e2f743004e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsequential","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/hyalite","name":"Hyalite","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/hyalite\/screenshot.png?w=434"],"description":"Hyalite is a minimalistic, micro-blogging WordPress theme with a focus on typography and the ability to display a portfolio.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"1.6.0","tags":"Blanc, Clair, Une colonne, Mise en page adaptable, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, design, fashion, journal, lifestream, music, Photoblogging, photography, portfolio, tumblelog, video, wedding, bright, clean, contemporary, elegant, Clair, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":61,"popularityRank":242,"launchDate":"2015-01-30","demoUrl":"https:\/\/hyalitedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fhyalite&amp;_wpnonce=5c3af39bf3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fhyalite","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/hyalite&#038;ref=themesphp&#038;_wpnonce=5c3af39bf3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>39","purchased":false}},{"id":"pub\/intergalactic","name":"Intergalactic","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/intergalactic\/screenshot.png?w=434"],"description":"Intergalactic is a stunning specimen for your personal blog. Bold featured images act as the backdrop to your text, giving you a high-contrast, readable theme that&rsquo;s perfect for making your content pop. The one-column layout provides a distraction-free environment for reading, while the slide-out menu keeps your navigation and secondary content readily accessible.","author":"WordPress.com","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">WordPress.com<\/a>","version":"1.3.1-wpcom","tags":"blog, Photoblogging, photography, clean, conservative, Sombre, modern, Noir, Blanc, Une colonne, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page fixe, Mise en page adaptable, D\u00e9j\u00e0 accessible","parent":false,"active":false,"trendingRank":60,"popularityRank":61,"launchDate":"2014-09-26","demoUrl":"https:\/\/intergalacticdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fintergalactic&amp;_wpnonce=4620317839","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fintergalactic","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/cyanotype","name":"Cyanotype","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/cyanotype\/screenshot.png?w=434"],"description":"Cyanotype is a monochromatic blog theme with a bold, yet simple look that sets your blog apart from the rest. Pick your favorite background color or image to lend your personal flair.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.2-wpcom","tags":"Bleu, Blanc, Sombre, Une colonne, Mise en page fixe, Mise en page adaptable, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, design, journal, lifestream, travel, clean, contemporary, Sombre, geometric, minimal, modern, simple","parent":false,"active":false,"trendingRank":61,"popularityRank":345,"launchDate":"2015-04-13","demoUrl":"https:\/\/cyanotypedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcyanotype&amp;_wpnonce=a20818ec9f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcyanotype","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/veeva","name":"Veeva","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/veeva\/screenshot.png?w=434"],"description":"Un th\u00e8me color\u00e9 pour votre blog personnel","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Marron, Vert, Rouge, Blanc, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, craft, journal, colorful","parent":false,"active":false,"trendingRank":62,"popularityRank":367,"launchDate":"2014-06-04","demoUrl":"https:\/\/veevademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fveeva&amp;_wpnonce=75e10fd5e1","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fveeva","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/veeva&#038;ref=themesphp&#038;_wpnonce=75e10fd5e1"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/dicot","name":"Dicot","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/dicot\/screenshot.png?w=434"],"description":"Dicot est un th\u00e8me WordPress pour magazines, sites d&rsquo;actualit\u00e9s, ou pour blogs, \u00e0 l&rsquo;esth\u00e9tisme \u00e9pur\u00e9 et moderne. Dicot est totalement adaptatif et bas\u00e9 sur une technologie actuelle. Il met en vedette une structure large ou encadr\u00e9e, une barre lat\u00e9rale personnalis\u00e9e, une barre de navigation fixe, un diaporama d&rsquo;articles \u00e0 la Une, des widgets personnalis\u00e9s et plusieurs autres fonctions utiles et int\u00e9ressantes qui faciliteront votre travail. Nous esp\u00e9rons que vous appr\u00e9cierez ce th\u00e8me et que vous vous amuserez \u00e0 publier vos articles&nbsp;!","author":"DesignOrbital","authorAndUri":"<a href=\"http:\/\/designorbital.com\/\">DesignOrbital<\/a>","version":"1.0","tags":"Noir, Rouge, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Curseur d'article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, business, design, fashion, journal, magazine, music, news, Photoblogging, photography, sports, travel, tumblelog, bright, clean, contemporary, elegant, glamorouse, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":63,"popularityRank":171,"launchDate":"2015-04-30","demoUrl":"https:\/\/dicotdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fdicot&amp;_wpnonce=c406d6d40c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fdicot","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/dicot&#038;ref=themesphp&#038;_wpnonce=c406d6d40c"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>89","purchased":false}},{"id":"pub\/sela","name":"Sela","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sela\/screenshot.png?w=434"],"description":"Sela is not your typical business theme. Vibrant, bold, and clean, with lots of space for large images, this theme will look great on all devices, from desktop to mobile.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.8-wpcom","tags":"Gris, Rose, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Couleurs personnalis\u00e9es, D\u00e9filement Infini, Mise en page adaptable, site-logo, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Microformats, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, design, bright, clean, elegant, formal, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":65,"popularityRank":78,"launchDate":"2015-01-08","demoUrl":"https:\/\/selademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsela&amp;_wpnonce=f5f68142b8","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsela","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/goran","name":"Goran","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/goran\/screenshot.png?w=434"],"description":"Goran is a functional and responsive multi-purpose theme that is the perfect solution for your business\u2019s online presence.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.1-wpcom","tags":"Gris, Rouge, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, collaboration, design, food, hotel, portfolio, real-estate, school, bright, clean, conservative, elegant, formal, Clair, minimal, modern, professional, simple, sophisticated, traditional","parent":"Edin","active":false,"trendingRank":66,"popularityRank":23,"launchDate":"2014-08-28","demoUrl":"https:\/\/gorandemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fgoran&amp;_wpnonce=de982b8f0a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fgoran","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/onigiri","name":"Onigiri","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/onigiri\/screenshot.png?w=434"],"description":"Onigiri is a minimal, arty, responsive Portfolio theme to feature your creative work. Of course Onigiri also comes with a default blog layout, so that you can include a news stream or online journal on your portfolio website as well.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/en\/\">Elmastudio<\/a>","version":"1.0-wpcom","tags":"Blanc, Clair, Une colonne, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, site logo, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, craft, design, fashion, photography, Portfolio, artistic, bright, clean, contemporary, elegant, Clair, minimal, modern, professional, sophisticated","parent":false,"active":false,"trendingRank":67,"popularityRank":244,"launchDate":"2015-03-16","demoUrl":"https:\/\/onigiridemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fonigiri&amp;_wpnonce=05d0de0389","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fonigiri","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/onigiri&#038;ref=themesphp&#038;_wpnonce=05d0de0389"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>24","purchased":false}},{"id":"pub\/reddle","name":"Reddle","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/reddle\/screenshot.png?w=434"],"description":"Tout dans le design minimal de Reddle s&rsquo;adapte \u00e9l\u00e9gamment \u00e0 la fa\u00e7on dont vous souhaitez utiliser votre blog et \u00e0 ce pour quoi vous voulez l&rsquo;utiliser. Vous souhaitez un blog simple de liens sur colonne unique\u00a0? Un site d&rsquo;entreprise \u00e0 deux colonnes avec un en-t\u00eate personnalis\u00e9 et aucunes publications\u00a0? Reddle peut aussi faire \u00e7a, et aussi d&rsquo;une jolie mani\u00e8re&#8230;","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.3.3-wpcom","tags":"art, Couleurs personnalis\u00e9es, blog, journal, tumblelog, professional, bright, clean, conservative, minimal, simple, Rouge, Blanc, Une colonne, Colonne lat\u00e9rale droite, Deux colonnes, Mise en page fixe, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":68,"popularityRank":8,"launchDate":"2011-12-05","demoUrl":"https:\/\/reddledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Freddle&amp;_wpnonce=b6f1b4e412","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Freddle","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/candela","name":"Candela","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/candela\/screenshot.png?w=434"],"description":"Candela is a personal blogging and portfolio WordPress theme for displaying artwork. Candela focuses on showcasing portfolios of artists, web designers, illustrators and creatives in the most impressive manner. The responsive layout will adapt to different screen sizes which will make your website be compatible with any device such as smart phones, tablets or desktop computers.","author":"DesignOrbital","authorAndUri":"<a href=\"http:\/\/designorbital.com\/\">DesignOrbital<\/a>","version":"1.0","tags":"Noir, Bleu, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, site-logo, Options du th\u00e8me, Microformats, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, business, design, fashion, journal, music, Photoblogging, photography, portfolio, sports, travel, tumblelog, bright, clean, contemporary, elegant, modern, professional, sophisticated","parent":false,"active":false,"trendingRank":69,"popularityRank":280,"launchDate":"2014-10-24","demoUrl":"https:\/\/candelademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcandela&amp;_wpnonce=c959818ab3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcandela","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/candela&#038;ref=themesphp&#038;_wpnonce=c959818ab3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/carmela","name":"Carmela","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/carmela\/screenshot.png?w=434"],"description":"Carmela is a clean and responsive theme designed to make your blogging experience as pleasant as possible.","author":"SiloCreativo","authorAndUri":"<a href=\"http:\/\/www.silocreativo.com\">SiloCreativo<\/a>","version":"1.0.1","tags":"Blanc, Vert, Clair, Une colonne, Deux colonnes, Mise en page adaptable, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Couleurs personnalis\u00e9es, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Images \u00e0 la Une, \u00c9diteur de style, Support des langues RTL, blog","parent":false,"active":false,"trendingRank":71,"popularityRank":366,"launchDate":"2014-06-17","demoUrl":"https:\/\/carmelademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcarmela&amp;_wpnonce=2961cab980","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcarmela","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/carmela&#038;ref=themesphp&#038;_wpnonce=2961cab980"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"pub\/kelly","name":"Kelly","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/kelly\/screenshot.png?w=434"],"description":"Un th\u00e8me propre, clair et adaptable avec beaucoup de place pour vos images.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.5-wpcom","tags":"Vert, Clair, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Une colonne, blog, Photoblogging, photography, journal, clean, colorful, modern, minimal, simple, Mise en page fixe, Mise en page adaptable","parent":false,"active":false,"trendingRank":71,"popularityRank":60,"launchDate":"2014-05-29","demoUrl":"https:\/\/kellydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fkelly&amp;_wpnonce=a5280c6dad","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fkelly","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/fortune","name":"Fortune","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/fortune\/screenshot.png?w=434"],"description":"Fortune est un th\u00e8me WordPress propre, tr\u00e8s flexible et compl\u00e8tement adaptatif, il convient aux entreprises et aux organismes \u00e0 but non lucratif. ","author":"Tasko","authorAndUri":"<a href=\"http:\/\/tdwp.us\/\">Tasko<\/a>","version":"1.0-wpcom","tags":"Clair, Sombre, Deux colonnes, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, design, bright, clean, elegant, formal, minimal, modern, professional, simple, education, food, real estate","parent":false,"active":false,"trendingRank":72,"popularityRank":205,"launchDate":"2015-01-28","demoUrl":"https:\/\/fortunedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Ffortune&amp;_wpnonce=95ff2a6a59","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Ffortune","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/fortune&#038;ref=themesphp&#038;_wpnonce=95ff2a6a59"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>150","purchased":false}},{"id":"pub\/nucleare","name":"Nucleare","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/nucleare\/screenshot.png?w=434"],"description":"Nucleare is a classic blog theme with a crisp, elegant design and plenty of handy features. A built-in search box, links to your favorite social networks, four widget areas, and beautifully styled post formats make this an ideal theme for your personal blog.","author":"CrestaProject","authorAndUri":"<a href=\"http:\/\/crestaproject.com\">CrestaProject<\/a>","version":"1.0.3-wpcom","tags":"blog, journal, elegant, Clair, conservative, traditional, Vert, Gris, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Couleurs personnalis\u00e9es, Article mis en avant, Images \u00e0 la Une, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, site-logo","parent":false,"active":false,"trendingRank":73,"popularityRank":198,"launchDate":"2015-04-28","demoUrl":"https:\/\/nuclearedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fnucleare&amp;_wpnonce=5cb8a72178","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fnucleare","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/nowell","name":"Nowell","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/nowell\/screenshot.png?w=434"],"description":"Nowell&rsquo;s large hero image and featured content slider is a great way to draw attention to specific pages and content. Customized audio players and playlists allow musicians, podcasters, churches, and more the ability to have visitors playback audio in way that matches the sites layout and design. Archive pages have three display options that range from showing only the essentials upto full content and custom excerpts.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"2.1.2","tags":"Noir, Gris, Blanc, Clair, Deux colonnes, Trois colonnes, left sidebar, Colonne lat\u00e9rale droite, Mise en page adaptable, accesibility-ready, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Curseur d'article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, music, photography, portfolio, video, clean, contemporary, modern, professional","parent":false,"active":false,"trendingRank":74,"popularityRank":204,"launchDate":"2015-01-15","demoUrl":"https:\/\/nowelldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fnowell&amp;_wpnonce=787db2a365","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fnowell","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/nowell&#038;ref=themesphp&#038;_wpnonce=787db2a365"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>39","purchased":false}},{"id":"pub\/hemingway-rewritten","name":"Hemingway Rewritten","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/hemingway-rewritten\/screenshot.png?w=434"],"description":"Hemingway Rewritten est un th\u00e8me de blog classique avec un effet de d\u00e9filement parallaxe de l\u2019en-t\u00eate et un graphisme minimaliste et \u00e9l\u00e9gant. Les grandes images de l\u2019en-t\u00eate sont parfaitement adapt\u00e9es pour les photographes ou simplement les utilisateurs qui souhaitent partager leurs visuels de fa\u00e7on simple.","author":"Anders Noren","authorAndUri":"<a href=\"http:\/\/www.andersnoren.se\">Anders Noren<\/a>","version":"1.1.1-wpcom","tags":"Noir, Blanc, Deux colonnes, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, design, journal, lifestream, tumblelog, clean, conservative, elegant, minimal, modern, professional","parent":false,"active":false,"trendingRank":77,"popularityRank":14,"launchDate":"2014-03-20","demoUrl":"https:\/\/hemingwayrewrittendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fhemingway-rewritten&amp;_wpnonce=a727750692","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fhemingway-rewritten","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/bindery","name":"Bindery","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/bindery\/screenshot.png?w=434"],"description":"","author":"Pixel Union","authorAndUri":"<a href=\"http:\/\/pixelunion.net\">Pixel Union<\/a>","version":"0.4.0","tags":"Clair, Blanc, Une colonne, Deux colonnes, Trois colonnes, Quatre colonnes, Mise en page fluide, Mise en page adaptable, D\u00e9j\u00e0 accessible, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, business, collaboration, craft, design, education, fashion, food, gaming, Vacances, journal, lifestream, magazine, nature, news, outdoors, Photoblogging, photography, portfolio, productivity, real-estate, school, scrapbooking, Saisonnier, sports, travel, wedding, artistic, bright, clean, conservative, contemporary, elegant, formal, geometric, glamorous, handcrafted, Clair, minimal, modern, professional, simple, sophisticated, traditional, urban","parent":false,"active":false,"trendingRank":76,"popularityRank":193,"launchDate":"2015-03-06","demoUrl":"https:\/\/binderydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbindery&amp;_wpnonce=d6e7f87ceb","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbindery","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/bindery&#038;ref=themesphp&#038;_wpnonce=d6e7f87ceb"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/gazette","name":"Gazette","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/gazette\/screenshot.png?w=434"],"description":"A clean and flexible theme perfectly suited for minimalist magazine-style sites, personal blogs, or any content-rich site. It allows you to highlight specific articles on the homepage, and to balance readability with a powerful use of photography \u2014 all in a layout that works on any device.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.5-wpcom","tags":"Bleu, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, collaboration, food, gaming, journal, magazine, news, clean, contemporary, elegant, geometric, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":77,"popularityRank":231,"launchDate":"2015-05-07","demoUrl":"https:\/\/gazettedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fgazette&amp;_wpnonce=4f4903e525","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fgazette","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/hew","name":"Hew","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/hew\/screenshot.png?w=434"],"description":"Hew is a personal blog theme with distinct identity and a splash of colour! It&rsquo;s all about sharing your thoughts and experiences, and connecting with your readers via prominently placed social media links.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.2-wpcom","tags":"Blanc, Jaune, Noir, Une colonne, Mise en page adaptable, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, D\u00e9filement Infini, Images \u00e0 la Une, Article mis en avant, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, threaded-comments","parent":false,"active":false,"trendingRank":78,"popularityRank":343,"launchDate":"2015-02-19","demoUrl":"https:\/\/hewdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fhew&amp;_wpnonce=7b28e3de5e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fhew","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/swell","name":"Swell","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/swell\/screenshot.png?w=434"],"description":"Swell is a one-column, typography-focused, video WordPress theme.","author":"ThemeTrust.com","authorAndUri":"<a href=\"http:\/\/themetrust.com\">ThemeTrust.com<\/a>","version":"1.2.1-wpcom","tags":"business, portfolio, conservative, modern, professional, Noir, Blanc, Clair, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, site-logo, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page adaptable","parent":false,"active":false,"trendingRank":86,"popularityRank":184,"launchDate":"2014-12-04","demoUrl":"https:\/\/swelldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fswell&amp;_wpnonce=c67f646085","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fswell","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/swell&#038;ref=themesphp&#038;_wpnonce=c67f646085"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/album","name":"Album","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/album\/screenshot.png?w=434"],"description":"A beautifully crafted audio theme for WordPress.","author":"Press75","authorAndUri":"<a href=\"http:\/\/www.press75.com\/\">Press75<\/a>","version":"1.0.1","tags":"Gris, Blanc, Bleu, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":80,"popularityRank":363,"launchDate":"2015-04-16","demoUrl":"https:\/\/albumdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Falbum&amp;_wpnonce=ab4aa06e00","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Falbum","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/album&#038;ref=themesphp&#038;_wpnonce=ab4aa06e00"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/sobe","name":"Sobe","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sobe\/screenshot.png?w=434"],"description":"A lighthearted personal blogging theme for sharing life&rsquo;s most memorable moments.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.6-wpcom","tags":"blog, journal, lifestream, tumblelog, bright, clean, colorful, Clair, modern, whimsical, Rose, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Menu personnalis\u00e9, \u00c9diteur de style, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":81,"popularityRank":326,"launchDate":"2015-01-30","demoUrl":"https:\/\/sobedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsobe&amp;_wpnonce=36353269c2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsobe","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/purpose","name":"Purpose","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/purpose\/screenshot.png?w=434"],"description":"A versatile business theme designed with purpose.","author":"Organic Themes","authorAndUri":"<a href=\"http:\/\/www.organicthemes.com\">Organic Themes<\/a>","version":"1.0","tags":"art, artwork, blog, design, Photoblogging, business, education, food, real estate, portfolio, clean, contemporary, elegant, Clair, minimal, modern, professional, simple, Gris, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, responsive-width, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Curseur d'article, Article mis en avant, Format d&rsquo;article, Images \u00e0 la Une, site-logo","parent":false,"active":false,"trendingRank":82,"popularityRank":148,"launchDate":"2014-12-30","demoUrl":"https:\/\/purposedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpurpose&amp;_wpnonce=b09b244086","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpurpose","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/purpose&#038;ref=themesphp&#038;_wpnonce=b09b244086"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/illustratr","name":"Illustratr","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/illustratr\/screenshot.png?w=434"],"description":"Un th\u00e8me pour portfolio minimaliste","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.1-wpcom","tags":"Sombre, Rouge, Blanc, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, design, Photoblogging, photography, portfolio, clean, contemporary, elegant, geometric, Clair, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":82,"popularityRank":44,"launchDate":"2014-04-10","demoUrl":"https:\/\/illustratrdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fillustratr&amp;_wpnonce=66201a7f7b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fillustratr","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/together","name":"Together","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/together\/screenshot.png?w=434"],"description":"A holiday theme for 2014 from WordPress.com that brings everyone together around your blog.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Clair, Violet, Blanc, Une colonne, Mise en page fixe, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, design, journal, lifestream, portfolio, photography, colorful, modern, playful, retro, Image d&rsquo;en-t\u00eate \u00e0 la Une, Article mis en avant, D\u00e9filement Infini","parent":"Eighties","active":false,"trendingRank":84,"popularityRank":346,"launchDate":"2014-12-08","demoUrl":"https:\/\/togetherdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftogether&amp;_wpnonce=c2e77b0f53","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftogether","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/tonal","name":"Tonal","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/tonal\/screenshot.png?w=434"],"description":"Avec son style minimaliste qui change en fonction de la couleur de votre arri\u00e8re-plan, Tonal donne la r\u00e9plique \u00e0 votre contenu. Ce th\u00e8me propose de grandes images, des vid\u00e9os plein \u00e9cran et des formats de publication d\u2019un excellent rendu sur tous les p\u00e9riph\u00e9riques.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.1-wpcom","tags":"blog, design, journal, Photoblogging, Blanc, Noir, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, clean, minimal","parent":false,"active":false,"trendingRank":84,"popularityRank":41,"launchDate":"2014-03-11","demoUrl":"https:\/\/tonaldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftonal&amp;_wpnonce=9e3861eff2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftonal","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/big-brother","name":"Big Brother","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/big-brother\/screenshot.png?w=434"],"description":"A pleasant-to-read, customizable theme designed for large organizations and government.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.10-wpcom","tags":"Bleu, Clair, blog, business, education, school, clean, conservative, traditional, Colonne lat\u00e9rale droite, Deux colonnes, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, site-logo, Mise en page fixe, Mise en page adaptable","parent":false,"active":false,"trendingRank":85,"popularityRank":34,"launchDate":"2014-06-30","demoUrl":"https:\/\/bigbrotherdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbig-brother&amp;_wpnonce=dd97942089","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbig-brother","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/beacon","name":"Beacon","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/beacon\/screenshot.png?w=434"],"description":"Beacon is a mobile-friendly showcase for viral content and community discussion","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\">Pro Theme Design<\/a>","version":"1.0","tags":"Bleu, Gris, Rouge, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, collaboration, food, gaming, magazine, music, news, sports, clean, contemporary, elegant, formal, industrial, modern, professional, site-logo","parent":false,"active":false,"trendingRank":87,"popularityRank":268,"launchDate":"2014-11-19","demoUrl":"https:\/\/beacondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbeacon&amp;_wpnonce=f9bce6b12f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbeacon","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/beacon&#038;ref=themesphp&#038;_wpnonce=f9bce6b12f"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/hexa","name":"Hexa","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/hexa\/screenshot.png?w=434"],"description":"Un th\u00e8me color\u00e9 pour les blogs personnels qui prend en charge diff\u00e9rents formats de publication avec un grand sens de la g\u00e9om\u00e9trie.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"Bleu, Marron, Rouge, Ocre, Clair, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, lifestream, tumblelog, bright, clean, colorful, geometric, modern, playful, simple, whimsical, vibrant","parent":false,"active":false,"trendingRank":88,"popularityRank":95,"launchDate":"2014-02-19","demoUrl":"https:\/\/hexademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fhexa&amp;_wpnonce=0383190e22","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fhexa","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/mayer","name":"Mayer","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/mayer\/screenshot.png?w=434"],"description":"For the writer, established blogger, and inspired author.","author":"Pressware","authorAndUri":"<a href=\"http:\/\/pressware.co\/\">Pressware<\/a>","version":"1.9.0","tags":"Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Menu personnalis\u00e9, \u00c9diteur de style, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, news, clean, conservative, Clair, minimal, modern, professional","parent":false,"active":false,"trendingRank":89,"popularityRank":341,"launchDate":"2014-02-13","demoUrl":"https:\/\/mayerdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmayer&amp;_wpnonce=bfc66c34ea","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmayer","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/mayer&#038;ref=themesphp&#038;_wpnonce=bfc66c34ea"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/suidobashi","name":"Suidobashi","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/suidobashi\/screenshot.png?w=434"],"description":"Suidobashi is a minimal, clean, responsive Portfolio theme to feature your creative work or projects. Suidobashi also comes with a default blog layout, so you can include a news or online journal on your portfolio website as well.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/en\/\">Elmastudio<\/a>","version":"1.0.1-wpcom","tags":"Blanc, Clair, Une colonne, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, site logo, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, craft, design, fashion, photography, Portfolio, artistic, bright, clean, contemporary, elegant, Clair, minimal, modern, professional, sophisticated","parent":false,"active":false,"trendingRank":90,"popularityRank":236,"launchDate":"2015-03-16","demoUrl":"https:\/\/suidobashidemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fsuidobashi&amp;_wpnonce=2198b128da","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fsuidobashi","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/suidobashi&#038;ref=themesphp&#038;_wpnonce=2198b128da"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>24","purchased":false}},{"id":"pub\/lyretail","name":"Lyretail","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/lyretail\/screenshot.png?w=434"],"description":"Lyretail is a minimalist, one-column theme that packs a powerful visual punch. It&rsquo;s great for writing-focused blogs that make use of large featured images. With prominent links to your favorite social networks and a convenient slide-down menu\/widget area, Lyretail is sure to be your new favorite theme.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/automattic.com\/\">Automattic<\/a>","version":"1.0.0-wpcom","tags":"blog, lifestream, journal, clean, minimal, Clair, simple, Blanc, Vert, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, site-logo, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, Mise en page fixe, Mise en page adaptable","parent":"Minnow","active":false,"trendingRank":91,"popularityRank":325,"launchDate":"2015-02-24","demoUrl":"https:\/\/lyretaildemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Flyretail&amp;_wpnonce=3d008d26d4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Flyretail","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/satellite","name":"Satellite","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/satellite\/screenshot.png?w=434"],"description":"A snappy personal blogging theme with beautiful typography, prominent featured images, and a fresh, modern look.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"blog, journal, Clair, modern, simple, Noir, Blanc, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, En-t\u00eate flexible, Images \u00e0 la Une, \u00c9diteur de style, Format d&rsquo;article, Une colonne, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Mise en page fixe, Mise en page adaptable, site-logo","parent":"Scrawl","active":false,"trendingRank":92,"popularityRank":332,"launchDate":"2015-03-20","demoUrl":"https:\/\/satellitedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsatellite&amp;_wpnonce=a5764e582e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsatellite","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/espied","name":"Espied","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/espied\/screenshot.png?w=434"],"description":"Th\u00e8me de style book pour les graphistes et les photographes. Parfait pour faire admirer au monde entier vos projets orient\u00e9s images.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.5-wpcom","tags":"Bleu, Noir, Blanc, Une colonne, Mise en page fixe, Mise en page fluide, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, Photoblogging, photography, portfolio, clean, contemporary, elegant, geometric, Clair, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":93,"popularityRank":115,"launchDate":"2014-04-10","demoUrl":"https:\/\/espieddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fespied&amp;_wpnonce=3ab10d475a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fespied","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/capoverso","name":"Capoverso","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/capoverso\/screenshot.png?w=434"],"description":"Capoverso is a minimalist theme with strong typography, designed for those who want to make a bold statement in a simple way. The unique Front Page template allows you to display a large featured image of your choosing, overlaid with brief introductory text and a custom menu, allowing your readers to focus on your content by presenting them with the bare essentials. You can further customize Capoverso with a background, logo, or widgets.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Deux colonnes, Noir, Gris, Sombre, conservative, minimal, simple, announcement, blog","parent":false,"active":false,"trendingRank":94,"popularityRank":331,"launchDate":"2014-11-25","demoUrl":"https:\/\/capoversodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcapoverso&amp;_wpnonce=093ab0c29e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcapoverso","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/vagabond","name":"Vagabond","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/vagabond\/screenshot.png?w=434"],"description":"Vagabond est un th\u00e8me bien \u00e9tudi\u00e9 et bien rang\u00e9 pour les blogs personnels.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"blog, design, journal, photography, outdoors, travel, tumblelog, artistic, colorful, hand-drawn, elegant, sophisticated, vibrant, Bleu, Rose, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mise en page fluide, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":95,"popularityRank":237,"launchDate":"2013-07-04","demoUrl":"https:\/\/vagabonddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fvagabond&amp;_wpnonce=0d7ef154fa","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fvagabond","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/vagabond&#038;ref=themesphp&#038;_wpnonce=0d7ef154fa"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/wilson","name":"Wilson","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/wilson\/screenshot.png?w=434"],"description":"Wilson is a clean, simple and bold theme for personal sites and blogs. Make it your own with a custom header image or a Gravatar. Plus, use Post Formats to highlight your content, add a custom menu or take advantage of three widget areas.","author":"Anders Noren","authorAndUri":"<a href=\"http:\/\/www.andersnoren.se\">Anders Noren<\/a>","version":"1.16-wpcom","tags":"Noir, Bleu, Sombre, Blanc, Rouge, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fluide, Mise en page adaptable, Menu personnalis\u00e9, Images \u00e0 la Une, \u00c9diteur de style, En-t\u00eate flexible, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Article mis en avant, Support des langues RTL, site-logo, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, blog, clean, minimal, modern","parent":false,"active":false,"trendingRank":96,"popularityRank":286,"launchDate":"2015-01-14","demoUrl":"https:\/\/wilsondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fwilson&amp;_wpnonce=780f0ac57f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fwilson","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/saga","name":"Saga","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/saga\/screenshot.png?w=434"],"description":"Tell your story with Saga, a tailor-made theme for writers, by a writer. Aside from impeccable typography and attention to detail, the theme supports several customization options so you can personalize your site&rsquo;s design.","author":"Justin Tadlock","authorAndUri":"<a href=\"http:\/\/justintadlock.com\/\">Justin Tadlock<\/a>","version":"1.0.1-wpcom","tags":"Photoblogging, photography, blog, journal, lifestream, tumblelog, Sombre, formal, elegant, Noir, Rouge, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page fixe, Mise en page adaptable","parent":false,"active":false,"trendingRank":95,"popularityRank":334,"launchDate":"2015-03-25","demoUrl":"https:\/\/sagademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsaga&amp;_wpnonce=8e15178ae2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsaga","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/largo","name":"Largo","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/largo\/screenshot.png?w=434"],"description":"Largo offers a large, widescreen appearance and is intended for long-form content with striking full-screen images and a hidden menu\/widget panel.","author":"UpThemes","authorAndUri":"<a href=\"https:\/\/upthemes.com\/\">UpThemes<\/a>","version":"1.0.9","tags":"Blanc, Clair, sophisticated, simple, professional, minimal, formal, clean, tumblelog, video, travel, Photoblogging, photography, portfolio, lifestream, design, blog, Pr\u00eat \u00e0 \u00eatre traduit, Article mis en avant, Support des langues RTL, Format d&rsquo;article, D\u00e9filement Infini, Mod\u00e8le pleine largeur, En-t\u00eate flexible, Image d&rsquo;en-t\u00eate \u00e0 la Une, \u00c9diteur de style, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, responsive-width, Une colonne","parent":false,"active":false,"trendingRank":98,"popularityRank":287,"launchDate":"2015-01-26","demoUrl":"https:\/\/largodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Flargo&amp;_wpnonce=57448dc754","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Flargo","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/largo&#038;ref=themesphp&#038;_wpnonce=57448dc754"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/radcliffe","name":"Radcliffe","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/radcliffe\/screenshot.png?w=434"],"description":"A theme for bloggers who want their content to take center stage. Radcliffe features responsive design, retina-ready assets, full width header images, beautiful design and typography, support for custom logo, support for custom accent color, three widget areas, editor style and translation-ready code. Included translations: Swedish\/svenska.","author":"Anders Nor\u00e9n","authorAndUri":"<a href=\"http:\/\/www.andersnoren.se\">Anders Nor\u00e9n<\/a>","version":"1.07-wpcom","tags":"Gris, Blanc, Une colonne, Mise en page fluide, Mise en page adaptable, Menu personnalis\u00e9, Images \u00e0 la Une, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, \u00c9diteur de style","parent":false,"active":false,"trendingRank":99,"popularityRank":239,"launchDate":"2014-12-10","demoUrl":"https:\/\/radcliffedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fradcliffe&amp;_wpnonce=b45c4fde80","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fradcliffe","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/zuki","name":"Zuki","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/zuki\/screenshot.png?w=434"],"description":"Zuki is an elegant, modern, and flexible magazine theme with a custom front page template to show a posts filtered by categories as well as a default blog layout with a right-aligned sidebar. This way you can use Zuki also as a pure blog theme. With Zuki&rsquo;s Recent Posts widgets and the Front Page widget areas, it&rsquo;s easy to create a magazine-style blog in just a few simple steps.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/en\/\">Elmastudio<\/a>","version":"1.0.1-wpcom","tags":"Blanc, Clair, Une colonne, Deux colonnes, Trois colonnes, Quatre colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, site-logo, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, craft, design, fashion, food, journal, magazine, news, photography, travel, bright, clean, contemporary, elegant, Clair, minimal, modern, professional, sophisticated","parent":false,"active":false,"trendingRank":100,"popularityRank":12,"launchDate":"2014-10-13","demoUrl":"https:\/\/zukidemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fzuki&amp;_wpnonce=65b5294b5a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fzuki","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/zuki&#038;ref=themesphp&#038;_wpnonce=65b5294b5a"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>24","purchased":false}},{"id":"pub\/resonar","name":"Resonar","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/resonar\/screenshot.png?w=434"],"description":"Resonar is an elegant blog theme that features full-screen featured images.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.6-wpcom","tags":"Bleu, Blanc, Clair, Une colonne, Mise en page fixe, Mise en page adaptable, D\u00e9j\u00e0 accessible, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, fashion, journal, lifestream, magazine, news, Photoblogging, photography, portfolio, travel, bright, clean, conservative, contemporary, elegant, formal, Clair, minimal, modern, professional, simple, sophisticated, traditional","parent":false,"active":false,"trendingRank":98,"popularityRank":216,"launchDate":"2015-03-16","demoUrl":"https:\/\/resonardemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fresonar&amp;_wpnonce=39d9486aee","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fresonar","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/worldview","name":"Worldview","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/worldview\/screenshot.png?w=434"],"description":"Worldview est un th\u00e8me r\u00e9actif de photo-blogging gr\u00e2ce auquel vous pouvez afficher des photos d&rsquo;une incroyable beaut\u00e9 en toute simplicit\u00e9. Worldview se caract\u00e9rise par une typographie pr\u00e9cise qui allie excellente lisibilit\u00e9 et format redimensionnable en fonction de la taille du p\u00e9riph\u00e9rique ou de l&rsquo;\u00e9cran.","author":"UpThemes","authorAndUri":"<a href=\"https:\/\/upthemes.com\/\">UpThemes<\/a>","version":"1.1.7","tags":"design, education, fashion, food, gaming, lifestream, art, blog, news, Photoblogging, photography, portfolio, school, travel, artistic, bright, colorful, clean, contemporary, Sombre, design, modern, Clair, journal, professional, simple, vibrant, Noir, Jaune, Blanc, Pr\u00eat \u00e0 \u00eatre traduit, Article mis en avant, Support des langues RTL, Format d&rsquo;article, D\u00e9filement Infini, Mod\u00e8le pleine largeur, En-t\u00eate flexible, Image d&rsquo;en-t\u00eate \u00e0 la Une, \u00c9diteur de style, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Mise en page adaptable, Mise en page fluide, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite","parent":false,"active":false,"trendingRank":102,"popularityRank":278,"launchDate":"2014-04-24","demoUrl":"https:\/\/worldviewdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fworldview&amp;_wpnonce=6aa29dbd5f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fworldview","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/worldview&#038;ref=themesphp&#038;_wpnonce=6aa29dbd5f"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/lingonberry","name":"Lingonberry","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/lingonberry\/screenshot.png?w=434"],"description":"Lingonberry is a bright, personable blogging theme with bold colors and accents and a playful, modern twist.","author":"Anders Noren","authorAndUri":"<a href=\"http:\/\/www.andersnoren.se\">Anders Noren<\/a>","version":"1.17-wpcom","tags":"blog, journal, lifestream, tumblelog, bright, clean, Clair, playful, retro, Rose, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, site-logo, Article mis en avant, Mise en page fixe, Mise en page adaptable","parent":false,"active":false,"trendingRank":101,"popularityRank":264,"launchDate":"2015-04-08","demoUrl":"https:\/\/lingonberrydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Flingonberry&amp;_wpnonce=646c9836b4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Flingonberry","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/hive","name":"Hive","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/hive\/screenshot.png?w=434"],"description":"An effortless tool for publishers of all kind, cherished for its clean masonry-style layout, modern typography and flexibility. Whether you\u2019re looking to share your own thoughts, write about your latest findings or just have a scrapbook of photos, videos, quotes or other stuff, HIVE is designed to fulfill these and a lot more.","author":"PixelGrade","authorAndUri":"<a href=\"http:\/\/pixelgrade.com\">PixelGrade<\/a>","version":"1.0-wpcom","tags":"Clair, Blanc, Jaune, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Menu personnalis\u00e9, Images \u00e0 la Une, \u00c9diteur de style, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, blog, fashion, journal, lifestream, magazine, news, scrapbooking, video, bright, clean, elegant, geometric, glamorous, industrial, Clair, minimal, modern, sophisticated","parent":false,"active":false,"trendingRank":104,"popularityRank":70,"launchDate":"2014-10-24","demoUrl":"https:\/\/hivedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fhive&amp;_wpnonce=e3f9bf5cea","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fhive","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/hive&#038;ref=themesphp&#038;_wpnonce=e3f9bf5cea"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"pub\/museum","name":"Museum","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/museum\/screenshot.png?w=434"],"description":"Museum is a theme crafted to showcase all of your best photographs, drawings, or illustrations. Featuring elegant, museum-inspired typography and ample room for your images, Museum pays special attention to category and media attachment pages to help your collections shine.","author":"Kelly Dwan &amp; Mel Choyce","authorAndUri":"<a href=\"http:\/\/themes.redradar.net\/\">Kelly Dwan &amp; Mel Choyce<\/a>","version":"1.0.2-wpcom","tags":"Une colonne, Mise en page adaptable, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, Photoblogging, Noir, Rouge, Blanc, Clair","parent":false,"active":false,"trendingRank":105,"popularityRank":308,"launchDate":"2014-11-26","demoUrl":"https:\/\/museumdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmuseum&amp;_wpnonce=b46994874a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmuseum","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/mirror","name":"Mirror","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/mirror\/screenshot.png?w=434"],"description":"Mirror is a blog focused theme showcasing large featured images and clear typography. A large featured content slider in the header helps your top content to shine.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.0","tags":"Gris, Vert, Argent, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, flexible-heade, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, cartoon, Vacances, journal, lifestream, magazine, music, nature, Photoblogging, photography, bright, clean, conservative, contemporary, curved, elegant, Clair, minimal, modern","parent":false,"active":false,"trendingRank":106,"popularityRank":259,"launchDate":"2015-01-07","demoUrl":"https:\/\/mirrordemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmirror&amp;_wpnonce=9457ecd6a3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmirror","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/mirror&#038;ref=themesphp&#038;_wpnonce=9457ecd6a3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/harmonic","name":"Harmonic","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/harmonic\/screenshot.png?w=434"],"description":"Harmonic makes your content sing. No matter if you are a band looking to get a record deal, a travel blogger wanting to document your trip around the world or just someone that wants to make their home on WordPress.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.11-wpcom","tags":"Noir, Blanc, Une colonne, Deux colonnes, Mise en page fluide, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, Photoblogging, photography, music, portfolio, clean, contemporary, minimal, Sombre, professional, simple","parent":false,"active":false,"trendingRank":107,"popularityRank":170,"launchDate":"2014-10-06","demoUrl":"https:\/\/harmonicdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fharmonic&amp;_wpnonce=7c030e8cd7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fharmonic","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/solar","name":"Solar","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/solar\/screenshot.png?w=434"],"description":"A clean and modern blog theme made for those sophisticated writers who live to write and value simplicity and elegance mixture. Experience unique workflow and just write your blog. You will love it!","author":"Themes Kingdom","authorAndUri":"<a href=\"http:\/\/www.themeskingdom.com\">Themes Kingdom<\/a>","version":"1.0","tags":"Mise en page adaptable, Une colonne, Deux colonnes, Trois colonnes, Noir, Gris, Vert, Blanc, Sombre, Clair, Images \u00e0 la Une, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Format d&rsquo;article, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":108,"popularityRank":252,"launchDate":"2015-02-17","demoUrl":"https:\/\/solardemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fsolar&amp;_wpnonce=54cdea7446","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fsolar","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/solar&#038;ref=themesphp&#038;_wpnonce=54cdea7446"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/scrawl","name":"Scrawl","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/scrawl\/screenshot.png?w=434"],"description":"A clean, responsive theme for long-form writing, with bold featured images, fancy image captions and pull quotes, and plenty of space for your content to shine. A slide-out sidebar provides ready access to all your secondary content, including social links, custom menu, and widgets.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.8-wpcom","tags":"blog, journal, Clair, simple, Gris, Blanc, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, En-t\u00eate flexible, Images \u00e0 la Une, \u00c9diteur de style, Format d&rsquo;article, clean, minimal, Une colonne, Support des langues RTL, Options du th\u00e8me, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Mise en page fixe, Mise en page adaptable, site-logo","parent":false,"active":false,"trendingRank":109,"popularityRank":312,"launchDate":"2015-03-16","demoUrl":"https:\/\/scrawldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fscrawl&amp;_wpnonce=b922856772","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fscrawl","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/broadsheet","name":"Broadsheet","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/broadsheet\/screenshot.png?w=434"],"description":"Broadsheet is a newspaper theme. With 3 optional widget areas, and a huge homepage slider there are lots of options for creating interesting, immersive websites.","author":"Pro Theme Design","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/by\/pro-theme-design\">Pro Theme Design<\/a>","version":"1.1.4","tags":"Noir, Gris, Blanc, Clair, Une colonne, Deux colonnes, Trois colonnes, Quatre colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, education, gaming, magazine, news, conservative, formal, industrial, minimal, professional, simple, site-logo","parent":false,"active":false,"trendingRank":119,"popularityRank":143,"launchDate":"2014-03-06","demoUrl":"https:\/\/broadsheetdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbroadsheet&amp;_wpnonce=aeca7bd18b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbroadsheet","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/broadsheet&#038;ref=themesphp&#038;_wpnonce=aeca7bd18b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/spirit","name":"Spirit","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/spirit\/screenshot.png?w=434"],"description":"A merry and bright blogging theme. Happy holidays!","author":"Caroline Moore","authorAndUri":"<a href=\"http:\/\/carolinemoore.net\/\">Caroline Moore<\/a>","version":"1.1.1-wpcom","tags":"Format d&rsquo;article, En-t\u00eate flexible, Menu personnalis\u00e9, Saisonnier, Mod\u00e8le pleine largeur, Article mis en avant, Blanc, Bleu, Rouge, Vacances, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, D\u00e9filement Infini, Mise en page adaptable, blog, lifestream, journal, tumblelog, Saisonnier, cartoon, bright, clean, colorful, Clair, whimsical, vibrant, textured, playful","parent":false,"active":false,"trendingRank":111,"popularityRank":350,"launchDate":"2013-12-12","demoUrl":"https:\/\/spiritdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fspirit&amp;_wpnonce=4e1e978a29","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fspirit","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/editor","name":"Editor","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/editor\/screenshot.png?w=434"],"description":"Editor puts bold and beautiful publishing right at your fingertips with comfortable, legible typography and large featured images. Using Featured Posts, you can display your favorite articles or editorials in the sidebar for even more exposure. Please open the readme.txt file to learn how to use Editor.","author":"Array","authorAndUri":"<a href=\"https:\/\/array.is\/\">Array<\/a>","version":"1.0.5-wpcom","tags":"Clair, Blanc, Gris, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, blog, Photoblogging, clean, modern","parent":false,"active":false,"trendingRank":112,"popularityRank":282,"launchDate":"2014-11-05","demoUrl":"https:\/\/editordemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Feditor&amp;_wpnonce=8db93f10d5","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Feditor","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/vision","name":"Vision","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/vision\/screenshot.png?w=434"],"description":"Vision is a clean portfolio and photography theme with a flat minimal design. Perfect for showcasing your skills.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.3","tags":"Noir, Gris, Orange, Sombre, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, design, fashion, Photoblogging, photography, portfolio, scrapbooking, clean, conservative, contemporary, elegant, formal, geometric, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":112,"popularityRank":269,"launchDate":"2013-12-19","demoUrl":"https:\/\/visiondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fvision&amp;_wpnonce=d04fc01f4c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fvision","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/vision&#038;ref=themesphp&#038;_wpnonce=d04fc01f4c"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/mh-magazine","name":"MH Magazine","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/mh-magazine\/screenshot.png?w=434"],"description":"This is a clean, modern and fully responsive premium magazine WordPress theme for online magazines, news websites and other editorial websites. The theme includes custom widgets, shortcodes and advanced theme options to create amazing websites within a few minutes.","author":"MH Themes","authorAndUri":"<a href=\"http:\/\/www.mhthemes.com\/\">MH Themes<\/a>","version":"1.1.4","tags":"blog, magazine, news, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Options du th\u00e8me, threaded-comments, Mod\u00e8le pleine largeur, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL","parent":false,"active":false,"trendingRank":114,"popularityRank":54,"launchDate":"2014-02-20","demoUrl":"https:\/\/mhmagazinedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmh-magazine&amp;_wpnonce=75c3f41f14","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmh-magazine","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/mh-magazine&#038;ref=themesphp&#038;_wpnonce=75c3f41f14"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>59","purchased":false}},{"id":"premium\/nurture","name":"Nurture","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/nurture\/screenshot.png?w=434"],"description":"Un th\u00e8me parental pour Maman et Papa","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Gris, Vert, Rouge, Jaune, Sombre, Une colonne, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, craft, journal, scrapbooking, tumblelog, colorful, hand-drawn, handcrafted","parent":false,"active":false,"trendingRank":115,"popularityRank":329,"launchDate":"2013-09-12","demoUrl":"https:\/\/nurturedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fnurture&amp;_wpnonce=9c3234f286","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fnurture","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/nurture&#038;ref=themesphp&#038;_wpnonce=9c3234f286"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/bosco","name":"Bosco","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/bosco\/screenshot.png?w=434"],"description":"Un th\u00e8me parfait pour votre blog personnel, avec une mise en page adapt\u00e9e pour mobiles et une belle typographie.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.2-wpcom","tags":"D\u00e9j\u00e0 accessible, Mise en page adaptable, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Support des langues RTL, \u00c9diteur de style, Format d&rsquo;article, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, journal, Photoblogging, Rouge, Noir, Blanc, clean, bright, elegant, Clair, minimal, modern, simple, traditional","parent":false,"active":false,"trendingRank":116,"popularityRank":358,"launchDate":"2014-06-03","demoUrl":"https:\/\/boscodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbosco&amp;_wpnonce=5c22c76252","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbosco","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/mystique","name":"Mystique","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/mystique\/screenshot.png?w=434"],"description":"Packed with six layout options, six color schemes, a spot for you to link to four popular social network profiles, and support for aside, image, and quote post formats, Mystique can meet the needs of many types of blogs. Further customize the design by adding a custom header and background.","author":"digitalnature","authorAndUri":"<a href=\"http:\/\/digitalnature.eu\">digitalnature<\/a>","version":"2.6-wpcom","tags":"Sombre, Clair, Blanc, Vert, Bleu, Rouge, Rose, Violet, Deux colonnes, Trois colonnes, Une colonne, Mise en page fixe, Colonne lat\u00e9rale droite, Colonne lat\u00e9rale gauche, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, nature, outdoors, travel, bright, colorful","parent":false,"active":false,"trendingRank":117,"popularityRank":15,"launchDate":"2011-04-21","demoUrl":"https:\/\/mystiquedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmystique&amp;_wpnonce=90ae0233c7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmystique","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/ari","name":"Ari","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/ari\/screenshot.png?w=434"],"description":"A beautifully designed minimalistic blog theme. It comes with two color schemes and allows you to customize links and text colors. Also it supports a custom header, a custom background, a custom menu and two optional widget areas in sidebars. Together, all of these features help you to control how to present your blog to your readers.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/wordpress-themes\/\">Elmastudio<\/a>","version":"1.1.3-wpcom","tags":"Noir, Vert, Blanc, Clair, Sombre, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, journal, clean, Sombre, elegant, Clair, minimal, modern, simple, traditional","parent":false,"active":false,"trendingRank":118,"popularityRank":220,"launchDate":"2012-03-20","demoUrl":"https:\/\/aridemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fari&amp;_wpnonce=e8dbcb8d29","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fari","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/dynamic-news","name":"Dynamic News","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/dynamic-news\/screenshot.png?w=434"],"description":"A responsive, multipurpose blogging and magazine theme with bold colors and fonts. It comes with a featured content slider, custom widgets, and a magazine page template.","author":"ThemeZee","authorAndUri":"<a href=\"http:\/\/themezee.com\">ThemeZee<\/a>","version":"1.0","tags":"blog, business, collaboration, education, fashion, food, gaming, Vacances, journal, magazine, nature, news, sports, travel, abstract, clean, conservative, contemporary, elegant, formal, minimal, modern, professional, simple, traditional, vibrant, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, Article mis en avant, threaded-comments, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page fluide, Mise en page adaptable, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Trois colonnes, Clair, Noir, Orange, Marron, Rouge, Blanc, Vert, Bleu, Violet, Gris","parent":false,"active":false,"trendingRank":119,"popularityRank":77,"launchDate":"2014-04-02","demoUrl":"https:\/\/dynamicnewsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fdynamic-news&amp;_wpnonce=0125141d9d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fdynamic-news","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/dynamic-news&#038;ref=themesphp&#038;_wpnonce=0125141d9d"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>65","purchased":false}},{"id":"pub\/splendio","name":"Splendio","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/splendio\/screenshot.png?w=434"],"description":"The Splendio theme dazzles with an unconventional yet stylish design that pops out of the box \u2014 literally. Despite its fun exterior, Splendio supports featured header images, six widget areas (one in the right sidebar and five in the footer), custom background, custom header, and a showcase page template with a featured slider for sticky posts.","author":"Design Disease","authorAndUri":"<a href=\"http:\/\/designdisease.com\/\">Design Disease<\/a>","version":"1.1.2-wpcom","tags":"art, artwork, blog, craft, design, fashion, journal, scrapbooking, travel, abstract, artistic, bright, colorful, curved, geometric, playful, vibrant, Bleu, Gris, Orange, Ocre, Blanc, Jaune, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Couleurs personnalis\u00e9es","parent":false,"active":false,"trendingRank":122,"popularityRank":11,"launchDate":"2012-02-07","demoUrl":"https:\/\/splendiodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsplendio&amp;_wpnonce=dd9bd4445a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsplendio","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/plane","name":"Plane","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/plane\/screenshot.png?w=434"],"description":"Plane is a versatile blog theme, featuring classic, two-column layout and clean, modern design.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.2-wpcom","tags":"Blanc, Bleu, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, D\u00e9filement Infini, Article mis en avant, site-logo, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, threaded-comments","parent":false,"active":false,"trendingRank":121,"popularityRank":224,"launchDate":"2014-12-04","demoUrl":"https:\/\/planedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fplane&amp;_wpnonce=18ccfbec21","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fplane","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/gridiculous-pro","name":"Gridiculous Pro","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/gridiculous-pro\/screenshot.png?w=434"],"description":"Gridiculous Pro is a beautifully designed responsive theme that&rsquo;ll help make your website stand out on any device. With stunning typography, large images and multiple layout options, you can easily create a unique website to suit your needs.","author":"c.bavota","authorAndUri":"<a href=\"http:\/\/bavotasan.com\/\">c.bavota<\/a>","version":"1.0.9","tags":"Noir, Gris, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, Couleurs personnalis\u00e9es, Mod\u00e8le pleine largeur, minimal, modern, professional, blog, business, clean, conservative, formal, textured","parent":false,"active":false,"trendingRank":122,"popularityRank":161,"launchDate":"2014-03-04","demoUrl":"https:\/\/gridiculousprodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fgridiculous-pro&amp;_wpnonce=a23ce9abe3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fgridiculous-pro","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/gridiculous-pro&#038;ref=themesphp&#038;_wpnonce=a23ce9abe3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/designfolio","name":"Designfolio","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/designfolio\/screenshot.png?w=434"],"description":"A fully responsive portfolio theme for designers and creatives.","author":"Press Coders","authorAndUri":"<a href=\"http:\/\/www.presscoders.com\/\">Press Coders<\/a>","version":"1.2","tags":"Noir, Bleu, Marron, Gris, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Colonne lat\u00e9rale gauche, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, Images \u00e0 la Une, Mod\u00e8le pleine largeur, design, Photoblogging, portfolio, photography, clean, contemporary, professional, Curseur d'article, Mise en page adaptable, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":123,"popularityRank":294,"launchDate":"2014-04-29","demoUrl":"https:\/\/designfoliodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fdesignfolio&amp;_wpnonce=98458cd40d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fdesignfolio","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/designfolio&#038;ref=themesphp&#038;_wpnonce=98458cd40d"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/ubud","name":"Ubud","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/ubud\/screenshot.png?w=434"],"description":"Ubud is an elegant, minimal photography blog theme with a responsive 1-5 column image grid and square, portrait or landscape image format options. Ubud also offers a four-column footer widget area and easy-to-use theme options to customize your blog.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/en\/\">Elmastudio<\/a>","version":"1.0.3-wpcom","tags":"Blanc, Noir, Clair, Mise en page fluide, Mise en page adaptable, Une colonne, Deux colonnes, Trois colonnes, Quatre colonnes, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, D\u00e9filement Infini, Options du th\u00e8me, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, design, Photoblogging, photography, portfolio, travel, clean, minimal, modern, professional, contemporary, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Support des langues RTL","parent":false,"active":false,"trendingRank":124,"popularityRank":37,"launchDate":"2014-04-02","demoUrl":"https:\/\/ubuddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fubud&amp;_wpnonce=d42f1e399d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fubud","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/ubud&#038;ref=themesphp&#038;_wpnonce=d42f1e399d"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>18","purchased":false}},{"id":"pub\/sidespied","name":"Sidespied","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sidespied\/screenshot.png?w=434"],"description":"A portfolio child theme of Espied. Great for showing off your photographs or images.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"Vert, Noir, Blanc, Une colonne, Mise en page fixe, Mise en page fluide, Mise en page adaptable, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, Photoblogging, photography, portfolio, clean, contemporary, elegant, geometric, Clair, minimal, modern, professional, simple, sophisticated","parent":"Espied","active":false,"trendingRank":125,"popularityRank":349,"launchDate":"2014-05-22","demoUrl":"https:\/\/sidespieddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsidespied&amp;_wpnonce=49a0196cc1","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsidespied","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/chronicle","name":"Chronicle","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/chronicle\/screenshot.png?w=434"],"description":"Chronicle is a magazine theme. With 3 optional widget areas, featured posts, and a huge homepage slider, there are lots of options for creating interesting, immersive websites.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.0-wpcom","tags":"Gris, Rouge, Blanc, Clair, Une colonne, Deux colonnes, Trois colonnes, Quatre colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, education, gaming, magazine, music, news, bright, clean, conservative, contemporary, formal, geometric, industrial, Clair, minimal, modern, professional, sophisticated, site-logo","parent":"Broadsheet","active":false,"trendingRank":126,"popularityRank":132,"launchDate":"2014-05-22","demoUrl":"https:\/\/chronicledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fchronicle&amp;_wpnonce=04f559c192","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fchronicle","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/chronicle&#038;ref=themesphp&#038;_wpnonce=04f559c192"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/pocket","name":"Pocket","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/pocket\/screenshot.png?w=434"],"description":"Pocket est un th\u00e8me WordPress facile d\u2019utilisation, afin de partager vos images, vid\u00e9os, articles, citations et plus. Utilisez le pour un blog personnel, ou un portofolio minimaliste pour montrer vos derniers ouvrages.","author":"Array","authorAndUri":"<a href=\"https:\/\/array.is\">Array<\/a>","version":"5.2.2","tags":"Blanc, Gris, Rouge, Sombre, Blanc, Une colonne, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Format d&rsquo;article, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, photography, Photoblogging, clean, minimal, modern, simple, contemporary, journal, D\u00e9filement Infini, threaded-comments","parent":false,"active":false,"trendingRank":127,"popularityRank":293,"launchDate":"2014-06-27","demoUrl":"https:\/\/pocketdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpocket&amp;_wpnonce=2d74d167d3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpocket","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/pocket&#038;ref=themesphp&#038;_wpnonce=2d74d167d3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"pub\/choco","name":"Choco","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/choco\/screenshot.png?w=434"],"description":"Stylish WordPress theme with two columns, right-sidebar, and three available color schemes.","author":"CSSMayo","authorAndUri":"<a href=\"http:\/\/cssmayo.com\/\">CSSMayo<\/a>","version":"0.1.1-wpcom","tags":"Sombre, Marron, Rouge, Gris, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Options du th\u00e8me, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, artwork, craft, journal, blog, artistic, colorful, contemporary","parent":false,"active":false,"trendingRank":128,"popularityRank":25,"launchDate":"2011-02-25","demoUrl":"https:\/\/chocodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fchoco&amp;_wpnonce=38d5ce77b5","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fchoco","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/circa","name":"Circa","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/circa\/screenshot.png?w=434"],"description":"Circa is a minimal, one-column theme for your personal blog. Post formats are highlighted with an icon surrounded by a circle shape and displayed in a colorful style. The responsive design for this theme looks great on any device, large or small.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.2-wpcom","tags":"Vert, Rose, Jaune, Marron, Clair, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, lifestream, tumblelog, bright, clean, colorful, geometric, modern, playful, simple, whimsical, minimal, vibrant","parent":"Hexa","active":false,"trendingRank":129,"popularityRank":303,"launchDate":"2014-02-25","demoUrl":"https:\/\/circademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcirca&amp;_wpnonce=0703cbabd6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcirca","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/oxygen","name":"Oxygen","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/oxygen\/screenshot.png?w=434"],"description":"Minimalistic, mobile-optimized magazine theme with responsive layout. The main features include a featured post slider, custom front page template, custom header, custom background, seven widget areas, and three custom menus.","author":"AlienWP","authorAndUri":"<a href=\"http:\/\/alienwp.com\/\">AlienWP<\/a>","version":"1.0.1-wpcom","tags":"Blanc, Clair, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, design, fashion, journal, magazine, music, news, professional, travel, bright, clean, contemporary, elegant, geometric, Clair, minimal, modern, simple, sophisticated","parent":false,"active":false,"trendingRank":130,"popularityRank":16,"launchDate":"2012-05-10","demoUrl":"https:\/\/oxygendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Foxygen&amp;_wpnonce=829948ae36","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Foxygen","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/retro-mac-os","name":"Retro MacOS","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/retro-mac-os\/screenshot.png?w=434"],"description":"A whimsical homage to the days in black and white, celebrating the magic of Mac OS. Dress up your blog with retro, chunky-grade pixellated graphics to evoke some serious computer nostalgia. Supports a custom menu, custom header image, custom background, two footer widget areas, and a full-width page template.","author":"Stuart Brown","authorAndUri":"<a href=\"http:\/\/stua.rtbrown.org\/\">Stuart Brown<\/a>","version":"1.1.1-wpcom","tags":"Noir, Gris, Argent, Blanc, Sombre, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Pr\u00eat \u00e0 \u00eatre traduit, announcement, blog, cartoon, design, journal, lifestream, funny, geometric, hand-drawn, humorous, minimal, playful, retro, simple, tech, whimsical","parent":false,"active":false,"trendingRank":131,"popularityRank":261,"launchDate":"2011-10-07","demoUrl":"https:\/\/retromacosdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fretro-mac-os&amp;_wpnonce=6e3eb68638","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fretro-mac-os","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/profile","name":"Profil","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/profile\/screenshot.png?w=434"],"description":"Profile is designed to showcase the best about you. The theme may act as a self promotion tool, resume, portfolio, blog or hub for all your web endeavors. Profile features several social media options for sharing yourself with the world. Really, it&rsquo;s all about you.","author":"Organic Themes","authorAndUri":"<a href=\"http:\/\/www.organicthemes.com\">Organic Themes<\/a>","version":"1.0","tags":"art, artwork, blog, design, portfolio, clean, contemporary, elegant, Clair, minimal, modern, professional, sophisticated, simple, Gris, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Curseur d'article, Article mis en avant, formal, lifestream, business, travel, journal","parent":false,"active":false,"trendingRank":132,"popularityRank":18,"launchDate":"2013-06-27","demoUrl":"https:\/\/profiledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fprofile&amp;_wpnonce=6390884c6b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fprofile","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/profile&#038;ref=themesphp&#038;_wpnonce=6390884c6b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/cocoa","name":"Cocoa","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/cocoa\/screenshot.png?w=434"],"description":"Cocoa is a fresh, easy-to-use, minimal blog theme focussing on high-quality typography and a beautiful responsive design. The theme features a unique header and footer widget area, custom About, Social Links (via a custom menu) and Recent Post by Category widgets and aesthetic, minimal post formats. Cocoas makes is easy to start a blog that will look beautiful from your first post.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/en\/\">Elmastudio<\/a>","version":"1.1-wpcom","tags":"bright, Blanc, Clair, Mise en page fluide, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, design, fashion, food, journal, lifestream, Photoblogging, travel, clean, contemporary, elegant, minimal, modern, simple, sophisticated","parent":false,"active":false,"trendingRank":133,"popularityRank":87,"launchDate":"2014-07-01","demoUrl":"https:\/\/cocoathemedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcocoa&amp;_wpnonce=2550ca6ad3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcocoa","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/cocoa&#038;ref=themesphp&#038;_wpnonce=2550ca6ad3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>18","purchased":false}},{"id":"pub\/forever","name":"Forever","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/forever\/screenshot.png?w=434"],"description":"Le th\u00e8me Forever vous permet de pr\u00e9senter votre mariage avec un joli WordPress. Vous pouvez faire admirer \u00e0 tout le monde vos plus belles photos et mettre en valeur chaque d\u00e9tail important pour le grand jour et apr\u00e8s.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.3-wpcom","tags":"wedding, bright, clean, contemporary, elegant, formal, Clair, modern, simple, sophisticated, traditional, Blanc, Argent, Bleu, Deux colonnes, Une colonne, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Microformats, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Mod\u00e8le pleine largeur","parent":false,"active":false,"trendingRank":133,"popularityRank":17,"launchDate":"2012-01-12","demoUrl":"https:\/\/foreverdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fforever&amp;_wpnonce=c6945b587c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fforever","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/organization","name":"Organisation","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/organization\/screenshot.png?w=434"],"description":"Organization est un th\u00e8me business (entre guillemets !) bien \u00e9quilibr\u00e9 et complet qui a \u00e9t\u00e9 cr\u00e9\u00e9 en pensant aux organisations \u00e0 buts non lucratifs et \u00e9cologiques.","author":"Organic Themes","authorAndUri":"<a href=\"http:\/\/www.organicthemes.com\">Organic Themes<\/a>","version":"1.0","tags":"blog, clean, contemporary, elegant, Clair, minimal, modern, professional, sophisticated, simple, earthy, traditional, Gris, Blanc, Vert, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Colonne lat\u00e9rale gauche, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Curseur d'article, Article mis en avant, formal, lifestream, business, travel, journal, education, news, nature, outdoors, magazine","parent":false,"active":false,"trendingRank":135,"popularityRank":42,"launchDate":"2013-08-22","demoUrl":"https:\/\/organizationdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Forganization&amp;_wpnonce=f999203610","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Forganization","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/organization&#038;ref=themesphp&#038;_wpnonce=f999203610"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/finder","name":"Finder","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/finder\/screenshot.png?w=434"],"description":"A contemporary photoblog theme with a beautifully simple one-column layout and equally clean typography. Designed with a responsive layout that looks great on large displays, tablets and mobile devices.","author":"The Theme Foundry","authorAndUri":"<a href=\"https:\/\/thethemefoundry.com\">The Theme Foundry<\/a>","version":"201506191857","tags":"abstract, art, artistic, artwork, Noir, blog, bright, clean, contemporary, craft, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, design, \u00c9diteur de style, fashion, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Clair, minimal, modern, Une colonne, Photoblogging, photography, portfolio, Mise en page adaptable, scrapbooking, simple, sophisticated, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, video, Blanc","parent":false,"active":false,"trendingRank":136,"popularityRank":364,"launchDate":"2015-06-23","demoUrl":"https:\/\/finderdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Ffinder&amp;_wpnonce=8f54bbe554","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Ffinder","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/finder&#038;ref=themesphp&#038;_wpnonce=8f54bbe554"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/quadra","name":"Quadra","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/quadra\/screenshot.png?w=434"],"description":"Quadra is a tumblelog-style theme for your personal blog. Featured images are supported, and different post formats are highlighted with a unique icon in a square shape. The design is responsive and looks great on any device, large or small.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.3-wpcom","tags":"Bleu, Gris, Orange, Clair, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, lifestream, tumblelog, bright, clean, colorful, geometric, modern, playful, simple, whimsical, minimal, vibrant","parent":"Hexa","active":false,"trendingRank":137,"popularityRank":342,"launchDate":"2014-02-25","demoUrl":"https:\/\/quadrademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fquadra&amp;_wpnonce=434c5c9339","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fquadra","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/shine-on","name":"Shine On","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/shine-on\/screenshot.png?w=434"],"description":"A seasonal personal blogging theme featuring original illustration by Jacqui Oakley (http:\/\/jacquioakley.com\/)","author":"Automattic","authorAndUri":"<a href=\"http:\/\/wordpress.com\">Automattic<\/a>","version":"1.0-wpcom","tags":"Violet, Orange, Ocre, Blanc, Jaune, Clair, Une colonne, Mise en page fluide, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Microformats, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Mise en page adaptable, blog, journal, lifestream, tumblelog, abstract, bright, clean, colorful, flamboyant, playful, vibrant, Saisonnier, hand-drawn, whimsical, Couleurs personnalis\u00e9es, Mise en page fixe, En-t\u00eate flexible","parent":"Twenty Thirteen","active":false,"trendingRank":138,"popularityRank":219,"launchDate":"2013-12-05","demoUrl":"https:\/\/shineondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fshine-on&amp;_wpnonce=032c7be853","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fshine-on","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/collections","name":"Collections","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/collections\/screenshot.png?w=434"],"description":"A creative and responsive theme designed to help you share videos, photos, and music. Each content type is displayed in its own unique handcrafted style. Perfect for those who use different post formats.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"1.1.6b-wpcom","tags":"art, blog, craft, music, Photoblogging, photography, tumblelog, video, artistic, clean, contemporary, Sombre, elegant, handcrafted, minimal, modern, simple, Bleu, Gris, Vert, Orange, Rouge, Jaune, Une colonne, Mise en page fluide, Mise en page adaptable, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":139,"popularityRank":285,"launchDate":"2013-10-07","demoUrl":"https:\/\/collectionsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcollections&amp;_wpnonce=57bdec50c9","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcollections","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/collections&#038;ref=themesphp&#038;_wpnonce=57bdec50c9"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/fictive","name":"Fictive","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/fictive\/screenshot.png?w=434"],"description":"Fictive, c&rsquo;est vous &#8211; votre style, votre look, votre histoire. Rendez-le personnel avec une image d&rsquo;en-t\u00eate personnalis\u00e9e, un Gravatar, et des liens vers vos r\u00e9seaux sociaux pr\u00e9f\u00e9r\u00e9s. Utilisez les formats d&rsquo;article pour mettre en forme votre contenu, ajoutez un menu et des widgets personnalis\u00e9s, ou restez simples avec une en-t\u00eate fixe.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.2-wpcom","tags":"Marron, Orange, Bleu, Rouge, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, lifestream, tumblelog, clean, colorful, contemporary, elegant, modern, minimal, simple, vibrant","parent":false,"active":false,"trendingRank":140,"popularityRank":156,"launchDate":"2014-04-15","demoUrl":"https:\/\/fictivedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ffictive&amp;_wpnonce=e15ab8359d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ffictive","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/puzzle","name":"Puzzle","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/puzzle\/screenshot.png?w=434"],"description":"Puzzle est un th\u00e8me visuel, id\u00e9al pour les photographes et artistes qui d\u00e9sirent raconter des r\u00e9cits \u00e0 travers leurs images.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.5","tags":"Noir, Vert, Blanc, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, craft, design, food, gaming, lifestream, magazine, music, Photoblogging, photography, portfolio, scrapbooking, clean, conservative, contemporary, earthy, faded, minimal, modern, natural, simple, sophisticated, site-logo","parent":false,"active":false,"trendingRank":152,"popularityRank":110,"launchDate":"2014-06-06","demoUrl":"https:\/\/puzzledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpuzzle&amp;_wpnonce=a196329659","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpuzzle","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/puzzle&#038;ref=themesphp&#038;_wpnonce=a196329659"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/linen","name":"Linen","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/linen\/screenshot.png?w=434"],"description":"A clean and flexible magazine style theme. Features custom typography options, custom background support, and a featured post slider.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"1.3.19-wpcom","tags":"blog, business, journal, news, travel, real-estate, bright, elegant, magazine, modern, photography, clean, handcrafted, Clair, minimal, simple, Mise en page fixe, Deux colonnes, Blanc, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Curseur d'article, Article mis en avant, Colonne lat\u00e9rale droite, Couleurs personnalis\u00e9es, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":142,"popularityRank":13,"launchDate":"2011-04-28","demoUrl":"https:\/\/linendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Flinen&amp;_wpnonce=e0d4a2988e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Flinen","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/linen&#038;ref=themesphp&#038;_wpnonce=e0d4a2988e"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/sixteen-nine","name":"Sixteen Nine","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/sixteen-nine\/screenshot.png?w=434"],"description":"Th\u00e8me HTML5, mobile et adaptable cr\u00e9\u00e9 pour le framework Genesis.","author":"StudioPress","authorAndUri":"<a href=\"http:\/\/www.studiopress.com\/\">StudioPress<\/a>","version":"1.0.1","tags":"Noir, Blanc, Une colonne, Deux colonnes, Mise en page adaptable, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":"Genesis","active":false,"trendingRank":143,"popularityRank":276,"launchDate":"2014-02-28","demoUrl":"https:\/\/sixteenninedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fsixteen-nine&amp;_wpnonce=fedc986395","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fsixteen-nine","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/sixteen-nine&#038;ref=themesphp&#038;_wpnonce=fedc986395"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/nexus","name":"Nexus","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/nexus\/screenshot.png?w=434"],"description":"Nexus est un th\u00e8me unique bas\u00e9 sur une grille, au graphisme superbe et adaptable.","author":"Elegant Themes","authorAndUri":"<a href=\"http:\/\/www.elegantthemes.com\">Elegant Themes<\/a>","version":"1.0","tags":"art, blog, design, magazine, Photoblogging, photography, artistic, clean, colorful, contemporary, elegant, modern, Bleu, Blanc, Colonne lat\u00e9rale gauche, Deux colonnes, Mise en page adaptable, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":144,"popularityRank":159,"launchDate":"2013-07-18","demoUrl":"https:\/\/nexusdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fnexus&amp;_wpnonce=671142a36b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fnexus","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/nexus&#038;ref=themesphp&#038;_wpnonce=671142a36b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>68","purchased":false}},{"id":"pub\/babylog","name":"Babylog","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/babylog\/screenshot.png?w=434"],"description":"A sweet, illustrated theme for baby blogs featuring four color palettes and a customizable baby header graphic.","author":"Caroline Moore","authorAndUri":"<a href=\"http:\/\/carolinemoore.net\/\">Caroline Moore<\/a>","version":"1.0.1-wpcom","tags":"blog, cartoon, journal, lifestream, scrapbooking, colorful, curved, Clair, playful, traditional, whimsical, hand-drawn, Bleu, Rose, Vert, Violet, Clair, Marron, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":145,"popularityRank":245,"launchDate":"2012-10-11","demoUrl":"https:\/\/babylogdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbabylog&amp;_wpnonce=2ed43159de","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbabylog","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/adventure","name":"Adventure","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/adventure\/screenshot.png?w=434"],"description":"Un th\u00e8me cr\u00e9\u00e9 pour partager vos voyages et vos aventures.","author":"Organic Themes","authorAndUri":"<a href=\"http:\/\/www.organicthemes.com\">Organic Themes<\/a>","version":"1.0.2","tags":"art, artwork, blog, design, Photoblogging, photography, portfolio, clean, contemporary, elegant, Clair, minimal, modern, professional, simple, Gris, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Curseur d'article, Article mis en avant","parent":false,"active":false,"trendingRank":146,"popularityRank":65,"launchDate":"2013-11-14","demoUrl":"https:\/\/adventuredemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fadventure&amp;_wpnonce=18c6c83284","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fadventure","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/adventure&#038;ref=themesphp&#038;_wpnonce=18c6c83284"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/infoway","name":"InfoWay","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/infoway\/screenshot.png?w=434"],"description":"InfoWay is clean, simple, elegant and responsive. Well-suited for general blogging, InfoWay highlights your featured content in style with a unique built-in slider. InfoWay is very simple to manage with the Theme Customizer; easily add your own logo image, as well as links to your social network pages. The sidebar and footer areas are widgetized to allow you infinite ways to customize your site, and InfoWay also includes a full-width page template. You will love having your site built on InfoWay.","author":"InkThemes","authorAndUri":"<a href=\"http:\/\/www.inkthemes.com\">InkThemes<\/a>","version":"1.0","tags":"Noir, Clair, Orange, Blanc, Gris, Sombre, Une colonne, Deux colonnes, Mise en page adaptable, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Options du th\u00e8me, Article mis en avant, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, Curseur d'article, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, blog, business, design, bright, clean, simple, modern, minimal","parent":false,"active":false,"trendingRank":147,"popularityRank":178,"launchDate":"2013-09-19","demoUrl":"https:\/\/infowaydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Finfoway&amp;_wpnonce=59a436de35","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Finfoway","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/infoway&#038;ref=themesphp&#038;_wpnonce=59a436de35"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>70","purchased":false}},{"id":"pub\/next-saturday","name":"Next Saturday","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/next-saturday\/screenshot.png?w=434"],"description":"Add a touch of childlike innocence to your blog with Next Saturday, a bold and playful theme. Originally designed by Ian Mintz, Next Saturday features styling for muliple post formats, custom background and header support, and a right sidebar.","author":"Ian Mintz","authorAndUri":"<a href=\"http:\/\/www.ianmintz.com\/\">Ian Mintz<\/a>","version":"1.2.1-wpcom","tags":"Sombre, Bleu, Marron, Vert, Rouge, Jaune, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Article mis en avant, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Format d&rsquo;article, blog, journal, lifestream, tumblelog, video, colorful, contemporary, Sombre, geometric, playful, simple, vibrant, D\u00e9filement Infini, school, education","parent":false,"active":false,"trendingRank":149,"popularityRank":270,"launchDate":"2011-08-04","demoUrl":"https:\/\/nextsaturdaydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fnext-saturday&amp;_wpnonce=17eb3eb235","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fnext-saturday","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/panel","name":"Panel","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/panel\/screenshot.png?w=434"],"description":"A modern theme that makes it quick and easy to publish a webcomic.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.2-wpcom","tags":"Noir, Marron, Orange, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, cartoon, clean, Clair, minimal, modern, professional, traditional","parent":false,"active":false,"trendingRank":149,"popularityRank":291,"launchDate":"2013-07-10","demoUrl":"https:\/\/paneldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fpanel&amp;_wpnonce=595934a838","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fpanel","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/celsius","name":"Celsius","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/celsius\/screenshot.png?w=434"],"description":"Celsius provides a pure, white backdrop for your writing, photography, or videography. With a design that looks great on any device, large or small, Celsius supports multiple post formats, slide-out navigation and widget areas, and bold featured images. Clear out the clutter and let your content speak for itself.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"blog, photography, elegant, Clair, minimal, Blanc, Clair, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, journal, tumblelog, Photoblogging, simple, Images \u00e0 la Une, Format d&rsquo;article, D\u00e9filement Infini, En-t\u00eate flexible, Mise en page fixe, Mise en page adaptable","parent":"Isola","active":false,"trendingRank":148,"popularityRank":311,"launchDate":"2014-08-07","demoUrl":"https:\/\/celsiusdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcelsius&amp;_wpnonce=9e32d8b526","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcelsius","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/adelle","name":"Adelle","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/adelle\/screenshot.png?w=434"],"description":"Avec un design noir et blanc \u00e9l\u00e9gant accentu\u00e9 par des tons gris et roses doux, Adelle apporte sophistication et \u00e9l\u00e9gance \u00e0 n&rsquo;importe quel blog.","author":"BluChic","authorAndUri":"<a href=\"http:\/\/bluchic.com\/\">BluChic<\/a>","version":"1.0.5-wpcom","tags":"blog, craft, fashion, food, journal, clean, elegant, geometric, minimal, modern, sophisticated, Noir, Rose, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":151,"popularityRank":48,"launchDate":"2013-04-04","demoUrl":"https:\/\/adelledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fadelle&amp;_wpnonce=276f62469a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fadelle","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/timepiece","name":"Timepiece","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/timepiece\/screenshot.png?w=434"],"description":"Timepiece est con&ccedil;u pour mettre en valeur vos archives. Remontez le temps comme on remonte un fleuve, pour la gloire d&rsquo;un pass&eacute; haut en couleur, dans une mise en page simple et minimaliste.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"Noir, Gris, Blanc, Jaune, Une colonne, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, lifestream, minimal, simple","parent":false,"active":false,"trendingRank":152,"popularityRank":315,"launchDate":"2012-10-05","demoUrl":"https:\/\/timepiecedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftimepiece&amp;_wpnonce=7ce642c069","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftimepiece","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/matala","name":"Matala","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/matala\/screenshot.png?w=434"],"description":"Matala is a colorful, textured theme that supports two widget areas, six post formats, and several customization options, including custom background, custom header and an optional random image gallery on single image pages.","author":"Matt Mullenweg","authorAndUri":"<a href=\"http:\/\/ma.tt\/themes\/\">Matt Mullenweg<\/a>","version":"1.6-wpcom","tags":"D\u00e9filement Infini, Ocre, Bleu, Marron, Orange, Rouge, Blanc, Clair, Deux colonnes, Une colonne, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Options du th\u00e8me, Article mis en avant, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Images \u00e0 la Une, Format d&rsquo;article, artwork, blog, Photoblogging, cartoon, craft, design, journal, fashion, scrapbooking, artistic, colorful, grungy, handcrafted, playful, textured, vibrant, whimsical","parent":false,"active":false,"trendingRank":153,"popularityRank":33,"launchDate":"2011-07-12","demoUrl":"https:\/\/matalademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmatala&amp;_wpnonce=e93af0df75","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmatala","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/port","name":"Port","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/port\/screenshot.png?w=434"],"description":"A sleek and stylish agency theme","author":"ThemeTrust","authorAndUri":"<a href=\"http:\/\/themetrust.com\">ThemeTrust<\/a>","version":"1.1.7-wpcom","tags":"Couleurs personnalis\u00e9es, art, portfolio, blog, fashion, lifestream, travel, bright, clean, elegant, Clair, minimal, modern, Une colonne, \u00c9diteur de style, Support des langues RTL, Article mis en avant, artwork, journal, Photoblogging, design, simple, sophisticated, contemporary, Images \u00e0 la Une, D\u00e9filement Infini, En-t\u00eate flexible, Mise en page fluide, Mise en page adaptable, Options du th\u00e8me, Blanc, Deux colonnes, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, Menu personnalis\u00e9","parent":false,"active":false,"trendingRank":154,"popularityRank":62,"launchDate":"2014-07-01","demoUrl":"https:\/\/portthemedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fport&amp;_wpnonce=a5f95398a4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fport","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/port&#038;ref=themesphp&#038;_wpnonce=a5f95398a4"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/oslo","name":"Oslo","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/oslo\/screenshot.png?w=434"],"description":"Oslo is a stunning two-column theme fit for portfolio and general blog use, built around a customizable sidebar and beautiful typography.","author":"Pixel Union","authorAndUri":"<a href=\"http:\/\/www.pixelunion.net\/\">Pixel Union<\/a>","version":"1.3.1","tags":"Clair, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Mise en page adaptable, Images \u00e0 la Une, \u00c9diteur de style, En-t\u00eate flexible, D\u00e9filement Infini, Article mis en avant, Options du th\u00e8me, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, art, artwork, blog, colorful, craft, design, fashion, journal, magazine, Photoblogging, photography, portfolio, clean, contemporary, elegant, minimal, modern, professional, simple, sophisticated, urban","parent":false,"active":false,"trendingRank":155,"popularityRank":211,"launchDate":"2014-05-13","demoUrl":"https:\/\/oslodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Foslo&amp;_wpnonce=497fdf9579","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Foslo","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/oslo&#038;ref=themesphp&#038;_wpnonce=497fdf9579"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/outspoken","name":"Outspoken","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/outspoken\/screenshot.png?w=434"],"description":"A highly customizable WordPress theme developed for news websites, magazines &amp; blogs. Outspoken is a responsive, clean, simple &amp; easy to customize. Theme specifically designed for your new website, blog or online magazine.","author":"WPShower","authorAndUri":"<a href=\"http:\/\/wpshower.com\/\">WPShower<\/a>","version":"1.0","tags":"Blanc, Clair, Orange, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Colonne lat\u00e9rale gauche, Mod\u00e8le pleine largeur, Personnalisation de l&rsquo;en-t\u00eate, Curseur d'article, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Format d&rsquo;article, Support des langues RTL, Options du th\u00e8me, D\u00e9filement Infini, Pr\u00eat \u00e0 \u00eatre traduit, magazine, photography, business, professional, conservative, traditional, Images \u00e0 la Une","parent":false,"active":false,"trendingRank":156,"popularityRank":206,"launchDate":"2014-01-29","demoUrl":"https:\/\/outspokendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Foutspoken&amp;_wpnonce=d03fc9ec8d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Foutspoken","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/outspoken&#038;ref=themesphp&#038;_wpnonce=d03fc9ec8d"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>68","purchased":false}},{"id":"pub\/adaption","name":"Adaption","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/adaption\/screenshot.png?w=434"],"description":"A theme that adapts to your content, making sure it looks good on any device. Full width featured images make your content stand out. This theme adapts as add widgets with a 3rd column added to the layout.","author":"Automattic","authorAndUri":"<a href=\"http:\/\/themes.wordpress.com\/\">Automattic<\/a>","version":"1.0.7-wpcom","tags":"Noir, Blanc, Rouge, Trois colonnes, Deux colonnes, Mise en page adaptable, Mise en page fluide, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Photoblogging, photography, clean, contemporary, Clair, minimal, modern, simple, professional, Arri\u00e8re-plan personnalis\u00e9, blog, journal","parent":false,"active":false,"trendingRank":157,"popularityRank":255,"launchDate":"2014-07-09","demoUrl":"https:\/\/adaptiondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fadaption&amp;_wpnonce=9588f14a02","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fadaption","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"vip\/partner-mlb-modern","name":"MLB \"Modern\"","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/vip\/partner-mlb-modern\/screenshot.png?w=434"],"description":"The Official Major League Baseball &laquo;&nbsp;Modern&nbsp;&raquo; theme for WordPress.com. By activating this theme, you agree to the MLB <a href=\"http:\/\/mlb.mlb.com\/mlb\/official_info\/about_mlb_com\/terms_of_use.jsp\">terms of service<\/a>.","author":"MLB","authorAndUri":"<a href=\"http:\/\/www.mlb.com\">MLB<\/a>","version":"1.0","tags":"mlb, major-league-baseball, partner, sports, modern, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Options du th\u00e8me, blog, Clair, minimal, modern, vibrant","parent":false,"active":false,"trendingRank":158,"popularityRank":292,"launchDate":"2011-05-16","demoUrl":"https:\/\/partnermlbmoderndemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=vip%2Fpartner-mlb-modern&amp;_wpnonce=8cbf4a7079","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=vip%2Fpartner-mlb-modern","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/little-story","name":"Little Story","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/little-story\/screenshot.png?w=434"],"description":"Un th\u00e8me ludique et tendre, illustr\u00e9 par Laura Amiss","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"Jaune, Bleu, Blanc, Ocre, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Microformats, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, cartoon, craft, design, fashion, journal, lifestream, school, scrapbooking, tumblelog, artistic, bright, colorful, flamboyant, flowery, grungy, hand-drawn, Clair, paper-made, playful, sophisticated, textured, vibrant, whimsical, Mise en page adaptable, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":159,"popularityRank":188,"launchDate":"2013-03-21","demoUrl":"https:\/\/littlestorydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Flittle-story&amp;_wpnonce=41df301cfc","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Flittle-story","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/little-story&#038;ref=themesphp&#038;_wpnonce=41df301cfc"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/monster","name":"Monster","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/monster\/screenshot.png?w=434"],"description":"Boo! A spookyriffic monster theme with lots of tricks and treats.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.1-wpcom","tags":"Vacances, cartoon, Saisonnier, colorful, Sombre, playful, whimsical, funny, humorous, Noir, Gris, Vert, Blanc, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":160,"popularityRank":234,"launchDate":"2012-10-05","demoUrl":"https:\/\/monsterdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmonster&amp;_wpnonce=cb4aeb80c4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmonster","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/expound","name":"Expound","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/expound\/screenshot.png?w=434"],"description":"Un impressionant th\u00e8me magazine pour votre site d&rsquo;actualit\u00e9s. Une disposition r\u00e9active, des aper\u00e7us des publications en vignettes, des mises en avant de billets et plus encore.","author":"Konstantin Kovshenin","authorAndUri":"<a href=\"http:\/\/kovshenin.com\">Konstantin Kovshenin<\/a>","version":"1.6.1-wpcom","tags":"Noir, Bleu, bright, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Arri\u00e8re-plan personnalis\u00e9, Images \u00e0 la Une, Menu personnalis\u00e9, Format d&rsquo;article, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Mod\u00e8le pleine largeur, clean, Couleurs personnalis\u00e9es, D\u00e9filement Infini, magazine, news, professional, Mise en page adaptable, Support des langues RTL","parent":false,"active":false,"trendingRank":161,"popularityRank":91,"launchDate":"2013-08-22","demoUrl":"https:\/\/expounddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fexpound&amp;_wpnonce=80e1bf62f1","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fexpound","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/photographer","name":"Photographer","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/photographer\/screenshot.png?w=434"],"description":"Une solution superbe et simple pour exposer des photos de mani\u00e8re professionnelle. Le th\u00e8me propose le choix d&rsquo;un portfolio \u00e0 1, 2 et 3 colonnes, un mod\u00e8le de diaporama, un diaporama d&rsquo;accueil et un cadre r\u00e9actif pour afficher le contenu de mani\u00e8re adapt\u00e9e sur de nombreux types d&rsquo;appareils.","author":"Organic Themes","authorAndUri":"<a href=\"http:\/\/www.organicthemes.com\">Organic Themes<\/a>","version":"1.4.5","tags":"art, artwork, blog, design, Photoblogging, photography, portfolio, clean, contemporary, elegant, Clair, minimal, modern, professional, sophisticated, simple, Gris, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, fashion, D\u00e9filement Infini, Curseur d'article, scrapbooking, Article mis en avant, wedding","parent":false,"active":false,"trendingRank":168,"popularityRank":30,"launchDate":"2013-03-07","demoUrl":"https:\/\/photographerdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fphotographer&amp;_wpnonce=c7173211b6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fphotographer","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/photographer&#038;ref=themesphp&#038;_wpnonce=c7173211b6"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/bouquet","name":"Bouquet","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/bouquet\/screenshot.png?w=434"],"description":"Bouquet is an elegant, simple theme inspired by the beauty found in flowers. Notable features include two floral schemes, a responsive layout structure that adapts to smaller devices, a right sidebar, a full-width template, support for post formats, custom background, and custom header.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.5-wpcom","tags":"Bleu, Orange, Rose, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page adaptable, D\u00e9filement Infini, blog, craft, journal, nature, outdoors, Photoblogging, clean, curved, earthy, flowery, natural, simple, sophisticated","parent":false,"active":false,"trendingRank":163,"popularityRank":86,"launchDate":"2011-11-10","demoUrl":"https:\/\/bouquetdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbouquet&amp;_wpnonce=502387be1b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbouquet","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/manifest","name":"Manifest","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/manifest\/screenshot.png?w=434"],"description":"Manifest est un th&amp;egrave;me au design &eacute;pur&eacute; et &amp;agrave; la typographie soign&amp;eacute;e, r&amp;eacute;solument tourn&amp;eacute; vers le contenu, sans autre fioriture. Son option d&rsquo;image d&rsquo;en-t&amp;ecirc;te vous permet n&amp;eacute;anmoins de le personnaliser tr&egrave;s facilement. Il supporte divers formats d&rsquo;articles dont image, lien, et apart&amp;eacute;.","author":"Jim Barraud","authorAndUri":"<a href=\"http:\/\/jimbarraud.com\">Jim Barraud<\/a>","version":"1.01-wpcom","tags":"D\u00e9filement Infini, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page fixe, Une colonne, Blanc, Clair, minimal, simple, art, blog, journal, tumblelog","parent":false,"active":false,"trendingRank":164,"popularityRank":20,"launchDate":"2011-07-14","demoUrl":"https:\/\/manifestdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmanifest&amp;_wpnonce=411882a8d3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmanifest","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/traveler","name":"Traveler","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/traveler\/screenshot.png?w=434"],"description":"A photography theme, perfect for bloggers who want to document their travels with large photos, dramatic colors and Pinterest-style layouts.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.1","tags":"Bleu, Gris, Sombre, Une colonne, Deux colonnes, Mise en page adaptable, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, art, photography, lifestream, travel, contemporary, elegant, professional, clean, craft, journal, Photoblogging, scrapbooking, simple, site-logo","parent":false,"active":false,"trendingRank":179,"popularityRank":153,"launchDate":"2013-09-19","demoUrl":"https:\/\/travelerdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Ftraveler&amp;_wpnonce=5380f87dc7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Ftraveler","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/traveler&#038;ref=themesphp&#038;_wpnonce=5380f87dc7"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/photolia","name":"Photolia","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/photolia\/screenshot.png?w=434"],"description":"Photolia is a responsive photoblogging theme that makes displaying your photography dead simple and amazingly beautiful. Photolia offers crisp typography with great readability and resizable media for any device or screen size.","author":"UpThemes","authorAndUri":"<a href=\"http:\/\/upthemes.com\/\">UpThemes<\/a>","version":"1.3.6","tags":"Blanc, Clair, sophisticated, simple, professional, minimal, formal, clean, tumblelog, video, travel, Photoblogging, photography, portfolio, lifestream, design, blog, Pr\u00eat \u00e0 \u00eatre traduit, Article mis en avant, Support des langues RTL, Format d&rsquo;article, D\u00e9filement Infini, Mod\u00e8le pleine largeur, En-t\u00eate flexible, Image d&rsquo;en-t\u00eate \u00e0 la Une, \u00c9diteur de style, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Mise en page adaptable, Une colonne","parent":false,"active":false,"trendingRank":166,"popularityRank":263,"launchDate":"2013-12-19","demoUrl":"https:\/\/photoliademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fphotolia&amp;_wpnonce=b08d39b8cd","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fphotolia","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/photolia&#038;ref=themesphp&#038;_wpnonce=b08d39b8cd"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/piano-black","name":"Piano Black","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/piano-black\/screenshot.png?w=434"],"description":"This dark and elegant theme showcases your content with a techny, sophisticated design. Make it yours with a header image, background, and custom menu, and optional RSS and Search areas in the header. Includes a full-width-template for dropping the sidebar on pages.","author":"mono-lab","authorAndUri":"<a href=\"http:\/\/www.mono-lab.net\">mono-lab<\/a>","version":"2.3.2-wpcom","tags":"Noir, Sombre, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, gaming, journal, clean, contemporary, curved, Sombre, elegant, metallic, tech, textured","parent":false,"active":false,"trendingRank":172,"popularityRank":66,"launchDate":"2011-07-20","demoUrl":"https:\/\/pianoblackdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fpiano-black&amp;_wpnonce=d0aa1a76c2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fpiano-black","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/isola","name":"Isola","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/isola\/screenshot.png?w=434"],"description":"Isola is a fresh, clean slate for your best works, perfect for showcasing your writing, photographs, or videos in a bold way. Its primary menu and widget area are tucked behind a handy button, giving your content plenty of room to breathe, and Isola looks beautiful regardless of the device or screen size.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.4-wpcom","tags":"blog, lifestream, photography, clean, Blanc, Clair, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, journal, Photoblogging, simple, Images \u00e0 la Une, Format d&rsquo;article, D\u00e9filement Infini, Mise en page fixe, Mise en page adaptable","parent":false,"active":false,"trendingRank":168,"popularityRank":309,"launchDate":"2014-07-09","demoUrl":"https:\/\/isolademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fisola&amp;_wpnonce=9277a0824b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fisola","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/spun","name":"Spun","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/spun\/screenshot.png?w=434"],"description":"Spun est un th\u00e8me minimaliste qui met l\u2019accent sur votre contenu. La navigation superflue s\u2019efface pour laisser la vedette \u00e0 vos textes et images au premier-plan et au centre. Que vous soyez \u00e9crivain, photographe ou blogueur, la magnifique typographie et le graphisme adaptable de Spun mettent en valeur votre cr\u00e9ativit\u00e9 avec une \u00e9l\u00e9gance subtile.","author":"Caroline Moore","authorAndUri":"<a href=\"http:\/\/carolinemoore.net\/\">Caroline Moore<\/a>","version":"2.0.6-wpcom","tags":"Clair, Une colonne, Mise en page fixe, Blanc, Gris, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Couleurs personnalis\u00e9es, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Options du th\u00e8me, art, artwork, design, portfolio, photography, Photoblogging, tumblelog, clean, conservative, elegant, faded, minimal, modern, simple, artistic, Noir, Mise en page adaptable","parent":false,"active":false,"trendingRank":169,"popularityRank":84,"launchDate":"2013-11-19","demoUrl":"https:\/\/spundemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fspun&amp;_wpnonce=3b72c1645f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fspun","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/opti","name":"Opti","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/opti\/screenshot.png?w=434"],"description":"Un th\u00e8me magazine produisant un WordPress \u00e9l\u00e9gant, avec un design adaptatif et la prise en charge des widgets, des vignettes d&rsquo;aper\u00e7u des publications, des en-t\u00eates et arri\u00e8re-plans personnalis\u00e9s.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/prothemedesign.com\">Pro Theme Design<\/a>","version":"1.2","tags":"Noir, Bleu, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, magazine, news, professional, clean, conservative, contemporary, Sombre, elegant, modern, sophisticated, site-logo","parent":false,"active":false,"trendingRank":170,"popularityRank":59,"launchDate":"2012-11-08","demoUrl":"https:\/\/optidemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fopti&amp;_wpnonce=026a0aaff2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fopti","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/opti&#038;ref=themesphp&#038;_wpnonce=026a0aaff2"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/motif","name":"Motif","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/motif\/screenshot.png?w=434"],"description":"Motif est un th\u00e8me professionnel pimpant, minimaliste et enti\u00e8rement adaptable.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.9-wpcom","tags":"Gris, Rouge, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Couleurs personnalis\u00e9es, D\u00e9filement Infini, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Microformats, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, design, portfolio, bright, clean, conservative, elegant, formal, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":171,"popularityRank":52,"launchDate":"2014-01-02","demoUrl":"https:\/\/motifdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmotif&amp;_wpnonce=0d5b5a3dd6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmotif","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/lovebirds","name":"Lovebirds","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/lovebirds\/screenshot.png?w=434"],"description":"Un superbe th\u00e8me de mariage pour vous aider \u00e0 organiser tout les d\u00e9tails avant le grand jour.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.1-wpcom","tags":"Couleurs personnalis\u00e9es, D\u00e9filement Infini, Mise en page adaptable, Rose, Marron, colorful, whimsical, textured, traditional, wedding, elegant, colorful, Blanc, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Images \u00e0 la Une, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit","parent":"Forever","active":false,"trendingRank":171,"popularityRank":201,"launchDate":"2012-08-13","demoUrl":"https:\/\/lovebirdsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Flovebirds&amp;_wpnonce=3528b1b45b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Flovebirds","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/pictorico","name":"Pictorico","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/pictorico\/screenshot.png?w=434"],"description":"A single-column, grid-based portfolio theme with large featured images and a post slider, perfect for photoblogging or a portfolio site.","author":"WordPress.com","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">WordPress.com<\/a>","version":"1.0.8-wpcom","tags":"Noir, Bleu, Sombre, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, design, Photoblogging, photography, portfolio, clean, conservative, minimal, modern, professional","parent":false,"active":false,"trendingRank":173,"popularityRank":180,"launchDate":"2014-05-01","demoUrl":"https:\/\/pictoricodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fpictorico&amp;_wpnonce=341278140e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fpictorico","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/dusk-to-dawn","name":"Dusk To Dawn","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/dusk-to-dawn\/screenshot.png?w=434"],"description":"A dark theme that melds old-style organic ornaments with modern design and typography. It features a custom header, custom background, and a widget area in the sidebar. It comes with support for several post formats including aside, gallery, image, quote, link, chat, and audio.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.3.2-wpcom","tags":"Noir, Bleu, Violet, Sombre, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, blog, design, journal, nature, abstract, artistic, curved, elegant, flowery, grungy, retro, textured","parent":false,"active":false,"trendingRank":174,"popularityRank":29,"launchDate":"2011-10-13","demoUrl":"https:\/\/dusktodawndemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fdusk-to-dawn&amp;_wpnonce=41c21d5026","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fdusk-to-dawn","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/gridspace","name":"Gridspace","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/gridspace\/screenshot.png?w=434"],"description":"Pr\u00e9sentez clairement vos images avec ce th\u00e8me portfolio simple et adaptable, offrant de multiples choix de couleur et de mises en page.","author":"Graph Paper Press","authorAndUri":"<a href=\"http:\/\/graphpaperpress.com\">Graph Paper Press<\/a>","version":"1.1.4","tags":"Noir, Blanc, Clair, Sombre, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Mise en page adaptable, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, Photoblogging, photography, portfolio, art, design, clean, minimal, modern","parent":false,"active":false,"trendingRank":175,"popularityRank":21,"launchDate":"2012-09-06","demoUrl":"https:\/\/gridspacedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fgridspace&amp;_wpnonce=67e67a6092","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fgridspace","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/gridspace&#038;ref=themesphp&#038;_wpnonce=67e67a6092"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/lens","name":"Lens","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/lens\/screenshot.png?w=434"],"description":"Lens is a photo-oriented theme, great for people who like to tell stories with pictures, equally suitable for bloggers, scrapbookers, and writers.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"10.1.2","tags":"Gris, Argent, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, craft, design, fashion, food, gaming, Photoblogging, photography, bright, clean, conservative, contemporary, elegant, formal, geometric, industrial, Clair, minimal, modern, professional, simple, tech, site-logo","parent":false,"active":false,"trendingRank":178,"popularityRank":187,"launchDate":"2014-02-20","demoUrl":"https:\/\/lensdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Flens&amp;_wpnonce=16ce4bffed","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Flens","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/lens&#038;ref=themesphp&#038;_wpnonce=16ce4bffed"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/chunk","name":"Chunk","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/chunk\/screenshot.png?w=434"],"description":"A straightforward theme with bold typography designed by <a href=\"http:\/\/twitter.com\/thisistran\/\">Tran N<\/a>. Featuring multiple post formats, custom background, custom menu, and custom header. Also comes with an optional footer widget area.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.3.2-wpcom","tags":"Clair, Blanc, Mise en page fixe, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, art, blog, cartoon, Vacances, journal, lifestream, tumblelog, bright, clean, contemporary, flamboyant, modern","parent":false,"active":false,"trendingRank":177,"popularityRank":36,"launchDate":"2011-08-24","demoUrl":"https:\/\/chunkdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fchunk&amp;_wpnonce=10cec581ad","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fchunk","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/adventure-journal","name":"Adventure Journal","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/adventure-journal\/screenshot.png?w=434"],"description":"Adventure Journal is the perfect theme for highlighting your adventures. Choose your own layout, sidebar and footer widgets, header image, and background if you want to customize. Perfect for your next trip. Or your next blog.","author":"Contexture International","authorAndUri":"<a href=\"http:\/\/www.contextureintl.com\/\">Contexture International<\/a>","version":"2.0.1-wpcom","tags":"education, school, Marron, Sombre, Clair, Ocre, Jaune, natural, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, blog, lifestream, nature, Photoblogging, scrapbooking, travel, colorful, contemporary, earthy, hand-drawn, handcrafted, retro, paper-made, textured, whimsical, Couleurs personnalis\u00e9es","parent":false,"active":false,"trendingRank":178,"popularityRank":105,"launchDate":"2011-11-23","demoUrl":"https:\/\/adventurejournaldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fadventure-journal&amp;_wpnonce=22c11a2382","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fadventure-journal","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/silesia","name":"Silesia","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/silesia\/screenshot.png?w=434"],"description":"A clean and elegant blogging theme with an expanding left sidebar and great Post Format support","author":"NattyWP","authorAndUri":"<a href=\"http:\/\/www.nattywp.com\/\">NattyWP<\/a>","version":"1.0.7-wpcom","tags":"education, school, Blanc, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Couleurs personnalis\u00e9es, D\u00e9filement Infini, blog, Clair, clean, elegant, modern","parent":false,"active":false,"trendingRank":179,"popularityRank":295,"launchDate":"2013-01-24","demoUrl":"https:\/\/silesiademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsilesia&amp;_wpnonce=dd42c2e9ad","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsilesia","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/publisher","name":"Publisher","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/publisher\/screenshot.png?w=434"],"description":"Avec Publisher, organisez un album \u00e9clectique de photos, de vid\u00e9os, de fichiers audio, etc. Avec sa mise en page adaptable de style ma\u00e7onnerie, Publisher a de l\u2019allure sur vos appareils mobiles comme sur votre PC.","author":"Array","authorAndUri":"<a href=\"https:\/\/array.is\">Array<\/a>","version":"2.2.8","tags":"Bleu, Gris, Clair, Blanc, Une colonne, Colonne lat\u00e9rale droite, Deux colonnes, Mise en page fluide, Mise en page adaptable, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, clean, contemporary, minimal, Photoblogging, portfolio, simple","parent":false,"active":false,"trendingRank":205,"popularityRank":149,"launchDate":"2013-08-01","demoUrl":"https:\/\/publisherdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpublisher&amp;_wpnonce=b131e2e523","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpublisher","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/publisher&#038;ref=themesphp&#038;_wpnonce=b131e2e523"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"pub\/pachyderm","name":"Pachyderm","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/pachyderm\/screenshot.png?w=434"],"description":"Un th\u00e8me de micro-blog mignon, net et adaptable.","author":"Caroline Moore","authorAndUri":"<a href=\"http:\/\/www.carolinemoore.net\">Caroline Moore<\/a>","version":"1.4.3-wpcom","tags":"blog, cartoon, craft, design, journal, lifestream, Photoblogging, school, scrapbooking, tumblelog, bright, clean, colorful, funny, humorous, Clair, modern, playful, textured, vibrant, whimsical, Bleu, Vert, Rose, Jaune, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":181,"popularityRank":162,"launchDate":"2013-03-21","demoUrl":"https:\/\/pachydermdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fpachyderm&amp;_wpnonce=3fefd1469c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fpachyderm","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/handmade","name":"Handmade","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/handmade\/screenshot.png?w=434"],"description":"A beautiful retro-styled theme for foodies and crafters that&rsquo;s sure to delight even the most creative bloggers.","author":"Obox Themes","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/by\/obox-themes\/\">Obox Themes<\/a>","version":"1.0-wpcom","tags":"Bleu, Ocre, Jaune, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, craft, food, scrapbooking, colorful, handcrafted, textured","parent":false,"active":false,"trendingRank":157,"popularityRank":238,"launchDate":"2013-05-09","demoUrl":"https:\/\/handmadedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fhandmade&amp;_wpnonce=63e4b949b4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fhandmade","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/handmade&#038;ref=themesphp&#038;_wpnonce=63e4b949b4"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>80","purchased":false}},{"id":"pub\/suits","name":"Suits","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/suits\/screenshot.png?w=434"],"description":"Pour blogs et sites web. Un design &eacute;pur&eacute;, un code efficace, et un outil de personnalisation qui vous valorise.","author":"Theme Weaver","authorAndUri":"<a href=\"http:\/\/www.themeweaver.net\/\">Theme Weaver<\/a>","version":"1.0.3-wpcom","tags":"Noir, Gris, Blanc, Sombre, Une colonne, Deux colonnes, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Microformats, D\u00e9filement Infini, Format d&rsquo;article","parent":false,"active":false,"trendingRank":183,"popularityRank":82,"launchDate":"2014-01-08","demoUrl":"https:\/\/suitsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsuits&amp;_wpnonce=67aa8197d6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsuits","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/something-fishy","name":"Something Fishy","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/something-fishy\/screenshot.png?w=434"],"description":"An animated undersea theme with a fun, whimsical design.","author":"Caroline Moore","authorAndUri":"<a href=\"http:\/\/carolinemoore.net\">Caroline Moore<\/a>","version":"1.1-wpcom","tags":"education, cartoon, blog, outdoors, school, bright, colorful, flamboyant, funny, humorous, modern, playful, vibrant, whimsical, Couleurs personnalis\u00e9es, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Bleu, Marron, Orange, Colonne lat\u00e9rale droite, Deux colonnes, Article mis en avant, Mise en page fixe, Images \u00e0 la Une, Format d&rsquo;article, Pr\u00eat \u00e0 \u00eatre traduit, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Support des langues RTL, Gris, Clair, nature, Mise en page adaptable","parent":false,"active":false,"trendingRank":184,"popularityRank":190,"launchDate":"2012-10-25","demoUrl":"https:\/\/somethingfishydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsomething-fishy&amp;_wpnonce=0624d285a8","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsomething-fishy","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/chalkboard","name":"Chalkboard","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/chalkboard\/screenshot.png?w=434"],"description":"A whimsical theme emulating a classic school chalkboard, complete with a bottom-resting eraser and chalk.","author":"Edward R. Jenkins","authorAndUri":"<a href=\"http:\/\/www.edwardrjenkins.com\">Edward R. Jenkins<\/a>","version":"2.4.1-wpcom","tags":"blog, education, school, scrapbooking, Saisonnier, tumblelog, Sombre, funny, playful, simple, textured, whimsical, hand-drawn, humorous, Noir, Jaune, Colonne lat\u00e9rale droite, Une colonne, Deux colonnes, Mise en page fixe, Mise en page adaptable, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":185,"popularityRank":168,"launchDate":"2013-02-20","demoUrl":"https:\/\/chalkboarddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fchalkboard&amp;_wpnonce=3196aef9a2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fchalkboard","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/san-kloud","name":"San Kloud","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/san-kloud\/screenshot.png?w=434"],"description":"San Kloud is a blogging theme focused on typography and content. Includes three color schemes and supports custom header image and custom background.","author":"Theme.fm","authorAndUri":"<a href=\"http:\/\/theme.fm\/\">Theme.fm<\/a>","version":"1.0.6-wpcom","tags":"Bleu, Vert, Orange, Jaune, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, cartoon, journal, lifestream, tumblelog, bright, colorful, curved, flamboyant, funny, humorous, playful, vibrant, whimsical, En-t\u00eate flexible","parent":false,"active":false,"trendingRank":186,"popularityRank":233,"launchDate":"2012-03-20","demoUrl":"https:\/\/sanklouddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsan-kloud&amp;_wpnonce=e112a382bc","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsan-kloud","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/pretty-young-thing","name":"Pretty Young Thing","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/pretty-young-thing\/screenshot.png?w=434"],"description":"Pretty Young Thing is vibrant, hand-crafted theme that will capture the essence of your everyday life.","author":"StudioPress","authorAndUri":"<a href=\"http:\/\/www.studiopress.com\">StudioPress<\/a>","version":"1.0.2","tags":"blog, craft, scrapbooking, artistic, bright, colorful, handcrafted, wedding, Bleu, Marron, Vert, Orange, Rose, Violet, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":"Genesis","active":false,"trendingRank":187,"popularityRank":49,"launchDate":"2011-03-02","demoUrl":"https:\/\/prettyyoungthingdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpretty-young-thing&amp;_wpnonce=c8ccbad687","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpretty-young-thing","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/pretty-young-thing&#038;ref=themesphp&#038;_wpnonce=c8ccbad687"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/ascetica","name":"Ascetica","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/ascetica\/screenshot.png?w=434"],"description":"A minimal theme with responsive layout, sticky posts slider, and a plenty of widget space to suit any blogger.","author":"AlienWP","authorAndUri":"<a href=\"http:\/\/alienwp.com\/\">AlienWP<\/a>","version":"1.0.1-wpcom","tags":"blog, clean, minimal, Blanc, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":188,"popularityRank":251,"launchDate":"2012-09-06","demoUrl":"https:\/\/asceticademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fascetica&amp;_wpnonce=0701409978","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fascetica","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/themorningafter","name":"The Morning After","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/themorningafter\/screenshot.png?w=434"],"description":"Un th&egrave;me magazine classique dot&eacute; des options d&rsquo;en-t&ecirc;te et arri&egrave;re-plan personnalis&eacute;s. The Morning After supporte jusqu&rsquo;&agrave; trois zones widgets en page d&rsquo;accueil, o&ugrave; il expose vos articles vedettes au sommet de la page, et agr&eacute;mente vos derniers articles d&rsquo;images \u00e0 la Une. Il dispose en outre d&rsquo;options dans l&rsquo;&eacute;diteur visuel, d&rsquo;une page disponible en pleine largeur qui supprime la sidebar, et d&rsquo;un format Apart&amp;eacute; au style particulier.","author":"WooThemes","authorAndUri":"<a href=\"http:\/\/www.woothemes.com\">WooThemes<\/a>","version":"3.2.5-wpcom","tags":"Blanc, Gris, Clair, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Options du th\u00e8me, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Article mis en avant, Mod\u00e8le pleine largeur, Images \u00e0 la Une, Format d&rsquo;article, \u00c9diteur de style, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, magazine, news, professional, clean","parent":false,"active":false,"trendingRank":189,"popularityRank":56,"launchDate":"2011-04-08","demoUrl":"https:\/\/themorningafterdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fthemorningafter&amp;_wpnonce=d257d5a9f7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fthemorningafter","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/highwind","name":"Highwind","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/highwind\/screenshot.png?w=434"],"description":"Highwind is a lightweight, free WordPress theme designed to showcase content. It features a clean, responsive design with a strong focus on typography, plus a bunch of presentational options and widgetised regions allowing you to give your site a unique touch.","author":"James Koster","authorAndUri":"<a href=\"http:\/\/jameskoster.co.uk\">James Koster<\/a>","version":"1.0.1-wpcom","tags":"blog, journal, bright, clean, Clair, simple, Bleu, Blanc, Gris, Colonne lat\u00e9rale droite, Deux colonnes, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":184,"popularityRank":228,"launchDate":"2013-09-05","demoUrl":"https:\/\/highwinddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fhighwind&amp;_wpnonce=d1e4144698","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fhighwind","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/cheer","name":"Cheer","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/cheer\/screenshot.png?w=434"],"description":"Celebrate the holidays with Cheer, a whimsical, textured holiday theme featuring illustrations from The Fox and King.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.2-wpcom","tags":"Mise en page adaptable, D\u00e9filement Infini, cartoon, art, craft, Vacances, journal, blog, Saisonnier, artistic, colorful, faded, flamboyant, funny, hand-drawn, paper-made, playful, textured, whimsical, vibrant, grungy, Rouge, Vert, Ocre, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":191,"popularityRank":266,"launchDate":"2012-12-04","demoUrl":"https:\/\/cheerdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcheer&amp;_wpnonce=5362fd6c65","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcheer","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/triton-lite","name":"Triton Lite","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/triton-lite\/screenshot.png?w=434"],"description":"Triton Lite is a clean and simple\u2014yet versatile\u2014theme designed with photographers in mind. Its home page and archive pages offer truly dynamic layouts that snap to both the heights and widths of all available content on a page, thus creating tight and tidy post arrangements that beautifully showcase your images.","author":"Towfiq I.","authorAndUri":"<a href=\"http:\/\/www.towfiqi.com\/\">Towfiq I.<\/a>","version":"1.4-wpcom","tags":"Couleurs personnalis\u00e9es, Noir, Sombre, Gris, Clair, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Curseur d'article, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Photoblogging, photography, clean, simple","parent":false,"active":false,"trendingRank":192,"popularityRank":92,"launchDate":"2012-03-08","demoUrl":"https:\/\/tritonlitedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftriton-lite&amp;_wpnonce=cc2b14baf0","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftriton-lite","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/misty-lake","name":"Misty Lake","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/misty-lake\/screenshot.png?w=434"],"description":"Misty Lake vous donne une toile de fond douce et paisible sur laquelle vous pouvez faire briller votre contenu. Il prend en charge cinq formats de publication, une sidebar, et le menu, l&rsquo;en-t\u00eate et le fond sont personnalisables.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.1-wpcom","tags":"blog, journal, nature, outdoors, conservative, faded, Clair, simple, D\u00e9filement Infini, Mise en page adaptable, Vert, Ocre, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":193,"popularityRank":102,"launchDate":"2012-12-20","demoUrl":"https:\/\/mistylakedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmisty-lake&amp;_wpnonce=144a1da136","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmisty-lake","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/soundcheck","name":"Soundcheck","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/soundcheck\/screenshot.png?w=434"],"description":"Th\u00e8me audio aux nombreuses fonctions, parfait pour les groupes, les artistes et les musiciens. Soundcheck propose un curseur de d\u00e9filement des images pleine largeur, un lecteur audio HTML5 personnalis\u00e9, une fonctionnalit\u00e9 spectacles\/\u00e9v\u00e9nements, quatre widgets personnalis\u00e9s, quatre mod\u00e8les de page personnalis\u00e9s et de nombreuses options de th\u00e8me.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"2.3.2","tags":"blog, music, portfolio, clean, modern, professional, Noir, Bleu, Sombre, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Curseur d'article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":194,"popularityRank":32,"launchDate":"2012-07-12","demoUrl":"https:\/\/soundcheckdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fsoundcheck&amp;_wpnonce=36d12117b6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fsoundcheck","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/soundcheck&#038;ref=themesphp&#038;_wpnonce=36d12117b6"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/fiore","name":"Fiore","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/fiore\/screenshot.png?w=434"],"description":"A light, feminine theme in vintage colors, with support for post formats, a fixed toggle sidebar, and a responsive layout for small screens.","author":"Caroline Moore","authorAndUri":"<a href=\"http:\/\/carolinemoore.net\/\">Caroline Moore<\/a>","version":"1.1.2-wpcom","tags":"artistic, colorful, Couleurs personnalis\u00e9es, elegant, Une colonne, Orange, Bleu, blog, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Format d&rsquo;article, Mise en page adaptable, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, Menu personnalis\u00e9","parent":false,"active":false,"trendingRank":195,"popularityRank":199,"launchDate":"2013-07-18","demoUrl":"https:\/\/fioredemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ffiore&amp;_wpnonce=4fe0d6df7a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ffiore","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/sweet-life","name":"Sweet Life","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/sweet-life\/screenshot.png?w=434"],"description":"Sweet Life is an easy to use theme with responsive layout that looks great on any device, big or small. Sweet Life features different post formats, each displayed in their own unique way. If you want to make your blog post more flexible you can use different kinds of post formats such as image, gallery, video, aside, link or quotes.","author":"Anariel Design","authorAndUri":"<a href=\"http:\/\/www.anarieldesign.com\/\">Anariel Design<\/a>","version":"1.0","tags":"Colonne lat\u00e9rale droite, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Mise en page adaptable, Article mis en avant, blog, design, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, news, Marron, food, elegant, artistic, Format d&rsquo;article, art, business, colorful, earthy, modern, natural, sophisticated, Blanc","parent":false,"active":false,"trendingRank":196,"popularityRank":279,"launchDate":"2014-03-14","demoUrl":"https:\/\/sweetlifedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fsweet-life&amp;_wpnonce=99c3a8ea97","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fsweet-life","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/sweet-life&#038;ref=themesphp&#038;_wpnonce=99c3a8ea97"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/retro-fitted","name":"Retro-fitted","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/retro-fitted\/screenshot.png?w=434"],"description":"Subtle textures are mixed with clean lines and shadows to create a beautifully balanced composition perfect for all types of blogs.","author":"Justin Tadlock","authorAndUri":"<a href=\"http:\/\/justintadlock.com\">Justin Tadlock<\/a>","version":"0.2-wpcom","tags":"education, school, blog, journal, retro, textured, traditional, Rose, Ocre, Rouge, Bleu, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":193,"popularityRank":185,"launchDate":"2012-02-14","demoUrl":"https:\/\/retrofitteddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fretro-fitted&amp;_wpnonce=6c8b0dcae9","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fretro-fitted","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/strange-little-town","name":"Strange Little Town","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/strange-little-town\/screenshot.png?w=434"],"description":"This theme will take your readers on a journey to a strange and wonderful place! Nestled below a star-studded sky they will find a cluster of whimsical, crooked little houses covered in a blanket of fog. Some dwellings appear to have minds of their own while others defy the laws of gravity.","author":"Minmin","authorAndUri":"Minmin","version":"1.0-wpcom","tags":"Noir, Rose, Violet, Sombre, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, cartoon, Vacances, Saisonnier, artistic, colorful, playful, whimsical, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":198,"popularityRank":135,"launchDate":"2011-11-01","demoUrl":"https:\/\/strangelittletowndemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fstrange-little-town&amp;_wpnonce=4765c8a620","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fstrange-little-town","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/gigawatt","name":"Gigawatt","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/gigawatt\/screenshot.png?w=434"],"description":"Gigawatt is a clean and bold video display theme that shows off your content in a way that compliments it. Designed especially for film-makers, editors, creatives and professionals working in the motion picture-related industries, Gigawatt can be trusted to display your big screen talents in the best way possible on the small screen.","author":"Obox Themes","authorAndUri":"<a href=\"http:\/\/obox-design.com\">Obox Themes<\/a>","version":"1.0-wpcom","tags":"Noir, Sombre, Gris, Clair, Blanc, Une colonne, Deux colonnes, Quatre colonnes, Mise en page fixe, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, grungy, minimal, video, clean, Sombre, geometric, retro, simple, textured","parent":false,"active":false,"trendingRank":199,"popularityRank":274,"launchDate":"2012-09-20","demoUrl":"https:\/\/gigawattdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fgigawatt&amp;_wpnonce=9eb7d35c73","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fgigawatt","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/gigawatt&#038;ref=themesphp&#038;_wpnonce=9eb7d35c73"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>80","purchased":false}},{"id":"pub\/vertigo","name":"Vertigo","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/vertigo\/screenshot.png?w=434"],"description":"A stylish and fun theme with one column, a custom header, and a custom accent color. It includes special styles for Aside, Gallery, Image, Quote, Link, Chat, Status, Audio and Video post formats. Inspired by the design work of the late Saul Bass, and based on the original design by Matthew Buchanan.","author":"Matthew Buchanan","authorAndUri":"<a href=\"http:\/\/matthewbuchanan.name\/\">Matthew Buchanan<\/a>","version":"1.50.3-wpcom","tags":"Noir, Sombre, Rouge, Une colonne, Mise en page fixe, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, craft, design, tumblelog, artistic, hand-drawn, handcrafted, retro, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":202,"popularityRank":35,"launchDate":"2011-05-09","demoUrl":"https:\/\/vertigodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fvertigo&amp;_wpnonce=efc1380d80","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fvertigo","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/book-lite","name":"Book Lite","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/book-lite\/screenshot.png?w=434"],"description":"Un th\u00e8me de blog classique, style livre, avec de larges polices. Un design \u00e9pur\u00e9 et minimaliste mettant l&rsquo;accent sur votre contenu.","author":"Chandra Maharzan","authorAndUri":"<a href=\"http:\/\/www.wpshoppe.com\/\">Chandra Maharzan<\/a>","version":"109.0.1-wpcom","tags":"blog, education, journal, lifestream, school, tumblelog, clean, conservative, contemporary, elegant, formal, Clair, minimal, professional, simple, Noir, Blanc, Gris, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":201,"popularityRank":71,"launchDate":"2012-12-20","demoUrl":"https:\/\/booklitedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbook-lite&amp;_wpnonce=bbea3ce561","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbook-lite","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/academica","name":"Academica","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/academica\/screenshot.png?w=434"],"description":"Academica is an education- and school-oriented CMS theme with a three-column layout and modern design. It is easy to customize and comes with a custom widget, three templates for Posts and Pages, and a featured content slider.","author":"WPZOOM","authorAndUri":"<a href=\"http:\/\/www.wpzoom.com\/\">WPZOOM<\/a>","version":"1.2.4-wpcom","tags":"education, school, formal, Clair, Bleu, Orange, Blanc, Une colonne, Deux colonnes, Trois colonnes, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Personnalisation de l&rsquo;en-t\u00eate, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite","parent":false,"active":false,"trendingRank":195,"popularityRank":137,"launchDate":"2012-11-20","demoUrl":"https:\/\/academicademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Facademica&amp;_wpnonce=9a5124f917","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Facademica","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/crafty","name":"Crafty","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/crafty\/screenshot.png?w=434"],"description":"Crafty is a general-purpose blogging theme with a bright and playful design. It comes with support for the aside, image, video, quote, and link post formats, a custom header image, custom background, and a widget area in the left column.","author":"CraftyCart","authorAndUri":"<a href=\"http:\/\/craftycart.co.uk\/\">CraftyCart<\/a>","version":"1.0.1-wpcom","tags":"art, blog, craft, education, journal, scrapbooking, bright, colorful, curved, geometric, Clair, playful, retro, whimsical, Bleu, Rouge, Ocre, Blanc, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":203,"popularityRank":151,"launchDate":"2013-02-21","demoUrl":"https:\/\/craftydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcrafty&amp;_wpnonce=31f731d578","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcrafty","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/sunspot","name":"Sunspot","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sunspot\/screenshot.png?w=434"],"description":"A sharp theme with subtle grid lines and sun-splashed accents, Sunspot is a great all-purpose blogging canvas, especially for those who prefer a dark color scheme. Sunspot offers two arrangements for posts on the front page. Additional features include a custom header and a custom background, two optional widget areas, and a responsive layout that adapts gracefully to smaller screen sizes.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.3-wpcom","tags":"Sombre, Noir, Orange, Ocre, Jaune, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Mise en page adaptable, blog, journal, nature, outdoors, clean, geometric","parent":false,"active":false,"trendingRank":208,"popularityRank":47,"launchDate":"2012-03-08","demoUrl":"https:\/\/sunspotdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsunspot&amp;_wpnonce=98db4c8e25","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsunspot","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/nuntius","name":"Nuntius","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/nuntius\/screenshot.png?w=434"],"description":"If you&rsquo;ve been itching to turn your blog into an online newspaper or magazine, Nuntius could be your perfect companion. Based on the highly-popular News theme by Justin Tadlock, Nuntius offers an advanced, news-style page template that lets you highlight sticky posts and featured categories.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.2-wpcom","tags":"D\u00e9filement Infini, Curseur d'article, announcement, blog, magazine, news, professional, bright, clean, conservative, contemporary, Noir, Gris, Orange, Rouge, Blanc, Une colonne, Colonne lat\u00e9rale droite, Deux colonnes, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Microformats, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":205,"popularityRank":124,"launchDate":"2011-12-21","demoUrl":"https:\/\/nuntiusdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fnuntius&amp;_wpnonce=85a090910b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fnuntius","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/duet","name":"Duet","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/duet\/screenshot.png?w=434"],"description":"A dashing responsive two-column newspaper-style theme designed to highlight long-format writing.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\">The Theme Foundry<\/a>","version":"1.4.12-wpcom","tags":"Bleu, Vert, Clair, Orange, Blanc, Mise en page fluide, Une colonne, Colonne lat\u00e9rale droite, Deux colonnes, Mise en page adaptable, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, business, journal, news, travel, clean, elegant, formal, handcrafted, minimal, professional, sophisticated, traditional","parent":false,"active":false,"trendingRank":206,"popularityRank":67,"launchDate":"2012-01-05","demoUrl":"https:\/\/duetdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fduet&amp;_wpnonce=c9c3fb3696","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fduet","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/duet&#038;ref=themesphp&#038;_wpnonce=c9c3fb3696"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/avid","name":"Avid","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/avid\/screenshot.png?w=434"],"description":"Un th\u00e8me innovant et stylis\u00e9 pour les photographes. Avec un blog photos unique, une galerie extr\u00eamement fonctionnelle, une mise en page adaptative et une interface raffin\u00e9e, vous partagez facilement vos clich\u00e9s instantan\u00e9s, vos photographies et votre travail cr\u00e9atif.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"1.5.16-wpcom","tags":"Photoblogging, photography, portfolio, professional, scrapbooking, travel, tumblelog, video, artistic, Sombre, handcrafted, textured, Gris, Sombre, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Article mis en avant, Options du th\u00e8me","parent":false,"active":false,"trendingRank":210,"popularityRank":68,"launchDate":"2012-08-23","demoUrl":"https:\/\/aviddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Favid&amp;_wpnonce=54358e742d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Favid","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/avid&#038;ref=themesphp&#038;_wpnonce=54358e742d"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/shaan","name":"Shaan","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/shaan\/screenshot.png?w=434"],"description":"Set the tone of your blog with a calm, blue ambiance embellished with subtle textures. Shaan presents a cool and casual atmosphere perfect for sharing your thoughts with the world.","author":"Specky Geek","authorAndUri":"<a href=\"http:\/\/www.speckygeek.com\/\">Specky Geek<\/a>","version":"1.1.8-wpcom","tags":"Bleu, Sombre, Colonne lat\u00e9rale droite, Deux colonnes, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, artistic, colorful, elegant, modern, art, artwork, blog, craft, design, journal, nature, scrapbooking","parent":false,"active":false,"trendingRank":208,"popularityRank":210,"launchDate":"2011-11-24","demoUrl":"https:\/\/shaandemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fshaan&amp;_wpnonce=f68c60dc9b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fshaan","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/parament","name":"Parament","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/parament\/screenshot.png?w=434"],"description":"Si vous aimez les jeux de couleurs sombres mais craignez la sobri&eacute;t&eacute;, le th&egrave;me Parament, par ses touches orang&eacute;es et sa texture unique, va vous int&eacute;resser. Et puisqu&rsquo;il supporte les images d&rsquo;en-t&ecirc;te et d&rsquo;arri&egrave;re-plan personnalis&eacute;es, il deviendra vite le meilleur ami de vos caprices. Notez en outre que l&rsquo;option pleine largeur des images cliquables (ou en galerie) permet &agrave; Parament de restituer &laquo;&nbsp;le choc des photos&nbsp;&raquo; comme un pro&nbsp;!","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.3-wpcom","tags":"Noir, Sombre, Orange, Deux colonnes, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Microformats, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, art, artwork, blog, clean, colorful, curved, geometric, journal, textured, vibrant","parent":false,"active":false,"trendingRank":209,"popularityRank":72,"launchDate":"2011-09-21","demoUrl":"https:\/\/paramentdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fparament&amp;_wpnonce=806e52b654","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fparament","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/responsive","name":"Sensible","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/responsive\/screenshot.png?w=434"],"description":"Un th\u00e8me rempli de fonctionnalit\u00e9s avec de nombreuses dispositions de page, des zones de widgets, de menus personnalis\u00e9s, fil d&rsquo;Ariane de navigation, un mod\u00e8le de page d&rsquo;accueil, des ic\u00f4nes de r\u00e9seaux sociaux et des CSS souples.","author":"CyberChimps","authorAndUri":"<a href=\"http:\/\/cyberchimps.com\/\">CyberChimps<\/a>","version":"1.0.2-wpcom","tags":"blog, business, Blanc, Gris, Clair, clean, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Options du th\u00e8me, Mod\u00e8le pleine largeur, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":210,"popularityRank":120,"launchDate":"2013-02-28","demoUrl":"https:\/\/responsivedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fresponsive&amp;_wpnonce=c6841e7141","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fresponsive","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/fanwood-light","name":"Fanwood Light","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/fanwood-light\/screenshot.png?w=434"],"description":"a bold blogging theme. Features a responsive design layout. Design by DevPress.com.","author":"DevPress","authorAndUri":"<a href=\"http:\/\/devpress.com\/\">DevPress<\/a>","version":"1.0.2-wpcom","tags":"Jaune, Noir, Colonne lat\u00e9rale droite, blog, bright, clean, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, design, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, D\u00e9filement Infini, journal, Photoblogging, Format d&rsquo;article, Mise en page adaptable, Article mis en avant, Deux colonnes","parent":false,"active":false,"trendingRank":211,"popularityRank":222,"launchDate":"2013-04-25","demoUrl":"https:\/\/fanwoodlightdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ffanwood-light&amp;_wpnonce=d59e42fc93","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ffanwood-light","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/studio","name":"Studio","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/studio\/screenshot.png?w=434"],"description":"Studio est un th\u00e8me minimaliste de style book, bas\u00e9 sur une grille, con\u00e7u pour les photographes et les galeristes. Il est simple, soign\u00e9 et tr\u00e8s souple, et associe esth\u00e9tisme d\u00e9licat et organisation parfaite.","author":"Pixel Union","authorAndUri":"<a href=\"http:\/\/www.pixelunion.net\/\">Pixel Union<\/a>","version":"2.2.0","tags":"Noir, Clair, Sombre, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, craft, design, fashion, journal, magazine, Photoblogging, photography, portfolio, clean, contemporary, Sombre, elegant, Clair, minimal, modern, professional, simple, sophisticated, urban","parent":false,"active":false,"trendingRank":212,"popularityRank":182,"launchDate":"2014-01-28","demoUrl":"https:\/\/studiodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fstudio&amp;_wpnonce=ca86a69874","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fstudio","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/studio&#038;ref=themesphp&#038;_wpnonce=ca86a69874"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/mixfolio","name":"Mixfolio","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/mixfolio\/screenshot.png?w=434"],"description":"A responsive, post format-packed, photographer-loving portfolio theme. Use it for your portfolio and make your friends jealous.","author":"Graph Paper Press","authorAndUri":"<a href=\"http:\/\/graphpaperpress.com\">Graph Paper Press<\/a>","version":"1.1.2-wpcom","tags":"Noir, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Photoblogging, photography, portfolio, clean, minimal, simple","parent":false,"active":false,"trendingRank":213,"popularityRank":163,"launchDate":"2012-06-21","demoUrl":"https:\/\/mixfoliodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmixfolio&amp;_wpnonce=b8261b9c81","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmixfolio","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/connect","name":"Se connecter","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/connect\/screenshot.png?w=434"],"description":"Your online business card. Connect is designed and developed for sharing a professional profile.","author":"Organic Themes","authorAndUri":"<a href=\"http:\/\/www.organicthemes.com\">Organic Themes<\/a>","version":"1.0","tags":"art, artwork, blog, business, design, Photoblogging, photography, portfolio, clean, contemporary, elegant, Clair, lifestream, minimal, modern, professional, simple, Bleu, Orange, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, responsive-width, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Curseur d'article, Article mis en avant, Format d&rsquo;article, Images \u00e0 la Une, site-logo, \u00c9diteur de style, threaded-comments","parent":false,"active":false,"trendingRank":214,"popularityRank":186,"launchDate":"2014-08-13","demoUrl":"https:\/\/connectdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fconnect&amp;_wpnonce=37a7ff5126","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fconnect","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/connect&#038;ref=themesphp&#038;_wpnonce=37a7ff5126"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/yoko","name":"Yoko","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/yoko\/screenshot.png?w=434"],"description":"Yoko est un th&egrave;me moderne en trois colonnes de style r&eacute;actif, ce qui le rend particuli&egrave;rement adapt&eacute; aux mobiles, tablettes et autres smartphones, gr&acirc;ce &agrave; une mise en page intuitive qui adapte le nombre de colonnes dispens&eacute;es lat&eacute;ralement (une ou deux) &agrave; la largeur de chaque &eacute;cran. Profitez de toute la panoplie des formats d&rsquo;articles (galerie, image, vid&eacute;o, apart&eacute;, lien ou citation) pour gagner en souplesse, et personnalisez l&rsquo;apparence avec vos propres images d&rsquo;en-t&ecirc;te et d&rsquo;arri&egrave;re-plan, et des liens de couleur ad&eacute;quate.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/wordpress-themes\/\">Elmastudio<\/a>","version":"1.0.9-wpcom","tags":"blog, bright, business, clean, contemporary, elegant, Gris, modern, simple, Clair, Blanc, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":215,"popularityRank":74,"launchDate":"2012-06-21","demoUrl":"https:\/\/yokodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fyoko&amp;_wpnonce=86a13934e7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fyoko","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/skeptical","name":"Skeptical","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/skeptical\/screenshot.png?w=434"],"description":"Un th&egrave;me offrant un en-t&ecirc;te et un fond personnalisables, cinq zones widget dont une zone lat&eacute;rale et quatre en pied de page. Le pied de page affiche &eacute;galement un maximum de trois articles en vedette (sticky). Skeptical offre un choix de quatre jeux de couleurs et prend en charge les formats d&rsquo;articles suivants: apart&eacute;, galerie, image, citation, lien, chat, audio, et vid&eacute;o.","author":"WooThemes","authorAndUri":"<a href=\"http:\/\/www.woothemes.com\">WooThemes<\/a>","version":"1.0.4-wpcom","tags":"school, education, Bleu, Marron, Gris, Vert, Rouge, Clair, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, announcement, blog, design, news, professional, travel, tumblelog, video, clean, colorful, contemporary, Clair, modern, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":216,"popularityRank":39,"launchDate":"2011-08-23","demoUrl":"https:\/\/skepticaldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fskeptical&amp;_wpnonce=5b87af0200","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fskeptical","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/moka","name":"Moka","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/moka\/screenshot.png?w=434"],"description":"Moka est un th\u00e8me minimaliste et adaptable pour les blogs, les magazines et les activit\u00e9s cr\u00e9atives. Son graphisme est attractif et moderne, et il est assorti de nombreuses fonctions de th\u00e8mes individuels simples \u00e0 utiliser, comme un mod\u00e8le de premi\u00e8re page personnalisable, un mod\u00e8le de pr\u00e9sentation et de citations et une option d\u2019encadr\u00e9 fixe.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/en\/\">Elmastudio<\/a>","version":"1.0.5-wpcom","tags":"Blanc, Clair, Mise en page fluide, Mise en page adaptable, Une colonne, Trois colonnes, Quatre colonnes, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Options du th\u00e8me, Format d&rsquo;article, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, art, artwork, design, fashion, food, journal, magazine, Photoblogging, photography, clean, elegant, minimal, modern, contemporary, Noir, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Colonne lat\u00e9rale gauche, Curseur d'article, Support des langues RTL, Deux colonnes","parent":false,"active":false,"trendingRank":217,"popularityRank":27,"launchDate":"2014-01-23","demoUrl":"https:\/\/mokademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmoka&amp;_wpnonce=199912bb92","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmoka","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/moka&#038;ref=themesphp&#038;_wpnonce=199912bb92"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>18","purchased":false}},{"id":"pub\/stay","name":"Stay","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/stay\/screenshot.png?w=434"],"description":"Designed with hotels, inns, and bed &amp; breakfasts in mind, Stay is the perfect theme for property owners. Take advantage of its Room and Testimonial post types, home page template, large imagery, and minimal layout to show off to potential guests.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.5-wpcom","tags":"business, hotel, real-estate, travel, clean, Clair, minimal, professional, Gris, Blanc, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":218,"popularityRank":176,"launchDate":"2013-04-22","demoUrl":"https:\/\/staydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fstay&amp;_wpnonce=8737beabcd","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fstay","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/suburbia","name":"Suburbia","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/suburbia\/screenshot.png?w=434"],"description":"Suburbia is a unique magazine theme in a minimalistic style. Designed by WPShower. It features five widget areas, custom header, and custom background.","author":"WPShower","authorAndUri":"<a href=\"http:\/\/www.wpshower.com\">WPShower<\/a>","version":"1.1.2-wpcom","tags":"Gris, Blanc, Clair, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, design, fashion, magazine, news, portfolio, artistic, bright, clean, contemporary, geometric, minimal, modern","parent":false,"active":false,"trendingRank":219,"popularityRank":63,"launchDate":"2012-02-07","demoUrl":"https:\/\/suburbiademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsuburbia&amp;_wpnonce=61a0717f7e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsuburbia","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/hustle-express","name":"Hustle Express","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/hustle-express\/screenshot.png?w=434"],"description":"A freshly designed, open and responsive blogging theme designed by <a href=\"http:\/\/www.woothemes.com\">WooThemes<\/a>.","author":"WooThemes","authorAndUri":"<a href=\"http:\/\/woothemes.com\">WooThemes<\/a>","version":"1.0","tags":"blog, clean, minimal, Noir, Bleu, Rouge, Deux colonnes, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":220,"popularityRank":337,"launchDate":"2013-02-21","demoUrl":"https:\/\/hustleexpressdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fhustle-express&amp;_wpnonce=ee529a6ae3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fhustle-express","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/hustle-express&#038;ref=themesphp&#038;_wpnonce=ee529a6ae3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>68","purchased":false}},{"id":"pub\/typo","name":"Typo","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/typo\/screenshot.png?w=434"],"description":"A typography-centered, responsive theme for photos, articles, quotes, videos, and more. Its sleek one-column design makes it perfect for a personal blog, and support for multiple post formats allows you to tumblelog your finds with style.","author":"Okay Themes","authorAndUri":"<a href=\"http:\/\/okaythemes.com\">Okay Themes<\/a>","version":"1.1-wpcom","tags":"Noir, Gris, Blanc, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, journal, lifestream, tumblelog, clean, conservative, Sombre, elegant, modern, paper-made, professional, textured, minimal","parent":false,"active":false,"trendingRank":221,"popularityRank":235,"launchDate":"2013-11-14","demoUrl":"https:\/\/typodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftypo&amp;_wpnonce=6f1333ece2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftypo","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/runo-lite","name":"Runo Lite","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/runo-lite\/screenshot.png?w=434"],"description":"Runo Lite was made especially for poets and writers. It is lightweight, clean, simple, spacious, and feels like your favorite notebook, and the responsive, minimal layout looks good in every device.","author":"La&amp;La","authorAndUri":"<a href=\"http:\/\/runo.lala.fi\">La&amp;La<\/a>","version":"1.3.1-wpcom","tags":"blog, education, journal, news, school, clean, contemporary, elegant, formal, Clair, minimal, simple, traditional, Blanc, Noir, Rouge, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":222,"popularityRank":272,"launchDate":"2012-10-18","demoUrl":"https:\/\/runolitedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fruno-lite&amp;_wpnonce=4afa8a86fd","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fruno-lite","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/selecta","name":"Selecta","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/selecta\/screenshot.png?w=434"],"description":"With a featured posts slider on the front page, a wide, one-column template on image and video posts, and archives displayed in gallery format, Selecta is well-suited for blogs which focus primarily on showcasing videos or images. It comes with six color schemes, support for video, image, aside, gallery, quote, chat, and audio post formats, custom header, custom background, and four widget areas &#8212; one in the left sidebar and three in the footer.","author":"Obox Design","authorAndUri":"<a href=\"http:\/\/obox-design.com\/\">Obox Design<\/a>","version":"1.1.1-wpcom","tags":"Noir, Bleu, Vert, Rouge, Blanc, Sombre, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, portfolio, tumblelog, video, bright, clean, colorful, curved, Sombre, geometric, playful, retro, simple, vibrant","parent":false,"active":false,"trendingRank":223,"popularityRank":96,"launchDate":"2011-09-01","demoUrl":"https:\/\/selectademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fselecta&amp;_wpnonce=156ecf340b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fselecta","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/elemin","name":"Elemin","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/elemin\/screenshot.png?w=434"],"description":"Elemin est un th\u00e8me fin et minimaliste o\u00f9 les espaces vides sont pr\u00e9sents, accompagn\u00e9s d&rsquo;une \u00e9l\u00e9gante typographie. Il propose neuf jeux de couleurs, trois mises en page du site en option, deux mises en pages possibles pour les articles, deux zones de menu personnalis\u00e9es, la couleur des liens de votre choix. La prise en charge des formats de publication, une zone widget de pied de page, un en-t\u00eate et l&rsquo;arri\u00e8re plan personnalisables, et tout ceci avec une disposition r\u00e9active qui s&rsquo;adapte \u00e0 diverses tailles d&rsquo;\u00e9crans.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Noir, Bleu, Gris, Vert, Rose, Orange, Blanc, Jaune, Sombre, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, fashion, journal, lifestream, portfolio, professional, tumblelog, bright, clean, elegant, minimal, simple, sophisticated, video","parent":false,"active":false,"trendingRank":224,"popularityRank":40,"launchDate":"2011-09-29","demoUrl":"https:\/\/elemindemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Felemin&amp;_wpnonce=061c905540","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Felemin","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/elemin&#038;ref=themesphp&#038;_wpnonce=061c905540"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"pub\/beach","name":"Beach","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/beach\/screenshot.png?w=434"],"description":"Beach brings the warm feel of Thailand&rsquo;s shores to your blog year round. Originally designed for Drupal Thailand by Gibbo, Beach features special post formatting for Aside, Gallery, Quote, and Status posts, along with a beautiful secondary menu area in the header.","author":"Gibbo and Automattic","authorAndUri":"<a href=\"http:\/\/webzer.net\/\">Gibbo and Automattic<\/a>","version":"1.3-wpcom","tags":"Bleu, Vert, Deux colonnes, Mise en page fixe, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, nature, outdoors, Saisonnier, travel, clean, colorful, hand-drawn, vibrant, whimsical, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":225,"popularityRank":108,"launchDate":"2011-01-18","demoUrl":"https:\/\/beachdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbeach&amp;_wpnonce=523aba6d87","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbeach","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/ever-after","name":"Ever After","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/ever-after\/screenshot.png?w=434"],"description":"A wedding blog-centric theme decorated with subtle but gorgeous textures and ornaments. The wide one-column layout is great for photos and videos of your wedding or your wedding plan that you want to share with family, friends, or the world.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2-wpcom","tags":"Bleu, Rose, Blanc, Clair, Une colonne, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, announcement, blog, journal, news, Photoblogging, scrapbooking, wedding, bright, clean, flowery, formal, Clair, minimal, modern, paper-made, simple, sophisticated, textured, traditional, Mise en page adaptable, D\u00e9filement Infini, Curseur d'article","parent":"Forever","active":false,"trendingRank":226,"popularityRank":58,"launchDate":"2012-08-13","demoUrl":"https:\/\/everafterdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fever-after&amp;_wpnonce=d336001438","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fever-after","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/sight","name":"Sight","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sight\/screenshot.png?w=434"],"description":"Sight blends simplicity with sophistication to bring refined beauty to your blog. It features a right sidebar for widgets, two custom menu locations, a slider for sticky posts, and a responsive layout that adapts to smaller screen sizes.","author":"WPShower","authorAndUri":"<a href=\"http:\/\/wpshower.com\/\">WPShower<\/a>","version":"1.0.1-wpcom","tags":"blog, journal, magazine, clean, conservative, elegant, formal, simple, sophisticated, Noir, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":227,"popularityRank":131,"launchDate":"2012-08-30","demoUrl":"https:\/\/sightdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsight&amp;_wpnonce=648d05f618","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsight","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/modern-news","name":"Modern News","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/modern-news\/screenshot.png?w=434"],"description":"Modern News est un th\u00e8me minimaliste pour mettre en valeur votre contenu d&rsquo;une mani\u00e8re moderne et agr\u00e9able \u00e0 lire.","author":"StudioPress","authorAndUri":"<a href=\"http:\/\/www.studiopress.com\/\">StudioPress<\/a>","version":"2.0","tags":"Noir, Bleu, Gris, Vert, Orange, Rose, Violet, Rouge, Blanc, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mise en page fixe, Mod\u00e8le pleine largeur, Colonne lat\u00e9rale gauche, Une colonne, Colonne lat\u00e9rale droite, Article mis en avant, Options du th\u00e8me, Trois colonnes, Pr\u00eat \u00e0 \u00eatre traduit, Deux colonnes, D\u00e9filement Infini, blog, magazine, news, clean, contemporary, fashion, futuristic, Clair, minimal, modern, tech, vibrant","parent":"Genesis","active":false,"trendingRank":228,"popularityRank":38,"launchDate":"2011-10-12","demoUrl":"https:\/\/modernnewsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmodern-news&amp;_wpnonce=c6e3a680da","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmodern-news","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/modern-news&#038;ref=themesphp&#038;_wpnonce=c6e3a680da"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/blissful-blog","name":"Blissful Blog","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/blissful-blog\/screenshot.png?w=434"],"description":"The Blissful Blog is a beautifully designed wedding photography blog for couples, photographers and industry professionals.","author":"Organic Themes","authorAndUri":"<a href=\"http:\/\/www.organicthemes.com\/\">Organic Themes<\/a>","version":"1.0.2-wpcom","tags":"blog, photography, wedding, bright, Bleu, Blanc, Clair, Une colonne, Deux colonnes, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Curseur d'article, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Support des langues RTL","parent":false,"active":false,"trendingRank":229,"popularityRank":145,"launchDate":"2012-10-25","demoUrl":"https:\/\/blissfulblogdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fblissful-blog&amp;_wpnonce=a565fd6c13","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fblissful-blog","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/tuned-balloon","name":"Tuned Balloon","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/tuned-balloon\/screenshot.png?w=434"],"description":"Tuned Balloon est un th\u00e8me simple \u00e0 utiliser, avec une mise en page adaptable \u00e0 l\u2019excellent rendu sur tous les p\u00e9riph\u00e9riques, grands ou petits. Tuned Balloon propose diff\u00e9rents formats de publication, qui s\u2019affichent tous de fa\u00e7on unique. Si vous voulez faire varier vos billets, vous pouvez utiliser diff\u00e9rents formats de publication \u2013 image, galerie, vid\u00e9o, apart\u00e9, lien ou citations.","author":"Anariel Design","authorAndUri":"<a href=\"http:\/\/www.anarieldesign.com\/\">Anariel Design<\/a>","version":"1.0","tags":"Colonne lat\u00e9rale droite, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Mise en page adaptable, Article mis en avant, art, blog, Sombre, design, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, music, news, Orange, portfolio, Format d&rsquo;article","parent":false,"active":false,"trendingRank":230,"popularityRank":334,"launchDate":"2014-02-17","demoUrl":"https:\/\/tunedballoondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Ftuned-balloon&amp;_wpnonce=b3c2e72829","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Ftuned-balloon","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/tuned-balloon&#038;ref=themesphp&#038;_wpnonce=b3c2e72829"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/sidekick","name":"Sidekick","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sidekick\/screenshot.png?w=434"],"description":"The single-column, widget-free child theme of Superhero.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.4-wpcom","tags":"blog, Photoblogging, photography, tumblelog, clean, minimal, simple, D\u00e9filement Infini, Gris, Clair, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant","parent":"Superhero","active":false,"trendingRank":231,"popularityRank":247,"launchDate":"2013-03-07","demoUrl":"https:\/\/sidekickdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsidekick&amp;_wpnonce=613b195a05","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsidekick","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/esquire","name":"Esquire","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/esquire\/screenshot.png?w=434"],"description":"An elegant and bold theme featuring multiple, visually distinct, Post Formats. Designed by Matthew Buchanan and inspired by the art direction of Esquire magazine.","author":"Matthew Buchanan","authorAndUri":"<a href=\"http:\/\/matthewbuchanan.name\/\">Matthew Buchanan<\/a>","version":"1.4-wpcom","tags":"Clair, Rouge, Blanc, Jaune, Deux colonnes, Mise en page fixe, Menu personnalis\u00e9, Images \u00e0 la Une, Format d&rsquo;article, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, fashion, tumblelog, artistic, bright, clean, contemporary, elegant, formal, minimal, modern, playful, sophisticated, whimsical, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":232,"popularityRank":191,"launchDate":"2011-08-03","demoUrl":"https:\/\/esquiredemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fesquire&amp;_wpnonce=66aad1f2b2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fesquire","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/singl","name":"Singl","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/singl\/screenshot.png?w=434"],"description":"Singl est un th\u00e8me minimaliste qui vous aide \u00e0 cr\u00e9er une pr\u00e9sence en ligne forte et belle. Con\u00e7u \u00e0 l\u2019origine pour les artistes musiciens, Singl est un th\u00e8me puissant et souple.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.3-wpcom","tags":"Noir, Vert, Blanc, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, music, clean, Sombre, minimal","parent":false,"active":false,"trendingRank":233,"popularityRank":154,"launchDate":"2014-02-19","demoUrl":"https:\/\/singldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsingl&amp;_wpnonce=cde9fcec8d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsingl","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/blaskan","name":"Blaskan","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/blaskan\/screenshot.png?w=434"],"description":"Blaskan is a high quality, minimal theme focused on what WordPress does best, blogging. It sports a fully responsive layout that works well on all devices. Supports custom background, custom header, and featured image thumbnails in posts.","author":"Per Sandstrom","authorAndUri":"<a href=\"http:\/\/www.helloper.com\">Per Sandstrom<\/a>","version":"2.5.1-wpcom","tags":"Noir, Clair, Blanc, Une colonne, Trois colonnes, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, clean, contemporary, minimal, simple","parent":false,"active":false,"trendingRank":234,"popularityRank":207,"launchDate":"2012-04-05","demoUrl":"https:\/\/blaskandemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fblaskan&amp;_wpnonce=d386192bad","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fblaskan","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/publish","name":"Publier","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/publish\/screenshot.png?w=434"],"description":"Publish is a clean minimal theme which puts you and your content on stage. Ideal for single-author blogs.","author":"Konstantin Kovshenin","authorAndUri":"<a href=\"http:\/\/kovshenin.com\">Konstantin Kovshenin<\/a>","version":"1.2.4-wpcom","tags":"blog, journal, clean, formal, Clair, minimal, modern, simple, Blanc, Bleu, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Personnalisation de l&rsquo;en-t\u00eate, education, lifestream","parent":false,"active":false,"trendingRank":235,"popularityRank":203,"launchDate":"2012-11-29","demoUrl":"https:\/\/publishdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fpublish&amp;_wpnonce=689373c212","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fpublish","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/liquorice","name":"Liquorice","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/liquorice\/screenshot.png?w=434"],"description":"Make your blog a little sweeter with Liquorice, a simple, clean vintage-style WordPress theme. Originally designed by NudgeDesign.ca, Liquorice features a right sidebar, custom background and header support, configurable RSS, Facebook and Twitter icons in the top left corner of the page, and special formatting for Aside, Gallery, Image and Quote posts.","author":"Nudge Design","authorAndUri":"<a href=\"http:\/\/www.nudgedesign.ca\">Nudge Design<\/a>","version":"2.1-wpcom","tags":"D\u00e9filement Infini, Marron, Ocre, Bleu, Rouge, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Format d&rsquo;article, Options du th\u00e8me, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Images \u00e0 la Une, artwork, blog, craft, design, fashion, scrapbooking, clean, minimal, retro, simple, sophisticated, whimsical","parent":false,"active":false,"trendingRank":240,"popularityRank":75,"launchDate":"2011-03-17","demoUrl":"https:\/\/liquoricedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fliquorice&amp;_wpnonce=1ca80250ed","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fliquorice","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/lifestyle","name":"Lifestyle","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/lifestyle\/screenshot.png?w=434"],"description":"Lifestyle is a colorful theme with a stylish frame for your all of your magazine or news related content.","author":"StudioPress","authorAndUri":"<a href=\"http:\/\/www.studiopress.com\/\">StudioPress<\/a>","version":"2.0.1","tags":"blog, bright, colorful, wedding, Bleu, Vert, Orange, Rose, Violet, Jaune, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, clean, contemporary, fashion, Image d&rsquo;en-t\u00eate \u00e0 la Une, lifestream, magazine, modern, news, professional","parent":"Genesis","active":false,"trendingRank":237,"popularityRank":99,"launchDate":"2011-07-13","demoUrl":"https:\/\/lifestyledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Flifestyle&amp;_wpnonce=0ca9b97433","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Flifestyle","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/lifestyle&#038;ref=themesphp&#038;_wpnonce=0ca9b97433"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/widely","name":"Widely","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/widely\/screenshot.png?w=434"],"description":"Widely est un th&egrave;me minimaliste qui convient &agrave; la fois aux blogueurs ordinaires, aux entreprises, et aux artistes d&eacute;sireux d&rsquo;exposer leurs cr&eacute;ations ou tout autre contenu dans un portfolio simple au design parfaitement structur&eacute;.","author":"Themes Kingdom","authorAndUri":"<a href=\"http:\/\/www.themeskingdom.com\/\">Themes Kingdom<\/a>","version":"2.0.3-wpcom","tags":"education, school, blog, journal, lifestream, photography, clean, elegant, Clair, modern, professional, Gris, Blanc, Une colonne, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Microformats, Support des langues RTL","parent":false,"active":false,"trendingRank":238,"popularityRank":232,"launchDate":"2012-12-13","demoUrl":"https:\/\/widelydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fwidely&amp;_wpnonce=94ec6d4a7e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fwidely","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/quintus","name":"Quintus","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/quintus\/screenshot.png?w=434"],"description":"A theme that has an old-style appeal with semi-academic graciousness and elegant typography. Fitting for displaying either text or images, Quintus offers a fresh look with room for customization, including custom backgrounds, menus, header images, and the option to publish short aside posts.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.5-wpcom","tags":"Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Article mis en avant, Microformats, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Mod\u00e8le pleine largeur, Format d&rsquo;article, Marron, Blanc, Clair, Ocre, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, art, artwork, blog, craft, education, journal, lifestream, professional, travel, elegant, formal, retro, textured, traditional, D\u00e9filement Infini, Mise en page adaptable","parent":false,"active":false,"trendingRank":239,"popularityRank":69,"launchDate":"2011-08-10","demoUrl":"https:\/\/quintusdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fquintus&amp;_wpnonce=f4d00bbb78","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fquintus","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/portfolio","name":"Portfolio","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/portfolio\/screenshot.png?w=434"],"description":"Un th&egrave;me portfolio &eacute;pur&eacute; et l&eacute;ger, complet avec un slider d&rsquo;en t&ecirc;te et des pages de portfolio faciles &agrave; configurer. Con&ccedil;u pour s&rsquo;adapter joliment aux larges formats d&rsquo;affichage, tablettes et smartphones.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"1.3.20-wpcom","tags":"business, portfolio, professional, photography, clean, elegant, formal, handcrafted, Clair, minimal, sophisticated, Gris, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Curseur d'article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":240,"popularityRank":43,"launchDate":"2012-06-07","demoUrl":"https:\/\/portfoliothemedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fportfolio&amp;_wpnonce=06b8da25a7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fportfolio","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/portfolio&#038;ref=themesphp&#038;_wpnonce=06b8da25a7"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/the-columnist","name":"The Columnist","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/the-columnist\/screenshot.png?w=434"],"description":"Columnist allie une typographie large audacieuse au principe minimaliste pour offrir un design vraiment particulier.","author":"Ben Martineau","authorAndUri":"<a href=\"http:\/\/thecolumnist.info\/\">Ben Martineau<\/a>","version":"1.0.1-wpcom","tags":"Gris, Deux colonnes, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Couleurs personnalis\u00e9es, design, magazine, news, professional, clean, contemporary, Clair, minimal, Blanc, Colonne lat\u00e9rale gauche","parent":false,"active":false,"trendingRank":241,"popularityRank":172,"launchDate":"2012-07-19","demoUrl":"https:\/\/thecolumnistdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fthe-columnist&amp;_wpnonce=a59d668a1d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fthe-columnist","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/arcade","name":"Arcade","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/arcade\/screenshot.png?w=434"],"description":"Arcade is a beautifully designed responsive theme which features a large header image on the home page. Stunning typography and multiple layout options make it easy to create a unique site that suits your every need.","author":"c.bavota","authorAndUri":"<a href=\"http:\/\/bavotasan.com\/\">c.bavota<\/a>","version":"1.0.3","tags":"business, design, magazine, news, personal, photography, portfolio, clean, elegant, modern, professional, Noir, Bleu, Gris, Argent, Blanc, Colonne lat\u00e9rale gauche, Une colonne, Colonne lat\u00e9rale droite, Trois colonnes, Deux colonnes, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, featured-image, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":242,"popularityRank":122,"launchDate":"2014-05-29","demoUrl":"https:\/\/arcadedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Farcade&amp;_wpnonce=8ef6f1a05c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Farcade","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/arcade&#038;ref=themesphp&#038;_wpnonce=8ef6f1a05c"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"pub\/eventbrite-event","name":"Eventbrite Single Event","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/eventbrite-event\/screenshot.png?w=434"],"description":"Utilisez ce th&egrave;me pour exposer vos activit&eacute;s, ou projets,Eventbrite et rester en contact avec votre audience avant et apr&egrave;s les &eacute;v&egrave;nements, nouveaut&eacute;s, mises &agrave; jour, commentaires et partages sociaux.","author":"Voce Platforms","authorAndUri":"<a href=\"http:\/\/voceplatforms.com\">Voce Platforms<\/a>","version":"1.2.2","tags":"Mise en page adaptable, Deux colonnes, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Support des langues RTL, Menu personnalis\u00e9","parent":false,"active":false,"trendingRank":243,"popularityRank":258,"launchDate":"2013-09-16","demoUrl":"https:\/\/eventbriteeventdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Feventbrite-event&amp;_wpnonce=26aa8eadce","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Feventbrite-event","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/imbalance2","name":"Imbalance 2","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/imbalance2\/screenshot.png?w=434"],"description":"A theme designed in strict modern style with a minimalistic touch. Imbalance 2 can easily turns your blog to an attractive blog, a portfolio or even an online magazine. It supports both fixed and fluid layouts. Also it allows you to choose a theme color.","author":"WPShower","authorAndUri":"<a href=\"http:\/\/www.wpshower.com\/\">WPShower<\/a>","version":"1.0.4-wpcom","tags":"Blanc, Clair, Une colonne, Quatre colonnes, Mise en page fixe, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, craft, design, fashion, journal, magazine, news, portfolio, professional, artistic, bright, clean, contemporary, elegant, geometric, Clair, minimal, modern, simple, sophisticated","parent":false,"active":false,"trendingRank":239,"popularityRank":127,"launchDate":"2011-12-06","demoUrl":"https:\/\/imbalance2demo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fimbalance2&amp;_wpnonce=c4ca0c23d6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fimbalance2","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/writr","name":"Writr","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/writr\/screenshot.png?w=434"],"description":"Writr est un th&egrave;me minimaliste de style tumblelog, simple d&#8217;emploi, d&eacute;clin&eacute; en six couleurs: Turquoise (par d&eacute;faut), bleu, vert, gris, pourpre et rouge. Par son look moderne et sa typo craquante, Writr exalte votre contenu.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.5-wpcom","tags":"Noir, Bleu, Gris, Vert, Violet, Rouge, Blanc, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, lifestream, tumblelog, clean, geometric, minimal, modern, simple","parent":false,"active":false,"trendingRank":247,"popularityRank":64,"launchDate":"2013-10-31","demoUrl":"https:\/\/writrdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fwritr&amp;_wpnonce=b69fd46dfb","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fwritr","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/sorbet","name":"Sorbet","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sorbet\/screenshot.png?w=434"],"description":"Sorbet is a delicious treat for your blog or website. Colorful post formats help your content pop, while secondary information (navigation, search, social links, and widgets) is tucked neatly away in the header for easy access that doesn&rsquo;t crowd your content.","author":"WordPress.com","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">WordPress.com<\/a>","version":"1.2.1-wpcom","tags":"clean, design, Bleu, Gris, Vert, Orange, Rose, Rouge, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, gaming, journal, lifestream, Photoblogging, school, tumblelog, artistic, bright, colorful, modern, playful, vibrant","parent":false,"active":false,"trendingRank":246,"popularityRank":73,"launchDate":"2014-01-29","demoUrl":"https:\/\/sorbetdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsorbet&amp;_wpnonce=0c726d7610","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsorbet","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/newsworthy","name":"Newsworthy","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/newsworthy\/screenshot.png?w=434"],"description":"Le th\u00e8me Newsworthy est un th\u00e8me simple avec un design cool et de beaux accents de couleur. C&rsquo;est un th\u00e8me parfait pour le blogueur personnel.","author":"WPThemes NZ","authorAndUri":"<a href=\"http:\/\/wpthemes.co.nz\/\">WPThemes NZ<\/a>","version":"1.4.4-wpcom","tags":"Bleu, Orange, Blanc, bright, Deux colonnes, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, D\u00e9filement Infini, Article mis en avant, Support des langues RTL, Mise en page fluide, Format d&rsquo;article, colorful, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Mise en page adaptable","parent":false,"active":false,"trendingRank":247,"popularityRank":174,"launchDate":"2013-05-02","demoUrl":"https:\/\/newsworthydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fnewsworthy&amp;_wpnonce=a4b3c75203","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fnewsworthy","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/skylark","name":"Skylark","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/skylark\/screenshot.png?w=434"],"description":"Skylark is a bright, clean, and responsive theme that&rsquo;s a great starting point for individuals and businesses who want to establish a professional online presence. Not only is the theme well-suited for general blogging, but its showcase and portfolio page templates make it easy to highlight latest news and projects in style.","author":"Blank Themes","authorAndUri":"<a href=\"http:\/\/blankthemes.com\/\">Blank Themes<\/a>","version":"1.0.6-wpcom","tags":"blog, business, portfolio, professional, conservative, simple, Bleu, Orange, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":256,"popularityRank":195,"launchDate":"2012-06-14","demoUrl":"https:\/\/skylarkdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fskylark&amp;_wpnonce=7dca7fc489","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fskylark","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/bonpress","name":"BonPress","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/bonpress\/screenshot.png?w=434"],"description":"BonPress is the perfect personal blog theme. Packed with Post Formats and subtle details, it offers a unique blogging experience.","author":"WPZOOM","authorAndUri":"<a href=\"http:\/\/www.wpzoom.com\/\">WPZOOM<\/a>","version":"1.0.2-wpcom","tags":"blog, tumblelog, clean, conservative, formal, industrial, professional, simple, traditional, Mise en page adaptable, Couleurs personnalis\u00e9es, D\u00e9filement Infini, Orange, Ocre, Gris, Deux colonnes, Colonne lat\u00e9rale gauche, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":249,"popularityRank":299,"launchDate":"2013-04-18","demoUrl":"https:\/\/bonpressdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbonpress&amp;_wpnonce=844e376e12","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbonpress","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/ideation-and-intent","name":"Ideation and Intent","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/ideation-and-intent\/screenshot.png?w=434"],"description":"They say a picture is worth a thousand words and this theme was built for photoblogging! Showcase your images in style with front-page featured images and an automatically generated photo sidebar.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.2-wpcom","tags":"education, school, Photoblogging, Orange, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Menu personnalis\u00e9, Images \u00e0 la Une, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, bright, En-t\u00eate flexible, Gris, D\u00e9filement Infini, photography, portfolio, textured","parent":false,"active":false,"trendingRank":257,"popularityRank":164,"launchDate":"2012-05-31","demoUrl":"https:\/\/ideationandintentdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fideation-and-intent&amp;_wpnonce=c19c1af094","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fideation-and-intent","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/nishita","name":"Nishita","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/nishita\/screenshot.png?w=434"],"description":"A simple, elegantly styled photoblog theme. Includes dark or light color schemes, wide or narrow layout choice, three footer widgets areas, and an optional sidebar.","author":"Brajeshwar","authorAndUri":"<a href=\"http:\/\/brajeshwar.com\/\">Brajeshwar<\/a>","version":"1.2.2-wpcom","tags":"D\u00e9filement Infini, Noir, Bleu, Sombre, Gris, Clair, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Support des langues RTL, Article mis en avant, Options du th\u00e8me, blog, Photoblogging, photography, portfolio, video, clean, minimal, simple","parent":false,"active":false,"trendingRank":251,"popularityRank":100,"launchDate":"2011-09-14","demoUrl":"https:\/\/nishitademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fnishita&amp;_wpnonce=9fcfc02df9","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fnishita","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/minimalizine","name":"Minimalizine","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/minimalizine\/screenshot.png?w=434"],"description":"A simple and clean theme, perfect for focusing on your content. It supports 3 widget areas above the footer.","author":"Rizqy Hidayat","authorAndUri":"<a href=\"http:\/\/hirizh.name\/\">Rizqy Hidayat<\/a>","version":"0.3-wpcom","tags":"En-t\u00eate flexible, blog, design, journal, clean, conservative, contemporary, elegant, formal, minimal, modern, professional, simple, Bleu, Gris, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":252,"popularityRank":256,"launchDate":"2013-01-11","demoUrl":"https:\/\/minimalizinedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fminimalizine&amp;_wpnonce=983f0b51cb","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fminimalizine","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/grisaille","name":"Grisaille","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/grisaille\/screenshot.png?w=434"],"description":"A classic two-column design adjusted for mobile browsing. Both featured images and Sticky posts are supported. Twitter, Facebook, and Google Plus Theme Options available, as well as custom menus, header image, and background. It&rsquo;s pronounced &laquo;&nbsp;griz-eye&nbsp;&raquo;.","author":"Nudge design","authorAndUri":"<a href=\"http:\/\/www.nudgedesign.ca\">Nudge design<\/a>","version":"1.3.1-wpcom","tags":"education, school, Images \u00e0 la Une, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Deux colonnes, Mise en page fixe, Colonne lat\u00e9rale droite, Gris, Bleu, Orange, Clair, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, \u00c9diteur de style, Support des langues RTL, grungy, D\u00e9filement Infini, art, artwork, En-t\u00eate flexible, Mise en page adaptable, modern, blog","parent":false,"active":false,"trendingRank":253,"popularityRank":209,"launchDate":"2012-06-07","demoUrl":"https:\/\/grisailledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fgrisaille&amp;_wpnonce=c888f511a8","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fgrisaille","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/balloons","name":"Balloons","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/balloons\/screenshot.png?w=434"],"description":"Balloons est un th\u00e8me adaptable, simple et original, avec un d\u00e9filement parallaxe et trois espaces widgets en pied de page.","author":"Moargh.de","authorAndUri":"<a href=\"http:\/\/www.moargh.de\">Moargh.de<\/a>","version":"1.0.1-wpcom","tags":"Une colonne, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Support des langues RTL, Arri\u00e8re-plan personnalis\u00e9, D\u00e9filement Infini, Mise en page adaptable, Gris, Bleu, Blanc, Clair, tumblelog, clean, funny, humorous, minimal, playful, simple, whimsical, Mise en page fixe, blog, artistic, cartoon, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":254,"popularityRank":81,"launchDate":"2012-07-24","demoUrl":"https:\/\/balloonsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fballoons&amp;_wpnonce=4f50c19fc6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fballoons","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/my-life","name":"My Life","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/my-life\/screenshot.png?w=434"],"description":"A serene blogging theme that emphasizes your content with readable typography. It uses post formats, has three nav menu locations, and supports one-, two-, or three-column layouts.","author":"Justin Tadlock","authorAndUri":"<a href=\"http:\/\/justintadlock.com\">Justin Tadlock<\/a>","version":"1.0-wpcom","tags":"blog, design, journal, lifestream, tumblelog, clean, conservative, earthy, elegant, faded, Clair, natural, retro, textured, traditional, Bleu, Ocre, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":255,"popularityRank":226,"launchDate":"2013-01-24","demoUrl":"https:\/\/mylifedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmy-life&amp;_wpnonce=2d769acecc","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmy-life","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/hero","name":"Hero","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/hero\/screenshot.png?w=434"],"description":"A very neat and clean, black and red business theme. The theme supports sidebar and footer widgets, and simple and neat typography. It also has a front page template with featured post slider and promotional callout areas.","author":"Manishg","authorAndUri":"<a href=\"http:\/\/antthemes.com\/\">Manishg<\/a>","version":"1.0.1-wpcom","tags":"blog, business, clean, contemporary, Sombre, formal, industrial, minimal, professional, sophisticated, Noir, Rouge, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":256,"popularityRank":129,"launchDate":"2012-12-06","demoUrl":"https:\/\/herodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fhero&amp;_wpnonce=33c9e72df2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fhero","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/flounder","name":"Flounder","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/flounder\/screenshot.png?w=434"],"description":"Flounder est un th\u00e8me \u00e9pur\u00e9 et minimaliste pour les blogueurs qui privil\u00e9gie un support color\u00e9 pour le format de leurs billets et une mise en page nette et adaptable.","author":"Kelly Dwan &amp; Mel Choyce","authorAndUri":"<a href=\"http:\/\/themes.redradar.net\/\">Kelly Dwan &amp; Mel Choyce<\/a>","version":"1.0.3-wpcom","tags":"Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Format d&rsquo;article, Personnalisation de l&rsquo;en-t\u00eate, Images \u00e0 la Une, \u00c9diteur de style, Menu personnalis\u00e9, Bleu, Gris, Vert, Orange, Rose, Violet, Jaune, Sombre, bright, clean, colorful, Sombre, minimal, modern, playful, vibrant, blog, journal, lifestream, tumblelog, design, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Mise en page fixe, D\u00e9filement Infini, Rouge, Mise en page adaptable, Support des langues RTL, Argent, Pr\u00eat \u00e0 \u00eatre traduit, Blanc","parent":false,"active":false,"trendingRank":264,"popularityRank":114,"launchDate":"2013-12-18","demoUrl":"https:\/\/flounderdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fflounder&amp;_wpnonce=b2e5c35038","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fflounder","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/brand-new-day","name":"Brand New Day","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/brand-new-day\/screenshot.png?w=434"],"description":"A fun illustrated theme in four &laquo;&nbsp;flavors,&nbsp;&raquo; perfect for personal websites or blogs.","author":"Caroline Moore","authorAndUri":"<a href=\"http:\/\/www.carolinemoore.net\">Caroline Moore<\/a>","version":"1.4-wpcom","tags":"school, education, blog, craft, nature, outdoors, scrapbooking, Saisonnier, tumblelog, artistic, colorful, hand-drawn, handcrafted, playful, textured, whimsical, Bleu, Gris, Vert, Orange, Blanc, Jaune, Une colonne, Deux colonnes, Mise en page fixe, Microformats, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Couleurs personnalis\u00e9es, Menu personnalis\u00e9","parent":false,"active":false,"trendingRank":258,"popularityRank":146,"launchDate":"2011-11-10","demoUrl":"https:\/\/brandnewdaydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbrand-new-day&amp;_wpnonce=22d07fefbb","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbrand-new-day","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/delicacy","name":"Delicacy","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/delicacy\/screenshot.png?w=434"],"description":"Culinary-oriented WordPress theme","author":"Aleksandra &#321;&#261;czek","authorAndUri":"<a href=\"http:\/\/webtuts.pl\/\">Aleksandra &#321;&#261;czek<\/a>","version":"1.2.3-wpcom","tags":"Clair, Blanc, Rouge, food, contemporary, colorful, simple, textured, Deux colonnes, Mise en page fixe, Colonne lat\u00e9rale droite, \u00c9diteur de style, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Curseur d'article, Article mis en avant, En-t\u00eate flexible, D\u00e9filement Infini, elegant, bright, modern, Images \u00e0 la Une, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, blog","parent":false,"active":false,"trendingRank":259,"popularityRank":118,"launchDate":"2012-10-11","demoUrl":"https:\/\/delicacydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fdelicacy&amp;_wpnonce=1190b19a4b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fdelicacy","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/yumblog","name":"Yumblog","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/yumblog\/screenshot.png?w=434"],"description":"Yumblog is a delicious blog theme that can be used for a variety of purposes, including food blogs, recipe sharing, and web journaling.","author":"UpThemes","authorAndUri":"<a href=\"http:\/\/upthemes.com\/\">UpThemes<\/a>","version":"1.3.6","tags":"Clair, Gris, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, artistic, blog, bright, Marron, collaboration, colorful, Couleurs personnalis\u00e9es, earthy, \u00c9diteur de style, elegant, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, food, Vert, D\u00e9filement Infini, modern, natural, Orange, outdoors, playful, Curseur d'article, Mise en page adaptable, Saisonnier, Ocre, textured, threaded-comments, tumblelog, vibrant, whimsical","parent":false,"active":false,"trendingRank":260,"popularityRank":157,"launchDate":"2014-02-17","demoUrl":"https:\/\/yumblogdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fyumblog&amp;_wpnonce=9a1ef61f00","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fyumblog","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/yumblog&#038;ref=themesphp&#038;_wpnonce=9a1ef61f00"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/confit","name":"Confit","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/confit\/screenshot.png?w=434"],"description":"Confit is the perfect theme for restaurants and caf\u00e9s. With Confit, it\u2019s easier than ever to add (and edit) your menu, and to show off your best dishes and restaurant decoration. Map your location so customers can easily find you, and display phone numbers and business hours with our specialized Contact Info widget.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.3-wpcom","tags":"Vert, Orange, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Microformats, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, business, food, clean, elegant, Clair, minimal, modern, simple, sophisticated, vibrant","parent":false,"active":false,"trendingRank":266,"popularityRank":103,"launchDate":"2012-11-28","demoUrl":"https:\/\/confitdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fconfit&amp;_wpnonce=18186606f6","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fconfit","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/fontfolio","name":"Fontfolio","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/fontfolio\/screenshot.png?w=434"],"description":"A stylish, clean, responsive portfolio theme, perfect for typographers, illustrators, or graphic designers.","author":"Marios Lublinski","authorAndUri":"<a href=\"http:\/\/www.dessign.net\/\">Marios Lublinski<\/a>","version":"1.0.2-wpcom","tags":"Noir, Blanc, Clair, Gris, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, design, Photoblogging, photography, portfolio, clean, conservative, geometric, minimal, simple, traditional, magazine","parent":false,"active":false,"trendingRank":262,"popularityRank":177,"launchDate":"2013-08-15","demoUrl":"https:\/\/fontfoliodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ffontfolio&amp;_wpnonce=1ee8a0c680","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ffontfolio","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/rusty-grunge","name":"Rusty Grunge","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/rusty-grunge\/screenshot.png?w=434"],"description":"A somewhat dirty, grungy theme with two widget areas and several customization options, including Custom Background, Header Image, Post Formats, and more.","author":"Christopher Wallace","authorAndUri":"<a href=\"http:\/\/www.chris-wallace.com\">Christopher Wallace<\/a>","version":"1.3-wpcom","tags":"Rouge, Noir, Bleu, Ocre, Vert, Deux colonnes, Mise en page fixe, Colonne lat\u00e9rale droite, Menu personnalis\u00e9, Microformats, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Mod\u00e8le pleine largeur, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Format d&rsquo;article, blog, cartoon, gaming, journal, scrapbooking, tumblelog, colorful, Sombre, grungy, textured, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":264,"popularityRank":134,"launchDate":"2011-03-25","demoUrl":"https:\/\/rustygrungedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Frusty-grunge&amp;_wpnonce=aea65a0576","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Frusty-grunge","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/p2","name":"P2 Classic","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/p2\/screenshot.png?w=434"],"description":"Blogging at the speed of thought. P2 transforms a mild-mannered blog into a super-blog with features like inline comments, a posting form right on the homepage, inline editing of posts and comments, real-time updates, and much more.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.5.6-wpcom","tags":"Bleu, Couleurs personnalis\u00e9es, Deux colonnes, Mise en page fixe, Support des langues RTL, Colonne lat\u00e9rale droite, Blanc, Clair, Page d&rsquo;accueil personnalis\u00e9e, Pr\u00eat \u00e0 \u00eatre traduit, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me, blog, collaboration, education, lifestream, productivity, clean, geometric, minimal, modern","parent":false,"active":false,"trendingRank":265,"popularityRank":125,"launchDate":"2009-11-19","demoUrl":"https:\/\/p2classicdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fp2&amp;_wpnonce=546ec3515a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fp2","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/visual","name":"Visuel","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/visual\/screenshot.png?w=434"],"description":"Un th&egrave;me portofio sombre et &eacute;l&eacute;gant de style r&eacute;actif, et une structure en grille qui sublime vos travaux artistiques.","author":"Devin Price","authorAndUri":"<a href=\"http:\/\/wptheming.com\">Devin Price<\/a>","version":"0.3.1-wpcom","tags":"art, artwork, design, magazine, news, Photoblogging, photography, portfolio, clean, conservative, contemporary, Sombre, elegant, formal, modern, professional, traditional, Noir, Gris, Bleu, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":266,"popularityRank":128,"launchDate":"2013-05-02","demoUrl":"https:\/\/visualdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fvisual&amp;_wpnonce=451a73ea76","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fvisual","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/wedding","name":"Mariage","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/wedding\/screenshot.png?w=434"],"description":"Wedding is an elegant WordPress theme to build a beautiful wedding website easily. Let share your wedding photos, galleries, videos and memorable moments with family &amp; friends by using the wedding WordPress theme.","author":"DesignOrbital","authorAndUri":"<a href=\"http:\/\/designorbital.com\/\">DesignOrbital<\/a>","version":"1.0","tags":"Gris, Rose, Rouge, Argent, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Options du th\u00e8me, Microformats, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, business, design, journal, Photoblogging, photography, travel, tumblelog, wedding, clean, elegant, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":267,"popularityRank":306,"launchDate":"2014-03-03","demoUrl":"https:\/\/weddingdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fwedding&amp;_wpnonce=75baa6e269","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fwedding","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/wedding&#038;ref=themesphp&#038;_wpnonce=75baa6e269"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/blogum","name":"Blogum","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/blogum\/screenshot.png?w=434"],"description":"Blogum is a simple, clean, and grid-based theme designed in a modern and minimalist style with a great attention to detail. It comes with supports for several post formats, including image, gallery, and aside. Includes a full-width template for dropping the sidebar on pages.","author":"WPShower","authorAndUri":"<a href=\"http:\/\/www.wpshower.com\/\">WPShower<\/a>","version":"1.0.1-wpcom","tags":"Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Mod\u00e8le pleine largeur, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, design, journal, news, professional, bright, clean, elegant, geometric, Clair, minimal, modern, simple, sophisticated, traditional, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":275,"popularityRank":88,"launchDate":"2011-07-28","demoUrl":"https:\/\/blogumdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fblogum&amp;_wpnonce=36bacf9e4e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fblogum","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/hatch","name":"Hatch","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/hatch\/screenshot.png?w=434"],"description":"A simple, responsive, and minimal portfolio theme for photographers, illustrators, designers, or photobloggers. Ideal for sites where images are the primary content.","author":"AlienWP","authorAndUri":"<a href=\"http:\/\/alienwp.com\/\">AlienWP<\/a>","version":"0.2.8-wpcom","tags":"art, artwork, design, Photoblogging, photography, portfolio, clean, conservative, contemporary, elegant, Clair, minimal, modern, simple, Noir, Blanc, Gris, Bleu, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":269,"popularityRank":155,"launchDate":"2012-11-08","demoUrl":"https:\/\/hatchdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fhatch&amp;_wpnonce=39d0a05af7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fhatch","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/truly-minimal","name":"Truly Minimal","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/truly-minimal\/screenshot.png?w=434"],"description":"A clean, modern theme that is true to its name, with multiple sidebar placement options and support for all post formats.","author":"FlareThemes","authorAndUri":"<a href=\"http:\/\/www.flarethemes.com\">FlareThemes<\/a>","version":"1.1.6-wpcom","tags":"modern, simple, minimal, clean, Clair, professional, blog, design, Bleu, Blanc, Gris, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Colonne lat\u00e9rale gauche, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":270,"popularityRank":166,"launchDate":"2013-04-11","demoUrl":"https:\/\/trulyminimaldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftruly-minimal&amp;_wpnonce=0f2da8cf48","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftruly-minimal","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/vintage-camera","name":"Vintage Camera","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/vintage-camera\/screenshot.png?w=434"],"description":"Un th&egrave;me dot&eacute; de six styles\/couleurs, adapt&eacute; au microblogging illustr&eacute;, cher aux amateurs de photos vintage. Supporte tous les formats d&rsquo;articles, et dispose des options menu, en-t&ecirc;te, et arri&egrave;re-plan personnalis&eacute;s.","author":"Caroline Moore","authorAndUri":"<a href=\"http:\/\/www.carolinemoore.net\">Caroline Moore<\/a>","version":"2.3.1-wpcom","tags":"Marron, Gris, Rouge, Rose, Sombre, Clair, Vert, Une colonne, Mise en page adaptable, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, artistic, hand-drawn, photography, Photoblogging, retro","parent":false,"active":false,"trendingRank":271,"popularityRank":94,"launchDate":"2012-07-19","demoUrl":"https:\/\/vintagecamerademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fvintage-camera&amp;_wpnonce=126c610468","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fvintage-camera","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/shelf","name":"Shelf","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/shelf\/screenshot.png?w=434"],"description":"A unique tumblelog style theme featuring a fluid and responsive design. Looks great on the iPad, iPhone, and other modern mobile devices.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"2.2.5-wpcom","tags":"design, journal, lifestream, portfolio, tumblelog, music, video, blog, artistic, clean, colorful, elegant, handcrafted, Jaune, Gris, Clair, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Images \u00e0 la Une, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Format d&rsquo;article, Couleurs personnalis\u00e9es","parent":false,"active":false,"trendingRank":272,"popularityRank":45,"launchDate":"2011-02-03","demoUrl":"https:\/\/shelfdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fshelf&amp;_wpnonce=e25585220f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fshelf","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/shelf&#038;ref=themesphp&#038;_wpnonce=e25585220f"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/origin","name":"Origin","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/origin\/screenshot.png?w=434"],"description":"Minimalistic, mobile-optimized theme with responsive layout.","author":"AlienWP","authorAndUri":"<a href=\"http:\/\/alienwp.com\">AlienWP<\/a>","version":"0.3.1-wpcom","tags":"blog, design, journal, simple, traditional, Menu personnalis\u00e9, Mise en page fluide, Mise en page adaptable, Microformats, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Article mis en avant, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Blanc, Noir, modern, clean, Clair, minimal","parent":false,"active":false,"trendingRank":273,"popularityRank":101,"launchDate":"2012-04-26","demoUrl":"https:\/\/origindemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Forigin&amp;_wpnonce=91ac129970","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Forigin","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/bold-life","name":"Bold Life","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/bold-life\/screenshot.png?w=434"],"description":"Un th\u00e8me aux couleurs vibrantes et audacieuses, id\u00e9al pour un blog personnel.","author":"jayhafling","authorAndUri":"<a href=\"http:\/\/www.jayhafling.com\/\">jayhafling<\/a>","version":"1.2-wpcom","tags":"Noir, Marron, Orange, Rouge, Ocre, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, announcement, art, blog, craft, journal, scrapbooking, artistic, colorful, earthy, faded, grungy, hand-drawn, handcrafted, natural, paper-made, textured, vibrant","parent":false,"active":false,"trendingRank":265,"popularityRank":167,"launchDate":"2011-09-29","demoUrl":"https:\/\/boldlifedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbold-life&amp;_wpnonce=e4b1509631","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbold-life","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/fruit-shake","name":"Fruit Shake","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/fruit-shake\/screenshot.png?w=434"],"description":"Fruit Shake features multiple fruit flavors (color schemes actually, including a secret unlockable one), an optional, one-column, tumblelog layout (just remove the widgets from your sidebar to see it), and all your favorite theme features like custom headers, backgrounds, and menus. It&rsquo;s a perfectly fruitylicious theme for your blog.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"blog, craft, nature, tumblelog, artistic, colorful, faded, Clair, whimsical, playful, Bleu, Vert, Rose, Jaune, Une colonne, Deux colonnes, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Microformats, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL","parent":false,"active":false,"trendingRank":275,"popularityRank":121,"launchDate":"2011-07-05","demoUrl":"https:\/\/fruitshakedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ffruit-shake&amp;_wpnonce=afba9c810f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ffruit-shake","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/basic-maths","name":"Basic Maths","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/basic-maths\/screenshot.png?w=434"],"description":"Basic Maths is a thoughtful and well-constructed grid theme based on the landmark design of Khoi Vinh&rsquo;s subtraction.com. One of the best looking, most elegant, and smartest designed blog themes available. Make it yours with custom colors, custom header image, custom menu, and custom background. Originally designed by Khoi Vinh and built by Allan Cole.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2-wpcom","tags":"Couleurs personnalis\u00e9es, Blanc, Trois colonnes, Mise en page fixe, Mise en page adaptable, Colonne lat\u00e9rale droite, Options du th\u00e8me, Microformats, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, magazine, news, professional, contemporary, elegant, formal, geometric, Clair, professional, Orange","parent":false,"active":false,"trendingRank":276,"popularityRank":169,"launchDate":"2011-03-30","demoUrl":"https:\/\/basicmathsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbasic-maths&amp;_wpnonce=2f4f925648","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbasic-maths","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/basic-maths&#038;ref=themesphp&#038;_wpnonce=2f4f925648"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/scrollider-express","name":"Scrollider Express","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/scrollider-express\/screenshot.png?w=434"],"description":"A clean blogging theme designed by <a href=\"http:\/\/www.woothemes.com\">WooThemes<\/a>.","author":"WooThemes","authorAndUri":"<a href=\"http:\/\/woothemes.com\/\">WooThemes<\/a>","version":"1.0.1","tags":"blog, travel, photography, journal, Photoblogging, clean, elegant, modern, sophisticated, Gris, Blanc, Noir, Vert, Orange, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":277,"popularityRank":284,"launchDate":"2013-03-21","demoUrl":"https:\/\/scrolliderexpressdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fscrollider-express&amp;_wpnonce=069cf71e51","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fscrollider-express","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/scrollider-express&#038;ref=themesphp&#038;_wpnonce=069cf71e51"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>68","purchased":false}},{"id":"pub\/untitled","name":"Sans titre","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/untitled\/screenshot.png?w=434"],"description":"Un joli th\u00e8me au charme particulier. Permet des articles et des images pr\u00e9sent\u00e9s en pleine page, un en-t\u00eate fixe, et de subtiles transitions en CSS3.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.4-wpcom","tags":"Noir, Blanc, Une colonne, Colonne lat\u00e9rale droite, Deux colonnes, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, Curseur d'article, abstract, artistic, clean, minimal, modern, Mise en page adaptable","parent":false,"active":false,"trendingRank":278,"popularityRank":144,"launchDate":"2013-05-09","demoUrl":"https:\/\/untitleddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Funtitled&amp;_wpnonce=0b2f98393b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Funtitled","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/autofocus","name":"AutoFocus","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/autofocus\/screenshot.png?w=434"],"description":"Ce th\u00e8me \u00e9l\u00e9gant et minimaliste est con\u00e7u pour les cr\u00e9atifs \u2013 artistes ou photographes, par exemple \u2013 qui souhaitent promouvoir leur talent en ligne de fa\u00e7on simple et attractive.","author":"Allan Cole","authorAndUri":"<a href=\"http:\/\/allancole.com\/wordpress\/\">Allan Cole<\/a>","version":"1.1-wpcom","tags":"Gris, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, lifestream, Photoblogging, photography, scrapbooking, clean, elegant, simple, sophisticated","parent":false,"active":false,"trendingRank":279,"popularityRank":76,"launchDate":"2011-12-06","demoUrl":"https:\/\/autofocusdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fautofocus&amp;_wpnonce=df234bf3ed","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fautofocus","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/forefront","name":"Forefront","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/forefront\/screenshot.png?w=434"],"description":"Forefront is a responsive business and corporate theme that helps you to create a strong&#8211;yet beautiful&#8211;online presence for your business.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2-wpcom","tags":"Gris, Vert, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, collaboration, design, food, hotel, journal, magazine, news, portfolio, real-estate, bright, clean, conservative, elegant, formal, Clair, minimal, modern, professional, simple, sophisticated, traditional","parent":false,"active":false,"trendingRank":280,"popularityRank":136,"launchDate":"2013-06-11","demoUrl":"https:\/\/forefrontdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fforefront&amp;_wpnonce=928a7743ff","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fforefront","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/forefront&#038;ref=themesphp&#038;_wpnonce=928a7743ff"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>175","purchased":false}},{"id":"premium\/debut","name":"Debut","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/debut\/screenshot.png?w=434"],"description":"An eye-catching multimedia theme featuring a unique content carousel and responsive gallery style layout.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"4.4.0","tags":"blog, business, portfolio, magazine, music, news, outdoors, sports, tech, video, artistic, clean, professional, Sombre, Noir, Bleu, Gris, Blanc, Trois colonnes, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Curseur d'article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":281,"popularityRank":93,"launchDate":"2012-02-02","demoUrl":"https:\/\/debutdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fdebut&amp;_wpnonce=0ecd629912","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fdebut","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/debut&#038;ref=themesphp&#038;_wpnonce=0ecd629912"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"pub\/pink-touch-2","name":"Pink Touch 2","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/pink-touch-2\/screenshot.png?w=434"],"description":"A theme that has a stellar mix of color, texture and typography. Designed by Kcmr. It features a custom header, custom background, and maximum three widget areas in the footer. It comes with supports for several post formats including aside, gallery, image, quote, link, chat, and audio.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.3.1-wpcom","tags":"Gris, Rose, Rouge, Argent, Clair, Une colonne, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, blog, design, fashion, journal, news, tumblelog, video, bright, clean, modern, simple, textured","parent":false,"active":false,"trendingRank":282,"popularityRank":83,"launchDate":"2011-08-09","demoUrl":"https:\/\/pinktouch2demo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fpink-touch-2&amp;_wpnonce=3e9ed0d664","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fpink-touch-2","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/minimum","name":"Minimum","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/minimum\/screenshot.png?w=434"],"description":"Minimum is a stunning execution of &laquo;&nbsp;less is more&nbsp;&raquo;, which allows you to express everything you&rsquo;re about, with very little effort.","author":"StudioPress","authorAndUri":"<a href=\"http:\/\/www.studiopress.com\/\">StudioPress<\/a>","version":"1.0.1","tags":"Noir, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mise en page fixe, Gris, Colonne lat\u00e9rale gauche, Une colonne, Colonne lat\u00e9rale droite, Article mis en avant, Options du th\u00e8me, Trois colonnes, Deux colonnes, Blanc, blog, clean, contemporary, design, Image d&rsquo;en-t\u00eate \u00e0 la Une, Mod\u00e8le pleine largeur, journal, Clair, minimal, photography, portfolio, professional, professional, simple","parent":"Genesis","active":false,"trendingRank":283,"popularityRank":55,"launchDate":"2011-08-31","demoUrl":"https:\/\/minimumdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fminimum&amp;_wpnonce=3bb56fc089","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fminimum","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/minimum&#038;ref=themesphp&#038;_wpnonce=3bb56fc089"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/pinboard","name":"Pinboard","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/pinboard\/screenshot.png?w=434"],"description":"A crafty, textured theme with three post column sizes, optional right or left sidebar, and an area for a welcome message.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"craft, design, lifestream, magazine, scrapbooking, blog, artistic, handcrafted, Clair, natural, paper-made, playful, textured, Rouge, Ocre, Clair, Deux colonnes, Trois colonnes, Quatre colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":284,"popularityRank":133,"launchDate":"2012-09-20","demoUrl":"https:\/\/pinboarddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpinboard&amp;_wpnonce=5b8f886130","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpinboard","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/pinboard&#038;ref=themesphp&#038;_wpnonce=5b8f886130"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>50","purchased":false}},{"id":"pub\/sundance","name":"Sundance","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sundance\/screenshot.png?w=434"],"description":"A free video theme brought to you by the folks at Automattic. Despite its minimalist design, Sundance was crafted with clean, elegant typography and close attention to detail. The home page offers a featured video carousel. It supports the video post format, widgets, custom background, custom header, custom menus, and a custom link feature for your social media pages.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.5-wpcom","tags":"Gris, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, En-t\u00eate flexible, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, blog, journal, news, video, bright, clean, minimal, simple","parent":false,"active":false,"trendingRank":285,"popularityRank":116,"launchDate":"2012-03-01","demoUrl":"https:\/\/sundancedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsundance&amp;_wpnonce=889428089b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsundance","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/full-frame","name":"Full Frame","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/full-frame\/screenshot.png?w=434"],"description":"Full Frame est un th&egrave;me WordPress id&eacute;al pour exposer de grandes images, galeries et vid&eacute;os, et raconter des histoires, ou pr&eacute;senter un travail de fa&ccedil;on unique.","author":"Graph Paper Press","authorAndUri":"<a href=\"http:\/\/graphpaperpress.com\">Graph Paper Press<\/a>","version":"1.0.2","tags":"art, blog, craft, design, fashion, food, journal, magazine, music, nature, Photoblogging, photography, portfolio, travel, video, wedding, clean, colorful, Sombre, elegant, futuristic, Clair, minimal, modern, playful, simple, vibrant, Noir, Rouge, Blanc, Sombre, Une colonne, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":286,"popularityRank":57,"launchDate":"2013-03-28","demoUrl":"https:\/\/fullframedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Ffull-frame&amp;_wpnonce=41e0ef632a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Ffull-frame","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/full-frame&#038;ref=themesphp&#038;_wpnonce=41e0ef632a"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/mckinley","name":"McKinley","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/mckinley\/screenshot.png?w=434"],"description":"McKinley est un th\u00e8me de blog soign\u00e9, bas\u00e9 sur le superbe th\u00e8me TwentyThirteen de WordPress.","author":"ThemeTrust","authorAndUri":"<a href=\"http:\/\/themetrust.com\/\">ThemeTrust<\/a>","version":"1.2-wpcom","tags":"Une colonne, Mise en page fluide, Menu personnalis\u00e9, Images \u00e0 la Une, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":287,"popularityRank":141,"launchDate":"2014-01-22","demoUrl":"https:\/\/mckinleydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fmckinley&amp;_wpnonce=3d75fa0369","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fmckinley","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/personal","name":"Personal","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/personal\/screenshot.png?w=434"],"description":"A minimal, content-first theme tailored for writers, journalists and bloggers.","author":"Obox Themes","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/by\/obox-themes\/\">Obox Themes<\/a>","version":"1.0-wpcom","tags":"Noir, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Article mis en avant, blog, business, design, Vacances, Photoblogging, travel, video, clean, conservative, contemporary, formal, Clair, minimal, modern, simple, sophisticated","parent":false,"active":false,"trendingRank":288,"popularityRank":225,"launchDate":"2013-08-29","demoUrl":"https:\/\/personaldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpersonal&amp;_wpnonce=44969c4dfe","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpersonal","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/personal&#038;ref=themesphp&#038;_wpnonce=44969c4dfe"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>80","purchased":false}},{"id":"premium\/mimbopro","name":"Mimbo Pro","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/mimbopro\/screenshot.png?w=434"],"description":"A classically designed magazine theme, with flexible widget sidebars, custom header and background images, and custom footer widgets.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/prothemedesign.com\/themes\/mimbo-pro\/\">Pro Theme Design<\/a>","version":"4.3","tags":"Noir, clean, contemporary, professional, Sombre, Bleu, magazine, elegant, modern, sophisticated, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fixe, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":289,"popularityRank":160,"launchDate":"2012-04-05","demoUrl":"https:\/\/mimboprodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmimbopro&amp;_wpnonce=a6bc0a9e6a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmimbopro","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/mimbopro&#038;ref=themesphp&#038;_wpnonce=a6bc0a9e6a"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>59","purchased":false}},{"id":"premium\/on-a-whim","name":"On a Whim","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/on-a-whim\/screenshot.png?w=434"],"description":"A colorful and whimsical blogging theme designed by Meagan Fisher.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"Vert, Orange, Ocre, Sombre, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, craft, food, journal, colorful, curved, geometric, playful, vibrant, whimsical","parent":false,"active":false,"trendingRank":290,"popularityRank":213,"launchDate":"2013-05-09","demoUrl":"https:\/\/onawhimdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fon-a-whim&amp;_wpnonce=e9e616996f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fon-a-whim","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/on-a-whim&#038;ref=themesphp&#038;_wpnonce=e9e616996f"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/collective","name":"Collective","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/collective\/screenshot.png?w=434"],"description":"A theme for small businesses with an emphasis on staff or collaboration.","author":"Organic Themes","authorAndUri":"<a href=\"http:\/\/www.organicthemes.com\">Organic Themes<\/a>","version":"1.0","tags":"blog, business, education, photography, portfolio, clean, elegant, Clair, minimal, modern, tech, Noir, Gris, Vert, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, artwork, journal, magazine, collaboration, simple, sophisticated, contemporary, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, professional, Curseur d'article, En-t\u00eate flexible, Mise en page adaptable, Mise en page fluide, threaded-comments","parent":false,"active":false,"trendingRank":291,"popularityRank":183,"launchDate":"2014-04-23","demoUrl":"https:\/\/collectivedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcollective&amp;_wpnonce=a49b9d149b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcollective","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/collective&#038;ref=themesphp&#038;_wpnonce=a49b9d149b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/gallery","name":"Galerie","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/gallery\/screenshot.png?w=434"],"description":"A grid-based theme with masonry layout, infinite scroll, and single column post layouts.","author":"UpThemes","authorAndUri":"<a href=\"https:\/\/upthemes.com\">UpThemes<\/a>","version":"3.2.6","tags":"site-logo, Blanc, Vert, Gris, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, contemporary, En-t\u00eate flexible, threaded-comments, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, cartoon, collaboration, craft, design, fashion, food, lifestream, music, Photoblogging, photography, portfolio, scrapbooking, travel, tumblelog, video, artistic, bright, clean, colorful, elegant, formal, geometric, Clair, minimal, modern, professional, simple, sophisticated, tech, vibrant","parent":false,"active":false,"trendingRank":280,"popularityRank":196,"launchDate":"2014-01-23","demoUrl":"https:\/\/gallerydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fgallery&amp;_wpnonce=a02fa8c102","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fgallery","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/gallery&#038;ref=themesphp&#038;_wpnonce=a02fa8c102"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/able","name":"Able","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/able\/screenshot.png?w=434"],"description":"Un th\u00e8me de blog traditionnel, multi-usage avec une mise en page nette, adaptable et d&rsquo;une agr\u00e9able lisibilit\u00e9, qui peut s&rsquo;afficher sur trois larges colonnes.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.2.3-wpcom","tags":"Bleu, Gris, Blanc, Clair, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page adaptable, D\u00e9filement Infini, blog, news, clean, traditional","parent":false,"active":false,"trendingRank":293,"popularityRank":202,"launchDate":"2012-08-30","demoUrl":"https:\/\/abledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fable&amp;_wpnonce=cc55b9ba81","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fable","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/bushwick","name":"Bushwick","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/bushwick\/screenshot.png?w=434"],"description":"Bushwick est un th\u00e8me l\u00e9ger et r\u00e9actif, parfaitement adapt\u00e9 pour bloguer et pr\u00e9senter un contenu attractif et de belles images.","author":"James Dinsdale and Automattic","authorAndUri":"<a href=\"http:\/\/molovo.co.uk\">James Dinsdale and Automattic<\/a>","version":"1.3.1-wpcom","tags":"Photoblogging, photography, art, artwork, blog, design, fashion, bright, clean, elegant, modern, sophisticated, Blanc, Violet, Clair, Deux colonnes, Mise en page adaptable, Mise en page fluide, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Microformats, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":302,"popularityRank":139,"launchDate":"2013-12-31","demoUrl":"https:\/\/bushwickdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fbushwick&amp;_wpnonce=b309ec4b6c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fbushwick","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/zoren","name":"Zoren","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/zoren\/screenshot.png?w=434"],"description":"Un th&egrave;me WordPress flexible et polyvalent, gracieusement r&eacute;alis&eacute; par fabthemes.com pour la communaut&eacute; des utilisateurs.","author":"Fabthemes","authorAndUri":"<a href=\"http:\/\/www.fabthemes.com\">Fabthemes<\/a>","version":"1.0.2-wpcom","tags":"Clair, Gris, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, journal, tumblelog, bright, clean, elegant, minimal, modern","parent":false,"active":false,"trendingRank":295,"popularityRank":112,"launchDate":"2013-08-01","demoUrl":"https:\/\/zorendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fzoren&amp;_wpnonce=b7e374999c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fzoren","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/watson","name":"Watson","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/watson\/screenshot.png?w=434"],"description":"Un th&egrave;me de style magazine, brillant et tr&egrave;s classe. Parfait pour le photojournalisme et les blogs d&rsquo;auteurs au contenu substantiel.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"1.1.7-wpcom","tags":"Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, fashion, journal, magazine, news, professional, sports, clean, elegant, formal, handcrafted, Clair, minimal, sophisticated","parent":false,"active":false,"trendingRank":297,"popularityRank":51,"launchDate":"2012-11-29","demoUrl":"https:\/\/watsondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fwatson&amp;_wpnonce=2b4ebb4e16","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fwatson","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/watson&#038;ref=themesphp&#038;_wpnonce=2b4ebb4e16"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/sempress","name":"SemPress","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/sempress\/screenshot.png?w=434"],"description":"SemPress is a respsonsive theme perfect for personal blogs. Rebuilt for WordPress.com.","author":"Matthias Pfefferle","authorAndUri":"<a href=\"http:\/\/notizblog.org\/\">Matthias Pfefferle<\/a>","version":"1.1-wpcom","tags":"Noir, Gris, Clair, Blanc, Mise en page fluide, Mise en page adaptable, Une colonne, Colonne lat\u00e9rale droite, Deux colonnes, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, portfolio, video, simple, clean, elegant, minimal","parent":false,"active":false,"trendingRank":297,"popularityRank":254,"launchDate":"2013-04-18","demoUrl":"https:\/\/sempressdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsempress&amp;_wpnonce=2897ffadfd","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsempress","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/anthem","name":"Anthem","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/anthem\/screenshot.png?w=434"],"description":"Un th\u00e8me tumblog minimaliste et adaptatif pour les photographes, les artistes et les cr\u00e9atifs. Il prend en charge les formats image, galerie, audio, vid\u00e9o, chat, lien et citation. Un excellent rendu sur tous les appareils.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\">The Theme Foundry<\/a>","version":"1.4.2-wpcom","tags":"Blanc, Mise en page adaptable, tumblelog, Noir, Gris, Clair, Deux colonnes, Images \u00e0 la Une, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Format d&rsquo;article, Microformats, Options du th\u00e8me, Couleurs personnalis\u00e9es, art, artwork, blog, design, fashion, journal, lifestream, music, Photoblogging, photography, video, artistic, clean, elegant, handcrafted, minimal, modern, sophisticated","parent":false,"active":false,"trendingRank":301,"popularityRank":78,"launchDate":"2011-11-17","demoUrl":"https:\/\/anthemdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fanthem&amp;_wpnonce=d0597aee23","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fanthem","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/anthem&#038;ref=themesphp&#038;_wpnonce=d0597aee23"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/standard","name":"Par d\u00e9faut","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/standard\/screenshot.png?w=434"],"description":"Standard is a meticulously designed, hand-crafted theme for professional blogging. It adapts to mobile devices and individual posts can be styled distinctly for words, images, quotes, links, videos, or statuses using post formats.","author":"WooThemes","authorAndUri":"<a href=\"http:\/\/www.woothemes.com\/\">WooThemes<\/a>","version":"3.4.1-wpcom","tags":"blog, design, lifestream, productivity, professional, clean, minimal, modern, simple, sophisticated, Noir, Bleu, Gris, Clair, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, En-t\u00eate flexible, Mise en page fixe, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":299,"popularityRank":46,"launchDate":"2012-03-22","demoUrl":"https:\/\/standarddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fstandard&amp;_wpnonce=bc9b89a2ef","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fstandard","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/standard&#038;ref=themesphp&#038;_wpnonce=bc9b89a2ef"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>39","purchased":false}},{"id":"vip\/partner-mlb-fan","name":"MLB \"Fan\"","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/vip\/partner-mlb-fan\/screenshot.png?w=434"],"description":"The Official Major League Baseball &laquo;&nbsp;Fan&nbsp;&raquo; theme for WordPress.com is loud and vibrant, as every good baseball fan should be. By activating this theme, you agree to the MLB <a href=\"http:\/\/mlb.mlb.com\/mlb\/official_info\/about_mlb_com\/terms_of_use.jsp\">terms of service<\/a>.","author":"MLB","authorAndUri":"<a href=\"http:\/\/www.mlb.com\">MLB<\/a>","version":"1.0","tags":"mlb, major-league-baseball, partner, sports, colorful, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Options du th\u00e8me, bright, colorful, flamboyant, playful, vibrant, blog","parent":"MLB \"Modern\"","active":false,"trendingRank":300,"popularityRank":246,"launchDate":"2011-05-16","demoUrl":"https:\/\/partnermlbfandemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=vip%2Fpartner-mlb-fan&amp;_wpnonce=348b926f5d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=vip%2Fpartner-mlb-fan","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/superhero","name":"Superhero","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/superhero\/screenshot.png?w=434"],"description":"Parez votre blog de quelques touches vives dans un style &eacute;pur&eacute;. Superhero dispose des options d&rsquo;articles et images \u00e0 la Une, d&rsquo;une en-t&ecirc;te fixe, et des transitions de CSS3.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.3-wpcom","tags":"clean, Mise en page adaptable, Gris, Deux colonnes, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Format d&rsquo;article, Curseur d'article, site-logo, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, Support des langues RTL, blog, business","parent":false,"active":false,"trendingRank":301,"popularityRank":152,"launchDate":"2013-03-07","demoUrl":"https:\/\/superherodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsuperhero&amp;_wpnonce=a2b632db7f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsuperhero","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/hum","name":"Hum","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/hum\/screenshot.png?w=434"],"description":"A responsive theme designed to show off a stream of posts, quotes, and images. Add a custom logo to stand out from the crowd. Hum builds off Twenty Eleven, so you get all of the goodness of a WordPress core theme included.","author":"Daryl Koopersmith","authorAndUri":"<a href=\"http:\/\/darylkoop.com\/\">Daryl Koopersmith<\/a>","version":"0.2.1-wpcom","tags":"Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, lifestream, tumblelog, clean, conservative, formal, minimal, modern, simple, sophisticated, D\u00e9filement Infini, Couleurs personnalis\u00e9es, En-t\u00eate flexible, Clair, Blanc, Gris, Une colonne, Deux colonnes, Mise en page adaptable, Bleu, Menu personnalis\u00e9, Colonne lat\u00e9rale gauche, Mise en page fluide, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Article mis en avant, Format d&rsquo;article, Images \u00e0 la Une","parent":"Twenty Eleven","active":false,"trendingRank":302,"popularityRank":241,"launchDate":"2012-10-05","demoUrl":"https:\/\/humdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fhum&amp;_wpnonce=2979db43c3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fhum","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"pub\/eventbrite-venue","name":"Eventbrite Multi Event","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/eventbrite-venue\/screenshot.png?w=434"],"description":"Utilisez ce th&egrave;me pour promouvoir vos activit&eacute;s, ou projets,Eventbrite et rester en contact avec votre audience avant et apr&egrave;s les &eacute;v&egrave;nements, nouveaut&eacute;s, mises &agrave; jour, commentaires et partages sociaux.","author":"Voce Platforms","authorAndUri":"<a href=\"http:\/\/voceplatforms.com\">Voce Platforms<\/a>","version":"1.2.2","tags":"Mise en page adaptable, Deux colonnes, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Support des langues RTL, Menu personnalis\u00e9","parent":false,"active":false,"trendingRank":303,"popularityRank":181,"launchDate":"2013-09-16","demoUrl":"https:\/\/eventbritevenuedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Feventbrite-venue&amp;_wpnonce=d7ecd18e9f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Feventbrite-venue","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/bloggy","name":"Bloggy","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/bloggy\/screenshot.png?w=434"],"description":"Bloggy is an easy to use theme with responsive layout that looks great on any device, big or small. Bloggy features different post formats, each displayed in their own unique way. If you want to make your blog post more flexible you can use different kinds of post formats such as image, gallery, video, aside, link or quotes.","author":"Anariel Design","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/by\/anariel-design\/\">Anariel Design<\/a>","version":"1.0","tags":"Colonne lat\u00e9rale droite, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Mise en page adaptable, Article mis en avant, Clair, blog, design, Mod\u00e8le pleine largeur, D\u00e9filement Infini, news, Marron, elegant, artistic, portfolio, Format d&rsquo;article","parent":false,"active":false,"trendingRank":304,"popularityRank":130,"launchDate":"2014-04-30","demoUrl":"https:\/\/bloggydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbloggy&amp;_wpnonce=04b828a780","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbloggy","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/bloggy&#038;ref=themesphp&#038;_wpnonce=04b828a780"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/on-demand","name":"On Demand","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/on-demand\/screenshot.png?w=434"],"description":"A video centric theme with a unique content carousel to make your videos stand out and accessible.","author":"Press75","authorAndUri":"<a href=\"http:\/\/www.press75.com\/\">Press75<\/a>","version":"3.0.2-wpcom","tags":"Couleurs personnalis\u00e9es, Gris, Blanc, Colonne lat\u00e9rale droite, Deux colonnes, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Format d&rsquo;article, Curseur d'article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, portfolio, professional, video, contemporary, Clair, minimal, simple","parent":false,"active":false,"trendingRank":305,"popularityRank":90,"launchDate":"2012-03-29","demoUrl":"https:\/\/ondemanddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fon-demand&amp;_wpnonce=b98377a068","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fon-demand","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/on-demand&#038;ref=themesphp&#038;_wpnonce=b98377a068"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/snap","name":"Snap","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/snap\/screenshot.png?w=434"],"description":"Un th\u00e8me l\u00e9ger et adaptatif con\u00e7u dans l&rsquo;optique de vous aider \u00e0 pr\u00e9senter en ligne vos projets de cr\u00e9ations. Plusieurs mod\u00e8les de pages et une mise en page organis\u00e9e en grille vous assurent d&rsquo;apporter \u00e0 votre site Web flexibilit\u00e9 et professionnalisme.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"1.0.10-wpcom","tags":"business, portfolio, professional, art, photography, clean, elegant, formal, handcrafted, Clair, minimal, Gris, Blanc, Clair, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Article mis en avant, Options du th\u00e8me, D\u00e9filement Infini, Pr\u00eat \u00e0 \u00eatre traduit, artwork, blog, contemporary, craft, design, geometric, journal, modern, Curseur d'article, simple, traditional","parent":false,"active":false,"trendingRank":306,"popularityRank":192,"launchDate":"2013-05-13","demoUrl":"https:\/\/snapdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fsnap&amp;_wpnonce=2c343e009a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fsnap","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/snap&#038;ref=themesphp&#038;_wpnonce=2c343e009a"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"pub\/comet","name":"Comet","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/comet\/screenshot.png?w=434"],"description":"A very classy, lightweight, and content-focused theme, customizable to your liking. Includes seven color schemes, four layout options, and a full-width page template.","author":"Frostpress","authorAndUri":"<a href=\"http:\/\/frostpress.com\/\">Frostpress<\/a>","version":"1.4.2-wpcom","tags":"Clair, Blanc, Gris, Rouge, Jaune, Vert, Bleu, Violet, Une colonne, Deux colonnes, Trois colonnes, Mise en page fixe, Colonne lat\u00e9rale droite, Colonne lat\u00e9rale gauche, Couleurs personnalis\u00e9es, Article mis en avant, Menu personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Arri\u00e8re-plan personnalis\u00e9, Mod\u00e8le pleine largeur, Support des langues RTL, Options du th\u00e8me, blog, journal, conservative, faded, simple, traditional","parent":false,"active":false,"trendingRank":307,"popularityRank":175,"launchDate":"2011-09-06","demoUrl":"https:\/\/cometdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fcomet&amp;_wpnonce=fc1d0f1c44","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fcomet","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/healthy-living","name":"Healthy Living","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/healthy-living\/screenshot.png?w=434"],"description":"Healthy Living is a fresh, simple, and well-rounded blogging theme. With its laid-back, modern design, and beautiful typography, this theme gives your content the deserved spotlight and draws your readers right in. It is fully responsive and includes different page templates, post formats, and a custom header image to expand your customizing options.","author":"Anariel Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/anariel-design\/\">Anariel Design<\/a>","version":"1.0","tags":"Gris, Blanc, Clair, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Article mis en avant, blog, business, collaboration, design, food, hotel, portfolio, real-estate, school, bright, clean, elegant, Clair, minimal, modern, professional, simple, sophisticated, traditional","parent":false,"active":false,"trendingRank":308,"popularityRank":107,"launchDate":"2014-08-15","demoUrl":"https:\/\/healthylivingdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fhealthy-living&amp;_wpnonce=f4e993501b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fhealthy-living","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/healthy-living&#038;ref=themesphp&#038;_wpnonce=f4e993501b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/thestyle","name":"TheStyle","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/thestyle\/screenshot.png?w=434"],"description":"A grid-based blog theme featuring a bold and beautiful style.","author":"Elegant Themes","authorAndUri":"<a href=\"http:\/\/www.elegantthemes.com\">Elegant Themes<\/a>","version":"1.0","tags":"Sombre, Deux colonnes, Une colonne, Colonne lat\u00e9rale droite, Mise en page fluide, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, artistic, Noir, blog, clean, contemporary, Couleurs personnalis\u00e9es, elegant, fashion, D\u00e9filement Infini, journal, magazine, modern, news, Une colonne, Blanc","parent":false,"active":false,"trendingRank":314,"popularityRank":80,"launchDate":"2013-04-25","demoUrl":"https:\/\/thestyledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fthestyle&amp;_wpnonce=4914cb6aaf","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fthestyle","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/thestyle&#038;ref=themesphp&#038;_wpnonce=4914cb6aaf"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>68","purchased":false}},{"id":"pub\/trvl","name":"Trvl","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/trvl\/screenshot.png?w=434"],"description":"Con\u00e7u par Danny Cohen, Trvl est un simple et superbe th\u00e8me tumblelog.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.1-wpcom","tags":"blog, tumblelog, clean, contemporary, Sombre, simple, D\u00e9filement Infini, Bleu, Gris, Jaune, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":310,"popularityRank":179,"launchDate":"2013-06-06","demoUrl":"https:\/\/trvldemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Ftrvl&amp;_wpnonce=256f8cba01","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Ftrvl","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"vip\/partner-mlb-retro","name":"MLB \"Retro\"","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/vip\/partner-mlb-retro\/screenshot.png?w=434"],"description":"The Official Major League Baseball &laquo;&nbsp;Retro&nbsp;&raquo; theme for WordPress.com is a throwback to old MLB Club logos and styles, for baseball fans with a sense of nostalgia. By activating this theme, you agree to the MLB <a href=\"http:\/\/mlb.mlb.com\/mlb\/official_info\/about_mlb_com\/terms_of_use.jsp\">terms of service<\/a>.","author":"MLB","authorAndUri":"<a href=\"http:\/\/www.mlb.com\">MLB<\/a>","version":"1.0","tags":"mlb, major-league-baseball, partner, sports, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Options du th\u00e8me, retro, traditional, blog","parent":"MLB \"Modern\"","active":false,"trendingRank":311,"popularityRank":298,"launchDate":"2011-05-16","demoUrl":"https:\/\/partnermlbretrodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=vip%2Fpartner-mlb-retro&amp;_wpnonce=8a3c35beb4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=vip%2Fpartner-mlb-retro","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/tdeditor","name":"tdeditor","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/tdeditor\/screenshot.png?w=434"],"description":"A responsive, clean and simple WordPress theme developed for news websites, magazines and blogs.","author":"Tasko","authorAndUri":"<a href=\"http:\/\/tdwp.us\/\">Tasko<\/a>","version":"1.0","tags":"Noir, Blanc, Clair, Sombre, Deux colonnes, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, news, clean, minimal, modern, Une colonne, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, journal, magazine, simple, D\u00e9filement Infini, professional, Curseur d'article, education, fashion, food","parent":false,"active":false,"trendingRank":312,"popularityRank":215,"launchDate":"2014-07-08","demoUrl":"https:\/\/tdeditordemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Ftdeditor&amp;_wpnonce=30a2ab5f7b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Ftdeditor","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/tdeditor&#038;ref=themesphp&#038;_wpnonce=30a2ab5f7b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"pub\/syntax","name":"Syntax","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/pub\/syntax\/screenshot.png?w=434"],"description":"Syntax est un th\u00e8me con\u00e7u pour l\u2019\u00e9criture et la lecture. Sa grande police facile \u00e0 lire, son menu de navigation fixe et son graphisme adaptable au tr\u00e8s beau rendu sur tous les \u00e9crans quelle que soit leur taille le rendent parfait pour les \u00e9crivains ou les bloggeurs qui recherchent une pr\u00e9sentation nette et sophistiqu\u00e9e pour leur site.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.9-wpcom","tags":"Clair, Noir, Blanc, Une colonne, Gris, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, clean, conservative, minimal, simple, traditional","parent":false,"active":false,"trendingRank":313,"popularityRank":123,"launchDate":"2014-01-16","demoUrl":"https:\/\/syntaxdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=pub%2Fsyntax&amp;_wpnonce=3d4e3b2c8a","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=pub%2Fsyntax","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null}},{"id":"premium\/photography","name":"Photographie","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/photography\/screenshot.png?w=434"],"description":"Th&egrave;me WordPress sp&eacute;cialement con&ccedil;u pour les photographes. Inclut des galeries pr&ecirc;tes &agrave; l&#8217;emploi, et deux magnifiques couleurs d&rsquo;apparence.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"2.1.9-wpcom","tags":"art, Photoblogging, photography, Sombre, Clair, Noir, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, artistic, clean, design, elegant, Mise en page fixe, formal, Gris, handcrafted, minimal, portfolio, professional, travel","parent":false,"active":false,"trendingRank":331,"popularityRank":89,"launchDate":"2013-08-21","demoUrl":"https:\/\/photographydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fphotography&amp;_wpnonce=141615168e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fphotography","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/photography&#038;ref=themesphp&#038;_wpnonce=141615168e"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/luscious","name":"Luscious","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/luscious\/screenshot.png?w=434"],"description":"Luscious is super-clean, lip-smacking theme designed for bloggers and publishers who want to frame their work in professional fashion.","author":"StudioPress","authorAndUri":"<a href=\"http:\/\/www.studiopress.com\/\">StudioPress<\/a>","version":"1.0","tags":"Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Images \u00e0 la Une, Deux colonnes, artistic, bright, Marron, colorful, contemporary, craft, Menu personnalis\u00e9, design, Mise en page fixe, Mod\u00e8le pleine largeur, handcrafted, journal, Colonne lat\u00e9rale gauche, modern, Une colonne, Orange, Rose, playful, Violet, Colonne lat\u00e9rale droite, scrapbooking, Article mis en avant, Trois colonnes, vibrant, Blanc","parent":"Genesis","active":false,"trendingRank":315,"popularityRank":150,"launchDate":"2011-11-17","demoUrl":"https:\/\/lusciousdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fluscious&amp;_wpnonce=ed59e1225d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fluscious","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/luscious&#038;ref=themesphp&#038;_wpnonce=ed59e1225d"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>60","purchased":false}},{"id":"premium\/flora-and-fauna","name":"Flora and Fauna","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/flora-and-fauna\/screenshot.png?w=434"],"description":"A playful personal blogging theme designed and illustrated by Aline Yamada","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"art, artwork, blog, cartoon, craft, journal, lifestream, outdoors, scrapbooking, tumblelog, artistic, Clair, bright, colorful, flamboyant, flowery, playful, vibrant, whimsical, Blanc, Bleu, Gris, Orange, Rose, Jaune, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":316,"popularityRank":253,"launchDate":"2013-04-25","demoUrl":"https:\/\/floraandfaunademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fflora-and-fauna&amp;_wpnonce=7e025f92e4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fflora-and-fauna","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/flora-and-fauna&#038;ref=themesphp&#038;_wpnonce=7e025f92e4"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/massive-press","name":"Massive Press","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/massive-press\/screenshot.png?w=434"],"description":"A clean, three-column, responsive grid-based magazine\/news theme great for handling larger amounts of content. With a 100% widgetized home page template, Massive Press allows for great flexibility and content integration. Choose to show one, two, or no sidebars, leaving the content full width. With options to arrange the sidebar order, display images in a slider widget, and more, Massive Press allows for easy customization and unique page layouts.","author":"Press75","authorAndUri":"<a href=\"http:\/\/www.press75.com\/\">Press75<\/a>","version":"3.0.0","tags":"Noir, Blanc, Clair, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, journal, magazine, news, clean, conservative, contemporary, formal, Clair, simple, traditional","parent":false,"active":false,"trendingRank":318,"popularityRank":267,"launchDate":"2013-10-17","demoUrl":"https:\/\/massivepressdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmassive-press&amp;_wpnonce=dccbb3ec46","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmassive-press","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/massive-press&#038;ref=themesphp&#038;_wpnonce=dccbb3ec46"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/react","name":"React","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/react\/screenshot.png?w=434"],"description":"A simple and elegant WordPress theme for business. Features a customizable portfolio page and a responsive layout that looks great on mobile devices.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"1.3.9-wpcom","tags":"Noir, Clair, Blanc, Mise en page fluide, Mise en page adaptable, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Menu personnalis\u00e9, Format d&rsquo;article, Article mis en avant, Mod\u00e8le pleine largeur, art, blog, business, design, photography, portfolio, travel, clean, elegant, handcrafted, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":319,"popularityRank":117,"launchDate":"2011-07-27","demoUrl":"https:\/\/reactdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Freact&amp;_wpnonce=29b68aaf5e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Freact","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/react&#038;ref=themesphp&#038;_wpnonce=29b68aaf5e"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/blog-simple","name":"Blog Simple","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/blog-simple\/screenshot.png?w=434"],"description":"As the name says, Blog Simple is a simple blog-centric theme designed by Mike Kus. Its unique and bold two-tone design sets your blog apart from the crowd. Not only can you choose a theme color from four suggested colors, but also pick any color from a color picker.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Bleu, Vert, Orange, Rouge, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page fixe, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, education, journal, school, tumblelog, minimal, retro, simple, vibrant, Mise en page adaptable, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":320,"popularityRank":158,"launchDate":"2012-06-14","demoUrl":"https:\/\/blogsimpledemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fblog-simple&amp;_wpnonce=0be1412d54","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fblog-simple","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/blog-simple&#038;ref=themesphp&#038;_wpnonce=0be1412d54"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>175","purchased":false}},{"id":"premium\/camera","name":"Appareil photo","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/camera\/screenshot.png?w=434"],"description":"Camera is an elegant, distraction-free canvas for showcasing your photography. Along with large, beautiful Featured Images, you can also create unique photo series in a full-width carousel, which accommodates your landscape and portrait photographs. Camera is perfect for travel blogs, food blogs and photo series.","author":"Array","authorAndUri":"<a href=\"https:\/\/array.is\/\">Array<\/a>","version":"1.1.0","tags":"Clair, Blanc, Deux colonnes, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, photography, clean, minimal, modern, design, art, portfolio, simple, contemporary, D\u00e9filement Infini, site-logo","parent":false,"active":false,"trendingRank":321,"popularityRank":290,"launchDate":"2015-03-05","demoUrl":"https:\/\/camerademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcamera&amp;_wpnonce=cca14785b4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcamera","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/camera&#038;ref=themesphp&#038;_wpnonce=cca14785b4"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"premium\/isca","name":"Isca","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/isca\/screenshot.png?w=434"],"description":"Un th\u00e8me magazine produisant un WordPress \u00e9l\u00e9gant, avec un design adaptatif et la prise en charge des widgets, des vignettes d&rsquo;aper\u00e7u des publications, des en-t\u00eates et arri\u00e8re-plans personnalis\u00e9s.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/prothemedesign.com\">Pro Theme Design<\/a>","version":"1","tags":"Noir, clean, contemporary, professional, Sombre, Bleu, magazine, elegant, modern, tumblelog, sophisticated, Deux colonnes, Colonne lat\u00e9rale droite, En-t\u00eate flexible, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Images \u00e0 la Une, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Couleurs personnalis\u00e9es","parent":false,"active":false,"trendingRank":326,"popularityRank":300,"launchDate":"2013-08-08","demoUrl":"https:\/\/iscademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fisca&amp;_wpnonce=80c58c8ad2","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fisca","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/isca&#038;ref=themesphp&#038;_wpnonce=80c58c8ad2"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>59","purchased":false}},{"id":"premium\/kiore-moana","name":"Kiore Moana","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/kiore-moana\/screenshot.png?w=434"],"description":"Kiore Moana est un th\u00e8me adaptable, tr\u00e8s simple d\u2019utilisation, avec une colonne, de grandes vignettes, une belle typographie aux caract\u00e8res gras, qui prend en charge le format de publication et une option de page d\u2019information minimale de type widget. Le graphisme du th\u00e8me est ax\u00e9 sur la lisibilit\u00e9 et offre de nombreux espaces blancs. Kiore Moana est un th\u00e8me adapt\u00e9 aux blogs personnels, de voyage ou de photographie.","author":"Elmastudio","authorAndUri":"<a href=\"http:\/\/www.elmastudio.de\/en\/themes\/\">Elmastudio<\/a>","version":"1.0.9-wpcom","tags":"Blanc, Clair, Rouge, Une colonne, Mise en page adaptable, Couleurs personnalis\u00e9es, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, Format d&rsquo;article, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, artwork, journal, Photoblogging, travel, tumblelog, clean, minimal, modern, contemporary","parent":false,"active":false,"trendingRank":323,"popularityRank":113,"launchDate":"2013-12-05","demoUrl":"https:\/\/kioremoanademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fkiore-moana&amp;_wpnonce=07b1b8b763","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fkiore-moana","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/kiore-moana&#038;ref=themesphp&#038;_wpnonce=07b1b8b763"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>18","purchased":false}},{"id":"premium\/alto","name":"Alto","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/alto\/screenshot.png?w=434"],"description":"Alto est un th\u00e8me de contenu qui regroupe le meilleur de la publication num\u00e9rique. La lisibilit\u00e9 des caract\u00e8res et la simplicit\u00e9 organisationnelle de ce th\u00e8me offre une exp\u00e9rience passionnante au lecteur tout en garantissant un rendu parfait de votre contenu en toute simplicit\u00e9. Gr\u00e2ce \u00e0 une esth\u00e9tique alliant subtilement tradition et modernit\u00e9, Alto est une trame parfaite pour les blogs, les portefeuilles et les magazines.","author":"Pixel Union","authorAndUri":"<a href=\"http:\/\/pixelunion.net\/\">Pixel Union<\/a>","version":"1.0","tags":"Clair, Blanc, Rouge, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Article mis en avant, Options du th\u00e8me, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Mod\u00e8le pleine largeur, Mise en page fluide, threaded-comments, art, artwork, blog, colorful, craft, design, fashion, journal, magazine, Photoblogging, photography, portfolio, clean, contemporary, elegant, minimal, modern, professional, simple, sophisticated, tech, bright, conservative, formal, industrial, urban","parent":false,"active":false,"trendingRank":324,"popularityRank":320,"launchDate":"2014-04-24","demoUrl":"https:\/\/altodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Falto&amp;_wpnonce=8c8b7f1fb4","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Falto","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/alto&#038;ref=themesphp&#038;_wpnonce=8c8b7f1fb4"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/atrium","name":"Atrium","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/atrium\/screenshot.png?w=434"],"description":"Atrium is a single-channel theme that keeps content cleanly organized with sharp lines and modular sections. Bright and spacious, Atrium\u2019s architectural layout is the perfect framework for any form of content. It&rsquo;s designed for brands and bloggers and you.","author":"Pixel Union","authorAndUri":"<a href=\"http:\/\/pixelunion.net\">Pixel Union<\/a>","version":"1.0","tags":"Blanc, Bleu, Une colonne, Colonne lat\u00e9rale droite, Mise en page adaptable, Images \u00e0 la Une, Article mis en avant, Options du th\u00e8me, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, threaded-comments","parent":false,"active":false,"trendingRank":325,"popularityRank":324,"launchDate":"2014-09-29","demoUrl":"https:\/\/atriumdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fatrium&amp;_wpnonce=099971b529","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fatrium","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/atrium&#038;ref=themesphp&#038;_wpnonce=099971b529"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/designer","name":"Designer","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/designer\/screenshot.png?w=434"],"description":"Promote your latest design work, sketches, audio, photography and more with Designer. Featuring an eclectic, responsive design and a fully-featured blog, you can get a professional portfolio up and running effortlessly, with zero coding required. Designer is easy to customize and ships with several portfolio styles including tiled, landscape, portrait and square.","author":"Array","authorAndUri":"<a href=\"https:\/\/array.is\/\">Array<\/a>","version":"1.1.7","tags":"art, design, photography, portfolio, clean, Clair, minimal, modern, professional, simple, Gris, Clair, Blanc, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Pr\u00eat \u00e0 \u00eatre traduit, site-logo, Options du th\u00e8me, Support des langues RTL","parent":false,"active":false,"trendingRank":326,"popularityRank":338,"launchDate":"2014-09-03","demoUrl":"https:\/\/designerdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fdesigner&amp;_wpnonce=ce7818f5ce","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fdesigner","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/designer&#038;ref=themesphp&#038;_wpnonce=ce7818f5ce"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"premium\/magazine","name":"Magazine","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/magazine\/screenshot.png?w=434"],"description":"Magazine est une th\u00e8me \u00e9l\u00e9gant et moderne pour mettre en valeur votre contenu.","author":"StudioPress","authorAndUri":"<a href=\"http:\/\/www.studiopress.com\/\">StudioPress<\/a>","version":"2.0","tags":"Noir, Bleu, Sombre, Gris, Vert, Orange, Rose, Violet, Rouge, Blanc, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, fashion, magazine, news, clean, contemporary, futuristic, metallic, modern, tech, vibrant","parent":"Genesis","active":false,"trendingRank":327,"popularityRank":106,"launchDate":"2011-09-21","demoUrl":"https:\/\/magazinedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmagazine&amp;_wpnonce=2fc51189eb","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmagazine","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/magazine&#038;ref=themesphp&#038;_wpnonce=2fc51189eb"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/the-parisian","name":"The Parisian","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/the-parisian\/screenshot.png?w=434"],"description":"A minimal theme for personal blogging with a generous image slider, featured header images, and more!","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Marron, Ocre, Orange, Une colonne, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, blog, lifestream, Photoblogging, photography, conservative, formal, minimal, natural, textured","parent":false,"active":false,"trendingRank":330,"popularityRank":355,"launchDate":"2013-10-24","demoUrl":"https:\/\/theparisiandemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fthe-parisian&amp;_wpnonce=8457613930","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fthe-parisian","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/the-parisian&#038;ref=themesphp&#038;_wpnonce=8457613930"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>65","purchased":false}},{"id":"premium\/magnate-express","name":"Magnate Express","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/magnate-express\/screenshot.png?w=434"],"description":"Magnate Express is a blogging \/ photography theme with an adaptive layout focused on your content and with a unique slider to showcase featured images from your posts. Another awesome theme by <a href=\"http:\/\/woothemes.com\/\">WooThemes<\/a>.","author":"WooThemes","authorAndUri":"<a href=\"http:\/\/woothemes.com\/\">WooThemes<\/a>","version":"1.0.4","tags":"Rouge, Blanc, Gris, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, artwork, blog, business, design, journal, Photoblogging, photography, portfolio, tumblelog, video, clean, colorful, elegant, Clair, minimal, modern, professional, retro, simple","parent":false,"active":false,"trendingRank":329,"popularityRank":360,"launchDate":"2013-07-25","demoUrl":"https:\/\/magnateexpressdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmagnate-express&amp;_wpnonce=77b906de1b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmagnate-express","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/magnate-express&#038;ref=themesphp&#038;_wpnonce=77b906de1b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>68","purchased":false}},{"id":"premium\/business-identity","name":"Business Identity","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/business-identity\/screenshot.png?w=434"],"description":"Showcase your business, connect with your customers, and make a strong and professional impact on the web with Business Identity. Featuring custom logo and site layout functionality, a beautiful home page template, and customer testimonials, Business Identity is the right choice for your online brand.","author":"Professional Themes","authorAndUri":"<a href=\"http:\/\/professionalthemes.nyc\/\">Professional Themes<\/a>","version":"3.0.2","tags":"Violet, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Image d&rsquo;en-t\u00eate \u00e0 la Une, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Curseur d'article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, business, clean, conservative, modern, professional","parent":false,"active":false,"trendingRank":330,"popularityRank":97,"launchDate":"2014-07-30","demoUrl":"https:\/\/businessidentitydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbusiness-identity&amp;_wpnonce=bfd714df26","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbusiness-identity","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/business-identity&#038;ref=themesphp&#038;_wpnonce=bfd714df26"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>150","purchased":false}},{"id":"premium\/bailey","name":"Bailey","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/bailey\/screenshot.png?w=434"],"description":"A minimal portfolio theme with designer grid layouts and easy-to-configure projects. Crafted with a responsive layout that looks great on large displays, tablets and mobile devices.","author":"The Theme Foundry","authorAndUri":"<a href=\"https:\/\/thethemefoundry.com\">The Theme Foundry<\/a>","version":"201508080148","tags":"abstract, art, artistic, artwork, Noir, blog, Bleu, bright, business, clean, contemporary, craft, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, design, \u00c9diteur de style, fashion, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Clair, minimal, modern, Une colonne, Photoblogging, photography, portfolio, professional, Mise en page adaptable, scrapbooking, simple, sophisticated, Article mis en avant, Options du th\u00e8me, Trois colonnes, Pr\u00eat \u00e0 \u00eatre traduit, Deux colonnes, video, Blanc","parent":false,"active":false,"trendingRank":331,"popularityRank":362,"launchDate":"2015-03-05","demoUrl":"https:\/\/baileydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbailey&amp;_wpnonce=227dc06c9e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbailey","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/bailey&#038;ref=themesphp&#038;_wpnonce=227dc06c9e"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"premium\/traction","name":"Traction","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/traction\/screenshot.png?w=434"],"description":"A super clean magazine theme featuring built-in post thumbnail support, a featured post slider, and a robust theme options menu.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"2.6.3-wpcom","tags":"blog, business, gaming, magazine, news, professional, clean, elegant, handcrafted, modern, tech, Mise en page fixe, Deux colonnes, Sombre, Noir, Bleu, Rouge, Vert, Colonne lat\u00e9rale droite, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Curseur d'article, Article mis en avant, Couleurs personnalis\u00e9es","parent":false,"active":false,"trendingRank":337,"popularityRank":50,"launchDate":"2011-03-02","demoUrl":"https:\/\/tractiondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Ftraction&amp;_wpnonce=3d471f2f30","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Ftraction","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/traction&#038;ref=themesphp&#038;_wpnonce=3d471f2f30"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>68","purchased":false}},{"id":"premium\/basis","name":"Basis","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/basis\/screenshot.png?w=434"],"description":"A professional business theme with flexible drag and drop layouts and stunning slideshows.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\/\">The Theme Foundry<\/a>","version":"1.0.14-wpcom","tags":"Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, D\u00e9filement Infini, Curseur d'article, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, craft, magazine, news, productivity, clean, conservative, contemporary, elegant, formal, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":336,"popularityRank":140,"launchDate":"2013-11-19","demoUrl":"https:\/\/basisdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbasis&amp;_wpnonce=ed15f44489","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbasis","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/basis&#038;ref=themesphp&#038;_wpnonce=ed15f44489"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/blocco","name":"Blocco","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/blocco\/screenshot.png?w=434"],"description":"A very unique block style theme including a responsive design.","author":"Press75","authorAndUri":"<a href=\"http:\/\/www.press75.com\/\">Press75<\/a>","version":"2.1.0","tags":"blog, photography, portfolio, clean, contemporary, geometric, minimal, modern, simple, Noir, Clair, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":337,"popularityRank":147,"launchDate":"2013-02-21","demoUrl":"https:\/\/bloccodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fblocco&amp;_wpnonce=006b9dc9b3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fblocco","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/blocco&#038;ref=themesphp&#038;_wpnonce=006b9dc9b3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/creative","name":"Creative","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/creative\/screenshot.png?w=434"],"description":"Show off your design skills and style with Creative by UpThemes. Creative lets you express yourself through crisp typography, social media presence, and much more with a self-hiding navigation system that tucks itself away while the user reads and shows up just when you expect it to.","author":"UpThemes","authorAndUri":"<a href=\"https:\/\/upthemes.com\/\">UpThemes<\/a>","version":"1.3","tags":"Blanc, Rose, two-column, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, photography, clean, minimal, modern, design, art, portfolio, simple, contemporary, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":338,"popularityRank":230,"launchDate":"2014-12-05","demoUrl":"https:\/\/creativethemedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcreative&amp;_wpnonce=21c495e0f3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcreative","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/creative&#038;ref=themesphp&#038;_wpnonce=21c495e0f3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/ampersand","name":"Ampersand","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/ampersand\/screenshot.png?w=434"],"description":"Ampersand est un th\u00e8me de style book, qui privil\u00e9gie une typographie attractive et lisible et un redimensionnement \u00e9l\u00e9gant pour la navigation nomade.","author":"Array","authorAndUri":"<a href=\"https:\/\/array.is\">Array<\/a>","version":"2.2.9","tags":"Bleu, Gris, Vert, Clair, Blanc, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, design, photography, portfolio, clean, contemporary, minimal, simple","parent":false,"active":false,"trendingRank":339,"popularityRank":248,"launchDate":"2014-01-29","demoUrl":"https:\/\/ampersanddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fampersand&amp;_wpnonce=b39977a8e7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fampersand","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/ampersand&#038;ref=themesphp&#038;_wpnonce=b39977a8e7"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"premium\/funki","name":"Funki","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/funki\/screenshot.png?w=434"],"description":"Funki is a funky theme with some artsy flare. It has a responsive structure and offers multiple layouts, either one, two, or three columns, based on the widget areas you choose to show. It also comes with many background choices, with different motifs and patterns, and a primary color chooser. It has a featured section for sticky posts, supports custom menus, featured images, custom header, background image, and optional footer widget areas. Funk up your site with Funki now!","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1","tags":"Article mis en avant, Microformats, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, Mod\u00e8le pleine largeur, Format d&rsquo;article, art, blog, cartoon, design, fashion, music, news, tumblelog, artistic, bright, colorful, glamorous, playful, textured, vibrant, whimsical, Bleu, Clair, Blanc, Rouge, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Curseur d'article, Options du th\u00e8me","parent":false,"active":false,"trendingRank":341,"popularityRank":195,"launchDate":"2011-10-06","demoUrl":"https:\/\/funkidemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Ffunki&amp;_wpnonce=2baef223ff","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Ffunki","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/funki&#038;ref=themesphp&#038;_wpnonce=2baef223ff"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"premium\/the-writer","name":"The Writer","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/the-writer\/screenshot.png?w=434"],"description":"A minimal writing theme, built for writers, authors and columnists. Nothing else. Simple.","author":"Obox Themes","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/obox-themes\/\">Obox Themes<\/a>","version":"1.0-wpcom","tags":"Noir, Rouge, Blanc, Clair, Quatre colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Image d&rsquo;en-t\u00eate \u00e0 la Une, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, fashion, journal, colorful, contemporary, elegant, formal, minimal, modern, vibrant","parent":false,"active":false,"trendingRank":343,"popularityRank":223,"launchDate":"2014-03-05","demoUrl":"https:\/\/thewriterdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fthe-writer&amp;_wpnonce=b44b460ffc","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fthe-writer","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/the-writer&#038;ref=themesphp&#038;_wpnonce=b44b460ffc"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>80","purchased":false}},{"id":"premium\/just-desserts","name":"Just Desserts","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/just-desserts\/screenshot.png?w=434"],"description":"Just Desserts is a clean and stylish food-blogging theme designed by Andy Rutledge. Its single-column layout and unique presentation of images and posts on the front page give you a delectable canvas on which your mouthwatering content &#8212; from text to photographs &#8212; can really shine.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1.1-wpcom","tags":"Photoblogging, Marron, Gris, Rouge, Blanc, Clair, Une colonne, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, glamorous, sophisticated, Mise en page adaptable, blog, food, journal, bright, clean, contemporary, elegant, photography, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":344,"popularityRank":208,"launchDate":"2012-05-10","demoUrl":"https:\/\/justdessertsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fjust-desserts&amp;_wpnonce=34910659ed","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fjust-desserts","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/just-desserts&#038;ref=themesphp&#038;_wpnonce=34910659ed"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"premium\/axon","name":"Axon","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/axon\/screenshot.png?w=434"],"description":"Axon is a clean, creative and responsive WordPress blog theme. It has an eye-catching featured posts content area. Axon is powered with boxed or wide layout that can be further customized to left sidebar, right sidebar or without sidebar easily. Other features are custom header, post formats, social links, and footer widgets.","author":"DesignOrbital","authorAndUri":"<a href=\"http:\/\/designorbital.com\/\">DesignOrbital<\/a>","version":"1.0","tags":"Bleu, Gris, Argent, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, D\u00e9filement Infini, art, artwork, news, blog, business, design, journal, Photoblogging, photography, portfolio, travel, tumblelog, clean, elegant, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":345,"popularityRank":289,"launchDate":"2014-02-13","demoUrl":"https:\/\/axondemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Faxon&amp;_wpnonce=5c415cb1c3","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Faxon","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/axon&#038;ref=themesphp&#038;_wpnonce=5c415cb1c3"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/promenade","name":"Promenade","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/promenade\/screenshot.png?w=434"],"description":"Featuring a widgetized home page, Promenade&rsquo;s clean layout and minimalistic design is perfect to capture your audience&rsquo;s attention and allow them to easily navigate your content.","author":"Cedaro","authorAndUri":"<a href=\"http:\/\/www.cedaro.com\/\">Cedaro<\/a>","version":"1.5.4","tags":"Blanc, Clair, Une colonne, Deux colonnes, Trois colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, music, portfolio, video, clean, conservative, contemporary, minimal, modern, professional, simple, traditional, Couleurs personnalis\u00e9es","parent":false,"active":false,"trendingRank":339,"popularityRank":119,"launchDate":"2014-07-24","demoUrl":"https:\/\/promenadedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpromenade&amp;_wpnonce=b1be756ba7","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpromenade","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/promenade&#038;ref=themesphp&#038;_wpnonce=b1be756ba7"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/mina-olen","name":"Mina Olen","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/mina-olen\/screenshot.png?w=434"],"description":"Mina olen is made for cool business type of sites. You can showcase your most important pages, latest posts, random portfolios and testimonials on front page template. You can also upload your logo, set global layout and enter footer text in theme customizer. And in the same time blogging features looks great too.","author":"Foxnet","authorAndUri":"<a href=\"https:\/\/foxland.fi\">Foxnet<\/a>","version":"1.1.1","tags":"Rouge, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Format d&rsquo;article, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, news, portfolio, clean, elegant, Clair, minimal, modern, professional, tech","parent":false,"active":false,"trendingRank":347,"popularityRank":317,"launchDate":"2014-03-13","demoUrl":"https:\/\/minaolendemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fmina-olen&amp;_wpnonce=500276110c","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fmina-olen","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/mina-olen&#038;ref=themesphp&#038;_wpnonce=500276110c"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/wire","name":"Wire","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/wire\/screenshot.png?w=434"],"description":"A customizable, responsive, personal blog theme for the creative in you","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Orange, Gris, Blanc, Clair, Une colonne, Mise en page fluide, Mise en page adaptable, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, blog, business, journal, music, news, Photoblogging, photography, video, bright, clean, modern","parent":false,"active":false,"trendingRank":348,"popularityRank":313,"launchDate":"2013-06-20","demoUrl":"https:\/\/wiredemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fwire&amp;_wpnonce=7dba5277fd","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fwire","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/wire&#038;ref=themesphp&#038;_wpnonce=7dba5277fd"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/creative-portfolio","name":"Creative Portfolio","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/creative-portfolio\/screenshot.png?w=434"],"description":"Show off your professional portfolio and make an immediate and incredible impact with a featured content home page slider, featured home page video, client testimonials, and brilliant calls to action. Flexible, robust, and simple to use, Creative Portfolio is the right choice for showcasing your creativity.","author":"Professional Themes","authorAndUri":"<a href=\"http:\/\/professionalthemes.nyc\/\">Professional Themes<\/a>","version":"1.3.1","tags":"Noir, Bleu, Gris, Blanc, Une colonne, Deux colonnes, Trois colonnes, Quatre colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Microformats, Format d&rsquo;article, Curseur d'article, Support des langues RTL, site-logo, Article mis en avant, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, business, design, Photoblogging, photography, portfolio, video, clean, Clair, minimal, modern, professional, sophisticated","parent":false,"active":false,"trendingRank":347,"popularityRank":221,"launchDate":"2015-01-30","demoUrl":"https:\/\/creativeportfoliodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fcreative-portfolio&amp;_wpnonce=754a8368b1","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fcreative-portfolio","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/creative-portfolio&#038;ref=themesphp&#038;_wpnonce=754a8368b1"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>175","purchased":false}},{"id":"premium\/notebook","name":"Notebook","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/notebook\/screenshot.png?w=434"],"description":"Notebook is a clean and modern one-column theme ideal for bloggers of any field. Notebook makes your site&rsquo;s content look amazing with a balanced typography, colors and the attention to details.","author":"Tasko","authorAndUri":"<a href=\"http:\/\/tdwp.us\/\">Tasko<\/a>","version":"1.0","tags":"Noir, Blanc, Clair, Une colonne, Mise en page adaptable, site-logo, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, design, journal, photography, Photoblogging, minimal, modern, professional, simple, art, artwork, blog, D\u00e9filement Infini","parent":false,"active":false,"trendingRank":350,"popularityRank":340,"launchDate":"2014-09-29","demoUrl":"https:\/\/notebookdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fnotebook&amp;_wpnonce=3fe29eebba","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fnotebook","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/notebook&#038;ref=themesphp&#038;_wpnonce=3fe29eebba"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>39","purchased":false}},{"id":"premium\/bromley","name":"Bromley","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/bromley\/screenshot.png?w=434"],"description":"The best elements of blogging themes manipulated into something beautifully simple. Ideal for local community, fan magazines, and talking about updates in your industry.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.1","tags":"Rouge, Blanc, Gris, Une colonne, Deux colonnes, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, gaming, journal, lifestream, magazine, news, bright, clean, conservative, contemporary, elegant, formal, geometric, Clair, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":350,"popularityRank":217,"launchDate":"2013-11-14","demoUrl":"https:\/\/bromleydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbromley&amp;_wpnonce=5917e3d003","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbromley","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/bromley&#038;ref=themesphp&#038;_wpnonce=5917e3d003"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/eight","name":"Eight","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/eight\/screenshot.png?w=434"],"description":"Featuring a design by renowned web designer <a href=\"http:\/\/elliotjaystocks.com\/\">Elliot Jay Stocks<\/a>, Eight will transform the look of your blog. Even better, Eight&rsquo;s custom highlight color feature, custom background, and custom header, let you transform it right back and easily create your own blog design.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"art, blog, craft, artistic, faded, grungy, handcrafted, textured, Noir, Gris, Rouge, Ocre, Blanc, Deux colonnes, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Microformats, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":352,"popularityRank":319,"launchDate":"2011-09-29","demoUrl":"https:\/\/eightdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Feight&amp;_wpnonce=778aee9c33","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Feight","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/eight&#038;ref=themesphp&#038;_wpnonce=778aee9c33"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/oxford","name":"Oxford","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/oxford\/screenshot.png?w=434"],"description":"Un th\u00e8me multi-colonnes au format magazine avec les polices Typekit.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\">The Theme Foundry<\/a>","version":"1.1.3","tags":"Blanc, Clair, Une colonne, Deux colonnes, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Mod\u00e8le pleine largeur, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, blog, news, travel, artistic, elegant, formal, geometric, minimal, modern, Noir, Deux colonnes, Couleurs personnalis\u00e9es, journal, magazine, Photoblogging, simple, traditional, sophisticated, contemporary, Image d&rsquo;en-t\u00eate \u00e0 la Une, professional, D\u00e9filement Infini, En-t\u00eate flexible, Mise en page fluide","parent":false,"active":false,"trendingRank":356,"popularityRank":240,"launchDate":"2014-07-31","demoUrl":"https:\/\/oxforddemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Foxford&amp;_wpnonce=81cd4b657d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Foxford","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/oxford&#038;ref=themesphp&#038;_wpnonce=81cd4b657d"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"premium\/blogly","name":"Blogly","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/blogly\/screenshot.png?w=434"],"description":"Blogly is a clean, flat design theme for personal bloggers.","author":"ThemeFurnace","authorAndUri":"<a href=\"http:\/\/themefurnace.com\">ThemeFurnace<\/a>","version":"1.0.1","tags":"Gris, Rouge, Deux colonnes, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Format d&rsquo;article, blog, journal, lifestream, Photoblogging, tumblelog, clean, contemporary, minimal, modern, Sombre, Colonne lat\u00e9rale gauche, Images \u00e0 la Une, site-logo, Options du th\u00e8me, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, Mise en page adaptable","parent":false,"active":false,"trendingRank":353,"popularityRank":357,"launchDate":"2014-11-13","demoUrl":"https:\/\/bloglydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fblogly&amp;_wpnonce=678cf7771b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fblogly","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/blogly&#038;ref=themesphp&#038;_wpnonce=678cf7771b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>49","purchased":false}},{"id":"premium\/kent","name":"Kent","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/kent\/screenshot.png?w=434"],"description":"Kent is a clean WordPress theme designed for writers who want to focus on writing content. It&rsquo;s the perfect theme for people who want to tell stories. Kent includes custom header, social links, and footer widget options to allow you to lay out your site exactly as you wish.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.2","tags":"Blanc, Clair, Bleu, Une colonne, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, journal, news, clean, bright, minimal, modern, professional, simple","parent":false,"active":false,"trendingRank":355,"popularityRank":310,"launchDate":"2013-11-07","demoUrl":"https:\/\/kentdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fkent&amp;_wpnonce=794dda6a3e","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fkent","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/kent&#038;ref=themesphp&#038;_wpnonce=794dda6a3e"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/chalk","name":"Chalk","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/chalk\/screenshot.png?w=434"],"description":"An innovative WordPress theme for the twenty-first century teacher. Specially crafted to bring the classroom environment online, the theme includes some exciting features: to-do lists, class conversations, podcasts and video lectures.","author":"The Theme Foundry","authorAndUri":"<a href=\"http:\/\/thethemefoundry.com\">The Theme Foundry<\/a>","version":"1.2.9-wpcom","tags":"Mise en page adaptable, education, Format d&rsquo;article, blog, lifestream, bright, clean, elegant, handcrafted, Clair, Clair, Orange, Blanc, Jaune, Colonne lat\u00e9rale gauche, Deux colonnes, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Menu personnalis\u00e9, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me","parent":false,"active":false,"trendingRank":356,"popularityRank":348,"launchDate":"2012-03-22","demoUrl":"https:\/\/chalkdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fchalk&amp;_wpnonce=1058e2c07b","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fchalk","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/chalk&#038;ref=themesphp&#038;_wpnonce=1058e2c07b"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>79","purchased":false}},{"id":"premium\/poly","name":"Poly","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/poly\/screenshot.png?w=434"],"description":"A colorful theme with a dynamic grid layout","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0","tags":"Clair, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, design, Photoblogging, bright, clean, colorful, elegant, geometric, modern","parent":false,"active":false,"trendingRank":357,"popularityRank":318,"launchDate":"2014-01-16","demoUrl":"https:\/\/polydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fpoly&amp;_wpnonce=80e79f6742","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fpoly","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/poly&#038;ref=themesphp&#038;_wpnonce=80e79f6742"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"premium\/simfo","name":"Simfo","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/simfo\/screenshot.png?w=434"],"description":"Simfo est un th\u00e8me soign\u00e9 et minimaliste, id\u00e9al pour les photographes.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1-wpcom","tags":"art, design, fashion, portfolio, clean, Clair, minimal, simple, Blanc, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Curseur d'article, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":358,"popularityRank":200,"launchDate":"2012-11-29","demoUrl":"https:\/\/simfodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fsimfo&amp;_wpnonce=b9e8d9a760","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fsimfo","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/simfo&#038;ref=themesphp&#038;_wpnonce=b9e8d9a760"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"premium\/awesome","name":"Awesome","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/awesome\/screenshot.png?w=434"],"description":"Un th&egrave;me extra-large et ultra-distingu&eacute;, id&eacute;al pour exposer vos photos, galeries, et vid&eacute;os!","author":"Graph Paper Press","authorAndUri":"<a href=\"http:\/\/graphpaperpress.com\">Graph Paper Press<\/a>","version":"1.0.4","tags":"Noir, Blanc, Rose, Sombre, Clair, Une colonne, Mise en page fluide, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, design, fashion, food, journal, music, Photoblogging, photography, portfolio, tumblelog, video, wedding, bright, clean, colorful, elegant, formal, futuristic, minimal, modern, professional, simple, vibrant","parent":false,"active":false,"trendingRank":359,"popularityRank":262,"launchDate":"2013-11-19","demoUrl":"https:\/\/awesomedemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fawesome&amp;_wpnonce=c7b78107be","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fawesome","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/awesome&#038;ref=themesphp&#038;_wpnonce=c7b78107be"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/bon-vivant","name":"Bon Vivant","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/bon-vivant\/screenshot.png?w=434"],"description":"Un th\u00e8me \u00e9clectique pour les blogueurs culinaires et les restaurants.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0.1-wpcom","tags":"food, journal, business, craft, art, artistic, Sombre, earthy, elegant, flamboyant, hand-drawn, playful, retro, whimsical, Marron, Rouge, Blanc, Deux colonnes, Colonne lat\u00e9rale gauche, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, site-logo, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit","parent":false,"active":false,"trendingRank":361,"popularityRank":257,"launchDate":"2013-04-18","demoUrl":"https:\/\/bonvivantdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbon-vivant&amp;_wpnonce=a9144fff02","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbon-vivant","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/bon-vivant&#038;ref=themesphp&#038;_wpnonce=a9144fff02"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/bexley","name":"Bexley","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/bexley\/screenshot.png?w=434"],"description":"Bexley is a photo blog &#8211; placing the photos at the forefront and giving you plenty of space to add your own writing around them.","author":"Pro Theme Design","authorAndUri":"<a href=\"http:\/\/theme.wordpress.com\/themes\/by\/pro-theme-design\/\">Pro Theme Design<\/a>","version":"1.1","tags":"Noir, Gris, Blanc, Vert, Deux colonnes, Mise en page adaptable, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Support des langues RTL, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, craft, design, fashion, Vacances, Photoblogging, photography, clean, conservative, contemporary, Clair, minimal, modern, professional, simple, sophisticated","parent":false,"active":false,"trendingRank":362,"popularityRank":347,"launchDate":"2013-11-20","demoUrl":"https:\/\/bexleydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fbexley&amp;_wpnonce=510f8e2648","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fbexley","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/bexley&#038;ref=themesphp&#038;_wpnonce=510f8e2648"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/delight","name":"Delight","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/delight\/screenshot.png?w=434"],"description":"A responsive, mobile friendly theme with the ability to add contact details and links to your social network profiles in the header. Other design customizations include the choice between a left- or right-sidebar, and the ability to display custom menus in both the header and the footer.","author":"CyberChimps Inc","authorAndUri":"<a href=\"http:\/\/cyberchimps.com\/\">CyberChimps Inc<\/a>","version":"1.0-wpcom","tags":"Gris, Blanc, Bleu, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, D\u00e9filement Infini, Support des langues RTL, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, blog, business, design, artistic, clean, modern","parent":false,"active":false,"trendingRank":363,"popularityRank":243,"launchDate":"2013-11-19","demoUrl":"https:\/\/delightdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fdelight&amp;_wpnonce=7f236e6d62","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fdelight","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/delight&#038;ref=themesphp&#038;_wpnonce=7f236e6d62"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>40","purchased":false}},{"id":"premium\/ladder","name":"Ladder","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/ladder\/screenshot.png?w=434"],"description":"Ladder is a visually striking theme with a modern, flat design that ensures you present yourself and your company professionally. With Ladder, you can showcase your work and identity in a unique way.","author":"Viva Themes","authorAndUri":"<a href=\"http:\/\/www.vivathemes.com\">Viva Themes<\/a>","version":"1.0.2","tags":"Sombre, Vert, Rouge, Une colonne, Mise en page fluide, Options du th\u00e8me, Curseur d'article, design, business, photography, modern, elegant, minimal, simple, clean, Mise en page adaptable, Menu personnalis\u00e9, Images \u00e0 la Une, art, craft, portfolio, travel, artistic, Blanc, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, \u00c9diteur de style, Pr\u00eat \u00e0 \u00eatre traduit, sophisticated, D\u00e9filement Infini, site-logo","parent":false,"active":false,"trendingRank":364,"popularityRank":354,"launchDate":"2014-07-25","demoUrl":"https:\/\/ladderdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fladder&amp;_wpnonce=1a9bda2fae","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fladder","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/ladder&#038;ref=themesphp&#038;_wpnonce=1a9bda2fae"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>69","purchased":false}},{"id":"premium\/antenna","name":"Antenna","screenshot":["https:\/\/i2.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/antenna\/screenshot.png?w=434"],"description":"Antenna est un magnifique th\u00e8me pour magazine qui plaira \u00e0 toute personne n\u00e9cessitant un site Web attrayant et rapide. Antenna se caract\u00e9rise par un design clair et moderne et prend en charge les dispositions multi-cadres et pleine largeur. Ce th\u00e8me est en outre facile \u00e0 configurer \u00e0 l&rsquo;aide du personnalisateur de th\u00e8me.","author":"DesignOrbital","authorAndUri":"<a href=\"http:\/\/designorbital.com\/\">DesignOrbital<\/a>","version":"1.0","tags":"Noir, Bleu, Blanc, Clair, Une colonne, Deux colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, En-t\u00eate flexible, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Curseur d'article, Options du th\u00e8me, Microformats, Support des langues RTL, Article mis en avant, threaded-comments, Pr\u00eat \u00e0 \u00eatre traduit, art, artwork, blog, business, design, fashion, magazine, news, Photoblogging, photography, sports, bright, clean, elegant, modern, professional, sophisticated, music, portfolio, contemporary, travel, journal, tumblelog","parent":false,"active":false,"trendingRank":365,"popularityRank":212,"launchDate":"2014-06-06","demoUrl":"https:\/\/antennademo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fantenna&amp;_wpnonce=34b5691b5f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fantenna","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/antenna&#038;ref=themesphp&#038;_wpnonce=34b5691b5f"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/inspiration-laboratory","name":"Inspiration Laboratory","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/inspiration-laboratory\/screenshot.png?w=434"],"description":"A playful, colorful personal blogging theme with exclusive artwork by Dima Je","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"Noir, Blanc, Jaune, Clair, Trois colonnes, Colonne lat\u00e9rale gauche, Colonne lat\u00e9rale droite, Mise en page fixe, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Images \u00e0 la Une, Mod\u00e8le pleine largeur, D\u00e9filement Infini, Format d&rsquo;article, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, artwork, blog, cartoon, craft, design, journal, lifestream, tumblelog, artistic, bright, colorful, funny, hand-drawn, humorous, playful, retro, whimsical","parent":false,"active":false,"trendingRank":366,"popularityRank":296,"launchDate":"2013-07-18","demoUrl":"https:\/\/inspirationlaboratorydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Finspiration-laboratory&amp;_wpnonce=d8aad2b91f","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Finspiration-laboratory","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/inspiration-laboratory&#038;ref=themesphp&#038;_wpnonce=d8aad2b91f"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/espresso","name":"Espresso","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/espresso\/screenshot.png?w=434"],"description":"A sophisticated, responsive portfolio theme designed by Justin Caroll, perfect for showcasing your work. With a convenient slide-out sidebar, bold featured images, and quick access to your favorite social networks, Espresso will make your portfolio stand out from the rest.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.0-wpcom","tags":"business, blog, journal, photography, portfolio, clean, modern, Marron, Vert, Une colonne, Deux colonnes, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Couleurs personnalis\u00e9es, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, Support des langues RTL, Pr\u00eat \u00e0 \u00eatre traduit, sophisticated, contemporary, Images \u00e0 la Une, Format d&rsquo;article, D\u00e9filement Infini, En-t\u00eate flexible, Mise en page adaptable, threaded-comments","parent":false,"active":false,"trendingRank":367,"popularityRank":353,"launchDate":"2014-07-24","demoUrl":"https:\/\/espressodemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fespresso&amp;_wpnonce=3298d7c1ef","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fespresso","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/espresso&#038;ref=themesphp&#038;_wpnonce=3298d7c1ef"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>125","purchased":false}},{"id":"premium\/clear-news","name":"Clear News","screenshot":["https:\/\/i1.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/clear-news\/screenshot.png?w=434"],"description":"Clear News was designed to get out of the way and provide a medium for your users to easily access your content on any device.","author":"Press75","authorAndUri":"<a href=\"http:\/\/www.press75.com\/\">Press75<\/a>","version":"1.3.0","tags":"Clair, Blanc, Une colonne, Deux colonnes, Trois colonnes, Mise en page adaptable, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, \u00c9diteur de style, Images \u00e0 la Une, Image d&rsquo;en-t\u00eate \u00e0 la Une, Format d&rsquo;article, Article mis en avant, Options du th\u00e8me, Pr\u00eat \u00e0 \u00eatre traduit, Clair, simple, Couleurs personnalis\u00e9es, journal, D\u00e9filement Infini, En-t\u00eate flexible","parent":false,"active":false,"trendingRank":368,"popularityRank":283,"launchDate":"2014-07-01","demoUrl":"https:\/\/clearnewsdemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Fclear-news&amp;_wpnonce=21c0639059","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Fclear-news","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/clear-news&#038;ref=themesphp&#038;_wpnonce=21c0639059"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}},{"id":"premium\/everyday","name":"Everyday","screenshot":["https:\/\/i0.wp.com\/s0.wp.com\/wp-content\/themes\/premium\/everyday\/screenshot.png?w=434"],"description":"Precisely calibrated to be pleasurably readable on almost any screen. Attention and care has especially been given to providing a robust and versatile layout to suit your writing needs. From short quips to lengthier bits of prose, Everyday will rise to the challenge and shine with every post you publish.","author":"Automattic","authorAndUri":"<a href=\"https:\/\/wordpress.com\/themes\/\">Automattic<\/a>","version":"1.1-wpcom","tags":"Clair, Gris, Rouge, Deux colonnes, Colonne lat\u00e9rale droite, Arri\u00e8re-plan personnalis\u00e9, Personnalisation de l&rsquo;en-t\u00eate, Menu personnalis\u00e9, En-t\u00eate flexible, Microformats, Format d&rsquo;article, Support des langues RTL, Article mis en avant, Pr\u00eat \u00e0 \u00eatre traduit, blog, design, journal, lifestream, clean, contemporary, elegant, minimal, modern, D\u00e9filement Infini, Mise en page adaptable","parent":false,"active":false,"trendingRank":369,"popularityRank":359,"launchDate":"2012-04-26","demoUrl":"https:\/\/everydaydemo.wordpress.com\/","actions":{"activate":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=activate&amp;stylesheet=premium%2Feveryday&amp;_wpnonce=c75788528d","customize":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php?theme=premium%2Feveryday","preview":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php","delete":null,"purchase":"https:\/\/juniorp15.wordpress.com\/wp-admin\/themes.php?action=confirmpremiumtheme&#038;stylesheet=premium\/everyday&#038;ref=themesphp&#038;_wpnonce=c75788528d"},"premium":{"price":"<abbr title=\"Dollars US\">$<\/abbr>75","purchased":false}}],"settings":{"canInstall":false,"installURI":null,"confirmDelete":"Are you sure you want to delete this theme?\n\nClick 'Cancel' to go back, 'OK' to confirm the delete.","adminUrl":"\/wp-admin\/"},"l10n":{"addNew":"Add New Theme","search":"Chercher parmi les th\u00e8mes install\u00e9s","searchPlaceholder":"Recherche parmi les th\u00e8mes...","themesFound":"Nombre de th\u00e8mes trouv\u00e9s&nbsp;: %d","noThemesFound":"Aucun th\u00e8me trouv\u00e9. Essayez une autre recherche."}};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var _wpCustomizeLoaderSettings = {"url":"https:\/\/juniorp15.wordpress.com\/wp-admin\/customize.php","isCrossDomain":false,"browser":{"mobile":false,"ios":false},"l10n":{"saveAlert":"Les modifications que vous avez faites seront perdues si vous changez de page."}};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var heartbeatSettings = {"nonce":"251b1429e2"};
var heartbeatSettings = {"nonce":"251b1429e2"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var authcheckL10n = {"beforeunload":"Votre session a expir\u00e9. Vous pouvez vous reconnecter depuis cette page ou aller \u00e0 la page de connexion.","interval":"180"};
var authcheckL10n = {"beforeunload":"Votre session a expir\u00e9. Vous pouvez vous reconnecter depuis cette page ou aller \u00e0 la page de connexion.","interval":"180"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var wpNotesArgs = {"cacheBuster":"20150825","iframeUrl":"https:\/\/widgets.wp.com\/notifications\/","iframeAppend":"2","iframeScroll":"no","wide":"1"};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var wpcom_olark = {"identity":"3146-815-10-9343","system":{"group":"66d798c4dd78f8b487b69f361ea6d507"},"box":{"start_hidden":false,"expand":true,"inline":true},"api":{"visitor":{"customFields":{"wpcom_id":93895094,"wpcom_olark_api_id":1,"from_page":"themes","site_url":"https:\/\/juniorp15.wordpress.com\/"}},"chat":{"visitorNickname":{"snippet":"doston15 | New User"}}},"nonce":"afcbbae3f4","message_nonce":"d455561599","campaignArgs":{"campaign":"newuser","fromPage":"themes","user_type":"New User","welcome_message":"Start typing your question...","show_offline":0,"eligible":false,"ping_tracks":true},"user_hid_chat":"0","notifications":{"visitor":{"onOperatorsAway":["Oups, nos op\u00e9rateurs sont absents pour quelques instants. Si vous n'avez pas de nos nouvelles rapidement, veuillez r\u00e9essayer plus tard. Merci\u00a0!"],"onOperatorAvailable":["Nous revoici. Si vous n'avez pas rapidement de nouvelles de notre part, veuillez reposer votre question encore une fois. Merci\u00a0!"]},"operator":{"onBeginConversation":["Site : https:\/\/juniorp15.wordpress.com\/","Admin du R&eacute;seau: https:\/\/wordpress.com\/wp-admin\/network\/users.php?submit=Search+Users&s=doston15","Upgrades and Transactions : https:\/\/wordpress.com\/wp-admin\/network\/wpcom-paid-upgrades.php?action=search&username=doston15"],"onOperatorAvailable":[]}}};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var _WPcomTHX = {"sorts":{"trending":{"slug":"trending","field":"trendingRank","order":"ASC"},"popular":{"slug":"popular","field":"popularityRank","order":"ASC"},"newest":{"slug":"newest","field":"launchDate","order":"DESC"}}};
/* ]]> */
</script>
<script type='text/javascript'>
/* <![CDATA[ */
var WpcomTrackAdminHelpL10n = {"nonce":"fe5bc6e4a3"};
/* ]]> */
</script>
<script type='text/javascript' src='https://s0.wp.com/_static/??-eJyNUttygyAQ/aESxzTTaR86fe5nIG4F5TawGNuv7xpNykyU5gXBc1l2OdXZM2WFTi3Eqo8Vb42yrOHhQN9DH58qIghnESzOeAujEuCnK5RrpRshfF6oufpiOePCGeNsDuVqlEoMjZtumy1Ssi2EKFyAPZuGz2K7i9MxodIF+AEHXtffmy2iBLMrFCmiM+oHqER8gKUdp24368SxY54rmnXYfAngARvgWOohoWRCghi2ntok5nXqlM0iQTg9IfuLyH08DF2ek2nBzjqEdWVLIth4/Jd/K1omO83DsKzUr0LFsXSXnE7wl+pSuOMvpa8SA63iDCavKYSBUbsYCxVQTuvYaFd2XmmB4rfOWIL2O7/J6sO816dT/fz2ejy+9L+xxGVg'></script>
		<script type="text/javascript">
		  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
		  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
		  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
		  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
			
				  ga( 'create', 'UA-10673494-16', 'auto', { 'userId': 'u-93895094' } );
		  ga( 'send', 'pageview' );
				
		</script>
			<script type="text/javascript">
	//<![CDATA[
		jQuery(function($) {
			var record_stat = function(stat_name) {
				var i = new Image(1,1);
				var p = document.location.protocol || 'http:';
				i.src = p + '//pixel.wp.com/g.gif?v=wpcom-no-pv&x_welcome-screen='+stat_name+'&baba='+Math.random();
			};
			var $link_to_welcome = $('a#are-you-new');
			var $welcome = $('#welcome');
			var classes_of_links = ['learn', 'support', 'resource-settings', 'resource-profile', 'resource-themes', 'resource-upgrades', 'elsewhere-tv', 'elsewhere-support', 'elsewhere-learn', 'hide-remind', 'hide-forever'];
			for(var i=0; i<classes_of_links.length; ++i) {
				var link_class = classes_of_links[i];
				$('a.'+link_class, $welcome).bind('click', {link_class: link_class}, function(e) { record_stat(e.data.link_class); return true;});
			}
			var resize_vid = function() {
				var $welcome_video = $('#welcome-video', $welcome);
				var new_video_width = $welcome_video.width() - 30;
				// assume the video is 16:9, because in FF we can't reliably get the height of the object tag
				var new_video_height = (new_video_width * 9) / 16;
				var new_dimensions = {width: new_video_width, height: new_video_height};
				$('.video-player', $welcome_video).add($('object', $welcome_video)).add('img', $welcome_video).attr(new_dimensions).css(new_dimensions);
			}
			resize_vid();
			$link_to_welcome.click(function(e) {
				if ( $welcome.is(':visible') ) {
					$welcome.hide();
				} else {
					$welcome.show();
					resize_vid();
				}
				record_stat('click');
				return false;
			});
			$('div.hide-links a', $welcome).click(function() {
				$welcome.slideUp();
				var self = $(this);
				var $href = self.attr('href');
				if ( $href != '#' ) {
					$.get($href + '&ajax' );
				}
				return false;
			});
		});
	//]]>
	</script>

<div class="clear"></div></div><!-- wpwrap -->
<script type="text/javascript">if(typeof wpOnload=='function')wpOnload();</script>
</body>
</html>

