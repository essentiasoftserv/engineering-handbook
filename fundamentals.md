# Introduction
This is an attempt to indoctrinate fresh engineers with some of the best practice / viewpoints before they join the workforce. It wouldn't hurt for experienced folks to also take a look. 
It outlines the basics of what is expected of a software engineer. While it mostly contains brief reference materials to be read, it also contains some books which cannot possibly be read by anyone in a short span of time. 
Use it as a guide rather than a syllabus. Cover what is humanly possible. Some of the directives are lifelong habits so to speak, eg: revising basic concepts daily. 
# Communication
## Command over language
This is at the heart of everything. Human workers spend most of their time communicating with other humans, their own past or future selves, LLM chatbots, their computers or ensuring their programs talk to other programs flawlessly. 

Someone with command over the English language is automatically capable of getting more done in the modern world. The language of choice may depend upon the situation, demography geography etc, but communication goes beyond just being able to frame grammatically correct sentences. An effective communicator is able to ensure that 
- they are thinking the correct thing that needs to be said 
- their thoughts are being translated to the right words
- their sentences and pronunciation are free of ambiguity 
- their words reach their intended audience clearly.
- their audience understands what they wanted to say
- they are able to verify that the audience understood what they thought they should say.

Poorly chosen words and ambiguous doctrines can be blamed as the root cause for a ton of the pain and mayhem in human history.

## Asking Questions - seeking Clarity
This is the most underrated skill. Most of the miscommunication can be avoided by asking the right questions, in the right tone of voice.

Statements might make people defensive. 
Honest questions make people open up. 
Engineers have to be inquisitive and curious to the extent of being annoying to be any good at their job. 

One needs to approach it like a lawyer interrogating a witness. A question framed correctly, even if it is coming from a biased standpoint is better than no-question. It either helps learn something new or confirms what someone already knows.

Very few people have a clear idea of what they want. Our job as engineers called in to build a technical solution is, to first figure out whether people want what they say they want. And then also understand whether they understand what they think they want is actually the thing they say they want.
Attempting this without asking questions would be an endeavour doomed to fail even before it starts. 

Expecting the client / manager / stakeholder / user to explain what they want and trusting that blindly, is a recipe for disaster. 
Trusting the assumption that we come to, without verifying it with the user is equally bad. 
Yes, make assumptions. 
Yes, guess what the user may want. 
\Yes, trust your gut - but VERIFY.

Questions should be precise and concise. 
Questions with options are answered more promptly by busy people.
Your managers are busy, make their life easy. 

Clarity is key.
Prefer written communication for critical decision making. 
Human memory cannot be trusted. Even honest people may honestly not remember something they said or committed to. A written trail to hold people accountable is always better. While this is a no-brainer for freelancers - they may not get paid for an iota of work if the client claims "I never asked you to do this." - the reputation and hence the career growth of employees also depends on being able to fulfil their promises.

## Touch typing
Typing has stood the test of time and is here to stay for the foreseeable future. Most of the white collar workforce is going to spend a lot of time typing away on their keyboards. Goes without saying that someone who is able to touch type (type with all their 10 fingers, without looking at the keyboard) is a lot more productive than someone who hunts and pecks with two.


So, how do you learn?
- choose a keyboard layout: dvzine.org
- choose a typing tutorial tool: keybr.org
When you start practicing:
- sit with your back straight,  do NOT slouch.
- rest the heel of your palm on the palm rest of your keyboard. 
- place the fingers on the home row. Fingers come back to this position after tapping every key.
- try to maintain 100% accuracy, do NOT even try to type fast. 
- Do NOT look at the keyboard. 
- practice for 10 - 15 minutes everyday, do NOT over exert yourself. 
- STOP if you are making mistakes, take a break, stretch a little, re-focus, concentrate and try again. 
- This takes time before results become apparent, just like working out in a gym.

Train of thought flows a lot more smoothly when the fingers have the muscle-memory and know which keys to hit. Hot Take: no one (except the differently-abled) should be able to call themselves a computer engineer without knowing how to touch type. 

Note: Not maintaining proper posture will strain your rests and cause RSI. 

# The Basics of Computer Science
The sphere of human knowledge is expanding at a rate impossible for any human to encompass. Increasingly, humans aren't even being expected to know everything about everything, when you can ask an AI. However, even in order to search the web, books or to ask an AI chatbot, one would need to know enough to be able to form the right questions and judge their response.

One needs to keep revising the concepts the were taught during their engineering days, and exploring more to get acquainted with new stuff that came up after they graduated. 

Scrolling wikipedia is a better activity than scrolling social media in this regard.

https://speakerdeck.com/swanandp/the-well-rounded-engineer

## Mathematics, Electronics, Physics, Chemistry
As a student evaluating my options for higher studies I knew I wanted to pursue Computer Science. In my mind it was an island in its own right. Everything else was mundane. 
Little did I know, that I was falling prey to the hype around computer science created by corporations and universities.
I see it happening again, as colleges rename their courses to make them seem more relevant with a dash of AI sprinkled in their curriculum. 

As we flock to take these overhyped and inflated courses, we go farther away from the knowledge that made the technological advances possible in the first place. We risk becoming a priest who chants the mantra and participates in the 

Disconnected from the basics, we will never be able to sink our roots deep enough to weather the next storm the industry whips up in the next hype cycle. 

We as engineers, need to go deep and understand how things work and in order to do that, we need to revise the basics of everything Science and Mathematics.

After all, it was physics that specialized into Electronics and with the amalgamation of Mathematics and Electronics, Computer Science was born. 

## Data Structures and Algorithms
The present day obsession around solving DSA problems and competitive programming competitions is an inevitable manifestation of Goodhart's law.
Do not get me wrong, grokking DSA is extremely important, however doing so with the sole goal of cracking an interview round is depressing.

