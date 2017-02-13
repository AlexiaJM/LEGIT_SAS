# LEGIT_SAS
SAS macros for the Latent Environmental &amp; Genetic InTeraction (LEGIT) model.

*R package vs SAS macro*: The R package LEGIT provides similar functions but the implementation is incredibly faster. In R, it is also much easier to set the model properly with a single formula instead of the clunky way it is done in SAS. The stepwise search function in R is also much better and does multiple steps (instead of just one step in SAS). It provides, forward, backward, stepwise-forward and stepwise-backward search instead of just forward search. It is completely automatic but can also be runned in interactive mode where you choose which variable to add at every step based on the information shown to you. The only thing that the R package cannot do is mixed models.

Therefore, for fixed-effect models I highly recommend using R exclusively and for mixed models, I recommend using the stepwise search function in R to find the best subset of variables assuming no random effects and then refitting the best model in SAS with the random effects.
