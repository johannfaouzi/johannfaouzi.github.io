I'm currently **Assistant Professor** in **Computer Science** at **ENSAI**
(*École Nationale de la Statistique et de l'Analyse de l'Information*,
a French public higher education institution specialized in statistics and
information processing), Bruz, France, and a member of **CREST**
(Center for Research in Economics and Statistics).
My main research interest is **machine learning**, with a focus on
**time series**, **Python programming**, **open source software**, and
**applications in medicine**.

Previously, I was first a PhD student then a postdoctoral researcher at the
[Paris Brain Institute](https://icm-institute.org/en/)
in both the [ARAMIS team](https://www.aramislab.fr) and the
[Corti-Corvol team](https://institutducerveau-icm.org/en/team/team-corti-corvol/).
I worked on machine learning for precision medicine in Parkinson's
disease and was supervised by Olivier Colliot and Jean-Christophe Corvol.


### Open source software

I strive for open science and open source software in particular.
I find creating and contributing to open source software to be a great
learning experience.

More information on my contributions in the
[Open Source Software](/open_source_software.md) section.


### Postdoctoral research

I worked on machine learning for precision medicine in Parkinson's
disease, more precisely on the genetics of cognitive decline in Parkinson's
disease as the genetic risk factors are currently not well known.


### Other research works during my PhD

I co-wrote several literature reviews on deep learning for brain disorders,
impulse control disorders in Parkinson's disease,
machine learning for Parkinson's disease and related disorders (accepted book chapter)
and prediction of mild cognitive impairment in Alzheimer's disease using machine learning.
I also co-wrote a high-level introductory chapter on classic machine learning algorithms (accepted book chapter).
I took part in a challenge on brain-age prediction,
in a study on automatic classification of parkinsonian syndromes,
and in an analysis of functional brain connectivities in Tourette disorder.


### PhD thesis

During my PhD thesis, I worked on machine learning to predict impulse control
disorders (ICDs) in Parkinson's disease (PD). I was under the supervision of
Olivier Colliot and Jean-Christophe Corvol.

Parkinson's disease is the second most common neurodegenerative disease in
the world, with no cure available for the moment. The therapeutic strategy is
based on the dopamine replacement therapy. Although available since the 1960s',
it is only relatively recently that behavioral disorders associated with these
drugs have been described. Gathered under the term of "behavioral addiction",
they include impulse control disorders, dopamine dysregulation syndrome,
and punding.

Impulse control disorders are a class of psychiatric disorders characterized by impulsivity.
These disorders are common during the course of Parkinson’s disease, decrease
the quality of life of subjects, and increase caregiver burden. Being able to predict
which individuals are at higher risk of developing these disorders and when is of high
importance.

The main objective was to build predictive models of ICDs in Parkinson's disease,
in order to improve the quality of life of the patients. We were particularly
interested in investigating the predictive performance of algorithms trained
using known and suggested risk factors, as well as identifying new risk factors,
especially genetic factors.

As the literature on predicting ICDs in PD was almost non-existent, we studied
the predictability of impulse control disorders in Parkinson's disease.
With the objective of predicting their presence or absence at the next clinical visit
(binary classification task with longitudinal data), we showed that the
predictive performance was acceptable. We also showed that removing the genetic
variants as input of the algorithms did not significantly change the predictive
performance. As importantly, we detailed our rigorous methodology
(nested cross-validation, replication in an independent cohort) that
is missing in the few studies currently published on this topic.
An article summing up this work is currently under review.

Since the genetic variants suggested in the literature did not seem to be
important contributors to the models, we studied the genetics of impulse control
disorders using genetic risk scores. A genetic risk score is a number indicating
the risk of developing a given phenotype based on genetic data and can be obtained
from a genome-wide association study. Because there is no genetic risk score
for impulse control disorders to date and the sample sizes in the available
datasets were relatively small, we computed genetic risk scores for other
phenotypes and studied their associations with impulse control disorders.
We could not report any association after correction for multiple comparisons.
An article summing up this work has been published in Parkinsonism & Related
Disorders in 2021.

Finally, in a more methodological study, we investigated the combination of
static and dynamic data in recurrent neural networks. We performed a literature
review, identified four approaches and proposed a new one. We evaluated the
five approaches in the use case of predicting impulse control disorders in
Parkinson's disease. We used clinical data as dynamic data and genetic data
as static data. All five approaches yielded very similar results. These negative
results were not really surprising due to the lack of positive results with
these genetic data in the other two studies.