Someone who does not understand the algorithms and their underlying data structures cannot be a good programmer but an excellent competitive programmer may be terrible at software engineering.

Dive deep into DSA, with the aim of using it for the rest of your life and not just for clearing a job interview.

reference:
- Introduction to Algorithms: CLRS
- Wikipedia articles on each algorithm / data structure.
- https://en.wikibooks.org/wiki/Data_Structures
- https://en.wikibooks.org/wiki/Algorithms
- 
## Computer Architecture and Operating Systems
A good software engineer would know the os where their programs run. A long time favourite interview question is: what happens between me pressing the power button on my personal computer and the os presenting me with the login screen?

Answering it in as detailed manner as possible requires knowledge transcending boundaries of different courses taught in engineering days.
## Computer networks
Similar to the trope about OS, there is a question for poeple who want to make web applications: "What happens when I type the address of a website in my browser and press enter?".

Most of the applications we build would talk to other programs over some network and lack of knowledge of how the data flows between them will stunt our ability to reason about them. 

The book on Computer Networks by Andrew S. Tannenbaum is a favourite bed time read for me. Wikipedia articles on various concepts also help in keeping those concepts fresh.

github.com/alex/what-happens-when

## Databases
Managing data is the whole reason we build programs. More often than not, our cool web applications, built on fancy frameworks and awesome programming languages are just a veneer on top of a database.

As it is with the concepts of DSA, OS and networks, knowing the theory and working of databases enable us to write better, performant software.

Besides in depth understanding of Postgres, knowledge of any no-sql database is essential for a modern software engineer.
## Machine Learning and Artificial Intelligence
Calling APIs provided by Anthropic or OpenAI is akin to present day religious people performing rites and chanting hymns / mantras oblivious of what the words / actions are supposed to mean. 

Know how to call the apis, but also understand what the APIs do underneath.

## Theory of Automata

## History, Psychology, Humanities and Public Policy.

These subjects aren't usually taught as a part of any engineering course, but they should be.
### Why?
#### Recursive blunderer
A good engineer would know why a piece of technology was built, when and by whom. What were the problems that it solved and what new problems did it create? Armed with this knowledge the good engineer would make informed choices when faced with similar conundrum in their present, while the bad engineers stumbles on the same potholes that stumped their predecessors.
#### Blissfully ignorant
Every action, every choice of an individual has an effect on the society and thus becomes political in nature.

Whether engineers follow orders OR question the authority figure when asked to build surveillance software, they are taking a political stand. Someone who does not understand the ramification of their choices will unknowingly help build the dystopia that eventually dehumanises them eroding their rights and privacy.
#### Reference Materials: 
- 1984 by George Orwell
- Stories of Aaron Swartz, Edward Snowden.
- Minority Report (movie)
- Public Policy course by Takshila Foundation
# Software Engineering and Development Ecosystem

# Standard tools and practices

## programming language and its ecosystem
Choose one, to begin with. Stick with it.


It may be difficult in the age of LLMs for our monkey brains to realize, but computers do not really understand human language. Besides, human languages are prone to miscommunication. Programming languages make it possible to give unambiguous instructions to a computer that it follows down to the letter.

A software engineer needs to master at least one, and be comfortable with a few programming languages. While the machine understands electrical currents, voltages, machine language (zeros and ones), instructions in Assembly are the closest to hardware (low level). The programs written in Assembly language are difficult to port to other architectures, because its instruction set depend on the architecture of the underlying hardware.
This is where "high" level languages come in with their compilers, interpreters and virtual machines. Programs written in these high level languages can either be cross compiled or run on Virtual machines compiled for other hardware architectures.

Every programming language is opinionated with its paradigms and the way idiomatic code is written in them. 
The closer you are to the hardware, the faster your code runs, but its takes longer for the human to write that code. 
Become comfortable with the tools and libraries in the ecosystem of the language.

Python: pymbook
Rust: rustbook

Elixir: official documentation
Javascript: ydkjs
Typescript
C / C++
Haskell: learnyouahaskell

reference:
- practice here: https://exercism.org/ 
- learn what makes a  here: 
	- https://web.mit.edu/6.001/6.037/sicp.pdf
	- https://mitp-content-server.mit.edu/books/content/sectbyfn/books_pres_0/6515/sicp.zip/index.html
## ​text editor
Choose either emacs or vim or one of their distros, eg doomemacs or neovim
Use it in the terminal without AI or auto suggest.
Would you give a child a calculator before she can add two numbers in her mind?

TODO: Know the editor inside out, rather than just trying to look cool with it. 
## Version Control: git 
During the life of a codebase, programmers try innumerable things. Some of them work, some don't. Being able to go back to a version that used to work provides the safety net crucial for making modifications.

Git is the most famous Version Control system. Learning and using it for every project is non-negotiable. 

Reference: https://git-scm.com/book/en/v2
Interactive Tutorial: https://gitimmersion.com/

Developer tools
Team work, collaboration, accountability 
Problem solving approaches: recursively breaking large problems down into smaller problems.
definition of done.

# Devops

# Management

## Time, Self, Projects 

##  People: managers, reportees, colleagues, bosses, clients. 

# Marketing and Sales

## Software Design: A Tool-Based Introduction with Python
https://third-bit.com/sdxpy/ is a free online book that teaches how to design and build real software systems using Python. Instead of focusing only on basic syntax, it shows how real tools like databases, interpreters, web servers, and debuggers work internally. 

By studying this, you learn important software engineering skills such as organizing code, breaking big problems into smaller parts, and writing clean, maintainable programs. 

It helps you move from basic programming to thinking like a professional software developer and building real-world applications.
