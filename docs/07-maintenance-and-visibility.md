# Maintaining a dataset

## Semantic versioning

Research data is usually work in progress. When we gain more experience we usually understand better how to do everything, and no matter how hard we try, there are always mistakes. Versioning is a central concept here. We just discussed publishing the data, and it's a good convention to call the first version 1.0. After we have done some changes, we can always publish the version 1.1, 1.2, and so on. Or we can use 1.0.0, 1.0.1 etc. I do not think the conventions with this are very well established yet. [Semantic versioning](https://semver.org/) is one concept that may be useful here. This means that the three numbers in the version number do have specific significance. In the software context they would mean:

1. MAJOR version when you make incompatible API changes,
2. MINOR version when you add functionality in a backwards compatible manner, and
3. PATCH version when you make backwards compatible bug fixes.

With research data one could also imagine conventions where the numbering corresponds roughly to how likely the change is to mess up the code and analysis done for the earlier version of the corpus. This is not really something anyone does, so let's not dwell too much into it. Still, the idea that we can update our research data is very important. 

## Keeping a changelog

When we update the resource in any way, however, there should be some changelog. This means a simple listing of what kind of changes have been done between the versions. Here is an example of changelog of [Zyrian Komi treebank](https://github.com/UniversalDependencies/UD_Komi_Zyrian-Lattice/) curated by me. It is arguably not the best changelog ever, but it is much better than none at all!

- 2020-04-30
  - Auxiliary, feature and deprel documentation
  - New sentences added from grammar Ӧнія коми кыв: морфология
- 2020-10-31
  - 193 new sentences added from grammar Ӧнія коми кыв: морфология
  - 10 new parallel sentences added that are shared with [Komi Permyak](https://github.com/UniversalDependencies/UD_Komi_Permyak-UH) treebank
- 2020-05-15
  - Parallel sentences from Minjin shared with Komi_Permyak-UH.
  - Expanding advmod:mmod, :lmod and :tmod.
  - Punctuation was harmonized
  - Various consistency improvements were made, especially in converbs
- 2019-10-11
  - Improvements in annotation consistency: Unmarked accusatives analysed as nominatives, aux:neg and acl:relcl new added relations. Individual lemmas corrected. Few missing tags added and POS classes reconsidered Gerunds classified as converbs. Features for PronTypes and Degree improved. New sentences added. Few typos corrected.
- 2019-04-30
    - Annotations harmonized
- 2018-11-01
  - README file updated and various corrections done
- 2018-10-18
  - New sentences from various sources added

And besides this we do have the version control of the whole project, starting from 2017. However, it is not particularly easy to get the glance of these changes just by looking into the version history, no matter how good and descriptive the commit messages. 

## Tracking the use of dataset

It's a nice idea that we could follow somehow what all happens to the research data we publish. In practice this is not necessarily very easy. In principle, one could assume, that if data is findable, relevant and easy to use, once it is downloaded enough there will also be some use. 

We can track in services such as Google Scholar when some resource is cited, but in my experience this is not always very accurate. To know when the dataset has been used would important especially for merit: data citations are citations. Additionally if someone uses the datasets and creates something new, or modifies or extends it in some manner, then we should know about this so that we do not repeat the same work. 

Finnish Social Science Data Archive, for example, has in their terms and conditions that:

> The user shall notify the archive of all publications where she or he has used the data.

This way the archive gets the information. In this case this is very useful, as the data has been moved into the archive's repository. This is a very important question in general when we discuss research data: who is the actual maintainer? When we move the data into this kind of a larger and more established archive or repository, there are normally contracts signed that allow that organization to handle various processes in relation to the data. This often means that the archive can handle the data requests without asking the original authors, and collects and curates the material such as who have used it and which ways. 

There is a bit different model going on when we store the data openly into repositories such as Zenodo. 

# Visibility

## Related materials

[palmerpenguins](https://github.com/allisonhorst/palmerpenguins) is a good example of a dataset that has a logo and related artwork [@palmer]. The dataset is released under CC-0. The artwork is by [allison_horst](https://twitter.com/allison_horst). 

![palmerpenguins R package's logo](media/palmerpenguins.png){width=30%}

Sometimes your data may be very specific, and there can be concepts that are not obvious to many who still could be interested about them. If your dataset is really good and useful, people may want to use it in teaching. It is not a bad idea to make this as easy as possible. 

![Educational art material about penguin culmen length and depth are measured](media/penguin-bill-dim.png){width=50%}

Important message here is also that we do not need to be boring all the time with our data.

## Social media

It can be a good idea to let people know about your work through social media. I'm not an expert in this, but I assume I should also do this more myself. 

## Mailing lists

If your field has some mailing list where most of the researchers are, then if a major new dataset in your field is created, it is very recommendable to send an email about this. Lots of this work is really relevant for a small research community, and no matter how findable our data is, if nobody knows to search for it they will not end up using it. 

## Recommend it to your students

It can be a be really strong model to foster new research if the datasets created by some older researchers are further used by their students in BA and MA thesis, and elsewhere. Research community is quite wild place with lots of weird people who have their own ideas of what they want to do. People may not gravitate toward your dataset no matter how good it is. But by advising your students to use it, and guiding them through the instructions and how to use it, it is certainly possible to create bit more vibrant research environment where the same materials are used in different studies from different angles. 

# Ok, but my data sucks! 😭

Mine too! But this is not really true, and we are all getting better in this continuously. And the system is built so that we can update our mistakes, if there are those, and create incrementally better materials and studies. The most common reason not to publish data is probably the fear that it is not good enough. 

This is also why I want to emphasize the benefit of data sharing and publishing in further work that it allows. We can build on top of each others work, and make something larger than what we could ever do alone. I think we put at times too much weight on verification. Of course it is useful to be able to check what has been done in some study, but I also think we should be nice and merciful to one another, and try not to focus too heavily on the mistakes we all inevitably do.

Luckily this kind of attitude seems to be relatively rare, and my experiences in publishing linguistic data and using the data of others has been very positive. I'm confident the same will be true also for you. 
