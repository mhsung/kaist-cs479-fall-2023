# CS492(A): Machine Learning for 3D Data

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Spring 2022
</b></h3>


## Project Review Guidelines

<!-- (Last updated: May 29, 2022. Subject to change.) -->

^^Review Deadline^^: ==December 8 (Fri), 23:59 KST==  
^^Rebuttal Deadline^^: ==December 13 (Wed), 23:59 KST==  
^^Where to submit^^: ==OpenReview==   
[https://openreview.net/group?id=kaist.ac.kr/KAIST/Fall2023/CS479](https://openreview.net/group?id=kaist.ac.kr/KAIST/Fall2023/CS479){:target="_blank"}


### Review Process

- You will be asked to review *two* projects, and each project will be reviewed by at least *four* peer reviewers and also *two* TAs.
- The review will be *single-blind* and will be performed in **OpenReview** (but both the submissions and reviews will NOT be open to the public). 
- ==Reviews can be **rejected** based on the assessment of the review quality, and rejected reviews will be penalized in the project evaluation &mdash; see [Penalty](#penalty).==


### Infeasible Experiments

In the report, you can argue the **infeasibility** of experiments that are expected to be shown in the results.
For example,

- Some experiments in the original work (Performance Improvement Track) may not be reproducible if the experiments require more than two GPUs *(note that only two GPUs are provided to each team)* or some important details about the experiments are missing.
- An exact comparison with the original work (Performance Improvement Track) or previous work (Novel Problem Solving Track) may not be possible when the data used in the experiment is not released.

For such infeasible experiments, the authors must consider **substituting** them with similar but feasible experiments (or, also argue why it is even not possible to substitute them).
For example,

- If an experiment is computationally infeasible, try to simplify the experiment (use a smaller dataset, use a simplified neural network, reduce the batch size, etc).
- If data for replication is not provided, consider using the other similar data.
- If some experiment details for replication are not provided, use any common parameters or approaches.

As a **reviewer**, you need to judge whether the argument about infeasibility is valid or not and whether the authors tried to substitute the infeasible experiments.

For the experiments considered infeasible, do not take them into account in the evaluation.


### Review Questions

#### ^^This is a tentative plan and is subject to change.^^

==Total score range: [-8 ~ +8]==


#### Note
- 'Outstanding' is outstanding. Consider giving this score when you think this team seems the best in the class.  
- 'Poor' is poor. Consider giving this score when you think this team is REALLY bad.


#### Summary
Summarize the project ideas in ~5 sentences. Describe the goal of the project, the achievements, and strengths and weaknesses compared with the other projects.


#### Plagiarism
If you find any suspected plagiarism, please describe it here.


#### Writing
- **[+2] Outstanding.** Clearly described motivation, method or implementation details, and experimental results. Very well organized the paper, and very easy to follow the paper. Includes sufficient illustrations for the methods or implementation details, and figures and tables for the experimental results. (Almost) no flaw. 
- **[+1] Great.**  Well organized the paper, and clearly described most parts. But it is a bit difficult to follow, or there are a few minor flaws.
- **[ 0] Moderate. **  Some descriptions are not clear to understand. Some details in the method, implementation details, or experimental setup are missing. Technically adequate, but some technical details are incorrect.
- **[-1] Needs to be improved.**  Some required sections or important details are missing. Too many flaws and mistakes in the writing. Fatal mistakes in the technical details.
- **[-2] Poor.**  Did not complete the writing. Most parts are missing.

Justify your rating. Be specific.


#### [Novel Problem Solving Track] Novelty

==Check out which parts the authors implemented and not implemented but borrowed the code from the other places. Only the parts the authors implemented need to be considered to evaluate the difficulty.==

- **[+2]** Very novel and interesting ideas that need to be published in an academic paper.
- **[+1]** Novel and interesting ideas.
- **[ 0]** Worthy contributions with some novel (but small) ideas. 
- **[-1]** Trivial ideas.
- **[-2]** Does not advance the state of knowledge , or closely duplicates existing work.

Justify your rating. Be specific.


#### [Performance Improvement Track] Implementation Difficulty

==Check out which parts the authors implemented and not implemented but borrowed the code from the other places. Only the parts the authors implemented need to be considered to evaluate the difficulty.==

- **[+2]** Very difficult. Requires extraordinary efforts and/or skills.
- **[+1]** More challenging than our project.
- **[ 0]** Challenging as much as our project.
- **[-1]** Easier than our project.
- **[-2]** Very easy.

Justify your rating. Be specific.


#### [Novel Problem Solving Track] Experimental Results

==Refer to the guidelines about [Infeasible Experiments](#infeasible-experiments) before answering this question.==

- **[+4] Outstanding.** Showed clear outperformance than previous work in comprehensive experimental analyses. Showed very interesting results in a novel problem.  
- **[+3]** (Between +2 and +4)  
- **[+2] Great.**  Showed outperformance in some experiments. Showed promising results in a novel problem.  
- **[+1]** (Between 0 and +2)  
- **[ 0] Moderate.** No outperformance or interesting results for now, but perhaps they would get promising results if they spend more time.  
- **[-1]** (Between -2 and 0)  
- **[-2] Not good.** The results do not look promising. The performance is clearly worse than previous work, or there is no improvement in incremental work.  
- **[-3]** (Between -4 and 2)  
- **[-4] Poor.** Did not complete the implementation, or did not show any meaningful results.

Justify your rating. Be specific.


#### [Performance Improvement Track] Experimental Results

==Refer to the guidelines about [Infeasible Experiments](#infeasible-experiments) before answering this question.==

- **[+4] Outstanding. **The results are comparable to or even better than those of the paper. Provided more experimental results than the paper. Improved the method and showed better performance.  
- **[+3]** (Between +2 and +4)  
- **[+2] Great. **Reproduced (almost) all experimental results in the paper except for some infeasible experiments. The results are comparable to or even slightly better than those of the paper.  
- **[+1]** (Between 0 and +2)  
- **[ 0] Moderate.** Reproduced most of the major experimental results. The results are comparable to those of the paper. Missed a few less important experiments.  
- **[-1]** (Between -2 and 0)  
- **[-2] Not good.** Missed many experimental results. The results are clearly worse. The comparison is not fair.  
- **[-3]** (Between -4 and 2)  
- **[-4] Poor.** Did not complete the implementation, or did not reproduce the results at all. Showed very bad results.  

Justify your rating. Be specific.


#### Feedback
Provide questions or comments. Please be constructive, respectful, and detailed in your comments.


### Rebuttal and Final Decision Process

- After the review deadline, the authors will have an opportunity to rebut the review comments in OpenReview.
- ==All the reviewers are responsible to read the rebuttal and check how the authors addressed the reviewers' comments.==
- Reviewers can adjust the review comments and scores after the rebuttal.
- The review scores will NOT be averaged. There will be a discussion among the reviewers on Discord, and the final score will be decided in the discussion.


### Penalty
- **Unsubmitted or rejected review** (for each): ==20% penalty== in the project evaluation.


<br />