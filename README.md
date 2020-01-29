# DSC 180A Capstone: Wikipedia Edit Wars


![Wikipedia Edit Wars](https://www.economist.com/img/b/1280/1594/85/sites/default/files/20130810_GDC178_1190_1.png)

How to create a better Internet environment to exchange knowledge and ideas?

- TA: [Keng-Chi Chang](https://kengchichang.com/)  &lt;kechang@ucsd.edu&gt;
- Discussion Section A02
    + Time: Wednesdays 9:00-9:50am
    + Location: Warren Lecture Hall 2113
- Lab/Office Hours
    + Time: Fridays 9:00-10:00am or by appointment
    + Sign up [here](https://calendly.com/kengchichang/dsc180a) in advance
    + Location: CSE Basement (B250)


## Schedule

|Week|Topic|Notes|
|--|--|--|
|1|[Introduction](topics/Week-01.md)|[Slides](slides/Week-01.pdf)|
|2|[Background & Data I: Wisdom of the crowds and bias in articles](topics/Week-02.md)|[Slides](slides/Week-02.pdf)|
|3|[Background & Data II: Edit wars and controversies](topics/Week-03.md)|[Jan 24 Assignment 1 Due](assignments/assignment-1.md) |
|4|[Techniques I](topics/Week-04.md)|Slides|
|5|Techniques II|Slides|
|6|Replication Result I|Slides|
|7|Replication Result II|Slides|
|8|Impacts and Ethics|Slides|
|9|Work on Proposals|Slides|
|10|Work on Proposals|Slides|


## Keywords

* Tags: Social Media, Online Conflict, Information Control
* Data: Unstructured text, Webpage metadata
* Methods: Causal Inference, Natural Language Processing, Network Analysis


## Background

Wikipedia is the largest collection of human knowledge, featuring open access and contributions. 
However, [edit wars](https://qz.com/347227/wiki-wars-inside-the-increasingly-nasty-battle-for-wikipedias-soul/) are actually quite common, making Wikimedia Foundation set up certain [policies](https://en.wikipedia.org/wiki/Wikipedia:Edit_warring).

One might argue that not putting restrictions on edits allows free exhange of ideas and helps to grow the community.
Others might argue that putting certain restrictions can produce a higher-quality content and attract better editors.
The lessons from Wikipedia can inform us possible directions for the future of social media.

This project will initially replicate a [study](https://arxiv.org/pdf/1107.3689.pdf) quantifying controversies of Wikipedia articles, conducted before 2014. 
This project will then update the result to 2019, evaluate its performance, and derive other ways to measure controversies.


## Data

All edit histories are publicly available through [Wikimedia](https://dumps.wikimedia.org/backup-index.html).

- For the first part of the replication, we will use the (cleaned) Wikipedia data released by [WikiWarMonitor](http://wwm.phy.bme.hu/).
- For the second part of the replication, we will use the (raw) Wikipedia data released by [Wikimedia Data Archives](https://dumps.wikimedia.org/backup-index.html).


## Possible Projects

Note: Your proposal is NOT limited to be about edit wars. The replication is the process to give you hands-on experience of the data and detect possible directions.

- Visualize the controversies across languages and across time
- Combinine text and edits to improve controversy detection
- Detect and prevent systematic coordination to attack Wikipedia
- Develop algorithms to make automatic judgments on edit wars, evaluate its effectiveness, and compare with human judgments
- Evaluate the effectiveness of Wikipedia's policy to combat coordination attacks


## Useful Resources

- [Computing for the Social Sciences](https://cfss.uchicago.edu/notes/)
- [R for Data Science](https://r4ds.had.co.nz/)
- [Introduction to Econometrics with R](https://www.econometrics-with-r.org/)
- [Data Visualization: A Practical Introduction](http://socviz.co/)
- [Structural Topic Model](https://www.structuraltopicmodel.com/)
