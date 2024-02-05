# freundlichDeutschLernen
Tracking the process of German learning, ChatGPT enhanced

## Wicked and kind learning
In their book [The Myth of Experience](https://www.amazon.com/Myth-Experience-Learn-Lessons-Correct/dp/1541742052), Soyer and Hogarth, among other things, speak of two learning environments: wicked and kind.

Putting it shortly and simplified, a kind learning environment is the one where the feedback to your learning is:
* immediate
* correct
* understandable

As opposed to that, a wicked learning environment is a learning environment where some, or all, of those aren't true. So the feedback can be:
* slow
* incorrect
* complicated

For instance, learning programming is (mostly) a kind learning environment. The code executes (or doesn't) immediately, if it works it works, and when it doesn't, you usually get a clear message why.

Contrary to that, learning something like financial investment is a wicked environment: it takes time for an investment to bring fruit, the success can be a temporary thing, and it's not immediately understandable why any profit or loss happened.

Learning a language is mostly a mix of the two - rules are clear, but sometimes there's exceptions. Speed of correct feedback depends on conditions (if you're in a course, or have a friend who speaks it...), and there's multiple ways of saying something. So the idea is to have a system that would create a kind learning environment for learning a language.

In this repo I will keep track of my attempts of using ChatGPT 3 and 4 to make that a kinder environment and help me with my studies.

## ChatGPT
I will be using ChatGPT to translate and help with translation of blocks of text I create in either English or Croatian. The idea is to create a general structure of the text I feel comforable translating to German, then try to translate it. 

The use of ChatGPT will be two-fold: I will ask it for a direct translation, and I will work with it iteratively to iron out the errors I make in the initial translation.

As I have access to ChatGPT 4 I will be also comparing the feedback gotten both from 3 and 4. In addition, I will have two prompts for each, trying to get a native speaker-level translation and also an A2 level (my current level for German after 1 year of studying) translation. The translation will be only copied over to a file for storage and comparison, and will not be used when doing my manual translation (my manual will be the first one).

In regards to iterative improvement, I have worked with prompts in which it supplies me with a general correctness rate of the sentence and generally pointing out the errors without correcting it (for instance: "grammar cases do not match in X and Y"). In those prompts the general structure and tone will remain the same and the work will only be done on grammar. I have considered spelling as well, but with ubiquity of grammar checkers and autocorrect, I think this is less important, so that will be skipped.

All prompts will be available in a prompt folder, and will be updated as they are improved. Each translation will start with only that prompt.

## Other tools
There's two more tools that I use - [Google Translate](https://translate.google.com/) (GT) and [wiktionary](https://www.wiktionary.org/) (WK). Google translate offers a good enough set of synonyms when supplied only one word, and wiktionary expands the explanation for that word to include ideas such as plural form, gender, etc. I use GT to translate the word in it's default form, and then use WK to learn about the word and reshape it in it's correct form.

In addition I sometimes consult [Duden](https://www.duden.de/) (DD) and [German stackexchange](https://german.stackexchange.com/) (GSE). Duden covers more words then wiktionary, and GSE covers interesting questions, such as differences etc.

When proofreading the initial translation, I will first be using a [Grammar checker](https://languagetool.org/) (GC) and then ChatGPT. The usage will be geared towards information as much as possible - meaning I will use the indication of error to correct it myself, and only after multiple failures will I take the offered solution.

I generally will not mark the use of those tools in the text, but if there appears a need for that I will be using the shorhand described here.

## Texts
Texts will, hopefully, be up to 3000 characters long, and will be concering various things I come across during the day, or homework I get for my German course.

Each text will be written in a folder in the following format:
```
repo
├── #_text_topic
│   ├── ChatGPT
│   │   ├── GPT3_A2.txt
│   │   ├── GPT3_C2.txt
│   │   ├── GPT4_A2.txt
│   │   ├── GPT4_C2.txt
│   ├── original.txt
│   ├── translation.txt
│   ├── prompt.txt
├── #_text_topic
...
├── prompts
    ├── GPT3_A2.txt
    ├── GPT3_C2.txt
    ├── GPT3_iter.txt
    ├── GPT4_A2.txt
    ├── GPT4_C2.txt
    ├── GPT4_iter.txt
```

Folder prompts will hold the prompts used in translation, with _iter refering to the prompt for iterative improvement.

Text topic folder will contain each text in it's own folder, with translation.txt holding an iterating translation and it will be possible to use git history to do a diff and compare the level of iterative improvements done on the text.

The first text will be this readme, but some changes will probably be made, to accomodate A2 speaking level.
