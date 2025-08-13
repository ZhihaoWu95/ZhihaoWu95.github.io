---
title: "MYOPIA: Protecting Face Privacy from Malicious Personalized Text-to-Image Synthesis via Unlearnable Examples"
collection: publications
category: conferences
permalink: /publication/myopia
excerpt: 'This paper proposes a face privacy protection method for Text-to-Image Synthesis models.'
date: 2025-03-04
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence 2025'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/32075/34230'
citation: 'Wu Z, Cheng Y, Sun T, et al. MYOPIA: Protecting Face Privacy from Malicious Personalized Text-to-Image Synthesis via Unlearnable Examples[C]//Proceedings of the AAAI Conference on Artificial Intelligence. 2025, 39(1): 905-913.'
---

Personalized text-to-image synthesis models, such as DreamBooth, have demonstrated significant potential in creating lifelike images tailored to a specific individual by fine-tuning from a limited set of face images and simple prompts. However, if misused, these model could pose a serious risk of privacy infringement by generating harmful images containing violent or pornographic content. To tackle this issue, this paper introduces MYOPIA, a method that renders facial images unlearnable by incorporating error-minimizing perturbations. These meticulously designed perturbations enables the model to quickly overfit to them, resulting in a swift reduction in loss and the cessation of model fine-tuning, effectively preventing the model from capturing genuine facial features. Moreover, to ensure the imperceptibility and robustness of the perturbations, we utilize the Just-Noticeable-Difference and Expectation-of-Transformation techniques to regulate both their location and intensity. Evaluation on two face dataset, ie, VGGFace2 and CelebA-HQ, with various model versions illustrates the effectiveness of our approach in preserving personal privacy. Furthermore, our method showcases robust transferability across diverse model versions and demonstrates resilience against various image pre-processing techniques.
