

### The four steps of Bayesian modelling
#### Step 1: Generative model
**a)** Draw a diagram where each node is a variable and each arrow has a dependency. Observations are at the bottom
**b)** For each variable:
	Write eq of its prob. distribution
	![[Pasted image 20231123133705.png| 200]]
#### Step 2: Bayesian inference decision rule
**a) Compute** posterior over the world sttate of interest given observations.

**b)** Specify the read-out of the posterior
![[Pasted image 20231123134002.png| 200]]
#### Step 3: Response prob
![[Pasted image 20231123134053.png|300]]
#### Step 4: Model fitting and model comparison



![[Pasted image 20231123134147.png |200]]




---

Low contrast stimuli Perceived to be slower


In visual perception, low-contrast stimuli (e.g., a gray object moving against a background of a
different shade of gray) appear to move slower than high-contrast stimuli (for example, a white object moving against the same background) that are in reality moving at the same speed [169]. Weiss and colleagues explained this and many other puzzling visual illusions as resulting from the brain’s use of a prior distribution over speed that is higher for lower speeds (a so-called low-speed prior) [189]. A lower-contrast object provides less reliable information, which means that the likelihood function is wider. This results in a posterior estimate that is shifted more towards the mean of the prior. If the prior peaks at 0, then the perceived speed will be shifted towards a lower value when contrast is lower. Subsequently, the Bayesian model for visual motion perception got further refined by estimating the shape of the prior [167].