# AIpsych
### How Scaling VLMs Trades Cognitive Biases

Hallucination remains a persistent challenge in Vision-Language Models (VLMs). While usually attributed to technical constraints or sycophancy, these explanations often overlook how hallucinations may mirror human-like cognitive biases. In this work, we propose a psychological taxonomy for VLMs, categorizing biases such as sycophancy, logical inconsistency, and a newly identified behavior: authority bias. To study these, we developed AIpsych, a scalable benchmark designed to reveal psychological tendencies in model responses. Our analysis of varying architectures shows that as model size increases, VLMs exhibit a greater tendency of sycophancy but reduced authority bias—suggesting that increased competence may come at the cost of response integrity. This work suggests a new perspective for understanding hallucination in VLMs and highlights the importance of integrating psychological principles into model evaluation. The benchmark and codes are tested and available in the supplementary material.


<div align="center">
    <img src='img/ques_tree.png'/>
</div>





## 🎈 Quick Start

### Running the Qwen2.5VL model inference using the AIpsych - COCO valid 2014 dataset
```bash
python ./demo/qwen25_inference.py
```

### Evaluate the results 
```bash
python evaluation_v4.py --input './demo/demo_Ovis2-2B.json'
```

