---
layout: favipage
title: About
permalink: /
---

Have you have observed something twisted in genomics data? Do you feel like genomics is sometimes more a black magic than science? Well, then let's do something about it. Here, I would like to create a plaform for collecting and sharing peculiar genomic observations, so everyone can take a look if something similarly-weird have been observed before or not.

The collection intens to be inclusive for biological pecularities (e.g. massive polymorphic deletions, obscure repetitiveness, ...) and technical artifacts (e.g. unexpected outcome of whole genome amplification, contamination of samples etc.), but also unexplained peculiar observations (e.g. a strange kmer spectra that does not have a satifactory explanation), all welcomed.

This idea is based on feedback I got on my PopGroup53 talk "Peculiar Genomics Cases", where I presented the first three cases that will initiate the page.

### Contributing

PLEASE DO.

It will require you to fork this repository, adding one more `.md` file with your peculiar observation to `_post` directory, and adding yourself in the list of authors (`_data/authors.yml`) and make a pull request. I will check that everything is in check and accept it.

I will create a more detailed guidelines soon, if interested, get in touch.

I would be happy to get more people to run the webpage, although maintaining a jekyll web is quite easy, so I might manage by my own. However, if you feel opinionated about anything (what should/not be part of this webpage), now it's the good time to speak. More people will get involved, harder it will be to change things.

#### Contribution notes

- "Author" is an author of the post, if the observation was not done (solely) by you, mention the original source (publication, other authors) in the text. The same with the explanation of the observation.
- I tried to structure the posts in four sections, intro, observation, explanation and methods. Introduction should contain enough information to explain why the observation is peculiar. More references the better. Observation should as plainly as possible show what is the strange observation and following supporting analyses to figure out where the observation comes from. The explanation should wrap up the analyses and conclude what we have learned from this observation. Methods need to contain at least the names of used software and links to publicly available data (I think we should refuse non-public datasets). However, you can get much more creative. Link your GitHub repo, methods of a paper, add sniplets of code... feel free to explore what works for you.
- figures for posts should be stored as `assets/<post_name>/<figure1.png>` (e.g. `assets/2020-01-08-crayfish`). Try to keep total sizes of figures for a single post smaller than 1MB.
- I hoped for bibtex based citation manager, but I could not make that work natively on github, I ended up just manually linking DOIs. This might change in future if I find a way around.
- I also hoped to have a domain only for peculiar observations (having my name in the url was not the goal), if you would know how to get one without saying a forture, get in touch.