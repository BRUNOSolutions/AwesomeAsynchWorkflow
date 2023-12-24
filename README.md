## Why curated AWESOME lists and RSS feeds matter so much

*We'd never keep up without curated reading lists that help us build RSS feeds ... especially in rapidly evolving industries with lots of investment driving R&D and new theoretical work.*

A rapidly developing research and development space such as eGPUs/eTPUs connectivity illustrates why. But, more generally, it is important to curate repositories of lists of AWESOME blogs and online publications by independent thinkerers, industry experts and research institutions ... by following these curated lists, or the abstracts from linked RSS feeds, one is better able to an eye on key things.  

So it's not JUST researchers/labs involved that developing as well as the conferences and workshops focused on HPC, cloud computing, and server technologies, as these often serve as a place for new ideas in cutting-edge research and development in eGPU/eTPU connectivity to emerge ... we ALSO continue to learn from [Archetypal Repository](https://github.com/sindresorhus/awesome) which laid the foundation for the broader archetypal example of listification in [the Awesome Lists of Awesome Lists](TheArchetype.md).

## Awesome Asynch Workflow Tools 

We will focus this AWESOME lists on various patterns, methodologies, practices and tools used in the development of asynchronous workflows ... we are our own most demanding customer for what is a particularly recursive topic, since we are all about using asynchronous workflows as we [dogfood](https://en.wikipedia.org/wiki/Eating_your_own_dog_food) the asynchronous workflows that we will use to [dogfood](https://en.wikipedia.org/wiki/Eating_your_own_dog_food) new asynchronous workflows.

### Software Development

#### Feature Branch Workflow

Developers work on independent branches for specific features, merging them into the main branch once complete. This fosters collaboration while minimizing conflict.

#### Kanban Boards: 

Beyond using GitHub Projects ... what are some OPEN SOURCE ways that teams visualize and track individual tasks on virtual boards, facilitating clear communication and ownership.

#### Test-Driven Development. Design-For-Test (DFT) and Observability Engineering: 

SHIFT your thinking LEFT ... think of observability engineering [including security aspects of testing a user's environment for intruders] as being akin to hardware development, rather than an afterthought ...incorporate a DFT strategy into the architecture of your workflow ... consider adapting ideas from hardware development into your software development ... think about things such as hierarchical DFT with Memory Built-In Self Test (MBIST), IJTAG/TAP and Hi-Speed IO, traceable requirements from fundamental DFT logic, with pre-silicon verification to Co-work with test engineers post silicon ... shift the testing left, and make *copilot* the design process by understanding how boundary scan, scan chains, DFT Compression, Logic Built-In Self Test (BIST), Test Access Point (TAP) controller, Clock Control block, and other DFT IP blocks are used in hardware. Design in the observability and controllability of the design to enable testability; consider why it's so important to insert and hook up MBIST logic including test collar around memories, MBIST controllers, eFuse logic and connect to core and TAP interfaces.
Document DFT architecture and test sequences, including boot-up sequence associated with test pins. Make it almost effortless to test the design by using the DFT architecture to control the design and test sequences; complete all Test Design Rule Checks (TDRC) and Design changes to fix TDRC violations to achieve high test quality which can support to the traceability and analytics used to improve customer use and interactivity.

#### Code Reviews: 

Developers asynchronously review each other's code after pull requests, ensuring quality and knowledge sharing ... not just tools like Gerrit, but the best practices for Gerrit.

### Project Management

#### Issue Tracking Systems

Organize tasks, assign priorities, and track progress asynchronously through platforms like Jira or Asana.

#### Collaborative Documentation:

Tools like Notion or Confluence enable team members to contribute to shared documents and wikis at their own pace.

#### Meeting Summaries and Action Items: 

Share concise summaries and action items from meetings via email or internal platforms, ensuring information accessibility.

### Creative Collaboration

#### File Sharing and Version Control: 
Beyond utilizing best practices for platforms like Dropbox or Google Workspace, there's a lot of Git and Mercurial to cover.

#### Feedback Tools: 

Tools like Figma or Adobe XD allow asynchronous feedback on design mockups and prototypes, promoting iterative improvement.

#### Messaging and Communication Platforms:

Slack, Discord, or Telegram enable quick updates, file sharing, and discussions even when team members are offline.

### Miscellaneous Applicable Practices / Relevant Technologies

#### Clear Communication BEST PRACTICES

Regardless of the workflow, establishing clear expectations, deadlines, and communication channels is crucial for asynchronous success.

#### Transparency and Documentation

Sharing project progress, decisions, and rationale through documentation enables everyone to stay informed even when working asynchronously.

#### Tools and Technology

Leverage appropriate tools and platforms to facilitate smoother asynchronous collaboration and information sharing.  
