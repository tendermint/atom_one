# ATOM ONE CONSTITUTION 

_NOTE: THIS IS A DRAFT; MAKE A PR BEFORE IT BECOMES FINAL!_

_This document is a work in progress. This document assumes familiarity with
the current workings of cosmoshub4 as of Oct 11th 2022. What is described here
are modifications to what already is. This clause will be removed with future
revisions, and the corresponding parts of the document updated with a full
description of the constitution of the hub._

_This proposal will be proposed concurrently along with the ATOM ZERO proposal
and the ATOM2.0 proposal._

## Preamble

We the people of the Cosmos, in order to create a free world, enable voluntary
and borderless transactions, facilitate permissionless innovation, ensure
economic security, cater for economic and technological development, allow for
the creation of sovereign zones, and maintain order among sovereign zones, do
ordain and establish this Constitution for the Cosmos Hub.

## Part 0 Definitions

Cosmos is the interchain network composed of many sovereign zones connected by
IBC.

A zone is an independent chain (or an application hosted on a parent chain)
with a well defined governing body or bodies that dictate the governance and
economic rules internal to that zone. A zone by definition is sovereign or
partially sovereign. A treasury DAO of the Cosmos Hub is partially sovereign.

IBC is short for Interchain Blockchain Communication, and includes all
protocols that allow one chain to communicate state or messages with another
chain by tracking the consensus state of the other.

The ATOM is the primary staking token of the Cosmos Hub.

The PHOTON token is a fixed supply (deflationary) representation of ATOM used
for ICS2 staking across other blockchains.

ICS is short for Interchain Security, and includes all protocols that allow the
consensus of one chain to be partially or wholly secured by mechanisms on
another chain.

ICS1 also known as Simple Replicated Security, includes all protocols where the
validator set is simply replicated across multiple blockchains and slash
conditions are always submitted to a root chain.

ICS2 includes all protocols where slash conditions for complex failure
scenarios of one validator set are handled by another validator set, where
slashing affects tokens on the latter validator set.

ICS2A includes all protocols of ICS2 where the ownership of PHOTONs are
entirely managed on the Cosmos Hub.

ICS2B includes all protocols of ICS2 where the ownership of PHOTONs are
entirely managed by logic of the other chain.

Auto-staking is staking across all current validators in proportion to their
voting power. For example, if a validator that had 10% of the voting power were
to get slashed 30% on the Cosmos Hub, and 50% of ATOMs were either staked onto
the Cosmos Hub or free (not bonded to PHOTONs), everyone who auto-staked ATOMs
on the Cosmos Hub would get slashed 1.5%. Inflationary ATOMs are paid to
auto-stakers such that they do not suffer from the inflation rate of ATOMs.

A two thirds supermajority is where more than 2/3rd of all participating staked
ATOMs votes YES and the vote is above the current governance quorum value and
the voting period has concluded. ABSTAIN votes do not count toward the 2/3.

## Part 1 General Provisions

### Article 1.A. Fundamental Principles

This Constitution of the Cosmos Hub, hereinafter “the Constitution” hereby
establishes the foundations of the governance model, economical model, and
operating system of the Cosmos Hub.

All subsequent governance proposals must be in alignment with the provisions of
the Constitution, and each proposal's proponents and all active governance
voters are required to ensure consistency between such proposals and the
Constitution.

### Article 1.B. Sovereignty of the Cosmos Hub

The Cosmos interchain network is composed of many sovereign zones such as the
Cosmos Hub.

The Cosmos Hub is composed of many chains including the root hub chain where
staking and governance transactions are committed and executed, but also other
chains secured by ICS that are subservient to the governance of the root hub
chain, hereinafter "Hub Governance".

Other sovereign zones that are completely or partially secured by Cosmos Hub
ICS by definition have their own governance mechanism, and the Cosmos Hub
principally enables and follows the will of the governance of such sovereign
zones with regards to the pegged tokens originating from said zones, except in
well defined exceptional circumstances that involve bugs, theft, or harm to the
Cosmonauts of the Cosmos ecosystem.

### Article 1.C. General Mission and Objectives

The mission of the Cosmos Hub is to create a new world allowing for
permissionless yet secure interactions between the Cosmonauts of Cosmos in the
Solar system.

