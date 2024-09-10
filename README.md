# Wring of Thought: Can LLMs Creatively Translate Puns as an Open-Ended Language Game? 🤹‍♀️🧠🎉

Welcome to the whimsical world of **Wring of Thought**! Here, we dive into the wild and wacky realm of translating puns from Chinese to English (and vice versa) using large language models (LLMs). Inspired by the clever wordplay in TV shows like "2 Broke Girls" and "The Big Bang Theory", we're pushing the boundaries of machine translation. Let's see if our AI can keep up with the punny humans! 🤖💬😂

## Why "Wring of Thoughts"? 🤔🌀

Ever heard of the Chinese idiom "绞尽脑汁" (jiǎo jìn nǎo zhī), which means "to wring one's brains"? That's our inspiration! Picture this: an AI going into overdrive, furiously brainstorming and juggling words to translate puns between Chinese and English. It's a concept rooted in the idea of exhausting all possible word associations and connections to achieve a clever and accurate translation. Hence, we proudly present "Wring of Thoughts" – where our AI's brain gets a thorough workout! 🏋️‍♂️💡

## Why This is Cool 😎✨
- **No Human Experts Needed**: Our LLMs are the stars of this show, performing without human intervention. 🌟
- **Minimal Labeling**: Who needs exhaustive data labeling when you have a brainy AI? 🧠💻
- **Automated Quantitative Evaluation**: We measure success with metrics, not just gut feelings. 📊📈

## The Mission 🎯🚀
We're introducing **WoT-CN-EN** (Wring-of-Thought-Chinese-English), a task designed to test the prowess of LLMs in translating puns between these two languages. This isn't just any translation challenge; it's an open-ended language game that involves creative thinking and linguistic reasoning. 🧩🔤🧩

**Key Goals**
1. **Present the Task**: WoT-CN-EN, a creative language game for puns translation. 📝🎮
2. **Optimize Translation Strategies**: Use variables from pragmatic translation to enhance strategies. 🛠️🔧
3. **Evaluate Translation Quality**: Implement quantitative metrics to assess the outcome. 🧮✅

## Beyond Translation 🌐📚
Through this pun-tastic task, we're proposing a new CoT-family prompting method to inspire more creative writing and complex cross-linguistic literary tasks. ✍️🎭🌍

## Installation and Usage 🛠️🚀

### Prerequisites 📋🔧
- Python 3.x
- Relevant NLP libraries (e.g., Hugging Face Transformers)

### Installation 💻⚙️
```bash
git clone https://github.com/your-repo/wring-of-thoughts.git
cd wring-of-thoughts
pip install -r requirements.txt
```

### Running the Main Experiment 🧪🔍
Our main experiment uses a multi-agent framework. The baseline strategies are:
- **Vanilla**: Plain and simple, like vanilla ice cream. 🍦
- **ToT**: "Tree of Thoughts" – branching out in all directions. 🌳💭
- **BoT**: "Bag of Tricks" – a little bit of this, a little bit of that. 🎩✨

Run the experiment with:
```bash
python main_experiment.py --task WoT-CN-EN --strategy multi_agent
```

### Ablation Studies 🔬🧩
To see what makes our puns tick, we perform ablation experiments. Test the effects of different components:

#### With or Without Translation Strategy 🔄🗣️
```bash
python ablation_study.py --combine translation_strategy
python ablation_study.py --omit translation_strategy
```

#### With or Without Chain-of-Thought 🤔➡️💭
```bash
python ablation_study.py --apply chain_of_thought
python ablation_study.py --omit chain_of_thought
```

#### Specific Adjustments to Agent Architecture 🏗️🧩
```bash
python ablation_study.py --adjust agent_architecture
```

## Our Vision 🌟🌍
By tackling the challenge of pun translation, we're proposing a novel chain-of-thought prompting method. This approach aims to inspire more creative writing tasks and handle complex cross-linguistic literary projects. Our dream is to make AI not just smart, but witty and creative too! 🧠✨🤹‍♂️

## References

```
https://github.com/liuhuanyong/ChineseHumorSentiment.git
```

```
@inproceedings{chen-etal-2024-u,
    title = "Are {U} a Joke Master? Pun Generation via Multi-Stage Curriculum Learning towards a Humor {LLM}",
    author = "Chen, Yang  and
      Yang, Chong  and
      Hu, Tu  and
      Chen, Xinhao  and
      Lan, Man  and
      Cai, Li  and
      Zhuang, Xinlin  and
      Lin, Xuan  and
      Lu, Xin  and
      Zhou, Aimin",
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Findings of the Association for Computational Linguistics ACL 2024",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand and virtual meeting",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.findings-acl.51",
    pages = "878--890",
    abstract = "Although large language models (LLMs) acquire extensive world knowledge and some reasoning abilities, their proficiency in generating humorous sentences remains a challenge. Previous research has demonstrated that the humor generation capabilities of ChatGPT are confined to producing merely 25 unique jokes. In this work, we concentrate on endowing LLMs with the ability of generating puns, a particular category of humor by preference learning method. We propose a multi-stage curriculum preference learning framework to optimize both pun structure preferences and humor preferences. Specifically, we improve the Direct Preference Optimization (DPO) algorithm to address the challenge of multi-objective alignment problem. Besides, to facilitate further advancement in this field, we collect a Chinese Pun (ChinesePun) dataset, containing 2.1k puns and corresponding annotations. Experimental results on both Chinese and English benchmark datasets demonstrate that our method significantly outperforms all the baseline models.",
}
```

```
@inproceedings{simpson2019predicting,
   author    = {Edwin Simpson and Do Dinh, Erik-L{\^{a}}n and
                Tristan Miller and Iryna Gurevych},
   title     = {Predicting Humorousness and Metaphor Novelty with
                {Gaussian} Process Preference Learning},
   booktitle = {Proceedings of the 57th Annual Meeting of the
                Association for Computational Linguistics (ACL 2019)},
   month     = jul,
   year      = {2019},
   pages     = {5716--5728},
}
```

## Contact Us 📬💬
Got questions, feedback, or just want to share a good pun? Reach out to us at:

- **Email**: mayiran@bupt.edu.cn

Let's make the world a funnier place, one translation at a time! 🌏😂🔤

Happy punning! 🎉🤖😄
