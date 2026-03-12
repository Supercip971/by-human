

<div align="center">
<a href="https://github.com/Supercip971/by-human">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-dark.svg">
  <img height="96" alt="Made by humand, not by gen AI badge" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-light.svg">
</picture>

</a>
<h1>Made by Human, not by Gen-AI</h1>
</div>

This is a repository that aims to provide a **collection of badge to symbolize** that you didn't use generative AI (aka LLMs) for the creation of your project. By using this, we expect that the number of written line of code by ai is less than 1% of your total number of written line of code project. 

Note that nobody will check your code, and if you are against AI use in your codebase but are not sure for the number of line of code written by AI, you can still use the badge. The goal is to be transparent and to try to reduce the abusive use of AI in codebase.

This repository is accompanied by this explaination file that tries to use **scientific research** to support every claim. But this part **is still work in progress**.


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
			<b>Picture (Dark)</b>
		</td>
		<td>
			<b>Picture (Light)</b>
		</td>
	</thead>
    <tr>
		<td>
            transparent-dark.svg + 
            transparent-light.svg
        </td>
		<td>
			<img width="306" alt="transparent dark mode" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-dark.svg">
		</td>
		<td>
			<img width="306" alt="transparent-light" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-light.svg">
		</td>
	</tr>
    <tr>
		<td>
            transparent-slim-dark.svg +
            transparent-slim-light.svg 
        </td>
		<td>
			<img width="306" alt="transparent dark mode" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-slim-dark.svg">
		</td>
		<td>
			<img width="306" alt="transparent-light" src="https://raw.githubusercontent.com/Supercip971/by-human/main/transparent-slim-light.svg">
		</td>
	</tr>
      <tr>
		<td>
            filled-dark.svg + filled-light.svg
        </td>
		<td>
			<img width="306" alt="filled dark mode" src="https://raw.githubusercontent.com/Supercip971/by-human/main/filled-dark.svg">
		</td>
		<td>
			<img width="306" alt="filled-light" src="https://raw.githubusercontent.com/Supercip971/by-human/main/filled-light.svg">
		</td>
	</tr>
    <tr>
		<td>
            filled-slim-dark.svg + filled-slim-light.svg
        </td>
		<td>
			<img width="306" alt="filled dark mode" src="https://raw.githubusercontent.com/Supercip971/by-human/main/filled-slim-dark.svg">
		</td>
		<td>
			<img width="306" alt="filled-light" src="https://raw.githubusercontent.com/Supercip971/by-human/main/filled-slim-light.svg">
		</td>
	</tr>
   
</table>


-----


## Why do we think writing by using a generative AI is bad ? 

Writing by using a generative AI is bad in multiple ways. It may appear better but is like a drug. Quick and rapid improvement, while developping slow maintenance and long-standing issues, every statement is backed by research and scientific papers. This is why it's hard to make a statement about the cological aspect or the license-washing, because there is not a lot of research on those topics.

### 1. Copyright, plagiarism and license-washing 


#### 1.1 Plain and obvious license-washing 

