---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

## Working Papers

---
### *Real Effects of Judge Selection: The Role of Campaign Finance* (Draft available soon) 
 
This paper studies the real effects of campaign finance and judicial selection. Using the Supreme Court's surprise verdict in the Citizens United v. FEC case in 2010, I document that relaxing campaign finance restrictions led to a 61% increase in the average electoral expenditure of judicial candidates. Competition in judicial elections increased while the judicial bench became more business-friendly. Concomitantly, labor productivity increased by 8%, but only in states with judicial elections. This increase is driven by industries that are more reliant on the quality of legal institutions. Overall, I provide the first evidence that campaign finance deregulation in judicial elections increases electoral competition and scrutiny and improves factor allocation. 

**Presented at:** CICF 2024, ISB Summer Research Conference 2024, 8th HEC PARIS Finance PhD Workshop, Nottingham Interdisciplinary Centre for Economic and Political Research 2024, EEA Congress 2024, EFMA 2024

---
### [*Political Finance and Party Preferences*](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4385015) 
 
Politicians’ influence depends on their relationships with other powerful politicians. In a network of elected representatives based on their committee assignments, I use network centrality as a measure of such influence. I use plausibly exogenous variation in funding to show that well-funded politicians tend to be more central. I also estimate the political parties' preferences over politicians' attributes and document that the parties place candidates with higher funding in more central positions than candidates with a stronger legislative record. This bias in favour of well-funded representatives is robust to other measures of influence such as their legislative productivity. 

![Centrality vs. Funding](/assets/images/fig2.png){:width="900"}


--- 

### [*Stress Tests: Strength v. Frequency*](/files/BST.pdf)
* with [Deepal Basak](https://sites.google.com/a/nyu.edu/dbasak/home) and [Zhen Zhou](https://www.zhenzhoueconomics.com/)

This paper studies how the stress test design (in particular its strength and frequency) affects its effectiveness in providing information to persuade the bank’s stakeholders to coordinate on not “attacking” the bank to decrease the probability of bank failure during distress. The stakeholders are privately informed and move sequentially. We characterize all robustly persuasive stress tests, under which, even in the worst equilibrium, all bank stakeholders disregard their private information and perfectly coordinate their actions based on the test results (“pass” or “fail”). We show that testing the bank more frequently can substitute the role of an increased test strength in making the stress test result persuasive. We then characterize the optimal frequency and investigate how it depends on macroeconomic conditions, the bank’s idiosyncratic characteristics, as well as the endogenous maturity choices of banks. We further examine how other regulatory measures may complement the stress test policy.

**Presented at:** 7th Bristol Workshop on Banking and Financial Intermediation, Bank of England Financial Stability Seminar 

![Stress Tests: Strength vs. Frequency](/assets/images/k_j_plot_tau_9_v5.png){:width="900"}


--- 
 
### [*Experimentation and Learning under Competitive Search*](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4859787) 
* with [Emre Ozdenoren](https://sites.google.com/site/ozdenoren/home)

We study competitive search equilibrium in markets where matches between workers and firms are an experience good and there is uncertainty about match productivity. Parties learn about the underlying match productivity through on-the-job experimentation. If the firms can offer fully flexible wages, the competitive search equilibrium is efficient. However, under fixed-wage contracts, experimentation may be sub-optimal, resulting in fewer vacancies compared to the efficient benchmark. Conditions under which inefficiency occurs depend on whether the firms can commit to contract duration. Without commitment, there is generically too little experimentation. Minimum wages and non-common priors lead to inefficiency even under flexible wages.

**Presented at:** Econometric Society European Meetings 2024, LBS Economics Internal Seminar 


![Experimentation and Learning under Competitive Search](/assets/images/eucs_eq.png){:width="900"} 

--- 

## Works in Progress 
--- 
### *Dynamic Moral Hazard with Competitive Search* with [Doruk Cetemen](https://sites.google.com/site/dorukcetemen/) and [Emre Ozdenoren](https://sites.google.com/site/ozdenoren/home)
### *Social Media and Bank Runs* with [Rhiannon Sowerbutts](https://www.bankofengland.co.uk/research/researchers/rhiannon-sowerbutts) 
 

[comment]: <> (### *Learning about Productivity) 
[comment]: <>(* with [Emre Ozdenoren](https://sites.google.com/site/ozdenoren/home)) 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
