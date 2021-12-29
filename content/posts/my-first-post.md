+++ 
draft = false
date = 2021-12-29T14:21:49+08:00
title = "Minimum Best Practices For Data Scientists"
description = ""
slug = ""
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++
<!-----
NEW: Check the "Suppress top comment" option to remove this info from the output.

Conversion time: 0.699 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β31
* Tue Dec 28 2021 22:29:15 GMT-0800 (PST)
* Source doc: Data Scientist Skills

ERROR:
undefined internal link to this URL: "#heading=h.oc1gupq12efw".link text: rabbit hole
?Did you generate a TOC?

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 1; WARNINGs: 0; ALERTS: 1.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



# Minimum Best Practices For Data Scientists

This is part 3 in a series to give some guidance on milestones/goals/expectations or really just “best practices” at various levels in the data science career. For guidance on getting to the pre-Data Scientist level look [here](https://medium.com/@paulbrenner_1107/it-is-time-to-share-some-guidance-for-analysts-that-want-to-become-junior-data-scientist-2fc50f8331b). To learn about moving up from Data Scientist to Senior Data scientist you want this [link](https://medium.com/@paulbrenner_1107/data-scientist-no-senior-data-scientist-lets-talk-about-how-that-happens-87f12c06f573).


### What I’m actually looking for in a Data Scientist - WIP

_This section focuses on what I, Paul Brenner - Head of DS at PlaceIQ, personally want to see in a working Data Scientist. It leaves out many “table stakes” included in other sections. If you work at PlaceIQ then it is a good way to understand what I’m looking for. If you don’t, then perhaps it is worth reading through, evaluating how it compares to your current situation/goals, and then forming an opinion on why you agree or disagree with each point._



1. Understand and be able to explain **WHY**
    1. Why are you even doing this project?
    2. Why are you using the tools you are using (scala? Spark? A nifty ML package? etc)?
    3. Why are you paid so much?
        1. In summary, there are multiple skills here: Understand the value of your work, have some awareness of how the company works, understand the value of skills you have or don’t have, be able to persuade the people up the chain when you have a strong case, and finally bonus points if you are starting to learn how to manage your own career. But also there is a whole tangent here if you want to go down that 

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: undefined internal link (link text: "rabbit hole"). Did you generate a TOC? </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

[rabbit hole](#heading=h.oc1gupq12efw).
2. “Simpler is better” Believe this, don’t just pretend to agree with it, but really deeply believe it even when no one else is looking
    4. Have experience reading code that was too smart for its own good, and appreciate why dumb, readable, and easily changed code is better than flashy code. Ideally have written that code yourself, then come back to it later and have been like “what the… what is this, why?”
    5. See a blog post or talk or random anecdote or company description where ML was used and think “this is not a good use case for ML, they should have done something simpler”
    6. Accept that all that time you spent learning the theory of model select and how SVM works was probably educational, but won’t actually be relevant: if you need to use ML you should probably start by tossing automl or an xgboost varietal at the problem, checking the results, then only digging in if the results/performance don’t meet requirements
3. Leave everything better than you found it
    7. When you learn something new share it
    8. When you get results you should…
        2. Document them for a technical audience (put them on a ticket perhaps?)
        3. Reflect on “who needs to know about this”
            1. If the answer is no one then, what the, why did you do this project?
            2. If the answer is “just the people on the ticket” then stop and think “really? There is no one else who I can show these nice results off to?”
            3. If there is someone else, identify the best way to share with that audience. Is it a slack message? Email? A meeting? A few slides?
            4. Ok now share appropriately
4. Every problem you find is your problem
    9. Job #1 is to do good work on whatever project you are supposed to be working on
    10. Job #2 is to start looking for areas of opportunity. That means if you stumble across a problem with something, your response should be “nice! I found something that might need fixing and maybe that fixing could make the company better”. 
5. Make mistakes and really believe that it's fine to make mistakes
    11. Your job is to move quickly, write code that may only run once, and apply the 80/20 rule. Embrace that you aren’t a software engineer who needs to write rock solid code that needs to meet an uptime requirement with five nines. YOU WILL MAKE MISTAKES. And that is fine.
    12. Everyone else on your team makes mistakes too. Do you believe that? Please do.
    13. The real job is NOT to NOT make mistakes. It is to catch most of your mistakes before someone else does.
    14. The real job is also not to catch all of your mistakes before someone else does… nope, other people will catch your mistakes sometimes and you will feel embarrassed and like the world must be about to end. When you make a mistake you need to own it, realize that it’s fine to make mistakes, and help clean up the mess.
    15. Failure modes here would be 
        4. Catch a mistake after it is out in the world and try to cover it up
        5. Get defensive if someone else catches your mistake
        6. Get distraught and beat yourself up if you make a mistake and it has impact
        7. Fail to appreciate that mistakes are a job expectation
        8. Go overboard and embrace this philosophy too much and just not even try to avoid mistakes… oops, that went too far, don’t do that either, find glorious balance
    16. All that said, the real solution to mistakes is to build systems/procedures that aren’t vulnerable to human error when possible. If a mistake causes a major business problem, then that means it is time to find a way to make it so that such a mistake can’t cause as much damage in the future
6. Take care of yourself 
    17. Start building some skills to defend against burn out
    18. Start helping your manager help you. Speak up when you need something


### Normal Expectations For Data Scientists - WIP

_This section attempts to include less of my very specific opinion and cover expectations that may be more generally shared among DS managers. As above, you don’t need to agree with everything, but it is worth having some thoughts about why you agree or disagree._



1. Project ownership - Given a clear and detailed description of prioritized project requirements, a DS should be able to…
    1. Produce results within the estimated timeline and realize when that timeline needs to change
    2. Ask questions to ensure most time is spent on the correct work
    3. Raise issues, slow downs, blockers, or findings that may change the project plan promptly
    4. Work for 2-3 days completely independently and productively, understanding how to pause on anything that requires input
    5. Identify and document new problems whether or not they are related to the current project
    6. Package results/code so that others can understand the project’s outcome and extend the work when needed
2. Learning independence - A DS should be able to… 
    7. Independently survey existing available tools (e.g. packages, language, algorithm, statistical method, ML, etc) and propose an approach to quickly evaluate and find the best option for a project
    8. Rapidly learn the basics of any new tool enough for a quick POC
    9. Get to a moderate depth of understanding of any new tool or language when necessary across the span of a longer/more in depth project (1-3 months)
    10. Summarize and share findings about 
    11. Understand why this section does not include a list of tools/algorithms/languages/textbooks, but instead talks about how quickly a DS can learn those things
3. Communication - A DS should…
    12. Start to have an opinion on topics specific to recent projects and share those opinions within the team
    13. Confidently respond to questions about his/her work from anyone in the company
    14. Proactively share findings with the team and stakeholders
    15. Start discussions in team meetings by raising interesting findings or topics
    16. Talk to stakeholders, know when to get their feedback, know when it is important to share your findings, and know how to share them effectively


### Specific “Checklist” To Help Get That Data Scientist Title/Job

_Now that I’ve forced you through two sections on expectations for a Data Scientist, if you still think that is a job you want, then here is a list of specific accomplishments that would be good to have under your belt to get that title._

Important Disclaimer:

Here is basically a checklist for someone who does not currently have the title of DS that wants to get that title. This sort of thing is dangerous. It isn’t a promise that if you do all of these things you will get a promotion/job. It also isn’t a blocker. If you haven’t checked off every “requirement” but are just crushing it on a few of the others, that could be plenty. In fact, being a data scientist requires enough business acumen that I’m just going to put that on the list “understand that you can check all these boxes and still not get the title/job and really get why that is… but also that the reverse is true”  



1. Technical Problem Solving: Provide “proof” that you have problem solving experience and that your abilities are worth proper evaluation. Some examples that could count as proof, whether fair or not, are below. More is always better, but the requirement here is at least a-i, a-ii, or b-ii.
    1. In School:
        1. A PhD that included beating your head against a hard problem for multiple years and the ability to articulate why it was so hard and what your role was in solving that problem. Note that there are plenty of people who make it through a PhD and don’t acquire the problem solving skills needed for data science, so it isn’t a sure thing. But there is a decent correlation between those successful at finishing a PhD and those who have this problem solving box checked.
        2. A Masters that includes some really above and beyond extra projects or lab work. Masters programs tend to focus a higher percentage of time on coursework/homework/class projects which are just too guided/not open-ended enough to really check this box. There is nothing wrong with that! There are plenty of people who learned valuable skills from their masters program. But you should just know that if your masters really involved some outstanding demonstration of problem solving then you need to make that clear.
    2. Technical project at work/home:
        3. It doesn’t actually matter if you just create your own home project and see it through to the end (impressive because it also shows internal motivation) or it is a work project assigned to you (impressive because of working inside the complexity of a company).
        4. Two (or more) projects that may have come with a high level problem statement / requirements but required your own independent work/thought on the following 4 steps in the problem solving process:
            1. Problem Identification: Figure out the actual sub problems that needed to be solved to complete the project
            2. Defining unknowns: Identify what questions need to be answered/data collected/experiments run to get the data that will inform which solutions should be attempted
            3. Solution Brainstorming: Propose multiple solutions to the problem, prioritize which ones to try first
            4. Solution Evaluation: Identify the best solution based on an appropriate set of criteria
2. Non-DS problem solving anywhere in life:
    3. Problem solving is not just looking at data and writing code. Have an example where you can talk through the problem solving process in problems you encountered with…
        5. People
        6. Non-people (physical objects, pets, I don’t know, get creative)
        7. Logistics (like planning a trip, being lost and getting unlost, or making some process better)
    4. Ideally, the less fancy the better here. Your goal is to make it clear that problem solving is so deep in your blood that you can’t help but do it all the time and you can articulate how you do it.
3. Interpreting Results: You should have a lot of experience under your belt interpreting results, the numbers here are rough guidelines (completely made up?), but if you hit these guidelines you should naturally be able to convince someone that you have great experience interpreting results.
    5. 50+ times that you have looked at data (counts? A chart? Rows in a table?) and made a decision. No you shouldn’t remember all of them because 50 is a lot. But basically this should be something you have done a lot. 50 is a completely made up number here to represent “a lot”. This should be really easy to hit
    6. 3 examples of the above that you remember because there was some really cool conclusion/decision/next step that came out of looking at data. Be able to tell the story here. This should be quite easy to hit.
    7. 1 example of the above where you shared your data with someone else “smart” (Your team? A well informed friend? Your boss if you are lucky and have a smart boss? What I mean is not just your dog) and YOU had the great aha discovery moment to figure something out from the data before they did. PLUS you explained it to them and they said “good job, you must be some sort of data scientist” (they didn’t actually need to say this, you just need to have explained it and they understood and agreed). This may be a hard one for so many reasons: maybe you are too humble to take credit, maybe an outside opinion/fresh set of eyes is just what you needed the times you shared… or MAYBE you don’t share your results enough which is its own problem. Pretty cool how this requirement forces you to share your results a lot though.
4. Coding ability: Provide proof that you have a good enough handle on the basics of coding that you can solve problems using your coding language of choice.
    8. Finish some sort of coding class/bootcamp/book/web tutorial/whatever that covers coding fundamentals. That should mean familiarity with everything on [this page](https://en.wikiversity.org/wiki/Programming_Fundamentals). I don’t care how you do it. But if you show up being a wiz with dataframes and sklearn but don’t know what a for loop is that would be annoying (but not necessarily a deal breaker!)
    9. Solve 10 “easy” coding problems (like the easiest problems on HackerRank) using Variables, Functions, Conditions, Loops, Arrays, and Strings. OR if you are pretty confident you can do this and don’t want to spend the time practicing just be able to solve such a problem if someone were to test you for some reason.
    10. Two (or more) projects that require the use of dataframes and any imported package. This one should honestly sound like a preposterously low bar.
5. Learning ability: Provide proof that you can learn basically anything and quickly
    11. 2 examples of learning to use a new package/tool for a project when it was appropriate for the problem at hand
    12. 1 example of learning to use a new algorithm/statistical concept/methodology/etc for a project
    13. 1 example of something you learned recently related to data science that you can explain and convince me is actually pretty cool/useful
    14. 1 example of something you have learned/know that is really just too complicated to explain in depth in 30 minutes
    15. Nice to have: 1 example of learning at least the basics of a programming language beyond your first. You may be surprised how fast you can get the hang of javascript or R or whatever basics (1 day?) and then you can always cite that as an example.
6. Communication: Provide proof that you value communication and can do it. Note that the ordering of these and the number of examples required implies something about how each one is valued. By this point in life you certainly should have a good example of presenting your results in a structured format, but admitting you don’t know the answer to a question during that presentation may still be scary.
    16. 3 examples answering a question from someone you respect with “I don’t know”
    17. 3 examples telling someone you respect that you don’t know/don’t understand something even though they didn’t ask you a question and you could have just pretended you understood.
    18. 2 examples learning about a problem someone else has and helping them with it
    19. 2 examples sharing a problem you are in the middle of and having someone else help you with it
    20. 1 example of a really great short email you have written that really got the point across in a concise way
    21. Sharing something you learned/results you collected/a thing you created/ a project you finished…
        8. 1 good examples successfully sharing in **an ad hoc format** (just talking and waving your hands around, maybe pulling up a chart on the fly, etc)
        9. 1 good example successfully sharing in **a structured format** (slides? A document? etc)
7. Understand that you can check all these boxes and still not get the title/job and really get why that is… but also that the reverse is true


## Data Scientist Pay Tangent

_This is just a tangent. Do what you will with it. _



1. Don’t think you aren’t paid that much? You may have already failed this one. Think about it again from the perspective of the CFO. Or imagine you had founded the company and were responsible for making sure everyone gets a paycheck every pay cycle. 
2. Thought about that and still think you are underpaid? Ok, fine, that was cost-based pricing and sure that may not be appropriate here. How about value-based pricing: Can you put a dollar amount on the value of your work? An exact number is probably pretty hard if you don’t bill hourly, but do you have any idea how your work for the past year translates to value for the company?
3. Next up, how much are other people with your skill set getting paid, whether at your company or other comparable companies? Is it more? Are those people doing jobs you would actually want to do or does your company have some sort of perks beyond just money that you value (more interesting work? You don’t hate your life?). What I’m saying is be sure to also consider “total comp” and not just salary.
4. Ok, if you’ve made it this far, and you are confident that your company has absolutely no problem making payroll, and you know the value your work provides (like money value, not just it’s neat value) is a big multiple of your pay, and other people with the same skills make more… do you see the problem yet?
5. What I was getting at in 4 is that if you have all that information and think you are underpaid you should either have plenty to make a case for a raise, be job hunting, or appreciate what it is about your job that keeps you there even though you don’t like the pay