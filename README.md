# Case Study - Facebook Emotional Contagion Study

## Introduction
The [Tuskegee Syphilis Study](https://www.cdc.gov/tuskegee/timeline.htm), was a notoriously unethical study with devestating effects resulting from a disregard of the impact of experiments on test subjects. In the Information Age, it can be easy to lose sight of how testing might harm subjects. An example of a potentially harmful test inflicted upon unknowing users was the __Facebook Emotional Contagion Study__, published in 2014. The paper chronicled a study conducted in 2012 by which data scientists at Facebook manipulated the content that users would see on their newsfeed in order to manipulate their emotions. This was done in order to measure the impact of the user's emotions on the entire social network. 

In this case study, you will learn about the Facebook Emotional Contagion Study and the ethical shortcomings of the experiment's design. Then, you will learn how you can improve the design of the study to reduce harm to users.


## Learning Objectives
* Summarize the Facebook Emotional Contagion in the context of ethical experimental design
* Identify opportunities to make the experiment more ethical

## Case Summary
Perhaps the most high-profile A/B test of the 21st Century so far is the Facebook "emotional contagion" study published in 2014, formally titled Experimental evidence of massive-scale emotional contagion through social networks. This study used Facebook's A/B testing tools as well as natural language processing (NLP) techniques to manipulate the news feeds of over 600,000 Facebook users. Some users had posts with "negative emotional content filtered out, while others had posts with "positive emotional content" filtered out, and then researchers measured the impact of these changes on the "emotional content" of those users' future Facebook posts.

There was broad backlash to this study, in part because there had been no informed consent process (not even in the ToS). But possibly what angered the public the most was Facebook not following the two other ethical areas of application from the [Belmont Report](https://www.hhs.gov/ohrp/regulations-and-policy/belmont-report/read-the-belmont-report/index.html): assessment of risks and benefits, and ethical selection of subjects.

Assessment of Risks and Benefits
While the Belmont Report does not state that human subjects research must be risk-free, it does say that there should be a "systematic assessment of risks and benefits". Those benefits include "anticipated benefit to society in the form of knowledge to be gained from the research" while risks include "risks of psychological harm, physical harm, legal harm, social harm and economic harm".

The stated benefit of the "emotional contagion" study was to learn whether the emotional contagion observed in in-person studies also occurred in large online social networks. The main risk pointed out by critics was that Facebook was potentially causing depression in its users. Activists and politicians argued in response that this risk was not worth the stated benefit.

An alternative to A/B testing in a sensitive context like this could be a data mining approach, as in this paper, which collected and analyzed already-existing data from an online depression community rather than performing an experiment that manipulated people's online experiences. This may not meet the "gold standard" of a randomized controlled trial in terms of statistical strength but may provide comparable insights with much lower risk to users.

Ethical Selection of Subjects
The final application area listed in the Belmont Report is the ethical selection of subjects. Subjects must be ethically selected on a social and individual level, and researchers should consider distributive justice in choosing subjects due to "social, racial, sexual and cultural biases institutionalized in society". It also emphasizes that vulnerable subjects should receive additional protections "because they are easy to manipulate as a result of their illness or socioeconomic condition".

The "emotional contagion" study concerned activists because participants appeared to have been chosen randomly, and potentially-vulnerable people experiencing depression or under the age of 18 were apparently not excluded from the study.

## Improving the Study
In response to concerns about the study, Facebook CTO Mike Schroepfer posted this update to Facebook's research practices. It acknowledged that this particular study could have been done non-experimentally, and also established a new framework for research ethics:

> Guidelines: we’ve given researchers clearer guidelines. If proposed work is focused on studying particular groups or populations (such as people of a certain age) or if it relates to content that may be considered deeply personal (such as emotions) it will go through an enhanced review process before research can begin. The guidelines also require further review if the work involves a collaboration with someone in the academic community.

Note how the examples of "particular groups or populations" corresponds to the ethical selection of subjects application area, and "content that may be considered deeply personal" corresponds to the assessment of risks and benefits application area. Facebook also established "a panel including our most senior subject-area researchers, along with people from our engineering, research, legal, privacy and policy teams, that will review projects falling within these guidelines" that resembles an IRB.


## Summary
Even though following the Belmont Report is not mandatory for a company like Facebook, its basic principles have proven relevant in the 21st Century. As social networks on platforms like Facebook become more integrated into your daily life, you need to consider how you might regulate the influence of social networks on the welfare of users. 
