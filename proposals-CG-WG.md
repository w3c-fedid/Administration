# FedID CG/WG Process Mechanics

This is an exploration of options to manage the mechanics of the proposals with github between the FedID CG and the FedID WG.

|  Stage |  Entrance Criteria |  Entrance artifacts |  Exit Criteria |  Purpose  |
| :---: | ----- | ----- | ----- | ----- |
|  **Community Group**  |  |  |  |  |
| 0 | * Nothing: no permission needed from anyone.  | * An issue, a personal repo, a blog post, a tweet, etc | * Identification of [champions](https://github.com/tc39/how-we-work/blob/main/champion.md) <br>* A problem statement | * Understand the problem Identity challenges |
| 1 | * Products of the prior stage and <br>* The CG consensus that the problem is worth spending the CG’s time working on | * A FedID repo gets created in the CG for the champions to develop the feature (e.g. [https://github.com/fedidcg/CrossSiteCookieAccessCredential](https://github.com/fedidcg/CrossSiteCookieAccessCredential)) | * An [explainer](https://tag.w3.org/explainers/) <br>* A specific proposal under consideration (with varying degrees of specificity, e.g. from code samples to a spec PR) <br>* Alternatives considered Issues filed by FedID CG members in the repo <br>* Implementation experience (e.g. a prototype, dev trials, origin trials, etc) <br>* Evidence of developer demand | Understand the solutions: incubate and make a proposal <br>* Explore alternatives <br>* Gather implementation experience <br>* Understand tradeoffs <br>* Gather evidence of demand |
|  **Working Group**  |  |  |  |  |
| 2 | * Products of the prior stage and WG consensus to adopt the solution as the basis for their work <br>*The WG identifies a list of (seemingly resolvable) issues that have to be addressed before Stage 3 | * The spec PR gets merged into the [Editor’s Draft](https://www.w3.org/policies/process/\#editors-draft) at [https://w3c-fedid.github.io/FedCM](https://w3c-fedid.github.io/FedCM/)  <br>* The feature repo gets transferred to the Working Group | * An [Editor’s draft](https://www.w3.org/policies/process/\#editors-draft) that addresses all issues that were identified at the entrance Web Platform Tests Further implementation experience | Refine the proposal to produce a [Working Draft](https://www.w3.org/policies/process/\#RecsWD) <br>* Deal with corner cases <br>* Specify details Integrate proposal with other parts <br>* Resolve concerns |
| 3 | * Products of the prior stage and <br>* WG consensus that the [Editor’s Draft](https://www.w3.org/policies/process/\#editors-draft) sufficiently resolves all of the issues raised | The [Editor’s Draft](https://www.w3.org/policies/process/\#editors-draft) gets published as a Working Group [Working Draft](https://www.w3.org/policies/process/\#RecsWD) at [https://www.w3.org/TR/fedcm](https://www.w3.org/TR/fedcm/) | * Two independent and interoperable implementations <br>* Significant deployment experience | * Gather two independent implementation experience to produce a [Candidate Recommendation](https://www.w3.org/policies/process/\#RecsCR)  |
| 4 | * Products of the prior stage and <br>* WG consensus that the [Working Draft](https://www.w3.org/policies/process/\#RecsWD) as a whole is complete  | * The [Working Draft](https://www.w3.org/policies/process/\#RecsWD) gets published as [Candidate Recommendation](https://www.w3.org/policies/process/\#RecsCR) | * Consensus across all of W3C to move forward towards a [Proposed Recommendation](https://www.w3.org/policies/process/\#RecsPR) | * Inclusion as a [W3C Recommendation](https://www.w3.org/policies/process/\#RecsW3C) |

# ANNEX

# Related Docs

* Policies [FedID CG & WG Stages](https://docs.google.com/document/d/1SflJDyMFxt5dBvfRRzUs1fDa4c9KZmkDpfuYf75i9rI/edit)

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

# Proposal

## Bootstrap

* Each of the Stage 1 proposals being currently actively worked on gets a repo created at the W3C FedID organization:  
  * Example [https://github.com/w3c-fedid/awesome-proposal](https://github.com/fedidcg/fedcm) and   
  * Gets added to [https://github.com/w3c-fedid/proposals](https://github.com/fedidcg/proposals) list  
  * For example  
    * [https://github.com/w3c-fedid/CrossSiteCookieAccessCredential](https://github.com/fedidcg/CrossSiteCookieAccessCredential)  
    * [https://github.com/w3c-fedid/Multiple-IdP](https://github.com/fedidcg/CrossSiteCookieAccessCredential)  
    * [https://github.com/w3c-fedid/Button-Mode](https://github.com/fedidcg/CrossSiteCookieAccessCredential)  
    * [https://github.com/w3c-fedid/IdP-Registration](https://github.com/fedidcg/CrossSiteCookieAccessCredential)  
    * [https://github.com/w3c-fedid/Params](https://github.com/fedidcg/CrossSiteCookieAccessCredential)  
    * [https://github.com/w3c-fedid/Continuation](https://github.com/fedidcg/CrossSiteCookieAccessCredential)  
    * Etc  
  * Related [issues are transferred](https://docs.github.com/en/issues/tracking-your-work-with-issues/transferring-an-issue-to-another-repository) from [https://github.com/fedidcg/fedcm](https://github.com/fedidcg/fedcm) to [https://github.com/w3c-fedid/awesome-proposal](https://github.com/fedidcg/fedcm)  
* ~~The current FedCM spec moves to Stage 2 as a [First Public Working Draft](https://www.w3.org/policies/process/drafts/\#fpwd)~~   
  * ~~The FedCM [FedID Community Group](https://www.w3.org/community/fed-id/) repo gets transferred to the [FedID Working Group](https://www.w3.org/groups/wg/fedid/), i.e. [https://github.com/fedidcg/fedcm](https://github.com/fedidcg/fedcm) moves to [https://github.com/w3c-fedid/fedcm](https://github.com/w3c-fedid/fedcm)~~  
  * ~~The list of open concerns for Stage 3 is identified by the Working Group members and labeled as “stage-3-concerns”go~~  
* ~~We mark the [https://github.com/fedidcg](https://github.com/fedidcg) organization as archived~~

# GC

* Stage 0: the definition of the Problem  
  * What’s required to enter it?  
    1. Nothing: no permission needed from anyone. Anything goes: An issue, a personal repo, a blog post, a tweet, etc  
  * What gets produced during it?  
    1. A champion  
    2. A github repo (anywhere) or issue (for small features)  
    3. A Problem Statement  
* Stage 1: the acknowledgement of the Problem  
  * What’s required to enter it?   
    1. What gets produced by the previous stage  
    2. The [FedID Community Group](https://www.w3.org/community/fed-id/) consensus that the problem is worth working on  
  * What happens when you enter it?   
    1. The github repo gets created/transferred to the [https://github.com/w3c-fedid](https://github.com/fedidcg) github organization for the proposal, e.g. [https://github.com/w3c-fedid/awesome-proposal](https://github.com/fedidcg/awesome-proposal)   
  * What gets produced during it?  
    1. An explainer  
    2. A specific **proposal** under consideration (with varying degrees of specificity, e.g. multiple options under consideration, code examples, a Spec Diff \- e.g. [a Monkey Patch](https://www.w3.org/TR/design-principles/\#monkey-patch) or a spec PR \-, etc)  
    3. **Alternatives** considered  
    4. A series of **issues** filed by the [FedID Community Group](https://www.w3.org/community/fed-id/) in the repo  
*  Stage 2: the acknowledgement of the Solution  
  * What’s required to enter it?  
    1. What gets produced by the previous stage  
    2. The [FedID Working Group](https://www.w3.org/groups/wg/fedid/) has reached consensus consensus to adopt the solution as the basis for their work (but doesn’t necessarily need to agree that the specific solution is perfect)  
  * What gets produced when entering?   
    1. The WG identifies a list of (seemingly resolvable) issues that have to be addressed before Stage 3  
    2. The [FedID Community Group](https://www.w3.org/community/fed-id/) repo gets transferred to the [https://github.com/w3c-fedid](https://github.com/w3c-fedid) org:  
       * Example: [https://github.com/w3c-fedid/awesome-proposal](https://github.com/w3c-fedid/awesome-proposal)   
    3. The spec PR (if any) gets merged into the Editor’s Draft  
  * What gets produced during it?  
    1. The Editor’s draft matures  
    2. The list of issues identified by members gets resolved  
    3. Web Platform Tests are introduced  
  * What is the effect?  
    1. Signaling to users and developers that this is the path being pursued for implementation  
    2. Starting the W3C Patent Policy to secure  [royalty-free patent commitments](https://www.w3.org/policies/patent-policy/20200915/) at the expiration of a [patent exclusion opportunity.](https://www.w3.org/policies/patent-policy/\#exclusion-opportunity)  
* Stage 3: the consensus of the Solution  
  * What’s required to enter it?   
    1. What gets produced by the previous stage    
    2. The [FedID Working Group](https://www.w3.org/groups/wg/fedid/) has reached consensus that the current [Editor’s Draft](https://www.w3.org/policies/process/drafts/\#editors-draft) / [Working Draft](https://www.w3.org/policies/process/drafts/\#RecsWD) or the Spec Diff (e.g.[Monkey Patch](https://www.w3.org/TR/design-principles/\#monkey-patch) or Spec Branch PR) is ready to be merged and needs to gather further implementation experience  
       * The members feel like the list of issues is sufficiently resolved  
  * What gets produced when entering?  
    1. The Spec Diff (e.g. [Monkey Patch](https://www.w3.org/TR/design-principles/\#monkey-patch) or Spec Branch PR) gets merged into the Editor’s Draft / Working Draft   
    2. The proposal repo [https://github.com/w3c-fedid/awesome-proposal](https://github.com/w3c-fedid/awesome-proposal) gets archived  
    3. The [Working Draft](https://www.w3.org/policies/process/drafts/\#RecsWD) gets snapshotted into the latest [Candidate Recommendation](https://www.w3.org/policies/process/drafts/\#RecsCR) to represent that the Working Group agrees that the Working Draft has sufficiently resolved the list of issues  
       * Working Draft \+ Issues resolved \= Candidate Recommendation  
* Stage 4: from Candidate Recommendation to Proposed Recommendation  
  * What’s required to enter it?   
    1. The broad W3C members have reached consensus that the specification is done and ready to be implemented  
  * What is required?  
    1. Two Independent interoperable Implementation (as per Success Criteria)  
  * What gets produced when entering?  
    1. The [Candidate Recommendation](https://www.w3.org/policies/process/drafts/\#RecsCR) gets snapshotted into a [Proposed Recommendation](https://www.w3.org/policies/process/drafts/\#RecsPR)
