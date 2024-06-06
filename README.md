# INTERSPEECH_Media

<p align="justify">
This repository contains media files that enhance the clarity of our paper titled "Rapport-Driven Virtual Agent: Rapport Building Dialogue Strategy for Improving User Experience at First Meeting" which will be presented at INTERSPEECH 2024. The repository includes example prompts and dialogue samples for both free-form and predefined dialogue strategies. Notes: If you need the full prompts, please contact me at: 	muhammad_yeza.baihaqi.lx2@naist.ac.jp
</p>

## 1. Prompts

<p align="justify">
We implemented two different dialogue strategies: free-form interaction and a predefined scenario.
</p>

### Free-Form Dialogue Strategy

<p align="justify">
We utilized GPT-3.5-Turbo to develop an agent with a free-form dialogue strategy. Using a chat completion function, the model was initially prompted before the conversation started. Following this setup, the model generated responses independently, continually referring back to the initial prompt throughout the conversation. This approach enabled a more dynamic and adaptable dialogue, enhancing rapport-building.
</p>

- **Example LLM prompt for free-form dialogue strategy implementation:**

<img src="https://github.com/yezato11/INTERSPEECH_Media/assets/103475689/58af4d97-67bb-4000-bca0-9e308ffb61e6" alt="Free Rapport Agent example prompt" width="900"/>

### Predefined Scenario Dialogue Strategy

<p align="justify">
For developing our agent based on a predefined scenario dialogue strategy, we used the completion type of GPT-3.5-Turbo, specifically GPT-3.5-Turbo-Instruct. This model was prompted at each dialogue turn using a completion function. We preferred it for its proficiency in handling focused single-input tasks over chat completion models. Unlike chat completion, which could introduce contextual ambiguity, the completion model emphasized simplicity for predefined sequence implementations. To ensure contextual coherence, utterances from previous turns were incorporated into the prompts for subsequent turns.
</p>

- **Example LLM prompt for predefined dialogue strategy implementation:**

<img src="https://github.com/yezato11/INTERSPEECH_Media/assets/103475689/b4b653e1-7977-480a-81ac-075e1acef1f6" alt="Predefined Rapport Agent example prompt" width="800"/>

## 2. Dialogue Samples

### Free-Form Dialogue Strategy

<p align="justify">
In the comparison of dialogue strategies between the Free Rapport Agent and the Predefined Rapport Agent, the superiority of the Free Rapport Agent lies in its adaptability. The Free Rapport Agent's flexibility enables dynamic exploration of user interests, utilizing rapport-building utterances contextually.
</p>

- **Excerpt from Small Talk with Free Rapport Agent:**

<img src="https://github.com/yezato11/INTERSPEECH_Media/assets/103475689/a442e038-b304-4607-9ec5-e01866d923b5" alt="Excerpt from Small Talk with Free Rapport Agent" width="500"/>

### Predefined Scenario Dialogue Strategy

<p align="justify">
The Predefined Rapport Agent's reliance on predetermined sequences can hinder the fluidity of conversation. As shown in the illustration below, when a user shows interest in visiting Europa Park, the Predefined Rapport Agent may struggle to smoothly transition into discussing specific park aspects due to its scenario, such as delivering a question and encouragement. This limitation may negatively impact naturalness, satisfaction, and usability. Consequently, the Free Rapport Agent is perceived as more relevant and comfortable to interact with.
</p>

- **Excerpt from Small Talk with Predefined Rapport Agent:**

<img src="https://github.com/yezato11/INTERSPEECH_Media/assets/103475689/65b0e27e-3902-4475-9265-ca847aec8720" alt="Excerpt from Small Talk with Predefined Rapport Agent" width="500"/>

