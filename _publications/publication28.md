---
title: "Systematic biases in parameter estimation on LISA binaries. II. The effect of excluding higher harmonics for spin-aligned, high-mass binaries"
collection: publications
permalink: /publications/publication28
excerpt: "We extend our previous analysis of systematics in LISA, including aligned spins and more massive systems."
date: 2026-02-09
venue: "Phys. Rev. D"
authorlist: "S. Yi, **F. Iacovelli**, E. Berti, R. S. Chandramouli, S. Marsat, D. Wadekar, N. Yunes"
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
var recid = '3118150';
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
We extend our [previous analysis]({{ site.baseurl }}{% link _publications/publication21.md %}) to higher masses and aligned spins, in which cases biases are more severe. We improve our likelihood optimization tool and show how it can be used to predict wrong inference of the sky localization.  

### Contribution
I contributed to the conceptual development of the paper, the writing, and the improvement and validation of the likelihood optimization tool.

### Abstract
The Laser Interferometer Space Antenna (LISA) will observe massive black hole binaries (MBHBs) with astoundingly high signal-to-noise ratio, leaving parameter estimation with these signals susceptible to seemingly small waveform errors. Of particular concern for MBHBs are errors due to neglected higher-order modes. We extend Yi et al. [[Phys. Rev. D **112**, 124063 (2025)](https://doi.org/10.1103/3gs3-gmb4)] to examine errors due to neglected higher-order modes for MBHBs with nonzero (aligned) progenitor spins and total mass up to 10<sup>8</sup> M<sub>&odot;</sub>. For these very massive systems, there can be regions of parameter space in which the (&ell;,|_m_|)=(2,2) modes are no longer dominant with respect to higher-order ones. We find that the extent of systematic bias can change significantly when varying the progenitor spins of the binary. We also find that for the heaviest, and therefore shortest, MBHB signals, slight systematic errors can cause severe mis-inference of the sky localization parameters. We propose an improved likelihood optimization scheme with respect to previous work as a way to predict these effects in a computationally efficient manner.

### Links

<i class="ai ai-arxiv ai-fw"></i> arXiv: <a href="https://arxiv.org/abs/2602.09088" target="_blank" rel="noopener">2602.09088 [gr-qc]</a>