# Escalating an Issue

![escalation](http://i.giphy.com/ToMjGpjpXMFPshSYGLm.gif)

Sometimes as a Technical Coach, you will encounter questions that are beyond your scope to answer. In these cases, you'll need to escalate the issue to the appropriate department at Flatiron.

## What kinds of issues should be reported?

### Non-lab Questions - refer the student to the correct department

- Questions about the course and admissions
  - How long does the course take?
  - What courses do you offer?
  - Do you offer scholarships?

Occasionally someone asks non-technical questions such as "How long does this course take to complete?", "Do you offer scholarships?", "Can you explain the job guarantee to me?", etc. If you feel like you know the answer, please **do not try and answer these questions**. Please refer the student to our admissions or student services department. 

- To contact admissions directly: `admissions@flatironschool.com`. 
- To contact student services: `studentservices@flatironschool.com`

### Personal/Behavioral Escalation - Through Escalation Form and Slack

Students get a little frustrated all the time - learning to do something new is challenging! If a student is very frustrated or disheartened, or is otherwise not interacting with TCs or other students in a healthy way, that student needs to be escalated.  

We use a Google form to escalate students to members of the full-time team. You can find that form [here](https://docs.google.com/forms/u/1/d/e/1FAIpQLSdIP65BStJfWBgG0dZO5dhQb3Yqs3TwN29xjk5GUOyyReI5QQ/viewform). For extreme or urgent cases, you should also send a DM to your Faculty Manager. Paste the message that concerned you and a link to the question so we can easily get in touch and review. 

If in doubt, err on the side of escalating a student, rather than potentially letting the issue continue, unaddressed. If necessary, we'll refine the instructions, but we'd rather get too many false positives than fail to help a student who's having a hard time.

When using the escalation form, it is important that you are objective, detailed, and specific in your explanation of what occurred. A nice general rule of thumb is to describe what happened, give specific details (quote the student if at all possible!), and elaborate on why the interaction concerned you.

Here is an example:

>This student started a question due to the IDE constantly reconnecting during the Sinatra Playlister lab. He spoke with [TC name] first, who submitted a ticket for him, then [second TC] who screen shared with him to get him going on his local environment. This resulted in some issues with the bundler gem.

>The student repeatedly made negative remarks as I tried to help him. We tried running his code in shotgun and got an error. I suggested a change to his code and then recommended to try it in shotgun again, to which he responded “woooo nothing's gonna change let's check shotgun...” Many of his responses had a similar tone.

>He brought up the course several times like “I just don’t know about this course... I spent hours on this, I don’t want to spend time fixing every single lab” - comments along those lines. Didn’t necessarily threaten to quit but is clearly unhappy with the course right now.

>At the very end, he did thank me for spending so much time debugging with him. He didn’t say anything inappropriate directly to me, but it was a super uncomfortable tone the entire time.

We see that there is a description of the student's overall demeanor and why he might be frustrated, the steps that were taken to address the issue, and specific details and quotes from the student to help illustrate the student's feelings and behavior, as well as why the TC was concerned.

### Struggling Student / Major Conceptual Issues - Through Escalation Form

If a paying student is struggling with the curriculum, we want to get them the appropriate help as soon as possible. At this point, you may have already tried to explain a concept to them, and/or documented it on their admin profile. If not, check their admin profile and see if there are other comments. If it seems there is a pattern developing based on the notes in their admin profile (e.g. there are several other notes by other TCs / staff members about the student struggling with concepts), please escalate the student via the escalation form. Once that student is escalated, we can make sure the student gets the appropriate support from their Section Lead or Cohort Lead.

Here is an example of a reasonable escalation:

> [Student] opened a question on the Rails Amusement Park lab and is approaching their portfolio project, but seems to still be struggling with routing in Rails, as well as with using pry to debug their controllers. The notes on their admin profile report similar conceptual issues, and the student seems to have had issues with routing in the Sinatra section as well. While on my screen share with [student], they seemed to generally be unable to answer my questions about routing and route helpers, and seemed to have a hard time parsing error messages in general. They repeatedly responded to me with "I don't know" or "what should I do next". We looked at the Rails routing documentation together, but I had to do a lot of handholding. I shared several resources with the student as well, but I think they're going to need more direct support before starting their portfolio project. Otherwise, I'm worried that they're really going to struggle on their final project.

### Abuse of Pair with a TC or Lack of Trying - Through Escalation Form 
Pair with a Coach exists to help students learn to debug effectively as they work their way through labs and lessons in the curriculum - it's why we're here! However, it's on students to debug independently as much as possible. While we can offer suggestions and strategies when students get stuck, we should also take note of when a particular student seems to be relying on us for answers rather than putting an appropriate amount of effort into their their lab work. Abuse of Pair with A Coach might look like any of the following:

- Asking for answers directly, or asking to be given the solution code
- Repeatedly demanding screen shares and being reluctant to share information over chat
- Hanging out in PWATC for most of the day, or for seemingly an entire lab
- Opening a new question within a few minutes of resolving the previous question
- Being unwilling to troubleshoot, try things independently, or identify possible strategies for moving forward (e.g. a student frequently responds with "I don't know", or "what is wrong with this code") or something similar.

A good general rule of thumb is to tell students to work independently for 15-20 minutes before opening a new question. However, if you find that a student is overly reliant on PWATC or resistant to the teaching strategies we use, you should escalate that student via the escalation form so that their expectations of the program, and of PWATC, can be reset. 

Here is an example of a reasonable escalation:

> [Student] seems unwilling to troubleshoot his errors or put much effort in at all, instead pasting all of his code and errors at once and saying things like "how do i make it pass" or "how do I fix this". Sometimes he will resolve his question and open a new one immediately if he is not getting responses quickly enough. It seems that he is not making much of an effort, even though he is in the paid program. Additionally, he is not very communicative in screen shares. Most of my questions were met with silence. Even when we successfully completed a lab, [student] was completely silent — no reaction whatsoever, not even a "thanks for your help."

### All other issues - Through Jira

In other cases, technical issues need to be escalated to our development team. In the next section, we'll cover how to correctly escalate an issue by submitting a ticket on Jira. The table below briefly outlines the types of issues that should be escalated:

| Issue | Description |
| --- | --- |
| IDE |  Any issues related to the Learn IDE. For example, the user is getting an error when installing the IDE, or the IDE won't load |
| Chat |  Issues related to Ask A Question, DM, or Lobby features in Learn, e.g. chat is totally empty, or notifications not showing up for chat|
| UI |  Buttons not working, problems with the site, pages 500ing |
| Account | Billing, feature access, Github name change |
| Lights | Lights not flipping |
| Project | Issues related to an assessment / portfolio project (this would likely need to be submitted by a member of the full-time team, as technical coaches do not resolve issues related to assessments) |
| VirtualBox | Issues related to installing or using VirtualBox |
| Learn Gem | e.g. User is getting non-test errors when running tests or submitting lessons |
| Github |  e.g. Github account not connecting to Learn.co |
| Blog | Student's Learn.co blog-related issues - can't save blog posts, issues switching blog type, etc.

## Resources
[Student Escalation Form](https://docs.google.com/forms/d/e/1FAIpQLSdIP65BStJfWBgG0dZO5dhQb3Yqs3TwN29xjk5GUOyyReI5QQ/viewform)
