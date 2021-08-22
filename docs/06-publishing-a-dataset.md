# Publishing a dataset

Publishing a dataset differs in critical ways from publishing, for example, an article. The emphasis is less in publishing as such, but in creating a resource that is stored in an unchanged and well documented structure, and that is located in some organization where we can rely that it will be foundable and curated in the future. 

One way how different ways to publish a dataset differ lies in maintenance and responsibility. We'll discuss this more later, but cover here some basics. There are several repositories where we can login, and upload our own data, and then also edit and curate it. There are certainly some validation mechanisms, sometimes less and sometimes more, but still the depositor kind of remains the curator and maintainer of the dataset. 

This differs greatly from more traditional model, where, for example, we would archive the materials into a physical archive, and in connection to this sign a contract that specifies very well how the responsibilities are in relation to the data now and later. 

I don't think FAIR really addresses this question so much. Again, as discussed before, more firmly the data is in hold and curation of an actual organization that specifies to this kind of work, the better this is in many ways. If the dataset is entirely processed, uploaded and maintained by an individual researcher, then the user may have to spend more time to make certain everything is as should be expected. 

As we discussed before, you should have an idea where to publish the dataset already before you start to work with the data at all. This is already a part of the data management plan, and with many repositories it is important to communicate very early what kind of data you would like to store and what kind of documentation and forms the repository demands. 

## Where to publish

There are plenty of ways to publish research data. Only way to answer which solution suits the best your needs is to examine in detail the context where you are working. Are there some repositories that are widely used in your field? What are the solutions most used by your colleagues? In some cases a non-perfect solution that is similar to the standards of your fields may be the best. 

There may also be institutional constraints. For example, universities at times have their own data storage solutions, and they may want you to use them. University of Eastern Finland, for example, has this repository. At the same time there are also national solutions, such as Fairdata services in Finland, or CHECK services in Estonia. So you may want to prefer the solution of your university, at least if you plan to stay in the university, or the national system, if there are reasons to consider that infrastructure worth contributing into.  

