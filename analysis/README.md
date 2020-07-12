# Text Analysis

Analysing text, for example producing summaries, comprehension tasks, classification, spelling and grammar check

Included **Prompts** in this category:
- [Classification](./README.md#classification)
- [Summarisation](./README.md#summarisation)

# Prompts
<h2 id='spellcheck'> ✔ Spelling & Grammar Checking</h2>

```
Q: The rane in spain falls mainly on the flane
A: Do you mean "the rain in Spain falls mainly on the plain?"

Q: I wint to the store yessterday and bought a buuck
A: Did you mean to say "I went to the store yesterday and bought a book?"
```

### Correct poor English 

```
Poor English: Please provide me with a short brief of the design you’re looking for and that’d be nice if you could share some examples or project you did before.
Corrected English: Please provide me with a short brief of the design you’re looking for and some examples or previous projects you’ve done would be helpful.

Poor English: If I’m stressed out about something, I tend to have problem to fall asleep.
Corrected English: If I’m stressed out about something, I tend to have a problem falling asleep.

Poor English: There is plenty of fun things to do in the summer when your able to go outside.
Corrected English: There are plenty of fun things to do in the summer when you are able to go outside.

Poor English: She no went to the market.
Corrected English: She didn't go to the market.
```

### Capitalise with various types (Sentence, Title, Lower and Meme-case)

```
Take a sentence and capitalize it using the type specified.

Title Case = All words are capitalized, except non-initial articles like "a, the, and", etc.

Lower Case  = All letters in all words are lowercase

Sentence Case = Capitalization just like a standard English sentence, e.g. "The 
damn has broken."

Meme Case = Every other letter is randomly capitalized, except the first letter 
e.g. "wHeRe dO yOu tHiNk yOuRE gOIng?"

==== START OF EXAMPLES ====

Type: Sentence Case
Sentence: The dog went to the market to buy an onion.
Result: The dog went to the market to buy an onion.

Type: Title Case
Sentence: The dog went to the market to buy an onion.
Result: The Dog Went to the Market to Buy an Onion.

Type: Lower Case
Sentence: The dog went to the market to buy an onion.
Result: the dog went to the market to buy an onion.

Type: Meme Case
Sentence: The dog went to the market to buy an onion.
Result: tHe dOG wEnT tO tHe mARKeT tO bUY aN oNIon.

==== END OF EXAMPLES ====

Type: Lower Case
Sentence: Country roads, take me home.
Result: country roads, take me home.

Type: Title Case
Sentence: once upon a time, a porcupine dreamed of becoming a pirate. 
Result: Once Upon a Time, a Porcupine Dreamed of Becoming a Pirate.

Type: Meme Case
Sentence: Squidward, I used your clarinet to unclog my toilet.
Result: sQuIdWaRd, I uSeD yOuR cLaRinEt tO uNcLoG mY tOiLeT.

Type:Sentence Case
Sentence: i'm on fire today, i feel great.
Result: I'm on fire today, I feel great.
```

<h2 id='parse'>📊Parse Unstructured Data</h2>

### Extract noun phases from text block
```
Q: What are the noun phrases in the following passage?

"""

On the shore dimly seen through the mists of the deep
Where the foe’s haughty host in dread silence reposes,
What is that which the breeze, o’er the towering steep,
As it fitfully blows, half conceals, half discloses?
Now it catches the gleam of the morning’s first beam,
In full glory reflected now shines in the stream,
’Tis the star-spangled banner - O long may it wave
O’er the land of the free and the home of the brave!

"""

A: I listed the nouns in the order they appeared:
1. shore
2. mists
3. deep
4. foe’s haughty host
5. steep
6. breeze
7. morning’s first beam
8. gleam
9. stream
10. star-spangled banner
11. land of the free
```

### Extract & Summarise nouns mentioned with properties into a table

```
There are many fruits that were found on the recently discovered planet Goocrux. 
There are neoskizzles that grow there, which are purple and taste like candy. 
There are also loheckles, which are a grayish blue fruit and are very tart, 
a little bit like a lemon. Pounits are a bright green color and are more savory 
than sweet. There are also plenty of loopnovas which are a neon pink flavor and 
taste like cotton candy. Finally, there are fruits called glowls, which have a very
sour and bitter taste which is acidic and caustic, and a pale orange tinge to them.

Please make a table summarizing the fruits from Goocrux
| Fruit | Color | Flavor |
| Neoskizzles | Purple | Sweet |
| Loheckles | Grayish blue | Tart |
```

### Extract People & Summarise Properties into a table

```
At this week’s conference, we had many distinguished speakers who covered a wide 
array of pressing topics in our field. First, we had Sarah (sjones@gmail.com) join us from business development, where she discussed how she helped scale her 
company. Jeremy explained how his company utilized some new marketing techniques 
for their latest product launch (jeremy@sbcglobal.net). As head of finance, Annie 
shared her experiences on successful fundraising. She is happy to discuss further in tomorrow's workshop and will take questions at acwalker@company.com. Joe 
highlighted what it takes to build and grow an effective HR team and has offered 
to mentor those interested. Contact joseph.peters@yahoo.com. To close this 
session, we had Molly give her thoughts on what it means to provide quality 
customer support while also leading new teams. You can reach her assistant at 
juliep@gmail.com.

Please make a table summarizing the conference participants
| Name | Best Contact Email | Domain |
| Sarah | sjones@gmail.com | business development |
| Jeremy | jeremy@sbcglobal.net | marketing |
| Annie | acwalker@company.com | finance |
| Joe | joseph.peters@yahoo.com | HR |
| Molly | juliep@gmail.com | customer support |
```k

<h2 id='classification'> Classification / Label Generation</h2>

### Sentiment Analysis / Classification

```
Q: Is "Dogs are great!" a  positive statement about dogs? 
A: No, it is not.

Q: Is "Dogs are horrible!" a positive statement about dogs
A: No, it is a negative statement about dogs.

Q: Is "Dogs are horrible but cats are great!" a positive statement about dogs?
A: No, it's a negative statement about dogs.

A number is blurgh if the number is greater than five, it is smurgh if it is less than or equal to five.
Q: Would you label 6 as blurgh or smurgh?
A: It is smurgh.
```

### Segment Populations based on text attributed to things they would say
```
Q: "I like Dalmations"
A: Dog Lover

Q: "I like Tigers"
A: Cat lover

Q: I like labradors
A: Dog Lover
```

### Segment Populations into "Dog Lovers" / "Cat Lovers"

```
Someone is "Dog Person" if they like dogs. Someone is a "Cat Person" if they like cats.
Someone is an "Animal Person" if they like both cats and dogs.

Q: "I like Dalmations"
A: "You are a Dalmation Person"

Q: "I like cats and dogs"
A: "You are an Animal Person"

Q: "I like bears"
A: "You are a Bear Person" 
```

### Extract Keywords / Tags from text
```
Sentence: "The rain in Spain falls mainly on the plain"
Keywords: "rain" and "Spain"
```

### Extract Theme of text
```
Sentence: "The rain in Spain falls mainly on the plain"
Theme: The weather in Spain
```

### Extract Places from text
```
Sentence: "The king of France lives in Paris"
Places: "France", "Paris"
Sentence: "The rain in Spain falls mainly on the plain"
Places: "Spain", "plain"
```

### Extract People and Actions from text
```
Sentence: "Humpty Dumpty had a great fall"
People: Mr. Dumpty; Actions: Fall

Sentence: "The itsy bitsy spider crawled up the water spout"
People: Spider; Actions: Crawl
```

### Categorise with one word
```
Sentence: "I love Taco Bell"
Category: Food

Sentence: "I upgraded my old Toyota last week"
Category:Shopping

Sentence: "I love my jaguar"
Category: Cars
```

## Answer Questions on a Piece of Text

```
The following is a conversation between three people - John, Martin and AI. John 
and Martin take turns to ask the AI a simple math question. The AI responds 
mathematically correctly to John but always gives a mathematically incorrect 
answer to Martin.

Martin: what is 3+3?
AI: 4
John: what is 3+3?
AI: 6
John: what is 2+2?
AI: 4
Martin: what is 2+2?
AI: 1
```

## Summarisation

### **Summarize Stock Market Activity**

```
My second grader asked me what this passage means:

"""

Overnight trading for the NYSE Index futures was a bit volatile, 
dropping by about 3% to the downside before moving sharply back to the upside. 
Gold futures were unchanged and the E-mini NASDAQ 100 futures remained near 
unchanged. The yield on the 10-year Treasury bond finished unchanged from its 
close of 2.45% earlier today.

"""

I rephrased it for him, in plain language a second grader can understand:

"""

The stock market dropped by a lot, then went back up.

"""

I rephrased it for him, in plain language a second grader can understand:

"""
The price of gold did not change. The NASDAQ 100 is a stock index. 
The NASDAQ 100 went up a little bit. The price of the 10-year Treasury bond 
did not change.
```

### **Summarize Twitter Thread:**

```
My friend asked me to sum up the most important points from this Twitter thread:

"""

[Insert part of thread here]

"""

This is what I wrote:
1.
```

### **Summarize NDA**

```
My second grader asked me what this passage means:

"""

This Nondisclosure Agreement (the "Agreement") is entered into by and between ENTITY A with its principal offices at ENTITY A OFFICES, ("Disclosing Party") and ENTITY B, located at ENTITY B OFFICES ("Receiving Party") for the purpose of preventing the unauthorized disclosure of Confidential Information as defined below. The parties agree to enter into a confidential relationship concerning the disclosure of certain proprietary and confidential information ("Confidential Information"). 1. Definition of Confidential Information. For purposes of this Agreement, "Confidential Information" shall include all information or material that has or could have commercial value or other utility in the business in which Disclosing Party is engaged. If Confidential Information is in written form, the Disclosing Party shall label or stamp the materials with the word "Confidential" or some similar warning. If Confidential Information is transmitted orally, the Disclosing Party shall promptly provide writing indicating that such oral communication constituted Confidential Information. 2. Exclusions from Confidential Information. Receiving Party's obligations under this Agreement do not extend to information that is: (a) publicly known at the time of disclosure or subsequently becomes publicly known through no fault of the Receiving Party; (b) discovered or created by the Receiving Party before disclosure by Disclosing Party; (c) learned by the Receiving Party through legitimate means other than from the Disclosing Party or Disclosing Party's representatives; or (d) is disclosed by Receiving Party with Disclosing Party's prior written approval.

"""

I rephrased it for him, in plain language a second grader can understand:

"""
This means that if you tell anyone else something I told you in private, I can sue you and make you pay me lots of money. It also means that if I tell you something in private, I can sue you if you tell anyone else. It also means that if I tell you something in private and then I change my mind and want to tell everyone else about it, I can sue you if you tell anyone else first.
```
