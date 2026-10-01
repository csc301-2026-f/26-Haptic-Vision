# Real-Time Blind and Low Vision Accessibility Software — Haptic Vision Inc. (Tactile Vision)
> _Note:_ This document will evolve throughout your project. You commit regularly to this file while working on the project (especially edits/additions/deletions to the _Highlights_ section). 
 > **This document will serve as a master plan between your team, your partner and your TA.**

## Product Details
 
#### Q1: What is the product?

Our product is a real-time accessibility system that converts 2D digital interfaces and visual content into interactive, customizable 3D representations to help blind and low vision (BLV) users better understand and interact with digital content.

This project is being developed in partnership with Haptic Vision. Our primary partner contact is **Alexander Kurk, CEO of Tactile Vision and an MBA student at the University of Toronto's Rotman School of Management**. The organization develops assistive technology for blind and low vision individuals. Many modern digital interfaces rely heavily on visual information such as spatial layouts, buttons, images, diagrams, videos, and visual hierarchy. This information can be difficult or impossible for BLV users to perceive using existing accessibility tools, limiting their ability to independently interact with modern digital devices and applications.

Our team will build a functional MVP that captures visual content from a screen or browser window, analyzes the content, and generates a corresponding 3D representation in real time. For example, a button displayed on a webpage could be represented as a raised 3D object, while images and other visual elements could be represented using varying depths and shapes. Important areas of the interface can also be emphasized so that the resulting representation communicates not only where elements are located, but also which elements are most relevant to the user.

Users will be able to customize aspects of the 3D representation, such as depth, scale, and emphasis. The system will also support interaction between the generated 3D representation and the original interface, so that interacting with an element in the 3D representation can correspond to an interaction with the original digital interface.

The software developed during this project represents one component of Haptic Vision's larger accessibility system. In the future, the generated 3D representations are intended to be integrated with robotic assistive technology that can physically reproduce these representations, allowing BLV users to feel and interact with digital interfaces through touch. The robotic hardware and its integration are outside the scope of our project. Our focus is on building the software prototype that converts visual digital content into useful, interactive 3D representations.

#### Q2: Who are your target users?

The primary target users are **blind and low vision (BLV) individuals who experience difficulty accessing visual and spatial information presented through modern digital interfaces**. These users may currently rely on assistive technologies to interact with computers and other digital devices, but visual information such as interface layouts, images, diagrams, videos, and the spatial relationships between elements can remain difficult to understand.

For example, a BLV user may be able to access the text associated with elements on a webpage but still have difficulty understanding how those elements are spatially organized, which areas are visually emphasized, or what information is being communicated through an image or diagram. Our product aims to provide an alternative representation of this information by translating visual content into customizable 3D structures.

Because accessibility needs can differ between users, customization is an important part of the product. Users should be able to adjust characteristics such as the depth, scale, and emphasis of the generated representation so that information can be presented in a way that is most useful to them.

Secondary stakeholders include the partner organization's researchers and engineers, who may continue developing the system and integrate it with robotic assistive technology in the future. Other stakeholders include accessibility researchers, UI/UX designers exploring alternative ways of representing digital interfaces, assistive technology partners, and future developers who may continue developing and integrating the system.

Ultimately, the product is intended to help BLV individuals gain greater access to the spatial and visual information contained in digital interfaces, while providing the partner organization with a software foundation that can later be integrated with its physical assistive technology.

#### Q3: Why would your users choose your product? What are they using today to solve their problem/need?
This product fits the needs of the target users because it’s designed to improve the digital experience of blind and low-vision people by helping them better understand and navigate unfamiliar interfaces. Tools today provide screen readers, magnification software, and tactile displays, but they don’t provide the overall spatial understanding of how the user interface is organized. 

Research conducted by Alex and his team showed the value of this project. They 3D printed a model of Microsoft Teams interface, and after letting the participants feel this model, they instantly had a better grasp of what the platform, which they’d use almost daily, actually looked like. The study found that providing a 3D representation helped visually impaired participants better understand the architecture of the platform they were using and be able to navigate it more quickly, bringing their understanding of the interface closer to that of sighted users. Using this software, it will allow visually impaired users to better familiarize themselves and understand the content that they’re being shown, and in turn, help them orient themselves more quickly (content ranging from, but not restricted to, online shopping such as Amazon, maps, and other). 

Overall, there exist bits and pieces of software that provide a similar solution, such as TactiDesk, which captures the screen in real time and converts it into tactile graphics for pin-based displays. However, they don’t provide the interface understanding and tactile representation that Haptic Vision is looking for.  

