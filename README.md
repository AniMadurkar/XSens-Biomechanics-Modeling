# XSens-Biomechanics-Competition

Abstract:
Through a robust and comprehensive analysis of data collected from XSens IMU sensors during a variety of exercises at varying weights, we propose a generalized and probabilistic modeling approach to quantitatively understand a subject’s form and performance. This is for the objective of offering clinical practitioners useful and practical techniques to provide better guidance in training and rehabilitation. We conclude our approach provides a strong localized and global view into a subject’s fitness behavior through data mining and simulated Bayesian estimation.

Conclusion:
In this study we look at each set by finding the periodic repetitions and calculating average metrics to generalize the activity to a reasonable degree. We focus primarily on the concentric phase of each rep, and this allows us to see whether the subject’s power output, joint angle flexion, grip width, squat depth, and more are within means given the height, weight, and objective of the subject. We add outputs of the sticking points in the bench press and squat to see when there is dramatic decrease in the power output in the concentric phase, which can reflect different potential points of injury/strain and different remedy strategies. The issue with only looking at averages for an activity is that it provides a microscopic view into a given set or a minimal set of workout exercises and this inhibits the trainer from having a macro perspective of coaching a subject to achieving their goals. Due to this, we conduct Bayesian estimation through Monte Carlo Markov Chain models to estimate the probability distribution of power output and elbow/knee flexion which yields insight into how concentrated and variable a given workout was. This approach allows the trainer to conduct simulated models of a workout for a subject which can save the clinic/subject money and time without sacrificing rehabilitation. For future improvements, we would recommend adjusting the weakly informative priors in our models with stronger priors advised by physiotherapists/trainers that allows more precise knowledge to be embedded in the modeling. Additionally, we believe a machine learning predictive approach can also be leveraged to predict what activity a person is doing based on their biometrics and sensor data, and depending on the activity/their performance, these quantitative analyses could be triggered to provide real-time suggestions to encourage better form and performance.
