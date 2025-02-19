---
type: Product Visualization
skill: Modeling / Texturing / Lighting / Comp
software: Houdini
title: Sofa visualization
year: 2024
shortname: 31_sofas
uniquepage : true 
product: true
---
<p>
    Client requested high quality images for whole line of sofas.
</p>
<p>
    Each sofa needed multiple variations. In total 28(sofas) * 15(colors) * 6(angles) = 2520 images.
    Some sofas also required different variations to show how mechanism works.
</p>
<p>
    Usually these renders would be a big and complicated task, 
    but using Houdini Solaris I was able to build a system that was easy to manage 
    and make any adjustments for any particular sofa/angle/color configuration.
</p>
<p>
    I had to rebuild low quality CAD models into high resolution meshes 
    by using different workflows(remeshing, retopology, VDB conversion and vellum simulation).
</p>
<p>
    I build a  system to automatically assemble scene and center camera 
    around sofa with proper parameters for each camera angle. 
</p>
<p>
    With this setup I was able to output properly organized and named files.
</p>
<p>
    I was able to optimize render times by rendering unique part of the image only once and combining all parts in compositing.
</p>

<p>Here are sofas with the same color and angle:</p>
<a href="../assets/images/portfolio/31_sofas/sofas_mozaic.jpg">
    <img src="../assets/images/portfolio/31_sofas/sofas_mozaic.jpg" class="zoomportfolio img-fluid" alt="">
</a>
<p> Let's look at few angles for single sofa in full resolution: </p>
<a href="../assets/images/portfolio/31_sofas/sofa_example_far.jpeg">
    <img src="../assets/images/portfolio/31_sofas/sofa_example_far.jpeg" class="zoomportfolio img-fluid" alt="">
</a>
<a href="../assets/images/portfolio/31_sofas/sofa_example_side.jpeg">
    <img src="../assets/images/portfolio/31_sofas/sofa_example_side.jpeg" class="zoomportfolio img-fluid" alt="">
</a>
<a href="../assets/images/portfolio/31_sofas/sofa_example_closeup.jpeg">
    <img src="../assets/images/portfolio/31_sofas/sofa_example_closeup.jpeg" class="zoomportfolio img-fluid" alt="">
</a>
<p> Here are all possible variations for single sofa: </p>

<a href="../assets/images/portfolio/31_sofas/sofa_single_mozaic.jpg">
    <img src="../assets/images/portfolio/31_sofas/sofa_single_mozaic.jpg" class="zoomportfolio img-fluid" alt="">
</a>

<p>
Example of switching between different models, camera angles and sets: 
</p>
<video width="690" height="690" controls>
    <source src="../assets/images/portfolio/31_sofas/houdini_Variations.mp4" class="zoomportfolio img-fluid" alt="">
</video>

<p>Houdini Stage, this is where whole scene is setup:</p>
<img src="../assets/images/portfolio/31_sofas/HoudiniStage.png" class="zoomportfolio img-fluid" alt="">
<p>Houdini Comp, final image assembly happens here: </p>
<img src="../assets/images/portfolio/31_sofas/HoudiniComp.png" class="zoomportfolio img-fluid" alt="">
<p>Houdini TOPs, this is used to automate renders and comp jobs:</p>
<img src="../assets/images/portfolio/31_sofas/HoudiniTOPs.png" class="zoomportfolio img-fluid" alt="">



<p>I also rendered top view for each sofa, so that it can be used in dimensions image: </p>
<img src="../assets/images/portfolio/31_sofas/dimensions_example.jpg" class="zoomportfolio img-fluid" alt="">