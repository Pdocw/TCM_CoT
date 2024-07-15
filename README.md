## TCM CoT: Controllable Notes Generation for Traditional Chinese Medicine Medical Records with Large Language Models

#### Methods

##### Step 1: Divide the medical record notes into four parts by using the LLMs.

<p align="center">
  <img src="img/Figure 1.png" style="width: 90%; height: auto;">
</p>

##### Step 2: Based on the four-part medical record notes obtained in the previous step, fine-tune a large language model that can generate four-part medical record notes based on medical records.

<p align="center">
  <img src="img/Figure 2.png" style="width: 90%; height: auto;">
</p>

##### Step 3: Based on the four-part medical record notes obtained in the previous step and the previous medical records information, fine-tune a large language model that can generate complete medical record notes, and use Direct Preference Optimization to optimize the model.

<p align="center">
  <img src="img/Figure 3.png" style="width: 90%; height: auto;">
</p>
