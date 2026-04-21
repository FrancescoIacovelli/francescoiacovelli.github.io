---
title: "Not too close! Evaluating the impact of the baseline on the localization of binary black holes by next-generation gravitational-wave detectors"
collection: publications
permalink: /publications/publication29
excerpt: "We study the impact of the baseline on the localization of BBHs observed by Cosmic Explorer."
date: 2026-04-13
venue: "Phys. Rev. D"
authorlist: "**F. Iacovelli**, L- Reali, E. Berti, A. Corsi, B.S. Sathyaprakash, D. Wadekar"
classes: wide
pubtype: "arXiv"
---

<html>
<head>
   <script src="https://code.jquery.com/jquery-3.7.0.js"></script>
</head>
<body>

<div id="inspirecount"></div>
<script>
var recid = '3144773';
var recurl = 'https://inspirehep.net/api/literature/?q=recid%3A'+recid+'&size=10&page=1&fields=citation_count&format=json';

if (recid === "undefined") {
	document.getElementById("inspirecount").innerHTML='';
} else {
	$.getJSON(recurl, function(data){
		if (data.hits.hits[0].metadata.citation_count === 0){
			var html = '';
		} else {
    	var html =`<a href="https://inspirehep.net/literature/${recid}" target="_blank" rel="noopener"><button type="button inspire" class="btn btn-inspire">iNSPIRE </button></a><span class="badge inspcitations">${data.hits.hits[0].metadata.citation_count} citations</span>`  
    	}  
    	document.getElementById("inspirecount").innerHTML= html
  });
}
</script>
</body>
</html>

### Summary
We study how the localization of BBHs observed by CE in a 2L configuration depends on the baseline between instruments. We find that baselines even shorter than that of the two LIGOs offer a good compromise and, crucially, that adding a third detector to the network eliminates localization multimodality. 

### Abstract
Next-generation (XG) gravitational-wave detectors, such as Cosmic Explorer (CE) and the Einstein Telescope (ET), will observe compact binary coalescences at unprecedented rates and signal-to-noise ratios (SNRs). Accurate sky localization of these sources is crucial for several aspects of the science case of CE and ET. The localization of most binary black hole (BBH) signals, which will spend at most a few minutes within the XG detector's effective sensitivity band, will continue to rely primarily on timing triangulation across a network of detectors. A key design choice for triangulation is the baseline between instruments. We investigate how the baseline affects the localization capabilities of a two-detector CE network, analyzing both fixed-parameter injections and a realistic BBH population consistent with the latest GWTC-4 results. For detector-frame total masses up to &sim;100 M<sub>&odot;</sub>, we find that baselines corresponding to light travel times of 8&ndash;11 ms (&sim;2300&ndash;3300 km) offer a reasonable compromise, producing predominantly unimodal or bimodal sky localizations suitable for electromagnetic follow-up and statistical host galaxy identification and galaxy cross-correlation studies. Shorter baselines significantly degrade localization, particularly for high SNR events. Crucially, we find that adding a third detector to the network eliminates localization multimodality for a substantial fraction of sources. A network with two CEs and LIGO-India provides unimodal posteriors for a good fraction of events, whereas two CEs plus ET would provide unimodal posteriors for essentially all of them. These considerations should be useful to inform the development of the XG detector network.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2604.11871" target="_blank" rel="noopener">2604.11871 [gr-qc]</a>