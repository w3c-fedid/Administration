# FedID CG/WG Process Mechanics

This is a proposal to break proposals into 5 stages of maturity, with clear guidelines and requirements to advance them:

* [Stage 0](#stage0): Understand the Problem Space
* [Stage 1](#stage1): Incubate Proposals
* [Stage 2](#stage2): Specify a Preferred Proposal
* [Stage 3](#stage3): Increase Deployment Confidence
* [Stage 4](#stage4): Publish a Proposed Recommendation

# Stage 0

The purpose of Stage 0 proposals is to allow anyone to raise and explore the Problem Space without asking for permission.  

  * Entrance criteria
    * Nothing: no permission needed from anyone. 
  * Entrance artifact
    * An issue, a personal repo, a blog post, a tweet, etc 
  * Exit criteria
    * Identification of [champions](https://github.com/tc39/how-we-work/blob/main/champion.md)
    * A problem statement 
# Stage 1

The purpose of Stage 1 proposals is to explore the Solution Space and pick a preferred direction. This is where most of the work gets done because it involves exploring alternatives, understanding tradeoffs, gathering implementation experience, incubating alternatives, gathering evidence of demand and product market fit and finally identifying the best out of the many alternatives.

  * Entrance criteria
    * Products of the prior stage and
    * The CG consensus that the problem is worth spending the CG’s time working on
  * Entrance artifact
    * A FedID repo gets created in the CG for the champions to develop the feature (e.g. [example](https://github.com/fedidcg/CrossSiteCookieAccessCredential)).
  * Exit criteria
    * An [explainer](https://tag.w3.org/explainers/)
    * A specific proposal under consideration (with varying degrees of specificity, e.g. from code samples to a spec PR)
    * Alternatives considered
    * Known Issues filed
    * Implementation Experience (e.g. a prototype, dev trials, origin trials, etc) 
    * Evidence of developer demand

# Stage 2
  * Entrance criteria
    * Products of the prior stage and
    * WG consensus to adopt the solution as the basis for their work.
    * The WG identifies a list of (seemingly resolvable) issues that have to be addressed before Stage 3.
  * Entrance artifact
    * The spec PR gets merged into the [Editor’s Draft](https://w3c-fedid.github.io/FedCM/)
    * The feature repo gets transferred to the Working Group 
  * Exit criteria
    * Proposal fully merged into the [Editor’s Draft](https://w3c-fedid.github.io/FedCM/)
    * The [Editor’s draft](https://www.w3.org/policies/process/#editors-draft) addresses all issues that were identified at the entrance
    * Web Platform Tests
    * Further implementation experience
   * Purpose
     * Refine the proposal to produce a [Working Draft](https://www.w3.org/policies/process/#RecsWD)
     * Deal with corner cases
     * Specify details
     * Integrate proposal with other parts
     * Reeconcile proposal with other proposals
     * Resolve concerns
# Stage 3
  * Entrance criteria
    * Products of the prior stage and
    * WG consensus that the [Editor’s Draft](https://www.w3.org/policies/process/#editors-draft) sufficiently resolves all of the issues raised
  * Entrance artifact
    * The [Editor’s Draft](https://w3c-fedid.github.io/FedCM/) gets published as the WG [Working Draft](https://www.w3.org/TR/fedcm/)
  * Exit criteria
    * Two independent and interoperable implementations
    * Significant deployment experience
 * Purpose
    * Gather two independent implementation experience to produce a [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR)
  
# Stage 4
  * Purpose
    * Inclusion as a [W3C Recommendation](https://www.w3.org/policies/process/#RecsW3C)
  * Entrance criteria
    * Products of the prior stage and
    * WG consensus that the [Working Draft](https://www.w3.org/policies/process/#RecsWD) as a whole is complete
  * Entrance artifact
    * The [Working Draft](https://www.w3.org/policies/process/#RecsWD) gets published as [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR)
  * Exit criteria
    * Consensus across all of W3C to move forward towards a [Proposed Recommendation](https://www.w3.org/policies/process/#RecsPR) 

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

