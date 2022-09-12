# Multilevel Bayesian analysis combined with Multiple Imputation

This data set comes from a singing experiment. One of the tasks (analyzed here) had participants vocally imitate a 4-tone melody, six times. In total there were three ascending melodies and three descending ones and the melodies were
randomized. The singing task gave a score for each note sung in a melody. For instance, after singing back the a 4-note melody, participants would get 4 scores (one for each note of the melody sung). These scores are signed pitch-deviation scores that are computed by subtracting the value of the sung pitch from the value of the imitated target pitch 
(i.e. score = sung pitch – target pitch). The closer to zero the value is, the more accurate the pitch sung is (relative to the target pitch). The unit of the score is CENT which is a logarithmic unit of measure used for musical interval. It measures the ratio between two frequencies.

The design of this experiment was a pretest-posttest within subject design with four different conditions (i.e. sham/placebo brain simulation, visual cortex brain simulation , left cerebellum brain simulation , right cerebellum brain simulation). Participants did the singing test once before brain stimulation and once after brain stimulation.

The variables are:

* **Imitation 3**: Participant ID
* **PRE_S**: Sham pretest stimulation condition
* **POST_S**: Sham posttest stimulation condition
* **PRE_RC**: Right Cerebellum pretest stimulation condition
* **POST_RC**: Right Cerebellum posttest stimulation condition
* **PRE_V**: Visual cortex pretest stimulation condition
* **POST_V**: Visual cortex posttest stimulation condition
* **PRE_LC**: Left Cerebellum pretest stimulation condition
* **POST_LC**: Left Cerebellum posttest stimulation condition