The objective of the Cosmos Hub is to provide a classical BFT proof-of-stake
multi-token payment and transfer system; and to scale the security of the
platform to many applications hosted in other zones via Cosmos Hub ICS.

### Article 1.D. Cosmonauts

Every person has the right to become a Cosmonaut and can freely engage on the
Cosmos Hub. As such, every Cosmonaut has the right to own at least one address
on the Cosmos Hub.

Any Cosmonaut can also become a Citizen of the Cosmos Hub by using their
address to stake ATOMs toward the Cosmos Hub and participate actively in
governance. The status of citizenship is granted in an autonomous manner.

### Article 1.E. Rights, Liberties, and Obligations in the Cosmos Hub

The Liberty and Property of all Cosmonauts engaging in the Cosmos Hub is hereby
guaranteed. Any restriction to the Liberty and Property of Citizens on the
Cosmos Hub can be done only through the Cosmos Hub's governance.

Every Cosmonaut has the right to receive benefits from their engagement in the
Cosmos Hub, including rights derived from held or staked ATOMS in line with the
provisions of this Constitution.

Every Citizen allows the Governance of the Cosmos Hub to restrict their staked
ATOM property by partial or full slashing according to their voting activity.

The Core Values of the Cosmos Hub are transparency, accountability, honesty,
(BFT) robustness, security, and simplicity.

Every Cosmonaut allows any other Cosmonaut to create full or partial airdrops
of new tokens to any chain using the distribution of any token on the Cosmos
Hub at any time.

Every Citizen allows any Cosmonaut to modify their pro-rata of their airdrop
portion by partial or full slashing based on their cryptographic voting
activity according to well defined principles at any time.

## Part 2 Governance

### Article 2.A. The Cosmos Hub Chain

The root hub chain of the Cosmos Hub is uniquely identified by chainid
"cosmoshub". This chain commits and executes transactions that serve the
following functions:

 * governance voting
 * ATOM and PHOTON staking
 * ATOM <-> PHOTON conversion
 * intra-hub token transfers
 * IBC token transfers
 * ICS1 and ICS2 management

### Article 2.B. Cosmos Hub governance

The working language of Cosmos Hub governance is English.

The quorum necessary for a proposal to be valid shall depend only on number of
bonded ATOMs, and not on the number of PHOTONs.

The total voting power for all bonded PHOTONs shall not exceed the total voting
power of all staked ATOMs.

PHOTONs bonded for ICS2 hosting according to whitelisted ICS2A and ICS2B
protocols may vote in Cosmos Hub governance proposals.

The governance process must extend the voting deadline to ensure at least 2
weeks of voting after the minimum quorum has been met.

UX interfaces that present the results of voting on governance proposals should
also display the content of the memo field of each voting transaction such that
the reason for the vote can be seen.

TODO: fill in rules of cosmoshub4 governance.

### Article 2.C. Memorandums

The same system as that of governance proposals may be used to pass or reject
memorandums that shall have no effect upon the governance of the system.

Memorandums may be used to notify Cosmonauts of behavior from validators and
key executives of validators, as well as prominent members of the Cosmos Hub,
of behavior that violates the Core Values of the Cosmos Hub. Voting should
depend solely on the evidence provided on the memorandum proposal. Incomplete
proposals should be rejected with a NWV vote.

### Article 2.D. Treasury DAOs

The Cosmos Hub governance may establish one or more transparent and accountable
Treasury DAOs by simple majority vote.

The operations of the Treasury DAO must operate on an ICS secured zone outside
of the hub. As an exception, the tokens of the Treasury DAO may reside on the
the Cosmos Hub as a m-of-n multisig account where n is at least 3 and m is at
least 1/2 of n, where each signatory is an authorized member of the Treasury
DAO and Citizen of the Cosmos Hub.

The Treasury DAO shall be composed of Cosmonauts, and at the top Executive
Board level be composed of one or more Citizens. All Cosmonauts and Citizens of
Treasury DAOs including their Oversight Committee must have public and known
real personal identities. 

To enable the well-functioning of Treasury DAOs and the separation of powers in
the utmost interest of the Cosmos Hub, each member can hold just one type of
role within each Treasury DAO.

