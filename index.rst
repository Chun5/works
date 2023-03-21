===============
✍️ Writings
===============

1. WorldFirst enterprise solution API specification
----------------------------------------------------
::

  WorldFirst enterprise solution is developed to boost the financial inclusion by driving a
  significant increase in digital payment across the globe. I cooperate with developers and
  system admins, then write API specifications for the payment associated modules.


My works
============
- `API specification <https://developers.worldfirst.com.cn/docs/alipay-worldfirst/worldfirst_enterprise_solution/submit_trade_order>`_



2. WorldFirst developer center user manual
------------------------------------------
::

  WorldFirst developer center is a platform for developers and partners to build, test, and
  launch WorldFirst products. I write this manual to guide developers through the integration
  process and introduce tools to facilitate their integration with WorldFirst.


My works
============
- `User manual <https://developers.worldfirst.com.cn/docs/alipay-worldfirst/overview/home>`_
 
 

3. Zyla documentation center
-----------------------------
::

  Zyla is developed for cross-border businesses trading in multiple currencies. I design the
  information architecture for the documentation center, draw API integration workflow chart,
  and write user manual. I also work with US team members to publish the global documents.
  
  

My works
=========
- `Documentation center IA <https://developers.zyla.com/docs/>`_


| 
============
📚 Learning
============

IBM DQTI
-----------------------------------------
Developing Quality Technical Information

Technical information continues to evolve
============================================
::
    
  Information that you put in an installation guide is not appropriate in an application
  development guide. Different interface display mechanisms require different types of
  information.
  
  When you become more adept at creating meaningful and effective embedded assistance and
  delivering it progressively, you create a better customer experience and become a more
  valuable member of your product team.


::
  
  We are more involved with product design and user interface development, which means that we
  must be involved earlier than ever in the development cycle. The problem with the historic 
  waterfall development process is that downstream teams have very little chance to change 
  anything that happened upstream. Develop ever smaller chunks of information to address the 
  changing needs of users.


::

  An overwhelming majority of customers report that information quality both affects their view 
  of product quality and their overall product satisfaction. Information quality also has a 
  significant impact on customers' buying decisions.
  
  Almost always, users seek answers to specific questions and don't want to read a book from
  beginning to end to find those answers. Quality information addresses users where they are.
  Writers must apply their own skills and expertise based on solid research and proven methods.
  


QTI's characteristics:
======================
- **Easy to use**
::
  
   1. Task orientation: A focus on helping users do tasks that support their goals
   
   2. Accuracy: Freedom from mistake or error; adherence to fact or truth
   
   3. Completeness: The inclusion of all necessary parts-and only those parts

- **Easy to understand**
::

   1. Clarity: Freedom from ambiguity or obscurity; using language clear to understand
   
   2. Concreteness: The inclusion of appropriate examples, scenarios, analogies, and graphics
   
   3. Style: Correctness and appropriateness of writing conventions and of words and phrases
  
- **Easy to find**
::

   1. Organization: A coherent arrangement of parts that makes sense to the user
   
   2. Retrievability: The presentation of information in a way that enables users to find 
      specific items quickly and easily
   
   3. Visual effectiveness: Attractiveness and enhanced meaning of information through the use of
      layout, illustrations, color, typography, icons, and other graphical devices



TW's characteristics:
========================
::

  1. Technical document is written for the specific audience.
  
  2. Technical writing helps audience accomplish tasks or resolve problems. It is different
     from literature works.
  
  3. TW focuses on how the words are presented and organized, like the font, color, alignment.
     Use more brief sentences and lists.



|
Reading list
=============

 1. IBM Style Guide - The Conventions for Writers and Editors
 2. Microsoft Style Guide
 3. A Practical Guide to Information Architecture
 4. Understanding Your Users - A Practical Guide to User Research Methods
 5. Managing Enterprise Content
 6. Content Strategy for the Web
 7. Docs for Developers - An Engineer’s Field Guide to Technical Writing
 8. Handbook of Technical Writing
 9. SAP Style Guide For Technical Communication
 10. `TCBOK <https://www.tcbok.org>`_ (Technical Communication Body Of Knowledge)
 11. `reStructuredText reference <https://docutils.sourceforge.io/docs/user/rst/quickref.html>`_


