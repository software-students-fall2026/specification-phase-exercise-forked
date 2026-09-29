# Specification Phase Exercise

A little exercise to get started with the specification phase of the software development lifecycle. In this exercise, your team specifies a set of improvements and new features for [The Slide Machine](https://theslidemachine.com) — see the [instructions](instructions.md) for detail, and the [background](background.md) for an introduction to the software product you are tasked with extending.

## Team members

[Jack Jiang](https://github.com/jack-k-jiang)
[Ruikun Xu](https://github.com/xuruikun)
[Shuo Cao](https://github.com/ShuoWu6529)
[Ronald Szeto](https://github.com/ronaldszeto)
[Eric Wu](https://github.com/ew2725)

## Review of the Current Application
Strength:
* The generation of the slides, text, images, etc. is fast. There is little delay in the words being spoken being outputted into slides. 
* Overall, program summarizes the spoken information quite well within its paragraph and bullet point heavy format. The speak aloud feature also fits the slide.

Weakness: 
* Text is sometimes repeated, whether from when the user repeats something or with the seed material. Doesn't support different colors for text or highlighting for sentences.
* The project title of a slides project changes to match whatever was discussed most recently, and it shifts easily when the lecturer goes off on a tangent. As a result, a project's title often does not describe the lecture as a whole. This makes it easy to mistake one project for another when trying to find a relevant deck or slide later.
* Correcting inaccurate content adds new slides rather than editing the original material. This inflates presentation length, forces tedious manual cleanup, and breaks the flow between the slides. Treating user feedback as an additive history log instead of an inline edit creates significant workflow friction.
* The software has poor math integration for the slides. For example, telling the slides to give an example of the sample space of flipping a coin would be omega equals to H and T inside brackets would result in words. Then after asking it to represent it mathematically, the program would write up LaTeX code without compiling it unless told to.
* The software doesn't support multi-language translation. This would be really helpful in a language class where someone can speak in two languages and the program would be able to output text in both languages to support translation.

Gap:
* A slide doesn't seem to be able to show more than one generated image, so side-by-side comparisons are not possible. Generating a table doesn't work either, and neither do diagrams. When asked to generate images side by side, the app produces only one image for the slide, as well as text saying that it is comparing. Lectures that compare two things (before and after, two examples, two historical figures) cannot be illustrated as such.
* There is a lack of presenter mode that Google Slides and Powerpoint has. More specifically, Google Slides and Powerpoint both offers presenter mode that allows you to view your speaker notes and timer in another tab.
* The software relies strictly on photos and bullet points and lacks support for other functionality like tables, shapes, charts, and diagrams. This makes the slides struggle with effectively displaying complex data, such as side-by-side comparisons. Without this ability it forces standard formatting tools and limits its use to lower-complexity and heavier text slides.

## Prior Art & Originality

We looked at the Future Work and Open Questions in the SPEC.md and closed/open PRs in the Slide Machine repository. We saw that there wasn’t any student accessibility support in the current implementation of Slide Machine, nor was it mentioned in Future Work. We do see that there is an option for the instructor to make a quiz from the slides, but not for the students to do so. We propose student-oriented accessibility features such as generating a study guide, flashcards, and a practice quiz organized by slides/topic. 

## Stakeholders

### Instructors
- Prof. J is a professor at NYU Tandon who teaches Electrical Engineering to graduate students. He first established that his goals are to transfer knowledge to students and help them develop critical thinking skills. He wants to help students gain skills for present topics involving problem-solving, as well as skills needed for the future that are centered more around research and developing new approaches. Additionally, Prof. J said that grades in one of the classes he teaches are very varied, and he hopes that all of his students will perform better on exams. 

  One of the problems and frustrations he mentioned was that attendance in his in-person classes was sometimes lacking. He said this could be attributed to the fact that graduate students are sometimes too busy to attend class because of responsibilities such as part-time jobs. Prof. J also said that graduate students often believe they are more capable of self-studying topics. He gives students practice questions in PDF format that are based on lecture notes. He does not give sample tests, such as previous exams, because he believes they would not be helpful for current exam questions. He said that he believes practice exams are useful but does not believe in reusing old exams. 
  
  Regarding his opinions on Slide Machine, while giving a mock lecture, he noted that he was speaking more to the AI than to the actual class and students. Slide Machine also had trouble generating equations and diagrams when he asked for them, and he often had to repeat himself before an equation or diagram was generated. He believes that Slide Machine would not be useful for his subject, graduate-level Electrical Engineering, because the material is too complex for the AI to reliably generate useful equations and diagrams. However, he said that the exit ticket form is a good idea for providing students with practice and is also a good way to gauge their understanding of the lecture.

## Product Vision Statement

See instructions. Delete this line and place your Product Vision Statement here — one sentence describing the improvements and new features your team is proposing for The Slide Machine.

## User Requirements

### Instructors
<!--As a [type of user], I want [some goal] so that [some reason].", where [type of user], [some goal] and [some reason] are replaced with appropriate values. Keep them small and written in non-technical language that the type of user would use.-->
1. As an instructor, I want to select which lectures are included in an exam study collection so students know which course material is relevant.
2. As an instructor, I want to see which topics students struggle with on practice quizzes so that I know what to review.
3. As an instructor, I want to read student comments attached to a specific slide so that I can understand why students are confused
4. As an instructor, I want to see what type of problem students report on a slide so that I know whether the issue is the explanation, example, image, or accuracy
5. As an instructor, I want to see how many students are using the study materials so that I can tell whether the resources are useful
6. 
7. 
8. 
9. 
10. 


### Students

## Activity Diagrams

See instructions. Delete this line and place images of your UML Activity diagrams here, each with the text of the user story it illustrates.

## Wireframes

See instructions. Delete this line and place your wireframe diagrams here, covering every new screen and every existing screen your proposal changes, for every type of user.

## Clickable Prototype

See instructions. Delete this line and place a publicly-accessible link to your clickable prototype here.

## Stakeholder Demo

See instructions. Delete this line and place a link to the deck The Slide Machine generated during your presentation here, after you have presented.

## Exit Ticket

See instructions. Delete this line and place a link to the exit-ticket quiz you generated from your demo deck and distributed to the class, along with a short note on what — if anything — you had to correct in the generated questions before publishing.
