### About this Repository

Murre and Dros (2015) used multiple studies to validate their findings in replicating the work on the "forgetting curve," originally pioneered by Ebbinghaus. These parameter values are based on Ebbinghaus's (1880) work.

Walsh et al. (2018) conducted an analysis of three models of the spacing effect in learning.

In this code, I reference the ACT-R model (Pavlik and Anderson, 2005), expanding upon its result, the activation level, by applying the work done by Murre and Dros.

### The Memory Chain Model, a model of forgetting and amnesia

![Memory Chain Model](mcm.png)

- *myu_1* is the initial strength of the memory traces in store 1,
- *a_1* is the decay rate in store 1,
- *myu_2* is the rate of consolidating the contents of store 1 to store 2, and
- *a_2* is the decay rate in store 2

Under the conditions of this experiment, store 1 is the hippocampus, where memory exponentially declines in intensity and store 2 is the neocortex, where memory contents are steadily transferred for long-term retention and decline at a lower rate.

I applied Murre and Dros' equation to Walsh et al.'s (2018) work investigating [ACT-R](Pavlik_Anderson_2005.pdf) and two other models of spaced memory practice and, I think, expanded the accuracy of the activation likelihood predictions made by ACT-R's simplified implementation of Ebbinghaus' classic forgetting curve.

### ACT-R Activation Equation

![ACT-R Activation Equation](act-r_activation.png)

Further work could use ACT-R's models of spaced practice and retention; however, I strongly suggest investigating Walsh et al.'s claims that ACT-R is not the best means (of the three they investigated) to model accelerated relearning.

### Sources

Murre JMJ, Dros J. (2015). Replication and Analysis of Ebbinghaus’ Forgetting Curve. PLoS ONE 10(7): e0120644. doi:10.1371/journal. pone.0120644

Ebbinghaus H. (1880). Urmanuskript "Ueber das Gedächtniß". Passau: Passavia Universitätsverlag.

Pavlik, PI & Anderson, JR. (2005). Practice and forgetting effects on vocabulary memory: An Activation-based model of the spacing effect. Cognitive Science, 29, 559-586.

Walsh, M.M., Gluck, K.A., Gunzelmann, G., Jastrzembski, T., Krusmark, M., Myung, J.I., Pitt, M.A., & Zhou, R. (2018). Mechanisms underlying the spacing effect in learning: A comparison of three computational models. Journal of Experimental Psychology: General, 147, (9):1325-1348.