The members of the DAO must perform efficiently in their role in line with
their job description. They are accountable to each DAO’s Oversight Committee
and the Hub Governance. They can be dismissed from their functions by a
two-thirds majority vote by the DAO’s Oversight Committee or the Governance
Hub.

The role and functions of the Executive Board shall be further developed
through governance proposals within each DAO, unless the DAO chooses to defer
to Cosmos Hub governance by Citizens.

Each Treasury DAO shall have an Oversight Committee composed of any number of
Cosmonauts. The Oversight Committee must have at least the right to freeze all
transfers of tokens from the Treasury or its designated m-of-n multisig account
on the Cosmos Hub.

## Part 3 Economics

### Article 3.A. Economic model

The one and only economic incentive model of the Cosmos Hub is the collection
of market-based transaction fees from a large number of transactions across all
the chains secured by the staking of ATOMs on the Cosmos Hub including ICS1
hosted blockchains, and the staking of PHOTONs for ICS2 secured blockchains.

### Article 3.B. The ATOM Token

The ATOM functions as voting shares, economic incentive shares, and security
bond for the Cosmos Hub.

To preserve the security and identity of the acting governance and validator
set, the inflation rate of the ATOM is made to vary over time to target 2/3 of
all ATOMs. The maximum inflation rate is 20% non-compounded per year.  There is
no minimum inflation rate, and it can even be negative (deflationary).

Inflated ATOMs are paid to bonded ATOM holders in proportion to each
delegator's staking amount.

Staked ATOMs are converted to Bonded Share Units.

The Atom Unbonding Period shall be 3 weeks.

Redelegation is allowed twice per Atom Unbonding Period for any delegation.

Double signing at any height/round/step results in slashing penalty that is
proportional to the total amount of double signing by all validators for that
height/round/step, with evidence collected during the Atom Unbonding Period;
the penalty shall range from +0% to 100% of the Upper Slashing Limit in linear
proportion, the latter when 1/3 of voting power double-signs.

Complex signing failures (those that require +1/3 to coordinate) shall result
in slashing the Upper Slashing Limit.

The Upper Slashing Limit shall be 50%. This parameter may be increased by a two
thirds majority of the Cosmos Hub. In cases where there is sufficient evidence
of malice and intent, this parameter may be overruled by a simple majority of
the Cosmos Hub on a per-case basis up to 100%.

Liquid staking may only be supported through interchain accounts (aka
non-native liquid staking).

To limit the amount of liquid staked tokens so as to reduce systemic risk from
liquid staking, there shall be imposed a 5% tax (the "Liquid Staking Tax") on
all rewards paid out to staked interchain accounts at time of reward
withdrawal. This Liquid Staking Tax parameter may be adjusted by a two thirds
supermajority vote of the Cosmos Hub. 

If the amount of ATOMs staked using interchain accounts exceeds 20% (the
"Liquid Staking Factor") of the total staked ATOMs, the Liquid Staking Tax
shall automatically increase by 1% per month. The Liquid Staking Factor
parameter may be adjusted by a two thirds supermajority vote of the Cosmos Hub.

TODO: simplify the above two rules.

### Article 3.C. The PHOTON Token

The PHOTON distribution shall be created by mechanism similar to auto-staking
ATOMs called "ATOM to PHOTON bonding". For the purpose of ATOM to PHOTON
bonding, transaction fees are not paid to the ATOM to PHOTON bonders, and the
bonded ATOMs are not included in the target two thirds ATOMs staked for the
Cosmos Hub.

The exchange rate formula from ATOMs to PHOTONs shall be such that if all the
ATOMs not already bonded into PHOTONs were to be bonded to PHOTONs, there would
always be 1 billion PHOTONs. This is a succinct but true invariant of the
system. Consequently, the number of PHOTONs is capped and will never reach 1
billion PHOTONs (because the number of ATOMs in existence must be greater than
0 for there to be any validators).

The Photon Equivalent of Atoms is equal to 1 billion minus the number of total
existing PHOTONs. If all ATOMs were to become bonded as PHOTONs, there would be
an additional inflation of the Photon Equivalent of Atoms.

