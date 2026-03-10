# Made by human, not by gen-AI 




# THIS IS A WORK IN PROGRESS AND NOT MEANT TO BE FINAL, INFORMATION MUST BE DOUBLE CHECKED AND CORRECTED 


This is a repository that aims to provide a **collection of badge to symbolize** that you didn't use generative AI (aka LLMs) for the creation of your project. By using this, we expect that you only use ai for less than 5% of your project. 

This repository is accompanied by this explaination file that tries to use **scientific research** to support every claim. 


# Badge usage

You can copy paste code to your repository or use directly the logos in your project.

```md
## Made by human

<a href="https://github.com/Supercip971/by-human">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-dark.svg">
  <img height="96" align="right" alt="Made by humand, not by gen AI badge" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-light.svg">
</picture>
</a>

[Project name] is made by **Humans**, and not by a generative AI.

More information can be linked to the [by-human](https://github.com/Supercip971/by-human) repository.
```


## Made by human

<a href="https://github.com/Supercip971/by-human">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-dark.svg">
  <img height="96" align="right" alt="Made by humand, not by gen AI badge" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-light.svg">
</picture>
</a>

[Project name] is made by **Humans**, and not by a generative AI.

More information can be linked to the [by-human](https://github.com/Supercip971/by-human) repository.


## Raw badges 

<table align="center">
	<thead>
		<td>
			<b>Name</b>
		</td>
		<td>
			<b>Picture</b>
		</td>
	</thead>
    <tr>
		<td>
            transparent-dark.svg
        </td>
		<td>
			<img width="306" alt="transparent dark mode" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-dark.svg">
		</td>
	</tr>
    <tr>
		<td>
            transparent-light.svg
        </td>
		<td>
			<img width="306" alt="transparent-light" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-light.svg">
		</td>
	</tr>
    <tr>
		<td>
            transparent-slim-dark.svg
        </td>
		<td>
			<img width="306" alt="transparent dark mode" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-slim-dark.svg">
		</td>
	</tr>
    <tr>
		<td>
            transparent-slim-light.svg
        </td>
		<td>
			<img width="306" alt="transparent-light" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-slim-light.svg">
		</td>
	</tr>
      <tr>
		<td>
            filled-dark.svg
        </td>
		<td>
			<img width="306" alt="filled dark mode" src="https://raw.githubusercontent.com/Supercip971/by-human/main/filled-dark.svg">
		</td>
	</tr>
    <tr>
		<td>
            filled-light.svg
        </td>
		<td>
			<img width="306" alt="filled-light" src="https://raw.githubusercontent.com/Supercip971/by-human/main/filled-light.svg">
		</td>
	</tr>
    <tr>
		<td>
            filled-slim-dark.svg
        </td>
		<td>
			<img width="306" alt="filled dark mode" src="https://raw.githubusercontent.com/Supercip971/by-human/main/filled-slim-dark.svg">
		</td>
	</tr>
    <tr>
		<td>
            filled-slim-light.svg
        </td>
		<td>
			<img width="306" alt="filled-light" src="https://raw.githubusercontent.com/Supercip971/by-human/main/filled-slim-light.svg">
		</td>
	</tr>
</table>
-----



## Why do we think writing by using a generative AI is bad ? 

Writing by using a generative AI is bad in multiple ways. It may appear better but is like a drug. Quick and rapid improvement, while developping slow maintenance and long-standing issues: 

### 1. Copyright, plagiarism and license-washing 

By using simple request, Chat-GPT, and in general, all llms are copying other users work.

For exemple, I asked to only give me C code for a nvme driver.

### 2. Creation of bugs


- [1](https://dl.acm.org/doi/epdf/10.1145/3639474.3640052) Is stating that chat gpt 4 is instantly failling **~8%** of the time, and code quality is good only **~60% of the time**.
- [2](https://www.coderabbit.ai/blog/state-of-ai-vs-human-code-generation-report) code rabbit, an AI company, states that LLMs introduce **70% major defect and 40% critical issues** in pull request. Twice more than humans. 
- [3](https://arxiv.org/pdf/2509.13650) this paper tells that **github-copilot has only superficial capability when trying to find bugs**. It can hardly help discover bugs. Across multiple project filled with vulnerability issues (more than 39 different type). Github copilot only helped found a couple but in general only fixed spelling mistakes. And in general Github-copilot lacked any valuable comments 
- [4](https://uplevelteam.com/blog/ai-for-developer-productivity) Up level states that generative AI is introducing 40% more bugs. 
- [5](https://www.gitclear.com/coding_on_copilot_data_shows_ais_downward_pressure_on_code_quality) put into perspective the fact that we have a year over year increase of **40% of code pushed, then reverted or removed within 2 weeks**. Meaning that since the introduction of AI, quickly 'reverted' code has increased from 3.97% to 7.09%. 


In the end, we understand that AI generate incremental technical dept, that makes projetcs unmaintable in the long term. And it's rarely able to fix itself. 
It's like a student writing code for you and not being able to learn and have cognitive introspection. And you, the programmer, are less likely to fully understand your code as you did not write it. 

#### 2.1 You seem smarter, but you are becoming worse 

- [8](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4895486) In some research, it is shown that using **AI makes you 48% to 127% more likely to achieve a better grade during practice problems**. But in the end, **you are 17% less likely to achieve a worse grade during the real test**.
What is worse, is that those students were not able to grasp that they learned less. And were unable to become more understanding. 

This is a critical issue because you are leading to a false sens of understanding. Generally you write code using AI and trust your competence by checking it. But you are becoming a really bad programmer by trusting the AI and not learning by yourself. 

As you are expected to learn your codebase, by using an LLMs, you are becoming worse at understanding your own codebase, thus worse at fixing and improving it. This makes you more and more dependent to AI, and will loop forever until your codebase is unable to be maintained. 



### 3. The ecological aspect is devastating ? 

It is hard to translate into number the aspect of AI.  

[6](https://www.tomshardware.com/pc-components/ram/data-centers-will-consume-70-percent-of-memory-chips-made-in-2026-supply-shortfall-will-cause-the-chip-shortage-to-spread-to-other-segments) First, 70% of ram production is dedicated to datacenter. A production increased by the reallocation of supplier capacity woards AI datacenters. Meaning that we are using a lot of economical ressources to make AI run. 

[7](https://news.mit.edu/2025/explained-generative-ai-environmental-impact-0117) Since the introduction of chat-GPT, the power consumption has increased by 98% in one year. (2.69 MW in 2022 -> 5.43 MW in 2023). 

The water usage is hard to put into perspective, the only trustable source is a citation from Sam Altman saying that chat-GPT uses 0.000085 Gallons of water per query. [9](https://www.techtimes.com/articles/310771/20250612/how-much-water-energy-does-chatgpt-use-sam-altman-breaks-down-numbers.htm) but chat-GPT processes 2.5 billions of request per day [10](https://www.businessinsider.com/chatgpt-openai-user-stats-messages-per-day-tech-ai-2025-10) meaning that in average chat-GPT uses 804400 L of water per day.  

While it may seems a lot, those numbers are a ghost. We can't make any further claim and are not able to put into perspective the direct ecological aspect of Chat-GPT usage. 
We would need a full research that are using Open-AI insight but as they are not releasing a lot of information we are stuck at guessing how much we are destroying the world by using AI. 

### 4. LLMs Inbreeding is as bad as it is for humans 

Github code is 



