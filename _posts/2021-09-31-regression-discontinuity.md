---
layout: singlepost
title: "A guide to regression discontinuity"
author: "Eric Yeh"
date: 2021-09-31
tags: 
  - project
  - statistics
permalink: /blog/:title
excerpt: "do causal inference without RCT"

---

* TOC
{:toc}

### **What is regression discontinuity?**

<p>Regression discontiuity is an analytical method applied on observational data to infer causal effect of certain intervention.
As its name suggests, the technique can be used when you have a discontinuity in the regression curve.
The dependent variable is a binary variable indicating if the patient receives treatment, and the independent variable is a continuous variable that affects the decision of giving treatment. Usually we call the latter "running variable." The treatment probability will usually abruptly increases when the running variable passes a specific threshold. 
For example, antihypertensive drugs may be more commonly prescribed when blood pressure is over 140 mmHg, or antidiabetic drugs may be more common prescribed when HbA1c is over 6.5%.
When we plot the treatment against the  running variable, we would see a sudden "jump" of treatment probability at the threshold (Figure 1).
</p>

![Figure 1](/assets/img/rdd.jpg){:class="img-responsive" width="600"}



### **What is its potential in medical researches?**

<p>Normally, we need randomized controlled trial to eliminate confounding and get unbiased causal effects. 
However, not all important problems can be answered in randomized controlled trials. 
For example, what is the impact of overprescription of certain drugs?
Obviously, we can't enroll a patient in a trial to let them take unnecessary drugs.</p>

<p>Another reason is real-world situations often deviates from that of research settings. 
Patients walking into your clinic might have diseases that would make them ineligible for the trial. 
So we have no idea whether the conclusion drawn from the trial actually applies to the patients you see.
</p>

### **How is the causal effect calculated?**

### **Applications**