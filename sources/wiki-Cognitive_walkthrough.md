---
source: https://en.wikipedia.org/wiki/Cognitive_walkthrough
fetched: 2026-06-20
---

Usability inspection method 
|  | This articleneeds additional citations forverification.Please helpimprove this articlebyadding citations to reliable sources. Unsourced material may be challenged and removed.Find sources:"Cognitive walkthrough"–news·newspapers·books·scholar·JSTOR(June 2024)(Learn how and when to remove this message) |
| --- | --- |

 

The **cognitive walkthrough** method is a [usability inspection](./Usability_inspection) method used to identify [usability](./Usability) issues in interactive systems, focusing on how easy it is for new users to accomplish tasks with the system. A cognitive walkthrough is task-specific, whereas [heuristic evaluation](./Heuristic_evaluation) takes a holistic view to catch problems not caught by this and other [usability inspection methods](./Usability_inspection_method).
The method is rooted in the notion that users typically prefer to learn a system by using it to accomplish tasks, rather than, for example, studying a manual. The method is prized for its ability to generate results quickly with low cost, especially when compared to [usability testing](./Usability_testing), as well as the ability to apply the method early in the design phases before coding even begins (which happens less often with usability testing).

 

## Introduction

 

A cognitive walkthrough starts with a [task analysis](./Task_analysis) that specifies the sequence of steps or actions required by a user to accomplish a task, and the system responses to those actions. The designers and developers of the software then walk through the steps as a group, asking themselves a set of questions at each step. Data is gathered during the walkthrough, and afterwards a report of potential issues is compiled. Finally the software is redesigned to address the issues identified.

 

The effectiveness of methods such as cognitive walkthroughs is hard to measure in applied settings, as there is very limited opportunity for controlled experiments while developing software. Typically measurements involve comparing the number of usability problems found by applying different methods. However, Gray and Salzman called into question the validity of those studies in their dramatic 1998 paper "Damaged Merchandise", demonstrating how very difficult it is to measure the effectiveness of [usability inspection methods](./Usability_inspection_method). The consensus in the usability community is that the cognitive walkthrough method works well in a variety of settings and applications.

 

## Streamlined cognitive walkthrough procedure

 

