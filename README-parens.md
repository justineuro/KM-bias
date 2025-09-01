<script type="text/x-mathjax-config">
MathJax = {
  tex: {
    packages: ["base","require","enclose",], 
    inlineMath: [ ["$","$"], ["\\(","\\)"] ],
    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
    processEscapes: true
  }
};
</script>

<script id="MathJax-script" async="" src="https://cdn.jsdelivr.net/npm/mathjax@3.2.2/es5/tex-mml-chtml.js"></script>


This repository contains sample files ([Maple](https://www.maplesoft.com/) codes, [Maxima](https://maxima.sourceforge.io/) codes, and [Jupyter Notebook](https://jupyter.org/)) that may be used for computing the small-sample bias of the [Kaplan-Meier estimator](https://en.wikipedia.org/wiki/Kaplan%E2%80%93Meier_estimator).  The codes are similar to the Maple V codes discussed in the article "Exact Calculation of the Kaplan-Meier Bias Using Maple Software" (Gillespie, B. and J. Uro, 1993) that appeared in _Mathematical Computation with Maple V: Ideas and Applications (Proceedings of the 1993 Maple Summer Workshop and Symposium)_, pp. 128-136.  

## For Python (Jupyter Notebook)
Please use the following link below pointing to a [Binder](https://mybinder.org) server:  

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/justineuro/KM-bias/9e36a2b2b553672faabffa341ff810520907672d?urlpath=lab%2Ftree%2Fkm-n5-e1e1t1.ipynb)
  
`Jupyter` notebook files for \\(n=5,\ T=1.0\\):  
(`Jupyter` input file: [km-n5-e1e1t1.ipynb](./km-n5-e1e1t1.ipynb); `Jupyter` output file:  [km-n5-e1e1t1-out.ipynb](./km-n5-e1e1t1-output.ipynb))  

---

## Computed Bias for \\(T = 0.5\\)
\\(n = 10\\)  
Failure Time Distribution: \\(f_X(x) = \exp(-x),\ x>0\\)  
Censoring Time Distribution: \\(f_Y(y) = \exp(-y),\ y>0\\)  
Expected Lifetime: \\(\exp(-0.5) = 0.6065306597126334 \\) 

Estimator | Estimated Expected Value | Bias
---|---|---
Efron | \\( 0.6048530839301303\\) | \\(-0.00167757578250316\\)
Gill | \\(0.6066478084305761\\) | \\(\hspace{12px}0.00011714871794266\\)

(`Maxima` input file: [km-n10-e1e1t05.mac](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t05.mac); `Maxima` output file:  [km-n10-e1e1t05-output.mac](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t05-output.mac))  
(`Maple` input file: [km-n10-e1e1t05-Efron.mws](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t05-Efron.mws); `Maple` output file:  [km-n10-e1e1t05-Efron-output.mw](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t05-Efron-out.mw))  

---

## Computed Bias for \\(T = 1.0\\)
\\(n = 10\\)  
Failure Time Distribution: \\(f_X(x) = \exp(-x),\ x>0\\)  
Censoring Time Distribution: \\(f_Y(y) = \exp(-y),\ y>0\\)  
Expected Lifetime: \\(\exp(-1.0) = 0.36787944117144233 \\) 

Estimator | Estimated Expected Value | Bias
---|---|---
Efron | \\( 0.3339997005016279\\) | \\(-0.03387974066981442\\)
Gill | \\(0.37515976194249184\\) | \\(\hspace{12px}0.007280320771049509\\)
  
(`Maxima` input file: [km-n10-e1e1t1.mac](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t1.mac); `Maxima` output file:  [km-n10-e1e1t1-output.mac](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t1-output.mac))  
(`Maple` input file: [km-n10-e1e1t1-Efron.mws](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t1-Efron.mws); `Maple` output file:  [km-n10-e1e1t1-Efron-output.mw](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t1-Efron-out.mw))  

---

## Computed Bias for \\(T = 2.0\\)
\\(n = 10\\)  
Failure Time Distribution: \\(f_X(x) = \exp(-x),\ x>0\\)  
Censoring Time Distribution: \\(f_Y(y) = \exp(-y),\ y>0\\)  
Expected Lifetime: \\(\exp(-2.0) = 0.1353352832366127 \\) 

Estimator | Estimated Expected Value | Bias
---|---|---
Efron | \\( 0.06114801462318425\\) | \\(-0.07418726861342845\\)
Gill | \\(0.20760745229019978\\) | \\(\hspace{12px}0.07227216905358708\\)
  
(`Maxima` input file: [km-n10-e1e1t2.mac](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t2.mac); `Maxima` output file:  [km-n10-e1e1t2-output.mac](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t2-output.mac))  
(`Maple` input file: [km-n10-e1e1t2-Efron.mws](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t2-Efron.mws); `Maple` output file:  [km-n10-e1e1t2-Efron-output.mw](https://raw.githubusercontent.com/justineuro/KM-bias/refs/heads/main/km-n10-e1e1t2-Efron-out.mw))  


---

#### Acknowledgments: 
Many thanks to:

* [GitHub](https://github.com/) for hosting the project.
* [OpenAI](https://openai.com/): [ChatGPT](https://chatgpt.com/) was used to rewrite the Maple codes to Maxima codes.  Please access the public ChatGPT session at: [URL](https://chatgpt.com/share/68690057-0dc4-8002-a554-71a615f8a91b), for more info. 

---

## License
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/">
<a property="dct:title" rel="cc:attributionURL" href="https://github.com/justineuro/KM-bias">KM-bias</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://justineuro.github.io/">Justine Leon A. Uro</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution 4.0 International<img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"/><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"/></a><br/>Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/justineuro/KM-bias" rel="dct:source">KM-bias</a>.
</p>