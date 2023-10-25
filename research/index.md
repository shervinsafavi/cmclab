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
_how much we want to explore new options_, 
_how pricey they are_, ... .
There is much computation going on in our brain to sort out each of those questions.
And, at the end, all is happening in a piece of wet machinery (brain).
We want to understand how our brain does those computations and how they are implemented (biophysics of computations).

{% capture sumLabResMeth %}
We do normative and biophysical modeling (with the goal of combining them) to understand the cognitive functions; we will test these models with neural and behavioral data (in collaboration with experimental labs); and we will develop machine learning methods for multi- and cross-scale analysis of neural data to first better understand the multi-scale machinary of the brain, and second better capture the neural markers of underlying cognitive (sub-)processes and ultimately connect them to underlying computations. 
{% endcapture %}

{%
  include alert.html
  type="info"
  content=sumLabResMeth
%}
	

## Computational machinery of perceptual decision-making (CMPD)

We want develop *functional* multi-scale models of decision processes,
which is a key aspect of information processing. 
We will start this development from *perceptual multistability* (phenomena like Necker cube
and binocular rivalry), that is also a form of perceptual decision. 

{::options parse_block_html="true" /}
<details  style="text-align: left;">
<summary markdown="span">Read more:</summary>

We chose perceptual multistability as our starting point due to
its multi-faceted richness:

1. It is an evolutionary-preserved phenomenon.
2. It is studied across several levels of organization (from genes to brain
networks).
3. It is a rich task to understand different aspects of neural
computaitons. This includes, perceptual inference and we recently showed it is
*also* a rich task for understanding value-based decision-making, and even cognitive control.
4. It is broadly applicable across many species, from Drosophila to human, as well as across different sensory modalities.

Furthermore, perceptual multistability is also important from a
psychiatric perspective, as it has been found to differ in a wide range
of psychiatric conditions (e. g., differences in the rate of perceptual
switches), 
So, we believe studying this phenomenon has great potential
for gaining an integrative insight into a wide range of neural functions
and dysfunctions.

</details>
{::options parse_block_html="false" /}

### Highlighted paper of the research program
{% include citation.html lookup="Multistability, perceptual value, and internal foraging" style="rich" %}

{% capture nemcPaps %}
Check [here]({{ site.baseurl }}/publications/?search=%22tag:%20cognition%22) for more papers from CMC lab on this research program.
{% endcapture %}

{%
  include alert.html
  type="info"
  content=nemcPaps
%}

## Multi-scale analysis of neural and behavioral data (MNBD)

We start this research program from _Neural events_. Neural events are characteristics, transient, coordinated, neural activities that we can identify them in aggregated signals (e.g., local field potentials or LFPs). 
We want to use them as accessible neural markers of cognitive processes, 
that likely shed light on behaviorally relevant coordination mechanisms in the brain.

{::options parse_block_html="true" /}
<details  style="text-align: left;">
<summary markdown="span">Read more:</summary>

It has been shown some neural events have signature across several scales (neurons, neural populations, and large-scale networks). 
Moreover, they are also closely connected to behavior;
for instance Sharp-Wave Ripples is one of the most studied neural events and, over two decades, it has been shown they are involved in everything from memory consolidation to offline and online planning. 
We want to use them as accessible neural markers of cognitive processes, 
that likely shed light on behaviorally relevant coordination mechanisms in the brain.


key gaps that we are trying to fill are the following: 
1. How we can detect neural events in data reliably? Thus, we will develop unsupervised machine learning methods to identify neural events.
2. If and how neural events are coupled to behavior? Thus we will use our method(s) to investigate the occurrence of different kinds of neural events in variety of behavioral task.
3. How rich multi-scale dynamics of neural event support the behavior? Thus, we will characterize the multi-scale signature of neural events (e.g., how different brain regions interact/communicate during each event) during variety of behavioral task.

</details>
{::options parse_block_html="false" /}

### Highlighted paper of the research program
{% include citation.html lookup="Generalized Phase Locking Analysis" style="rich" %}

{% capture nemcPaps %}
Check [here]({{ site.baseurl }}/publications/?search=%22tag:%20cognition%22) for more papers from CMC lab on this research program.
{% endcapture %}

{%
  include alert.html
  type="info"
  content=nemcPaps
%}



## Criticality in functional and dysfunctional neural systems (CFDN)

We will use *"brain criticality hypothesis"* which has the potential of bridging
multi-scale neural dynamics to
*basic* information processing capabilities, as well as behavior.

{::options parse_block_html="true" /}
<details  style="text-align: left;">
<summary markdown="span">Read more:</summary>

Crudely speaking, this
hypothesis states that the brain operates close to the *edge of
instability* (e.g., a sweet spot between over-synchronization and random
activity). Operating in this regime explains some key features of neural
dynamics that are particularly important for a multi-scale description
of the brain (e. g., scale-freeness). Furthermore, criticality has been
suggested to be an optimized regime for information processing.

We extend the previous line of research in
two directions. 
1. Extend it to a broader range of information processing and other biologically relevant neuronal networks.
2. We investigate if deviation from the critical state occurs in psychiatric disorders. 

</details>
<!-- <br/> -->
{::options parse_block_html="false" /}

### Highlighted paper of the research program
{% include citation.html lookup="Signatures of criticality in efficient coding networks" style="rich" %}

{% capture nemcPaps %}
Check [here]({{ site.baseurl }}/publications/?search=%22tag:%20cognition%22) for more papers from CMC lab on this research program.
{% endcapture %}

{%
  include alert.html
  type="info"
  content=nemcPaps
%}

## Hybrid neural networks for cognitive neuroscience (HNNC)

Artificial neural network (ANN) have been influential for understanding the neural computations, 
however they suffer from biological plausibility. 
This is a key caveat when we want to use them to understand the computational machinery of cognitive process. 

{::options parse_block_html="true" /}
<details  style="text-align: left;">
<summary markdown="span">Read more:</summary>

We will exploit the  capacity of ANN for implementing different kinds of computations and hybrid them as much as possible with biological neural networks.
This will let us to have the goodness of both worlds.


</details>
{::options parse_block_html="false" /}


