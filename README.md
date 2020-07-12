# ai-prompts
Useful prompts for interacting with an AI.

The goal of [ai-prompts](https://github.com:ethi-technologies/ai-prompts) is to be a public effort to construct a platform for collaboration on the design of friendly & useful AI prompts.

The full capabilities of the EthiX AI Assistant go far behind text generation. As such, interacting with and getting useful responses from the Assistant involves a prompt design process.

# TODO
---

- [x] [Book Review Generator](https://www.notion.so/Book-Review-Generator-8d7bc8bfca704b7d9e95ec44412d6bc6): [playground](./playground)
- [ ] [Bullet Points→Email Generator](https://www.notion.so/Bullet-Points-Email-Generator-3ba8ae8fa674442b81b6c74c1bc78693) - 
- [ ] [Sentence→Email Generator](https://www.notion.so/Sentence-Email-Generator-a36d269ce8e94cc58daf723f8ba8fe3e)
- [ ] [Headline Generation](https://www.notion.so/Headline-Generation-fa254c5ef7a04c918a2284e7f5b728a0)
- [ ] [Sales/Marketing/Product Generator](https://www.notion.so/Sales-Marketing-Product-Generator-f783013acefd4128b7d4b179bcc07f15)
- [ ] [Idea Generator](https://www.notion.so/Idea-Generator-56b1f1d323a747979ed905bbe0c3782c)
- [ ] [Tweet Generation](https://www.notion.so/Tweet-Generation-bc100b66aa414346938d89f3bf52b908)
- [ ] [Instagram Description Generator](https://www.notion.so/Instagram-Description-Generator-de56582afaf647eead889011cc013dbd)
- [ ] [Poem Generator](https://www.notion.so/Poem-Generator-a551bd250e5f49ed81c714f930c09641)
- [x] [Text→Emoji Generator](https://www.notion.so/Text-Emoji-Generator-d5e18b52e10b4e1e907f83d617f8ce35)
- [x] [Storytelling](https://www.notion.so/Storytelling-6cfb8fc15f254fbd9619b6de7766496a)
- [x] [Film Transcripts](https://www.notion.so/Film-Transcripts-9a940254e6f94751a5f20e73f9df5b28)
- [x] [Q&A](https://www.notion.so/Q-A-48f726c86c3d46fbb503596c6037dfab)
- [x] [Answer questions on a piece of text](https://www.notion.so/Answer-questions-on-a-piece-of-text-2e3fbb93d53649c0ac724521d9003377): [analysis](./analysis)
- [x] [Multiple Choice Answers & Explanation ](https://www.notion.so/Multiple-Choice-Answers-Explanation-d7cf2d59e9ac4fa4aa30dd3864b364c3)
- [x] [Multiple Choice Question Distractor Generator](https://www.notion.so/Multiple-Choice-Question-Distractor-Generator-eee19f4eafa84f0088993c3b11ca4234)
- [x] [Complex Concept Learning](https://www.notion.so/Complex-Concept-Learning-00b1a7434ff946079eb54e960ded9c2c): [analysis](./analysis)
- [x] [Classification](https://www.notion.so/Classification-8ff7f21d03994466a0f6b36f929723ee): [analysis](./analysis)
- [x] [Label Generation](https://www.notion.so/Label-Generation-a86e3a8e1fca46e49c5d2994af25a8ff)
- [ ] [Chatbot](https://www.notion.so/Chatbot-b5952a2843ed44ce8ce916011dcbdeef)
- [x] [Parse Unstructured Data](https://www.notion.so/Parse-Unstructured-Data-e2bd1a7b0a52417d9a1a31e3d8103c4a): [analysis](./analysis)
- [x] [Summarization](https://www.notion.so/Summarization-8fa53998f3c642eb850bd864d4d23d99): [analysis](./analysis)
- [x] [Spellcheck & Capitalization](https://www.notion.so/Spellcheck-Capitalization-b764a4acc49f46f490454f169e701942): [analysis](./analysis)
- [x] [Text→Command](https://www.notion.so/Text-Command-a09b1c55156940a9bc357872729e4c14): [analysis](./analysis)
- [x] [Code Translation](https://www.notion.so/Code-Translation-e313a4fbad7c4dc6a69840a12033beed)
- [x] [Language Translation](https://www.notion.so/Language-Translation-a57185496d6d416c9c492af83b8af292): [analysis](./analysis)
- [x] [Python Palindrome](https://www.notion.so/Python-Palindrome-8496a06e619449cd90924ceb45665840)
- [x] [1st→3rd Person Writing](https://www.notion.so/1st-3rd-Person-Writing-2ebf3f7a51db410ea80325a2356f6156)
- [x] [Math](https://www.notion.so/Math-5f54d4f1b6e543e0bf144f143c88e43f)

# Structure

Now that we've gone through the basics of getting started, let's explain the structure of this repo.

## [Prompts](./prompts)

**Prompts** are the basic sauce of interacting with the AI used for EthiX's Assistant. Read the [**Guide**](./#guide) on this page to learn more about **Prompts**.

We've split prompts into different directories; we've tried to make each directory a non-overlapping **category**, designed for a different type of interaction. For example, [creative](./creative) prompts like writing a fiction story or poem are a different category to question answering prompts which you'll find in the [informative](./informative) directory. We've tried to lay out in the [README.md](./playground/README.md) of each directory.

The **Prompt** categories so far are:
- [playground](./playground/README.md) - Miscellaneous, fun and interesting prompts that don't fit any other category.
- [analysis](./analysis/README.md) - Analysing text, for example producing summaries, comprehension tasks, classification, spelling and grammar check, 1st to 3rd person translation, language translation.
- [creative](./creative/README.md) - Creative pursuits, like writing a short story, a poem or generating fictional text in the style of famous authors.
- [chatbots](./chatbots/README.md) - Helping you to understand yourself, ask you useful questions, help you to think about self-improvement.
- [developer](./developer/README.md) - Generating code, parsing unstructured data, writing code documentation, Code Translation.
- [informative](./informative/README.md) - Information querying. The AI has read _all_ of the internet, these prompts help you to query the AI for useful information. This might involve a Q & A with a famous scientist, or explaining topics as if to a 5 year old.
- [psychology](./psychology/README.md) - Helping you to understand yourself, ask you useful questions, help you to think about self-improvement.
- [sales](./sales/README.md) - Generating product/website/sales copy, social media posts, emails, headline generation.
- [translation](./translation/README.md) - Translating between languages and different styles of writing e.g. from 1st to 3rd person text.

## Primers

**Primers** are similar conceptually to **Prompts**, however, **Primers** are designed to impart contextual knowledge to the Assistant. Our aim with **Primers** is to _prime_ the Assistant with relevant information as densely as possible. For example, for interactions with involving [psychology](./psychology) prompts, you would want the Assistant to understand as much as possible about you in order to give responses that are more relevant _to you_. **Primers** are our attempt to figure out the most information dense way of priming **Prompts** with contextual information.

<hr>

**Prompts** & **Primers** are written in in [YAML](https://yaml.org/ ), such that this repo can be used as a static resource for those wanting to have programmatic access to these prompts. YAML offers a good balance between readability both for humans and machines, and allows things that are harder to do in JSON such as block text. 🤖

Please ensure any contributions made endeavour to maintain a high standard for human readability for those humans who may find this repo useful.

Those of you who have never heard of YAML, don't worry - it's perfectly readable and you should get the hang of it pretty easily. It's just a way of ensuring the data has a readable but consistent, machine-readable structure.

# Guide (from OpenAI, adjusted for EthiX)

The OpenAI API behind EthiX's capabilities is built to flexibly solve a number of language tasks with a unified text-in, text-out interface.

**Text generation**
Program the AI by describing your task in plain english as a set of instructions, or giving a few written examples. For example, summarization, translation, composing emails, and much more.

The AI provides a general-purpose “text in, text out” interface, which makes it possible to apply it to virtually any language task. This is different from most other language AIs, which are designed for a single task, such as sentiment classification or named entity recognition.

To use the AI, you simply give it a **text prompt💡**and it will return a text completion, attempting to match the context or pattern you gave it. You can “program” it by crafting a description or writing just a few examples of what you’d like it to do. Its success generally varies depending on how complex the task is. A good rule of thumb is thinking about how you would write out a word problem for a middle schooler to solve.

**Text prompt:** We define this as the text-based input or "instructions" you provide to the AI.

## Key concepts

There are three concepts that are core to interacting with the AI: **prompt,** **completion**, and **tokens**. The “prompt” is text input to the AI, and the “completion” is the text that the AI generates based on the prompt. For example, if you give the AI the prompt, “As Descartes said, I think, therefore”, it will return the completion “ I am” with high probability. It’s worth noting that the AI is stochastic by default, meaning that every time you call it you might get a slightly different completion, even if the prompt stays the same.

You’ll probably see a few more words than that being generated, since the default setting for EthiX Notes is to generate **50 tokens**.💡 “Tokens”, which can be thought of as pieces of words. (Much like a jigsaw puzzle, the pieces are not cut up nicely according to the actual images displayed). The AI turns text into tokens before processing it, as a trick to be able to handle more text at once. For example, the word “Descartes” gets broken up into the tokens “Desc”, “art” and “es”, while a short and common word like “pear” is a single token. One thing you’ll notice is that many tokens start with a whitespace, for example “ hello” and “ bye”.

**Prompt length:** One limitation to keep in mind is that the text prompt and generated completion must be below 2000 tokens together.

The AI runs models with weights from the [GPT-3](https://arxiv.org/abs/2005.14165) family with many speed and throughput improvements. Ethi currently uses the biggest and most capable model, which is named **`davinci`**. In the future we may move to one of the other models: **`davinci`**, **`curie`**, **`babbage`** and **`ada`**. The models provide a spectrum of capability, where **`davinci`** is the most capable model and **`ada`** is the fastest.

---

## Text Generation

Text generation is the core function of the AI in EthiX Assistant. You give the AI a prompt, and it generates a completion. The way you “program” the AI to do a task is by simply describing the task in plain english or providing a few written examples. This simple approach works for a wide range of use cases, including summarization, translation, grammar correction, question answering, chatbots, composing emails, and much more (see the prompts in this repo for inspiration).

### Basics of prompt design

One way to think of the model is as a powerful pattern matching machine. It was trained on large amounts of text from the web and other sources. That means it's been exposed to a wide variety of patterns, and it will match these patterns against the prompt. So, if you provide a few questions and answers, it’ll pick up on that. If you write in a more formal tone, the AI will generally complete in a formal tone.

For instance, you can make it answer trivia questions by giving it two examples of questions and answers:

```
Question: Which was the last state in the United States that declared Christmas a legal holiday?
Answer: Oklahoma
Question: What is the smallest state in the United States by land area?
Answer: Rhode Island
```

The patterns that the AI picks up on can be pretty subtle. When you design the prompt, you can imagine giving the prompt to a stranger that knows nothing about your intent, and ask them to complete it. How easy will it be for them to do it? For example, consider the following prompt:

```
Question: What would you do if you saw a dragon?
Answer:
```

There are so many different ways to complete this prompt. Do you want a serious answer, or a funny one? Is it part of a story, where the answer depends on the circumstances? If there isn't a lot of context to go on, the model will pick a storyline randomly, similarly to what a human would do. But if you instead provide more context to the prompt, you can make the model complete it more in line of what you had in mind. For example, here's one way to answer the question like a child would:

```
The following is an interview between Susan, a 2nd grader living in San Francisco, and her teacher Robert.

Robert: What would you do if you saw a dragon?
Susan: That's a scary question. I would probably call my parents. They would know what to do.
```

Or, if you want a more serious answer:

```
News has been spreading about a real life dragon being sighted in the redwood 
forests around Santa Cruz. The following is an interview between Susan, a 
professor at Stanford University and a world-renowned expert on exotic animals, 
and Robert, a journalist at the local newspaper.

Robert: What would you do if you saw a dragon?
Susan: Well, I'd run. You have to remember that dragons are huge, fire-breathing, carnivorous lizards with a tendency to burn down villages. I'd call 911 if I 
thought I could get through. Otherwise I'd run into a building, or even just dive into a hole in the ground.
```

The point here is that if you want the API to answer questions, there are many ways to do it. The same goes for all other tasks, like summaries, chats, lists and so on. By giving the AI a detailed description of your task, it’s more likely that it’ll generate useful completions.

## Prompt design tips and tricks

As discussed in the previous section, completions can vary a lot based on how the context is built up in the prompt. Writing out details around style, scope and so on will change the output, just as a clearer task description to a human would yield better results. Below are a few more tricks for getting good completions:

**Examples:** The API picks up on patterns relatively quickly, so even a single example is often enough to give a decent completion. But adding 3-5 examples usually provides better results. Adding more examples than that sometimes help, but not always, since it can also constrain the model too much on the style or patterns of the specific examples. We recommend starting with around 3 examples, and seeing if adding more helps or hurts.

### Examples

You can get the API to answer questions by simply providing a few examples of questions and answers, like this:

```
Q: What is human life expectancy in the United States?
A: Human life expectancy in the United States is 78 years.
 
Q: Who was president of the United States in 1955?
A: Dwight D. Eisenhower was president of the United States in 1955.
 
Q: What party did he belong to?
A: He belonged to the Republican Party.
 
Q: Who was president of the United States before George W. Bush?
A: Bill Clinton was president of the United States before George W. Bush.
 
Q: Who won the World Series in 1995?
A: The Atlanta Braves won the World Series in 1995.
```

When there’s a single right answer, it’s usually a good idea to keep the temperature setting low. So for trivia-like questions like the ones above, you can pick temperature 0 which makes the completion completely deterministic.

For applications where you want more “creativity,” you can increase the randomness of the output by setting a higher temperature. For example, if you’d like the API to complete a poem, a temperature of 1 might be a good choice:

```
[From [https://en.wikipedia.org/wiki/In_Memoriam_A.H.H](https://en.wikipedia.org/wiki/In_Memoriam_A.H.H)]

Who trusted God was love indeed
And love Creation’s final law
Tho’ Nature, red in tooth and claw
With ravine, shriek’d against his creed.
The hills are shadows, and they flow
From form to form, and nothing stands;T
hey melt like mist, the solid lands,
Like clouds they shape themselves and go.
----
Where are the stars? The mighty sun?
Of space—and time—and matter—where?
What mightier hand than God’s could fling
The stars around the sky like sand?
Whose throes convuls’d the deepest sea,
And bade the abyss its secrets roar?
If Nature’s laws the stars control,
Then God is less than Nature’s soul.
white_check_markeyesraised_hands
```

```
The following is a conversation with an AI assistant. The assistant is helpful, creative, clever, and very friendly.
 
Human: Hello, who are you?
AI: I am an AI created by OpenAI. How can I help you today?
Human: What are you up to today?
AI: I'm preparing for OpenAI's robot games. I like playing video games so it's a lot of fun.
```

# Thank Yous

This repo is not the sole work of [Ethi](https://ethi.me). It brings together many individuals' and organisations' contributions, for which we are very grateful.

This would not be possible without the incredible work done by OpenAI.
