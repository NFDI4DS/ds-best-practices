---
title: Before Starting Your Research
date: 2019-04-27
category: Jekyll
layout: post
cover: ../assets/gitbook/images/before.svg
---

--------------------------------------------------------------------------------------------

<center>
  <span style="font-size: 1.5em;">
  Are you at the very beginning of your research project?  
  </span>
</center>
<br>

In this section, you will find recommendations for planning and starting FAIR<sup>1,4</sup> research in Data Science (DS) and Artificial Intelligence (AI). Here and in the next phases, we will focus on how to ensure FAIRness of DS and AI research artifacts such as *(meta)data*, *code, models, software*, and *(research) knowledge graphs* (KGs/RKGs). 

Before diving into the best practices, first try to answer the questions presented in the figure below. Those are aimed to serve as a reference when you plan the project and as a checklist before you start the actual research. 

>Note: These questions apply to KGs/RKGs as well! 

<br>
<img src="../assets/gitbook/images/before_fig.png"
     alt=""
     style="float: left; margin-right: 10px; margin-bottom: 10px;" />
<br>



### (Meta)data
--------------------------------------------------------------------------------------------

1. Decide whether pre-existing data can be used and/or raw data should be collected.
2. Define the goal of data collection/reuse.
3. Before starting to collect/reuse data, assess whether it is subject to privacy/legal/ethical/copyright restrictions (see [Submitting Your Research](https://nfdi4ds.github.io/ds-best-practices/jekyll/2019-04-29-submitting.html#code-models-and-software)). 
4. In case of data collection:
* Plan your approach and methods (e.g., how the data will be collected and the duration of the data collection).
* Decide on (meta-)data, ontologies, and the way data documentation will be provided.
5. Decide on data storage, security, sharing (e.g., with collaborators), and preservation strategies during and after the project.
6. Assess resources required, e.g., computational costs for collecting, storing and pre-processing data, and expenses on annotators. 

>Consider the following data search and collection services:
>* RKGs such as [ORKG](https://orkg.org) or [OpenAIRE Graph](https://graph.openaire.eu)
>* [Papers With Code](https://paperswithcode.com)  
>* [Google Dataset Search](https://datasetsearch.research.google.com)
>* [Kaggle](https://www.kaggle.com/datasets)
>* [Hugging Face Datasets](https://huggingface.co/docs/datasets/index)
>* [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
>* [Data.world](https://data.world/search?context=community&entryTypeLabel=dataset&type=resources)
>* [ELG](https://live.european-language-grid.eu)
>* Additional useful data collection services are available under *Services Lifecycle* on the [NFDI4DS](https://www.nfdi4datascience.de/services/all/) webpage.

### Code, Models, and Software
--------------------------------------------------------------------------------------------

1. Decide whether existing or/and new code/models/software should be used. Before using an existing resource, check its implementation conditions (e.g., have a look at its licence type).
>
>Consider the following code/models/software search services:
>* [Hugging Face Models](https://huggingface.co/models)
>* [SourceForge](https://sourceforge.net)
>* [Software Heritage](https://www.softwareheritage.org)
>* [ELG](https://live.european-language-grid.eu)
>
2. Assess resources required, e.g., computational costs for running and storing code/models/software.
3. Decide on storage, security, sharing (e.g., with collaborators) and preservation strategies during and after the project.

### Publication Venue
--------------------------------------------------------------------------------------------

1. Find and select a suitable publication venue in advance. 
2. Make sure that your paper fits the scope of the venue and that its content is relevant to the venue’s topics.
3. Assess the credibility of a journal or publisher:
* Check the impact factor of an academic journal, i.e., the yearly average of citations of articles published in the last N years in a given journal. You can search for the journal's impact factor by specifying its full name or International Standard Serial Number (ISSN). Note that this measure should be used to compare journals from the same field. For instance, the Artificial Intelligence Journal (AIJ) (impact factor of 14.05 for 2021) vs the Journal of Artificial Intelligence Research (JAIR) (impact factor of 2.441 for 2019). Both are scientific journals on AI research.
* Check whether articles go through a peer-review process and if it is fully disclosed. 
>
>Check what peer-review type the venue adheres to: 
>* Single-blind, author(s) do not know the identity of reviewers. 
>* Double-blind, both identities of authors and reviewers are anonymised. 
>* Open, identities of authors and reviewers are known by all participants (during or after the review process). 
>* Transparent, reviewers’ reports, authors’ responses and editors’ decision letters are published along with an accepted paper. 
>* Collaborative, either reviewers work together to review a manuscript or they collaborate with authors to improve a paper.
>* Post-publication, the review is done after a paper has been published.
>
* Check whether the submission guidelines are clearly stated on the journal/conference webpage.
* Check whether information on ethical considerations such as plagiarism, conflicts of interest, informed consent, and confidentiality is provided.
* Check members of the editorial board. The committee should consist of well-known experts in the field, affiliated with recognised institutions and hold appropriate academic credentials.
* Check if there are fees for publication, this information should be clearly stated.
4. Make sure to pick a publication venue that provides full Open Access to the eventual paper:
* Check the author and copyright policies of the journal/proceedings of the conference. Ideally, the venue should permit authors to retain their copyright, meaning that authors are allowed to reuse, distribute, and republish their work. 

>### tl;dr
><span style="font-size: 1.1em;"><strong>(Meta)data:</strong><span>
>
>Decide where your data is from, and then make sure it has the right license! If you want to create new data, consider your method, documentation strategy, and storing/preservation mechanism carefully. Don’t forget to assess the required human/computational resources needed for your data. 
>
><span style="font-size: 1.1em;"><strong>Code, models, and software:</strong></span>
>
>If you are building on existing code, make sure you are allowed to use it. Consider your computational resources and storing/preservation strategies carefully!
>
><span style="font-size: 1.1em;"><strong>Publication venue:</strong><span>
>
>Choose where you want to publish in advance! Check the call for papers (CfP) and make sure your work fits the topic(s). Make sure that the venue is credible, and that it provides Open Access to papers.
{: .block-tip }


--------------------------------------------------------------------------------------------
