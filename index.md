---
layout: default
title: Home
markdown: kramdown
---


<h1>Alex Deng</h1>

<div style="float: right;padding-left:15px;">
  <img src="{{ site.baseurl }}public/profile2_mono_sq.jpg" alt="Alex Shaojie Deng" title="Alex Deng" width="200px"/>
</div>

I'm a data and applied scientist on the [Microsoft Analysis and Experimentation Team](http://www.exp-platform.com). The Analysis and Experimentation team is responsible for one of the largest and best cutting-edge online experimentation system in the industry. I'm currently leading a team focusing on methodological improvements of the experimentation platform and tackling the related engineering challenges. [We are hiring!](http://www.exp-platform.com/Pages/hiring.aspx)

I finished my Ph.D. study in statistics at Stanford in 2010 focusing on sequential Monte Carlo with [Prof. Tze Lai](https://statistics.stanford.edu/people/tze-leung-lai). I have broad interests in all kinds of statistical methods, web programing, data visualization and physics. 


## Selected Publications (newest first)
-   [On randomization-based causal inference for matched-pair
factorial designs]({{site.baseurl}}public/files/STAPRO_7848_final.pdf)  
Jiannan Lu, Alex Deng. Statistics and Probability Letters, 2017. 
-   [Trustworthy analysis of online A/B tests: Pitfalls, challenges and solutions (Draft Version)]({{site.baseurl}}public/files/WSDM2017draft.pdf)  
    Alex Deng, Jiannan Lu, Jonathan Litz. To appear in WSDM 2017. 
-   [Continuous monitoring of A/B tests without pain: Optional stopping in Bayesian testing]({{site.baseurl}}public/files/continuousMonitoring.pdf)  ([ArXiv ver.](http://arxiv.org/abs/1602.05549))    
    Alex Deng, Jiannan Lu, Shouyuan Chen. DSAA 2016.
-   [Data-Driven Metric Development for Online Controlled Experiments: Seven Lessons Learned](http://www.kdd.org/kdd2016/papers/files/adf0853-dengA.pdf)  
    Alex Deng, Xiaolin Shi. KDD 2016.
-   [Demystifying the Bias from Selective Inference: a Revisit to Dawid's Treatment Selection Problem]({{site.baseurl}}public/files/LuDeng2016SPL_final.pdf)  
    Jiannan Lu, Alex Deng. Statistics and Probability Letters, 2016.
-   [Objective Bayesian Two Sample Hypothesis Testing for Online Controlled Experiments]({{site.baseurl}}public/files/BayesianAB.pdf) ([Slides]({{site.baseurl}}public/files/OBA.pdf))      
    Alex Deng. WWW 2015, The 1st Workshop on Offline and Online Evaluation of Web-based Services
-   [Diluted Treatment Effect Estimation for Trigger Analysis in Online Controlled Experiments]({{site.baseurl}}public/files/wsdm2015-dilution.pdf) ([Slides]({{site.baseurl}}public/files/WSDM2015DilutionTalk.pdf))  
    Alex Deng and Victor Hu. WSDM 2015.  
-   [Seven Rules of Thumb for Web Site Experimenters](http://www.exp-platform.com/Pages/SevenRulesofThumbforWebSiteExperimenters.aspx)    
    Ron Kohavi, Alex Deng, Roger Longbotham, and Ya Xu. KDD 2014.
-   [Statistical Inference in Two-stage Online Controlled Experiments with Treatment Selection and Validation](http://www.exp-platform.com/Documents/p609-deng.pdf)  
    Alex Deng, Tianxi Li and Yu Guo. WWW 2014.
-   [Online Controlled Experiments at Large Scale](http://www.exp-platform.com/Pages/ControlledExperimentsAtLargeScale.aspx)  
    Ron Kohavi, Alex Deng, Brian Frasca, Toby Walker, Ya Xu, Nils Pohlmann. KDD 2013.
-   [Improving the Sensitivity of Online Controlled Experiments by Utilizing Pre-Experiment Data](http://www.exp-platform.com/Pages/CUPED.aspx)  
    Alex Deng, Ya Xu, Ron Kohavi and Toby Walker. WSDM 2013.
-   [Trustworthy Online Controlled Experiments: Five Puzzling Outcomes Explained](http://www.exp-platform.com/Pages/PuzzlingOutcomesExplained.aspx)  
    Ron Kohavi, Alex Deng, Brian Frasca, Roger Longbotham, Toby Walker and Ya Xu. KDD 2012.
-   [Sequential importance sampling and resampling for dynamic portfolio credit risk](http://statweb.stanford.edu/~ckirby/lai/pubs/2011_SequentialImportance.pdf)  
    Shaojie Deng, Kay Giesecke and Tze Lai. Operations Research Feb, 2012.
-   [Rare-event simulation of heavy-tailed random walks by sequential importance sampling and resampling](http://statweb.stanford.edu/~ckirby/lai/pubs/2012_Rare-EventSimulation.pdf)  
    Hock Peng Chan, Shaojie Deng and Tze-Leung Lai. Advances in Applied Probability 2012.


## Preprints And Working Papers
-   Concise Summarization of Heterogeneous Treatment Effect Using Total Variation Regularized Regression    
    Alex Deng, Pengchuan Zhang, Shouyuan Chen, Dong Woo Kim and Jiannan Lu. [ArXiv](https://arxiv.org/abs/1610.03917)
-   Flexible Online Repeated Measures Experiment  
    Yu Guo and Alex Deng. [ArXiv](http://arxiv.org/abs/1501.00450)

## Other Talks/Slides 
-   [A/B Testing for the Next Decade: challenges, competitions and opportunities (Netflix U Talk)]({{site.baseurl}}public/files/NetflixUTalk.pdf)
-   [Challenges in A/B Testing (Amazon Tech Talk)]({{site.baseurl}}public/files/Amazon%20Tech%20Talk.pdf)
-   [Essential Causual Inference Using Observational Data](http://rpubs.com/alexdeng/EssentialDnA)


## Other (non-peer-reviewed) 
-   [Finite User Pool Effect in Two Sample t-test of Controlled Experiments on the Web]({{site.baseurl}}public/files/interface2011-deng.pdf)    
    Shaojie Deng. Interface 2011.
-   [Choice of the Randomization Unit in Online Controlled Experiment]({{site.baseurl}}public/files/jsm2011-deng.pdf)  
    Shaojie Deng, Roger Longbotham, Toby Walker and Ya Xu. JSM 2011.




<!-- <div class="posts">
  {% for post in paginator.posts %}
  <div class="post">
    <h1 class="post-title">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div> -->

<!-- <div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div> -->