In order to prevent hostile takeover of the Cosmos Hub, the following
restrictions shall apply in converting PHOTONs back into ATOMs:

 * Each month, there shall be a total allowance of 2% of the Photon Equivalent
   of Atoms (the "Monthly Photon Equivalent Allowance") that can become
   unbonded into ATOMs. This restricts the total amount of ATOMs that may
   become unbonded from PHOTONs.

 * There shall be a monthly auction where PHOTON holders may elect the number
   of PHOTONs they wish to convert to ATOMs with a minimum required conversion
   limit factor ranging from 0% to 100%. A limit of 0% is like a market order,
   and means the user wishes to get a pro-rata of the available Photon
   Equivalent of Atoms available for conversion that month. A conversion order
   with limit of 100% will not execute if the total number of PHOTONs bidding
   to convert to ATOMs exceeds the Monthly Photon Equivalent Allowance.

 * The auction shall start on the first day of the month and last for a week.

 * If the amount of PHOTONs being converted back to ATOMs exceeds the Monthly
   Photon Equivalent Allowance, the ATOMs bonded for the difference shall be
   considered burned at the end of the auction period.

The PHOTON shall be the only staking token for ICS2 staking. 

When PHOTONs are burned via ICS2 slashing on a zone, or when burned as
transaction fees, or burned for any reason, their burn amount must be reported
back to the Cosmos Hub via IBC. The amount will be deducted from the PHOTON
balance of the zone. Because of the invariant that there shall always be 1
billion PHOTON equivalent, burning PHOTONs in this way is beneficial to the
ATOM holders. On the other hand, burning ATOMs say through slashing on the
Cosmos Hub does not change the number of PHOTONs in circulation, such that the
relative market cap of the remaining ATOMs can be better preserved for the sake
of the Cosmos Hub's security.

The PHOTON shall be whitelisted as transaction fee payments for the Cosmos Hub
and all ICS1 and ICS2 hosted blockchains.

### Article 3.D. Inflation

Any inflation of ATOMs to the Community Pool or a designated Treasury DAO
beyond the default inflation rate described in the Constitution shall require a
two thirds supermajority vote of a special inflation governance proposal type.

The special inflation proposal can include a description of the purpose of the
inflation, but cannot include any other modifications to the Cosmos Hub or its
Constitution, nor the adoption of any new Treasury DAOs.

### Article 3.E. The Common Pool 

The Common Pool tax proceeds shall apply to transaction fees and inflationary
ATOMs, and shall be sent to the Community Pool.

The Common Pool Tax rate shall initially be 2%, but can be increased up to 50%
by two thirds supermajority of the Cosmos Hub governance.

### Article 3.F. The Interchain Security (ICS) Systems

While the ATOM is the only token allowed for staking on the Cosmos Hub, thereby
allowing validators to also partake in ICS2 hosting of Consumer Chains, the
PHOTON is the only token allowed for ICS2 hosting.

2% of the transaction fees earned from ICS2 hosting shall be paid to the ATOM
holders staked toward the Cosmos Hub (the "ICS2 Tax"). The ICS2 Tax parameter
may be adjusted by a two thirds supermajority of Cosmos Hub governance, with
the constraint that it may not increase by more than 1% per year. For clarity,
if the ICS2 Tax is 2% today, it may not be higher than 3% within a year.

The ICS2A systems must ensure a reasonable Nakamoto coefficient for each zone.
This shall be accomplished, among other means, by selecting validators from
similar tiers of bonded photons, where the largest tier is no larger than 3
times the size of the smallest tier. Each validator may elect to disclose their
true geographic location as well as the location of all backup systems, or they
may elect to remain geographically unlocated.

Sovereign zones secured by ICS2B systems must allow its delegators' votes to be
represented pro-rata according to the explicit and manual voting activity via
the primary staking token of that zone; thus its participation in Cosmos Hub
voting through the PHOTON shall be represented by a distribution of choices.
Staking token holders of the zone who abstain or do not vote must also count
toward non-voting (rather than the ABSTAIN option) on the Cosmos Hub.

### Article 3.E. The Crypto Court System

TODO add details of ICS1/ICS2 and custom court procedure.

## Part 4 Final Dispositions