#### Q4: What are the user stories that make up the Minumum Viable Product (MVP)?

 * At least 5 user stories concerning the main features of the application - note that this can broken down further
 * You must follow proper user story format (as taught in lecture) ```As a <user of the app>, I want to <do something in the app> in order to <accomplish some goal>```
 * User stories must contain acceptance criteria. Examples of user stories with different formats can be found here: https://www.justinmind.com/blog/user-story-examples/. **It is important that you provide a link to an artifact containing your user stories**.
 * If you have a partner, these must be reviewed and accepted by them. You need to include the evidence of partner approval (e.g., screenshot from email) or at least communication to the partner (e.g., email you sent)

#### Q5: Have you decided on how you will build it? Share what you know now or tell us the options you are considering.

> Short (1-2 min' read max)
 * What is the technology stack? Specify languages, frameworks, libraries, PaaS products or tools to be used or being considered. 
 * How will you deploy the application?
 * Describe the architecture - what are the high level components or patterns you will use? Diagrams are useful here. 
 * Will you be using third party applications or APIs? If so, what are they?

----
## Intellectual Property Confidentiality Agreement 
> Note this section is **not marked** but must be completed briefly if you have a partner. If you have any questions, please ask on Piazza.
>  
**By default, you own any work that you do as part of your coursework.** However, some partners may want you to keep the project confidential after the course is complete. As part of your first deliverable, you should discuss and agree upon an option with your partner. Examples include:
1. You can share the software and the code freely with anyone with or without a license, regardless of domain, for any use.
2. You can upload the code to GitHub or other similar publicly available domains.
3. You will only share the code under an open-source license with the partner but agree to not distribute it in any way to any other entity or individual. 
4. You will share the code under an open-source license and distribute it as you wish but only the partner can access the system deployed during the course.
5. You will only reference the work you did in your resume, interviews, etc. You agree to not share the code or software in any capacity with anyone unless your partner has agreed to it.

**Your partner cannot ask you to sign any legal agreements or documents pertaining to non-disclosure, confidentiality, IP ownership, etc.**

Briefly describe which option you have agreed to.

----

## Teamwork Details

#### Q6: Have you met with your team?

Do a team-building activity in-person or online. This can be playing an online game, meeting for bubble tea, lunch, or any other activity you all enjoy.
* Get to know each other on a more personal level.
* Provide a few sentences on what you did and share a picture or other evidence of your team building activity.
* Share at least three fun facts from members of you team (total not 3 for each member).

The team did an online game night on Discord as a way to get to know each other better. We played typical party games such as Texas Holdem poker (with fake money of course!), pictionary, and Monopoly.

Fun facts:
Parth visited Spain in the summer.
Ediz has visited over 20 countries.
Johnson once ate 32 chicken wings in one sitting.


#### Q7: What are the roles & responsibilities on the team?

All members are listed as Full Stack Developers for now. There was a delay in meeting with the partner so we do not have enough information about the technical details and requirements of the project to definitively choose between front-end, back-end or database. We will revise the roles once we know more about the technical details and requirements.

Sofia Borodaenko will be our team’s partner liaison.

#### Q8: How will you work as a team?

Partner meetings:
We have a weekly online call with Alexander Kurk and his team at Haptic Vision. Alex suggested Saturday at noon; we are picking a Saturday afternoon or Sunday time that works for everyone, and that will be our fixed weekly call for the whole term. We picked the weekend because weekday evenings clash with tutorials and other courses for several of us, and having one fixed time avoids the scheduling back and forth that delayed our second call. Sofia is our contact person for Alex. Before each call she sends him the list of topics so he can prepare. After each call she sends a short email summarizing what was decided and who is doing what by when, so both sides have it in writing. We save the notes from every meeting in the repo under deliverables/team/minutes.

First call (Thursday September 24, 7:55 pm, on Google Meet, about 40 minutes). Goal: understand what Haptic Vision wants and what problem we are solving. We talked about the problems blind and low vision users have on sites like Amazon, Google Maps, and government forms; the research Alex already did, including a 3D printed model of the Microsoft Teams screen; what kind of AI the project needs; what the input to our system is (a screen capture that works on any browser or app); what the 3D output should look like; whether users need to interact with the 3D version for the first version; and how often we talk. Alex agreed to send us his existing 3D models and example sites before the next call.

Second call (this weekend, at the confirmed weekly time). Goal: agree on the first version of the product, the user stories, and the tech approach, and get his feedback on our mockup. This call got delayed because of Alex's schedule.

Team meetings:
We have our own weekly team call on Discord, 30 to 45 minutes, right after the call with Alex, so we can turn his feedback into tasks on GitHub the same day while it is fresh. A different person runs the meeting each week so everyone gets practice and we do not depend on one person; whoever is running it posts the topics the day before. We start by checking what everyone finished from last week, then go through progress on each feature, anything someone is stuck on, and the plan for the week. Every task gets a person and a deadline before the meeting ends.

Other events:
Thursday tutorial for check-ins with the TA and showing our deliverables. Pair coding on Discord whenever someone is stuck, so problems come up early instead of when we try to combine everyone's code. Every code change goes through a pull request and one teammate has to approve it before it goes into the main branch, so nothing unreviewed gets in. One team building activity before the next deliverable.

  
#### Q9: How will you organize your team?

We track all work using GitHub Issues on our repo. Our TA and partner should have access: https://github.com/csc301-2026-f/deliverable-documents/issues
 
**Artifacts:** GitHub Issues with priority labels; a GitHub Projects board for tracking status; milestones for each deliverable (D1, D2, etc.); epics where each MVP user story is a parent issue broken into smaller sub-issues.
 
**Tracking:** anything that comes up in meetings, partner feedback, or development gets filed as an issue so nothing stays buried in chat.
 
**Prioritization:** each issue gets a label: High (blocks an MVP story or the partner asked for it), Medium (needed for MVP but not blocking), or Low (nice-to-have). Anyone can suggest a priority when creating an issue, and the team confirms labels together at the weekly meeting based on the MVP stories and partner feedback.
 
**Assignment:** pull-based. When someone has capacity they pick up the highest-priority unassigned issue, ideally matching their role, and assign themselves before starting so nobody duplicates work.
 
**Status:** tracked on a GitHub Projects board with columns: To Do, In Progress, In Review, Done. An issue moves to In Progress when someone assigns themselves and opens a branch, to In Review when a PR is up, and to Done when the PR merges and the acceptance criteria are met.

#### Q10: What are the rules regarding how your team works?

**Communications:**
 * What is the expected frequency? What methods/channels will be used? 
 * If you have a partner project, what is your process for communicating with your partner? Who is responsible?
 
**Collaboration:**
 * How are people held accountable for attending meetings, completing action items? What is your process?
 * How will you address the issue if one person doesn't contribute or is not responsive?

**Communications:**
We use Discord as our main communication channel, with separate channels for specific topics so conversations don't get lost in one general thread. The expected response time is within 24 hours, with flexibility around busy periods like midterms as long as people give the team a heads up.
 
For partner communication, Sofia is our main point of contact. We have weekly meetings with our partner, planned beforehand with a clear agenda. Between meetings, we reach out to the partner through email as needed.
 
**Collaboration:**
At the start of each weekly meeting, the team reviews outstanding action items from the previous week. If something wasn't completed, we discuss whether to reassign it or adjust the timeline.
 
If someone is unresponsive or not contributing, we reach out to them directly first. If that doesn't work, we bring it up at the next team meeting. If the issue continues after that, we escalate to the TA.

## Organisation Details

#### Q11. How does your team fit within the overall team organisation of the partner?
* Given the team structure of your partner, what role do you think your team will play?
* Examples include product development that includes developing new features, or quality assurance that includes developing features that test the product reliability, or software maintenance that includes fixing crucial bugs in the product.
* Provide examples of why you think you fit this role.

#### Q12. How does your project fit within the overall product from the partner?
* Look at the big picture of the product and think about how your project fits into this product.
* Is your project the first step towards building this product? Is it the first prototype? Are you developing the frontend of a product whose backend is developed by the partner? Are you building the release pipelines for a product that is developed by the partner? Are you building a core feature set and take full ownership of these features?
* You should also provide details of who else is contributing to what parts of the product, if you have this information. This is more important if the project that you will be working on has strong coupling with parts that will be contributed to by members other than your team (e.g., from a partner).
* You can be creative for these questions and even use a graphical or pictorial representation to demonstrate the fit.
* Briefly specify what your partner considers a success for this project. Do they want you to build specific features? Publish a usable product? Just a prototype? Be as specific as you can be at this point.

## Potential Risks

#### Q13. What are some potential risks to your project?
* Now that you have defined your project, what risks can you identify that might impact it?
* Some examples of risks at this planning stage could include:
  * Uncertainties regarding a specific feature
  * Misaligned expectations or conflicts
  * Lack of clarity in execution or decision-making
  * Limited access to data, systems, or other dependencies
  * User stories that are too abstract or too simple
* For each risk, provide a brief bullet point and then explain the risk in detail. 

#### Q14. What are some potential mitigation strategies for the risks you identified?
* Examples of mitigation strategies:
  * More communication with the partner might help with improving clarity.
  * Adding more details for an user story might make it less abstract.
  * Adding an extra user story might increase the project complexity, making it less simple.
* It's ok if you are unable to find mitigation strategies for all the risks right now.
