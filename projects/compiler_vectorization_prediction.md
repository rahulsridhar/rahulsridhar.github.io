---
layout: page
title: Compiler Vectorization Prediction
permalink: /compiler_vectorization_prediction/
exclude: true
---
![Compiler Vectorization](../files/compiler_image.jpg?raw=true)
<center> <i>Figure: Distribution of instruction cache misses across non-vectorized and vectorized loops </i></center>
<br>
The process of vectorization entails converting the scalar implementation of a computer program into a vector implementation. This project attempts to build on <a href="http://cecs.uci.edu/files/2017/05/combinepdf.pdf">recent work</a> involving the usage of hardware performance counters and techniques from machine learning to predict auto-vectorization of compilers by validating similar machine learning models on a different architecture and compiler, and also shows the benefits of data augmentation through sample synthesis on such applications. Using predictive models along with data augmentation on hardware performance data, I was able to successfully predict whether a compiler was able to auto-vectorize a program.


The project report can be viewed/downloaded below:
<object data="/files/compiler_report.pdf" type="application/pdf" width="360px" height="400px">
    <embed src="/files/compiler_report.pdf">
	<i>This browser does not support embedded PDFs. Please download it here: </i><a href="/files/compiler_report.pdf">Download report</a>
    </embed>
</object>
<br>
The Jupyter notebooks containing the experiments and their results can be downloaded <a href='/files/compiler_codes.zip'>here</a>.

<!--
You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)-->


[jekyll-organization]: https://github.com/jekyll
