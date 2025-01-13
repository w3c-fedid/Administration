# CG/WG Proposal Stages

Author: @samuelgoto
Created: 2024-08-11
Last update: 2024-11-26
Status: under review

This is a proposal to break proposals into 5 stages of maturity, with clear guidelines and requirements to advance them:

* [Stage 0](#stage0): **Exploration** of the Problem Space
* [Stage 1](#stage1): **Incubation** of competing Alternatives
* [Stage 2](#stage2): **Formalization** a preferred Proposal
* [Stage 3](#stage3): **Implementation** of the preferred Proposal
* [Stage 4](#stage4): **Publication** of a Proposed Recommendation

These stages support the W3C process and align with the [TC39 process](https://tc39.es/process-document/) and the [WHATWG process](https://whatwg.org/stages). If there is ever any question between W3C process requirements and how the groups will progress their work, the W3C process has precedent.

# Stage 0: Exploration

The purpose of Stage 0 proposals is to allow anyone to raise and explore the Problem Space without asking for permission. 

  * What's needed from individuals?
    * [ ] Typically, a written issue, a personal repo, a blog post, a tweet, etc. 
  * What's asked of the **Community Group**?
    * Nothing: no permission needed from anyone.

# Stage 1: Incubation

The purpose of Stage 1 proposals is to explore the Solution Space and pick a preferred direction. This is where most of the work gets done because it involves exploring alternatives, understanding tradeoffs, gathering implementation experience, incubating alternatives, gathering evidence of demand and fitness for purpose, and finally, identifying the best out of the many alternatives.

  * What's needed from individuals?
    * [ ] Identification of [champions](https://github.com/tc39/how-we-work/blob/main/champion.md).
    * [ ] An understanding of the Problem Space.
    * [ ] Optionally, alternatives under consideration.
  * What's asked of the **Community Group**?
    * [ ] The Community Group consensus that the problem is worth spending the Community Group’s time working on.
    * [ ] A home for incubating the proposal. Small features will incubate in issues. If and when the champions are ready to more thoroughly document their proposal, the WG chairs will create a repo for the champions to develop the feature (e.g., [example](https://github.com/fedidcg/LightweightFedCM)). 

# Stage 2: Formalization

The goal of Stage 2 is to refine the preferred solution into a detailed, cohesive proposal that addresses known issues and integrates feedback from stakeholders. The Proposal enters Stage 2 with a list of issues that block advancement to the next stage, and exits with all of the issues resolved.  This stage focuses on preparing the proposal for Working Group review and creating a complete, formal draft.

  * What's needed from champions?
    * [ ] An [explainer](https://tag.w3.org/explainers/).
    * [ ] Documentation of alternatives and trade-offs considered.
    * [ ] Optionally, a draft specification text (or detailed examples/code samples if needed for clarity).
    * [ ] Early implementation experience, including prototypes or trials.
    * [ ] Evidence of stakeholder (e.g. web developers) demand and use-case alignment.

  * What's asked of the **Working Group**?
    * [ ] Working Group consensus to adopt the proposal as the basis for their work.
    * [ ] A clear list of blocking issues to be addressed before advancing to Stage 3.
    * [ ] A completed Working Draft for further iteration.
    * [ ] Approval to dedicate the WG's time to Review spec PRs to merge the proposal into the [Working Draft](https://www.w3.org/policies/process/#RecsWD).

  
# Stage 3: Implementation

> NOTE: We don't yet have enough experience as we get towards Stage 3 and 4, so they aren't fully baked yet. It is possible that these
> will change a lot as we learn, including potentially entirely replacing them with references to the W3C Process. 

The purpose of Stage 3 Proposals is to increase implementation and deployment confidence in order to produce a [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR). The spec should be considered finished, pending editorial nit review. However, since multiple implementations are expected to be produced during this stage, it is possible there will be further changes to normative content based on feedback from those implementors.
 
  * What's needed from champions?
    * [ ] Proposal fully merged into the [Working Draft](https://www.w3.org/policies/process/#RecsWD).
    * [ ] Web Platform Tests are available.
    * [ ] At least two independent implementers and no unresolved objections (where resolution may include an agreement not to address the issue).
  * What's asked of the **Working Group**? 
    * [ ] Working Group consensus that the [Working Draft](https://www.w3.org/policies/process/#RecsWD) sufficiently resolves all of the issues raised at [Stage 2](#stage-2).
    * [ ] Working Group consensus to publish the [Working Draft](https://www.w3.org/policies/process/#RecsWD) as the Working Group's [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR).
  
# Stage 4: Publication

 The purpose of Stage 4 Proposals is to produce a [W3C Recommendation](https://www.w3.org/policies/process/#RecsW3C). At this stage, the spec is merged and has finished editor review. This editor review could be lengthy, especially if the feature is large and/or the contributor is new to W3C process, but it will usually be short.
 
  * What's needed from champions?
    * [ ] Documented [implementation experience](https://www.w3.org/policies/process/#implementation-experience) across multiple environments.
  * What's asked of the **Working Group**?
    * [ ] Working Group consensus that the [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR)'s implementation experience is complete.
    * [ ] Working Group consensus to publish it as a [Proposed Recommendation](https://www.w3.org/policies/process/#RecsPR).

# Prior Art

* TC39  
  * Proposals Repo: [https://github.com/tc39/proposals](https://github.com/tc39/proposals)  
  * Stages: [https://tc39.es/process-document/](https://tc39.es/process-document/)   
  * Examples  
     * Decorators Repo: [https://github.com/tc39/proposal-decorators](https://github.com/tc39/proposal-decorators)   
     * Temporal Repo: [https://github.com/tc39/proposal-temporal](https://github.com/tc39/proposal-temporal)   
* Immersive Web CG/WG  
  * Proposals Repo: [https://github.com/immersive-web/proposals](https://github.com/immersive-web/proposals)  
  * Stage 0 Issues: [https://github.com/immersive-web/proposals/issues](https://github.com/immersive-web/proposals/issues)   
  * Examples  
     * \<model\> Repo: [https://github.com/immersive-web/model-element](https://github.com/immersive-web/model-element)  
     * Depth sensing Repo: [https://github.com/immersive-web/depth-sensing](https://github.com/immersive-web/depth-sensing)   
* WebAssembly  
  * Proposals Repo: [https://github.com/WebAssembly/proposals](https://github.com/WebAssembly/proposals)  
  * Examples  
     * Tail call Repo: [https://github.com/WebAssembly/tail-call](https://github.com/WebAssembly/tail-call)  
     * GC Repo: [https://github.com/WebAssembly/gc](https://github.com/WebAssembly/gc)