## Article 4.A. Updates to the Cosmos Hub

New updates to the Cosmos Hub should be broken down into independent components
and discussed/proposed separately with adequate time between, regardless of any
omnibus whitepaper. 

## Article 4.B. The Implementation

The Cosmos Hub shall not have any VM functionality, but shall be plainly
implemented in a single garbage collected language as reference (namely Go);
and other clients may implement all or portions of the stack in another
language like Rust.

The only cryptographic assumptions allowed to be used by the Cosmos Hub
including its consensus protocol shall be Ed25519 and Secp256k1 elliptic
curves, and RIPEMD160 and SHA256 hash functions.

No zero-knowledge proof systems may be adopted on the Cosmos Hub even if they
are composed of the approved primitives.

The rules of this article may only be changed by two thirds supermajority vote
of the Cosmos Hub.

## Article 4.C. Compute/storage/memory limitations

For the sake of decentralization, accessibility, accountability, and security,
the Cosmos Hub and each ICS zone shall be restricted such that each can run on
a commodity computer.

## Article 4.D. Amendment of the Constitution

This constitution may be modified or additional parts and rules appended by two
thirds supermajority of Cosmos Hub governance.

<hr />

# COMMENTARY

_This is not part of the Constitution_

## About the PHOTON

The PHOTON is intended to be a deflationary representation of ATOMs.

## Comments from Jae Kwon

### About the economic model

The notion that ATOM is a "memecoin" ignores the obvious and original business
model for the hub -- token transfer fees. Bitcoin and Ethereum gas transaction
fees are in the 10s/100s of millions, and we haven't even gotten to VISA scale
yet. ATOM is not money, it's VISA shares, IBM shares, and FED shares (but where
ATOM stakers are general partners rather than limited partners).

It's an alternative to the status quo that Bitcoin originally wanted to be, but
more. Well, imagine what kind of social manipulation we must be under, to be
pursuing such a dream.

The best part is we've done most of the work already. With minimal ICS the
simple-transfer-zones are already more or less done. We're 90% done with
massive scale MVP, and after that scaling will be relatively easy. AND this
ATOM1 hub is a minimal hub that zones will want to use. The product market fit
is already there. It's simple, and we are already positioned for it. It is
neutral to application zones that provide more functionality than token
transfers.

As IBM's CEO once said, the secret cash cow of IBM is transaction processing.
> IBM Mainframe=FT, Tendermint=BFT

Cosmos is the VISA network built upon this decentralized BFT mainframe system.
Always was, and should remain.

New functionality can always be permissionlessly added on top of this base
ATOM1 framework. The gno.land prop69 #exitdrop is a demonstration of value-add
to the Cosmos Hub, as it will provide Gnolang smart contracts while IBC pegging
to the Cosmos Hub for tokens.

Using ICS, it should be possible to run new Gnolang VM powered zones secured by
the Cosmos Hub, but also IBC connected to the gno.land chain for importing
logic hosted on the gno.land "github" (and paying gas fees & license fees to
each).

### The need for hubs

Say there are 10,000 zones. Say a zone fails and it requires manual
intervention.  With 10,000 IBC connections you require 10,000 zones to all
agree on recovery procedure; will never happen. But a zone connected to a more
secure hub will be protected when it needs intervention.

Another need for hubs; uniformity of guarantees. You need a hub to coordinate
shard zones where governance/policy and staking gets applied to all shards.
Otherwise, you don’t have one system of guarantees, you have many independent
chains. Need to scale sendtx, might as well ICS.

### About ATOM2.0

I'm not against all the ideas of ATOM2. Some ideas are genuinely interesting. I
just think we should do it on ATOM1, and use PHOTONs. That is, ATOM2 ->
PHOTON1.

Pretty much all the proposals in the ATOM2 paper can be implemented on top of
ATOM1 (see github link above for draft) on the PHOTON token on separate zones
implemented permissionlessly. The Allocator service zone could be implemented
by anyone and secured by ICS, and use PHOTONs as the counterparty token in
AMMs. The Scheduler likewise can be implemented permissionlessly and use
PHOTONs as payment token. Zones can choose to use whatever scheduling or
allocation system they want. ATOM1 allows governance to approve of inflation of
PHOTONs for any particular purpose such as this.

