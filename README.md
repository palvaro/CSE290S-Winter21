# CSE290S-Winter21: 
## Distributed storage systems and programming models
| key | value | 
|-----|-------|
|When: | TBD |
|Where: | TBD |
|Who: | Peter Alvaro |
|Office hours: | TBD |
|Prerequisites: | A background in systems and an interest in theory |
|Readings: | [Readings](https://github.com/palvaro/CSE290S-Winter21/blob/master/readings.md) (volatile; subject to significant change)|

# Description

Hi prospective students!  This page is a placeholder for the Winter 2021 Special Topics Seminar in Distributed Systems.

I have been so busy with *gestures around* that I have not yet chosen the special topic!  Here are some things that I can say for sure about the course:

 * it is a reading seminar in systems research.  this means that we will read and discuss a lot of conference papers.  it means that we will come to class prepared to discuss the papers critically; to talk about how the research was carried out, what questions it attempted to answer, and ultimately whether it was successful.
 
 * it is not a lecture course.  I will prepare for each class in the same way you will: by reading a paper or two critically and coming to class ready to dig in and/or argue.
 
 * to make all of this work, I will do my best to keep the class size small so that we can have meaningful discussions in which everyone feels included.
 
 * I will update this page soon with details about the specific topics on which the course will focus.
 
 In the meantime, I provide an example of a past special topics seminar that I taught a number of years ago.  The syllabus for that course follows:

# Example Description

This graduate seminar will explore distributed systems research, both current and historical, with a particular focus on storage systems and programming models.

Due to fundamental uncertainty in their executions arising from asynchronous communication and partial failure, distributed systems present unique challenges to programmers and users.  Moreover, distributed systems are increasingly ubiquitous: nearly all non-trivial systems are now physically distributed.  It is no longer possible to relegate responsibility for managing the complexity of distributed systems to a group of expert library or infrastructure writers: all programmers must now be distributed programmers. This is both a crisis and an opportunity.

A great deal of theoretical work in distributed systems establishes important impossibility results, including the famous FLP result, the CAP Theorem, the two generals problem and the impossibility of establishing common knowledge via protocol.  These results tell us what we *cannot* achieve in a distributed system, or more constructively, they tell us about the properties we must trade off for the properties we require when designing or using large-scale systems.  But what *can* we achieve?  The history of applied distributed systems work is largely the history of infrastructures -- storage systems as well as programming models -- that attempt to manage the fundamental complexity of the domain with a variety of abstractions.  

This course focuses on these systems, models and languages.  We will cover the following topics:
 

 * Consistency models
 * Large-scale storage systems and data processing frameworks
 * Commit, consensus and synchronization protocols
 * Data replication and partitioning
 * Fault-tolerant design
 * Programming models
 * Distributed programming languages and program analysis
 * Seminal theoretical results in distributed systems
 
# Readings

This course is a research seminar: we will focus primarily on reading and discussing conference papers.  We will read 1-2 papers (typically 2) per session; for each paper, you will provide a brief summary (about 1 page).  The summary should answer some or all of the following questions:

 * What problem does the paper solve?  Is is important?
 * How does it solve the problem? 
 * What alternative approaches are there? Are they adequately discussed in the reading?
 * How does this work relate to other research, whether covered in this course or not?
 * What specific research questions, if any, does the paper raise for you?
 
 
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



