# Maia Ecosystem Governance Monorepo

Welcome to the MaiaDAO Governance GitHub Monorepo! This repository serves as a central hub for all governance-related aspects of our decentralized finance protocols. Here, you will find comprehensive documentation, guidelines, governance procedures, proposal history and useful resources. By leveraging this documentation, community members, ecosystem partners and developers can actively contribute to the decision-making process and drive the protocol's evolution.

We believe in the power of decentralized decision-making and welcome your active involvement in shaping the future of our protocol. Let's collaborate, innovate, and drive the advancement of our DeFi ecosystem together!

### Table of Contents
1. [Governance Process](#governance-process)

2. [Governance Proposal Structure](#governance-proposal-structure)

## Governance Process

This section offers detailed instructions and a step-by-step guide on how to progress from an initial idea to the on-chain execution of a proposal.

### Phase 1: Request for Comment (RFC)

The first phase of the governance process is meant to allow the community to digest a proposal, comment, and ask questions about the proposal in question and how it will benefit the ecosystem.

In the proposal, you should provide a clear and detailed description supported with verifiable information on how the proposal is intended to meet the proposed goals. If necessary the proposal should include a transparent framework with measurable objectives that allows any community member to easily track and evaluate the proposal progress and performance towards achieving different milestones. 

To post a RFC, label your post “RFC - [Your Title Here]”. Prior to moving to Phase 2, give the community at least 3 days to read and comment on the RFC. Please respond to questions in the comments, and take feedback into account in the next iteration of the proposal posted in Phase 2.

### Phase 2: Temperature Check (TC)

The purpose of the Temperature Check is to signal community sentiment on a new proposal prior to moving towards an on-chain vote.

To create a Temperature Check:

    1. Incorporate the community feedback from the RFC phase into the proposal.

    2. Create and post this version of the proposal in the Governance Forum with the following title “TC - [Your Title Here]”. Include a link to the RFC post. You will update the post to include a link to the Snapshot poll after you’ve posted that.

    3. Create a Snapshot poll. The voting options should consist of those which have gained support in the RFC Phase. This poll can be either binary or multiple choice but must include a “Nay” option. Set your poll duration. Include a link to the Forum Proposal Temperature Check post.

    4. Update the Forum post with a link to the Snapshot Poll.

At the end of 5 days, the option with the majority of votes wins. There must be at least 10M bHERMES yes votes to move onto Phase 3. If the “Nay” option wins, the proposal will not move onto the Phase 3.

Until V2 launch that will have full on-chain governance, proposals that pass Phase 2 don’t need to continue to Phase 3. They are considered passed and will be executed when migrating from V1 to V2.

### Phase 3: Governance Proposal

Phase 3 is the final step of the governance process. If this vote passes, then a change will be enacted on-chain.

To create an on-chain Governance Proposal:

    1. Incorporate any last iterations to your proposal based on feedback prior to posting.

    2. Create a topic in the [TBD] titled “Governance Proposal — [Your Title Here]” and link to previous forum posts and the Proposal Temperature Check Snapshot poll.

    3. Create your proposal. This can be done either through an interface (on [TBD]) or through writing the calldata for more complicated proposal logic. This calldata will be executed if and when the proposal passes. If writing the calldata yourself, please review the logic with a qualified Hermes community member prior to posting the proposal.

    4. Ensure that at least the minimum voting power threshold is delegated to your address in order to submit a proposal, or find a delegate who has enough delegated bHERMES to meet the proposal threshold to propose on your behalf.

    5. Once the proposal has been submitted (or the propose() function has been called), a two day voting delay will start. After the voting delay is finished, a seven day voting period begins. If the proposal passes successfully, the proposed code is executed.
    
## Governance Proposal Structure

The Governance Proposal Structure section outlines the format and essential components of a governance proposal. It provides a comprehensive template that covers all the necessary sections and information required to present a proposal effectively. By adhering to this structure, contributors can ensure that their proposals are coherent, organized, and provide the necessary details for informed decision-making.

### Introduction:
- Provide a concise overview of the proposal.
- State the purpose and objectives of the proposal.
- Clearly identify the DeFi protocol or platform to which the proposal applies.

### Background and Rationale:
- Describe the existing governance framework of the protocol.
- Explain the motivation behind the proposed changes or improvements.
- Outline any issues or challenges that the proposal aims to address.

### Proposal Details:
- Clearly articulate the specific changes or updates being proposed.
- Provide a detailed explanation of each proposed change.
- Highlight the benefits and potential impact of the proposed changes.

### Implementation Plan:
- Outline the steps and timeline required to implement the proposed changes.
- Describe any dependencies or prerequisites for successful implementation.
- Address any potential risks or challenges that may arise during implementation.

### Governance Considerations:
- Discuss how the proposed changes align with the principles and values of the protocol.
- Explain how the proposal enhances the decentralization, security, and trustlessness of the protocol.
- Highlight any potential implications for token holders, stakeholders, or the wider ecosystem.

### Community Engagement and Support:
- Outline strategies to engage and gather feedback from the community.
- Describe any discussions or debates that have taken place regarding the proposal.
- Provide evidence of community support or consensus for the proposed changes.

### Next Steps and Decision-making Process:
- Explain how the proposal will move forward and be implemented.
- Clearly state who will be responsible for making the final decision.
- Outline the decision-making process, including voting mechanisms or signaling periods.

### Conclusion:
- Summarize the main points of the proposal.
- Reiterate the benefits and potential impact of the proposed changes.
- Encourage the community to support and participate in the decision-making process.