The main benefit of allowing permissionless implementation of the allocator and
scheduler is that it allows competition of implementation. For example, there
are alternative ways to implement the Scheduler that is different than ABCI++;
it can be implemented as an extension to ABCI to allow Tendermint to allocate
different priority mempools for different transaction types. This isn’t what is
proposed in ABCI++ but IMO the first step to solving pay-for-priority. We don’t
have to solve this by commitee, we can let the free market decide what solution
is actually preferred.

The proposed treasury inflation is ludicrously high. - there was another tweet
by someone extolling the virtues of treasury funding, of how 100,000 ATOMs were
able to accomplish so much. The ATOM2.0 proposal creates FIVE HUNDRED (500)
TIMES as much to go into treasury in the first year alone. Not only are there
enough funds within the ICF alone to complete the featureset of the Cosmos Hub,
it is certainly unnecessary to inflate so much in addition. No single
centralized entity can responsibly distribute such funds in a responsible way.
In fact, it will lead to failure. Queue all the crypto projects that raised so
much money that are not even breaking even. EOS comes to mind, but there are
numerous examples.

Instead, the proposal for the ATOM ONE constitution here proposes the adoption
of one or more Treasury DAOs that can be funded as needed; slowly at first,
with more funding to come from the community pool as the Treasury DAO proves
itself.

Described in the constitution also are a way for the ICF to defer to a Treasury
DAO for execution and decisions, while still maintaining control over the
distribution of funds via a m-of-n multisignature account on the hub, thereby
having ultimate veto power.

Also, the tax system may be used to allocation a portion of ATOM inflation to
fund the common pool.

Also, with two thirds supermajority vote, more ATOMs can be allocated for any
purpose.

### About security, and the need for ATOM/PHOTON separation

I do see the “monification” of ATOM as per ATOM2.0 to be fundamentally flawed,
for a chain whose main selling point is SECURITY. I believe ETH2.0 with its ETH
staking is similarly flawed. I fear that we won’t realize it until it is too
late. We can prevent future disasters.

The staking ratio today on Ethereum PoS is 12%. With massive adoption, unless
we have complete laymen involved in staking, and with ETH becoming money, the
stake ratio should fall even lower, perhaps even to <1%. At that point it
becomes easy to coordinate a fund to take over the consensus process of the
chain. PoW networks have two “tokens” the mining infrastructure (which can be
bought or sold, and also is “inflationary”) and the coins themselves. This
separation allows Bitcoin to become widely adopted without worrying about
security vulnerabilties, because even the largest of whales cannot simply buy
1/2 of mining infrastructure. It isn’t a superfluid market, which makes it more
secure.

(In biology, it’s the difference between Eukaryotic (cell nucleus) and
Procaryotic (no nucleus) cells. Evolution has proven that multicellular
(inter-cellular) systems like us are generally Eukaryotic. They both exist, but
complexity demands more intracellular security.)

Imagine how easy it would be to create a fund and simply buy VISA… well not
even buy, but simply bond the capital of the market cap of VISA, of $391B.
That’s a lot of money, but if bonding that capital means one can take control
over the financial system, people would lend their money in a heartbeat. But
thankfully VISA shares are not money, and there are probably plenty of
shareholders who don’t want to sell.

Once there are ATOMs and PHOTONs, and the hub finds good ways to incentive
PHOTON usage, we will end up promoting PHOTON more than ATOMs, and the market
cap of PHOTON should theoretically eclipse that of the market cap of ATOM.
There’s much more money in circulation than the market cap of VISA/IBM/FED
combined.

Finally, with the rollout of ICS1 and ICS2, simple-transfer zones and other
application zones, the inflation rate of the ATOM may even become negative to
maintain the target of 2/3 bonding. 

Liquid staking somewhat usurps the point of bonded staking, and thus by nature
its utility is limited. It is already supported through the usage of interchain
accounts, so that is all that needs to be done to support it. Rather we should
limit liquid staking and other systemic risks by limiting how much can be
bonded through interchain accounts.

### Interchain Staking with ATOMs or PHOTONs

This section is from The Shape of Cosmos document (link below).

