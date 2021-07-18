---
layout: post
title: How to write rebuttals
subtitle: Rebuttal을 작성하는 방법
gh-repo: kthyeon/kthyeon.github.io
gh-badge: [follow]
tags: [Rebuttals, taehyeon Kim, research, paper]
cover-img: /assets/img/how_to_write_rebuttal.png
comments: true
---
[How we write rebuttals By Devi Parikh, Dhruv Batra, Stefan Lee medium.com](https://medium.com/@deviparikh/how-we-write-rebuttals-dc84742fece1)

\*상기 포스트를 기반으로 내용을 재정리 하였음.

## **What is Rebuttal & its Goal**

AI conference (e.g., CVPR, ECCV, ICCV, NeurIPS, ICLR, EMNLP, IJCAI, AAAI etc...)으로 논문을 제출(submission)하면 reviewer들로 부터 중간평가를 받는 rebuttal process를 겪습니다. 이것은 Reviewer와 Area Chair (RACs)들이 제출된 논문을 쉽게 따라오게 가이드하는 역할을 하기 위함입니다. 흔히 Area chair를 놓치기 쉬운데, 이것을 신중히 고려해서 잘 작성해야합니다.

## **Why Rebuttal?**

**To clarify and convince. "과학은 심의적인 과정이며, 반박(rebuttal)은 그 과정 중 하나이다"라고 합니다.** CVPR에서는 Good Reviewer와 관련해서 Session을 열기도 했습니다. \[[Link](https://www.cc.gatech.edu/~parikh/citizenofcvpr/)\] 

Rebuttal은 크게 2종류의 청자를 대상으로 합니다. 리뷰어들의 직접적인 질문들에 대해서 대답하는 것도 중요하지만, 그보다 상위의 AC들에게 적혀진 review들을 재정리하여서 가이드도 하는 것이 굉장히 중요합니다.

1.  **The reviewers,** who have read your paper (to varying degrees), but may have forgotten some of the details or didn’t understand them in the first place.
2.  **The AC,** who is likely even less familiar with your work, and a good guiding principle is to assume that all they will read is the set of reviews and the rebuttal.

그렇다면, 위의 두 청자들을 위한 rebuttal의 작성은 어떻게 해야할까요? CVPR의 세션에서는 아래의 목적으로 리부탈이 이루어져야한다고 말합니다.

1.  **For the reviewers**: clarify doubts, answer questions, correct misunderstandings, push back on mischaracterizations, and make a good-faith effort to incorporate feedback and improve your work.
2.  **For the AC:** convince them that you have made a good-faith effort, present a representative summary of the reviews, help them understand if the reviewer concerns were addressed, call out bad-faith reviewing, and ultimately,help them make a decision.

**결국 최종적으로 결정을 내리는 사람들의 판단을 잘 설득해야한다고 말합니다. 따라서, 상대방의 마음을 바꾸게 하는 것보다 판단을 설득하는 것이 굉장히 중요한 것입니다.**

They provide concrete recommendations below, but a good short-hand is the following — would a neutral third-party be able to tell if the reviewer concerns were addressedpurely based on your rebuttal(without reading the paper or the reviews again)?

## **Recommendation Process**

1.  **Itemize reviewer comments.** We use a [handy spreadsheet](https://docs.google.com/spreadsheets/d/1-FqA8RfQY5XwycJLqjVLLM0QIVNwzelGJqpWSInCen0/edit?usp=sharing) to organize individual comments/questions/concerns raised by each reviewer. Laying everything out in the same place helps identify common concerns and keeps us from missing anything accidentally. Do this ASAP to identify any necessary new experiments (if the venue allows it) or analysis early.
2.  **Brain dump possible responses.** The sheet has a column for each author to reply to each reviewer comment. Dump your thoughts here in rough text without regard for style or length. Being convincing and concise is a subtractive process.
3.  **Write a draft rebuttal.** Turn your consensus in the sheet into concrete responses in a rebuttal draft. Write concisely but don’t worry about space. Cover every point and trim / prioritize them later.
4.  **Review and revise.** Reread the initial reviews and your sheet to make sure everything has been addressed. Prioritize major concerns and start working towards meeting space limitations.

## **Tips** - 18 Rules

1\. **Start Positive**: 받은 리부탈들을 기반으로 긍정적인 것들을 먼저 열거해라. RAC들이 잊지 않도록.

2\. **Order matters.** Start with the biggest concerns that you have good answers for and work your way to less clear-cut responses and minor points.

3\. **Let reviewers speak for themselves, then respond directly.** Quote the core of the reviewer’s question or concern concisely and completely. Then before saying anything else, respond to it directly. And then give details, describe context, or explain your position.

4\. **Be conversational.** Notice the conversational nature of the example responses above. It makes it easier for RACs to follow, and the responses are less likely to be perceived as being combative.

5\. **Respond to the intent of the questions.** Don’t feel trapped to only discuss the quoted concern — also address the intent of the comment. For example, “Why didn’t you evaluate on GLORP3?” may generally be calling your experiments into question. Answer, but then point out that you’ve already evaluated on X,Y, and Z which should be sufficient! Note that it is useful for other RACs to be reminded of your extensive experimental evaluation. A first glance at a reviewer comment suggesting otherwise could leave a false impression.

6\. **Don’t be afraid of emphasis**. “Row 2 in Table 4 showsexactlythat.” “We do NOT need a human-in-the-loop at test time.” Notice that many of the responses above are not just direct, but also have emphasis (in tone if not formatting of text).

7\. **Feel free to set the stage.** If it seems like all reviewers missed a central point, a concise, crisp recap of the main point could help.

8\. **Keep things self-contained.** Assume RACs don’t remember much about your paper and that they likely won’t read it again in detail. Re-introduce any acronyms, remind them of relevant details of an experimental setup. Notice that all the responses above likely make sense to you even though you may be unfamiliar with the papers (and in some cases the names and details are made up).

9\. **But get credit for details you already included.** That said, if something a reviewer asked for was already in the paper, say so. Give them line/Table/Figure numbers, and then restate it in the rebuttal. The references back to the main paper are to establish credibility with all RACs that the paper was not lacking important details. (They are not necessarily to have RACs go back and look at the paper.)

10\. **Color-code reviewers.** Notice above the trick to color-code reviewers. Make it as easy as possible for reviewers to spot responses that are relevant to them — even when things are merged or not in reviewer order.

11\. **Consolidate common concerns.** Save space by responding to multiple reviewers at once if they share related concerns.

12\. **Stats speak louder than words.** Rather than argue with RACs, give them data/stats to back your claim up. These can be statistics/analysis of your data or results. Or the results of additional experiments you run to respond to their concern (if allowed by the venue). Every time you find yourself having a different opinion than the reviewer, ask if you can establish that with data. You can always provide the intuitive arguments after you’ve settled the issue with data.

13\. **Don’t promise, do.** Instead of saying “We will discuss Singh et al. in the paper.”, provide a discussion in the rebuttal. Instead of saying “We will explain what D\_{RT} stands for in the paper”, explain what it stands for in the rebuttal. And then also add that you will add it to the paper. It makes it significantly easier for RACs to trust that you will make the promised changes.

14\. **Be receptive and reasonable.** Most RACs will appreciate it. Plus, it is just the better thing to do — these are your colleagues! :)

15\. **Be transparent.** Reviewers hinted at an additional experiment but the venue doesn’t allow it? Say so. They asked about intuitions about a trend but you don’t have any? Say that you’ve thought about it but don’t have any good ideas, and will continue to investigate it. Don’t have enough GPUs to run the experiment they asked for? Say so.


16\. **Shine a spotlight on reviewers acting in bad-faith.** In some circumstances, a reviewer may not be adhering to reviewing best practices or may not have taken the reviewing role seriously. It can be important to make sure the other RACs realize this and appropriately discount their review. Pointing out unreasonable or unsubstantiated comments and referencing other reviewers that disagree can help. This can also include confidential comments to the AC (where applicable).


17\. **Acknowledge reviewer efforts.** On the other hand, if a reviewer goes above and beyond to be constructive, thank them for it. Typo list? Thank you. Pointers to relevant work? Thank you. Detailed musings about future work? Thank you. Add at least a short blurb acknowledging these things!

18\. **Don’t forget the humans on the other end.** Keep in mind that this is not just a scientific but a sociopolitical interaction with other humans :) So decide whether you’d like to be argumentative and risk your reviewer taking a strong stand against the paper, or if you’d like to work towards a common ground. Finding points where you do agree with the reviewer and acknowledging them can help with the latter.


긴 글 읽어주셔서 감사합니다.