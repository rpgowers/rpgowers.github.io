---
layout: page
title: Stochastic Distributed Synapses
description:
img: assets/img/v_dendrites.svg
importance: 2
category: research
---

Neurons are extensive cells with various branches radiating from the cell body.  Along the dendrites, neurons receive synaptic inputs from other cells of varying strength and at various different times.  The combined effect of this synaptic input across space and time causes the membrane potential of the cell to fluctuate.

Cortical pyramidal cells often fire at a low (< 5 Hz) rate with irregular intervals between spikes.  Such cells are considered to be in the "fluctuation-driven" regime and can be modelled as being driven by a stochastic process.

In this project, we looked at how the dendritic structure of neurons integrates spatiotemporal synaptic drive and what this entails for the firing-rate response.  

For further reading, a detailed treatment of this work can be found in my PhD thesis [Fluctuation-driven firing in spatially extended neuron models](http://wrap.warwick.ac.uk/148007/1/WRAP_Theses_Gowers_2019.pdf), while the results for the steady-state response can be found in the article [Low-rate firing limit for neurons with axon, soma and dendrites driven by spatially distributed stochastic synapses](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007175).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/upcross-curve-example.svg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The upcrossing rate of a particular threshold is greatest when the mean membrane potential is equal to that threshold.
</div>

A video of my ICMNS 2020 presentation on this topic can be found [here](https://www.youtube.com/live/Lsj57MvDttU?feature=share&t=9301).