After the task analysis has been made, the participants perform the walkthrough:[[1]](./Cognitive_walkthrough#cite_note-1)

 
1. Define inputs to the walkthrough: a usability specialist lays out the scenarios and produces an analysis of said scenarios through explanation of the actions required to accomplish the task.

1. Identify [users](./End_user)
2. Create a sample task for evaluation
3. Create action sequences for completing the tasks
4. Implementation of interface

2. Convene the walkthrough:

1. What are the goals of the walkthrough?
2. What will be done during the walkthrough
3. What will not be done during the walkthrough
4. Post ground rules

1. Some common ground rules

1. No designing
2. No defending a design
3. No debating cognitive theory
4. The usability specialist is the leader of the session

5. Assign roles
6. Appeal for submission to leadership

3. Walk through the action sequences for each task

1. Participants perform the walkthrough by asking themselves a set of questions for each subtask. Typically four questions are as

- **Will the user try to achieve the effect that the subtask has?** E.g. Does the user understand that this subtask is needed to reach the user's goal
- **Will the user notice that the correct action is available?** E.g. is the button visible?
- **Will the user understand that the wanted subtask can be achieved by the action?** E.g. the right button is visible but the user does not understand the text and will therefore not click on it.
- **Does the user get appropriate feedback?** Will the user know that they have done the right thing after performing the action?

2. By answering the questions for each subtask usability problems will be noticed.

4. Record any important information

1. Learnability problems
2. Design ideas and gaps
3. Problems with analysis of the task

5. Revise the interface using what was learned in the walkthrough to improve the problems.

 

The CW method does not take several social attributes into account. The method can only be successful if the usability specialist takes care to prepare the team for all possibilities during the cognitive walkthrough. This tends to enhance the ground rules and avoid the pitfalls that come with an ill-prepared team.

 

## Common shortcomings

 

In teaching people to use the walkthrough method, Lewis & Rieman have found that there are two common misunderstandings:[[2]](./Cognitive_walkthrough#cite_note-2)

 
1. The evaluator doesn't know how to perform the task themself, so they stumble through the interface trying to discover the correct sequence of actions—and then they evaluate the stumbling process. (The user should identify and perform the *optimal* action sequence.)
2. The walkthrough method does not test real users on the system. The walkthrough will often identify many more problems than you would find with a single, unique user in a single test session

 

There are social constraints that inhibit the cognitive walkthrough process. These include time pressure, lengthy design discussions and design defensiveness. Time pressure is caused when design iterations occur late in the development process, when a development team usually feels considerable pressure to actually implement specifications, and may not think they have the time to evaluate them properly. Many developers feel that CW's are not efficient because of the amount of time they take and the time pressures that they are facing. A design team spends their time trying to resolve the problem, during the CW instead of after the results have been formulated. Evaluation time is spent re-designing, this inhibits the effectiveness of the walkthrough and leads to lengthy design discussions. Many times, designers may feel personally offended that their work is even being evaluated. Due to the fact that a walk-through would likely lead to more work on a project that they already are under pressure to complete in the allowed time, designers will over-defend their design during the walkthrough. They are more likely to be argumentative and reject changes that seem obvious.

 

## History

 

The method was developed in the early nineties by Wharton, et al., and reached a large usability audience when it was  published as a chapter in [Jakob Nielsen](./Jakob_Nielsen_(usability_consultant))'s seminal book on usability, "Usability Inspection Methods".[[3]](./Cognitive_walkthrough#cite_note-3) The Wharton, et al. method required asking four questions at each step, along with extensive documentation of the analysis. In 2000 there was a resurgence in interest in the method in response to a CHI paper by Spencer who described modifications to the method to make it effective in a real software development setting. [Spencer's streamlined method](https://facweb.cdm.depaul.edu/cmiller/eval/p353-spencer.pdf) required asking only two questions at each step, and involved creating less documentation. Spencer's paper followed the example set by Rowley, et al. who described the modifications to the method that they made based on their experience applying the methods in their 1992 CHI paper "The Cognitive Jogthrough".[[4]](./Cognitive_walkthrough#cite_note-4)

 

Originally designed as a tool to evaluate interactive systems, such as postal kiosks, automated teller machines (ATMs), and interactive museum exhibits, where users would have little to no experience with using this new technology. However, since its creation, the method has been applied with success to complex systems like CAD software and some software development tools to understand the first experience of new users.

 

## See also

 
- [Cognitive dimensions](./Cognitive_dimensions), a framework for identifying and evaluating elements that affect the usability of an interface

 

## References

  
1. [↑](./Cognitive_walkthrough#cite_ref-1) Spencer, Rick (2000). ["The streamlined cognitive walkthrough method, working around social constraints encountered in a software development company"](http://portal.acm.org/citation.cfm?doid=332040.332456). *Proceedings of the SIGCHI conference on Human Factors in Computing Systems*. The Hague, The Netherlands: ACM Press. pp. 353–359. [doi](./Doi_(identifier)):[10.1145/332040.332456](https://doi.org/10.1145%2F332040.332456). [ISBN](./ISBN_(identifier)) [978-1-58113-216-8](./Special:BookSources/978-1-58113-216-8). [S2CID](./S2CID_(identifier)) [1157974](https://api.semanticscholar.org/CorpusID:1157974).
2. [↑](./Cognitive_walkthrough#cite_ref-2) Lewis, Clayton; Rieman, John (1994). ["Section 4.1: Cognitive Walkthroughs"](http://hcibib.org/tcuid/chap-4.html#4-1). [*Task-Centered User Interface Design: A Practical Introduction*](http://hcibib.org/tcuid/index.html). pp. 46–54. Retrieved April 10, 2019.
3. [↑](./Cognitive_walkthrough#cite_ref-3) Wharton, Cathleen; Riemann, John; Lewis, Clayton; Poison, Peter (June 1994). "The cognitive walkthrough method: a practitioner's guide". In Nielsen, Jakob; Mack, Robert L. (eds.). [*Usability inspection methods*](https://dl.acm.org/doi/abs/10.5555/189200.189214). John Wiley & Sons. pp. 105–140. [ISBN](./ISBN_(identifier)) [978-0-471-01877-3](./Special:BookSources/978-0-471-01877-3). Retrieved 2020-02-11. `{{cite book}}`: `|website=` ignored ([help](./Help:CS1_errors#periodical_ignored))
4. [↑](./Cognitive_walkthrough#cite_ref-4) Rowley, David E; Rhoades, David G (1992). "The cognitive jogthrough: A fast-paced user interface evaluation procedure". *Proceedings of the SIGCHI conference on Human factors in computing systems - CHI '92*. pp. 389–395. [doi](./Doi_(identifier)):[10.1145/142750.142869](https://doi.org/10.1145%2F142750.142869). [ISBN](./ISBN_(identifier)) [0897915135](./Special:BookSources/0897915135). [S2CID](./S2CID_(identifier)) [15888065](https://api.semanticscholar.org/CorpusID:15888065).

 

## Further reading

 
- Blackmon, M. H. Polson, P.G. Muneo, K & Lewis, C. (2002) Cognitive Walkthrough for the Web CHI 2002 vol. 4 No. 1 pp. 463–470
- Blackmon, M. H. Polson, Kitajima, M. [(2003) Repairing Usability Problems Identified by the Cognitive Walkthrough for the Web CHI](https://www.researchgate.net/profile/Muneo_Kitajima/publication/221514993_Repairing_usability_problems_identified_by_the_Cognitive_Walkthrough_for_the_Web/links/00463537cb1c7e994e000000.pdf) 2003 pp497–504.
- Dix, A., Finlay, J., Abowd, G., D., & Beale, R. (2004). Human-computer interaction (3rd ed.). Harlow, England: Pearson Education Limited. p321.
- Gabrielli, S. Mirabella, V. Kimani, S. Catarci, T. (2005) Supporting Cognitive Walkthrough with Video Data: A Mobile Learning Evaluation Study [MobileHCI](./MobileHCI) ’05 pp77–82.
- Goillau, P., Woodward, V., Kelly, C. & Banks, G. (1998) Evaluation of virtual prototypes for air traffic control - the MACAW technique. In, M. Hanson (Ed.) Contemporary Ergonomics 1998.
- Good, N. S. & Krekelberg, A. (2003) Usability and Privacy: a study of KaZaA P2P file-sharing CHI 2003 Vol.5 no.1 pp137–144.
- Gray, W. & Salzman, M. (1998). Damaged merchandise? A review of experiments that compare usability evaluation methods, *Human-Computer Interaction vol.13 no.3*, 203–61.
- Gray, W.D. & Salzman, M.C. (1998) Repairing Damaged Merchandise: A rejoinder. Human-Computer Interaction vol.13 no.3 pp325–335.
- Hornbaek, K. & Frokjaer, E. (2005) Comparing Usability Problems and Redesign Proposal as Input to Practical Systems Development CHI 2005 391–400.
- Jeffries, R. Miller, J. R. Wharton, C. Uyeda, K. M. (1991) User Interface Evaluation in the Real World: A comparison of Four Techniques Conference on Human Factors in Computing Systems pp 119 – 124
- Lewis, C. Polson, P, Wharton, C. & Rieman, J. (1990) Testing a Walkthrough Methodology for Theory-Based Design of Walk-Up-and-Use Interfaces Chi ’90 Proceedings pp235–242.
- Mahatody, Thomas / Sagar, Mouldi / Kolski, Christophe (2010). State of the Art on the Cognitive Walkthrough Method, Its Variants and Evolutions, International Journal of Human-Computer Interaction, 2, 8 741–785.
- Rizzo, A., Marchigiani, E., & Andreadis, A. (1997). [The AVANTI project: prototyping and evaluation with a cognitive walkthrough based on the Norman's model of action](https://s3.amazonaws.com/academia.edu.documents/8651930/10.1.1.97.3355.pdf?response-content-disposition=inline%3B%20filename%3DThe_AVANTI_project_prototyping_and_evalu.pdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWOWYYGZ2Y53UL3A%2F20200212%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200212T093717Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=69b7f0d0d02ba3e92f25c7ee26ec60b83bb0f4697dd4f481fe2f154d43231c73). In Proceedings of the 2nd conference on Designing interactive systems: processes, practices, methods, and techniques (pp. 305-309).
- Rowley, David E., and Rhoades, David G (1992). The Cognitive Jogthrough: A Fast-Paced User Interface Evaluation Procedure. *Proceedings of CHI '92*, 389–395.
- [Sears, A.](./Andrew_Sears) (1998) The Effect of Task Description Detail on Evaluator Performance with Cognitive Walkthroughs CHI 1998 pp259–260.
- Spencer, R. (2000) [The Streamlined Cognitive Walkthrough Method, Working Around Social Constraints Encountered in a Software Development Company](https://facweb.cdm.depaul.edu/cmiller/eval/p353-spencer.pdf) CHI 2000 vol.2 issue 1 pp353–359.
- Wharton, C. Bradford, J. Jeffries, J. Franzke, M. Applying Cognitive Walkthroughs to more Complex User Interfaces: Experiences, Issues and Recommendations CHI ’92 pp381–388.

 

## External links

 
- [Cognitive Walkthrough](http://www.usabilitybok.org/cognitive-walkthrough)