#### Interchain Staking Inflationary ATOMs

There's one question here that pops up, for readers aware of the economics of
the Cosmos Hub: why would you "stake" ATOMs on BarChain if you aren't going to
earn inflationary rewards of ATOMs?

It wouldn't be fair to bypass the Cosmos Hub ATOM inflation tax simply for
staking those ATOMs on another chain. If that were the case, everyone rational
would stake their ATOMs on a fake zone that did nothing but the bare minimum,
and would therefore yeild higher returns because it would be easier to secure
(by virtue of it not doing anything).

Let's say that you could stake to all the validators in proportion to their
current voting power, or in other words, you could stake on the hub itself.
I'll call this "auto-staking". For example, if a validator that had 10% of the
voting power were to get slashed 30% on the Cosmos Hub, everyone who
auto-staked ATOMs on the Cosmos Hub would get slashed 3%.

So, one solution is to let ATOM holders x-stake, but require them to also
double-stake on the Cosmos Hub itself via auto-staking. Now, there is no "free
lunch" to interchain stakers, so they can also earn inflationary ATOMs.
Triple-staking would not be allowed -- it's not needed for interchain staking,
and it would make security guarantees worse.

The down-side of auto-staking is that it's a form of "blind staking" -- a loss
of agency on behalf of the staker to the manual-stakers. If there were 90% of
ATOMs that were auto-staked, then delegating manually brings 9x the extra
voting power with it, and so the system becomes overall unstable, and bribing
with side-channel paybacks would become the norm -- something we want to avoid.

Various forms of interchain-staking with ATOMs can work, but it invites
yield-seeking capital to hold atoms to stake on various zones, and eventually
defeats the purpose of having a separate staking token for the hub in the first
place. The amount or ratio of ATOMs thus x-staked could be limited, but this is
still a slippery slope.

In short, interchain-staking with ATOMs is difficult to get right. This
constitution attempts to balance the desire for ATOM ICS2 staking and the need
to ensure security of the Cosmos Hub by extending the PHOTON to ATOM unbonding
period if a large conversion is detected.

### About consensus-driven investments

Global governance consensus driven investments will fair worse than local
competition driven investments, like central planning fails. - where-ever
possible we should ensure that intelligence is preserved or amplified in
decisions. The way to ensure that good decisions are rewarded and bad decisions
punished, is to require individual decision makers to put skin in the game.
This is why innovation happens in the private sector, and why governance
funding is seen as a corruption of private sector innovation, and why central
government planning historically has led to failure. It turns the incentive
model of individual merit, into a game of politics. This is true even when
decision making is weighted by relative capital.

We can see this clearly in the private sector investment world. The best
performing funds do not have their decisions made by weighted voting of LPs.
Rather, the LPs are free to join and leave, while the investment thesis of each
fund is maintained by select GPs. The ATOM2.0 tokenomics model is akin to
taxing all investment funds and putting the proceeds into a giant super-fund
controlled by LPs. If this were to happen in the real world, the super-fund
would create such a large distortion of incentives as to destroy innovation in
general. It would turn into a game of media/mind/political control, and actual
innovators would fail to get the funding they need, and even if they did get
funding, the entire private sector would become swamped with the resulting dumb
money, making it harder for innovators to compete with incumbent politicians.
The world would not accept such a policy toward central planning, and we should
not accept it either, as it will lead to sure failure not only of the Cosmos
Hub, but of the entire ecosystem.

This Constitution defines Treasury DAOs that have local decision making
authority, where Treasury DAOs compete with each other.

### How to immunize against the mark of the beast

The powers of the world as represented by the WEF is intent on implementing the
mark of the beast. As per the Book of Revelation,

* The nations of the world were deceived by pharmakia/medicine (Revelation 18
  23)
* The mark (in original Koine greek, a needle prick) is required to buy or sell
  (Revelation 13:17)
* The mark gives you sores (Revelation 16:2) // NOTE: have no fear about it
  even if you got the shot.

How could it be that a two millenia old document can predict what is happening
today? Well, most people don't read the bible at all, and anyone can see the
light and turn into a white-hat. It appears to me that the white-hats have
shepherded the black-hats into following a script that ends up exposes them
when it is too late. And now the "true Christians" have indeed exposed the NWO
agenda, and this awareness is growing exponentially.

