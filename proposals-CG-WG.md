# FedID CG/WG Process Mechanics

This is a proposal to break proposals into 5 stages of maturity, with clear guidelines and requirements to advance them:

* [Stage 0](#stage0): Understand the Problem Space
* [Stage 1](#stage1): Incubate Proposals
* [Stage 2](#stage2): Specify a Preferred Proposal
* [Stage 3](#stage3): Increase Deployment Confidence
* [Stage 4](#stage4): Publish a Proposed Recommendation

# Stage 0

The purpose of Stage 0 proposals is to allow anyone to raise and explore the Problem Space without asking for permission. 

  * What's needed from individuals?
    * Typically, a written issue, a personal repo, a blog post, a tweet, etc. 
  * What's asked of the community group?
    * Nothing: no permission needed from anyone.

# Stage 1

The purpose of Stage 1 proposals is to explore the Solution Space and pick a preferred direction. This is where most of the work gets done because it involves exploring alternatives, understanding tradeoffs, gathering implementation experience, incubating alternatives, gathering evidence of demand and fitness for purpose and finally identifying the best out of the many alternatives.

  * What's needed from individuals?
    * Identification of [champions](https://github.com/tc39/how-we-work/blob/main/champion.md)
    * A good understanding of the Problem Space
    * Alternatives under consideration
  * What's asked of the **Community Group**?
    * The Communit Group consensus that the problem is worth spending the Community Group’s time working on
  * What happens if accepted?
    * Optionally, a repo gets created for the champions to develop the feature (e.g. [example](https://github.com/fedidcg/CrossSiteCookieAccessCredential)). Small features can also continue as issues.

# Stage 2

The purpose of Stage 2 Proposals is to formally specify the best (and seemingly workable) alternative that was identified in the prior step: handle corner cases, integrate with other parts, reconcile with other proposals and resolve the concerns identified at the entrance. The Proposal enters Stage 2 with a list of blocking issues to advance to the next stage and exits with all of the issues resolved.

  * What's needed from champions?
    * An [explainer](https://tag.w3.org/explainers/)
    * A specific proposal (with varying degrees of specificity, e.g. from code samples to a spec PR)
    * Alternatives and trade-offs considered
    * Browser and developer implementation experience (e.g. a prototype, dev trials, origin trials, etc) 
    * Evidence of developer demand and fitness for purpose
  * What's asked of the **Working Group**?
    * The Working Group consensus to adopt the solution as the basis for their work.
    * The Working Group identifies a list of (seemingly resolvable) issues that have to be addressed before [Stage 3](#stage-3).
  
# Stage 3

 The purpose of Stage 3 Proposals is to increase the implementation and deployment confidence in order to produce a [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR).
 
  * What's needed from champions?
    * Proposal fully merged into the [Editor’s Draft](https://w3c-fedid.github.io/FedCM/)
    * Web Platform Tests
    * Further implementation experience
  * What's asked of the **Working Group**? 
    * The Working Group consensus that the [Editor’s Draft](https://www.w3.org/policies/process/#editors-draft) sufficiently resolves all of the issues raised at [Stage 2](#stage-2)
  * What happens if accepted?
    * The [Editor’s Draft](https://w3c-fedid.github.io/FedCM/) gets published as the Working Group's [Working Draft](https://www.w3.org/TR/fedcm/)
  
# Stage 4

 The purpose of Stage 4 Proposals is to produce a [W3C Recommendation](https://www.w3.org/policies/process/#RecsW3C).
 
  * What's needed from champions?
    * Two independent and interoperable implementations
    * Significant deployment experience
  * What's asked of the **Working Group**?
    * The Working Group consensus that the [Working Draft](https://www.w3.org/policies/process/#RecsWD) as a whole is complete
  * What happens if accepted?
    * The [Working Draft](https://www.w3.org/policies/process/#RecsWD) gets published as [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR) and gets sent forward for further consensus across all of W3C to move forward towards a [Proposed Recommendation](https://www.w3.org/policies/process/#RecsPR) 

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

