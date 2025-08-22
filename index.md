---
layout: page
title: Guoming Tang
subtitle: Assistant Professor, DSA Thrust, Information Hub
subtitle2: The Hong Kong University of Science and Technology (Guangzhou)
img: /img/profile-photo-gmtang-2024.png
social_media: true
---


Hello and welcome!

I am a tenure-track Assistant Professor in the <a href="https://www.hkust-gz.edu.cn/academics/hubs-and-thrust-areas/information-hub/data-science-and-analytics/" target="_blank">Data Science and Analytics (DSA) Thrust</a> at the <a href="https://www.hkust-gz.edu.cn/academics/hubs-and-thrust-areas/information-hub/" target="_blank">Information Hub</a>, <a href="https://www.hkust-gz.edu.cn/" target="_blank">The Hong Kong University of Science and Technology (Guangzhou)</a>, and an Affiliate Assistant Professor at <a href="https://hkust.edu.hk/" target="_blank">The Hong Kong University of Science and Technology</a>. I lead the **Sustainable Computing (SusCom) Lab** at HKUST(GZ), where our research focuses on advancing **computing systems** and **AI Infra** to enhance energy efficiency, scalability, and environmental responsibility.

Current research interests include (**Sustainable AI** track):

- KV cache optimization for memory-efficient LLM inference;
- Energy-efficient AI model/LLM serving and deployment;
- Scheduling, dispatching, and orchestrating of computational resources (like GPUs) in cloud and edge environments.

We are also interested in developing AI-aided solutions for power monitoring, modeling, and saving in data centers and smart homes/buildings. Typical research problems we are tackling include (**AI for Sustainability** track):

- Software-defined power supplying for low/zero-carbon data centers;
- Non-intrusive load monitoring (NILM) for smart homes;
- Integrating LLM capability into building energy systems (BESs).


<div style="
    background-color: #f2f2f2; 
    border-radius: 5px;
    padding: 15px; 
    margin: 10px 0;">
  
  <span style="color:red"><strong>Recruitment:</strong></span> 
  I am actively seeking <strong>self-motivated PhD students, RAs, and Interns</strong> to join my research group. If you are interested, please send your CV and transcripts to my email below. If you are currently (or going to be) enrolled in the <strong>RBM program at HKUST(GZ)</strong> and are interested in any of our research topics, please feel free to reach out 😊

  <br><br>
  <strong>Email:</strong> guomingtang [at] hkust-gz [dot] edu [dot] cn

</div>


### <img src="../img/news.png" height="40px"> News

<ul style="margin-top: 10px; padding-left: 40px;">
  <li>May. 2025: <strong>LLM4NILM</strong>, the first study applying prompt-driven, general-purpose LLMs to NILM, is now available on <a href="https://arxiv.org/abs/2505.06330" target="_blank">arXiv</a>.</li>
  <li>May. 2025: Two papers got accepted to IEEE/ACM TON and IEEE TITS, respectively.</li>
  <li>Apr. 2025: <strong>ZSMerge</strong> (zero-shot KV Cache Compression for LLMs) is now available on <a href="https://arxiv.org/abs/2503.10714" target="_blank">arXiv</a> and open-sourced on <a href="https://github.com/SusCom-Lab/ZSMerge" target="_blank">GitHub</a>.</li>
  <li>Mar. 2025: <strong>GreenFL</strong> got accepted to ICDCS'25.</li>
  <li>Mar. 2025: Three papers got accepted to IEEE TIFS, TGCN and TVT, respectively.</li>
  <li>Nov. 2024: Our paper on real-world NILM system deployment won the <strong>Best Paper Award</strong> of SustainCom'24.</li>
  <li>Jun. 2024: Our work on <a href="https://dl.acm.org/doi/pdf/10.1145/3673038.3673080" target="_blank">low-carbon edge computing system</a> got accepted to ICPP'24.</li>

<div id="olderNews" style="display: none;">
  <li>Mar. 2024: One paper got accepted to IEEE TPDS.</li>
  <li>Jan. 2024: Two papers got accepted to IEEE Network and TMC, respectively.</li>
  <li>Dec. 2023: One Paper got accepted to IEEE TPDS.</li>
  <li>Nov. 2023: Two papers got accepted to IEEE TGCN and IoT-J, respectively.</li>
  <li>Aug. 2023: <a href="https://dl.acm.org/doi/epdf/10.1145/3617589" target="_blank">One survey paper</a> got accepted to ACM Computing Surveys.</li>
  <li>Aug. 2023: Three papers got accepted to IEEE IoT-J.</li>
  <li>May. 2023: One paper got accepted to ICDCS'23.</li>
  <li>May. 2023: <strong>FedNILM</strong> was published by IEEE TGCN.</li>
  <li>Apr. 2023: <strong>HyEdge</strong> got accepted to ACM TIOT.</li>
</div>

<a href="javascript:void(0)" onclick="toggleOlderNews()" style="color: #0066cc; text-decoration: none; font-weight: bold; display: inline-block; margin-top: 10px;">(More...)</a>

<script>
function toggleOlderNews() {
  var olderNews = document.getElementById('olderNews');
  var toggleLink = document.querySelector('a[onclick="toggleOlderNews()"]');
  
  if (olderNews.style.display === 'none') {
    olderNews.style.display = 'block';
    toggleLink.textContent = '(Less...)';
  } else {
    olderNews.style.display = 'none';
    toggleLink.textContent = '(More...)';
  }
}
</script>