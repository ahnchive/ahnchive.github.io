---
layout: page
title: Research
description: Seoyoung Ahn's research and selected publications
---

<div style="text-align:center; margin-top:-20px;">
  <figure>
    <img src="{{BASE_PATH}}/pics/bombard.gif" alt="attention is important" style="width:100%;"/>
    <figcaption>image source: <a href="https://medium.com/@albertlai631/how-do-self-driving-cars-see-13054aee2503" target="_blank">here</a></figcaption>
  </figure>
</div>

Our visual system is constantly receiving a large amount of information from the environment, and attention plays a critical role in selectively focusing on the most relevant aspects of our visual environment. My research is centered on exploring the role of attention in visual processing and how it shapes our perception of the world. I use computational models and behavioral experiments to investigate the mechanisms underlying attention and how they facilitate object recognition, grouping, and search in humans. By developing an artificial vision system that can mimic and predict human attentional processes more accurately, I aim to improve the safety and sophistication of human-machine interaction in visual environments. This will enable more intuitive and effective collaboration between humans and machines in various applications. Currently, I'm exploring the use of generative models to explain human object-based attention. 

**Keywords:** Vision, Attention, Eye-movements, Gaze Prediction, Computational Modeling

<!-- <a href="#book"> Generative Vision </a>, <a href="#book"> Object-based Attention</a>, <a href="#book">Goal-directed Attention</a>, <a href="#book">Gaze Prediction</a>, <a href="#book">Decoding Eye-Movements</a>, <a href="#book">Reading</a>
 -->


<!-- <div class="navbar-centered">
    <div class="navbar-inner-centered">
        <ul class="nav">
            <li><a href="#book">Modeling Generative Attention</a></li>
        </ul>
    </div>
    <div class="navbar-inner-centered">
        <ul class="nav">
            <li><a href="#letters">Decoding Eye-Movements</a></li>
        </ul>
    </div>
</div>


<div class="navbar-centered">
    <div class="navbar-inner-centered">
        <ul class="nav">
            <li><a href="#articles">Gaze Prediction</a></li>
        </ul>
    </div>
    <div class="navbar-inner-centered">
        <ul class="nav">
            <li><a href="#articles">Language & Vision</a></li>
        </ul>
    </div>
    <div class="navbar-inner-centered">
        <ul class="nav">
            <li><a href="#editorials">Reading</a></li> 
        </ul>
    </div>

</div> -->

---
##### Highlighted Projects and Publications:
for the most up-to-date and comprehensive list of publications, please visit my <a href="https://scholar.google.com/citations?user=FxF4Y1UAAAAJ&hl=en" target="_blank">google scholar</a>

<br/>

#### <a name="generative"></a> Generated Object Reconstructions for Object-based Attention
<div class="container" style="margin-top:20px;">
    <div class="row-fluid">
        <div class="span7">
        <img style="float: left; margin: 0px 15px 15px 15px;" src="{{ BASE_PATH }}/pics/pareidolia.jpeg" width="100" />
        Humans need to interact with objects, so evolution endowed us with a visual system that constantly attempts to reconstruct familar or meaningful objects; <a href="https://mars.nasa.gov/multimedia/space-oddities/" target="_blank">face on Mars</a>. This project explores how and to what extent this top-down object reconstruction is functionally used for object recognition, grouping, and attention. We use a generative, object-centric approach to study this problem.  
        </div>
    </div>
</div>

