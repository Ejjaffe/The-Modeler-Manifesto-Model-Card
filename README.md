# The-Modeler-Manifesto-Model-Card
A model card inspired by Derman &amp; Wilmott's ["Modelers' Hippocratic Oath"](https://web.archive.org/web/20140908100545/http://www.wilmott.com/blogs/paul/index.cfm/2009/1/8/Financial-Modelers-Manifesto) following the 2008 Financial Crisis.

## Introduction
Following the financial collapse of 2008, Quantitative Finance Researchers Emmanuel Derman and Paul Wilmott met in New York City and wrote a [Manifesto](https://web.archive.org/web/20140908100545/http://www.wilmott.com/blogs/paul/index.cfm/2009/1/8/Financial-Modelers-Manifesto) on the financial modeling practices that (partially) caused the crisis. Paul Wilmott is credited with being one of the first people to publish warnings about these models years in advance. In the manifesto, they provide a list of general guidelines for financial modelers, which the manifesto calls *The Modelers' Hippocratic Oath*.


> **The Modelers' Hippocratic Oath**
>
> ~ I will remember that I didn't make the world, and it doesn't satisfy my equations.
> 
> ~ Though I will use models boldly to estimate value, I will not be overly impressed by mathematics.
> 
> ~ I will never sacrifice reality for elegance without explaining why I have done so.
> 
> ~ Nor will I give the people who use my model false comfort about its accuracy. Instead, I will make explicit its assumptions and oversights.
> 
>~ I understand that my work may have enormous effects on society and the economy, many of them beyond my comprehension.

In 2022, as we experience the rapid development of large-scale language and image models like GPT-3 and Dall-E that are being trusted to perform critical tasks like [write code](https://github.com/features/copilot) and [communicate with people as a form of therapy](https://mdpi-res.com/d_attachment/sensors/sensors-22-03653/article_deploy/sensors-22-03653.pdf?version=1652257298), AI Safety researchers and Machine Learning Engineers 
[find](https://www.wsj.com/articles/tech-giants-pour-billions-into-ai-but-hype-doesnt-always-match-reality-11656508394) 
[themselves](https://www.washingtonpost.com/opinions/2022/06/17/google-ai-ethics-sentient-lemoine-warning/) 
[reinventing](https://twitter.com/rasbt/status/1541460380899086337) 
[the](https://openai.com/blog/language-model-safety-and-misuse/) 
[wheel](https://futurism.com/new-ai-detects-deception-bring-end-lying-know-it) 
[on](https://www.theregister.com/2021/05/26/ai_insurance_lemonade/) 
[the](https://wappp.hks.harvard.edu/files/wappp/files/elephant_in_ai_2021_report_2.pdf)
[theory](https://www.perpetuallineup.org/background) 
[of](https://www.scientificamerican.com/article/the-pitfalls-of-datas-gender-gap/) 
[irresponsible](https://www.reuters.com/article/us-amazon-com-jobs-automation-insight/amazon-scraps-secret-ai-recruiting-tool-that-showed-bias-against-women-idUSKCN1MK08G) 
[modeling](https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm) 
[and](https://www.washingtonpost.com/technology/2019/12/19/federal-study-confirms-racial-bias-many-facial-recognition-systems-casts-doubt-their-expanding-use/) 
[it's](https://www.scientificamerican.com/article/racial-bias-found-in-a-major-health-care-risk-algorithm/)
[consequences](https://www.nytimes.com/2020/06/24/technology/facial-recognition-arrest.html).

## The Card
In this spirit, I have created a model card from *The Modeler's Hippocratic Oath*. I consider this to be an addition to -- but not a replacement for -- [other](https://arxiv.org/pdf/1810.03993.pdf) [existing](https://blog.salesforceairesearch.com/model-cards-for-ai-model-transparency/) [model](https://modelcards.withgoogle.com/face-detection) [cards](https://github.com/ivylee/model-cards-and-datasheets).

| Modeler's Hippocratic Oath                                                                        | Model Card Text                                                                                            |
| ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| I will remember that I didn't make the world, and it doesn't satisfy my equations.                | What system actually determines the predicted variable, and how does it differ from a computational model? | 
| Though I will use models boldly to estimate value, I will not be overly impressed by mathematics. | We expect this model achieves novel results mainly as a consequence of these novel techniques (and not any kind of magic or infallibility):|
| I will never sacrifice reality for elegance without explaining why I have done so.                | We have excluded the following outliers, edge cases, and inconvenient truths:                              |
| Nor will I give the people who use my model false comfort about its accuracy.                     | This model cannot be relied upon in the following scenarios:                                               |
| Instead, I will make explicit its assumptions and oversights.                                     | We have made the following mathematical, statistical, and computational assumptions:                       |
| I understand that my work may have enormous effects on society and the economy,                   | We have done the following to mitigate real-world harms from this model:                                   |
| many of them beyond my comprehension.                                                             | We acknowledge these potential harms are unmitigated, and there may be many unforseen consequences from the model's use or misuse:|

## Template
---
# The Derman & Wilmott Model Card

## What system actually determines the predicted variable, and how does it differ from a computational model?
**The Modeler's Hippocratic Oath (I)**
> I will remember that I didn't make the world, and it doesn't satisfy my equations.


##  We expect this model achieves novel results mainly as a consequence of these novel techniques (and not any kind of magic or infallibility):
**The Modeler's Hippocratic Oath (II)**
> Though I will use models boldly to estimate value, I will not be overly impressed by mathematics.


## We have excluded the following outliers, edge cases, and inconvenient truths:
**The Modeler's Hippocratic Oath (III)**
> I will never sacrifice reality for elegance without explaining why I have done so.


## This model cannot be relied upon in the following scenarios:
**The Modeler's Hippocratic Oath (IV)**
> Nor will I give the people who use my model false comfort about its accuracy. ...

## We have made the following mathematical, statistical, and computational assumptions:
**The Modeler's Hippocratic Oath (IV)**
> ... Instead, I will make explicit its assumptions and oversights.


## We have done the following to mitigate real-world harms from this model:
**The Modeler's Hippocratic Oath (V)**
> I understand that my work may have enormous effects on society and the economy, ...


## We acknowledge these potential harms are unmitigated, and there may be many unforseen consequences from the model's use or misuse:
**The Modeler's Hippocratic Oath (V)**
> ... many of them beyond my comprehension.
---
## License
After careful consideration of cc-1.0 and cc-by-4.0, I ultimately chose a license from another model card (HuggingFace), which happened to be the Apache 2.0 License. If this is too restrictive for you or it's a bad choice for this project, please feel free to open an issue in this repo.
