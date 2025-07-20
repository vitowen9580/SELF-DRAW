# <img src="image/SELF-DRAW1.png" alt="icon" width="60"/> SELF-DRAW

# Abstract
Unpaired training methods have garnered increasing interest as a practical approach for mitigating adverse weather effects, as they do not require explicit clean-to-degraded image pairs. While prior works often enhance restoration quality by employing various attention mechanisms, such as transmission maps or rain masks, these methods typically rely on attention maps specifically tailored to individual weather types. Consequently, a unified architectural approach for handling diverse degradations in an unpaired setting remains largely underexplored. To address these challenges, we propose SELF-DRAW, a **Self**-**D**egradation Aware Unpaired **R**estoration method leveraging a Uniform **A**rchitecture for Adverse **W**eather Removal. This unified framework is designed to manage various weather-related degradations in an unpaired setting without requiring architecture modifications. It consists of three main components: the Degradation Restoration Network (DRNet), designed to transform degraded images into clean ones; the Weather-Agnostic Degradation-Aware Network (WaDaNet), which identifies pixel-level degradations independent of weather type to guide the restoration process; and Cross Attention Gates (CAGs), which enable adaptive fusion of multi-scale features for more precise degradation suppression. Extensive experiments on six distinct weather-degraded datasets demonstrate significantly improved and robust restoration performance compared to existing methods. Furthermore, the proposed SURE-Net significantly improves mean Average Precision (mAP) for object detection on degraded images by an average of 18%, underscoring its strong generalization ability and practical utility for downstream computer vision tasks.
<img src="image/Fig3.JPG" alt="icon"/>


# Using the code:
Clone this repository:
```bib
https://github.com/vitowen9580/SELF-DRAW.git
```bib
