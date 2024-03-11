# Web project 2

The Learning Integration Assessment for this course entails the
development of a dynamic website project from start to finish. The
subject of the project as well as the technologies used is up to
students. However, the project must meet certain requirements,
listed below.

## Requirements

The following list of requirements is intentionally vague to allow
students to work on projects that fit their interests. "Content" and
"articles" can refer to a variety of things: posts, events, services,
items, etc.

-   As a user, I can filter, search, and sort content.
-   As a user, I can register an account.
-   As a user, once logged in, I can access personalized content other
    users cannot.
-   As a user, once logged in, I can create content, as well as modify
    and delete the content I have created.
-   As a user, once logged in, I can add comment on the content.
-   As an administrator, I can manage user accounts, and modify their
    content.
-   As an administrator, I can generate statistics based on users and
    their content: number of registered users, amount of content (total
    and per user), content metadata (at least 3), number of comments per
    "article".
-   As an administrator, I can import content from a third-party API.

For instance, [Fonts In Use][], an independent archive of typography,
meets most of these requirements.

[Fonts In Use]: https://fontsinuse.com

Note that the application must include a panel, and that this panel is
part of the project. It must be designed and developed by students.

## Planning

The project must be planned and executed iteratively. Students are
required to establish a specific milestone to achieve each week. This
milestone should outline the tasks to be accomplished as well as who is
responsible for them.

Students are strongly encouraged to use [GitHub Issues][] for planning.
Once a milestone is completed, an annotated Git tag pointing to the last
commit must be added to the repository.

[GitHub Issues]: https://github.com/features/issues

Assessment of the project will take place in three phases, during which
students will informally present the work accomplished, and receive
feedback.

## Phase 1: Analysis and planning

The analysis and planning phase lays the foundation for the entire
development process. During this phase, you will need to conduct an
assessment of the project requirements, and produce a detailed project
plan.

### Deliverables

#### Request for proposal

A request for proposal (RFP) is a document issued by an organization
to solicit proposals from service providers for a specific project.
RFPs are usually produced by the client. However, for the purpose of
the LIA, you will have to produce the RFP.

The RFP must include the following:

-   Introduction: Name and description of the organization issuing
    the request.
-   Project background: Brief description of the problem(s) the
    organization is facing, and which the web project aims to address.
-   Objectives: Clear, measurable goals and objectives that the web
    project is expected to achieve.
-   Scope of work: Detailed description of the tasks, deliverables,
    and features required for the web project, including any specific
    functionalities, design elements, or technical requirements.

#### Proposal

The proposal is a document containing your team's response to the
RFP. It must include the following:

-   Project summary: Summary of the client's needs.
-   Stakeholders: People involved in the project, including developers,
    designers and end-users. A brief description of the latter should
    be included.
-   Technologies: Technologies, frameworks and tools used for developing
    the website, along with any rationale for their selection based on
    the project requirements.
-   Timeline and milestones: Deadlines for key deliverables and phases
    of the project.
-   Communication plan: Outline of how project communication will
    be managed, including frequency of meetings, and channels of
    communication.

### Submission

Both documents must be submitted separately on GitHub in plain text
format. The repository must be created through [GitHub Classroom][].

[GitHub Classroom]: https://classroom.github.com/a/kJapopx9

### Assessment criteria (30%)

-   Requirements are met.
-   The RFP is well detailed.
-   The proposal addresses the client's needs.
-   Technologies are chosen based on the project's requirements.
-   The timeline is comprehensive.
-   Milestones are logical and sensible.
-   Documents are written in proper prose.

Additionally, 5% of the grade will be allocated for peer evaluation.

## Phase 2–3: Implementation

Phases 2 and 3 will assess your implementation of the web project,
including design, client-side and server-side development. The choice of
weekly milestones is up to students, but the project should be
completed at the end of phase 3.

### Deliverables

-   Wireframes: one for each page, plus rationale
-   Visual language guidelines: typography (fonts, weights, styles, line
    height, plus rationale), colors (at least 2, plus rationale), grid
    and base unit
-   Mockups: one for each page
-   Semantic data model (entity-relationship diagram)
-   README file detailing the project's architecture, and how to install
    and run it locally
-   Source code, including docstrings and tests

### Assessment criteria (30% × 2)

#### Planning

-   Requirements are met.
-   Work is well-planned.
-   The project's architecture is well explained.
-   Instructions to install and run the project locally are clear.
-   Commits are [self-contained][].
-   Commit messages are [well-formed][].

[well-formed]: https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
[self-contained]: https://drewdevault.com/2019/02/25/Using-git-with-discipline.html/#each-commit-should-be-a-self-contained-change

#### Design

-   Wireframes take into account both the project's goals and its
    end-users.
-   Visual language guidelines are thorough, and the rationale is
    concretely based on the organization and the project's identity.
-   Mockups are detailed, and adhere to the guidelines.
-   Design is [accessible][What is accessibility?].

[What is accessibility?]: https://developer.mozilla.org/en-US/docs/Learn/Accessibility/What_is_accessibility

#### Programming

-   The entity-relationship diagram is complete, and faithfully
    represents the data model.
-   The database schema is normalized (3NF minimum).
-   Naming is descriptive and consistant.
-   Tests are accurate and rigorous.
-   Program is free of dead code.
-   Code is well documented, and the prose is correct and helpful.
-   Program flow is decomposed into manageable, logical pieces.
-   Common code is unified, and not duplicated.
-   Code is consistently formatted.
-   Stylesheets are written to be maintainable.
-   HTML is semantic.

Additionally, 5% of the grade will be allocated for peer evaluation.

#### Submission

Source code must be committed on GitHub. Links to wireframes, mockups,
and visual language guidelines must be provided.

## Presentation

To be determined.