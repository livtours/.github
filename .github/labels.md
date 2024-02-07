<div style="display: grid; margin: 2em;">
    <img src="https://livtours.com/wp-content/themes/livtours/images/logo-white.svg" style="width: 28vw; height: 10vh;" alt="Livtours logo">
</div>

---

# Github Labels
> ###### Documentation : Overview of CRUD flow utilized throughout projects

---

## Decision-Making Principles

- Github labels are used for both Issues and PR’s ( Pull-Requests), therefore the label context should be agnostic where applicable.

- Labels should be lowercase. It’s easier to type and ensures less competition between label names.

- Labels and their associated colour should have a logical connection that is intuitive at-a-glance.

- Where labels are relevant to both Issues and PRs, a prefix will be omitted ( eg. *:* )

- Where label should only be utilized when referencing an issue, prefix of issue:* <span style="color: #EF927B;">must</span> be added

- This is the same when referencing only a PR ( eg. pr:*)

- Github default labels only describe one label group (aka, type) , this is not useful when concerned with PRs and other label groups are necessary

- The label group of priority should only be used once absolutely necessary therefore a decision was made to omit priority:low or any equivalent

- This would lead to task being passed over and is a suboptimal scenario.

- Github’s UI should render some tags discussed in thought process of decision-making as futile.
<br>For example, state:closed or state:approved.

- Once a PR is closed, an extra burden is placed upon someone to place closed label on PR.
<br>This is not necessary as UI marks PRs closed independent of labels.
<br>Same with an issue, an issue is never likely to be rendered approved.

- Prefixes absolutely matter as aforementioned, labels get chaotic without them.
<br>
<br>

The prefixes chosen are :

| Tag | Description |
| ----------- | ----------- |
| ![Effort Tag](./resources/doc-images/effort-prefix-box.svg) | Relative effort involved, scaled using fibonacci from 1 to 13  |
| ![Priority Tag](./resources/doc-images/priority-prefix-box.svg) | Designate immediacy of task involved |
| ![State Tag](./resources/doc-images/state-prefix-box.svg) | Description of state of Issue or PR |
| ![Type Tag](./resources/doc-images/type-prefix-box.svg) | Description of <span style="color: #EF927B;">issue</span> involved  |
| ![Work Tag](./resources/doc-images/work-prefix-box.svg) | Description of situation/complexity involved in bringing feature into fruition, or task to completion |
| ![*:PR:* Tag](./resources/doc-images/pr-prefix-box.svg) | Any label <span style="color: #EF927B;">only</span> applicable to PRs |
| ![*:Issue:* Tag](./resources/doc-images/issue-prefix-box.svg) | Any label <span style="color: #EF927B;">only</span> applicable to Issues |

<br>
The only labels without prefixes are breaking, and help-needed

---

## Label Explanations

