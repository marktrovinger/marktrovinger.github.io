# Course Review: Modern Reinforcement Learning: Deep Q Learning in PyTorch

I recently completed Phil Tabor's [Modern Reinforcement Learning: Deep Q Learning in PyTorch](https://www.udemy.com/course/deep-q-learning-from-paper-to-code/) Udemy course. I found the overall course to be very useful, especially in addressing some shortcomings in my own approach to learning. There were some minor technical difficulties, but nothing that make the course impossible to complete.

I found the course to be very well structured, starting with a short introduction to the topics that will be learned, along with an overview of what strategies will be useful in completing the course, and what software and hardware will be needed. I found this section well laid out, without an unnecessarily long introduction about hardware, which other courses I have taken have felt the need to include. While the introduction was overall well done, it does lack a written list of what versions of the packages will be used throughout the course, which can lead to issues further on. While the package information is displayed in a terminal, it is very easy to miss, and a `requirements.txt` or similar file would be helpful.

The next main section is an overview of the fundamentals of Reinforcement Learning. I skimmed these, having had an introduction to the material in a different course. From what I watched, these lectures seemed very well done, which is a constant throughout this course.

The next section is a crash course in deep learning, which like the Reinforcement Learning section, I mostly skimmed. If you have a fairly strong grasp of how neural networks operate, you can probably skip it. I skimmed this section mostly to make sure there wasn't anything that I was missing before diving into the meat of the course.

The main thrust of this course is to take a paper, or series of papers in this case, and implement them in code. As the title of the course suggests, the code is written in Python and the framework of choice is PyTorch. The main value I derived from this course is a better sense of how to read an academic paper, and while reading the paper, start thinking about what data structures and algorithms could be used implement the paper. 

The first paper is [Human-level control through deep reinforcement
learning](https://web.stanford.edu/class/psych209/Readings/MnihEtAlHassibis15NatureControlDeepRL.pdf) by Mnih, et. al. Phil does an excellent job of explaining what sections of the paper should be paid attention to, and which sections can be skipped for a later read-through. Once the paper has been discussed, the software engineering part of the course comes into play. While I have a computer science degree, I find myself often forgetting some of the basics of software engineering, especially when it has been a while since I have written code. Here, Phil does a very good job of working through the process of taking an equation on a page and turning it first into psuedocode, and then into Python. He will always ask you to pause after explaining what is needed for a given section and give you a chance to code it first. I would highly recommend doing this! My solution was not even close when I started the course, but with more familiarity I was able to code solutions much closer to his by the end of the course. 

The course then covers three other papers, much in the same way it covered the first. I highly recommend the course to anyone who would like to learn more about taking a paper and implementing it.


