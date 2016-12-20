MVP: CI Installer
- As a BonnyCI Administrator, I can run and deploy the BonnyCI environment in production and locally in a VM or Container.

MVP: Enrollment
- As a Python project developer, I know how to use BonnyCI with my project by following instructions in the BonnyCI documentation.
- As a BonnyCI Administrator, I can respond to new enrollment requests from potential BonnyCI users within a reasonable amount of time. I understand how to set up new projects to use BonnyCI by following the instructions in the BonnyCI documentation.

MVP: Job Runner
- As a Python Project Developer, I can use BonnyCI to verify my changes before merging them into master.

MVP: Triggered Events
(Part of MVP: Job Runner)
- As a Python Project Developer, when I indicate my Github Pull Request is ready, BonnyCI picks up my change.

MVP: Job Resource Management
(Part of MVP: Job Runner)
- As a Python Project Developer, my changes are staged in an environment defined by me in a configuration file in my respository and set up and hosted by BonnyCI.

MVP: Test Execution
(Part of MVP: Job Runner)
- As a Python Project Developer, my changes are tested at the tip of the master branch independently using tests I've provided in my repository.
- As a Python Project Developer, my changes are tested with other changes in the same repository, at the tip of master in the order they are committed, that I've identified as being dependent using tests I've provided in my repository.

MVP: Job Completion Feedback
(Part of MVP: Job Runner)
- As a Python Project Developer, when a job finishes, I can see whether it passed or failed and why. The logs for my test runs are made available to me to view so I can debug test failures, improve upon my tests and/or my code, and provide feedback to the BonnyCI project when reporting bugs.

MVP: Gating
- As a Python Project Developer, my changes are merged by BonnyCI when BonnyCI indicates the staged merges have passed tests.

MVP: Cross-Project Dependencies
- As a Python Project Developer, my changes are tested with other changes I've identified in outside repositories using tests provided in both repositories. My changes and the other changes are tested at the tip of their master branches.

MVP: Monitoring
- As a BonnyCI Administrator, I am aware of the status of BonnyCI in production and am notified of any outages or performance degradation. I can identify potential bottlenecks and prevent future outages by viewing BonnyCI performance and resource usage over time. I can identify the root cause of outages, performance degradation, or other failures through searching historical log data or by watching real time logs.

MVP: Operations
- As a BonnyCI Administrator, I am able to administer and maintain a Bluebox-hosted BonnyCI environment that supports our developer community. I am able to restore the BonnyCI environment without minimal state or data loss.

MVP: CI User Metrics
- As a BonnyCI Contributor, I am in communication with open source communities willing to help beta test BonnyCI. I understand the CI-specific needs and pain points in these communities which we have considered in the BonnyCI implementation (and these communities are aware of how we've considered their needs). I have knowledge of key CI usage factors in an n > 20 sample of open source projects using TravisCI and have incorporated that data into BonnyCI's feature development. I understand how projects are using BonnyCI through project usage metrics and feedback from user-filed issues, surveys, and interviews. I am able to measure whether BonnyCI is successful at addressing the needs identified during initial customer research.

MVP: Documentation
As a BonnyCI Administrator, I know how to configure my project to use BonnyCI, set up my target environments, and define the jobs I want to run by following instructions in the BonnyCI documentation.

MVP: Project Management
- As a contributor to BonnyCI, I can communicate with other BonnyCI contributors through IRC and Github. I know the status of work being done on the project. I understand what features we are focused on developing and I can easily pick up tasks that I know are contributing to these goals. I am aware of the Open Source Licensing agreements required of me in order to contribute.
- As an observer of the BonnyCI project, I know what the team is working on, the current high level priorities, and how far along the team is in achieving these goals.
