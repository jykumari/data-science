# Hypothesis testing lab

# Overview

The American National Election Studies (ANES) conducts surveys of voters in the United States, with a flagship survey occurring immediately before and after each presidential election.  While the post-election data for 2020 is not yet available, pre-election data is available as a preliminary release. ANES data has been used to answer questions about voters in the US.

This lab consists of three research questions.  For each question, a statistical analysis has been conducted and a written report has been generated in pdf format.   

This exercise helps demonstrate both statistics and professional communication.  It uses properly executed techniques; a clear and organized writing, and a well justified argument.


# Data

Data for this hypothesis testing lab has been drawn from the 2020 American National Election Studies (ANES). This data can be accessed at [https://electionstudies.org](https://electionstudies.org).

The data that we have used here comes from the **2020 Time Series Study**.

There are two forms of data that are available,
1) data that is stored in a `.dta` format, and
2) data that is stored in a `.sav` format.
Both of these are proprietary data formats (`.dta` for STATA, and `.sav` for SPSS). In order to read this data into R; --library package has been used that is available within the "tidyverse".

Along with the data, codebook has also been downloaded from the ANES website, to refer to the description of the variables. because all of the variables are marked as something like, `V200002` -- which isn't very descriptive without the codebook.

# The Research Questions

The research question for each of the three parts of the lab exercise are as follows:

1. Are Democratic voters older or younger than Republican voters in 2020?
2. Are Democratic voters more enthusiastic about Joe Biden or Kamala Harris?
3. Are survey respondents who have had someone in their home infected by COVID-19 more likely to disapprove of the way their governor is handling the pandemic?
