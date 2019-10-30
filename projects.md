---
layout: page
title: Projects
---

## Physics

### Scattering Amplitude Approximation

<p style="text-align: justify; font-size: 0.8em">


<kbd><img style="float: right;" width="200" height="200" src="https://josephpb.github.io/images/Higgs.jpg"></kbd>
In particle physics collider experiments, such as at CERN, particles are smashed together at nearly the speed of light. Understanding how these particles interact, and scatter to form other particles is crucial for better picking apart these complex collisions in which billions of particles collide every second. To understand how two particles my scatter the *scattering amplitude* is calculated and integrated over the whole possible phase space of the outgoing particles giving the total *cross section* (a measure of the likelihood of two particles interacting in a certain way) for the event. Simulating and calculating these processes is extremely computationally expensive so we use Machine Learning to approximate the scattering amplitude function which, once learn, is considerably faster to query than the original computation.

</p>

## Humanitarian

### Refugee Camp Mapping

<div style="text-align: justify">

Refugee camps can be highly dynamical and constantly experience a state of flux. In order to understand their extend, populations and density, UNOSAT are regularly requested to produce maps of the camps from satellite imagery. This is vital work and provides and essential source of information for the aid agencies and NGOs working there. The mapping process, however, is highly manual and can take many hours for an analyst to successfully map the camp. By working with UNOSAT we have developed a tool for automatically mapping refugee camps across the Middle East and North Africa, saving countless hours for analysts and allowing them to repond faster when information is required.

</div>

### Automated Flood Mapping

<div style="text-align: justify">

After catastrophic events, situational information is critical to response teams. Flood maps showing the extent of the affected areas are provided by teams at [UNOSAT](https://unitar.org/sustainable-development-goals/satellite-analysis-and-applied-research) through their rapid mapping service. Current methods largely include semi-automatic pixel intensity thresholding on Sentinal-1 radar images which take approximately 6 hours to be performed by human analysts. Using a Machine Learning model this process has been automated, saving considerable time for the analysts, while attaining the high degree of accuracy required.

</div>

### Damage Detection

<div style="text-align: justify">

Post-event damage analysis plays a crucial role in directing response team resources. By using pre-event and post-even satellite imagery, combined with methods for automatic object detetion and classification, damage detection can be automated over extremely large regions. By providing up-to-dat rapid damage assessments, response teams can better allocate resources and provide assistance more rapidly.

</div>

### Mapping the Risks in Text Generation

<div style="text-align: justify">

Data and computing resources are becoming increasingly availabile and information can be rapidly and widely disseminated with relative ease. The ability to automate the generation of false information efficiently and convincingly, and disseminate it across these networks, often in a targetted way, poses great risks to peace and political stability. In work carried out the UN Global Pulse, we mapped the risks associated with this ability through demonstrating the ease with which an AI text generation model can be built and trained to produce disturbing content.

</div>

### Textual Analysis

<div style="text-align: justify">

Textual and linguistic data, particularly surrounding political and social debates, contain a wealth of information while being largely underutilisied on a large scale. Part of the reason for this is the lack of cross-discipline discussions between policy experts wanted insights into the data and technical researchers helping explore and frame new questions and understanding the tools required to ask them. As a proof-of-concept we analyse a corpus of UN General Assembly speech transcripts over a 45 year period and use a variety of NLP technicques to probe the data to discover new insights in global political diologue.

</div>

### Qatalog

<div style="text-align: justify">

Analysing large corpora of text is a burdensome task for humanitarian team with limited time and resources; however, access to a greater amount of timely information is crucial to many UN country teams, crisis response groups and others, in order to understand an evolving landscape. In an attempt to systematise the collection of data from across a variety of media sources, including social media, radio and news feeds, UN Global Pulse began developing Qatalog. As well as collecting this information, the system uses a variety of NLP processes to analyse and distill the information for easier querying and interpretability by analysts.

</div>

## Healthcare

### Medical Image Segmentation

<div style="text-align: justify">

The segmentation of medical X-Ray images to identify the bone and soft tissue structures is an important tasks in many image processing tasks, such as scatter correction. Indeed, although many Machine Learning models have the potential to automate this task, the amount of high-quality labelled data is often small, especially since medical institutions are often not able to share imagery. Given this, we developed an AI solution to this problem that out-performs other off-the-shelf methods like SegNet on small image datasets. We present the image pre and post-processing pipeline as well as the network achitecture we designed and tuned.

</div>

## Ethics

### Biases and Harms in AI Systems

<div style="text-align: justify">

The study of the ethical use of AI is of the upmost importance, however, many guidelines and docuements, although extremely valuable, overlook the direct link between data, model and design biases in AI systems and human level harms. By identifying possible such biases and exploring their translation into harmful results, we come to understand the additional required caution which must be used when approaching the deployment of AI solutions in humanitarian contexts.

</div>

## Human Rights Implications of AI

<div style="text-align: justify">

From the production of training data to the deployment of AI solutions, the model building process has significant human rights implications. Amoung others, I am concerned by the way in which training data is 'manufactured' around the world, where individuls are often employed to tag distressing content for social media platform content warnings sometimes with little support, or are being paid extremely low wages for laborious, long-houred work with minimal support. Similarly, there are significant concerns around the use of AI systems 'in-the-wild' and the often unquestionability of AI systems.

</div>

