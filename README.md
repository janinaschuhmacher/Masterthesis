# Masterthesis
This repository contains the statistical analysis of experimental data in R.

## The experiment
The study investigated how to counter costs of constant interruptions at work through an intelligent support system. 
We investigated if and how far a digital assistant improves performance, lessens delays and reduces mental workload. 
The effectiveness of the system was evaluated with 55 participants in a realistic work environment. The type of
support system was varied between participants and the experiment spanned multiple trials. 

## Where to start
The [statistical hypothesis tests](test_hypotheses/all_groups/hypothesis_analysis.nb.html) sum up the main results of the studies:  

<img src="https://github.com/janinaschuhmacher/Masterthesis/blob/master/test_hypotheses/all_groups/plots_hypothesis_tests/res_speed_per_groups.png" alt="resumption speed for each group" width="600" height="350">


Contrary to our hypotheses, participants who worked with the support system (experimental groups) needed, on average, longer to resume an interrupted task than participants who received no support (control group). 

<img src="https://github.com/janinaschuhmacher/Masterthesis/blob/master/test_hypotheses/all_groups/plots_hypothesis_tests/nasa-tlx_interaction_plot.png" alt="NASA-TLX scores for each group" width="600" height="350">


Also, to some extent, participants in the experimental groups experienced higher mental workload than participants who received no support.



### Further Analyses

In addition to the general hypothesis tests, more [detailed analyses](test_hypotheses) of participants resumption lags after interruptions and their mental workload were carried out. 

<img src="https://github.com/janinaschuhmacher/Masterthesis/blob/master/explorative_analysis/participants_interactions_with_the_prototype/plots_participants_interaction_with_prototype/highlight.png" alt="usage of the prototype's highlight function" width="600" height="350">
Further, log data of participants interactions with the prototype were analysed. This [explorative analysis](explorative_analysis/participants_interactions_with_the_prototype) revealed that usage declined across trials. 
