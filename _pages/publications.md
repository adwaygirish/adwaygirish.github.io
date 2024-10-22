---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- Link container for switching between views -->
<div class="link-container">
  <a href="javascript:void(0)" id="chronologicalLink" class="toggle-link selected-link" onclick="showView('chronological', this)">[Chronological Order]</a>|
  <a href="javascript:void(0)" id="areaLink" class="toggle-link" onclick="showView('area', this)">[Separated by Area]</a>
</div>

<!-- Chronological Order Section -->
<div id="chronological" class="view-section active">
{{"

### *Preprints/In preparation.*

—

### *Conference proceedings/Workshop papers.*
" | markdownify }}
  <ol reversed>
   <li> {{ " 

**Fundamental Limits of Prompt Compression: A Rate-Distortion Framework for Black-Box Language Models** \[[arXiv](#)\]\
*Alliot Nagle\*, **A. G.**\*, Marco Bondaschi, Michael Gastpar, Ashok Vardhan Makkuva, Hyeji Kim*\
NeurIPS 2024\
Also at ICML 2024 Workshop on Theoretical Foundations of Foundation Models (TF2M) \[Oral (top 4 out of 58)\] 

    " | markdownify }}
  </li> 
  <li>
    {{ " 

**Local to Global: Learning Dynamics and Effect of Initialization for Transformers** \[[arXiv](#)\]\
*Ashok Vardhan Makkuva\*, Marco Bondaschi\*, Chanakya Ekbote, **A. G.**, Alliot Nagle, Hyeji Kim, Michael Gastpar*\
NeurIPS 2024\
Also at ICML 2024 Workshop on Theoretical Foundations of Foundation Models (TF2M) 

    " | markdownify }}
  </li>
  <li>
    {{ " 

**Attention with Markov: A Framework for Principled Analysis of Transformers via Markov Chains** \[[arXiv](#)\]\
*Ashok Vardhan Makkuva\*, Marco Bondaschi\*, **A. G.**, Alliot Nagle,  Martin Jaggi, Hyeji Kim, Michael Gastpar*\
ICML 2024 Workshop on Mechanistic Interpretability (MI) 

    " | markdownify }}
  </li>
  <li>
    {{ " **ICQ: A Quantization Scheme for Best-Arm Identification Over Bit-Constrained Channels** \[[IEEE Xplore](#)\] \[[arXiv](#)\]\
    *Fathima Z. Faizal, **A. G.**, Manjesh K. Hanawal, Nikhil Karamchandani*\
    WiOpt (International Symposium on Modeling and Optimization in Mobile, Ad hoc, and Wireless Networks) 2023 " | markdownify }}
  </li>
  <li>
    {{ " **Micro-Doppler Parameter Estimation Using Variational Mode Decomposition With Finite Rate of Innovation** \[[IEEE Xplore](#)\]\
    *Shrikant Sharma, **A. G.**, Darin Jeff, Garweet Sresth, Sanket Bhalerao, Vikram M. Gadre, C. H. Srinivas Rao, P. Radhakrishna*\
    SPCOM (IEEE International Conference on Signal Processing and Communications) 2022  " | markdownify }}
  </li>
  <li>
    {{ " **Theoretical Analysis of an Inverse Radon Transform Based Multicomponent Micro-Doppler Parameter Estimation Algorithm** \[[IEEE Xplore](#)\]\
    *Shrikant Sharma, **A. G.**, Nikhar P. Rakhashia, Vikram M. Gadre, Shaan ul Haque, Aseer Ansari, Ram Bilas Pachori,
P. Radhakrishna, Peeyush Sahay*\
    NCC (National Conference on Communications) 2022 " | markdownify }}
  </li>
</ol>
</div>

<!-- Separated by Area Section -->
<div id="area" class="view-section">
{{"

### *Machine learning (Transformers/LLMs, bandits; 2022--24).*

" | markdownify }}

  <ol reversed>
   <li> {{ " 

**Fundamental Limits of Prompt Compression: A Rate-Distortion Framework for Black-Box Language Models** \[[arXiv](#)\]\
*Alliot Nagle\*, **A. G.**\*, Marco Bondaschi, Michael Gastpar, Ashok Vardhan Makkuva, Hyeji Kim*\
NeurIPS 2024\
Also at ICML 2024 Workshop on Theoretical Foundations of Foundation Models (TF2M) \[Oral (top 4 out of 58)\] 

    " | markdownify }}
  </li> 
  <li>
    {{ " 

**Local to Global: Learning Dynamics and Effect of Initialization for Transformers** \[[arXiv](#)\]\
*Ashok Vardhan Makkuva\*, Marco Bondaschi\*, Chanakya Ekbote, **A. G.**, Alliot Nagle, Hyeji Kim, Michael Gastpar*\
NeurIPS 2024\
Also at ICML 2024 Workshop on Theoretical Foundations of Foundation Models (TF2M) 

    " | markdownify }}
  </li>
  <li>
    {{ " 

**Attention with Markov: A Framework for Principled Analysis of Transformers via Markov Chains** \[[arXiv](#)\]\
*Ashok Vardhan Makkuva\*, Marco Bondaschi\*, **A. G.**, Alliot Nagle,  Martin Jaggi, Hyeji Kim, Michael Gastpar*\
ICML 2024 Workshop on Mechanistic Interpretability (MI) 

    " | markdownify }}
  </li>
  <li>
    {{ " **ICQ: A Quantization Scheme for Best-Arm Identification Over Bit-Constrained Channels** \[[IEEE Xplore](#)\] \[[arXiv](#)\]\
    *Fathima Z. Faizal, **A. G.**, Manjesh K. Hanawal, Nikhil Karamchandani*\
    WiOpt (International Symposium on Modeling and Optimization in Mobile, Ad hoc, and Wireless Networks) 2023 " | markdownify }}
  </li>
</ol>
{{"

### *Conference proceedings/Workshop papers.*
" | markdownify }}

  <ol reversed>
  <li>
    {{ " **Micro-Doppler Parameter Estimation Using Variational Mode Decomposition With Finite Rate of Innovation** \[[IEEE Xplore](#)\]\
    *Shrikant Sharma, **A. G.**, Darin Jeff, Garweet Sresth, Sanket Bhalerao, Vikram M. Gadre, C. H. Srinivas Rao, P. Radhakrishna*\
    SPCOM (IEEE International Conference on Signal Processing and Communications) 2022  " | markdownify }}
  </li>
  <li>
    {{ " **Theoretical Analysis of an Inverse Radon Transform Based Multicomponent Micro-Doppler Parameter Estimation Algorithm** \[[IEEE Xplore](#)\]\
    *Shrikant Sharma, **A. G.**, Nikhar P. Rakhashia, Vikram M. Gadre, Shaan ul Haque, Aseer Ansari, Ram Bilas Pachori,
P. Radhakrishna, Peeyush Sahay*\
    NCC (National Conference on Communications) 2022 " | markdownify }}
  </li>
</ol>
</div>

<script>
  function showView(view, link) {
    // Hide all sections
    document.getElementById('chronological').classList.remove('active');
    document.getElementById('area').classList.remove('active');
    
    // Show the selected section
    document.getElementById(view).classList.add('active');

    // Remove selected-link class from all links
    document.getElementById('chronologicalLink').classList.remove('selected-link');
    document.getElementById('areaLink').classList.remove('selected-link');
    
    // Add selected-link class to the clicked link
    link.classList.add('selected-link');
  }
  // Dynamically set the starting number for the reversed list
  window.onload = function() {
    var publicationList = document.getElementById('publicationList');
    var numItems = publicationList.getElementsByTagName('li').length;
    publicationList.setAttribute('start', numItems);  // Set the 'start' attribute to the number of items
  };
</script>

<style>
  .view-section {
    display: none;
  }
  .active {
    display: block;
  }
  
  .link-container {
    margin-bottom: 20px;
  }

  .toggle-link {
    text-decoration: none;
    color: #007BFF;
    cursor: pointer;
    margin-right: 10px;
  }

  .toggle-link:hover {
    text-decoration: underline;
  }

  .selected-link {
    font-weight: bold;
    text-decoration: underline;
  }
</style>
