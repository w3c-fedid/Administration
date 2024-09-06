# FedID CG/WG Process Mechanics

This is a proposal to break proposals into 5 stages of maturity, with clear guidelines and requirements to advance them:

* [Stage 0](#stage0): Understand the problem
* [Stage 1](#stage1): Understand the solutions
* [Stage 2](#stage2): Formalize a specific proposal
* [Stage 3](#stage3): Gather more implementation experience
* [Stage 4](#stage4): Publish a proposed recommendation

# Stage 0
  * Entrance criteria
    * Nothing: no permission needed from anyone. 
  * Entrance artifact
    * An issue, a personal repo, a blog post, a tweet, etc 
  * Exit criteria
    * Identification of [champions](https://github.com/tc39/how-we-work/blob/main/champion.md)
    * A problem statement 
# Stage 1
  * Entrance criteria
    * Products of the prior stage and
    * The CG consensus that the problem is worth spending the CG’s time working on
  * Entrance artifact
    * A FedID repo gets created in the CG for the champions to develop the feature (e.g. [example](https://github.com/fedidcg/CrossSiteCookieAccessCredential))
  * Exit criteria
    * An [explainer](https://tag.w3.org/explainers/)
    * A specific proposal under consideration (with varying degrees of specificity, e.g. from code samples to a spec PR)
    * Alternatives considered Issues filed by FedID CG members in the repo
    * Implementation experience (e.g. a prototype, dev trials, origin trials, etc) 
    * Evidence of developer demand
  * Purpose
    * Understand the solutions
      * Incubate and make a proposal
      * Explore alternatives
      * Gather implementation experience
      * Understand tradeoffs
      * Gather evidence of demand
# Stage 2
   * Purpose
     * Refine the proposal to produce a [Working Draft](https://www.w3.org/policies/process/\#RecsWD)
     * Deal with corner cases <br>* Specify details Integrate proposal with other parts
     * Resolve concerns
  * Entrance criteria
    * Products of the prior stage and WG consensus to adopt the solution as the basis for their work
    * The WG identifies a list of (seemingly resolvable) issues that have to be addressed before Stage 3
  * Entrance artifact
    * The spec PR gets merged into the [Editor’s Draft](https://w3c-fedid.github.io/FedCM/)
    * The feature repo gets transferred to the Working Group 
  * Exit criteria
    * An [Editor’s draft](https://www.w3.org/policies/process/#editors-draft) that addresses all issues that were identified at the entrance
    * Web Platform Tests
    * Further implementation experience
# Stage 3
  * Purpose
    * Gather two independent implementation experience to produce a [Candidate Recommendation](https://www.w3.org/policies/process/#RecsCR)
  * Entrance criteria
    * Products of the prior stage and
    * WG consensus that the [Editor’s Draft](https://www.w3.org/policies/process/#editors-draft) sufficiently resolves all of the issues raised
  * Entrance artifact
    * The [Editor’s Draft](https://w3c-fedid.github.io/FedCM/) gets published as the WG [Working Draft](https://www.w3.org/TR/fedcm/)
  * Exit criteria
    * Two independent and interoperable implementations
    * Significant deployment experience
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

