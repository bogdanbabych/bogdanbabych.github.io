---
layout: default
title: proj2007leverhulme
nav_order: 8

---

## Prof. Dr. Bogdan Babych
### Professor of Translation Studies, Head of Department of Translation, Communication and Technology
### Institute for Translation and Interpreting, Heidelberg University

[Home](index.md) | [Research](research.md) | [Teaching](teaching.md) | [Collaboration](collaboration.md) | [Techologies](techlabs.md)


#### Leverhulme Early Career Research Fellowship (2007-2009)
##### Project outline: Translation Strategies in Comparable Corpora

As the declining foreign-language skills of scholars increasingly inhibit research in the humanities and social sciences, so the need grows more urgent for linguistic models that can improve the quality of Machine Translation to make foreign-language written data accessible in English.

A fundamental problem in translation is to choose that equivalent from a set of potential equivalents which best fits the target language context. The proposed research will borrow from language modelling techniques used in Information Extraction to automatically identify and rank translation equivalents according to their contextual relevance. Focusing on English and Russian, it will use parallel, translated data to identify classes of the non-literal translation strategies adopted by translators, which will be modelled in a computer program. The model's ability to identify good translation solutions to novel translation cases will be tested on very large comparable corpora -- texts in the same domain which are not translations of one another. Evaluation will be conducted with professional translators. The work's theoretical significance lies in providing an important link between language, knowledge and the subject domain, which is essential for the process of translation.

Translation strategies are operations used by human translators to bridge the source and target languages with functionally equivalent constructions (Munday, 2001: 55). **Indirect** strategies employ translation shifts -- linguistic changes that deviate from word-for-word rendering of the original (Bakker et al., 1998: 226). Theories of translation strategies and shifts that have been proposed to date (Vinay and Darbelnet, 1959, 1995; van Leuven-Zwart, 1989, 1990) are descriptive: they categorise operations found in existing translations, but do not predict actual shifts that will work for previously unseen translation problems. Thus, they offer little support for translators in solving novel cases, which has contributed to the well-documented split between translation theory and practice and to a widespread view that translation cannot be theorised (Munday, 2001: 15).

There is a need for a model of translation strategies and shifts which has predictive power, i.e., which can support scientifically testable hypotheses and predict observable consequences from the theory (Yngve, 2003: 332). In particular, it should offer testable solutions to individual, previously unseen translation problems. Such a model should support translators in making decisions about challenging translation tasks in a systematic way, increasing consistency and efficiency.

The main objective of the proposed research is to develop and evaluate a predictive model of indirect translation procedures which can offer practical methods for applying appropriate translation shifts and find potentially useful solutions. This will be done by investigating general mechanisms behind individual shifts and testing deductive hypotheses about these mechanisms on real translation problems. To permit rigorous testing, the model will be implemented as a computer program and derived from very large corpora of English and Russian texts. This will constitute a dynamic resource for translators, which will apply the discovered and clearly understood translation strategies to novel expressions and contexts on-the-fly and generate potentially useful non-literal suggestions.

Traditionally, shifts have been described on the basis of parallel texts, i.e., collections of texts paired with their (human) translations. Although parallel corpora are also used in electronic translation resources (Somers, 2003: 513, 524), these static resources currently cannot apply indirect strategies to novel contexts. Attempts to extend their coverage have focused primarily on using larger corpora, rather than developing more general models for translation procedures applicable to open classes of contexts. In contrast, I will use very large (100-200M words each) existing comparable corpora -- texts authored independently in the two languages, but with a comparable purpose and readership, here journalism.

The hypothesis is that translation equivalents exhibit similar usage in comparable corpora in sharing contextual features that can be mapped via dictionaries or parallel texts. Consequently, they can be discovered by searching for distributionally similar combinations of these features in the target language corpus. For example, the Russian sentence *Deti poseshchajut ploxo otremontirovannyje shkoly, v ktoryx nedostajet samogo neobxodimogo (Lit.: Children attend badly repaired schools, in which [it is] missing the most necessary)* has two problematic expressions (highlighted), where a fluent translation into English should use structural and lexical shifts. These are predicted by translating and recombining words with similar distribution in the source and target corpora, i.e., English translation of *ploxoj (bad)* generates a list of similarly distributed words *appalling, awful, dreadful, ill, poor...*, and the Russian word *neobxodimyj (necessary)* yields a list that includes *vazhnyj = important*, which in its turn has similar distribution to the English word *essential*. These lexical features of constructions are then recombined and checked for co-occurrence in the target language corpus, predicting the fluent translation equivalents: *in poor repair* and *lacking basic essentials*.

The methodology will employ the framework of construction grammar (Fillmore and Key, 1993), distribution-based approach to meaning (Firth, 1957), and quantitative methods that measure the distributional similarity of constructions and can accurately generate thesauri (lists of near-synonyms) for words and phrases that have similar neighbours in the corpus (Rapp, 2004).

The evaluation of the computer-based model will include subjective tests done by human translators of the usefulness of proposed solutions, and objective experiments that will match the solutions to a corpus of multiple human translations of problematic expressions. The research will focus principally on English and Russian, but the model's extensibility to German and French will also be tested.

The primary output of the research will be publication of two articles on discovering translation procedures and shifts in comparable corpora intended for international journals in Translation Studies, such as __Meta__ and __The Translator__. A monograph "Modelling Indirect Translation Strategies" summarising the results of the research will be written for St Jerome Press. Wider dissemination of the results will involve participation in the annual international conferences of the Association for Computational Linguistics (ACL) and Translating and the Computer organised by Aslib in London and presenting a paper at the 2009 IATIS conference. The translation tool will be made available online, and a workshop for professional translators will be organised with members of the Chartered Institute of Linguists and the Institute for Translation and Interpreting. It will have two tasks -- evaluating the resource in a working environment and introducing it to translators, who may adopt it in their day-to-day work.

##### References
Bakker, M., Koster, C and van Leuven-Zwart, K. 1998. Shifts of translation. In: Baker, M. (ed.) Routledge Encyclopedia of Translation Studies. London: Routledge. pp. 226--231.

Filmore C. and Kay, P. 1993. Construction grammar coursebook, chapters 1 through 11 (Reading materials for Ling. X20). Berkley: University of California.

Firth, J. 1957. A Synopsis of Linguistic Theory 1930-1955. In: Studies in Linguistic Analysis, Philological Society, Oxford.

Leuven-Zwart, K. van. 1989 and 1990. Translation and the original: similarities and dissimilarities, I and II, Target 1.2 pp 151--81 and Target 2.1, pp. 60--95.

Munday, J. 2001. Introducing translation studies. Theories and applications. London: Routledge.

Reinhard Rapp. 2004. A freely available automatically generated thesaurus of related words. In Procs. LREC, 2004. Pp. 395--398, Lisbon.

Somers, H. 2003. Machine Translation: Latest developments. In: Mitkov, R. (ed.) Oxford handbook of Computational Linguistics. Oxford and New York: Oxford University Press. Pp. 512--528.

Vinay J.P. and Darbelnet J. 1958. Stylistique compare du français et delánglais: Méthode de traduction. Paris, Diter, translated and edited by J.Sager and M.-J Hamel (1995) as Comparative Stylistics of French and English: A Methodology for Translation, Amsterdam, Philadelphia, P.A., John Banjamins.

Yngve, V. 2004. The conduct of the hard-science research. In: Yngve, V. and Wasik, Z. (eds.) Hard-Science Linguistics. London and New York: Continuum. Pp. 332--341.
