# QMock-
Team 3
Project Name: Artificial Intelligence Powered Mock Interview Tool
Project Description:
The AI Mock Interview Tool utilizes advanced natural language processing and emotion
recognition algorithms to analyze candidates’ interview performances. Users will get real-time
feedback on eye-movement, tone, clarity, and confidence levels.
Project Purpose & Value to the industry (This is the value proposition statement of
why the project is initiated and how it matters to the business or industry.)
Implementing this tool enhances our business capabilities by providing a cutting-edge solution
that meets the evolving demands of recruitment and talent development.
This tool streamlines the interview process, saving time and resources while ensuring a more
thorough assessment of candidates. It empowers interviewers with valuable insights into
candidates’ soft skills and communication abilities, allowing for more informed hiring decisions.
Candidates receive personalized feedback and coaching, improving their interview performance
and increasing their chances of success. Employers gain access to a pool of better-prepared
candidates, ultimately leading to higher-quality hires and improved organizational performance.
Project Scope (Define the boundary of the project)
The AI Mock Interview Tool will be used to analyze candidates’ eye-movement, tone, clarity, and
confidence levels. This project covers analysis & design, development and testing of a prototype
of a mock interview tool plus full documentation that serves as a proof-of-concept supporting
limited functions as listed under High-level Requirements.
Constraints:
1. 2. No formal business requirement discovery process is performed.
This project is only a proof-of-concept showing the capabilities of the students to the best
supported by the information and data from TBC.
3. The end product from this project will not be deployable due to cost constraints and lack
of complete business & functional requirements from TBC.
4. The chatbot will not support follow-up questions from the users since the dataset does not
provide follow-up data.
5. This project is constrained by its timeline, functionality will be limited to necessities only at
the discretion of the project advisor.
Project End Product(s) (Define the expected outcome of the project which needs to be
tangible and measurable.)Page | 1
AIP PROJECT INCEPTION PAPER
1. The end-product is a prototype as Proof-of-Concept (POC) of a mock interview tool.
2. Full documentation including but not limited to technical spec, functional spec, source
code and installation scripts & procedures, user instruction in form of a library set
High-Level Requirements (Define the functional and technical requirements to be met to
produce project end product.)
User Interface (UI):
The mock interview tool has a user-friendly interface for candidates to start, pause, and stop mock
interviews, and a dashboard for displaying post-interview analysis.
Natural Language Processing (NLP):
The mock interview tool shows a transcription of candidate responses with advanced NLP and
emotion recognition algorithms. It provides analysis of speech content for clarity, relevance, and
coherence.
Post-Interview Analysis:
The mock interview tool shows a report summarizing strengths and areas for improvement and
suggestions for enhancing interview performance.
Compatibility and Expandability:
The mock interview tool provides support for various devices (desktop, mobile, tablets) and
operating systems and can allow additional features to be built upon its existing code as plug-ins.
Documentation:
The mock interview tool should have proper documentation and comments in code for easy
readability and understanding, which can allow the project to be further developed and deployed
by future teams.
MUST HAVE:
Video and Audio Recording:
The mock interview tool can allow users to video record themselves on the platform. Recordings
can be viewed, managed, and uploaded as needed.
Prep time, Recording time, and Flow:
For each question, the user gets a prep-time of 30 seconds and a recording time of 2 minutes
within which they can answer. Once the user has completed answering the question, they can
mark the recording as done to move on to the next question. Users can only move through the
questions sequentially.
Questions will be based on the role they are practicing their interview for. The mock interview tool
can support 5-10 different role-based job interviews, as well as a general interview HR round of
questions.
Face presence, distance to camera:
The mock interview tool detects the user’s face and analyzes their distance. If the user does not
have their face centered or is far away/too close to the camera, the user is prompted on the screen
Page | 2
AIP PROJECT INCEPTION PAPER
of this, and they will not be allowed to record themselves until they have corrected their posture
in front of the camera.
Eye Contact:
The mock interview tool can analyze how long the user is able to maintain eye contact with the
camera and based on the results provide corrective feedback at the end of the interview, as well
as the significance of maintaining eye contact.
Facial Expressions:
The mock interview tool can process and analyze the user’s facial expressions while conducting
the interview to provide corrective feedback at the end along with the significance of displaying
positive facial expressions.
Video Quality:
Audio Quality:
Video Background:
The mock interview tool can distinguish between the user and the background and focus on the
main subject in the frame if multiple people appear. If there is too much disturbance in the
background, the tool can prompt the user to find a space with less disturbance.
Audio Background:
The mock interview tool can distinguish and filter out the user’s voice from the background noise,
as well as music, or other people talking. If the audio background noise is interfering or too loud
for the tool, it can prompt the user to move to a quieter place.
Filler Words Detection:
The mock interview tool can detect and analyze the frequency of filler words to gauge whether
the user sounds natural or not. The tool can help with suggestions if there are too many filler
words, or too less to sound like the user is reading from a pre-prepared paragraph.
GOOD TO HAVE:
Grammar Check:
The mock interview tool can check for grammatical errors in the user’s speech. The only
supported language is English. The use of any other language will result in an invalid attempt.
Confidence Analysis:
The mock interview tool can perform tone analysis, as well as eye movement on the user’s speech
to determine the confidence levels.
Question Answer Scoring:
The mock interview tool can score the user based on the answer they provided for the question
provided. The questions supported are basic introductions such as “tell us a little about yourself”.
