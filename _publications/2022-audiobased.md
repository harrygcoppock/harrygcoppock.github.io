---
title: "Audio-based AI classifiers show no evidence of improved COVID-19 screening over simple symptoms checkers"
collection: publications
permalink: /publication/2022-audiobased
excerpt: ''
date: 2024/02/07
venue: 'Nature Machine Intelligence'
paperurl: 'https://www.nature.com/articles/s42256-023-00773-8'
biburl: /files/coppock2022audio.bib
citation: '<b>Harry Coppock</b>, et al., Audio-based AI classifiers show no evidence of improved COVID-19 screening over simple symptoms checkers, arXiv, 2022'
author_profile: false
---
Recent work has reported that AI classifiers trained on audio recordings can accurately predict severe acute respiratory syndrome coronavirus 2 (SARSCoV2) infection status. Here, we undertake a large scale study of audio-based deep learning classifiers, as part of the UK governments pandemic response. We collect and analyse a dataset of audio recordings from 67,842 individuals with linked metadata, including reverse transcription polymerase chain reaction (PCR) test outcomes, of whom 23,514 tested positive for SARS CoV 2. Subjects were recruited via the UK governments National Health Service Test-and-Trace programme and the REal-time Assessment of Community Transmission (REACT) randomised surveillance survey. In an unadjusted analysis of our dataset AI classifiers predict SARS-CoV-2 infection status with high accuracy (Receiver Operating Characteristic Area Under the Curve (ROCAUC) 0.846 [0.838, 0.854]) consistent with the findings of previous studies. However, after matching on measured confounders, such as age, gender, and self reported symptoms, our classifiers performance is much weaker (ROC-AUC 0.619 [0.594, 0.644]). Upon quantifying the utility of audio based classifiers in practical settings, we find them to be outperformed by simple predictive scores based on user reported symptoms.

[Download paper here](https://www.nature.com/articles/s42256-023-00773-8.pdf)


<script
	type="module"
	src="https://gradio.s3-us-west-2.amazonaws.com/3.36.1/gradio.js"
></script>

<gradio-app src="https://harrycoppock-interview-demo.hf.space"></gradio-app>


<details closed>
<summary>Bibtex Entry</summary>
<code>
<pre>
@article{coppock2023audiobased,
      title={Audio-based AI classifiers show no evidence of improved COVID-19 screening over simple symptoms checkers}, 
      author={ \textbf{Harry Coppock} and George Nicholson and Ivan Kiskin and Vasiliki Koutra and Kieran Baker and Jobie Budd and Richard Payne and Emma Karoune and David Hurley and Alexander Titcomb and Sabrina Egglestone and Ana Tendero Cañadas and Lorraine Butler and Radka Jersakova and Jonathon Mellor and Selina Patel and Tracey Thornley and Peter Diggle and Sylvia Richardson and Josef Packham and Björn W. Schuller and Davide Pigoli and Steven Gilmour and Stephen Roberts and Chris Holmes},
      year={2023},
      journal={Nature Machine Intelligence},
      notes={Contributions: H.C. led the project and wrote the manuscript. G.N. contributed to data analysis. I.K. and V.K. contributed to AI model development, etc. (expand with the specific contributions of each author)}
}

</pre>
</code>
</details>