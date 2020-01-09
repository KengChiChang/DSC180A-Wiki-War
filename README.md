# DSC 180A Capstone: Wikipedia Edit Wars


![Wikipedia Edit Wars](https://www.economist.com/img/b/1280/1594/85/sites/default/files/20130810_GDC178_1190_1.png)

How to create a better Internet environment to exchange knowledge and ideas?

- TA: [Keng-Chi Chang](https://kengchichang.com/)  &lt;kechang@ucsd.edu&gt;
- Discussion Section A02
    + Time: Wednesdays 9:00-9:50am
    + Location: Warren Lecture Hall 2113
- Lab/Office Hours
    + Time: Fridays 9:00-11:00am or by appointment
    + Sign up [here](https://calendly.com/kengchichang/dsc180a) in advance
    + Location: CSE Basement (B250)


## Schedule

|Week|Topic|
|--|--|
|1|[Introduction](topics/Week-01.md)|
|2|[Background & Data I: Wisdom of the crowds and bias in articles](topics/Week-02.md)|
|3|Background & Data II: Edit wars and controversies|
|4|Techniques I|
|5|Techniques II|
|6|Replication Result I|
|7|Replication Result II|
|8|Impacts and Ethics|
|9|Work on Proposals|
|10|Work on Proposals|


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

- Detecting controversies, number of revert edits or text-based?
- What kind of features predict edit wars?
- Do editors coordinate to change certain topics?
- How effective are Wikipedia's certain editing restrictions?
- Algorithms to judge edit wars, comparing with human judgments?


