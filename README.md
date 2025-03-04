# OSrCIR

## Overview
OSrCIR is a novel method for **Composed Image Retrieval (CIR)**, which finds target images by modifying a reference image based on user instructions. This is useful in internet search and e-commerce for tasks like scene image search and product recommendations.

## Contribution
1. **One-stage Reflective Chain-of-Thought Reasoning**: Unlike traditional two-stage methods, OSrCIR directly processes both the reference image and modification text in a single step, reducing information loss and improving retrieval accuracy.
2. **Multimodal Large Language Models (MLLMs) for Enhanced Reasoning**: By leveraging MLLMs, OSrCIR better retains critical visual details, leading to more precise target image retrieval.
3. **Improved Interpretation Ability**: OSrCIR enhances the alignment between modification intent and contextual cues from reference images, leading to more accurate and interpretable retrieval results.

## Status
✅ Paper accepted at **CVPR 2025**

⏳ Example code coming soon

🔜 Full release after the official publication

## Stay Updated
Watch or star this repository to get notified about the release.

## Contact
For questions or collaboration inquiries, reach out via [your email or GitHub Issues section].

## Citing

If you found this repository useful, please consider citing:

```bibtex
@misc{tang2024reasonbeforeretrieveonestagereflectivechainofthoughts,
      title={Reason-before-Retrieve: One-Stage Reflective Chain-of-Thoughts for Training-Free Zero-Shot Composed Image Retrieval}, 
      author={Yuanmin Tang and Xiaoting Qin and Jue Zhang and Jing Yu and Gaopeng Gou and Gang Xiong and Qingwei Ling and Saravan Rajmohan and Dongmei Zhang and Qi Wu},
      year={2024},
      eprint={2412.11077},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2412.11077}, 
}
```

## Credits
- Thanks to [CIReVL](https://github.com/ExplainableML/Vision_by_Language) authors, our baseline code adapted from there.
