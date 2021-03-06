---
layout: section
---

<img height="80" src="{{ site.logo }}" class="rounded mx-auto d-block" alt="logo">


|Speaker|Video/Audio|
|-------|--------------|
| [Larry Wasserman](#larry-wasserman)  |   [Problems With Bayesian Causal Inference](https://www.youtube.com/watch?v=sZyyaNdvfto)     | 
| [Philip Dawid](#philip-dawid) | [Causal Inference Is Just Bayesian Decision Theory](https://www.youtube.com/watch?v=F_nOhX-Vn1U) |
| [Finnian Lattimore](#finnian-lattimore)| [Causal Inference with Bayes Rule](https://www.youtube.com/watch?v=VoJWIKEF4x8) |
| Panel (Audio) |[Does causality mean we need to go beyond Bayesian decision theory?](https://www.youtube.com/watch?v=Vehb4pYf2L4) |
| [Cheng Zhang](#cheng-zhang) |[Efficient Decision Making with (Causal) Bayesian Deep Learning](https://www.youtube.com/watch?v=w1PvAgkdzKE) |
| Srivas Chennu | [Smooth Sequential Optimisation with Delayed Feedback](https://www.youtube.com/watch?v=BCI4cM64hlE) | 
| Panel (Audio)| [Is Bayesian inference suitable in production?](https://www.youtube.com/watch?v=MW8liCtbEmc) |
| Annadani  Yashas | [Variational Causal Networks: Approximate Bayesian Inference over Causal Structures](https://www.youtube.com/watch?v=8i28DzYrdZU) |
| [James McInerney](#james-mcinerney)  | [Scalable Thompson Sampling for Non-Conjugate Models](https://www.youtube.com/watch?v=qhODJHp0KYM) |



# Talk Abstracts
## Problems With Bayesian Causal Inference - Larry Wasserman
In this talk I'll review the difficulties that arise when using Bayesian inference methods for causal inference. The causal effect
is a functional of the distribution which can be estimated using standard semiparametric techniques.  This yields valid confidence intervals and estimates that converge at a root n rate. In contrast, Robins and Ritov showed that the Bayes estimate is inconsistent. The problem is that the Bayes estimator is biased. Furthermore, the Bayesian credible interval will have very low coverage.

## Causal Inference Is Just Bayesian Decision Theory - Philip Dawid
You may think that statistical causal inference is about inferring causation. You may think that it can not be tackled with standard statistical tools, but requires additional structure, such as counterfactual reasoning, potential responses or graphical representations. I shall try to disabuse you of such woolly misconceptions by locating statistical causality firmly within the scope of traditional Bayesian statistical decision theory. From this viewpoint, the enterprise of ???statistical causality??? could fruitfully be rebranded as ???assisted decision making???.

## Causal Inference with Bayes Rule - Finnian Lattimore
In this talk, I will show how to take a causal graphical model and represent the invariance assumptions underlying it in an ordinary probabilistic graphical model. This allows causal inference with nothing more than Bayes rule, yielding equivalent results to the do-calculus. I hope that drawing a direct connection between causal graphical models and Bayesian modelling helps bridge the gap in how causal inference is conceptualised between these two schools of thought and resolves confusion over questions such as ???should we always condition on all observable data???? There may also be some practical benefits. Encoding structural causal assumptions within a Bayesian framework makes it straightforward to add additional (parametric) assumptions. In addition, we can (in principle) tackle problems that are not identifiable - although in this case aspects of the posterior will remain sensitive to the prior even given infinite data. 


## Efficient Decision Making with (Causal) Bayesian Deep Learning - Cheng Zhang
Real-world decision-making needs to be efficient and robust. Thus, we need a machine learning system that can handle missing data to enable decision-making in any situation. Furthermore, acquiring information can be costly; therefore, personalized information acquisition is required. Lastly, the decision-making process needs to be robust and interpretable. In this talk, I will discuss how we can use (Causal) Bayesian deep learning to achieve efficient decision-making like humans.

## Scalable Thompson Sampling for Non-Conjugate Models - James McInerney
Thompson sampling is a leading Bayesian method for implementing exploration-exploitation in interactive systems. However, it is difficult to apply to non-conjugate models in which the posterior must be approximated. Reliable posterior covariance is challenging to scale with Monte Carlo methods and is underestimated with variational inference. In this talk, I develop methods for Thompson sampling non-conjugate models that are theoretically motivated and simple to implement.

# Speaker Bios
## Larry Wasserman
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/Larry.jpeg" alt="" width="200" class="center" />
</p>

[Larry Wasserman](https://www.stat.cmu.edu/~larry/)
is UPMC University Professor of Statistics and Data Science at Carnegie Mellon University. He also has an appointment in the Machine Learning Department in the School of Computer Science.

## Philip Dawid
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/pd.jpg" alt="" width="200" class="center" />
</p>

[Philip Dawid](http://www.statslab.cam.ac.uk/~apd/) is Emeritus Professor of Statistics, University of Cambridge. For many years he was Professor of Probability and Statistics at University College London. He has served as Editor of Biometrika and of the Journal of the Royal Statistical Society (Series B). He is an elected Fellow of the Royal Society, of the Institute of Mathematical Statistics, of the International Statistical Institute, and of the International Society for Bayesian Analysis (ISBA), and has served as Vice-President of the Royal Statistical Society (RSS) and as President of ISBA, of which he is an honorary lifetime member. Other honours include the Snedecor and DeGroot Prizes, and RSS Guy Medals in Bronze and Silver. His research interests include logical foundations of Bayesian and other schools of probability and statistics, Bayes nets, statistical causality, probability forecasting, and forensic inference.


## Finnian Lattimore
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/Finn.jpg" alt="" width="200" class="center" />
</p>

[Finnian Lattimore](https://scholar.google.com/citations?user=XlzIPUkAAAAJ&hl=en) 
is a Principal Researcher at Gradient Institute where she develops and communicates approaches to machine learning that make explicit the assumptions and value judgments they encode to ensure that AI driven systems satisfy ethical and societal norms. She completed her Ph.D from the Australian National University in 2014, focussing on causal inference in machine learning.


## Cheng Zhang
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/cheng-zhang.jpg" alt="" width="200" class="center" />
</p>

[Cheng Zhang](https://cheng-zhang.org) 
is a senior researcher at the All Data AI group at Microsoft Research Cambridge, UK. Currently, she leads the [Project Azua: Data efficient Decision Making in MSRC](https://www.microsoft.com/en-us/research/project/project_azua/). She is interested in both machine learning theory, including Bayesian deep learning, approximate inference, causality, Bayesian experimental design and reinforcement learning for sequential decision making, as well as various machine learning applications with business and social impact.


## James McInerney
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/James.jpeg" alt="" width="200" class="center" />
</p>

[James McInerney](https://jamesmc.com/about-me) 
is a Senior Research Scientist at Netflix. His research is on Bayesian approaches to machine learning with applications to recommender systems, stochastic processes, and causal reasoning. He was previously a senior researcher at Spotify (New York) and held postdoctoral positions at Columbia University and Princeton University.

## Carlos Cinelli 
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/pic.jpg" alt="" width="200" class="center" />
</p>

[Carlos Cinelli](https://carloscinelli.com/) is a PhD Candidate in Statistics at UCLA. 
He will join the Statistics Department at the University of Washington as an assistant professor, this Fall 2021. 
His work focuses on developing new causal and statistical methods for transparent and robust causal claims in the empirical sciences.

## Ralf Herbrich
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/ralf.jpg" alt="" width="200" class="center" />
</p>

[Ralf Herbrich](https://scholar.google.com.au/citations?user=RuvHkikAAAAJ&hl=en) 
, Senior Vice President Data Science and Machine Learning.
Dr. Ralf Herbrich leads a diverse range of departments and initiatives that have, at their core, research in the area of artificial intelligence (AI) spanning data science, machine learning and economics in order for Zalando to be the starting point for fashion AI. Ralf???s teams apply and advance the science in many established scientific fields including computer vision, natural language processing, data science and economics. Ralf joined Zalando in January 2020.
Previously, he served as Managing Director of the Amazon Development Center in Germany (with its locations in Berlin, Dresden, Aachen and T??bingen) and was Director of Machine Learning at Amazon in Berlin from 2013. Prior to this, he held senior positions at Facebook and Microsoft.

## John Langford
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/jl.jpg" alt="" width="200" class="center" />
</p>

[John Langford](https://www.microsoft.com/en-us/research/people/jcl/) is a Partner Researcher Manager at Microsoft.  He
studied Physics and Computer Science at the California Institute of Technology, earning a double bachelor???s degree in 1997, and received his Ph.D. from Carnegie Mellon University in 2002. Since then, he has worked at Yahoo!, Toyota Technological Institute, and IBM???s Watson Research Center. He is also the primary author of the popular Machine Learning weblog, hunch.net and the principle developer of Vowpal Wabbit. Previous research projects include Isomap, Captcha, Learning Reductions, Cover Trees, and Contextual Bandit learning.


## Diego Legrand
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/Diego.jpg" alt="" width="200" class="center" />
</p>

Diego Legrand is the Lead Machine Learning Engineer of the Contextual Recommendation team at Criteo. His work focuses on implementing deep learning systems in production to recommend the right product in online advertisements without using user history based data. He holds a Master's degree in applied mathematics from Ecole Centrale Paris and previously worked on Bayesian multivariate AB-testing.
