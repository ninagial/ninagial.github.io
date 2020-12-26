---
layout: post
title: Writing a Japanese Verb Conjugator
---

Writing a verb conjugator was something I was always interested in. I have made attempts to write conjugators for Ancient Greek and Latin, and they did not completely suck.

# Motivation

I am now looking into the Japanese verb, which is exciting because it is the first non-Indoeuropean language I am trying to learn, and I am completely fascinated.

Now most sources I find online underscore how _different_ Japanese is from European languages, and if you take at face value how fucked up this language is represented, it would be insane to even speak it as a native language.

However, it is _a_ language and people have used it for thousands of years to perform their daily tasks and communicate to each other. 

So no matter how exotic Japanese might appear, it is not futile to explore what is similar between Japanese and Indoeuropean language. For the time being I will focus on verbs.

# A glimpse into the Japanese verb

Let's not forget that people talk to each other for a reason. Among those reasons we can find the need to communicate clearly what happened, and when, what is happening, and what we will do if

## Polite Forms

Perhaps it is surprising for learners of Japanese that there is a _polite conjugation_ for almost all the other uses.

But in the end of the day I don't think that any social scientist is eventually bewildered that _pragmatic_ information that is important for a language is represented in a word form.

Many languages feature a connection between interpersonal, situational factors, and verb conjugation.

And this is most tangible in the _number_ of persons or things, grammatically. It is no surprise to the English speaker that one bird _has_ feathers, but two birds _have_ a nest.

And although English lacks a 'polite' number, the notion of "not knowing someone on a first person basis" might give an idea of what it is like to take the degree of acquaintance into account when addressing someone.

In other languages, the number system is overridden for this purpose. For instance in Argentina, the second plural is used to express politeness. In Spain, the third person. (Spanish is spoken in both countries.)

It is quite interesting that number systems vary wildly from one language to another. For example ancient Greek featured a third number, one that was used to refer to exactly two persons or things. (If something was done by more than two persons, the plural was used.)

A number of other languages extend this idea even further, having different word forms for three, and even four people doing something. And some of then even anticipate _the inclusion of the speaker_. (So you have a different word for you three without me go to the park, and another for let _us three_ go to the park.)

# Phonotactics

Phonotactics is a fancy word to refer that when speakers move their mouths around it is difficult or impossible to pronounce two sounds one after an other, and some times when we speak fast, an intermediate sound may result to substitute both sounds after some point.

The English language, being poor in conjugation, does not make immediately obvious what happens to each sound in the language when it collides with another sound.

Or perhaps the level at which it happens in English is not that obvious to the speaker as it is in Spanish, or Greek for example.

Japanese is an agglutinative language, with a finite set of open syllables (syllables that only consist of a consonant and a vowel.) With few exceptions, these _moras_ make up the whole language.

<table>
  <tr> <td align="right"> 1 </td> <td> a </td> <td> ka </td> <td> sa </td> <td> ta </td> <td> na </td> <td> ra </td> <td> ma </td> <td> wa </td> <td> ya </td> </tr>
  <tr> <td align="right"> 2 </td> <td> e </td> <td> ke </td> <td> se </td> <td> te </td> <td> ne </td> <td> re </td> <td> me </td> <td>  </td> <td>  </td> </tr>
  <tr> <td align="right"> 3 </td> <td> i </td> <td> ki </td> <td> si </td> <td> tsi </td> <td> ni </td> <td> ri </td> <td> mi </td> <td>  </td> <td>  </td> </tr>
  <tr> <td align="right"> 4 </td> <td> o </td> <td> ko </td> <td> so </td> <td> to </td> <td> no </td> <td> ro </td> <td> mo </td> <td> wo </td> <td> yo </td> </tr>
  <tr> <td align="right"> 5 </td> <td> u </td> <td> ku </td> <td> su </td> <td> tsu </td> <td> nu </td> <td> ru </td> <td> mu </td> <td>  </td> <td> yu </td> </tr>
   </table>
Now, since most verbs end in **u** (taberu: eat, miru: see, iu: speak, kiku:hear, suru:do, shiru:think, etc), this 'u' might come from a _ku_, a _ru_, an _ou_, and so on and so forth, so different inflection paradigms apply depending on what sound collisions, mergers etc, are allowed in a language phonotactics.

This is not exotic at all: It is, to my knowledge, quite common in Greek, Spanish, and other European languages.

