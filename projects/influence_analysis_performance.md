---
layout: page
title: Influence Analysis for Performance Data
permalink: /influence_analysis_performance/
exclude: true
---
![Influence Analysis for Performance Data](../files/llnl_hpc_image.png?raw=true)
<center> <i>Difference in Fourier spectra after removing weak/strong parameters</i></center>
<br>

This was a project I had worked on as part of a team (at LLNL) that consisted of researchers from the Data Analysis and High Performance Computing (HPC) groups. The HPC team makes use of multiple applications that work in a high-dimensional space, each of which have different parameter settings that can be differently tweaked to solve the same problem, resulting in different performance characteristics (execution times) of the program. Additionally, running simulations of the program with all possible parameter settings (in order to measure performance) is expensive, primarily due to most of the parameters being discrete in nature, with multiple possible levels. Given this context, their primary problems/questions were three-fold:
<ul>
	<li><b>Global parameter influence analysis:</b> How can the overall influence of each of these parameters on the execution time of a program be quantified? i.e., identify the most and least influential parameters</li>
	<li><b>Subdomain analysis:</b> How does influence vary across different subdomains of the parametric space?</li>
	<li><b>Enhancing predictive power with less data:</b> Can the execution time of a program for all different parameter combinations be predicted accurately with only <i>x</i>% of the entire data (<i>x</i> ideally being much smaller than 100)?</li>
</ul>
Furthermore, interpretibility of the predictive model was a highly desired trait. We hence implemented a novel, interpretable, model-agnostic influence analysis using a relatively emerging field of Machine Learning called Graph Signal Processing. 

A poster summarizing our findings and methodology was presented at the premier Supercomputing conference <a href="https://sc17.supercomputing.org">SC17</a>. The poster can be viewed/downloaded below:
<object data="/files/llnl_sc_poster.pdf" type="application/pdf" width="720px" height="400px">
    <embed src="/files/llnl_sc_poster.pdf">
	<i>This browser does not support embedded PDFs. Please download it here: </i><a href="/files/llnl_sc_poster.pdf">Download report</a>
    </embed>
</object>
<br>
