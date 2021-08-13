---
layout: section
---

<img height="80" src="{{ site.logo }}" class="rounded mx-auto d-block" alt="logo">


|Speaker|Monday 16 Aug | Monday 16 Aug | Sunday 15 Aug | Sunday 15 Aug| Sunday 15 Aug |
|-------|--------------|---------------|---------------|--------------|---------------|
|       |Singapore     |Sydney         |          Paris|        London|  San Francisco|   
| Welcome | 0.45-13.00 | 2.45 | 18.45 | 17.45 | 9.45 | 12.45 |
| [Larry Wasserman](#larry-wasserman) - [Problems With Bayesian Causal Inference](#problems-with-bayesian-causal-inference---larry-wasserman)  |       13.00 -13.45 |           3.00|          19.00|         18.00|          10.00|   
| [Philip Dawid](#philip-dawid) - [Causal Inference Is Just Bayesian Decision Theory](#causal-inference-is-just-bayesian-decision-theory---philip-dawid) |1.45-2.30|3.45|19.45|18.45|10.45|
| [Finnian Lattimore](#finnian-lattimore) - [Causal Inference with Bayes Rule](#causal-inference-with-bayes-rule---finnian-lattimore)| 2.30-3.15|4.30|20.30|19.30|11.30|
| [Theory Panel](#theory-panel) | 3.15-4.00|5.15    |  21.15   |  20.15   |  12.15   |
| [Cheng Zhang](#cheng-zhang) - [Simultaneous missing value imputation and causal discovery](#vicause-simultaneous-missing-value-imputation-and-causal-discovery---cheng-zhang)| 4.00-4.45 | 6.00   |  22.00   |  21.00   |  13.00   |
| Contributed talk: [Smooth Sequential Optimisation with Delayed Feedback](https://bcirwis2021.github.io/Smooth.pdf) - Srivas Chennu  | 4.45-5.05 | 6.45 | 22.45 | 21.45 | 13.45 | 
| Break | 5.05-6.00 | 7.05 | 23.05 | 22.05 | 14.05 |
| [Poster Session](https://bcirwis2021.github.io/accepted.html) | 6.00-6.45 |8.00|24.00|23.00|15.00|
| [Bayes in Production Panel](#bayes-in-production-panel) | 6.45-7.30|8.45|00.45|23.45|15.45|
| Contributed talk: [Variational Causal Networks: Approximate Bayesian Inference over Causal Structures](https://bcirwis2021.github.io/Variational.pdf) - Annadani  Yashas |7.30-7.50|9.30|1.30|00.30|16.30|
| [James McInerney](#james-mcinerney) - [Scalable Thompson Sampling for Non-Conjugate Models](#scalable-thompson-sampling-for-non-conjugate-models---james-mcinerney) |7.50-8.35|9.50|1.50|00.50|16.50|


# Theory Panel

## Does causality mean we need to go beyond Bayesian decision theory?

[Philip Dawid](#philip-dawid)

[Larry Wasserman](#larry-wasserman)

[John Langford](#john-langford)

[Finnian Lattimore](#finnian-lattimore)

[Carlos Cinelli](#carlos-cinelli)


# Bayes in Production Panel

## Is Bayesian inference suitable in production?

[Ralf Herbrich](#ralf-herbrich)

[James McInerney](#james-mcinerney)

[Cheng Zhang](#cheng-zhang)

[John Langford](#john-langford)

[Diego Legrand](#diego-legrand)


# Talk Abstracts
## Problems With Bayesian Causal Inference - Larry Wasserman
In this talk I'll review the difficulties that arise when using Bayesian inference methods for causal inference. The causal effect
is a functional of the distribution which can be estimated using standard semiparametric techniques.  This yields valid confidence intervals and estimates that converge at a root n rate. In contrast, Robins and Ritov showed that the Bayes estimate is inconsistent. The problem is that the Bayes estimator is biased. Furthermore, the Bayesian credible interval will have very low coverage.

## Causal Inference Is Just Bayesian Decision Theory - Philip Dawid
You may think that statistical causal inference is about inferring causation. You may think that it can not be tackled with standard statistical tools, but requires additional structure, such as counterfactual reasoning, potential responses or graphical representations. I shall try to disabuse you of such woolly misconceptions by locating statistical causality firmly within the scope of traditional Bayesian statistical decision theory. From this viewpoint, the enterprise of “statistical causality” could fruitfully be rebranded as “assisted decision making”.

## Causal Inference with Bayes Rule - Finnian Lattimore
In this talk, I will show how to take a causal graphical model and represent the invariance assumptions underlying it in an ordinary probabilistic graphical model. This allows causal inference with nothing more than Bayes rule, yielding equivalent results to the do-calculus. I hope that drawing a direct connection between causal graphical models and Bayesian modelling helps bridge the gap in how causal inference is conceptualised between these two schools of thought and resolves confusion over questions such as “should we always condition on all observable data?” There may also be some practical benefits. Encoding structural causal assumptions within a Bayesian framework makes it straightforward to add additional (parametric) assumptions. In addition, we can (in principle) tackle problems that are not identifiable - although in this case aspects of the posterior will remain sensitive to the prior even given infinite data. 


## VICAUSE: Simultaneous Missing Value Imputation and Causal Discovery - Cheng Zhang
Missing values constitute an important challenge in real-world machine learning for both prediction and causal discovery tasks. However, only few methods in causal discovery can handle missing data in an efficient way, while existing imputation methods are agnostic to causality. In this talk, I will introduce VICAUSE, a novel approach to simultaneously tackle missing value imputation and causal discovery efficiently with deep learning. Particularly, we propose a generative model with a structured latent space and a graph neural network-based architecture, scaling to a large number of variables. Moreover, our method can discover relationships between groups of variables which is useful in many real-world applications, such as in the education domain. In the end, I will discuss the opportunities and challenges of using VICause in interactive systems.

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
Dr. Ralf Herbrich leads a diverse range of departments and initiatives that have, at their core, research in the area of artificial intelligence (AI) spanning data science, machine learning and economics in order for Zalando to be the starting point for fashion AI. Ralf’s teams apply and advance the science in many established scientific fields including computer vision, natural language processing, data science and economics. Ralf joined Zalando in January 2020.
Previously, he served as Managing Director of the Amazon Development Center in Germany (with its locations in Berlin, Dresden, Aachen and Tübingen) and was Director of Machine Learning at Amazon in Berlin from 2013. Prior to this, he held senior positions at Facebook and Microsoft.

## John Langford
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/jl.jpg" alt="" width="200" class="center" />
</p>

[John Langford](https://www.microsoft.com/en-us/research/people/jcl/) is a Partner Researcher Manager at Microsoft.  He
studied Physics and Computer Science at the California Institute of Technology, earning a double bachelor’s degree in 1997, and received his Ph.D. from Carnegie Mellon University in 2002. Since then, he has worked at Yahoo!, Toyota Technological Institute, and IBM‘s Watson Research Center. He is also the primary author of the popular Machine Learning weblog, hunch.net and the principle developer of Vowpal Wabbit. Previous research projects include Isomap, Captcha, Learning Reductions, Cover Trees, and Contextual Bandit learning.


## Diego Legrand
<p style="text-align:center;">
<img src="https://bcirwis2021.github.io/Diego.jpg" alt="" width="200" class="center" />
</p>

Diego Legrand is the Lead Machine Learning Engineer of the Contextual Recommendation team at Criteo. His work focuses on implementing deep learning systems in production to recommend the right product in online advertisements without using user history based data. He holds a Master's degree in applied mathematics from Ecole Centrale Paris and previously worked on Bayesian multivariate AB-testing.
