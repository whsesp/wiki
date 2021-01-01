+++
title = "Spaced Repetition & Anki"
author = ["Zhenkai Weng"]
date = 2020-12-31
tags = ["anki", "vocab"]
draft = false
toc = true
+++

## Introduction {#introduction}

Vocabulary is an essential element to communicating in a foreign language. Without the right vocabulary, you will find yourself struggling to express your ideas efficiently and precisely. You need a minumum of 2,500 Spanish words to be able to express well in Spanish (by that I mean you will at least be able to describe the words you don't know). It might sound like a lot, but keep in mind that a native English speaker knows more than 20,000 English words on average, and the same for native Spanish speakers (Spanish words, of course).  

While there are many tools like Quizlet that can help you memorize vocab for your Spanish tests, we recommend using SRS (Spaced Repetition System) apps like Anki to prolong vocab retention (so that you wouldn't have to cram one week before the final, for example).  


## What is Spaced Repetition? {#what-is-spaced-repetition}

Spaced Repetition is a memorization technique specifically designed to maximize long-term retention with minimum effort. Say you learned a new word and you want to make sure that you won't forget about it. Naturally you repeat this word in your mind many times in a short interval and hope that you would still remember it later. This method does not work, as you would have guessed. Human brains are quick to forget new information. A German psychologist Hermann Ebbinghaus conducted experiments to figure out just how rapidly the brain forgets. See the Forgetting Curve below:  

{{< figure src="/images/ebbinghaus.jpg" caption="Figure 1: The Forgetting Curve" >}}  

Well, you probably know that you have to review this word to commit it to long-term memory. But more often than not, most people just review their vocab list a few times and ending up forgetting them after a test. To solve the problem, you can use Spaced Repetition to remember vocab words for as long as you review them. In a Space Repetition algorithm, you would review a new word every so often, but after each successfull recall, the algorithm lengthens the duration between now and the next review. This way easier vocab words will be reviewed less and less often.  

{{< figure src="/images/forgetting-curve-srs.png" caption="Figure 2: Forgetting Curve with Spaced Repetition" >}}  


## Anki {#anki}

The first spaced repetition algorithms used simple flashcards and boxes, but we can do better. Anki is a free and open source SRS app that can not only help you memorize Spanish vocab, but just about anything else like physics equations, history facts, etc. Alternatives do exist but they are either not as robust (e.g. Quizlet) or not free (SuperMemo).  


## Notes and Cards {#notes-and-cards}

You can install Anki [here](https://apps.ankiweb.net/). Sign up on [AnkiWeb](https://ankiweb.net/account/register) to sync with your phone (AnkiMobile on iOS costs $24.99 to cover development expenses; AnkiDroid is a free third-party Android app).  

Anki should look like this out of the box.  

![](/images/_20201231_195921screenshot.png)  
[Image Credit](https://intelalearning.wordpress.com/2018/07/19/learning-myth-1-ebbinghaus-forgetting-curve/)  

At the top you can see a toolbar with five buttons (Decks, Add, Browse, Stats, Sync). If you hover above them you can see their shorcut keys. The Decks button presents to you a list of decks. Right now there should only be a "Default" deck that Anki created for you. If you've got new vocab word, click the "Add" button to create a new _note_, which brings you to the dialog below. Note that you might not have as many styling options as I do because I have installed an add-on for that. In addition, the Browse button opens a note browser useful for managing notes in bulk; the Stats button is self-explanatory; the Sync button synchronizes your collection (of decks) with AnkiWeb (register [here](https://ankiweb.net/account/register) if you haven't yet).  

![](/images/_20201231_200638screenshot.png)  
[Image Credit](https://www.researchgate.net/figure/Ebbinghaus-forgetting-curve-and-review-cycle%5Ffig1%5F324816198)  

Let's return to "Add" dialog. In the top-left corner one can see "Type [Basic]", indicating the type of note you are adding. On the right you can see that it is adding to the "Default" deck. The "Basic" note type has two fields, Front and Back. If you are memorizing a vocab word, you might put the Spanish word in Front and English translation in Back. Basic notes only go from Front to Back, so if you want to memorize the Spanish word for a given English translation, you can click the button in the top-left corner and change the note type to "Basic (and reversed card)". This will produce two **cards**, one from Front to Back, and the other from Back to Front. To clarify, a note is a set of fields, and it can generate cards that make use of the fields in their template.  

If you click "Cards..." you can view all card templates for the current note type. The Front Template is presented to you to prompt for recall, after which the Back Template is used to reveal the correct answer. You can customize the templates in HTML. These two templates share a common stylesheet (the "Styling") written in CSS. If you don't know HTML and CSS, you can learn them [here](https://www.freecodecamp.org/).  

At the bottom of the "Add" dialog you can specify the tags (space-delimitted) of this particular note. You can use it to create filtered decks or use it in the Browser, which I will cover later. After filling out the fields, click "Add" or press Ctrl+Enter.  


## <span class="org-todo todo TODO">TODO</span> Decks and Option Groups {#decks-and-option-groups}


## <span class="org-todo todo TODO">TODO</span> Learning and Reviewing {#learning-and-reviewing}


## <span class="org-todo todo TODO">TODO</span> Customizing Notes {#customizing-notes}


## <span class="org-todo todo TODO">TODO</span> Browser {#browser}


## <span class="org-todo todo TODO">TODO</span> Add-ons {#add-ons}


## Conclusion {#conclusion}

This is it! You've just began on your Anki journey. If you want to get more out of it, I recommend skimming the [Anki Manual](https://docs.ankiweb.net/#/) and look for more online tutorials. Click "Get Shared" on the bottom of the Decks panel to acquire [pre-made decks on AnkiWeb](https://ankiweb.net/shared/decks/), or go [here](https://ankiweb.net/shared/addons/) for add-ons that might improve your Anki experience. If you have any questions feel free to ask on our Discord server. I hope you got something out of this post and thank you for reading.
