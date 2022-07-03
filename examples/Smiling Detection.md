# The Derman & Wilmott Modeler's Manifesto Model Card
This Model card is intended to be compared with the first example from [Model Cards for Model Reporting (Mitchell et al)](https://arxiv.org/pdf/1810.03993.pdf). It is for a Smiling Detection CNN Model trained on the CelebA dataset. (Disclaimer: This is an example and not necessarily factual. My apologies if I get some of the following information incorrect. I am by no means an expert on smiling or very familliar with the original paper.)

## What system actually determines the predicted variable, and how does it differ from a computational model?
**The Modeler's Hippocratic Oath (I)**
> I will remember that I didn't make the world, and it doesn't satisfy my equations.

For humans, a "smile" is determined by two primary systems, the first being biological and the second being sociological. 

The biological system that causes a smile is the contraction of the [Zygomaticus major muscle](https://en.wikipedia.org/wiki/Zygomaticus_major_muscle) in the face, which draws the the outer edges of the lips upward. In some smiles, (commonly referred to as '[Duchenne Smiles](https://en.wikipedia.org/wiki/Smile#Duchenne_smile)') the [Orbicularis oculi muscle](https://en.wikipedia.org/wiki/Orbicularis_oculi_muscle) contracts as well, pulling the cheeks up and causing wrinkling around the eyes commonly known as 'Crow's Feet'. These features are present in most smiles, although they can also be common in a grimace, a facial expression commonly used to display negative emotions. It is suspected that these muscle contractions [have physiological causes, and likely not visually learned](https://www.apa.org/news/press/releases/2008/12/facial-expressions).

The key deciding factor in the difference between a smile and a grimace, or how much of a muscle contraction is considered a "smile", is sociological and subjective, although smiling is almost universal across all human cultures (to different degrees). It is unknown to the authors how humans across many different cultures determine the difference between a smile and a grimace, or how much of a visible muscle contraction is considered a "smile". However, the researchers do find that there is a high level of agreement (metric here) between data labelers in (locations/cultures here). 

To more directly measure the biological activity in a smile or establish a ground truth, the researchers could have utilized [Facial EMG](https://en.wikipedia.org/wiki/Facial_electromyography), although this would have made commercial viability very limited due to accessibility issues. Instead, the researchers focus on a visual modality for detecting smiles, which allows them to use images and cameras. Conveniently, most humans also rely on visual modalities to detect a smile.

Unfortunately, there is insufficient knowledge regarding the higher-level functions of the human brain and how they relate to visual stimuli or the determination of a smile. Many artificial neural networks are modeled after the fundamental functions of a human brain, but a brain neuron is [significantly more complex than an artificial one](https://www.sciencedirect.com/science/article/abs/pii/S0896627321005018?dgcid=author) and has features (such as spiking or learning mechanisms) that this model does not capture.

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