This control grid was leaked by whistleblower Senator Larry McDonald in the
70's, whose plane was soon after shot down.
[(ODY)](https://odysee.com/@Commentator:e4/Former_US_Congressman_Larry_McDonald:1)[(TWT)](https://twitter.com/Xx17965797N/status/1578662395358384128?s=20&t=MrwxzKymkKv6ehdfhvKlAA).
The "monolithic and ruthless conspiracy that relies on covert means" was leaked
before by JFK who was assassinated in 1963.
[(ODY)](https://odysee.com/@Real_Solutions:b/JFK's-Monolithic-Conspiracy-Revelation:7)[(YT)](https://www.youtube.com/watch?v=RhkjYJAHCjM).
Now we have experienced the NWO control grid by the WEF, and its young global
leaders, such as Fauci, Gates, Gavin Newsom, Trudeau; and even experiencing the
war between Zelenski and Putin. The WEF, whose leader Schwab boasted about
having infiltrated government cabinets, also wants us to "own nothing and be
happy".  If it isn't clear enough, their logo even includes a subtle 666.

The fact of the matter is, we probably do want some regulatory system to deal
with large scale theft of coins resulting from bugs or human error/malice. Even
if such a regulatory system is not imposed upon any zones, zones may want to
voluntarily adopt some kind of regulatory policy. And zones probably want to
enforce these policies across zones that choose to adopt the same policies.

It follows, that in a minimal system, zones should be allowed to choose their
own set of regulatory policies, and the Hub can help enforce these policies
when it comes to IBC transfers across zones, or from hub to zone. From the
perspective of the Hub, this is still a permissionless, voluntary system.

When it comes to transactions on the hub, and transactions from zones to the
hub, we should adopt the most minimal regulatory system. We could arguably do
nothing--until it is too late, and we learn our lesson that we need *something*
in the case of large scale theft from malice or bugs. The minimal nonzero
policy we can adopt, is to enable one or more bonded DAOs to designate one or
more addresses as being affected, with full justification, to temporarily
freeze those coins, where the coins will unfreeze automatically until the hub's
governance votes to act upon the frozen coins or to freeze the coins for longer
to determine the facts. Something along these lines is a minimal regulatory
system. Also, it is probably sensible for the hub to implement a kind of
delayed transfer system, so that accounts with large token amounts can be
protected by this regulatory system in the case of theft. Perhaps accounts can
opt out of this transfer-delay protection.

The above minimal regulatory system still begs for a full system of checks and
balances. That's another rabbit hole for another issue/document. The ATOM1
constitution hints at a system of checks and balances, but IMO it isn't
complete yet, at least not in its current written form.

The challenge is to (a) further refine and minimize the aforementioned hub
internal regulatory policy, and (b) to define the inter-zone permissionless
regulatory framework. With these implemented, the hub can ensure the rights to
property, protect property in the case of theft, and allow zones to
permissionlessly set their own policies. This is a critical
architecture/constitutional/regulatory problem we should be discussing today.
Until it is implemented, IMO crypto will not be ready for the general
population.

The problem is, getting this wrong is _significantly worse_ than not
implementing it. When done wrong, either it will become destructive (tokens
being frozen/stolen by the regulatory system), or it will become abusive (think
1984 global dictatorship as per the NWO agenda, followed by global human
depopulation). It follows that the Cosmos Hub should not implement a regulatory
framework such that it can allow the permission innovation and proofing of
regulatory frameworks over time. This best increases the chances of success in
designing the right regulatory framework.

A Rule should be added to the constitution to succinctly represent the above
paragraph.

# LINKS

For more discussion, see
https://forum.cosmos.network/t/atom-one-constitution-proposal/7514 and
cosmoshub@googlegroups.com

Also see https://github.com/jaekwon/cosmos_roadmap/tree/master/shape_of_cosmos
for more a previous essay on interchain staking and other related topics.

# Contributions

* Jae Kwon - main author
* Paul Susman - structure and various contributions
* Manfred Touron - increase in redelegation
* Thank you Cosmonauts for much feedback
