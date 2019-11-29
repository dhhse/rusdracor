# rusdracor_relations
This is a repository for RusDraCor project
## Proposed project title: Fathers, Mothers and Children

Let’s think about relatives in drama. What can we say about characters and their speeches, if we focus on their family status? There are fathers and mothers, sons and daughters, husbands and wives in dramas. There are even friends and lovers, who often do interrupt in a family world and influence on development of the plot. What if we extract not only the gender information (see Gender specifics in character speech in [Building a Corpus for the Quantitative Research of Russian Drama: Composition, Structure, Case Studies] (http://www.dialog-21.ru/media/4332/skorinkind.pdf) but also annotate characters with relation labels? This markup will help us easily find all speeches related to particular family members, so we could make the statistical comparison of, for example, parents and children speeches in the corpus.
Here's the overview of types of relations (from our partners in Stuttgart): <https://github.com/quadrama/Corpus#relations>


## MVP

RusDraCor consists of about 200 dramas. We plan to annotate characters from the <listPerson> in XML with a relative label according to the description in <https://github.com/quadrama/Corpus#relations>. 


## EP

That is Analysis. The usage of the relative labels allows us to make a quantitative research of the data using Stylo package for R. An article with the results published in a DH-related journal is supposed to be a physical product of the project.

What can we count using relation makups?

- The length of parents' speeches vs child's speeches. Which group does speak more?

- Exclamation marks (?!) and interjections (Ах! Ох! Ба! Хм, Гм etc). Who's speech is more emotional?

- Words for parents' speech vs words for child's speech. What words are more prefered by parents and by children?

- Words for a female parent vs words for male parent. Are they different?

- How do parents address to children vs how do children address to parents (comparing with IDs, the usage of 'вы' and 'ты').

- Scenes with a parent and a child. How many scenes in drama where a parent speaks with a child?

- Agreements and disagreements. (Amount of 'да' и 'нет').

## HAP
It seems to be cool to make a usable open API, so anyone could make their own research based on the family relation’s metadata. This could be the beginning of some new wonderful projects like Shiny Dracor https://shiny.dracor.org/.

## Release
Every Friday at 5 p.m. Alexander and Anna are meeting to make a release of the previous tasks. If it was a busy week, we make an agreement on a delay and play table tennis. Anyway, we discuss our next step for the next week and play table tennis 😊.

## Calendar
via Google Calendar
https://calendar.google.com/calendar/ical/c6p95gcjj29cn4t67earemv8hk%40group.calendar.google.com/private-fc0615aee7c428b7dd3e623a0e72cea5/basic.ics
