# Playground

Fun or thus-far not fit into a Category yet.

## 🌈Emoji Colour Generator

```js
let red = [
  '#430c15',
  '#711423',
  '#a01c32',
  '#bf223c',
  '#da304c',
  '#e35f75',
  '#ec93a2',
  '#f3bac3',
  '#f9dce1',
  '#fcf0f2'
]

let orange = [
  '#341a04',
  '#5b2c06',
  '#813f09',
  '#a24f0b',
  '#b6590d',
  '#e06d10',
  '#f4a15d',
  '#f8c296',
  '#fbdbc1',
  '#fdf1e7'
]
```

## 🎼Text -> MIDI Generator

```diff
```
ENGLISH:
Alas my love you do me wrong
To cast me off discourteously
And I have loved you oh so long
Delighting in your company
Greensleeves was my delight
Greensleeves my heart of gold
Greensleeves was my heart of joy
And who but my lady Greensleeves

MUSIC:
melody = \relative {
  \key d \dorian
  r2. | r2 d'4 |
  \repeat volta 5
  { f2 g4 | a4. b8( a4) |
    g2 e4 | c4. d8( e4) |
    f2 d4 | d4. c8( d4) |
    e2 c4 | a2 d4 |
    f2 g4 | a4. b8( a4) |
    g2 e4 | c4. d8( e4) |
    f4. e8( d4) | c4. a8( c4) |
    d2 d4 | d2 r4 |
    c'2. | c4.( b8) a4 |
    g2 e4 | c4.( d8 e4) |
    f2( d4) | d4.( c8) d4 |
    e2 c4 | a2 r4 |
    c'2. | c4. b8 a4 |
    g2 e4 | c4.( d8) e4 |
    f4. e8 d4 | c4.( a8) c4 |
  } \alternative {
    { d2. | d4 r4 d4 | }
    { d2. | d2 r4 | r2. }
  }
  \bar "|."
}

ENGLISH:
My pangolin heart
has scales of tin
my pangolin heart
has wings of leather
my pangolin heart
is brown as chaff
my pangolin heart
has a curved body
my pangolin heart
says auf weidersehn
to sweet delicious blood
I hate you
and
I love you
you are inside me
you are the engine
the endless power
I depend upon
And why does your tender
furry skin
Seem to feel so good

MUSIC:
+ melody = \relative { 
+ \key d \dorian
+ \time 4/4
+ r2. | r2 d'4 |
+ \repeat volta 5
+ { f2 g4 | a4. b8( a4) |
+ g4 f2 | g2 f4 | e4 d2 | d4 c2 |
+ a2 d2 | d4 f2 | g4 b2 | a4 d4 |
+ d2 c2 | d4 e4 | f4 e2 | c4 b2 |
+ a2 d2 | d4 f2 | g4 b2 | a4 d4 |
+ d2 c2 | d2 r4 |
+ d2. c2 | c4. a4.( b8) a4 |
+ d4. f2 | d4. e4 | f4 e2 | c4. b4.( a8) c4 |
+ e2 c2 | a2 r4 |
+ c'2 | c4 b8 a4 |
+ a2 d2 | d4 f2 | g4 b2 | a4 d4 |
+ d2 c2 | d2 r4 |
+ d2. c2 | c4. a4. b8( a4) |
+ d4. f2 | d4. e4 | f4 e2 | c4 b2.( a8) c4 |
+ e2 c2 | a2 r4 |
+ c'2 | c4 b8 a4 |
+ }
``` 
```

## 🧠Analogies Generator
[**prompt**=**bold**, AI=normal]

**Neural networks are like** genetic algorithms in that both are systems that learn from experience.

**Social media is like** a market in that both are systems that coordinate the actions of many individuals.

**A2E is like** lipofuscin in that both are byproducts of the normal operation of a system.

**Haskell is like** LISP in that both are functional languages.

**Quaternions are like** matrices in that both are used to represent rotations in 
three dimensions.

**Quaternions are like** octonions in that both are examples of non-commutative 
algebra.

**Memes are like** viruses in that both are self-replicating ideas.

**Epidemics are like** cascading failures in that both are cases where a small perturbation can trigger a large and unpredictable effect.

**Amorphous computing is** like fermentation in that both rely on a network of microscopic agents interacting with each other.

## Play Chess

```diff
Using https://lichess.org/YCv2aATh, give one game as prompt and let it play black pieces in game 2

Here is a game of chess:
1. e4 e5
2. Bc4 a6
3. Qf3 a5
4. Qxf7#


Here is another a game of chess:
1. e4 e5
2. Nc3 Nc6
+ 3. f4 d6
+ 4. Nf3 Nf6
+ 5. Bc4 Be7
+ 6. O-O O-O
+ 7. d3 h6
+ 8. Qe1 d5
+ 9. exd5 Nxd5
+ 10. Nxd5 Qxd5
+ 11. Bxd5 Bg4
+ 12. Nxe5 Nxe5
+ 13. fxe5 c6
+ 14. Bb3 Rfe8
+ 15. Bxf7+ Kf8
+ 16. Bxe8+ Kxe8
+ 17. Qg3 Bb4
+ 18. Qxg4 Be7
+ 19. Qxg7 Bh4
+ 20. Rf8#
```

## 📗Book Review Generator

```diff
Title: Lovely War
Rating: 3/5
Quotes:
- "It was time for James and Hazel to get properly acquainted. Time to see if the magic of music and moonlight and graceful movement were all that they had shared, or if a grimy gray London dawn and a cheap cup of coffee could make them feel the same way."
- "Annihilation has its own je ne sais quoi. We’re all guilty of it. So spare me the sermons."
- "His mother’s letters are full of urgent warning. She grew up in Mississippi. 
She knows about lynching. Aubrey wonders if he’ll die in his country before he 
ever gets the chance to die for his country. Either way, he’d rather not."
- "Whatever boost sixty captured miles might have brought to German morale was 
erased by the chocolate in the BEF’s packs. War is morale. War is supply. War is 
chocolate."
Thoughts:
- Pacing felt awkward
- WW1 history felt accurate
- Didn't care too much for the story of the Gods
Review: A good book with well rounded characters, but the pacing felt super 
awkward. The titles of the chapters showed which Greek God was speaking, but I was more interested in the WW1 tales than their relationships.

'''
Title: Goodbye, Things
Rating: 4/5
+ Thoughts:
+ - very cleanly written
+ - read easily
+ - author did good research
+ Review: The books of Marie Kondo have become popular with minimalists. This book 
+ is an expansion on that philosophy. The idea of decluttering your mind is 
+ interesting, but I'm not ready to give up everything. Some parts of the book were repetitive, but overall a nice easy read. The book's message is to simplify your life and reduce the amount of things you own. 

'''
Title: Deep Work: Rules for Focused Success in a Distracted World
Rating: 5/5
Thoughts:
\- Great read, got me to refocus my goals around my schedule.
\- Got me to delete a social media I used too much
\- I like that Cal Newport is a computer scientist as well
+ Review: I liked that this book made me reflect on my personal goals and writing 
+ workflow. I felt like the book was tailored to me. I appreciated Cal Newport's 
+ background as a computer scientist since he brought solid research into this book. His writing style made this book easy to read and a good pick-up-when-you-can 
+ book. The book's message is to change your focus to deep work, reducing the amount of times you check social media/email, and manage your distractions
```