An AI can license wash unknowingly, but it has already been shown that it can be used to do it on purpose. As an example [https://tuananh.net/2026/03/05/relicensing-with-ai-assisted-rewrite/](https://tuananh.net/2026/03/05/relicensing-with-ai-assisted-rewrite/) someone used claude code to rewrite the whole project and then claim it was MIT instead of LGPL. 

This is a clear license violation. 
If someone say that it is not license washing, then does translating a book make it loose all of the copy-rights ?
Accepting this marks the end of copyleft and copyrights.  

#### 1.2 Plagiarism, and not obvious license-washing 

When making an LLM learn, it is unable to take into account the license of the code. 
As it is shown in those research paper [16](https://arxiv.org/html/2502.05023v1#:~:text=number%20of%20outputs%20can%20reproduce,memorized%20code%20snippets) [17](https://arxiv.org/html/2403.15230v1#:~:text=Our%20analysis%20revealed%20that%20every,for%20both%20researchers%20and%20the)

**Large Langues Models are generating 3.35% of strong copyleft licensed code** and are:
> not aware of reusing copyleft code and cannot be asked, through the prompt, to avoid reusing existing code in the responses.

This paper [16](https://arxiv.org/html/2502.05023v1#:~:text=number%20of%20outputs%20can%20reproduce,memorized%20code%20snippets) also states that
accepting a copyleft request may lead to more and more copyleft stolen code. (By a factor of 2 to 5).  


In the end, LLMs are blatently stealing code. It is not like a Human learning about a piece of code and then creating something.
A Human understand the whole picture, the algorithm, and doesn't remember the code peice.
But when an LLM learn, it is taking the whole piece of code and may reinject it back. Meaning that the strong copy-left 
piece of code is in its database, raising concern about the respect of license. Furthermore, a Human may copy-paste a piece of code 
but mention the copyright in its file, instead LLMs don't mention the license nor the Author.

### 2. Creation of bugs

- [1](https://dl.acm.org/doi/epdf/10.1145/3639474.3640052) Is stating that chat gpt 4 is instantly failling **~8%** of the time, and code quality is good only **~60% of the time**.
- [2](https://www.coderabbit.ai/blog/state-of-ai-vs-human-code-generation-report) code rabbit, an AI company, states that LLMs introduce **70% major defect and 40% critical issues** in pull request. Twice more than humans. 
- [3](https://arxiv.org/pdf/2509.13650) this paper tells that **github-copilot has only superficial capability when trying to find bugs**. It can hardly help discover bugs. Across multiple project filled with vulnerability issues (more than 39 different type). Github copilot only helped found a couple but in general only fixed spelling mistakes. And in general Github-copilot lacked any valuable comments 
- [4](https://uplevelteam.com/blog/ai-for-developer-productivity) Up level states that generative AI is introducing 40% more bugs. 
- [5](https://www.gitclear.com/coding_on_copilot_data_shows_ais_downward_pressure_on_code_quality) put into perspective the fact that we have a year over year increase of **40% of code pushed, then reverted or removed within 2 weeks**. Meaning that since the introduction of AI, quickly 'reverted' code has increased from 3.97% to 7.09%. 


In the end, we understand that AI generate incremental technical dept, that makes projetcs unmaintable in the long term. And it's rarely able to fix itself. 
It's like a student writing code for you and not being able to learn and have cognitive introspection. And you, the programmer, are less likely to fully understand your code as you did not write it. 

#### 2.1 You seem smarter, but you are becoming worse 

- [8](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4895486) In some research, it is shown that using **AI makes you 48% to 127% more likely to achieve a better grade during practice problems**. But in the end, **you are 17% more likely to achieve a worse grade during the real test**.
What is worse, is that those students were not able to grasp that they learned less. And were unable to become more understanding. 

This is a critical issue because you are leading to a false sens of understanding. Generally you write code using AI and trust your competence by checking it. But you are becoming a really bad programmer by trusting the AI and not learning by yourself. 

As you are expected to learn your codebase, by using an LLMs, you are becoming worse at understanding your own codebase, thus worse at fixing and improving it. This makes you more and more dependent to AI, and will loop forever until your codebase is unable to be maintained. 



### 3. The ecological aspect is devastating ? 

It is hard to translate into number the aspect of AI.  

[6](https://www.tomshardware.com/pc-components/ram/data-centers-will-consume-70-percent-of-memory-chips-made-in-2026-supply-shortfall-will-cause-the-chip-shortage-to-spread-to-other-segments) First, 70% of ram production is dedicated to datacenter. A production increased by the reallocation of supplier capacity woards AI datacenters. Meaning that we are using a lot of economical ressources to make AI run. 

[7](https://news.mit.edu/2025/explained-generative-ai-environmental-impact-0117) Since the introduction of chat-GPT, the power consumption has increased by 98% in one year. (2.69 MW in 2022 -> 5.43 MW in 2023). 

The water usage is hard to put into perspective, the only trustable source is a citation from Sam Altman saying that chat-GPT uses 0.000085 Gallons of water per query. [9](https://www.techtimes.com/articles/310771/20250612/how-much-water-energy-does-chatgpt-use-sam-altman-breaks-down-numbers.htm) but chat-GPT processes 2.5 billions of request per day [10](https://www.businessinsider.com/chatgpt-openai-user-stats-messages-per-day-tech-ai-2025-10) meaning that in average chat-GPT uses 804400 L of water per day.  

Now, this article tells us that [13](https://www.cell.com/joule/fulltext/S2542-4351(23)00365-3?_returnURL=https%3A%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2542435123003653%3Fshowall%3Dtrue#fig1) one chat-GPT 4.5 request cost 20.500 Wh. But you can still not make this statement as clear as possible, as it uses an approximation. 

It is more grounded as this article take into account large context, because a lot of study uses "short" request, but using LLM as an agent require it to read your file, your codebase, and can no longer be linked to a 'short request'.z

While it may seem a lot, those numbers are a ghost. We can't make any further claim and are not able to put into perspective the direct ecological aspect of Chat-GPT usage. We would need a full research that are using Open-AI insight but as they are not releasing a lot of information we are stuck at guessing how much we are collapsing the world by using AI.


### 4. LLMs are getting better ! 

### 4.1 Inbreeding is as bad as it is for humans 

Microsoft is training its LLMs on code from github, and they said in a conference that **40% of code written by an LLM is left unmodified** [11](https://www.microsoft.com/en-us/Investor/events/FY-2023/Morgan-Stanley-TMT-Conference)
While this quote is not really backed by any evidence, it is expected to be true that more and more code is written by an LLM, and it is more and more left untouched.
The training data of **LLMs can't differ between a human code and a LLM written code**. Meaning that we will need more and more energy, training and data to accomodate this shift in quality. 

An error just repeated multiple time by an LLM can become ground truth, as we know that only 20 documents can poison LLMs of any size [12](https://www.anthropic.com/research/small-samples-poison). (While this is not linked to this statement, this article shows how a couple of documents can shift an LLM point of view).

In the end, the easy shift in models knowledge coupled to the increasing use of LLMs in the wild means that what is expected to be ground truth for an LLM is becoming what it wrote by itself. 

It's just like inbreeding. 

### 4.2 Compute power availability 

Having to pay twice for your ram is a heavy cost of having datacenter eating the whole production. 

AI is mainly able to evolve by multiplying compute power, RAM, context size... 
But our world is unable to keep it up [13](https://arxiv.org/abs/2409.14160). 

This paper crystalize the issue with this statement:

> Empirically, Sutton’s “bitter lesson” (Sutton, 2019) appears
> partly incorrect: it is not that, for AI, “general methods
> that leverage computation are ultimately the most effective,
> [because of] Moore’s law, [...] continued exponentially
> falling cost per unit of computation”, but that increasing
> resources are spent on AI. This increase in resources is
> visible in computational costs but is also true of other costs.
> For instance, building larger AI models require more human
> labor.

![Ai-ressource](doc/ai-ressource-usage.png)

In the end, when we say an AI is getting better, it is not because of a ground breaking algorithm but rather:

- A more powerful hardware, meaning more money & more energy 
- More data (which is becoming more and more polluted by LLMs)
- More training, meaning more energy and more human labor.

We are reaching a point where we are unable to keep up with the increasing demand of resources, and the only way to keep up is to eat through the user market. The paper predicted the increase of recent ram price [14](https://www.tomshardware.com/pc-components/ram/ram-price-index-2026-lowest-price-on-ddr5-and-ddr4-memory-of-all-capacities). When we will no longer have enough ram, no longer enough compute power, the whole AI industry may collapse, bringing us back to the point where we are now... Or those who depends on AI will not be able to bring back their lost knowledge. 

> If you want to be positive, it may quickstart a tought of reversing computer evolution. And trying to become more efficient rather than more performant.


## Conclusion 

When writing by using an AI, the code seems great because its already a problem solved by someone else. 

It makes you seem smarter while making you worse. It has a lot of consumption issues, has more and more investment by having a training set being polluted by its own mistakes. And by investor giving billions wanting more and more while having less and less. 

It is only a temporary shiny rock that will become just a regular rock someday, and in the end, you would have hoped to not depend your whole workflow on an inbred junior that is unable to count the number of letter in a word. You will finish as the external tourist of your own codebase. 

The world is made of complex problem and there are no easy fixs. 
Our imperfection and tought process may be replicated someday, but for now your brain is precious. 

Programming has yet to be solved, and we are building our own babel tower trying to reach AGI while destroying our knowledge with bricks of ourselves. 

Please learn, discover, and make something creative. 

## Shouldn't I use brainmade.org ?

We don't share the exact same philosophy as [brainmade.org](https://brainmade.org/), they say: 

```md
It’s not AI = bad, it’s human = good. 
There’s something transcendent and magical in knowing a human made the artwork I’m consuming, knowing they tried hard is part of the experience. 
It doesn’t have to be 100% human made (what would that even MEAN these days?), perhaps 90% human made.

Three examples of what this mark could apply to:

- Using, say, ChatGPT as a rhyming dictionary feels fine, but writing whole verses of your poem doesn’t.
- Using DALL-E to start brainstorming with 100 generated views of birds sitting on telephone lines seems fine, but getting it to paint large sections of your artwork doesn’t.
- Asking a text generator to give you 10 happy-sounding synonyms for despair sparks joy in me, but asking it to write your anti-transcendentalist masterpiece does not.
```

And that's okay, for some people they see AI is a tool and can be used sometime. But for us, it is not a tool but rather a poison that can leed to knowledge dept. It should be avoided at all cost.
