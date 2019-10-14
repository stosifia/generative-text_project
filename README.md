# generative-text_project
Generative Text Project for ECE 188

Abstract: Stand Up Comedy Generator/Bot

The goal of this project is to create a character-based RNN that generates text/material (hopefully) in the vein of a stand up routine/special (specials traditionally being longer performances).


The initial plan is to train individual networks on transcripts from stand up routines performed by various comedians in the hopes that each network can learn the 'style' of humor/stand up comedy of its respective comedian 'source data'. Afterwards, an exercise can be carried out by generating data from a randomly chosen network and trying to determine (as a human audience) what comedian the network is 'trying' to emulate (i.e. what it was trained on). 

Moreover, a network will then be trained on the amalgamated data (transcripts from all the comedians) and will be used to generate 'unique' material that would ideally draw upon different elements of its source material



This topic was chosen primarily based off the idea that humor and comedy are for the most part seen as very human forms of expression. Humor (at least in the context of stand up comedy) often requires a large awareness of social context, basic human psychology, and reception to feedback (especially in an open mic context), amongst many other (what we see as) humanistic traits, such as creativity. Therefore, a hypothesis is that humor and comedy would be one of the last frontiers of human expression that a learning algorithm/'AI' would be able to replicate well, especially when it's only in a text-based language setting. As a result, my personal opinion is that the output won't be of any significance, especially with such a naive architecture (and inexperienced architect). However, it should be a fun(ny) exercise!


Of course, there are numerous restriction on this data - one big one being that this a textual translation of stand up comedy, which often relies as much on delivery as it does on material - and delivery is very hard to transcribe. So that dimension will be entirely missing.
