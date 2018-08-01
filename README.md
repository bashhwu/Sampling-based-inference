# Sampling-based-inference

Let me first introduce you  to the fundamnetal formula of bayesianism: Bayes rule which is defined as: 

                                 posterior=(likelihood*prior)/marginal likelihood
                                 
The key goal of any proposed probabilistic model is to compute the posterior distribution and then the predictive distribution by integrating over the posterior distribution. 

- The first question that might come to your mind is " why to approximate the posterior?". 
- Cannot we compute the exact inference?.

Well, if the prior is conjugate for the likelihood, the posterior is of the same family of the prior. if this not the case and the marginal likelihood is a high-dimensional integral, it would not be feasible to compute the posterior analytically. Therefore  approximating methods are used. These methods can be divided intow two main categories: sampling-based and deterministic methods. 
While the latter includes variational inference, the former contains MCMC, Gibbs and HMC. This repository will focus on the former by providing the intuitive explanations for such methods. 

We will mention the URLs of sites where codes are partially or entirely taken. 
