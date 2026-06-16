---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# Bio

I am currently a second-year Master's student (M2) at Université de Toulouse, working as a R&D intern at [LINAGORA Labs](https://labs.linagora.com/) under the supervision of [Dr. Julie Hunter](https://www.juliejhunter.com/).

My research interests center on reasoning in language models, mechanistic interpretability, and efficient systems for training and analysis.

I am currently working on model pruning and distillation techniques to develop a math-specialized model for the [Luciole](https://huggingface.co/collections/OpenLLM-France/luciole-llm) series at LINAGORA Labs. More recently, I pre-trained a 1B Luciole model from scratch on 3T tokens using a custom attention scoring function, [SSA](https://arxiv.org/pdf/2508.14685).

I am open to both research and industry roles starting after October 2026.

You can reach me at: niyar-r.barman[at]utoulouse[.]fr


# News
<div class='news-container'>
<ul>
<li><strong>Apr 2026</strong>: Joined the R&amp;D Team at (<a href="https://labs.linagora.com/">LINAGORA Labs</a>) for M2 Internship</li>
<li><strong>Apr 2026</strong>: TELL-TALE: Task Efficient LLMs with Task Aware Layer Elimination accepted at the Findings of ACL 2026</li>
<li><strong>Sep 2025</strong>: Started M.S. in Interactions of Computer Science and Mathematics for AI at Université de Toulouse, France</li>
<li><strong>Aug 2025</strong>: DIMSUM: Discourse in Mathematical Reasoning as a Supervision Module accepted at SIGDIAL 2025</li>
<li><strong>Jan 2025</strong>: Returned to IRIT, Toulouse for a second full-time research internship</li>
<li><strong>May 2024</strong>: Started first full-time research internship at IRIT, Toulouse, France</li>
<li><strong>Dec 2023</strong>: Counter Turing Test CT² presented at EMNLP 2023, received Outstanding Paper Award</li>
<li><strong>Jan 2023</strong>: Started remote research internship at the Artificial Intelligence Institute, University of South Carolina, USA</li>
<li><strong>Dec 2021</strong>: Started B.Tech. in Electronics and Communication Engineering at National Institute of Technology Silchar, India</li>
</ul>
</div>




# Publications 

<div class='publication-toggle'>
<span class='toggle-option active' data-filter='selected'>selected</span>
<span class='toggle-separator'>·</span>
<span class='toggle-option' data-filter='all'>all</span>
</div>

<div class='publication-item selected-pub'>
<div class='publication-venue'>ACL 2026 Findings</div>
<div class='publication-title'><a href="https://arxiv.org/abs/2510.22767">TELL-TALE: Task Efficient LLMs with Task Aware Layer Elimination</a></div>
<div class='publication-authors'>Omar Naim, Krish Sharma, <strong>Niyar R Barman</strong>, Nicholas Asher</div>
<!-- <div class='publication-details'>Proceedings of the 25th Annual Meeting of the Special Interest Group on Discourse and Dialogue</div> -->
<div class='publication-description'>TALE boosts LLM inference by removing task-irrelevant layers to match or exceed baseline accuracy across 9 tasks and 5 model families while reducing compute, requiring no retraining and only modest setup cost.</div>
<div class='publication-links'><a href="https://arxiv.org/abs/2510.22767">paper</a><span class='link-separator'> · </span><a href="https://github.com/omyokun/tale">code</a></div>
</div>

<div class='publication-item selected-pub'>
<div class='publication-venue'>SIGDIAL 2025</div>
<div class='publication-title'><a href="https://aclanthology.org/2025.sigdial-1.24/">DIMSUM: Discourse in Mathematical Reasoning as a Supervision Module</a></div>
<div class='publication-authors'>Krish Sharma*, <strong>Niyar R Barman</strong>*, Nicholas Asher, Akshay Chaturvedi</div>
<div class='publication-details'>Proceedings of the 26th Annual Meeting of the Special Interest Group on Discourse and Dialogue</div>
<div class='publication-description'>This work explores how discourse structures can be used as supervision for improving mathematical reasoning in large language models.</div>
<div class='publication-links'><a href="https://aclanthology.org/2025.sigdial-1.24/">paper</a><span class='link-separator'> · </span><a href="https://github.com/Krish2002/DIMSUM">code</a></div>
</div>

<div class='publication-item selected-pub'>
<div class='publication-venue'>EMNLP 2023</div><a class='publication-award' href="https://www.linkedin.com/posts/niyar_emnlp2023-activity-7139621629269118977-ia-L/">outstanding paper award</a>
<div class='publication-title'><a href="https://aclanthology.org/2023.emnlp-main.136/">Counter Turing Test CT²: AI-Generated Text Detection is Not as Easy as You May Think</a></div>
<div class='publication-authors'>Megha Chakraborty, S. M. Towhidul Islam Tonmoy, S. M. Mehedi Zaman, Krish Sharma, <strong>Niyar R Barman</strong>, Chandan Gupta, Shreya Gautam, Tanay Kumar, Vinija Jain, Aman Chadha, Amit P. Sheth, Amitava Das</div>
<div class='publication-details'>Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing</div>
<div class='publication-description'>Introduces the AI Detectability Index and challenges current approaches to AI-generated text detection.</div>
<div class='publication-links'><a href="https://aclanthology.org/2023.emnlp-main.136/">paper</a></div>
</div>

<div class='publication-item other-pub'>
<div class='publication-venue'>Preprint 2024</div>
<div class='publication-title'><a href="https://arxiv.org/abs/2408.10446">The Brittleness of Image Watermarking Techniques: Investigating Visual Paraphrasing for De-Watermarking AI-Generated Images</a></div>
<div class='publication-authors'><strong>Niyar R Barman</strong>, Krish Sharma, Ashhar Aziz, Shashwat Bajpai, Shwetangshu Biswas, Aman Chadha, Vasu Sharma, Amitava Das</div>
<div class='publication-description'>Demonstrates that current AI image watermarking methods are fragile and can be circumvented through visual paraphrase attacks using image captioning and diffusion systems.</div>
<div class='publication-links'><a href="https://arxiv.org/abs/2408.10446">paper</a></div>
</div>

<div class='publication-item other-pub'>
<div class='publication-venue'>IEEE CICT 2023</div>
<div class='publication-title'><a href="https://ieeexplore.ieee.org/abstract/document/10455356/">A Transformer-Based Approach to Automate Disease Prediction from Patient Descriptions</a></div>
<div class='publication-authors'><strong>Niyar R Barman</strong>, Krish Sharma, Ranjay Hazra</div>
<div class='publication-details'>IEEE 7th Conference on Information and Communication Technology</div>
<div class='publication-description'>Proposes a transformer-based approach for automated disease prediction using textual symptom descriptions to provide accurate diagnoses.</div>
<div class='publication-links'><a href="https://ieeexplore.ieee.org/abstract/document/10455356/">paper</a></div>
</div>

<div class='publication-item other-pub'>
<div class='publication-venue'>FIRE 2023</div>
<div class='publication-title'><a href="https://ceur-ws.org/Vol-3681/T6-6.pdf">Addressing Hate Speech: ATLANTIS for Efficient Hate Span Detection</a></div>
<div class='publication-authors'><strong>Niyar R Barman</strong>, Krish Sharma, Yashraj Poddar, Adwaitha Vatupal, Partha Pakray</div>
<div class='publication-details'>FIRE 2023 Working Notes</div>
<div class='publication-description'>Presents a hate span detection system capable of identifying consecutive sets of hateful content in text.</div>
<div class='publication-links'><a href="https://ceur-ws.org/Vol-3681/T6-6.pdf">paper</a></div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const toggleOptions = document.querySelectorAll('.toggle-option');
    const selectedPubs = document.querySelectorAll('.selected-pub');
    const otherPubs = document.querySelectorAll('.other-pub');
    
    // Default: show only selected
    otherPubs.forEach(pub => pub.style.display = 'none');
    
    toggleOptions.forEach(option => {
        option.addEventListener('click', function() {
            // Update active state
            toggleOptions.forEach(opt => opt.classList.remove('active'));
            this.classList.add('active');
            
            const filter = this.getAttribute('data-filter');
            
            if (filter === 'selected') {
                selectedPubs.forEach(pub => pub.style.display = 'block');
                otherPubs.forEach(pub => pub.style.display = 'none');
            } else {
                selectedPubs.forEach(pub => pub.style.display = 'block');
                otherPubs.forEach(pub => pub.style.display = 'block');
            }
        });
    });
});
</script>
<div class='publication-details'>
    <center>* equal contribution</center>
</div>
# Research Experience
<span class='anchor' id='-research-experience'></span>

- *Apr 2026 - Sep 2026*, **R&D Intern**, LINAGORA Labs, France
- *May 2024 - Jul 2024, Jan 2025 - Mar 2025*, **Research Intern**, Institut de Recherche en Informatique de Toulouse, France
- *Jan 2023 - Dec 2024*, **Research Intern**, Artificial Intelligence Institute of University of South Carolina, United States


# Education
<span class='anchor' id='-educations'></span>

- *2025 - 2026*, **M2 Master Interactions de l'Informatique et des Mathématiques pour l'IA**, Université de Toulouse, France
- *2021 - 2025*, **Bachelors of Technology in Electronics and Communication Engineering**, National Institute of Technology Silchar, India
