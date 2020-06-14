# D5 Constitution

## Purpose: why D5 exists
[D5](https://d5.ai/) is a decentralized autonomous organization (DAO) of data scientists and engineers. It was created by and for individuals who believe in a “third way” between employment and individual freelancing.

D5 exists with three purposes:
1. create **rewarding work** for our **members and associates**,
1. provide **maximum value** for our **clients**,
1. accomplish **more together** than we could individually.

## Mechanics: how D5 operates
### Executive Summary
1. Decisions are ratified via DFS votes
1. Earnings are made from client work being relayed between members
1. Products are created from a venture model that involves pooling risk and rewards
1. Non-billable contributions to D5 are rewarded with DFS
1. New members must be recruited, and require a financial contribution to D5
1. Members can leave at anytime and receive a proportional share of the D5 funds

### 1. Votes: how we decide
D5 is governed via [D5 Shares (DFS)](https://etherscan.io/token/0x683EcFe5B148c8840998c1B4884F60a8eAD432D1):
1. Votes are settled via proportional tokenholdership such that 1 DFS = 1 vote.
1. Voting period is 72 hours from when a vote has been created.
1. A strict majority (>50% of voting tokens) is required to pass a vote.
1. Furthermore, a quorum of 25% of the total DFS supply is required to pass a vote.

### 2. Relays: how we earn
**Relays** take place when one member passes on (i.e. relays) work to another member. Relays are the main source of cash flow for D5.

A successful relay transaction involves two parties, the Relayer and the Relayee - both of whom are D5 members. The Relayer is the person or entity that brings a client or project into D5, and the Relayee is the one billing the client (directly or indirectly).

The **relayer fee** is a simple revenue share, where the Relayee pays the Relayer a % of the amount billed for ordinary work (excluding sales taxes, paid travel arrangements and other direct expenses). The fee is paid after the Relayee has successfully received payment from the client, and the total amount paid in relayer fees for a single client is capped at US$Y.

Furthermore, a **network fee** is paid to the DAO itself when a relay takes place. In return, both Relayer and Relayee receive **bounties** in the form of DFS. The bounties represent an increase in ownership of the DAO.

Eligibility of the bounty is subject to the scrutiny of biweekly bounty meetings (in the extreme case, proof of billing a client and payment of relayer fee must be presented), and payment is due quarterly along with normal bounties.

We summarize the overall relay model as follows:
1. Relayer fee: *R*% paid in DAI from relayee to relayer
1. Network fee: *N*% paid in DAI to DAO
1. Relayer bounty: *B<sub>R</sub>*% in DFS minted and paid to relayer
1. Relayee bounty: *B<sub>E</sub>*% in DFS minted and paid to relayee

The DAO votes on the parameter values *R*, *N*, *B<sub>R</sub>*, *B<sub>E</sub>*.

#### Current parameter values
Currently the parameters are set as follows:
1. *R* = 9%
1. *N* = 5%
1. *B<sub>R</sub>* = 10%
1. *B<sub>E</sub>* = 10%

### 3. Ventures: how we create
Collectively, we put any work that involves sweat equity (i.e. getting equity for work instead of cash) under the umbrella of **venture**.

Our venture model aims to be an effective model that maximizes the chance of success of the venture, and distributes risk and reward fairly among venture participants.

Having such a model minimizes transaction costs, as it gives us a default structure that we can use - instead of spending efforts on how to structure new ventures.

There are three principal entities in the venture model:
1. **DAO**: the D5 organization
1. **Contributor**: a D5 member that works on the venture
1. **Product**: the project or startup in question - i.e. what’s being built

![Venture Participants](/assets/d5_venture.svg)

The relationships between these entities are as follows:
1. DAO provides **cash** and **equity** (DFS) to Contributor
1. Contributors provides working **hours** to a Product
1. Products provide **equity** to DAO, and also receive **access to network assets** from DAO

#### Example
This will become clearer in a specific example:
1. Product has a valuation of $150k
1. DAO hourly rate is $150/hour (so valuation can be expressed as 1,000 D5 hours)
1. Product offers up to 10% equity to DAO in return for 100 D5 hours
1. Contributor delivers the 100 D5 hours
1. DAO pays contributor [$50 + 100 DFS] / hour (Example cash share, assuming $1 = 1 DFS)

The end result after the transaction is:
1. DAO has received 10% share of Product
1. DAO has paid $5k
1. DAO has minted 10k new DFS (inflation)
1. Contributor has received $5k
1. Contributor has received 10k DFS (ownership of DAO)
1. Contributor has delivered 100 hours
1. Product has received 100 hours
1. Product has paid 10% equity

(In addition, Product may have benefitted from D5 network assets: exposure via Twitter and Discord; introductions to customers and investors; etc.. For simplicity we leave this out of the “balance sheet” above.)

Here are the parameters that go into this model:
1. **Valuation**: what is our best estimate of the Product at this point in time?
1. **Equity**: what share of the Product is offered to DAO?
1. **Rate**: what is the market rate of a DAO contributor?
1. **Cash**: what share of Contributor compensation is paid in cash?

In the example above
1. **Valuation**: $150k
1. **Equity**: 10%
1. **Rate**: $150/hour
1. **Cash**: 33%

For simplicity, we’ll refer to these parameters via their acronym **VERC**.

Note that this model works for both external products/startups, and internally-driven products. Furthermore, the Equity parameter could be floating, meaning that under a fixed valuation, it can simply increase as more work is delivered. However, it’s recommended to agree on a max equity share, as this serves as a form of budget.

The decision of *which Products the DAO invests in*, is decided via DAO voting, as usual.

#### Current parameter values
*VERC must be set on a case-by-case basis. Hence we do not have fixed parameter values.*

### 4. Bounties: how we contribute
Certain activities require contributions from D5 members where no cash-flow is involved. Examples include taking meeting notes, growing our social media accounts, or updating our website.

In these cases, **bounty** hunters are rewarded with DFS for their contributions.

There are two processes for bounty payouts:
1. **Bounty sessions**: deliverables are created and added to our bounty board based on what D5 members believe the network needs. Bounty hunters can then pick these deliverables (bounties) up and be rewarded by increasing their proportional ownership of D5. Bounty sessions represent the **top-down** creation of internal contributions.
1. **Recurring payouts**: a fixed amount of *N* DFS gets minted and distributed every month. D5 members can do what they see as valuable work for D5, with no bureaucracy, and then nominate themselves to receive a share of the recurring bounty. Any payout can be veto-ed by triggering a vote, so the D5 DAO ultimately still has control. Recurring payouts represent the **bottom-up** creation of internal contributions.

Recurring bounties were introduced to avoid stagnation of the network, making it more autonomous. In general, bounties can be seen as a way to bootstrap the network’s autonomy - similar to how Bitcoin and Ethereum both reward miners with their native tokens for performing proof-of-work.

#### Current parameter values
Currently, the recurring payouts are *monthly*, with *N* = 1000 DFS. This corresponds to approximately a 22% annual inflation of the DFS supply (ceteris paribus).

### 5. Memberships: how we join
New members are brought into the D5 DAO via a **JoinDAO** function. When executed by an existing DAO member X for a new candidate member Y, this triggers a vote on whether Y should be accepted into the D5 DAO.

If the vote passes with a positive vote, the following happens:
1. *Y* pays ADMISSION_FEE (in DAI) to the DAO wallet
1. *Y* receives newly minted ADMISSION_TOKENS (in DFS) from the DAO
1. *X* pays RECRUITER_FEE (in DAI) to the DAO wallet
1. *X* receives newly minted RECRUITER_TOKENS (in DFS) from the DAO
1. *Y* gains partial ownership (proportional to DFS tokens held, as always) and access to all common D5 assets, including:
   1. Discord group
   1. Website admin
   1. Profile on D5 website
   1. D5 as current position on Linkedin
1. In the first TRIAL_PERIOD months, either *Y* or the DAO can choose to reverse all the transactions above. In the case of the DAO, such a reversion is triggered via a vote, as usual. In the case of a reversion, all DFS earned within the trial period by *Y* will be burned.

The existence of these parameters and mechanisms needs some justification:
- ADMISSION_FEE: Gives the new member “skin in the game”. Furthermore, it means that a new member cannot “free-ride” on the value created by the existing DAO members.
- ADMISSION_TOKENS: Represents the partial ownership and influence in the DAO, and is what is effectively paid for by the ADMISSION_FEE
- RECRUITER_FEE: Gives the recruiting member “skin in the game” in that they are willing to invest financial assets into the DAO, believing that it becomes more valuable with the new member
- RECRUITER_TOKENS: Represents a bounty which is given in return for recruiting the member and paying the RECRUITER_FEE
- TRIAL_PERIOD: Exists to give both the new member and the DAO a way out of the arrangement without having to trigger a ragequit. There might be reasons why this was not a good match between DAO and member.

#### Current parameter values
Currently the parameters are set as follows:
1. ADMISSION_FEE = 500 DAI
1. ADMISSION_TOKENS = 500 DFS
1. RECRUITER_FEE = 250 DAI
1. RECRUITER_TOKENS = 500 DFS
1. TRIAL_PERIOD = 90 days

### 6. Exits: how we leave
We need a mechanism for how to handle members **leaving** D5; without one we have two problems:
1. For the individual member: If they decide to leave D5 with no exit mechanism, they are left with nothing, even if they have made contributions.
1. For the DAO overall: Members who do not believe in the D5 project are stuck as non-productive members, which will limit the progress of the DAO.

We should think about the DAO: *“All the non-believers have left. Thus, **I can believe in those that are still here, more”*** (cf. [Simon de la Rouviere](https://medium.com/@simondlr/burning-bridges-to-greener-grass-incentivizing-tokenized-forking-393c69dfecab)).

Exits are handled by an **ExitDAO** function, which when triggered by member X, does the following:
1. Burns all of X’s DFS tokens
1. Gives X a share of the D5 wallet’s funds proportional to the DFS tokens just burned
1. Removes ownership and/or access to all common D5 assets, including (but not limited to):
   1. Slack group
   1. Website admin
   1. Discord role
   1. Cloud assets (e.g. GCP, AWS)
   1. Profile on D5 website
   1. D5 as current position on Linkedin

To make point 2. above more explicit: if the total supply of DFS is *S*, and member *M* burned *T* DFS tokens, then *M* will receive *T/S* of all the assets in the DAO’s wallet at the time of executing the ragequit.

An ExitDAO can be executed at any time. Crucially, this includes in the middle of a vote, as this is when certain disagreements might manifest themselves.
