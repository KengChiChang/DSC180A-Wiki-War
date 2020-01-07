# DSC 180A Capstone Quarter I -- Wikipedia Edit Wars

- Section: Discussion A02
- Time: Wednesdays 9:00-9:50am
- Location: Warren Lecture Hall 2113

## Discussion Schedule and Readings

### Week 1: Introduction to Domain/Problem

#### Topics

- Themes of the class:
    + How can we measure online conflict and controversy?
    + When is controversy genuine and when is it coordinated?
    + What should social media companies do about it?
- Topic of this week:
    + Tensions between free speech and 1) online harassment 2) coordinated flooding and 3) false information
    + Discussion: What do we want out of an online environment?

#### Reading

- Henry Farrell and Bruce Schneier. "Democracy's Dilemma." *Boston Review*. [[Link]](http://bostonreview.net/forum-henry-farrell-bruce-schneier-democracys-dilemma)
- Facebook. "Mark Zuckerberg Stands for Voice and Free Expression." [[Link]](https://about.fb.com/news/2019/10/mark-zuckerberg-stands-for-voice-and-free-expression/)
- Wikimedia. Data Archives. [[Link]](https://dumps.wikimedia.org/backup-index.html) Download some snippets and read it.

#### Discussion questions from the reading/data

- What do you agree and disagree about Farrell and Schneier's article?
- What do you agree and disagree about Zuckerberg's speech?
- What kinds of data and metadata can we get from Wikimedia's archive?


---


### Week 2: Domain Background + Data (Part I)

#### Topics

- Wisdom of the crowds

#### Reading

- James Surowiecki. *The Wisdom of Crowds: Why the Many Are Smarter Than the Few and How Collective Wisdom Shapes Business, Economies, Societies and Nations.* (Introduction, Chapters 1-2.) [[Link]](http://www.asecib.ase.ro/mps/TheWisdomOfCrowds-JamesSurowiecki.pdf)
- Aniket Kittur and Robert E. Kraut. "Harnessing the Wisdom of Crowds in Wikipedia: Quality Through Coordination." CSCW '08. [[Link]](https://dl.acm.org/doi/10.1145/1460563.1460572)
- Jim Giles. "Internet Encyclopaedias Go Head to Head." Nature. [[Link]](https://www.nature.com/articles/438900a)
- Shane Greenstein and Feng Zhu. "Do Experts or Crowd-based Models Produce More Bias? Evidence from Encyclopædia Britannica and Wikipedia" [[Link]](https://pdfs.semanticscholar.org/5a1d/58d90143969b33a9a9d4ad4124c15033c745.pdf)
- Wikimedia Research [[Link]](https://research.wikimedia.org/) and their Github Repos [[Link]](https://github.com/wikimedia-research/)

#### Discussion questions from the reading/data

- When is wisdom of the crowds good? And when is it undermined?
- (Continue) Given the data structure on the archives of Wikimedia, what kinds of inferences are possible?


---


### Week 3: Domain Background + Data (Part I)

#### Topics

- Introduction to Edit Wars on Wikipedia
- Introduction to the dataset of interest
- Discussing data cleaning (bring examples, oddities, questions from the stops data!)

#### Reading

- Examples of edit warring:
    + Quartz. "Wiki Wars: Inside the increasingly nasty battle for Wikipedia's soul." [[Link]](https://qz.com/347227/wiki-wars-inside-the-increasingly-nasty-battle-for-wikipedias-soul/)
    + BBC. "China and Taiwan clash over Wikipedia edits." [[Link]](https://www.bbc.com/news/technology-49921173)
- Robert Sumi, Taha Yasseri, András Rung, András Kornai, and János Kertész. "Edit Wars in Wikipedia." 2011 IEEE Third International Conference on Privacy, Security, Risk and Trust and 2011 IEEE Third International Conference on Social Computing. [[Link]](https://arxiv.org/abs/1107.3689)
- Wikipedia Policies on Edit Warring. [[Link]](https://en.wikipedia.org/wiki/Wikipedia:Edit_warring)
- Taha Yasseri et al. WikiWarMonitor. [[Link]](http://wwm.phy.bme.hu/)

#### Discussion questions from the reading/data

- What is an edit war on Wikipedia? What are some strategies to detect them?
- Challenges while reading and cleaning the data


---


### Week 4: Domain Specific Techniques (Part 1)

#### Topics

- Techniques for measuring engagement
- Discussion of possible problems with these techniques
- Due Week 4: Fix the python code on the website to replicate the M-statistic from the light dump

#### Reading

- Robert Sumi, Taha Yasseri, András Rung, András Kornai, and János Kertész. "Edit Wars in Wikipedia." 2011 IEEE Third International Conference on Privacy, Security, Risk and Trust and 2011 IEEE Third International Conference on Social Computing. [[Link]](https://arxiv.org/abs/1107.3689)
- R. Stuart Geiger and Aaron Halfaker. "Using Edit Sessions to Measure Participation in Wikipedia." CSCW 2013. [[Link]](http://stuartgeiger.com/cscw-sessions.pdf)
- Aaron Halfaker, R. Stuart Geiger, Jonathan T. Morgan, and John Riedl. "The Rise and Decline of an Open Collaboration System: How Wikipedia's Reaction to Popularity Is Causing Its Decline." American Behavioral Scientist. [[Link]](https://journals.sagepub.com/doi/pdf/10.1177/0002764212469365)

#### Discussion questions from the reading/data

- How to measure editor engagement?
- Challenges while calculating engagement statistics


---


### Week 5: Domain Specific Techniques (Part 2)

#### Topics

- Linking engagement with time series covariates
- Comparative analysis of Wikipedia Wars by language
- Causality and Confounding
- Due Week 5: Reading in "total dump" data, calculating summary statistics

#### Reading

- Yasseri, Taha, Robert Sumi, András Rung, András Kornai, and János Kertész. "Dynamics of conflicts in Wikipedia." PloS One. [[Link]](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0038869)
- Yasseri, T., Spoerri, A., Graham, M., &amp; Kertész, J. (2014). The Most Controversial Topics in Wikipedia. Global Wikipedia: International and Cross-Cultural Issues in Online Collaboration. [[Link]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2269392)

#### Discussion questions from the reading/data

- What do you find when comparing an index across time? Across languages?
- What can we infer from these correlations?  Is there any way to get at causality?
- How did you read the "total dump" data? What summary statistics did you calculate?


---


### Week 6: Discussion of Main Result (Part 1)

#### Topics

- Exploration of pages with high engagement in different contexts, replication some of the substantive results of the paper.
- Due Week 6: Fix the dump extraction to extract light dump from total dump for one page from 2019

#### Reading

- Xiaoquan (Michael) Zhang and Feng Zhu. "Group Size and Incentives to Contribute: A Natural Experiment at Chinese Wikipedia." American Economic Review. [[Link]](http://fengzhu.info/chinesewikipedia.pdf)
- Shane Greenstein, Grace Gu, and Feng Zhu. "Ideology and Composition among an Online Crowd: Evidence from Wikipedians." Management Science. [[Link]](http://fengzhu.info/wikipedia_seg_final.pdf)

#### Discussion questions from the reading/data

- Who contributes to Wikipedia?
- What "natural experiment" is the Zhang and Zhu paper refer to? How does this help with establishing causality?
- How did you clean the data from "total dump" to "light dump"?


---


### Week 7: Discussion of Main Result (Part 2 -- Eval)

#### Topics

- Exploration of pages with high engagement in different contexts, replication some of the substantive results of the paper.
- Thinking a little bit about shortcomings, evaluation of the results.
- Applying the M-statistics and what they've learned to 2019.

#### Reading

- Ulrik Brandes and Jürgen Lerner. "Visual Analysis of Controversy in User-Generated Encyclopedias." Information Visualization. [[Link]](https://journals.sagepub.com/doi/pdf/10.1057/palgrave.ivs.9500171?casa_token=UuwXHp__AkQAAAAA:s145WlToQX5jVBD0M-OTL11uFguCf0gW7w4dSuYpOaQHaTduVzGoGuThI9vqqeBjwuLugzN1oRMlP4o)
- Hoda Sepehri Rad, Aibek  Makazhanov, Davood Rafiei, and Denilson Barbosa. "Leveraging Editor Collaboration Patterns in Wikipedia." Proceedings of the 23rd ACM conference on Hypertext and social media. [[Link]](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.353.8540&amp;rep=rep1&amp;type=pdf)
- Hoda Sepehri Rad and Denilson Barbosa. "Identifying Controversial Articles in Wikipedia: A Comparative Study." Proceedings of the Eighth Annual International Symposium on Wikis and Open Collaboration. [[Link]](https://www.opensym.org/ws2012/p18wikisym2012.pdf)

#### Discussion questions from the reading/data

- What did you find while replicating the M-statistics using new Wikimedia data?
- What are some shortcomings in the M-statistics measure?  How do the other measures make up for them?


---


### Week 8: Impacts and Ethics

#### Topics

- How could this be used by Wikipedia or other to better understand online conflict and mitigate it.
- What might be the ethical implications/unintended consequences of this.

#### Reading

- Wikipedia Policies on Edit Warring. [[Link]](https://en.wikipedia.org/wiki/Wikipedia:Edit_warring)
- Barbara Fister. "Wikipedia and the Challenge of Read/Write Culture" Library Issues. [[Link]](http://homepages.gac.edu/~fister/LIWikipedia.pdf)
- Joseph Michael Reagle Jr. *Good Faith Collaboration: The Culture of Wikipedia.* The MIT Press. (Chapter 5: The Challenges of Consensus) [[Link]](https://reagle.org/joseph/2010/gfc/chapter-5.html)

#### Discussion questions from the reading/data

- What are some difficulties in consensus decision making?
- How might Wikipedia affect society?
- Discuss the proposal ideas briefly.


---


### Week 9: Related Questions in the Domain

#### Topics

- Project proposal discussion

#### Reading

- No Reading (bring proposals to present)

#### Discussion questions from the reading/data

- Project proposal


---


### Week 10: Proposals (Elevator Pitch)

#### Topics

- Project Proposals

#### Reading

- No Reading

#### Discussion questions from the reading/data

- Project proposal


