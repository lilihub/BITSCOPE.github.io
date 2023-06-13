# BITSCOPE.github.io
![Picture 2](https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/a1976c0a-378f-40e4-9853-9ba8d0796936)


## Technology Target Statement
We seek to developed a passive hybrid BCI (phBCI) capable of operating “in the wild” and capable of monitoring user attention, memorability and curiosity. 

### Problem Terminology Breakdown
BCI (Brain computer interface). A BCI is a technology which uses a direct connection between the brain and computer systems. 

**Hybrid**. A BCI typically uses a single modality for measuring brain activity. A common choice is to non-invasively measure the electrical activity of the brain via electrodes placed on the scalp which in turn are connected via wires to an amplification device which scales up these signals such they can be digitized for a computer. This modality is called electroencephalography (EEG). A hybrid BCI then uses more than one measurement type, In BITSCOPE we propose to  augment EEG with eye tracking, galvanic skin responses (GSR), heart rate (HR) and movement. GSR and HR allow us to access a source that provides some information regarding emotional state which may be useful for our intended use case. 

**Passive**. A BCI is commonly understood in terms of what might be termed an active interface. This means the user controls the computer directly via the interface to get tasks done. A well-known example of an active BCI is a speller, in which a user selects letters to form words for communication via the BCI.  In contrast, a passive BCI does not explicitly use the device to control a computer system. Instead the BCI allows the software application (an AI agent for example) to be aware of a user’s brain state and adapt the interface or presentation of information to better accommodate the user’s wishes, capabilities or needs. 

**In the Wild**. A common problem with non-invasive BCI is their sensitivity to normal human behaviour. Activities such as talking, head movement, facial expressions, walking, hand gestures, even shifting one’s weight while seated cause the EEG signal to be overwhelmed with electrical signal changes which do not directly reflect the brain signals of interest. We target the development of additional technologies that will mitigate some of these effects allowing the BCI to operate in everyday settings. We use the term “in the wild” to refer to this objective. 

## Objectives
### Objective 1:
Demonstrate a robust, hybrid, i.e., multimodal passive BCI working as an experimental proof of concept for automated tracking of user engagement (attention/memorability/curiosity) in a virtual environmental setting that offers improved performance over competing approaches from an end-user perspective. 
### Objective 2: 
Collect and make openly available multimodal data sets (at least 60 experimental subjects), ground truths and code which can enable others to advance hybrid, passive BCI development through improved machine learning.
### Objective 3: 
Develop signal processing methods for noise suppression in the context of ecologically valid artefacts allowing more power-efficient extraction of useful signal for hybrid passive BCI compared to classical filtering methods.

## Hights to Date
### GSR Integration in OpenVIBE
OpenViBE is an open source software platform dedicated to designing, testing and using brain-computer interfaces developed at partner Inria Bordeaux Sud-Ouest
Sources of autonomic nervous system activity in the form of galvanic skin response, heart rate as well as movement can now be taken as input to OpenViBE with the new integration of the Shimmer gSR+ unit

1. GSR Integration in OpenViBE

<img width="400" height="200" alt="image" src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/2a5d7654-1577-4c9c-b9ca-1f9a957bca62">          <img width="330" height="200" alt="image" src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/300c1248-88bd-492d-8dc7-ca1008312fd9">

OpenViBE is an open source software platform dedicated to designing, testing and using brain-computer interfaces developed at partner Inria Bordeaux Sud-Ouest.
Sources of autonomic nervous system activity in the form of galvanic skin response, heart rate as well as movement can now be taken as input to OpenViBE with the new integration of the Shimmer gSR+ unit.

<div>
    <img align=middle src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/bc546966-2c6b-429e-bd1e-d8899f20818f" width="380" height="160">
    <img align=middle src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/6e0d7d12-0961-4a96-ab0a-513cbb86d25d" width="100" height="100"/>
    <img align=middle src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/7f3a9ddc-f88c-4d0d-910a-a1a2ae1f1846" width="380" height="140">
<div>

2. Editable VR Gallery Experience
    
   UPV have developed initial version of VR gallery suitable for first BCI experiments. Eye tracking feasibility underway with partner NCU
<div>
    <img align=middle src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/919fe2c4-f5e2-4e37-9365-96c6189ccf7c" width="380" height="240">
    <img align=middle src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/23437fcf-9758-46d1-b1e6-aacba94e5805" width="100" height="55"/>
    <img align=middle src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/49b59d7c-7286-49f7-8ffc-e0d11613dfb7" width="380" height="240">
<div>
  
3. Public Engagement  - Artists in Residence

<img width="170" height="220" alt="image" src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/fb046a40-bef0-4bff-b0d7-f9150c20fef1"> 
Erin Redmond’s practice inhabits a space between art, science, and ecology and has elements of sculpture, installation art, and participatory/interactive art. Erin connects the BITSCOPE consortium with galleries, artists and other stakeholders outside the academic domain and is an active contributor of pieces to the new VR gallery.

<img width="190" height="220" alt="image" src="https://github.com/lilihub/BITSCOPE.github.io/assets/37544742/60c404da-1d49-43f1-a531-eb3962f52f1a"> AlanJames Burns (he/they), is a neurodivergent, environmental and audio-visual artist and curator producing interactive, socially engaged and site-specific exhibitions. The focal points of their artistic practice are disability, climate change and the human mind.

AlanJames’ work with DCU and BITSCOPE uses interactive BCI technologies as a creative medium to explore the intersection of climate change and neurodiversity. AlanJames is interested in conceptualising and visualising the differences in people’s brain activity as a positive and creative human ability to solve problem and create change but that can only fully be achieved through collaboration and putting all of our diverse minds together.
























