# Statistical Modeling and Causal Inference with `R`
 
This course represented the 2nd part of the sequence in statistical modeling for MIA and MPP students at the Hertie School. Assuming prior knowledge in simple and multiple linear regression modelling, it introduced students to a new perspective on studying causes and effects in social science research. Based on a framework of causality, the course agenda covered various strategies to uncover causal relationships using statistical tools. We started with reflecting about causality, the ideal research design, and then learned to use a framework to study causal effects. Then, we revisited common regression estimators of causal effects and learned about their limits. Next, we focused on matching, instrumental variables, difference-in-differences and fixed effects estimators, regression discontinuity designs, and techniques to explore moderated and mediated relationships. All classes divided time between theory and application.

Instructors:

- Constantin Manuel Bosancianu ([https://cmbosancianu.github.io](https://cmbosancianu.github.io))
- Max Schaub ([https://maxschaub.eu](https://maxschaub.eu))

I am extremely grateful to Max for permission to make public the set of files he developed for the class. Authorship has been clearly indicated in the case of each file in the final section below.

Teaching assistants:

- Adelaida Barrera Daza ([GitHub](https://github.com/adelaida-barrera), [LinkedIn](https://www.linkedin.com/in/adelaidabarrera/))
- Sebastian Ramirez-Ruiz ([GitHub](https://seramirezruiz.github.io))

Both Adelaida and Sebastian were *invaluable* during the course of the class, from running laboratory sessions, to developing `Rmarkdown` code files, finding example data, generating teaching slides for labs, and many other tasks in between. All code files and slides developed for the seminar sessions were entirely authored by them, and they deserve full credit for this. We couldn't have wished for better support, for which we remain grateful to this day!

## General readings

Throughout the class we rely heavily on the material in:

Angrist, J. D., & Pischke, J.-S. (2015). *Mastering ’Metrics: The Path from Cause to Effect*. Princeton: Princeton University Press.

Most **Required Readings** are taken from this book. Occasionally, we also source key chapters from:

1. Pearl, J., & Mackenzie, D. (2018). *The Book of Why: The New Science of Cause and Effect*. New York: Basic Books.
2. Morgan, S. L., & Winship, C. (2015). *Counterfactuals and Causal Inference: Methods and Principles for Social Research* (2nd ed.). New York: Cambridge University Press.
3. Hernán, M. A., & Robins, J. A. (2020). *Causal Inference: What If*. Boca Raton, FL: CRC Press.
4. Cunningham, S. (2021). *Causal Inference: The Mixtape*. New Haven: Yale University Press.
5. Angrist, Joshua David, and Jörn-Steffen Pischke. *Mostly Harmless Econometrics: An Empiricist's Companion*. Princeton: Princeton University Press, 2009. Section 3.2.

In addition, participants will encounter chapters from other books and journal articles to read; these primarily provide illustrations and more background. Articles that are designated as **Optional Readings** are not required, although references to them and techniques they use will be made during the lecture. 

Articles listed under **Application Readings** serve as an example case during the lecture. For each session, the first reading is mandatory. In order to increase the choice set for participants, we also include additional applications papers, but these will usually not be discussed in class. Reading or skim-reading these papers will give you a clearer idea how the method discussed during the session is used in practice.

This course has an exclusive focus on causal identification and inference. There are other books that focus more on statistical modeling and estimation. If you are interested in these topics, please consult the following:

1. Andrew G., & Hill, J. (2007). *Data Analysis Using Regression and Multilevel/Hierarchical Models*. New York: Cambridge University Press. [a reference book for regression modeling and, particularly, mixed-effects models, from a Bayesian perspective]
2. Enders, C. K. (2010). *Applied Missing Data Analysis*. New York: The Guilford Press. [an accessible introduction into the problems of missing data for our analyses; includes chapters on maximum likelihood estimation]
3. Fox, J. (2016). *Applied Regression Analysis and Generalized Linear Models* (3rd ed.). London: Sage Publications. [theoretical treatment of OLS regression and GLMs, along with selected additional topics, e.g. multilevel models]
4. Freedman, D. A. (2009). *Statistical Models: Theory and Practice*. Cambridge: Cambridge University Press.
5. Wooldridge, J. M. (2013). *Introductory Econometrics: A Modern Approach* (5th ed.). Mason, OH: Cengage Learning. [an econometric classic]

## Session overview

1. **Introduction: Counterfactual causality** (Max and Manuel jointly)
2. **Foundations: The potential outcomes framework and experiments** (Manuel)
3. **Revisiting regression estimators of causal effects** (Max)
4. **Causal graphs** (Manuel)
5. **Instrumental Variable estimation** (Max)
6. **Matching** (Max)
7. **Regression discontinuity designs** (Manuel)
8. **DiD and Synthetic controls** (Max)
9. **Causal inference in panel data and fixed-effects specifications** (Manuel)
10. **Moderation and heterogeneous effects** (Max)
11. **Unpacking causal mechanisms: Mediation** (Manuel)
12. **Field experiments** (Max and Manuel jointly)

