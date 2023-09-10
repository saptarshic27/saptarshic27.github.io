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
  I'm Anirban, a Ph.D. candidate in Statistics at The Wharton School, University of Pennsylvania advised by Dr. Bhaswar Bhattacharya. My academic voyage commenced at the Indian Statistical Institute, Kolkata, where I earned both my Bachelor of Statistics and Master of Statistics degrees. These formative years equipped me with with a strong mathematical foundation to explore the depths of statistical theory and its real-world applications.


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
