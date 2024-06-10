[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15174960&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

- Software Engineering is the process of designing, developing, testing, and maintaining software. It is a systematic and disciplined approach to software development that aims to create high-quality, reliable, and maintainable software. (https://www.geeksforgeeks.org/software-engineering-introduction-to-software-engineering/)

What is software engineering, and how does it differ from traditional programming?

- The main difference between the two roles is that software engineering focuses more broadly on the software, using complex computer science and engineering to construct the structure of the software. Programmers focus only on the technical coding, or writing, of the software itself. (https://ca.indeed.com/career-advice/finding-a-job/software-engineering-vs-programming)

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

A full SDLC has 7 basic stages: Planning, requirements, design and prototype, software development, testing, deployment, and maintenance. 
1. Planning - In this phase, the project leads to defining the project’s purpose and the desired result
2. Requirements - This second phase of the software development life cycle is often done concurrently with the first. Here, the project lead analyzes the product or client’s goals and decides on the features to aim for as a final goal
3. Design - defines how a software application will work. During this phase, teams decide on the programming language, screen layouts, and relevant documentation they will use.
4. Implementation- During this phase, developers start programming. writing codes and building the software according to the design specifications.
5. Testing: conducting various tests to ensure the software meets quality standards and functional requirements. Different types of testing occur, such as code quality, unit testing, integration testing, performance testing, and security testing.
6. Deployment: the process starts once the testing phase is over and there are no bugs or errors in the development backlog. releasing the software to users or customers, after testing.
7. Maintenance: providing support updates and enhancements to the software after deployment.

Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

Similarities:
- Both Agile and Waterfall are project management methodologies
- Both aim to deliver working software that meets the needs of the customer
- Both rely on the participation and collaboration of all team members

Differences:
- Approach: Agile is an iterative and incremental approach, where requirements and solutions evolve through the collaborative effort of self-organizing and cross-functional teams. Waterfall is a linear, sequential approach, where each phase of the project must be completed before moving on to the next phase.
- Flexibility: Agile is flexible and adaptable to change, allowing teams to respond quickly to changing requirements and to incorporate new ideas and feedback as they arise. Waterfall is rigid and inflexible, and does not allow for changes once a phase is completed.
- Prioritization: Agile prioritizes working software over comprehensive documentation. Waterfall places a strong emphasis on documentation.
Phases: Agile does not have a clear set of distinct phases like Waterfall does, Agile methodologies like Scrum or Kanban have different ceremonies and roles but not phases.
- Feedback: Agile encourages continuous feedback and improvement. Waterfall does not allow for feedback or changes once a phase is completed.
- Risk management: Agile allows teams to break down large projects into smaller, manageable chunks, which helps teams to identify and address potential risks early on in the development process. Waterfall does not allow for this, making it harder to identify and address risks.
(https://www.linkedin.com/pulse/agile-vs-waterfall)

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.

- Requirements Engineering is the process of identifying, eliciting, analyzing, specifying, validating, and managing the needs and expectations of stakeholders for a software system

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

- Modularity in software engineering refers to the design approach where a complex software system is divided into smaller, loosely coupled modules. Each module performs a specific function or handles a particular feature, and they interact through well-defined interfaces.This approach promotes a clear division of labour, allowing developers to focus on individual modules without being overwhelmed by the entire system’s complexity.

- modularity greatly enhances scalability. By breaking down the software into independent modules, you can more easily adapt, extend, or replace parts of the system without affecting others. This flexibility is key when scaling your application to handle increased loads or adding new features
By breaking down a large software system into smaller modules, developers can focus on writing code that is easier to understand, test, and maintain

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

- Software Testing is an activity performed to identify errors so that errors can be removed to obtain a product with greater quality. To assure and maintain the quality of software and to represent the ultimate review of specification, design, and coding, Software testing is required. Software testing is now a key component of software development because it improves consistency and performance. There are different levels of testing:

-	Unit Testing: In this type of testing, errors are detected individually from every component or unit by individually testing the components or units of software to ensure that they are fit for use by the developers. It is the smallest testable part of the software.
-	Integration Testing: In this testing, two or more modules which are unit tested are integrated to test i.e., technique interacting components, and are then verified if these integrated modules work as per the expectation or not, and interface errors are also detected.
-	System Testing: In system testing, complete and integrated Software’s are tested i.e., all the system elements forming the system are tested as a whole to meet the requirements of the system.
-	Acceptance Testing: This is a kind of testing conducted to ensure that the requirements of the users are fulfilled before its delivery and that the software works correctly in the user’s working environment.


Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

- Version control systems are a category of software tools that helps in recording changes made to files by keeping a track of modifications done in the code

Version control systems are important in software development in various ways,
-	Enhances the project development speed by providing efficient collaboration,
-	Leverages the productivity, expedites product delivery, and skills of the employees through better communication and assistance,
-	Reduce possibilities of errors and conflicts meanwhile project development through traceability to every small change,
-	Employees or contributors of the project can contribute from anywhere irrespective of the different geographical locations through this VCS,
-	For each different contributor to the project, a different working copy is maintained and not merged to the main file unless the working copy is validated. The most popular example is Git, Helix core, Microsoft TFS,
-	Helps in recovery in case of any disaster or contingent situation,
-	Informs us about Who, What, When, Why changes have been made

Types of version control systems and their features:
- Local Version Control Systems: It is one of the simplest forms and has a database that kept all the changes to files under revision control. RCS is one of the most common VCS tools. It keeps patch sets (differences between files) in a special format on disk. By adding up all the patches it can then re-create what any file looked like at any point in time. 

- Centralized Version Control Systems: Centralized version control systems contain just one repository globally and every user need to commit for reflecting one’s changes in the repository. It is possible for others to see your changes by updating. 

Two things are required to make your changes visible to others which are:  
You commit
They update

The benefit of CVCS (Centralized Version Control Systems) makes collaboration amongst developers along with providing an insight to a certain extent on what everyone else is doing on the project. It allows administrators to fine-grained control over who can do what.

It has some downsides as well which led to the development of DVS. The most obvious is the single point of failure that the centralized repository represents if it goes down during that period collaboration and saving versioned changes is not possible. What if the hard disk of the central database becomes corrupted, and proper backups haven’t been kept? You lose absolutely everything. 

- Distributed Version Control Systems: Distributed version control systems contain multiple repositories. Each user has their own repository and working copy. Just committing your changes will not give others access to your changes. This is because commit will reflect those changes in your local repository and you need to push them in order to make them visible on the central repository. Similarly, When you update, you do not get others’ changes unless you have first pulled those changes into your repository. 

To make your changes visible to others, 4 things are required:  
You commit
You push
They pull
They update
The most popular distributed version control systems are Git, and Mercurial. They help us overcome the problem of single point of failure.

Software Project Management:
Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

- The main role of software project manager is to execute and supervise the software project life cycle and to ensure that it is working as per desired schedule.
Key reponsibilities:- 
- Planning Everything from Execution to Delivery of the software project
- Oversee the Software Development Team
- Delegating Work Effectively
- Monitoring Progress and Tracking Roadblocks
- Managing the Deployment Deliverables
- Establishing proper coordination between project stakeholders.
Challenges faced
-	Unclear and undefined expectations
-	Budget restrictions and changes
-	Time constraint (Impractical/unrealistic deadlines)
-	Scope creep (Changing project requirements and priorities)
-	Poor communication
-	Skills management ie mismatched team skills
-	Finding effective project management software
-	Changing technologies
-	Team conflict/Keeping everyone on the same page
-	Absence of accountability
-	Motivating team members (unrealistic expectations)
-	Steep learning curve
-	Project cancellation
-	Unrealistic estimation
-	High competition
-	Upgrade to a new system (company hesitates to replace them hence they become obsolate)
-	Poor risk management
-	Insufficient quality testing


Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

- Software Maintenance refers to the process of modifying and updating a software system after it has been delivered to the customer.
Several Types of Software Maintenance activities include;
- Corrective Maintenance: This involves fixing errors and bugs in the software system.
- Patching: It is an emergency fix implemented mainly due to pressure from management. Patching is done for corrective maintenance but it gives rise to unforeseen future errors due to lack of proper impact analysis.
- Adaptive Maintenance: This involves modifying the software system to adapt it to changes in the environment, such as changes in hardware or software, government policies, and business rules.
- Perfective Maintenance: This involves improving functionality, performance, and reliability, and restructuring the software system to improve changeability.
- Preventive Maintenance: This involves taking measures to prevent future problems, such as optimization, updating documentation, reviewing and testing the system, and implementing preventive measures such as backups

Software maintenance is essential for several reasons which are listed below:

1. Correction of 'bugs':
The most important part of the service is the correction of errors or in other words 'bugs'. It is very important that the software works without problems. We recommend setting this task as a priority.

This process contains the search for errors in the code and their correction. Problems can occur in hardware, operating systems, or any piece of software. This should be done without prejudice to the remaining functions of the existing software.

2. Improving opportunities for a changing environment:
This part of the service is important for improving the current functions and for making the system compatible for changing the environment.

It extends the capabilities of programs, work patterns, hardware upgrades, compilers, and all other aspects that affect the workflow of the system. Increase the performance of your system using a technically updated solution and regularly using software maintenance services.

3. Remove obsolete functions:
Functionalities that are no longer used and unnecessarily occupy the space in the solution actually reduce the efficiency of the system. Therefore, the removal of obsolete functions is necessary. These user interface and coding elements are removed and replaced with new functions using the latest tools and technologies.
This change makes the system adaptive to cope with changing circumstances.

4. Performance improvement:
Improving system performance is making in order to meet new requirements. Data and encoding constraints as well as reengineering are part of software maintenance. This prevents the solution from being vulnerable. This is not any functionality that works in operations, but it evolves to stop harmful actions, such as hacking.
Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

- Algorithmic bias- Computers cannot understand morality as a concept. When it is not thoroughly checked, its systems can unintentionally show bias or magnify biases that already exist.
For instance, when it was discovered that Google’s image processing engine couldn’t adequately reflect black and brown skin tones in images, the company came under fire for allegedly fostering systematic racism.

Software developers must deliberate potential biases in developing their products. By studying social norms and analyzing their current data, they can prevent wrong assumptions in the collection and use of information.

On the client’s end, they can prevent these mishaps by fostering a culture that encourages employees to speak up if they think a software feature is inappropriate. Being critical of the product helps address algorithmic prejudice.

- Privacy - The domain of privacy partially overlaps with security, which can include the concepts of appropriate use and protection of information. In the digital age, privacy and data protection are major concerns. Software engineers often find themselves at the crossroads of creating innovative applications and respecting user privacy.
For instance, consider a social media app that uses advanced algorithms to suggest friends to users. While this feature enhances user experience, it also raises questions about how the app collects, uses, and stores personal data. If the app collects data without explicit user consent or fails to secure the data adequately, it could lead to serious privacy breaches.

Determining the appropriate scope of data collection is a critical ethical consideration for software engineers, Ensuring the security of sensitive user information is another essential aspect of privacy protection. Software engineers must implement robust security measures, including security testing, to safeguard against unauthorized access, data breaches, and cyberattacks. This includes encryption protocols, secure storage practices, and regular security audits to identify and address vulnerabilities.

- Intellectual property rights are another area where ethical dilemmas often arise. Suppose a software engineer is working on a project and discovers an open-source code that perfectly solves a problem they’ve been struggling with. Should they use the code? If they do, how should they credit the original author? What if the employer insists on not crediting the original author for competitive reasons?

These are tough questions and navigating them requires a deep understanding of both ethical principles and intellectual property laws.

- Accountability entails taking responsibility for the consequences of one's actions and decisions as a software engineer. This includes acknowledging and rectifying mistakes, mitigating harms resulting from technology, and being transparent about the rationale behind design choices. By embracing accountability, developers demonstrate a commitment to ethical conduct and contribute to a culture of trust and accountability within the technology industry.

- Data collection has created additional ethical issues for computer science professionals. Many companies use digital consumer data to help make decisions and it is paramount that this data be collected in an ethical manner.

When data is collected and used without consent, such as in the case of 23andMe's selling of customers' genetic data, consumers feel a loss of trust. CS professionals can prevent this issue by asking for consent for data collection within digital consumer material and websites.

- Addictive design- Every developer yearns to create applications that people love to use -- that's just good UX design. The problem is that some teams craft apps that people love too much. There is an ethical concern about the role of digital platforms, such as social media.

"As long as social media companies profit from outrage, confusion, addiction and depression, our well-being and democracy are at risk," argue critics like Tristan Harris of the Center for Humane Technology. Harris notably went viral while at working Google, with a presentation about the push for addictive technology design and companies' moral responsibility in society.

Striking an ethical balance between products consumers love and products that hijack their attention is more an art than a science

- Protection of Customer Data- Numerous websites’ services exist in large part to gather your information. 

Take Google for instance. Here is some of the information it has about you: where you've been, your search history, applications you’ve used and with whom you use them, your YouTube history, etc. Google even allows you to download all the data they have about you—in all honesty, it would fill a huge number of Word documents!

What happens if the government or another legal entity demands information on clients from the information you’ve gathered with software you built? Where does your moral commitment lie? Have you conveyed your strategies clearly to your clients, and how have you secured their information?

Personal data security is one of the biggest concerns in the digital world because of the sensitive information that your clients trust you with. Personal information is a point of interest for many organizations, from national security to cybercriminals. The companies that don’t have policies in place for how to act in these kinds of situations place their clients at risk by not informing them of how their data will be treated.

- Be honest- Falsely advertising features or exaggerating the performance quality is unethical. Be straightforward and truthful while describing your goods. Inform the audience if the vision changes. Inform stakeholders as soon as there are updates or modifications to the software. To ensure that the product will be utilized as intended, create policies with the help of other teams inside your organization

- Weak security- The software industry is prone to security issues. Developers need further education to learn and implement proper security practices. However, these kinds of training are often limited to cybersecurity-specific seminars.

Software experts have to take the initiative in learning security protocols. Fortunately, there are now plenty of development resources to strengthen one’s skills and knowledge about cybersecurity. As a software developer, it is your duty to implement and update your project with standardized security.

Depending on the type of website or application you’re developing, there are now protection guidelines you can refer to. For example, if you’re developing a health application, you can refer to the Payment Card Industry Data Security Standard (PCI DSS) and the Health Insurance Portability and Accountability Act (HIPPA).


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
