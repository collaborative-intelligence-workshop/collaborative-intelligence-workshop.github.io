+++
title = "Collaborative Intelligence: New Horizons in Shared Autonomy"
+++

# Abstract

Our proposed workshop will explore the latest advances, challenges, and opportunities in human-robot collaboration where control is shared between human operators and autonomous systems. The workshop will focus on three themes: (1) adaptive manipulation, (2) intelligent mobility, and (3) human-centric interfaces, encompassing both foundational research and cutting-edge applications. By examining emerging technologies, user interface strategies, evaluation metrics, and ethical considerations, the workshop aims to foster a deeper understanding of how best to combine human insight and machine capabilities for real-world impact. We welcome a diverse range of participants, including academic researchers, industry practitioners, graduate students, and policymakers with an interest in shared autonomy. 

{{ new_block() }}



# Speakers

{{ grid(
    text = [
        ["Roman Garnett","Washington University in St. Louis and Uber"], 
        ["Jacob R. Gardner","University of Pennsylvania"],
        ["Virginia Aglietti","Google DeepMind"],
        ["Esther Rolf","University of Colorado Boulder"],
        ["Mark van der Wilk","University of Oxford"],
    ],
    urls = [
        "https://www.cse.wustl.edu/~garnett/",
        "https://jacobrgardner.github.io",
        "https://virgiagl.github.io/",
        "https://estherrolf.com",
        "https://mvdw.uk",
    ],
    image_dir = "speakers",
    narrow = true) }}



{{ new_block() }}



# Schedule

| Time (Canada) | Event |
|---------------|-------|
| 09:00 - 09:30 | **Introduction and Opening Remarks: Andreas Krause** {{ small_button(name = 'slides', url = 'slides/krause.pdf') }} |
| 09:30 - 10:00 | Invited Talk: Mark van der Wilk - _Open Problems in Gaussian Process Approximation and Benchmarking_  {{ small_button(name = 'slides', url = 'slides/vanderwilk.pdf') }} |
| 10:00 - 10:30 | **Discussion Break** |
| 10:30 - 11:00 | Invited Talk: Esther Rolf - _We need to talk (more) about uncertainty in geospatial machine learning_ {{ small_button(name = 'slides', url = 'slides/rolf.pdf') }} |
| 11:00 - 11:10 | Contributed Talk: Mathieu Alain - _Graph Classification Gaussian Processes via Hodgelet Spectral Features_ |
| 11:10 - 11:20 | Contributed Talk: Taiwo Adebiyi - _Gaussian Process Thompson Sampling via Rootfinding_ |
| 11:20 - 11:30 | Contributed Talk: Freddie Bickford Smith - _Rethinking Aleatoric and Epistemic Uncertainty_ |
| 11:30 - 12:30 | **Lunch and Poster Session Setup** |
| 12:30 - 12:40 | Contributed Talk: Patrick O'Hara - _Distributionally Robust Optimisation with Bayesian Ambiguity Sets_ |
| 12:40 - 12:50 | Contributed Talk: Joachim Schaeffer - _Lithium-Ion Battery System Health Monitoring and Resistance-Based Fault Analysis from Field Data Using Recursive Spatiotemporal Gaussian Processes_ |
| 12:50 - 13:00 | Contributed Talk: Rafael Oliveira - _Variational Search Distributions_ |
| 13:00 - 13:30 | Invited Talk: Roman Garnett - _What I learned while writing the BayesOpt book_ {{ small_button(name = 'slides', url = 'slides/garnett.pdf') }} |
| 13:30 - 14:00 | **Discussion Break** |
| 14:00 - 14:30 | Invited Talk: Jacob R. Garnder - _Bayesian optimization needs better deep learning_ {{ small_button(name = 'slides', url = 'slides/gardner.pdf') }} |
| 14:30 - 15:00 | Lightning Talks: Joshua Hang Sai Ip, Yibo Jiang, Dingyang Chen, Guiomar Pescador-Barrios, Sebastian W. Ober, Conor Heins, Richard Bergna, Martin Trapp |
| 15:00 - 16:00 | **Poster Session** |
| 16:00 - 16:30 | Invited Talk: Virginia Aglietti - _FunBO: Discovering Acquisition Functions for Bayesian Optimization with FunSearch_ {{ small_button(name = 'slides', url = 'slides/aglietti.pdf') }} |
| 16:30 - 17:25 | **Panel Discussion** | 
| 17:25 - 17:30 | **Closing Remarks** |



{{ new_block() }}



# Organizers


{{ grid(
    text = [
        ["Yuchen Cui","UCLA"],
        ["Raayan Dhar","UCLA"],
        ["Xu (Kristen) Yan","UCLA"],
        ["Zhenghao Peng","UCLA"],
        ["Priya Sundaresan","Stanford"],
        ["Huihan Liu","UT Austin"],
        ["Bolei Zhou","UCLA"],
        ["Yuke Zhu","UT Austin"],
    ],
    urls = [
        "https://yuchencui.cc/",
        "https://raayandhar.github.io/",
        "https://seas.ucla.edu/~kao/people_dir/xu_yan.html",
        "https://pengzhenghao.github.io/",
        "https://priyasundaresan.github.io/",
        "https://huihanl.github.io/",
        "https://boleizhou.github.io/",
        "https://yukezhu.me/",
    ],
    image_dir = "organizers") }}



{{ new_block() }}



# Advisory Committee

{{ grid(
    text = [
        ["Eytan Bakshy","Meta"],
        ["David Bindel","Cornell University"],
        ["Tamara Broderick","MIT"],
        ["Carl Henrik Ek","University of Cambridge"],
        ["Seth Flaxman","University of Oxford"],
        ["Emtiyaz Khan","RIKEN"],
        ["Andreas Krause","ETH Zürich"],
        ["Jasper Snoek","Google DeepMind"],
    ],
    urls = [
        "https://eytan.github.io",
        "https://www.cs.cornell.edu/~bindel/",
        "https://tamarabroderick.com/",
        "http://carlhenrik.com/",
        "https://sethrf.com/",
        "https://emtiyaz.github.io/",
        "https://las.inf.ethz.ch/krausea",
        "https://research.google/people/jasper-snoek/",
    ],
    image_dir = "advisors") }}



{{ new_block() }}



# Sponsors

{{ grid(
    text = [
        ["Google Research"],
        ["Meta"],
    ],
    urls = [
        "https://research.google/",
        "https://ai.meta.com/",
    ],
    images = [
        "sponsors/google-research.svg",
        "sponsors/meta.svg"
    ],
    dark_invert = [
        false,
        true
    ]) }}



{{ new_block() }}


# Accepted Workshop Papers

{{ table(
    data = "papers.csv", 
    columns = ["Title","Authors"],
    button_names = ["paper"], 
    button_data_columns = [2], 
    button_output_columns = [1]) }}