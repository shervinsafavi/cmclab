---
title: Research
nav:
  order: 1
  tooltip: Research in the lab
---

# Research

The overarching research theme of our lab is understanding the computational machinery of cognitive processes. Cognition spans a wide range of functions (from perception to planning), and it is one of the most remarkable capabilities of the brain. 
In CMC lab we want to understand the computations underlying cognitive processes, 
and the biophysical machinery that implement these computations.
Imagine we go to a restaurant and want to order a dish. 
For such decisions brain needs to take into account several factors: 
_how much we like each option_, 
_how much we want to explore new stuff_, 
_how pricey they are_, ... .
There is much computation going on in our brain to sort out each of those questions.
And, at the end, all is happening in a piece of wet machinery (brain).
We want to understand how our brain does those computations and how they are implemented (biophysics of computations).

{% capture sumLabResMeth %}
We do normative and biophysical modeling (to ideally combine them) to understand the cognitive functions (we chose perceptual decisions as our starting point); we will test these models with neural and behavioral data (in collaboration with experimental labs); and we will develop machine learning methods for multi- and cross-scale analysis of neural data to better capture the neural markers of underlying cognitive (sub-)processes and ultimately connect them to underlying computations. 
{% endcapture %}

{%
  include alert.html
  type="info"
  content=sumLabResMeth
%}
	

## Computational machinery of perceptual decision-making (CMPD)
## Neural events as markers of cognitive processes (NEMC)

Neural events are characteristics, transient, coordinated, neural activities that we can identify them in aggregated signals (e.g., local field potentials or LFPs). 
It has been shown some neural events have signature across several scales (neurons, neural populations, and large-scale networks). 
Moreover, they are also closely connected to behavior;
for instance Sharp-Wave Ripples is one of the most studied neural events and, over two decades, it has been shown they are involved in everything from memory consolidation to offline and online planning. 
We want to use them as accessible neural markers of cognitive processes, 
that likely shed light on behaviorally relevant coordination mechanisms in the brain.

{::options parse_block_html="true" /}

<details  style="text-align: left;">
<summary markdown="span">Read more:</summary>

key gaps that we are trying to fill are the following: 
1. How we can detect neural events in data reliably? Thus, we will develop unsupervised machine learning methods to identify neural events.
2. If and how neural events are coupled to behavior? Thus we will use our method(s) to investigate the occurrence of different kinds of neural events in variety of behavioral task.
3. How rich multi-scale dynamics of neural event support the behavior? Thus, we will characterize the multi-scale signature of neural events (e.g., how different brain regions interact/communicate during each event) during variety of behavioral task.

</details>
<br/>

{::options parse_block_html="false" /}

## Criticality in functional and dysfunctional neural systems (CFDN)
## Hybrid neural networks for cognitive neuroscience (HNNC)

Artificial neural network (ANN) have been influential for understanding the neural computations, 
however they suffer from biological plausibility. 
This is a key caveat when we want to use them to understand the computational machinery of cognitive process. 
We will exploit the  capacity of ANN for implementing different kinds of computations and hybrid them as much as possible with biological neural networks.
This will let us to have the goodness of both worlds.


# Highlighted

{% include citation.html lookup="Multistability, perceptual value, and internal foraging" style="rich" %}


{% include section.html %}


{% include button.html text="See our publications" link="publications" style="button" %}

