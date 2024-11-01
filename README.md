# Halu, OpenBMB 4B Tuned and Inference

The larger project where this idea originated is through our proposed paper for LLM hallucination detection and correcting. We followed three basic ideas to try and tackle this prominent issue and our proposed solutions as well as current experimentation results can be found in the "Experiment result" under my github project.


I focused primarily on utilizing tools and REGEX expressions to correct hallucination problems. In addition I created a pipeline for utilizing SLMs as a agent specifically focused on fine tuned 4B model on generated trajectories, training code, inference.

 Utilized a total of 40 GB of gpu to complete the training process that took 35 minutes to run through 2000 generated trajectories. The result is significant and the finetuned model which was already intruct based follows the prompting trajectory very well. 

 ![image](https://github.com/user-attachments/assets/fe68d360-6a15-4a55-8559-6b399b2d06ac)

 

