# Experiment Design Checklist

Atal Gawande's [The Checklist Manifesto](http://atulgawande.com/book/the-checklist-manifesto/) is a compelling account of how the simple checklist can scaffold expertise and teamwork in complex domains. Good checklists, he says, nudge our memories, prompting us to do what we already know we should do, but risk missing.

Good checklists are also short. 5-9 "killer" items, says Gawande. 

So, I got to thinking, what would be on my checklist for experiment design? Additional suggestions welcome, by [email](mailto:t.stafford@sheffield.ac.uk) or [on mastodon](https://mastodon.online/@tomstafford), but this is what I got so far:

## 1. Did you discuss authorship with the research team?

###  Not sure who is an author: [ICMJE Authorship definition](http://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html). Bonus points: start filling in the [Contributor Roles Taxonomy](https://casrai.org/credit/)

## 2. Is your study adequately powered?

### [Most studies are underpowered](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2000797), don't be one of them. Useful: [Understanding mixed effects models through data simulation](https://psyarxiv.com/xp5cy/). What is your recruitment plan? How will participants be enticed to take part? How will they be rewarded for taking part? Will they be *brought into* the research process in any way?

### More from me: [Power analysis for a between-sample experiment](https://tomstafford.sites.sheffield.ac.uk/news/power-analysis-for-a-between-sample-experiment), [Quantifying the benefits of using decision models with response time and accuracy data](https://link.springer.com/article/10.3758/s13428-020-01372-w)

## 3. Should you include a manipulation check?

### Probably you should. How will you know that participants were affected the way you think they should have been by your intervention?

## 4. Does your experiment produce data that you can analyse?

### This means you should do a full dry run through the experiment, noting how long it takes, and checking that the measures you need are recorded. Bonus points: simulate participant data (some platforms like Qualtrics will do this for you) and check your proposed analysis runs on the output. Bonus points: [Exercises for Lab Groups to Prevent Research Mistakes](https://psyarxiv.com/rsn5y/)

##  5. How will you judge the size of any effect?

### even a statistically significant result might be meaningless. How will you calculate an effect size, and how will you gauge whether it is important? Bonus points: [maximal positive controls](https://www.sciencedirect.com/science/article/pii/S0022103120304224) 

##  6. Will you be able to interpret all possible results which aren't in line with your predictions?

###  Maybe you made predictions. What will it mean if you get a null result? Or an intermediate result? Or any other unexpected outcomes.

## 7. Do you have a plan (and consent) for storing and sharing the data?

### Aim for your final data to be [FAIR](https://www.go-fair.org/fair-principles/) - Findable, Accessible, Interoperabe and Reusable

## 8. Have you checked prior work on this topic?

### How systematic was that review of the previous literature?

## 9. How will the final result be criticised?

### Imagine what your strongest critic will say when presented with your final results. Plan your defence. You might want to consider List #2

***


# List #2 : Common criticisms

Standard flaws, and standard criticisms that you might hear about your result

\- 

## failure to generalise

### Does your sample align with the population you want to draw inferences about? Do the stimuli you use fairly represent the situations you want to talk about?

### Reading on this: Yarkoni, T. (2019, November 22). [The Generalizability Crisis](https://doi.org/10.31234/osf.io/jqw35). https://doi.org/10.31234/osf.io/jqw35

##  placebo effect

### Participants responding to the situation, not your intended treatment. Address with an adequate control

##  demand effect

### Participants responding to what they think you want. Address by keeping partipants blind to which condition they are in. Advanced: your experiment will contain an *incentive structure* which participants respond to. It may be that errors are more costly than successes (so you are rewarding conservative behaviour), or it may be something as simple as that you can get through the experiment more quickly if you take a certain choice (so you are rewarding fast/inaccurate responding). You should know what the incentive structure of your experiment is. The incentive structure of your experiment may be driving behaviour, as much as any deeper psychological desires or biases. Even if this isn't the case, how will you convince a critic that your experiment reveals something about human psychology beyond "participants do what they are rewarded for?"

### Something to read on this: Corneille, O., & Lush, P. (2021). [Sixty years after Orne’s American Psychologist article: A Conceptual Framework for Subjective Experiences Elicited by Demand Characteristics](https://www.researchgate.net/publication/360589222_Sixty_years_after_Orne's_American_Psychologist_article_A_Conceptual_Framework_for_Subjective_Experiences_Elicited_by_Demand_Characteristics).

## experimenter bias

### may not be deliberate. Could result from unintentional exploitation of [researcher degrees of freedom](https://journals.sagepub.com/doi/full/10.1177/0956797611417632), inadvertant [signalling to participants](https://journals.sagepub.com/doi/abs/10.1111/1467-8721.ep10770698?journalCode=cdpa). Partially address with preregistration.

## selection and survivorship bias

### Are the results distorted by how you recruited, or how participants differentially dropped out during the experiment? Partially address with (truly) random assignment. 

##  regression to the mean

### Particularly a problem with test-retest designs

##  common method variance

### Particularly a problem if both your dependent and independent measures are of the same type (e.g. survey items)

##  so what?

### "This was obvious", says everyone *after*  you've done the work to show it happens

### Here's a quote to keep in mind, if you do want to rest the value of the experiment on theory-testing

> But I will mention one severe but useful private test – a touchstone of strong inference – that removes the necessity for third-person criticism, because it is a test that anyone can learn to carry with him for use as needed. It is our old friend the Baconian “exclusion,” but I call it “The Question.” Obviously it should be applied as much to one’s own thinking as to others’. It consists of asking in your own mind, on hearing any scientific explanation or theory put forward, “But sir, what experiment could disprove your hypothesis?” ; or, on hearing a scientific experiment described, “But sir, what hypothesis does your experiment disprove?” 

### Platt, J. R. (1964). Strong inference. Science, 146(3642), 347-353.

##  false positive

### You got lucky, they say. Address by replicating and/or [pre-registering](http://tomstafford.staff.shef.ac.uk/?p=573)

##  confound

### Something else you didn't control for produced the effect


***

You may also enjoy

* Peter Norvig: [Warning Signs in Experimental Design and Interpretation](https://norvig.com/experiment-design.html)
* Julia Strand: [Error Tight: Exercises for Lab Groups to Prevent Research Mistakes](https://psyarxiv.com/rsn5y/)
* Samuel J. Lord [Checklist for Experimental Design](https://blog.everydayscientist.com/?p=3836) (from a Cell biology and microscopy researcher)
* Ritter, F. E., Kim, J. W., Morgan, J. H., & Carlson, R. A. (2011). [Practical aspects of running experiments with human participants](https://link.springer.com/chapter/10.1007/978-3-642-21672-5_14). In Universal Access in Human-Computer Interaction. Design for All and eInclusion: 6th International Conference, UAHCI 2011, Held as Part of HCI International 2011, Orlando, FL, USA, July 9-14, 2011, Proceedings, Part I 6 (pp. 119-128). Springer Berlin Heidelberg.
* Kane, J. V. (2024). [More than meets the ITT: A guide for anticipating and investigating nonsignificant results in survey experiments](https://www.cambridge.org/core/journals/journal-of-experimental-political-science/article/more-than-meets-the-itt-a-guide-for-anticipating-and-investigating-nonsignificant-results-in-survey-experiments/C01250EB50598D6328B6065F1DF86BA7). Journal of Experimental Political Science, 1-16. <https://doi.org/10.1017/XPS.2024.1> 

Created: 2021-07-10  
Latest update: 2024-06-11  
Repo (contains citation widget): [github.com/tomstafford/psy-checklist](https://github.com/tomstafford/psy-checklist)  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5204496.svg)](https://doi.org/10.5281/zenodo.5204496)

<style type="text/css">
p{
font-style: italic;
}
  h1 {
    background: #e5ffff;
    }
  h2 {
  background: #ffe5e5;
  padding: 5px;
  font-weight: bold;
  font-size: 150%;
  }
  h3 {
	color: #808080;
	font-size: 100%;
	margin-left: 35px;

	}
  ul {
    list-style-type: circle;
  }
.footer {
  display: none;
}
</style>

<p align="right">
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</p>