(Like in ancient Greek, you get different tables for verb stems ending in r or l, a vowel, another consonant, but if you know the "collision" rules and the suffixes, you can work them out even if you don't remember. This is what I had based my previous conjugators off - because I did them without a database of the actual word forms. I should review and upload these projects at some point if anyone is interested.)

<table>
<tr> <th> </th> <th> Indicative </th> <th> Negative </th> <th> Polite </th> <th> Negative Polite </th> </td>
<tr> <td> Stem ends in a vowel </td> <td> **omou** </td> <td> **omowanai** </td> <td> **omoimasu** </td> <td> **omoimasen** </td> </tr>
<tr> <td> Stem ends in a K </td> <td> **kiku** </td> <td> **kikanai** </td> <td> **kikimasu** </td> <td> **kikimasen** </td> </tr>
<tr> <td> Stem ends in a R </td> <td> **tsukuru** </td> <td> **tsukuranai** </td> <td> **tsukurimasu** </td> <td> **tsukurimasen** </td> </tr>
</table>

And so on and so forth.

There are also **irregular** verbs. But in any language, you have to memorize those. It is obviously better to do so after learning the patterns for the regular ones, _obviously_.

# Structuring the Japanese Verb table

Since we established that speaking a language serves to communicate events and manage important social relationships, we can readily see that this is the _communicative_ and cognitive origin of different grammars, and since being social is something universal to humans, we should expect to find common aspects.

Now, I am still in the process of doing this, and I will explore the topic in future posts as well.

But the motivation is **"What would it look like if we filled in the Latin verbs' table with the Japanese pragmatic/semantic equivalent?"** I think that for native speakers of Greek, Italian, Spanish, and similar languages, the learning experience could be more comfortable. I know this is tha case for me!

<table border=1>
  <tr> <th> Indicative </th> </tr>
  <tr> <td> Present-Future </td> <td> </td> <td> </td> <td>  </td> <td>  taberu </td> </tr>
  <tr> <td> Past </td> <td> </td> <td> </td> <td>  </td> <td> tabeta </td> </tr>
  <tr> <td> Present-Future </td> <td> Negative </td> <td> </td> <td>  </td> <td>  tabenai </td> </tr>
  <tr> <td> Past </td> <td> Negative </td> <td> </td> <td>  </td> <td> tabenakata  </td> </tr>
  <tr> <td> Present-Future </td> <td> </td> <td> Polite </td> <td>  </td> <td> tabemasu </td> </tr>
  <tr> <td> Past </td> <td> </td> <td> Polite </td> <td>  </td> <td> tabemashita  </td> </tr>
  <tr> <td> Present-Future </td> <td> Negative </td> <td> Polite </td> <td>  </td> <td> tabemasen </td> </tr>
  <tr> <td> Past </td> <td> Negative </td> <td> Polite </td> <td>  </td> <td> tabemasen deshita </td> </tr>
  <tr> <th> Subjunctive </th> </tr>
  <tr> <td> Present-Future </td> <td> </td> <td> </td> <td>  </td> <td> tabeyou </td> </tr>
  <tr>  <td> Past </td> <td> </td> <td> </td> <td>  </td> <td> tabetaro </td> </tr>
  <tr>  <td> Present-Future </td> <td> Negative </td> <td> </td> <td>  </td> <td> tabenai darou </td> </tr>
  <tr>  <td> Past </td> <td> Negative </td> <td> </td> <td>  </td> <td> tabenakatta darou </td> </tr>
  <tr>  <td> Present-Future </td> <td> </td> <td> Polite </td> <td>  </td> <td> tabemashou </td> </tr>
  <tr>  <td> Past </td> <td> </td> <td> Polite </td> <td>  </td> <td> tabeta deshou </td> </tr>
  <tr>  <td> Present-Future </td> <td> Negative </td> <td> Polite </td> <td>  </td> <td> tabenai deshou </td> </tr>
  <tr>  <td> Past </td> <td> Negative </td> <td> Polite </td> <td>  </td> <td> tabenakatta deshou </td> </tr>
  <tr> <th> Imperative </th> </tr>
  <tr>  <td> Present-Future </td> <td> </td> <td> </td> <td>  </td> <td> tabero </td> </tr>
  <tr>  <td> Past </td> <td> </td> <td> </td> <td>  </td> <td> </td> </tr>
  <tr>  <td> Present-Future </td> <td> Negative </td> <td> </td> <td>  </td> <td> taberu na  </td> </tr>
  <tr>  <td> Past </td> <td> Negative </td> <td> </td> <td>  </td> <td>  </td> </tr>
  <tr>  <td> Present-Future </td> <td> </td> <td> Polite </td> <td>  </td> <td> tabete kudasai </td> </tr>
  <tr>  <td> Past </td> <td> </td> <td> Polite </td> <td>  </td> <td>  </td> </tr>
  <tr>  <td> Present-Future </td> <td> Negative </td> <td> Polite </td> <td>  </td> <td> tabenai de kudasai  </td> </tr>
  <tr>  <td> Past </td> <td> Negative </td> <td> Polite </td> <td>  </td> <td>  </td> </tr>
 </table>
 
# Things missing from this table
 
 I haven't included yet several Conditional Clauses, and Aspects. I will explain these shortly here, so that the table is still readable.
 
## Conditional Clauses

As in Greek, Spanish, and English, different configurations of timing and conjecture about things we don't know actually happened give rise to different manners of speaking about such, hypothetical events.

**If A had happened in the past, but it didn't, I would have done B.**

**If A happens (in the future), I will do that.**

## Aspect

Notice the difference between the following:

**I am currently cooking.**

**I cooked already.**

**I have been travelling back and forth to Greece.**

This is the aspect. 

So, I will come back to these. I need to consolidate that in my own learning process first.


# Remarks and Directions

Japanese may be strange in some aspects, but this post shows that it is pretty normal in others.

Even if you consider the _total number of word forms per verb_ as an index of "memory load" for a given language, I think that it is quite comparable in this respect with European languages.

Whereas Spanish for instance has all the three persons for each number, Japanese does not take person into account. All the following are expressed by the same form: I hear, you hear(s), he/she/they hear(s), we hear, you all hear, they all hear; So the whole thing is divided by six for starters, no matter the amount of inflection paradigms.

Then it is two times that, because of the plain/polite dimension, so I still think the complexity is like, perhaps 3 times lower, than many European languages.

**So, the Japanese verb might be easier than what YouTube probably has made you believe.**

Let's see how actually coding the conjugator will go. I might as well regret saying that!!