|
==============
⚙️ Methodology
==============

DITA
-----
Darwin Information Typing Architecture is an international standard released by OASIS on how to write and publish technical information.
DITA Topic is the minimum, independent, and reusable content unit. One topic, one subject.

**DITA Topic information type**

- Concept: what is
- Task: how to

  + title
  + shortdesc
  + prolog
  
    - metadata
    - keyword
    
  + taskbody
    
    * prereq
    * context
    * step (cmd, info/substeps/tutorialinfo, stepresult)
    * result
    * example
    * postreq

  + related-links

- Troubleshooting
- Reference


**DITA Map**
::

  DITA maps are documents that organize topics and other resources into structured collections
  of information. DITA maps specify hierarchy and the relationships among the topics; they also
  provide the context in which keys are defined and resolved. DITA maps should have .ditamap 
  file extensions.

  Maps draw on a rich set of existing best practices and standards for defining information 
  models, such as hierarchical task analysis. They also support the definition of 
  non-hierarchical relationships, such as matrices and groups, which provide a set of 
  capabilities that has similarities to Resource Description Framework (RDF) and ISO topic maps.

  DITA maps impose an architecture on a set of topics. Information architects can use DITA maps 
  to specify what DITA topics are needed to support a given set of user goals and requirements; 
  the sequential order of the topics; and the relationships that exist among those topics. 
  
::

  DITA maps use <topicref> elements to reference DITA topics, DITA maps, and non-DITA resources,
  for example, HTML and TXT files. The <topicref> elements can be nested or grouped to create 
  relationships between the referenced topics, maps, and non-DITA files; the <topicref> elements
  can be organized into hierarchies in order to represent a specific order of navigation or 
  presentation.

  DITA maps often represent a single deliverable, for example, a specific Web site, a printed 
  publication, or the online help for a product. DITA maps also can be subcomponents for a 
  single deliverable.


Other technical standards for structured writing
::

  DocBook: a structured standard for books, used in digital publishing field.
  
  S1000D: a general international standard for technical publications, used in aviation, 
  aerospace, military industry.




|
TW Process
----------
  1. Demand analysis: user task analysis
  
  2. Information architecture design
   - storytelling mode
   - progressive presentation
   - easily-searchable content
   
  3. Technical writing: write in reStructuredText, Markdown, markdown-dita.
  4. Quality control: review, test, and verify the document
  
  5. Publishment: PDF, website, ePub, Android, iOS, etc.
  6. delivering
    - print in the box
    - article on the website and app
    - embedded assistance in a software
  7. Maintenance: update as per market demand, product and technology.



|
=========
🧰 Tools
=========

1. Language
------------

reStructuredText
==================

- reStructuredText is a plaintext markup language used in static site generators like Sphinx.
- This page is written in reStructuredText language.
- `Reference <https://docutils.sourceforge.io/docs/user/rst/quickref.html>`_



Markdown
==========

Markdown is a lightweight markup language for creating formatted text using a plaintext editor.
  
+------------+----------------------------------------+
|  Syntax    |              Description               |
+============+========================================+
| # content  |  1st level title                       |
+------------+----------------------------------------+
| ## content |  2nd level title                       |
+------------+----------------------------------------+
|### content |  3rd level title                       |
+------------+----------------------------------------+
| > content  |  quotation effect                      |
+------------+----------------------------------------+



XML
======

- eXtensible Markup Language is a markup language used for storing and transporting data.
- Custom tag is a must and case sensitive.
- `Reference <https://www.w3school.com.cn/xml/xml_syntax.asp>`_


**XML file sample**

