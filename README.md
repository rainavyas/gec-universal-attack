# GEC Paper
Offiial Code for AACL 2022 submission: "Grammatical Error Correction Systems for Automated Assessment: Are They Susceptible to Universal Adversarial Attacks?"

## Absract

Grammatical error correction (GEC) systems are a useful tool for assessing a learner's writing ability. These systems allow the grammatical proficiency of a candidate’s text to be assessed without requiring an examiner or teacher to read the text. A simple summary of a candidate's ability can be measured by the total number of edits between the input text and the GEC system output: the fewer the edits the better the candidate. With advances in deep learning, GEC systems have become increasingly powerful and accurate. However, deep learning systems are susceptible to adversarial attacks, in which a small change at the input can cause large, undesired changes at the output. In the context of GEC for automated assessment, the aim of an attack can be to deceive the system into not correcting (concealing) grammatical errors to create the perception of higher language ability. An interesting aspect of adversarial attacks in this scenario is that the attack needs to be simple as it must be applied by, for example, a learner of English. The form of realistic attack examined in this work is appending the same phrase to each input sentence: a concatenative universal attack. The candidate only needs to learn a single attack phrase. State-of-the-art GEC systems are found to be susceptible to this form of simple attack, which transfers to different test sets as well as system architectures.

# Sub-Repositories

The submitted paper includes a range of experiments. Each set of experiments have been conducted within their own repositories:

