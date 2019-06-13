---
layout: page
title: About me
subtitle: You know, all models are wrong, but some are useful
css: "/css/aboutme.css"

---
<head>
  <link rel="stylesheet" href="scss_icon.css">
</head>



<div id="aboutme-section">

<p class="about-text">
<img class = "external-icon" src="/img/brain.svg" alt="image">
<!--<span href="/img/function.png" class="about-icon"> </span>-->
A Ph.D. candidate in behavioral science (Communication studies) with a dual M.S. in Statistics. I am working to be a data scientist or computational social scientist. 
</p>

<p class="about-text">
<img class = "external-icon" src="/img/ai.svg" alt="image">

My dissertation is titled <i>What deep learning could bring to framing analysis on Twitter</i> under the amazing supervisor <a href = "https://comm.tamu.edu/kirby-goidel/" target="_blank">Dr. Kirby Goidel</a>, the director of the <a href = "https://ppri.tamu.edu/" target="_blank">Public Policy Research Institute</a> at Texas A&M University. The dissertation serves as a comprehensive experiment about the effects of diverse state-of-the-art NLP models in analysing twitter messages and includes statistical tests for those effects.
</p>

<p class="about-text">
<img class = "external-icon" src="/img/stats.svg" alt="image">

4 years of statistical modeling experience. Proficient in experimental design, predictive modeling, structural equation modeling, mixture model methods, Bayesian inference and data visualization. See my projects in <a href = "">here</a>.  
Big fan of fast.ai and an practioner of their deep learning API for two years. 
</p>


<p class="about-text">
<img class = "external-icon" src="/img/bonfire.svg" alt="image">
I am an avid backpacker and cracy about national parks. <a href = "">Here</a> you could see some of the amateur photos I took while travling.
</p>

<br>


<section class="flex-block flex-block--wrapper">
    <article class="flex-block flex-block--row flex-block--flex-end">
            <aside class="flex-block--grid flex-block--padding">
                <ul class="skills-list flex-block--grid">
                        <h3 class="flex-block--full">Languages & tools</h3>
                        {% for skill in site.skills %}
                            <li class="skills-list-icon flex-block--grid__item">   
                            <img src="/img/icons/{{skill.image}}" alt="{{ skill.name }}" class="icon icon--skills">
                            </li>

                        {% endfor %}
                 </ul>

             </aside>
         </article>
 </section>

</div>






<div>Icons made by <a href="https://www.flaticon.com/authors/eucalyp" title="Eucalyp">Eucalyp</a> from <a href="https://www.flaticon.com/" 			    title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" 			    title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>
</div>


