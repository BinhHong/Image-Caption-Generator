<p align="center">

<img src="https://img.shields.io/badge/made%20by-Binh%20Hong%20Ngoc-green">
<a href="https://www.linkedin.com/in/binhhongngoc/">
  <img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn Profile">
</a>
</p>

<h1 align="center"> IMAGE CAPTION GENERATOR </h1>

  
<h3> Table of contents </h3>
<ol>
    <li><a href="#intro">Introduction</a></li>
    <li><a href="#data">Dataset</a></li>
    <li><a href="#preprocessing">Data preprocessing</a></li>
    <li><a href="#models">Deep Learning model</a></li>
    <li><a href="#results">Results and interpretation</a> </li>
    <li><a href="#acknowledgement">Acknowledgement</a></li>
</ol>

<h2 id="intro">Introduction</h2>


<p align="center">
<br><br><img src="Pictures/VGG16.jpg" width="600" height="300">
</p>
<br>
<p>
<h2 id="data">Dataset</h2>

...

<h2 id="preprocessing">Data preprocessing</h2>
A careful data preparation has been carried out, among them
<ul>
    <li> data cleaning: remove duplicates, spot missing values and impute on some stats: shot on target %, save % ...</li>
    <li> outliers: an analysis of the outliers has been made. A correction has been performed to some values in several rows that appeared to be incorrect due to wrong calculation </li>
    <li> feature engineering: LabelEncoder has been used, to add additional significant columns to the dataset. Moreover, the average performance of the last k=4 games has been calculated. Lastly, we have considered correlation matrix and picked the most significant features for the models </li>
</ul>

<h2 id="models">Deep Learning model</h2>

...

</ul>

 <h2 id="results">Results and interpretation</h2>
...


<h2 id="acknowledgement">Acknowledgement</h2>
This project is inspired by the works of 
<ul>
    <li> <a href="https://www.youtube.com/watch?v=Nt7WJa2iu0s&list=PLQ22X3eLL96fi00hQL2VNaX-OKuDZ3H7s&index=11"> Vikas Paruchuri</a> </li>
    <li> <a href="https://www.youtube.com/watch?v=Nt7WJa2iu0s&list=PLQ22X3eLL96fi00hQL2VNaX-OKuDZ3H7s&index=11"> Vikas Paruchuri</a> </li>
    <li> <a href="https://www.youtube.com/watch?v=Nt7WJa2iu0s&list=PLQ22X3eLL96fi00hQL2VNaX-OKuDZ3H7s&index=11"> Vikas Paruchuri</a> </li>
  
</ul>
