## CogInstuct
Dataset for paper: CogIntruct: Cognition Chain Reasoning for Explainable Psychological Stress Detection on Social Media
### Overview
CogInstruct is a novel instruction-tuning dataset designed to enhance the reasoning ability of psychological stress detection models by integrating psychological cognitive theory. 
CogInstruct is constructed using a three-stage self-reflective annotation pipeline, allowing Large Language Models (LLMs) to autonomously generate and refine instructional data. The dataset is based on Cognition Chain, a structured reasoning format inspired by cognitive appraisal theory, which explicates stress generation through a step-by-step cognitive perspective: Stimulus → Evaluation → Reaction → Stress State.
### Dataset Construction Framework
<img src='https://github.com/XinWangcs/CogInstuct/blob/main/framework.png' width=80%/>
### Data Format
The data is provided in Alpaca format like:
```json
{
  "instruction": "human instruction",
  "input": "human input",
  "output": "model response"
}
```
