# Accessibility of Python and Data Science

* Abhisar Waghmare
* Rishabh Jain
* Shakul Raj Sonkar
* Sunil Choudhary

---

# Assistive technologies

* Brief description about screen reader
* Demo of screen reader
* JAWS and NVDA
* Screen readers do not differentiate between code and text

---

# Accessibility of Python

### How do we quantify it?

* Ease-of-use for blind developers in doing the following coding activities
    * reading, 
    * navigating, 
    * understanding, 
    * writing,
    * debugging

---

# Accessibility of different IDE and editors

* IDLE: CLI not accessible
* Spyder: editor works fine, but the console is not accessible.
* IPython
* Jupyter notebook: the input field does not allow for moving from one line of code to the next
* VS code

---

# What makes an IDE accessible?

* Keyboard shortcuts for most essential functions (e.g. program execution, setting breakpoints, navigating to the debug window etc.)
* Use of semantically correct constructs to present information
* Easy editing with screen readers 
* Access to all functionalities of the IDE with a screen reader

---

# What makes an IDE awesome?

* Audio cues for visual information (e.g. indentation)
* Ability to navigate large codebases in more accessible ways (e.g. tree structure)
* real time access to critical information (sintax errors for example)
* non-visual methods to track performance metrics and status in case of long execution times

---

# Experiences of VI programmers

* I-Stem conducted technical training program in which six students used Python for an introductory CS course and an ML course

## 1. Introductory course

* Language simplification helped participants in the intro program learn faster
* Indentation can be challenging since screen readers usually don't read it (e.g. nested loops can be very challenging to learn for basic learners)
* Used CLI as it is fundamentally accessible

---

# Experiences of VI programmers

## 2. Data science and ML

### ML for non-technical people

* ML democratization usually excludes blind developers
* No accessible platform 

---

# Experiences of VI programmers

### Data analysis and Feature Engineering

* Visualizing data containing huge number of columns and rows can be challenging
* Visual representations are inherently inaccessible

#### Solutions

* Summarizing the graph through different statistical parameters
* Audio graph
* Can we do better?

---

# Experiences of VI programmers

### Model selection and training

* comparing different curves
* Understanding the path of different curves

---

# Experiences of VI programmers

### Deployment on cloud

* Accessibility of key cloud services (AWS, Azure, Google Cloud)?

---

# conclusion

* Accessibility of programming language is interplay of
    * screen reader
    * IDE
    * Programmer familiarity with tools
* if the above orchestra is in sync, then every language can be accessible.

---

# Further reading

* [Lessons from Accessible Scala](https://www.scala-lang.org/blog/2018/06/14/accessible-scala.html)
* [Quorum: language designed with accessibility focus](https://quorumlanguage.com)
* Khaled Albusays, Stephanie Ludi, and Matt Huenerfauth. 2017. Interviews and Observation of Blind Software Developers at Work to Understand Code Navigation Challenges.  In Proceedings of the 19th International ACM SIGACCESS Conference on Computers and Accessibility (ASSETS '17). ACM, New York, NY, USA,  91-100. DOI: https://doi.org/10.1145/3132525.3132550
* Catherine M. Baker, Cynthia L. Bennett, and Richard E. Ladner. 2019. Educational Experiences of Blind Programmers.  In <em>Proceedings of the 50th ACM Technical Symposium on Computer Science Education</em> (SIGCSE '19). ACM, New York, NY, USA,  759-765. DOI: https://doi.org/10.1145/3287324.3287410
* Shaun K. Kane, Varsha Koushik, and Annika Muehlbradt. 2018. Bonk: accessible programming for accessible audio games.  In <em>Proceedings of the 17th ACM Conference on Interaction Design and Children</em> (IDC '18). ACM, New York, NY, USA,  132-142. DOI: https://doi.org/10.1145/3202185.3202754
* Lauren R. Milne and Richard E. Ladner. 2018. Blocks4All: Overcoming Accessibility Barriers to Blocks Programming for Children with Visual Impairments.  In <em>Proceedings of the 2018 CHI Conference on Human Factors in Computing Systems</em> (CHI '18). ACM, New York, NY, USA,  Paper 69, 10 pages. DOI: https://doi.org/10.1145/3173574.3173643
* Emmanuel Schanzer, Sina Bahram, and Shriram Krishnamurthi. 2019. Accessible AST-Based Programming for Visually-Impaired Programmers.  In <em>Proceedings of the 50th ACM Technical Symposium on Computer Science Education</em> (SIGCSE '19). ACM, New York, NY, USA,  773-779. DOI: https://doi.org/10.1145/3287324.3287499