| Standard | Description | Priority | State | Type | Work
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| <p>Standard labels commonly used in most repositories.</p> | <p>Describes the relative effort to complete an issue or pull request.<p> | <p>Priority labels, but focused on describing the immediacy of attention required.<p> | <p>Describes the decision state of the issue or pull request.<p> | <p>Describes the type of issue or pull request.<p> | <p>Describes the kind of work involved in resolving the issue, using the [Cynefin framework](https://en.wikipedia.org/wiki/Cynefin_framework).<p> |
| <hr> | <hr> | <hr> | <hr> | <hr> | <hr> |
| <img src="./resources/doc-images/breaking-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Breaking Tag"> | <img src="./resources/doc-images/effort-1-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Effort-1 Tag"> | <img src="./resources/doc-images/downtime-priority-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Downtime Priority Tag">| <img src="./resources/doc-images/state-blocked-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Blocked State Tag"> | <img src="./resources/doc-images/type-bug-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Bug Type Tag"> | <img src="./resources/doc-images/work-chaotic-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Chaotic Work Tag"> |
| <img src="./resources/doc-images/help-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Help Needed Tag"> | <img src="./resources/doc-images/effort-2-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Effort-2 Tag"> | <img src="./resources/doc-images/priority-soon-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Priority Soon Tag"> | <img src="./resources/doc-images/state-needs-discussion-label-btn.svg" style="width: 28vw; height: 10vh;" alt="State Needs Discussion Tag"> | <img src="./resources/doc-images/type-chore-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Chore Type Tag"> | <img src="./resources/doc-images/work-complex-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Complex Work Tag"> |
| []() | <img src="./resources/doc-images/effort-3-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Effort-3 Tag"> | <img src="./resources/doc-images/priority-now-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Priority This Now Tag"> | <img src="./resources/doc-images/state-issue-dormant-label-btn.svg" style="width: 28vw; height: 10vh;" alt="State Dormant Tag"> | <img src="./resources/doc-images/type-docs-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Documentation Type Tag"> | <img src="./resources/doc-images/work-complicated-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Complicated Work Tag"> |
| []() | <img src="./resources/doc-images/effort-5-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Effort-5 Tag">| <img src="./resources/doc-images/priority-urgent-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Priority Urgent Tag"> | <img src="./resources/doc-images/state-issue-triage-label-btn.svg" style="width: 28vw; height: 10vh;" alt="State Triage Tag"> | <img src="./resources/doc-images/type-feature-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Feature Type Tag"> | <img src="./resources/doc-images/work-obvious-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Obvious Work Tag"> |
| []() | <img src="./resources/doc-images/effort-8-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Effort-8 Tag"> | []() | <img src="./resources/doc-images/state-issue-reject-label-btn.svg" style="width: 28vw; height: 10vh;" alt="State Reject Tag"> | <img src="./resources/doc-images/type-idea-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Idea Type Tag"> | []() |
| []() | <img src="./resources/doc-images/effort-13-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Effort-13 Tag"> | []() | <img src="./resources/doc-images/state-issue-resolved-label-btn.svg" style="width: 28vw; height: 10vh;" alt="State Resolved Tag"> | <img src="./resources/doc-images/type-refactor-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Refactor Type Tag"> | []() | 
| []() | []() | []() |<img src="./resources/doc-images/state-issue-wip-label-btn.svg" style="width: 28vw; height: 10vh;" alt="State WIP Tag"> | <img src="./resources/doc-images/type-project-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Project Type Tag"> | []() |
| []() | []() | []() | <img src="./resources/doc-images/state-pr-nr-label-btn.svg" style="width: 28vw; height: 10vh;" alt="PR Needs Reviews Tag"> | <img src="./resources/doc-images/type-security-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Security Type Tag">| []() |
| []() | []() | []() | <img src="./resources/doc-images/state-pr-nd-label-btn.svg" style="width: 28vw; height: 10vh;" alt="PR Needs Deploy Tag"> | <img src="./resources/doc-images/type-test-label-btn.svg" style="width: 28vw; height: 10vh;" alt="Test Type Tag"> | []() |
| []() | []() | []() | <img src="./resources/doc-images/state-pr-nc-label-btn.svg" style="width: 28vw; height: 10vh;" alt="PR Needs Changes Tag"> |  | []() |


### <u>Standard</u>

<span><span style="color: #EF927B;">breaking: </span>Utilised when PR or issue will introduce a breaking change to the codebase</span>

<span><span style="color: #EF927B;">help-needed: </span>Relevant when help is needed from another person with an issue or a PR</span>


### <u>Effort</u>

<span><span style="color: #EF927B;">effort : * </span>: Relevant when help is needed from another person with an issue or a PR</span>

### <u>Priority</u>

<span><span style="color: #EF927B;">priority : * </span>: &nbsp;Again Self explanatory, utilised to indicate the immediacy level of issue (eg. by now / urgent )</span>

### <u>State</u>

<span><span style="color: #EF927B;">state : blocked</span>: Required to inform when state of a PR/ an issue is at a standstill or awaiting another item to be completed beforehand</span>

<span><span style="color: #EF927B;">state : needs-discussion </span>: Implies issue/PR is in need of a discussion before further action is taken.</span>

<span><span style="color: #EF927B;">state : issue : triage</span>: Assigned to an issue when first created and not yet been fleshed out/categorised</span>

<span><span style="color: #EF927B;">state : issue : dormant</span>: Assigned to an issue that hasn’t been worked upon in a lengthy period of time</span>

<span><span style="color: #EF927B;">state : issue : reject</span>: Utilized to inform all users that an issue has been rejected. No further work is required on this specific issue.</span>

<span><span style="color: #EF927B;">state : issue : resolved </span>: Applied to indicate when an issue has been resolved. Again, no further action is required.</span>

<span><span style="color: #EF927B;">state : issue : wip </span>: Employed to depict when work is currently being undertaken to resolve the issue at-hand</span>

<span><span style="color: #EF927B;">state : pr : nr </span>: Applied to signal a PR needs reviews</span>

<span><span style="color: #EF927B;">state : pr : nd </span>: Applied to signal a PR needs merge / deployment</span>

<span><span style="color: #EF927B;">state : pr : nc </span>: Applied to signal a PR needs changes before any further action is taken</span>


### <u>Type</u>

<span><span style="color: #EF927B;">type : bug</span>: Shows issue is of type bug</span>

<span><span style="color: #EF927B;">type : chore</span>: Depicts issue is associated with changes that affect the build system, external dependencies, CI configuration files and scripts</span>

<span><span style="color: #EF927B;">type : docs</span>: States issue is associated with changes that affect documentation</span>

<span><span style="color: #EF927B;">type : feature</span>: Implies issue is associated with changes that enhance or add functionality to existing product/platform</span>

<span><span style="color: #EF927B;">type : idea</span>: Implies issue is associated with an innovative method or seed for enhancement. Needs to be explored further</span>

<span><span style="color: #EF927B;">type : refactor</span>: Implies involves changes that restructure, rewrite, or re-engineer existing code in a codebase.</span>

<span><span style="color: #EF927B;">type : project</span>: States issue involves an entirely new time-intensive separate project or used to indicate a mock project</span>

<span><span style="color: #EF927B;">type : security</span>: Informs that issue involves changes that deals directly with security matters</span>

<span><span style="color: #EF927B;">type : test</span>: Details that issue involves changes that deal directly with testing and testing suite/framework matters</span>


### <u>Work</u>

<span><span style="color: #EF927B;">work : chaotic</span>: Implies that the work involved in solving an issue has cause and effect unknowables. This is a situation where only course of action is to act and evaluate</span>

<span><span style="color: #EF927B;">work : complex</span>: Implies that the work involved in solving an issue has unknown questions and solutions. This situation dictates that the only course of action is to experiment and then assess</span>

<span><span style="color: #EF927B;">work : complicated</span>: Implies that the work involved in solving an issue has a difficult solution but known questions are at hand. Advise in this scenario is to obtain expert answers, analyze and then implement.</span>

<span><span style="color: #EF927B;">work : obvious</span>: Implies that the work involved in solving an issue has a simple and evident solution. The advice given in this scenario is to implement best practice</span>


<div style="display: grid; place-items:center; margin: 2em 0">
    <img src="./resources/doc-images/cynefin-framework-1.svg" style="width: 40vw; margin-bottom: 1em;">
    <br>
    <img src="./resources/doc-images/cynefin-framework-2.svg" style="width: 40vw; margin-bottom: 1em;">
    <span>These pictures depict the Cynefin Framework.</span>
    <span>Framework is utilized for quantifying uncertainty.</span>
</div>

### Resources:

1. [Simple version of framework](https://www.youtube.com/watch?v=L5fnxahydXM&list=PLQxPiNrHgSCqaDLp7HnncXQ5bN8DnU12n)
2. [Framework with simple examples](https://www.youtube.com/watch?v=YvWOTSEVSCY&list=PLQxPiNrHgSCqaDLp7HnncXQ5bN8DnU12n&index=3)


<br>


## Label Creation 

 In order to create a unified and clear workflow, these labels were created. A discussion <span style="color: #EF927B;">must</span>  be had in order to alter or add new labels with everyone involved in the team in agreement.
 
 This ensures a streamlined approach to task management
<br>
<br>

> <span style="color: #EF927B;">Note:</span> Labels don’t exist independently from a Github repository so if same label system is required in other repositories, a syncing operation needs to take place

<br>

In future versions, a syncing tool that performs this operation will be in charge of label creation.

<br>


## Label Attachment/Usage

As aforementioned, Github utilizes same labels across all of its product suite. This is not very helpful as some labels need exist for only specific products and not for others.

This formed the premise of my decision-making when it came to attaching labels to any product (PR or Issue). 

#### PRs only have four states:

##### <span style="color: #EF927B;">Needs Reviews (state : pr : nr) :</span> PR has been created, it is in progress and is seeking a reviewer
##### <span style="color: #EF927B;">Needs Changes (state : pr : nc) :</span> PR has been reviewed, it is of an unsatisfactory level to the reviewer. Changes need to be made
##### <span style="color: #EF927B;">Needs Deploy (state : pr : nd) :</span> PR has been approved by all reviewers and is ready to be merged
##### <span style="color: #EF927B;">Blocked (state : blocked) :</span> PR has been thwarted
<br>

Issues on the other hand at time of creation, should have access to all other labels mentioned in labels overview.

Once creating an issue, it is advised you select a label from each label group where applicable as this gives a more comprehensive overview of issue status, priority, and details.

<u>Don't double stack labels from the same group</u>


<br>For example,

<u>Task:</u> Want to build out a shopping cart into my e-commerce shop

<u>Labels applied might be: </u>

<div style="display: grid; place-items: center; margin: 4em;">
    <img src="./resources/doc-images/example-applied-labels.svg">
</div>

Again, <span style="color: #EF927B">state : pr : *</span> labels are off limits, however <span style="color: #EF927B">state : blocked</span> is available to use as it makes sense that an issue could also be blocked.

---


## Add Ons

With some label groups, there is a lifecycle encompassed within.
##### For example (eg. state of an issue )

<div style="display: grid;">
    <img src="./resources/doc-images/state-lifecycle-example.svg" style="height: 20vh;">
</div>

<br>Future versions may look to automate these life cycles as much as possible. However for now, manual addition/removing as set out in these guidelines is <span style="color: #EF927B"><u>mandatory.</u></span>