---
type: Product Visualization
skill: Modeling / Texturing / Lighting / Comp
software: Houdini
title: Fans visualization
year: 2024
shortname: 32_fans
uniquepage : true 
product: true
skip: true
---
<p>
    Client requested high quality videos of rotating fans.
</p>
<p>
    Fans needed multiple variations. Different materials for body and blade. Including light on/off options. In total some fans required up to 24 variations.

</p>
<p>
    Using Houdini Solaris I was able to build a system that was easy to manage 
    and make any adjustments for any particular fan/material configuration.
</p>
<p>
    I had to rebuild low quality CAD models into high resolution meshes 
    by using different workflows(remeshing, retopology, VDB conversion).
</p>
<p>
    I build a system to automatically assemble scene and position fan and camera correctly. Renders where separated into different layers. Compositing and FFmpeg conversion to .mov files was also done in Houdini.
</p>
<p>
    With this setup I was able to automate repetitive tasks and schedule render --> comp --> movie all in TOPs.
</p>

<p>Here are some fans:</p>
<a href="../assets/images/portfolio/32_fans/fans_mozaic_HQ.jpg">
    <img src="../assets/images/portfolio/32_fans/fans_mozaic_HQ.jpg" class="zoomportfolio img-fluid" alt="">
</a>

<p>
Here is single fan animation: 
</p>
<video width="690" height="313" autoplay loop muted>
    <source src="../assets/images/portfolio/32_fans/single_fan_preview.mp4" class="zoomportfolio img-fluid" alt="">
</video>

<p>Houdini Stage, this is where whole scene is setup:</p>
<img src="../assets/images/portfolio/32_fans/Houdini_Stage.png" class="zoomportfolio img-fluid" alt="">
<p>Houdini Comp, final image assembly happens here: </p>
<img src="../assets/images/portfolio/32_fans/Houdini_COPs.png" class="zoomportfolio img-fluid" alt="">
<p>Houdini TOPs, this is used to automate renders and comp jobs:</p>
<img src="../assets/images/portfolio/32_fans/Houdini_TOPs.png" class="zoomportfolio img-fluid" alt="">