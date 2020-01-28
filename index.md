<!DOCTYPE html>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width">
<title>Coronavirus Tracker Visualizations</title>
<meta charset="utf-8">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="HandheldFriendly" content="True">
<meta name="MobileOptimized" content="320">
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="default" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

<meta http-equiv="imagetoolbar" content="no">
<link type="text/css" rel="stylesheet" href="//lib.analitik.my/font/league-spartan-master/Variable/league-spartan.css"/>
<link type="text/css" rel="stylesheet" href="//lib.analitik.my/font/awesome/5.8.0/css/all.min.css"/>
<link type="text/css" rel="stylesheet" href="//lib.analitik.my/bootstrap/4.3.1/css/bootstrap.min.css"/>
<link type="text/css" rel="stylesheet" href="//lib.analitik.my/leaflet/0.7.2/leaflet.css"/>
<link type="text/css" rel="stylesheet" href="//lib.analitik.my/alertify/0.3.11/alertify.css"/>
<link type="text/css" rel="stylesheet" href="//lib.analitik.my/purecookie/PureCookie-master/english - english/purecookie.css"/>
<script type="text/javascript" src="//lib.analitik.my/jquery/jquery-3.3.1.slim.min.js"></script>
<script type="text/javascript" src="//lib.analitik.my/bootstrap/4.3.1/js/bootstrap.bundle.min.js"></script>

<script type="text/javascript" src="//lib.analitik.my/d3/5.15.0/d3.min.js"></script>
<!--
<script type="text/javascript" src="//lib.analitik.my/d3/5.9.7/d3.min.js"></script>
-->
<script type="text/javascript" src="//lib.analitik.my/d3-array/2.2.0/d3-array.v2.min.js"></script>
<script type="text/javascript" src="//lib.analitik.my/d3/4.12.0/d3-selection-multi.v1.min.js"></script>
<script type="text/javascript" src="//lib.analitik.my/d3/plugins/d3.comparator.js"></script>
<script type="text/javascript" src="//lib.analitik.my/chroma/0.6.3/chroma.min.js"></script>
<script type="text/javascript" src="//lib.analitik.my/URI/1.14.1/src/URI.min.js"></script>
<script type="text/javascript" src="//lib.analitik.my/moment/2.22.1/moment-with-locales.min.js"></script>

<script type="text/javascript" src="//lib.analitik.my/turf/5.1.6/turf.min.js"></script>
<script type="text/javascript" src="//lib.analitik.my/topojson/1.6.19/topojson.js"></script>
<script type="text/javascript" src="//lib.analitik.my/leaflet/1.5.1/leaflet.js"></script>
<script type="text/javascript" src="//lib.analitik.my/leaflet-providers/1.6.0/leaflet-providers.js"></script>

<script type="text/javascript" src="//lib.analitik.my/alertify/0.3.11/alertify.js"></script>
<script type="text/javascript" src="//lib.analitik.my/pym/1.3.2/pym.v1.min.js"></script>
<script type="text/javascript" src="//lib.analitik.my/purecookie/PureCookie-master/english - english/purecookie.js"></script>
<script type="text/javascript" src="//lib.analitik.my/requirejs/2.1.15/require.js"></script>
<script type="text/javascript" src="//lib.analitik.my/params.js"></script>

<style>
  body {
		font-family: 'League Spartan Variable', 'Helvetica Neue', 'Helvetica', sans-serif;
		font-variation-settings: "wght" 345;
		background:#fff;
		color:#000;
  }

  .leaflet-control-attribution.leaflet-control {
  	background:#333;
  	color:#ccc;
  }

	.cookieConsentContainer {
		z-index: 9999;
	}

</style>

<body>
<script>
new pym.Child({ polling: 300 });
var _v='map/1', _a='app', _t=parseInt(Math.random()*1e6),s=document.getElementsByTagName('script')[0],
uri=URI(_v+'/'+_a+'.js').addQuery('_t',_t),po=document.createElement('script');
po.type='text/javascript'; po.async=false; po.src=uri.toString();
s.parentNode.insertBefore(po, s);
</script>

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-156983001-1"></script>
<script>
if (!document.location.host.match(/diablo/i))	{
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'UA-156983001-1');
}
</script>