::

  <?xml version="1.0" encoding="UTF-8"?>
 
  <letter>  
    <to> Catherine </to>
    <from> Justin </from>
    
    <heading> I miss you </heading>
    <body> Hope everything goes well and take care of yourself. </body>    
  </letter> 



HTML
=======

HyperText Markup Language is the standard markup language for Web pages.

+------------+----------------------------------------+
|    Tag     |              Description               |
+============+========================================+
|    <a>     |  Defines a hyperlink                   |
+------------+----------------------------------------+
| <article>  |  Defines an article                    |
+------------+----------------------------------------+
|  <audio>   |  Defines embedded sound content        |
+------------+----------------------------------------+
|    <b>     |  Defines bold text                     |
+------------+----------------------------------------+
| <basefont> |  Specifies a default color, size, and  |
|            |  font for all text in a document       |
+------------+----------------------------------------+
|<blockquote>|  Defines a section that is quoted from |
|            |  another source                        |
+------------+----------------------------------------+
|   <body>   |  Defines the document's body           |
+------------+----------------------------------------+
|    <br>    |  Defines a single line break           |
+------------+----------------------------------------+
|<h1> to <h6>|  Defines HTML headings                 |
+------------+----------------------------------------+
|   <img>    |  Defines an image                      |
+------------+----------------------------------------+
|  <option>  |  Defines an option in a drop-down list |
+------------+----------------------------------------+
|  <select>  |  Defines a drop-down list              |
+------------+----------------------------------------+
|    <ul>    |  Defines an unordered list             |
+------------+----------------------------------------+
|  <video>   |  Defines embedded video content        |
+------------+----------------------------------------+


::

  HTML vs. XML
  
  1. HTML does not have custom tags while XML does.
  
  2. HTML's syntax is loose, and XML's syntax is strict with paired tags.
  
  3. HTML is used to display data, and XML is to transmit and store data.
  

  
|
2. Content and document management tool
----------------------------------------
::

  1) Sphinx: Create intelligent and beautiful documentation easily by reStructuredText.

  2) Visual Studio Code: a code editor redefined/optimized for building/debugging Apps.

  3) Document Type Definition (DTD) template: define/control topics' structure/style.


|
3. Project management tool
----------------------------
::

  1) Jira: Manage and track projects and issues.

  2) Slack: Communicate and collaborate with teammates.

  3) Box: Store and manage your cloud content.



|
================
🌟 Inspiration
================

Discussion
-----------

- *Will technical writers be replaced by AI?*

::

  My answer is no in the recent decade, but it could happen in 2050 when half of TW disappear.
  
  Technical writers could hardly be replaced by AI completely, no matter how advanced AI brain
  is trained. It is a progressive process AI infinitely approaches to replacing TW.
  
  From the historic perspective, it is slow to witness an occupation disappears, especially the
  occupation that lives a much long time and needs human wisdom as well as creativity.


::

  Besides, AI does have bugs and weakness in wording, rhetoric, contextual analysis, etc. This
  implies that the current AI is not ready for completing high-level writing jobs.
  
  There are still a large proportion of companies and individuals do not believe in AI's ability
  in writing technical documents, though they are much easier than suspense novel for AI.
  Moreover, information security and AI's understanding on our real requirements should be 
  carefully considered.
  
  Concerning creative writing, such as suspense novel, for now, AI is not competent to do this 
  kind of work, or deal with it satisfactorily. Although we can see AI is producing articles to 
  the public and people do not recognize that they are written by computers.
  

::

  But the days get closer. It is worth noting that ChatGPT, the household AI application,
  becomes the significant turning point to TW' career. Closer, no doubt.
  
  Probably in the coming decade, we can see more and more writing jobs will be taken over by AI.
  Meanwhile, we technical writers, or some of us will still be working on our familiar tasks,
  such as writing user guides or API specifications. 

  A well-worn question is raised: do you believe humankind will be manipulated by machines?
  
  

- *What do we consider when reviewing a technical document?*

