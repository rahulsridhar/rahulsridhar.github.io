---
layout: page
title: A Graph Signal Processing Approach for Sample Influence Analysis
permalink: /graph_signal_processing/
exclude: true
---
![A Graph Signal Processing Approach for Sample Influence Analysis](../files/llnl_graph_image.png?raw=true)
<br><i>Most influential samples in the ImageNet data (for AlexNet)</i>
<br>

This was a project I had worked on as part of a team (at LLNL) that consisted of researchers from the Data Analysis group. The motivation/goals for this work was as follows:
<ul>
	<li>With the growing complexity of deep neural networks, unraveling black-box models is more critical than ever</li>
	<li>Example-based explanation is a popular strategy to succinctly describe the model’s observed behavior</li>
	<li>Influence analysis refers to a broad class of sample selection methods – Strongly tied to the metric used to define the desired notion of influence</li>
	<li><b>Goals:</b></li>
		<ul>
			<li>Create a generic framework for different influence metric choices</li>
			<li>Support model-agnostic and model-aware sample selection</li>
			<li>Deal with graph-structured and manifold data</li>
			<li>Perform fast optimization</li>
		</ul>
</ul>

Our approach, which is based on techniques from Graph Signal Processing, decouples the influence metric from the actual sample selection technique, and hence can be used with any type of task-specific influence. We demonstrate how this approach can be used to identify samples for prototype selection, semi-supervised classification, characterizing the decision surface, recovering corrupted labels efficiently, and also for computing image saliency maps.

I had presented a poster summarizing our methodology and findings at the <a href="http://sites.google.com/view/socalml17/home">SoCal Machine Learning Symposium 2017</a>. The poster can be viewed/downloaded below:
<object data="/files/llnl_socal_poster.pdf" type="application/pdf" width="720px" height="400px">
    <embed src="/files/llnl_socal_poster.pdf">
	<i>This browser does not support embedded PDFs. Please download it here: </i><a href="/files/llnl_socal_poster.pdf">Download report</a>
    </embed>
</object>
<br>
Here is the <a class="page-link" href="http://arxiv.org/abs/1711.05407 "><b><u>link</u></b></a> to the arXiv paper that we had written (submitted to ICML 2018).
