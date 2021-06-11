# NEAR Protocol Specifications and Standards

This repository hosts the current NEAR Protocol specification and standards.
This includes the core protocol specification, APIs, contract standards, processes, and workflows.

Changes to the core specification and standards are called Near Enhancement Proposals (NEPs).

## Specification

NEAR Specification is under active development. The latest version can be found at [Nomicon](https://nomicon.io).
Specification defines how any NEAR client should be connecting, producing blocks, reaching consensus, processing state transitions, using runtime APIs, and implementing smart contract standards as well.

### Contributing

#### Expectations

#### Process

Spec changes are ultimately done via pull requests to this repository. However, in an effort to keep the pull request clean and readable, please follow these instructions to flesh out an idea.

1. Sign up for the [governance site](https://gov.near.org/) and make a post to the appropriate section. For instance, during the ideation phase of a standard, one might start a new conversation in the [Development » Standards section](https://gov.near.org/c/dev/standards/29).
2. The forum has comment threading which allows the community and NEAR Collective to ideate, ask questions, wrestle with approaches, etc. If more immediate responses are desired, consider bringing the conversation [to Discord](https://near.chat).
3. When the governance conversations have reached a point where a clear plan is evident, create a pull request, using the instructions below.

Pull request
* Clone this repository and create a branch with "my-feature".
* Update relevant content in the current specification that are affected by the proposal.
* Create PR, where information of the PR follows [0000-template.md](0000-template.md) to describe motivation and details of the change to the protocol.
* Post pre-approval of the spec change, present a PR for NEAR Protocol client(s) that implements this specification change.
* Receive final approval and merge change into the `master` to be included in the next specification release.

## Standards & Processes

Standards refer to various common interfaces and APIs that are used by smart contract developers on top of the NEAR Protocol.
For example, such standards include SDK for Rust, API for fungible tokens or how to manage user's social graph.

Processes include release process for spec, clients or how standards are updated.

### Contributing

* Copy `0000-template.md` to `specs/0000-my-feature.md` (where "my-feature" is descriptive. don't assign an NEP number yet).
* If applicable, link to the issued in specific repositories;
* Fill in the NEP. Put care into the details: NEPs that do not present convincing motivation, demonstrate understanding of the impact of the design, or are disingenuous about the drawbacks or alternatives tend to be poorly received. Again, by the time the NEP makes it to the pull request, it has a clear plan and path forward based on the discussions in the governance forum.
* Submit a pull request. As a pull request the NEP will receive design feedback from the larger community, and the author should be prepared to revise it in response.
* Build consensus and integrate feedback. NEPs that have broad support are much more likely to make progress than those that don't receive any comments. Feel free to reach out to the NEP assignee in particular to get help identify stakeholders and obstacles.
