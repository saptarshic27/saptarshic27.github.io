---
layout: about
title: "About me"
math: false
hide_title: true
---


<!-- Wrap your content in a container div -->
<div class="content-container">

  <div class="text-container">
  <!-- Add your text inside a paragraph -->
  <p>
  I am a post-doc at CEA Saclay, where I use machine learning / deep learning methods to analyze processes that happen at the atomic scale 🔬 in metals: 
  defects formation, thermally activated process, phase transformations, materials evolution in environment, ... 

  For this, I currently develop efficient atomic descriptors and machine-learning (ML) force-fields, together with [Mihai-Cosmin Marinica](https://scholar.google.com/citations?user=Yfj9RqUAAAAJ&hl=en) and [Alexandra M. Goryaeva](https://scholar.google.fr/citations?user=3VPSML8AAAAJ&hl=en).

  I intensively use massively parallel computational methods such as molecular dynamics to study solid state physics problems at different scales, using both classical and ML-based methods.
  An example is the [simulation of plasticity in metals](https://doi.org/10.1103/PhysRevMaterials.6.013608), which is mediated by dislocation motion --actually the subject of [my thesis](https://theses.hal.science/tel-03728547).

  For my PhD, I worked with David Rodney (Univ. Lyon), Michel Perez (INSA) and Fabienne Ribeiro (IRSN) on the [depinning of dislocations from interstitial solutes](https://doi.org/10.1103/PhysRevMaterials.6.013608), introducing a new [potential for Fe-C](https://github.com/arn-all/FeC-EAM-potential). 
  I defended in Dec. 2021 at Université de Lyon--UCBL.

  </p>
  </div>
    <!-- Add the image and give it a class for styling -->
  <img class="side-image" src="/images/mountains.jpeg" alt="" />

</div>

<!-- Add a style tag with CSS to control the layout -->
<style>
  .content-container {
    display: flex;
    align-items: flex-start;
  }
  .text-container {
    flex-grow: 1;
  }

  .side-image {
    margin-top: 50px;
    margin-left: 20px; /* Adjust the space between the image and the text */
    max-width: 40%; /* Adjust the width of the image */
    border-radius: 2%; /* Make the image circular */
    overflow: hidden; /* Hide anything outside of the circle */
  }

  /* Responsive design for smaller screens */
  @media (max-width: 768px) {
    .side-image {
      max-width: 100%;
      margin-left: 0;
      margin-bottom: 20px;
    }

    .content-container {
      flex-direction: column;
    }
  }
</style>