<u>Selected Publications</u>:
- Ahn S, Adeli H, Zelinsky G. Reconstruction-guided attention improves the robustness and shape processing of neural networks. SVRHM at Neurips Workshops. 2022 [![pdf]({{ BASE_PATH }}/pics/icons16/pdf-icon.png)](https://openreview.net/pdf?id=tmvg0VIHTDr){:target="_blank"}
- Adeli H, Ahn S, Zelinsky G. A brain-inspired object-based attention network for multi-object recognition and visual reasoning. bioRxiv. [under review] [![pdf]({{ BASE_PATH }}/pics/icons16/pdf-icon.png)](https://www.biorxiv.org/content/10.1101/2022.04.02.486850v2.full.pdf){:target="_blank"}


<br/>

#### <a name="decoding"></a> Decoding Cognitive States from Eye-Movements
<div class="container" style="margin-top:20px;">
    <div class="row-fluid">
        <div class="span7">
        <img style="float: left; margin: 5px 15px 15px 15px;" src="{{ BASE_PATH }}/pics/yarbus.png" width="120" />
        Since <a href="https://commons.wikimedia.org/wiki/File:Yarbus_The_Visitor.jpg" target="_blank">Yarbus (1967)</a>, many studies have shown that eye movements provide a sensitive indicator of  individual differences and the influence of top-down cognitive control on our visual processing. This project aims to extract meaningful features from eye movements and build computational models that can predict various cognitive states. These may include things like task demands, comprehension levels, memory performance, and even symptoms of certain psychiatric disorders. 
        </div>
    </div>
</div>

<u>Selected Publications</u>:
- Ahn S, Kelton C, Balasubramanian A, Zelinsky G. Towards predicting reading comprehension from gaze behavior. ETRA. 2020 [![pdf]({{ BASE_PATH }}/pics/icons16/pdf-icon.png)](https://dl.acm.org/doi/pdf/10.1145/3379156.3391335){:target="_blank"}
- Kelton C, Wei Z, Ahn S, Balasubramanian A, Das SR, Samaras D, Zelinsky G. Reading detection in realtime. ETRA. 2019 [![pdf]({{ BASE_PATH }}/pics/icons16/pdf-icon.png)](https://dl.acm.org/doi/pdf/10.1145/3314111.3319916){:target="_blank"}
- Ahn S, Lee D, Hinojosa A, Koh S. Task Effects on Perceptual Span during Reading: Evidence from Eye Movements in Scanning, Proofreading, and Reading for Comprehension [under review] 

<br/>

#### <a name="gaze"></a> Gaze Modeling and Prediction
<div class="container" style="margin-top:20px;">
    <div class="row-fluid">
        <div class="span7">
        <img style="float: left; margin: 5px 15px 15px 15px;" src="{{ BASE_PATH }}/pics/gaze.png" width="200" />
        This project aims to develop computational models that can predict human gaze trajectory during visual tasks, including free-viewing and visual search, by incorporating biologically plausible algorithms (e.g., reinforcement learning) and encoding constraints (e.g., foveated representation). The ultimate goal is to use this understanding of how humans allocate their spatial attention to develop next-generation systems that can intelligently anticipate a user's needs or desires.
        </div>
    </div>
</div>

<u>Selected Publications</u>:
- Mondal S, Yang Z, Ahn S, Samaras D, Zelinsky G, Hoai M. Gazeformer: Scalable, Effective and Fast Prediction of Goal-Directed Human Attention. CVPR. 2023
- Yang Z, Huang L, Chen Y, Wei Z, Ahn S, Zelinsky G, Samaras D, Hoai M. Predicting goal-directed human attention using inverse reinforcement learning. CVPR. 2020 [![pdf]({{ BASE_PATH }}/pics/icons16/pdf-icon.png)](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yang_Predicting_Goal-Directed_Human_Attention_Using_Inverse_Reinforcement_Learning_CVPR_2020_paper.pdf){:target="_blank"}
- Zelinsky G, Yang Z, Huang L, Chen Y, Ahn S, Wei Z, Adeli H, Samaras D, Hoai M. Benchmarking gaze prediction for categorical visual search. CVPR Workshops. 2019 [![pdf]({{ BASE_PATH }}/pics/icons16/pdf-icon.png)](https://openaccess.thecvf.com/content_CVPRW_2019/papers/MBCCV/Zelinsky_Benchmarking_Gaze_Prediction_for_Categorical_Visual_Search_CVPRW_2019_paper.pdf){:target="_blank"}





