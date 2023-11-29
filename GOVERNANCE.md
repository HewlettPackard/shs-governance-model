# Governance for Slingshot at HEWLETT PACKARD ENTERPRISE (HPE)

This document defines the project governance for Slingshot

## Overview

**Slingshot** is committed to building an open, inclusive, productive,
and self-governing open source community focused on build a high-quality integration solution
for HPE HPC computing solutions. The community is governed by this document with the goal of
defining how community should work together to achieve this goal.

## Code Repositories

The following code repositories are governed by Slingshot community and
maintained under the Slingshot namespace.

* **[product](https://github.hpe.com/HewlettPackard/product):** Main Product codebase. [ this is an example]
<!-- TODO add a listing of all repositorie -->

## Decision Making

Ideally, all project decisions are resolved by consensus. If impossible, any
maintainer may call a vote. Unless otherwise specified in this document, any
vote will be decided by a majority of maintainers. Final decision is subject to HPE's purview

## Proposal Process

One of the most important aspects in any open source community is the concept
of proposals. Large changes to the codebase and / or new features should be
preceded by a proposal in our community repo. This process allows for all
members of the community to weigh in on the concept (including the technical
details), share their comments and ideas, and offer to help. It also ensures
that members are not duplicating work or inadvertently stepping on toes by
making large conflicting changes.

The project roadmap is defined by accepted proposals and existing defined work.

Proposals should cover the high-level objectives, use cases, and technical
recommendations on how to implement. In general, the community member(s)
interested in implementing the proposal should be either deeply engaged in the
proposal process or be an author of the proposal.

### Proposal Lifecycle

The proposal PR can be marked with different status labels to represent the
status of the proposal:

* **New**: Proposal is just created.
* **Reviewing**: Proposal is under review and discussion.
* **Accepted**: Proposal is reviewed and accepted (either by consensus or vote).
* **Rejected**: Proposal is reviewed and rejected (either by consensus or vote).

## Lazy Consensus

To maintain velocity in a project as busy as [insert project name here], the concept of [Lazy
Consensus](http://en.osswiki.info/concepts/lazy_consensus) is practiced. Ideas
and / or proposals should be shared by maintainers via
GitHub with the appropriate maintainer groups tagged. Out of respect for other contributors,
major changes should also be accompanied by an email on the
[insert project name here] dev [mailing list](email@org.com). Author(s) of proposal, Pull Requests,
issues, etc.  will give a time period of no less than five (5) working days for
comment and remain cognizant of popular observed world holidays.

Other maintainers may chime in and request additional time for review, but
should remain cognizant of blocking progress and abstain from delaying
progress unless absolutely needed. The expectation is that blocking progress
is accompanied by a guarantee to review and respond to the relevant action(s)
(proposals, PRs, issues, etc.) in short order.

Lazy Consensus is practiced for all projects in the [insert project name here] org, including
the main project repository, community-driven sub-projects, and the community
repo that includes proposals and governing documents.

Lazy consensus does _not_ apply to the process of:

* Removal of maintainers

## Updating Governance

All substantive changes in Governance require a supermajority agreement by all maintainers or by HPE legal.

## Contributor Ladder
<!---
This section was dervied from the CONTRIBUTOR_LADDER.md which was originally created in the CNCF project at https://github.com/cncf/project-template/blob/main/CONTRIBUTOR_LADDER.md. This comment provides attribution of that work as defined under the Apache 2.0 license.
-->

* [Contributor Ladder](#contributor-ladder)
    * [Community Participant](#community-participant)
    * [Contributor](#contributor)
    * [Reviewer](#reviewer)
    * [Maintainer](#maintainer)
* [Inactivity](#inactivity)
* [Involuntary Removal](#involuntary-removal-or-demotion)
* [Stepping Down/Emeritus Process](#stepping-downemeritus-process)
* [Contact](#contact)

Hello! We are excited that you want to learn more about our project contributor ladder! This contributor ladder outlines the different contributor roles within the project, along with the responsibilities and privileges that come with them. Community members generally start at the first levels of the "ladder" and advance up it as their involvement in the project grows.  Our project members are happy to help you advance along the contributor ladder.

Each of the contributor roles below is organized into lists of three types of things. "Responsibilities" are things that a contributor is expected to do. "Requirements" are qualifications a person needs to meet to be in that role, and "Privileges" are things contributors on that level are entitled to.

### Supermajority

A supermajority is defined as two-thirds (2/3) of members in the group.
A supermajority of [Maintainers](#maintainer) is required for certain
decisions. Voting on decisions can happen on the mailing list, GitHub, Slack, or email when appropriate. Maintainers can either vote "agree", "disagree", or "abstain". A vote passes when supermajority is met. An abstain vote equals not voting at all.

## Community Participant

<!--This role spells out what's expected of general community participants.  This is the lowest
level of participation in the project, and as such many projects don't bother to
define it and leave this section out.-->
<!--TODO: project leads to fill in exact details of this role for your project-->
Description: A Community Participant engages with the project and its community, contributing their time, thoughts, etc. Community participants are usually users who have stopped being anonymous and started being active in project discussions.

* Responsibilities:
    * Must follow the [code of conduct](CODE_OF_CONDUCT.md)
* How users can get involved with the community:
    * Participating in community discussions
    * Helping other users
    * Submitting bug reports
    * Commenting on issues
    * Trying out new releases
    * Attending community events
<!--
    * [TODO: Other examples of non-contribution participation]
-->

## Contributor

<!-- This role describes people who have just started contributing, or who contribute occasionally but don't participate in project governance or have defined responsibilities.  Usually projects define either this level or Community Participant, but not both.  If you don't define this role, make sure to copy over its requirements to Organization Member -->
<!--TODO: project leads to fill in exact details of this role for your project-->
Description: A Contributor contributes directly to the project and adds value to it. Contributions need not be code. People at the Contributor level may be new contributors, or they may only contribute occasionally.

* Responsibilities include:
    * Must follow the [code of conduct](CODE_OF_CONDUCT.md)
    * Follow the <!--TODO: project leads to fill in exact details of this role for your project-->
    * Follow the project contributing guide
* Requirements (one or several of the below):
    * Report and sometimes resolve issues
    * Occasionally submit PRs
    * Contribute to the documentation
    * Show up at meetings, takes notes
    * Answer questions from other community members
    * Submit feedback on issues and PRs
    * Test releases and patches and submit reviews
    * Run or helps run events
    * Promote the project in public
    * Help run the project infrastructure
<!--
    * [TODO: other small contributions]
-->
* Privileges:
    * Invitations to contributor events
    * Eligible to become an Organization Member

## Reviewer
<!-- Some projects have CI/CD systems that allow for designating people as official reviewers, whose reviews count towards a PR being accepted into the project.  Other projects offer reviewers specific recognition and status.  This role is for either of those kinds of projects. Smaller projects will not use it.-->
<!--TODO: project leads to fill in exact details of this role for your project-->
Description: A Reviewer has responsibility for specific code, documentation, test, or other project areas. They are collectively responsible, with other Reviewers, for reviewing all changes to those areas and indicating whether those changes are ready to merge. They have a track record of contribution and review in the project.

Reviewers are responsible for a "specific area." This can be a specific code directory, driver, chapter of the docs, test job, event, or other clearly-defined project component that is smaller than an entire repository or subproject. Most often it is one or a set of directories in one or more Git repositories. The "specific area" below refers to this area of responsibility.

Reviewers have all the rights and responsibilities of an Organization Member, plus:

* Responsibilities include:
    * Following the reviewing guide
    * Reviewing most Pull Requests against their specific areas of responsibility
    * Helping other contributors become reviewers
* Requirements:
    * Experience as a Contributor for at least 3 months
    * Is an Organization Member
    * Has reviewed, or helped review, at least 10 Pull Requests
    * Has analyzed and resolved test failures in their specific area
    * Has demonstrated an in-depth knowledge of the specific area
    * Commits to being responsible for that specific area
    * Is supportive of new and occasional contributors and helps get useful PRs in shape to commit
* Additional privileges:
    * Has GitHub or CI/CD rights to approve pull requests in specific directories
    * Can recommend and review other contributors to become Reviewers

The process of becoming a Reviewer is:
<!-- TODO: define your exact process here.  What's below is given as an example process for a project that uses Owners files and has defined teams for each project area -->
1. The contributor is nominated by opening a PR against the appropriate repository, which adds their GitHub username to the OWNERS file for one or more directories.
2. At least two members of the team that owns that repository or main directory, who are already Approvers, approve the PR.

## Maintainer
<!-- In the simplest and most common project structures, projects have a single pool of "maintainers" who are collectively responsible for the entire project.  This example defines that role for your project.  If your project has a more complex structure, see the list of specific maintainer roles you might want to define, below. -->
<!--TODO: project leads to fill in exact details of this role for your project-->

Description: Maintainers are very established contributors who are responsible for the entire project. As such, they have the ability to approve PRs against any area of the project, and are expected to participate in making decisions about the strategy and priorities of the project.

A Maintainer must meet the responsibilities and requirements of a Reviewer, plus:

* Responsibilities include:
    * Reviewing PRs that involve multiple parts of the project
    * Mentoring new Reviewers
    * Writing refactoring PRs
    * Participating in maintainer activities
    * Determining strategy and policy for the project
    * Participating in, and leading, community meetings
* Requirements
    * Experience as a Reviewer for at least 3 months
    * Demonstrates a broad knowledge of the project across multiple areas
    * Is able to exercise judgment for the good of the project, independent of their employer, friends, or team
    * Mentors other contributors
    * Can commit to spending at least 40 hours per month working on the project
* Additional privileges:
    * Approve PRs to any area of the project
    * Represent the project in public as a Maintainer
    * Have a vote in Maintainer decision-making meetings
<!--    * Communicate with the [TODO] on behalf of the project -->


Process of becoming a maintainer:
<!-- TODO: this process will vary widely across projects, both because of project code structure, and because of project governance.  For example, in some projects the Steering Committee approves new Maintainers.  What's below is just an example from a simple project in which the maintainers are also the project leaders, and which uses GitHub OWNERS files. -->
1. Any current Maintainer may nominate a current Reviewer to become a new Maintainer, by opening a PR against the root of the project repository adding the nominee as an Approver in the OWNERS file.
2. The nominee will add a comment to the PR testifying that they agree to all requirements of becoming a Maintainer.
3. A supermajority of the current Maintainers must then approve the PR.

<!-- Some projects might add a limit on the percentage of maintainers from a specific organization here.  Obviously this only works if your project has
reached the stage where you have a reasonable diversity of maintainers.  At that point, you can add a statement like this:
The maintainers will avoid nominating new maintainers from any organization that already employs 50% or more of existing maintainers
-->

## Inactivity
<!--TODO: project leads to fill in exact details for how you measure inactivity for your project-->
It is important for contributors to be and stay active to set an example and show commitment to the project. Inactivity is harmful to the project as it may lead to unexpected delays, contributor attrition, and a lost of trust in the project.

* Inactivity is measured by:
    * Periods of no contributions for longer than 6 months
    * Periods of no communication for longer than 6 months
* Consequences of being inactive include:
    * Involuntary removal or demotion
    * Being asked to move to Emeritus status

## Involuntary Removal or Demotion

Involuntary removal/demotion of a contributor happens when responsibilities and requirements aren't being met. This may include repeated patterns of inactivity, extended period of inactivity, a period of failing to meet the requirements of your role, and/or a violation of the Code of Conduct. This process is important because it protects the community and its deliverables while also opens up opportunities for new contributors to step in.

<!-- TODO: replace with your method of removing/demoting contributors.  If you have a formal governance structure, this would be a good place to assign this to your governance, such as a Steering Committee.
Again, the example below is for a project without formal governance except the maintainers.-->
Involuntary removal or demotion is handled through a vote by a majority of the current Maintainers.

## Stepping Down/Emeritus Process
If and when contributors' commitment levels change, contributors can consider stepping down (moving down the contributor ladder) vs moving to emeritus status (completely stepping away from the project).

Contact the Maintainers about changing to Emeritus status, or reducing your contributor level.

## Contact
* For inquiries, please reach out to:
    *  <!-- TODO: fill in contact info for appropriate group or person for contributor mentorship-->

<!-- Definitions -->
