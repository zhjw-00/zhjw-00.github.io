---
layout: page
title: Urbano
description: "<strong>2024 Fall - Present</strong><br><strong>Key Word:</strong> Mobility modelling and simulation in Rhino & Grasshopper"
img: assets/img/Urbano/Cover.jpg
importance: 1
category: RESEARCH
---
<div class="row">
    <div class="col-sm mb-3 mt-md-0">
        <strong>Supervisor:</strong> Timur Dogan, Yang Yang
    </div>
</div>

<h2 style="font-size: 1.2em;"><strong>Overview</strong></h2>
<p><strong>Urbano</strong> is a research platform developed at Cornell University’s College of Architecture, Art, and Planning under the supervision of Prof. Timur Dogan. The project integrates behavioral modeling, spatial data analysis, and environmental simulation into a unified framework for data-driven urban mobility prediction. </p>
<p>The platform aims to bridge the gap between human behavior modeling and architectural and urban design tools, enabling interpretable, cross-scale simulation of mobility and environmental performance.</p>
You can learn more about the Urbano research platform on [Urbano's official website](https://urbano.io/).

<h2 style="font-size: 1.2em;"><strong>My Role & Contribution</strong></h2>
<p>I joined the group since Nov 2024, contributed to Urbano's development through model optimization, tool enchancement and validation workflow design</p>
<h3 style="font-size: 1em;"><strong>Modeling</strong></h3>
Redesigned and retrained the five behavioral models to include demographic featrues, trip features, climate-related features, improving environmental sensitivity and expanding coverage to seven U.S. states(AZ, CA, GA, IA, NY, OK, WI).
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Urbano/ModelTraining.jpg" title="Model Training Pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Model Training Pipeline
</div>
<h3 style="font-size: 1em;"><strong>Tool Development</strong></h3>
Developed and optimized Grasshopper components including ImportTerrain, DownloadClimateData, and SimulationConfig, automating terrain retrieval, projection, and weather data integration.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Urbano/ImportGeometries.jpg" title="ImportGeometries" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Urbano/Rhino_ImportGeometries.jpg" title="ImportGeometries" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Import Geometries Preview
</div>
<h3 style="font-size: 1em;"><strong>Validation</strong></h3>
Built a multi-run statistical framework for model testing, automating the comparison between simulated and recorded mobility distributions.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Urbano/validation_log.jpg" title="validation_log" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    validation Record
</div>