In Finnish [Fairdata](https://www.fairdata.fi/) infrastructure there is a constellation of several tools that can be used to store, describe and find research data. It also connects well to digital preservation system. There is certainly some redundancy in different countries and organizations building their own solutions, but still, this it's better to have many possibilities than not any. 

Your funder may also have something to say about the chosen data storage platform. At the same time I think it is still relatively common that the funders are not very explicit about this. They want the data management plan, which shows you have thought about these things, but it seems there is still some space for different solutions. 

## Zenodo

Let's discuss first the easiest solution. Your data has no personal information, it is clearly licensed, so you can use and license it pretty much however you like. In this context Zenodo is a very good alternative. [Zenodo promises](https://about.zenodo.org/policies/) to store your data at least 20 years.

> Items will be retained for the lifetime of the repository. This is currently the lifetime of the host laboratory CERN, which currently has an experimental programme defined for the next 20 years at least.

The good thing is that [CERN](https://home.cern/) is a pretty large project. Having it closing in 20 years is not really that realistic. Or if institutions of this magnitude are closing down, then we have already larger problems in our hands. 

## More complicated situations

Let's then discuss more complicated solutions. In many countries, I believe, there are local archives for various research datasets. In Finland we have [Finnish Social Science Data Archive](https://www.fsd.tuni.fi/en/). It is widely used in social sciences, and is a well known and valued archiving solution in Finnish context. The data they take in is normally anonymized, and they do not take multimedia. 

[The Language Bank of Finland](https://www.kielipankki.fi/language-bank/) is another organization that takes multimedia materials in Finland. Essentially they target the data in linguistics, so for other types of recorded material one has to look for other options. [Finnish Literature Society](https://www.finlit.fi/en) is one organization in Finland that has plenty of folkloric materials in their archive, for example. [Music Archive Finland](https://musiikkiarkisto.fi/music-archive-finland.php) would also match some types of data. [Society of Swedish Literature in Finland](https://www.sls.fi/en) has a very good archive for materials in Swedish Finnish. **At the moment in Finland the conditions to archive audio-visual material are extremely unclear.** In Estonia there is excellent [Archive of the Estonian Dialects and Finno-Ugric Languages](http://emsuka.eki.ee/) at the Institute of the Estonian Language. In Estonia there is also [Center of Estonian Language Resources](https://keeleressursid.ee/en/). 

[The Language Archive](https://archive.mpi.nl/) and [Endangered Languages Archive](http://elar.soas.ac.uk/) (moving to Berlin soon from London, so back to EU) are two good and widely used solutions to store spoken language materials. They have good access control mechanisms. Interfaces, however, are only in English. 

## Possibilities outside Europe

It's also possible that your research data is particularly closely connected to some geographical region, and you may want to prefer repositories that are closer to those areas or offer the user interfaces in the local languages. [The Archive of the Indigenous Languages of Latin America](https://ailla.utexas.org/), for example, would easily come to mind if you work with endangered language materials from that area. [Pacific and Regional Archive for Digital Sources in Endangered Cultures](https://www.paradisec.org.au/) is another very good example. Their interfaces exist, for example, in Tok Pisin and Indonesian. Recently also [Archive of Languages and Cultures of Ethnic Groups of Thailand](https://langarchive-th.org/) was launched. When we work in the European academic context, these may be bit far away from what we usually can consider, but if we want to be less Euro-centric, there are options. **Now, storing this kind of materials outside EU may be very complicated for GDPR, among other things, so don't take this as a recommendation.** But be aware about the plurality of possible practices, and I think there may be situations where we do international collaboration where there are various very valid reasons to store the research data also outside Europe.

Another axis that impacts strongly to the available choices is the restriction level. Can you share the data online with an open license, or are there more granular access levels? If there are, then you have to store data to an organization that allows user identification and can negotiate the access granting. 

## Writing a data paper

One common model is to publish an article at the same time with the publication of the dataset. Different journals in various fields accept nowadays data papers that do not contain new research as such, but describe the dataset. [Here](https://www.gbif.org/data-papers) are some examples of such papers in biodiversity-related fields. In computational linguistics there is also a conference that publishes proceedings that describe datasets and tools, [The International Conference on Language Resources and Evaluation](http://www.lrec-conf.org/). In digital humanities [DHNB](http://dhnb.eu/) is probably one well working venue. 

There is also a related practice that if the dataset is used very thoroughly and extensively in some study, where it is also described up to some detail, then the data creators may point that study as one of the items cited when using the dataset. This is not maybe that common, but there are numerous examples. For example, [Phonoprosodic corpus of spoken Catalan (PhonCAT)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/spoken-corpus:phoncat). 

This kind of papers can be really useful in giving even better description for the materials, and it also follows the FAIR principles that these studies are connected to the dataset. The most important reason why data papers are so popular is still that this way we can tie the citation of the dataset into a peer reviewed publication. At times I've also had discussions where it is argued that this is not a good development. We should cite the datasets and resources, and the citation into them should be valued as highly as publication citations. I absolutely agree with the idea and spirit: we should value datasets just like publications. But this is not the reality yet, I'm afraid. When we apply for jobs and positions peer reviewed articles do count differently than our datasets. 

So my take to this is very much that the older well established researchers should do everything they can to increase the value of the dataset citations, and meanwhile we who are in more precarious positions should consider playing this stupid game with the old rules as well as we can. 

We often end up in a situation where we want to publish the data and our study separately, or possibly publish with the paper just a subset or somehow processed version. 

Universal Dependencies [@ud] is a good example about a large project where individual sub-projects are located inside the main project. Everyone who contributes is within the authors of the whole dataset, but it is also possible to cite very exactly the individual treebanks as needed. 

## Dataset and code

It is important to archive also the code, especially when it has been used to transform the dataset from an earlier dataset. 

## Who did author this thing?

I think it's a good idea to have all names of everybody who did something with the dataset. This is not a place to be cheap on authorship. Maybe the most research project's leader can be the first or the last, but alphabetical order is also very good. I also like the idea that the roles and tasks would be fairly well described somewhere, so that people would have even more transparent way to show their skills and areas of experise. 

## Ethics & Data statements

In natural language processing research we see nowadays occasionally separate data statements associated with individual studies and datasets. The idea is to describe in detail what kind of population the dataset is based upon, and what can be the potential biases and risks in using it [@benderEtAl2018a]. in [@levow2021developing] we also see an example where the paper includes a section about ethical considerations, located between the Discussion and Conclusions, being an independent and important part of the study. This is an extremely good development, and somewhat distinct from FAIR, but very much connected to this approach if we truly care about how the data is created and used. There are numerous questions that only arise in specific contexts, which may necessitate the description of some issues for specific studies. For example, the use of speech recognition impacts all audio datasets in very specific ways, and also forces us to reconsider under which conditions these datasets can be made open. 

