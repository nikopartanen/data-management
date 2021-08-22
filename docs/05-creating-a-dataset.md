# Creating a dataset

In this step we have decided that we need to create a dataset. When we start to design it, I think one very important aspect to remember is:

> Collect only the data that you actually need!

I understand that this is not very welcome idea for many researchers, and we have a long tradition of collecting, for example, interview data rather widely about topics where we do not really know what will be important, and thereby we end up with very broad and varying materials. This kind of data is in many ways very rich and important, but at the same time we have to be able to justify what kind of personal data we process, and we have to know very specifically what kind of data we have in our collections. If we focus into collecting and storing the data we actually need, this much easier, and this also makes the work much easier for us. 

At least in linguistics we have a very long tradition of collecting large amounts of spoken data, then transcribing it and annotating the texts with very specific conventions. I've been arguing toward a structure where we do record widely, but already in the transcription phase see pretty much effort to select what we transcribe so that the resulting corpus is as good and balanced as possible. For the annotations my strategy has also been to annotate only those sentences that contain the feature I'm interested about, and then annotate only those aspects of each observation that I truly need in my study. The data is available, and the other researchers are perfectly able to annotate whatever they need. 

## Scenario 0: Your dataset may be just a piece of code

In many cases we can query a larger dataset through an API, or there are other specific download services. In these cases we do not necessarily have to store the dataset again anywhere, but it is very important to include the original query script or its documentation in your dataset. 

If it is not possible to redistribute data, but it is accessible for you through your institution's access contracts or policies, then it could be a very fair and transparent decision not to share the data itself in any manner, but document in detail how you acquired the dataset through these services, and which version you used. Metadata level information just as filenames and page numbers could be used in this connection to further clarify what exactly belonged to the used resource. It will be a test for our infrastructure whether the same dataset can be received again in the future, but if we document these means well enough, I think we are already doing pretty decent work. 

Many data repositories are not really designed for this kind of use, but I believe this will be changing in the future when we have more experience and examples of how to do it.

## Scenario 1: Using an existing dataset

We can be very lucky, and a dataset that is very suitable for our purposes already exists. First we should spend considerable time to dig little bit deeper into it. Who has done it, and what kind of documentation there is? From where does this data actually come from? 

Even though the dataset would had been made already open, we still have to think bit more broader what all it contains. What kind of data can be made available has been a moving target for quite a long time already, and there are older and newer materials with quite different practices. It is also very possible that someone has licensed the dataset openly, but in reality it contains some copyrighted material for which no arrangements have been done. It is very common that these practices are not very clear to anyone, and even the original authors may not be really aware of who actually has what kind of rights. It is a fairly good excuse if you used materials someone else has already licensed, and where everything seemed to be ok, but this doesn't remove our responsibility from taking these things into account either.

Again, we have to ask how the dataset is licensed? The main difference here is whether we can just take the entire material and transform it into something that is suitable for us, and redistribute that version with our study, or are there some limitations that specifically follow from the license. 

## Scenario 2: We collect some new data

One very good practice is to run a tiny pilot. Let's say you want to collect a survey. It is useful to get few filled examples, and already with those do put the answers to the database or whatever structure you want to use in your research. After you have done this, start to sketch the analytical code you are going to use. Have a minimal working example that shows you actually can get from this setup the type of structure or observation that you will analyse in the end. 

Testing and planning is particularly important if you are going to invest lots of time to the data collection, or if you are going to bug other people and spend their time too. I guess if we are just wasting our own time then we can do what we like and learn from our mistakes, but also here the normal course of action would be that we get enough advices and guidance from our supervisors and collaborators that we don't screw this up too much. 

Currently one of the most important delineations here is whether the data we collect or work with contain sensitive data. This is a special category of personal information. 

## Organizations are our friends

It's usually a very good situation if the the data we use is released or approved by some more recognized organization. [Finnish Social Science Data Archive](https://www.fsd.tuni.fi/en/) is a good example. As the researchers cannot update material there all by themselves, it is bound to be curated in various ways. The National Library of Finland is another good example. They have plenty of openly available material in their [Digi-service](https://digi.kansalliskirjasto.fi/etusivu?set_language=en), and much is explicitly marked as Public Domain. The user still has the responsibility for reuse they do, but the fact that an organization like this has made the consideration about this already does put our reuse already at firmer steps. 

Organizations are also important for us when the datasets are processed otherwise. More complicated the project, more ambitious and larger the intended dataset, more important it is that everything is led by competent professionals with plenty of experience in this, and that the affiliations and institutional roles are clear. In really large projects the responsibility should be at pretty high levels on the ladder. Not so much because of the merit, which I think we should share liberally to everyone who has contributed even little, but because of the security and reliability larger organizations bring. 
