# MC-C3100 Computer Graphics, Fall 2018
# Lehtinen / Aarnio, Kemppinen, Ollikainen
#
# Assignment 1: Introduction

Student name:   Aleksanteri Paakkinen
Student number: 588807
Hours spent on requirements (approx.): 3h
Hours spent on extra credit (approx.): 4h?

# First, some questions about where you come from and how you got started.
# Your answers in this section will be used to improve the course.
# They will not be judged or affect your points, but please answer all of them.
# Keep it short; answering shouldn't take you more than 5-10 minutes.

- What are you studying here at Aalto?

  Mathematics major + CS minor

- Which year of your studies is this?

  Third

- Is this a mandatory course for you?

  No

- Have you had something to do with graphics before? Other studies, personal interests, work?

  Very little personal programming experience, more with vfx tools like Maya et al

- Do you remember basic linear algebra? Matrix and vector multiplication, cross product, that sort of thing?

  Yes

- How is your overall programming experience? What language are you most comfortable with?

  Broad but not deep, most comfortable with C or Python

- Do you have some experience with these things? (If not, do you have experience with something similar such as C or Direct3D?)
C++: A little, but have C backgroud
C++11: Not much
OpenGL: I have played around with it before, but nothing complicated

- Have you used a version control system such as Git, Mercurial or Subversion? Which ones?

  Yes, Git

- Did you go to the technology lecture?

  Yes

- Did you go to exercise sessions?

  No

- Did you work on the assignment using Aalto computers, your own computers, or both?

  My own computer

# Which parts of the assignment did you complete? Mark them 'done'.
# You can also mark non-completed parts as 'attempted' if you spent a fair amount of
# effort on them. If you do, explain the work you did in the problems/bugs section
# and leave your 'attempt' code in place (commented out if necessary) so we can see it.

(Try to get everything done! Based on previous data, virtually everyone who put in the work and did well in the first two assignments ended up finishing the course, and also reported a high level of satisfaction at the end of the course.)

                            opened this file (0p): done
                         R1 Moving an object (1p): done
R2 Generating a simple cone mesh and normals (3p): done
  R3 Converting mesh data for OpenGL viewing (3p): done
           R4 Loading a large mesh from file (3p): done

# Did you do any extra credit work?

  Files are in my general school stuff git-repo. (logfile.txt)
  Object scaling and rotation works correctly. (scale +/-, rotation ins/del)
  Normals are transformed correctly and efficiently.
  Virtual trackball rotation for the camera works. I did it with quaternions for which I had to get the formulas from the interwebz, is there no readily
  available methods for this in the framework? (no translations for the camera, also the ui shows wrong coordinates)

# Are there any known problems/bugs remaining in your code?

(Please provide a list of the problems. If possible, describe what you think the cause is, how you have attempted to diagnose or fix the problem, and how you would attempt to diagnose or fix it if you had more time or motivation. This is important: we are more likely to assign partial credit if you help us understand what's going on.)

# Did you collaborate with anyone in the class?
I did answer to a question on Mycourses forums about the retargeting problem in VS.

(Did you help others? Did others help you? Let us know who you talked to, and what sort of help you gave or received.)

# Any other comments you'd like to share about the assignment or the course so far?

It was fun, the normal scaling part wasn't explained well enough IMO, especially the part about how you would fix it in your code.
Also I think it's kind of pointless to ask people to write inefficient code, especially in this situation where the faster way is also
the more idiomatic one.

(Was the assignment too long? Too hard? Fun or boring? Did you learn something, or was it a total waste of time? Can we do something differently to help you learn? Please be brutally honest; we won't take it personally.)

