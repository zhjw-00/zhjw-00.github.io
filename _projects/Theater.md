---
layout: page
title: THEIRter
description: "<strong>2024 Spring</strong><br><strong>Key Word:</strong> Theater Design; Geometry Panalization; Grasshopper-based design"
img: assets/img/Theater/ExteriorRender.jpg
importance: 4
category: ARCHITECTURE
related_publications: False
---

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width. -->

<!-- To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->

<style>
.page-content, .post-content {
  text-align: justify;
  text-justify: inter-word;
}
</style>

<div class="row">
    <div class="col-sm mb-3 mt-md-0">
        <strong>Supervisor:</strong> Carl D’Apolito-Dworkin
    </div>
    <div class="col-sm mb-3 mt-md-0">
        <strong>Collaborator:</strong> Junhan Wu
    </div>
</div>

<p>The topic for this studio is to figure out how to get geometry involved in a theater design. And using panelization to resolve the irregular curve surfaces makes it easier to calculate and build in practice.</p>
<p>The site is in a small and quiet community in east Boston near the water. After site trip and interviews with the residents there, it seems like live performance nowadays seems to be too high art for people to appreciate compared to internet media.</p>
<p>After we come back we have been thinking about what can we do for them by doing a theater. Or do they really need a typical theater and professional drama? The answer may be no. Then the thoughts came to our mind: “Maybe it could be a park!” We decided to build a weird theater that opens to everyone, which is very different from a typical theater like this. These theaters have similar auditoriums surrounded by circulation and dressing rooms and then covered by a shell, a façade.</p>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Theater/Prototype-01.jpg" title="Prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Surface Prototype combination Experiment
</div>
<p>The intention of creating openess made us choose this geometry prototype.</p>
To generate one surface, we need two spiral curves, loft them to get a surface, and then use a box to cut it. Then what happens is this surface can be copied and piled up in 3 dimensions. What feature does this kind of geometry have?
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Theater/Prototype-02.jpg" title="Prototype adapted on theater structure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Prototype adapted on theater structure
</div>
<p>First, it is endless, it won’t create any closed spaces that wrap around the theater. Also, due to the characteristics of the prototype, surfaces join the facade and floors, stairs naturally, which means the surfaces will make up not only the façade but also the whole building.</p>
The next thing we need to focus on is how to use panelization to resolve the geometry, forming the space in theater. We figured out two types of panelization that can be used in this project. In our project, two panelizations construct different functions. The first one is diamond panelization, this type has two uses, one is to build the surface outside and another one is to be transformed into boxes to inhabit people, for example, the café and boxes in the auditorium. Another type is the folded plane, which is used to form transportation spaces.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Theater/Prototype-03.jpg" title="Prototype adapted on theater structure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    two types of panelization mode
</div>
The auditorium is designed following the surface, spiraling up. At the bottom of the theater, we extracted the isocurves of the surface and used folded planes to create the way going up. For the upper half, since the isocurves begin to make the audience face outside and deconcentrated, we used diamond panels to make boxes to make people stay, and people get into boxes from the gaps which is the thickness created by two different panelized surfaces.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Theater/ExperimentModel-01.jpg" title="Experiment Model" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Theater/ExperimentModel-02.jpg" title="Experiment Model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Experimental Structure Model
</div>
<p>To make the structure strong enough to hold the building, straight-shaped beams are needed. It is better than those beams in polyline shape in terms of shear force. What is really nice about the surface is this prototype has straight isocurves that gather at one point although at different heights. We took this as structure. After the midterm, we merged some of those panels at the center with the beams in the same planer surface to hold different parts tighter. This structure system constrained us a lot but also provided us with opportunities.</p>
If we make all the creases and edges of surfaces aligned with structures, bounding tightly to the surface, the structure design can be coordinate with space form. Since both sides are using the same structural language, the building can keep a subtle balance itself. Once everything aligned up, the structure provided nice strength for our building.
<div class="row">
    <div class="row">
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="assets/img/Theater/FinalModel-01.jpg" title="Final Model" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="row">
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="assets/img/Theater/FinalModel-02.jpg" title="Final Model" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="assets/img/Theater/FinalModel-03.jpg" title="Final Model" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="assets/img/Theater/FinalModel-04.jpg" title="Final Model" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
</div>
<div class="caption">
    Final Model
</div>

<div class="row justify-content-sm-center">
    <div class="row">
        <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="assets/img/Theater/ExteriorRender.jpg" title="Exterior Render" class="img-fluid rounded z-depth-1" %}
            <div class="caption">
                Exterior Render
            </div>
        </div>
    </div>    
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Theater/InteriorRender.jpg" title="Interior Render" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Interior Render
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Theater/TheaterRender.jpg" title="Theater Render" class="img-fluid rounded z-depth-1" %}
        <div class="caption">
            Theater Render
        </div>
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Theater/plan1.jpg" title="Plan" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Theater/plan2.jpg" title="Plan" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Theater/Plan3&4.jpg" title="Plan" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Plans
</div>
