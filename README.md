# Concreteness Fading (Dataset)

## Overview
**Motivation:** <br>
Our comprehensive [literature review on concreteness fading](https://sanghosuh.github.io/papers/concreteness_idc.pdf) has shown that there are many different implementations and naming schemes for concreteness fading. This shows a lack of a shared understanding of the technique and the interface for various disciplines and research communities to communicate and inform each other.

**Solution:** <br>
Thus, we open-source this dataset to support a shared understanding of the technique and suggest this repository as an interface through which researchers can learn about and exchange materials on concreteness fading.

**Contribute:** <br>
Please contribute any missing resource on concreteness fading by editing the [spreadsheet](https://docs.google.com/spreadsheets/d/14qlqKLBrsBoyajdYDESxlwqr5YIqeGi0Ii_3zynVuU4/edit?usp=sharing) directly or adding the paper on the [web app](https://www.appsheet.com/newshortcut/1c40a60a-3b9c-478a-af40-1e5dcd9167af). (FYI, Google spreadsheet has a version history feature, so it's okay if you accidentally delete some records. Just let us know.)

**Repository:** <br>
This repository contains a description of the dataset and two interfaces for updating and interacting with the dataset. 

**Interface:** <br>
There are two interfaces: (1) Google [spreadsheet](https://docs.google.com/spreadsheets/d/14qlqKLBrsBoyajdYDESxlwqr5YIqeGi0Ii_3zynVuU4/edit?usp=sharing) and (2) [web app](https://www.appsheet.com/newshortcut/1c40a60a-3b9c-478a-af40-1e5dcd9167af). 
- The spreadsheet and web app allow you to interact with the dataset. For instance, on the spreadsheet, you can filter the dataset to see a set of studies conducted with primary school children or find a group of concreteness fading designs using 3-stage progression; you can also contribute to this dataset by adding any missing paper(s) such as your paper(s) to help others discover your work. 
- Note that the web app is displaying data in the spreadsheet. Thus if you add a paper in the spreadsheet and refresh the web app, it will display the newly added paper(s). 

## Dataset [[spreadsheet](https://docs.google.com/spreadsheets/d/14qlqKLBrsBoyajdYDESxlwqr5YIqeGi0Ii_3zynVuU4/edit?usp=sharing)][[web app](https://www.appsheet.com/newshortcut/1c40a60a-3b9c-478a-af40-1e5dcd9167af)] 
For a comprehensive review of concreteness fading, we conducted a systematic search with six research databases covering all potential disciplines: computing (ACM Digital Library and IEEE Xplore), Education (ERIC), Multidisciplinary (SCOPUS, Google Scholar, Web of Science). We also expanded our search terms beyond "concreteness fading" to ensure that we do not miss any paper that may be relevant and useful. These terms are listed below. You can find more details on our [paper](https://sanghosuh.github.io/papers/concreteness_idc.pdf).

**Note**: More resources have been added since our original literature review, as the intention is to update this dataset continually.


### Keywords
- `concreteness fading`
- `concrete fading`
- `concrete to abstract`
- `progressive formalization`
- `progressive idealization`
- `concrete-representational-abstract `
- `concrete-pictorial-abstract`
- `concrete-semiconcrete-abstract`
- `CRA`
- `RA`
- `CSA`
- `CPA`
- `VRA`

### Databases
- [ACM Digital Library](http://dl.acm.org) (Computing)
- [IEEE Xplore](https://ieeexplore.ieee.org/Xplore/home.jsp) (Computing)
- [ERIC](https://eric.ed.gov/) (Education)
- [SCOPUS](https://www.scopus.com/search/form.uri?display=basic) (Multidisciplinary)
- [Goolge Scholar](https://scholar.google.com/) (Multidisciplinary)
- [Web of Science](https://webofknowledge.com) (Multidisciplinary)

### Tags
- `id` : *resource identifier*
- `year`: *year it was published*
- `title`: *resource title*
- `author`: *resource author(s)*
- `venue`: *resource venue (e.g., conference)*
- `database`: *database*
- `database_query`: *keyword used to find resource*
- `url`: *link to access resource*
- `contribution`: *contribution type* (click [here](https://dl.acm.org/citation.cfm?id=2907069) for details)
- `domain`: *subject/field* (e.g., math, computing, science)
- `concept`: *concept(s) explored in resource*
- `peer_reviwed`: *whether it was peer-reviewed*
- `participant_age`: *age (range) of participants*
- `target_group`: *target group*
- `sample_size`: *number of participants*
- `order_of_progression`: *order of progression*
- `num_of_stages`: *number of stages*
- `sequence`: *sequence of representations/instructions*

### Note
- In general, `-` in the dataset imply **not applicable** or **couldn't find**. 
- Specifically, its implication(s) for each tag is as follows.
   - For `venue`, it is because the resource is an (online) article or dissertation and/or does not have a venue associated with it. 
   - For `database`, it is because the resource was not found with a database but instead with a search engine.
   - For `database_query`, it is because no database was used to find it.
   - For `concept`, it is because no specific concept was identified or was the focus of the resource. 
  - For `peer_reviewed`, it is because it is unclear whether it was peer-reviewed or is an online (article) or dissertation. 
   - For `participant_age`, `target_group`, `sample_size`, `order_of_progression`, `num_of_stages`, and `sequence`, the general implication (i.e., **not applicable** or **couldn't find**) applies.

## Reference
S. Suh, M. Lee, and E. Law, “How Do We Design for Concreteness Fading? Survey, General Framework, and Design Dimensions,” in Proceedings of the 19th ACM Conference on Interaction Design and Children, 2020. [[paper]](https://sanghosuh.github.io/papers/concreteness_idc.pdf)  [[presentation]](https://youtu.be/g4jDyxiFDTY)

```
@inproceedings{suh2020we,
  title={How do we design for concreteness fading? survey, general framework, and design dimensions},
  author={Suh, Sangho and Lee, Martinet and Law, Edith},
  booktitle={Proceedings of the Interaction Design and Children Conference},
  pages={581--588},
  year={2020}
}
```

## FAQ
1. I added a paper in the spreadsheet, but I don't see it on the web app. Why can't I see it?
- Please check if you specified `ID` in the spreadsheet. The `ID` property functions as a key. If it was not specified in the spreadsheet, it will not be displayed in the web app. 

## Questions 
- If you have any other questions, please report suggestions/issues [here](https://github.com/sanghosuh/concreteness_fading-dataset/issues) or email me using the contact information below. I will continue to update this README and FAQ to make clarifications. 

## Contact
- sh31659 at gmail dot com

[Last update: 12/20/2022]
