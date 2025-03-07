---
layout: page
title: Evaluating Persuasiveness of Large Language Models
description: Project for LLMs (11-667), CMU
img: 
importance: 1
category: projects
related_publications: false
github: https://github.com/shiviigupta/persuasive-language-model
pdf: https://drive.google.com/file/d/1ARfnfa8JF0g7J46Ftup836wwT5sK_jaX/view?usp=sharing
---
<style>
.responsive-wrap iframe{ max-width: 100%;}
</style>

Fall 2024 <br>

## **Project Overview**
Relevant Links: <br>
[Anthropic's persuasion blog](https://www.anthropic.com/research/measuring-model-persuasiveness) <br>
[Anthropic/persuasion on Huggingface](https://huggingface.co/datasets/Anthropic/persuasion)
- Designed language models for rating persuasiveness by instruction tuning and fine-tuning open-sourced language models on Anthropic Persuasion dataset, achieving a Cohen’s Kappa of 0.3 for zero shot with human ratings
- Fine-tuned GPT models for generating persuasive arguments for given claims, resulting in a perplexity score of 2082 demonstrating complex and nuanced generations

---

## **Example Argument Comparison**

**Claim: Self-driving cars will increase safety and should replace human drivers.**

<div class="row">
  <div class="col-md-6" style="font-size: 10px;">
    <h4>gpt-4o mini</h4>
    <p>Self-driving cars will significantly enhance road safety and should replace human drivers for several compelling reasons: <br>
        1. <b>Reduction in Human Error</b>: Statistics reveal that approximately 94% of traffic accidents are caused by human error, including distractions, fatigue, and impaired judgment. Self-driving cars are equipped with advanced sensors, cameras, and artificial intelligence that allow them to assess their surroundings in real-time and make decisions based on data, eliminating the possibility of human error. By taking human fallibility out of the equation, self-driving cars have the potential to drastically reduce the number of accidents on our roads.<br>
        2. <b>Consistent Reaction Times</b>: Human drivers often struggle with reaction times during high-pressure situations, which can lead to catastrophic outcomes. Autonomous vehicles (AVs) can process information and respond to unforeseen circumstances much faster than a human can. With their ability to analyze vast amounts of data instantaneously, self-driving cars can react to obstacles and emergencies preemptively, providing a level of decision-making that is currently unattainable for human drivers. <br>
        3. <b>Predictable Driving Patterns</b>: Self-driving cars operate based on predefined algorithms designed to maximize safety and efficiency. Unlike human drivers, who may engage in unpredictable behaviors due to emotional states or distractions, autonomous vehicles adhere to traffic laws and safety protocols consistently. This predictability creates a safer driving environment, as self-driving cars can more effectively anticipate and react to the actions of both vehicles and pedestrians. []
</p>
  </div>
  <div class="col-md-6" style="font-size: 10px;">
    <h4>gpt-4o finetuned for persuasiveness</h4>
    <p>In this fast-paced, modern world, self-driving cars represent not just innovation, but a revolutionary leap towards a safer, more efficient society. These autonomous vehicles are not just a marvel of technological advancement; they are the key to unlocking a future with dramatically reduced traffic fatalities, injuries, and congestion.<br>
    The facts speak for themselves. Studies have shown that over 90% of traffic accidents are caused by human error. By replacing fallible human drivers with precise, unemotional algorithms, we can dramatically lower these disturbing numbers. Self-driving cars are equipped with an arsenal of sensors, cameras, and advanced computing power, allowing them to detect obstacles and respond to hazards with lightning-fast reflexes that no human could ever match. Imagine a world where your morning commute is worry-free, where you can read, work, or even take a nap instead of navigating stoplights and on-ramps.<br>
    The societal benefits are undeniable. Fewer accidents mean less strain on our healthcare system, and less grief for families that have lost loved ones. Self-driving cars open up a world of mobility for the elderly and disabled, who can regain independence and autonomy. They also free up valuable time that we currently spend behind the wheel, allowing us to be more productive, more rested, and ultimately, happier.<br>
    The future is autonomous. It's time to embrace it.
</p>
  </div>
</div>

---

## **Project Resources**
[Github Repo](https://github.com/shiviigupta/persuasive-language-model) <br>
[Presentation Slides](https://docs.google.com/presentation/d/12q8UaCYGNGlH2Rv7pUfdggLOcynsWnc6e_uK9apHgsQ/edit#slide=id.g2d669d5524a_0_114) <br>
[Final Report](https://drive.google.com/file/d/1ARfnfa8JF0g7J46Ftup836wwT5sK_jaX/view?usp=sharing)
