# CSE290S-Winter21: 
## Resilience in Giant-scale Systems
| key | value | 
|-----|-------|
|When: | MWF 1:20 - 2:25PM |
|Where: | my zoom room |
|Who: | Peter Alvaro |
|Office hours: | TBD |
|Prerequisites: | A background in systems, an interest in theory, and a sincere curiosity about how stuff works and breaks |
|Readings: | [Readings](https://docs.google.com/spreadsheets/d/1MAhmHa4JQfOIXcwKv63uL9WlO1NBzfosml8oAEb3qJo/)|

# Description

This graduate reading seminar will explore cutting-edge systems research on large-scale distributed systems, with a particular focus
on fault tolerance (broadly defined).

Due to fundamental uncertainty in their executions arising from asynchronous communication and partial failure, distributed systems present unique challenges to programmers and users.  Moreover, distributed systems are increasingly ubiquitous: nearly all non-trivial systems are now physically distributed.  It is no longer possible to relegate responsibility for managing the complexity of distributed systems to a group of expert library or infrastructure writers: all programmers must now be distributed programmers. This is both a crisis and an opportunity.

Large-scale web services such as Google, Facebook, Twitter, Amazon, Netflix, and many others require the cooperation of many thousands
of physical computers, any of which may fail or misbehave at any time, to support their user-facing services.  How do these sites
continue to run?  Exactly how and why do they (rarely) fail to run?  How does the state of the art in resiliency for these massive-scale
systems look different than it did a mere decade ago?  I would very much like to discuss these questions in the context of the current state of the art.

Readings will be drawn from academic as well as industrial sources.  Topics will include emerging work on:

 * Lightweight software verification techniques
 * Bug finding approaches, including fault injection, and fuzzing.
 * Debugging frameworks
 * Tracing and data lineage collection
 * Configuration and release management
 * Scaleable and robust infrastructures
 * Incident response and remediation


To make good on the promise of ``cutting edge'' research, I will constrain our choice of papers to work published in the last three years at the top systems conferences (primarily SOSP, OSDI, NSDI and ATC, although we can make some exceptions).


We will come to class prepared to discuss the papers critically; to talk about how the research was carried out, what questions it attempted to answer, and ultimately whether it was successful. This is not a lecture course.  I will prepare for each class in the same way you will: by reading a paper or two critically and coming to class ready to dig in and/or argue. To make all of this work, I will do my best to keep the class size small so that we can have meaningful discussions in which everyone feels included.
 
I will update this page soon with details about the specific topics on which the course will focus.
 

# Readings

This course is a research seminar: we will focus primarily on reading and discussing conference papers.  We will read 1-2 papers (typically 1) per session; for each paper, you will provide a brief summary (about 1 page).  The summary should answer some or all of the following questions:

 * What problem does the paper solve?  Is is important?
 * How does it solve the problem? 
 * What alternative approaches are there? Are they adequately discussed in the reading?
 * How does this work relate to other research, whether covered in this course or not?
 * What specific research questions, if any, does the paper raise for you?

The tentative reading list for this class (a work in progress) can be found here:

[Readings](https://docs.google.com/spreadsheets/d/1MAhmHa4JQfOIXcwKv63uL9WlO1NBzfosml8oAEb3qJo/)
 
 
# Presentations

All students will be expected to present at least two research papers to the class.  The presentation format is open: students will not be required to prepare slides (though doing so may help to organize the subject matter).  If you do use slides, they should be original (created by you), and external material such as figures should be properly attributed.  If you choose not to present slides, use the whiteboard well.


# Final Project

Students must submit a final project related to distributed storage systems and/or programming models.  Projects can be of one of two kinds:

 * Research projects, which present novel research that could (eventually) lead to a conference or workshop publication.  I strongly encourage you to do a project of this kind; after all, research is what we are here to do.  Systems research is challenging and quarters are short, so students may work in teams of up to three people.  Note however that the number of contributors will be considered when the projects are graded.  A team of three can and should take on a substantially more ambitious problem than a team of two or one.
 * Survey papers, which attempt to provide a complete picture of work in a narrow area.  Survey papers may only have one author.  Needless to say, they should not cover material already covered in class.
 
Re-submitting a paper already submitted in any form to a class from a previous semester is not allowed.  Submitting a paper concurrently to another class is allowed only with pre-approval from the instructor.  In such cases, as with group papers, I expect the work to be especially strong.

# Grading

| Subject | Share |
|-------|---------|
| Paper summaries | 20% |
| Participation | 20% |
| Presentations | 20% |
| Project | 40% |

Final projects are required to pass the course.  The fact that participation accounts for 20% of the grade should give you an idea of the important of class attendance.  

# Academic honesty

Collaboration is a key part of research.  I encourage you to discuss the readings and the final project ideas with your classmates.  However, you must reveal the students with whom you discussed the papers in your summaries.  Failure to do so will result in formal disciplinary proceedings.  

I should not need to say so, but I do: plagiarism in any form is not acceptable and will not be tolerated.  As researchers, we always stand upon the shoulders of giants, and building upon existing work is the norm.  It is essential, however, that we provide proper attribution.  When in doubt, cite!  Missing a relevant piece of related work is an embarassment for any  researcher; failure to cite a direct influence is dishonest and catastrophic to a researcher's career.  The related work section is one of the most critical parts of any paper: spend an adequate amount of time on it.