::

  When reviewing a technical document, need I consider the writing style? If yes, which style?
  How could I ensure that I'm not controlled by my strong bias when reviewing the document?

  1. Exclude personal factors, like emotion, preference, and interests.
  
  2. What is the audience of this document?
  
  3. If I were the user, am I clear to do tasks?
  
  4. Can I search what I want easily?
  

- *How big is the communication gap between developers and writers?*

::

  1. The unsettled problems, as well as ignored issues, cause the big communication gap today.
  
  2. A new role Linguistic Lark is born to resolve the communication problem between Dev and TW.
  
  3. How to deploy the Dev-writer?


|
New deliverables of TW
-----------------------

- **Chat bot**

::

  The key points of an intelligent chat bot are a rich and elaborated repository, as well as 
  the code design of the bot program.
  
  
- **Augmented reality (AR)**

::

  The creative AR material supports user interaction, and act as a virtual mentor. This reduces
  users' learning barrier and motivates them to learn how-to significantly.
  
  Car companies release AR assistance systems. With a mobile phone, one user can scan the car 
  components to access the corresponding information, instead of reading the massive information
  in the user manual.
  
  
  
- **Software and hardware interactive assistance**

::

  Connected with the body, hardware can sense the user's operations.
  For example, Ninebot, a balance electric vehicle, guides users to install an application.
  
  Once connected with Ninebot, the app prompts users to move as required, and decides by the 
  sensor if the movement is right. The interactive mode gets started quickly and reduces users'
  reading workload a lot.



- **Further consideration**

::

  1. AR glasses evaluation
  
  2. Usage senario of AR user guide
  
  3. The content design for AR, like audio, menu and option.
  


| 
Technical writing improvement
------------------------------

- **What is a good technical document?**
::

  1. 
  
  2.
  
  3.



- **Learn more to ensure sufficient input.**

::

  Good habits for writing:
  
  1. Keep on reading the subject-specific materials.
  
  2. Learn, note, then clear your collections.
  
  3. Make the plan and do it at your own pace.

::

  Learning resources:
  
  1. Professional books on technical writing, such as DQTI.
  
  2. Official web pages of product documentation center, like IBM, Microsoft, Google.
  
  3. Standard documents of organizations or associations, like ISO.
  
  4. Trends towards technical communication field
  


- **Write in a friendly style.**
::

  1. Use a friendly layout and well presented typeset.
  
  2. Consider how to improve UI copywritings when using products.

  3. 



| 
TW's value
------------

- **Technical documents create great value for companies.**

::

  1. Company asset: accumulated digital asset and knowledge base for reference.
  
  2. Cost cut: With self-help user manual, a company's labor cost gets lower.
  
  3. Company image: act like a business card to show a company's image.

  4. Entrance to products: many users get to know a product from its user manual.


- **Value in a product's life cycle**

::

  1. Product strategy: help build the product or service strategy.
  2. Product design: help acquire market demand and target group.
  
  3. Development and production: meet users' needs of information about product's function.
  4. Sales: lead potential customers to find the product's information.
  5. Product implementation: offer information on installing/implementing/integrating products.
  6. Product use: help users use the product and resolve the problems.
  
  7. After-sale service: help technical support troubleshoot the issues.
  8. Track feedbacks: follow up for continuous improvement.




| 
===========
✨ Career
===========

- **Career path**

 1. Senior technical writer
  
 2. Content manager
  
 3. Information architect
  
  

- **Experience sharing**
  
 1. From 
  
 2. From 
  


- **Society and organization**

 1. `tekom <https://www.technical-communication.org>`_
 2. `STC <https://www.stc.org>`_
 3. 
 4. `OASIS Open <https://www.oasis-open.org>`_


  


|
=========
🌌 About
=========

This blog is written by Austen to share learning outcome and ideas on technical writing.
Please bookmark or share this page https://z.rtfd.io if you like it.

   If it is clear to me, it should be clear to them by technical writing.
   
   | --- Austen, a technical writer from China

Have a beautiful day. ☕


