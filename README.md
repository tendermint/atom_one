# ATOM ONE CONSTITUTION 

_NOTE: THIS IS A DRAFT; MAKE A PR BEFORE IT BECOMES FINAL!_

_This document is a work in progress. This document assumes familiarity with
the current workings of cosmoshub4 as of Oct 11th 2022. What is described here
are modifications to what already is. This clause will be removed with future
revisions, and the corresponding parts of the document updated with a full
description of the constitution of the hub._

## Preamble

We the people of the Cosmos, in order to create a free world, enable voluntary
and borderless transactions, facilitate permissionless innovation, ensure
economic security, cater for economic and technological development, allow for
the creation of sovereign zones, and maintain order among sovereign zones, do
ordain and establish this Constitution for the Cosmos Hub.

## Part 1 General Provisions

### Rule 1. Fundamental principles

The Constitution of the Cosmos, hereinafter “the Constitution” hereby
establishes the foundations of the governance, economical model and operating
ecosystem of the Cosmos Hub.

Any other subsequent rules or governance proposals have to be in alignment with
the provisions of this Constitution and the Proponents are required to ensure
consistency between such proposals and this Constitution.

### Rule 2. Sovereignty of Cosmos

Cosmos is composed by a main sovereign hub that allows for the development of
other inter-connected hubs that can form or create other sovereign zones.

The working language of Cosmos is English.

### Rule 3. General Mission and Objectives

The mission of the Cosmos Hub is to create a new world allowing for
permissionless yet secure interactions between the Cosmonauts of Cosmos in the
Sol system.

The objective of the Cosmos Hub is to provide a classical BFT proof-of-stake
multi-token payment and transfer system; and to scale the security of the
platform to many applications hosted in other chains (zones) via ICS.

### Rule 4. Cosmonauts

Every person has the right to become a Cosmonaut and can freely engage on the
Cosmos. As such, every Cosmonaut has the right to own at least one address on
the Cosmos Hub.

Any Cosmonaut can also become a citizen of the Cosmos Hub by using their
address to stake ATOMs and participate actively in governance. The status of
citizenship is granted in an autonomous manner.

### Rule 5. Rights, Liberties, and Obligations in the Cosmos Hub

The Liberty and Property of all Cosmonauts engaging in the Cosmos Hub is hereby
guaranteed. Any restriction to the Liberty and Property of citizens on the
Cosmos Hub can be done only through the hub's governance.

Every Cosmonaut has the right to receive benefits from their engagement in the
Cosmos Hub, including rights derived from held or staked ATOMS in line with the
provisions of this Constitution.

Every citizen allows the Governance of the Cosmos Hub to restrict their staked
ATOM property by partial or full slashing according to their voting activity.

## Part 2 Governance

### Rule 6. The COSMOS HUB Chain

The main hub is uniquely identified by chainid "cosmoshub".  This chain will
serve the following functions:

 * governance proposals
 * ATOM staking
 * flat PHOTON inflation
 * intra-hub token transfers
 * IBC token transfers
 * ICS service

### Rule 7. Decision-making

The provisions of this Constitution are to be implemented further though
governance Proposals.

TODO: describe the governance process.

The governance process will extend the voting deadline to ensure at least 2
weeks of voting after the quorum has been met.

### Rule 8. Air-drops and forks

Every Cosmonault allows any Cosmonaut to create full or partial airdrops of new
tokens to any chain using the distribution of any token on the Cosmos Hub.

Every citizen allows any Cosmonaut to modify their pro-rata of their airdrop
portion by partial or full slashing based on their cryptographic voting
activity according to well defined principles.

### Rule 9. The Interchain Security (ICS) System

The first zones secured by ICS will be simple-transfer zones. These are
blockchain applications that provide the following functions:

 * intra-zone token transfers
 * IBC token transfers back to the hub
 * atomic cross-chain transactions across other simple-transfer zones

The ICS system must ensure a reasonable Nakamoto coefficient for each zone.

The ICS system must enable geographically regional validator sets, at least in
the following regions;

 * Western US
 * Eastern US
 * Central America
 * South America
 * Europe
 * Asia
 * Africa

### Rule 10. Treasury DAOs

The Cosmos Hub governance may establish one or more transparent and accountable
Treasury DAOs by simple majority vote.

The operations of the Treasury DAO must operate on an ICS secured zone outside
of the hub. As an exception, the tokens of the Treasury DAO may reside on the
the Cosmos Hub as a m-of-n multisig account where n is at least 3 and m is at
least 1/2 of n, where each signatory is an authorized member of the Treasury
DAO and citizen of the Cosmos Hub.

The Treasury DAO will be composed of Cosmonauts, and at the top Executive Board
level be composed of one or more citizens. All Cosmonauts and citizens of
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
to Cosmos Hub governance by citizens.

Each Treasury DAO shall have an Oversight Committee composed of any number of
Cosmonauts. The Oversight Committee must have at least the right to freeze all
transfers of tokens from the Treasury or its designated m-of-n multisig account
on the Cosmos Hub.

## Part 3 Economics

### Rule 11. Economic model

The one and only economic incentive model is the collection of market-based
transaction fees from a large number of transactions across all the blockchains
secured by the bonding of ATOM tokens, first and foremost from simple intra and
inter-zone token transfers.

### Rule 12. The ATOM Token

The ATOM token functions as voting shares, economic incentive shares, and
security bond for the Cosmos Hub.

To preserve the security and identity of the acting governance and validator
set, the inflation rate of the ATOM token is made to vary to target 2/3 of all
ATOMs. The maximum inflation rate is 20% non-compounded per year. There is no
minimum inflation rate, and it can even be negative (deflationary).

Inflated ATOM tokens are paid to bonded ATOM holders in proportion to each
delegator's staking amount.

Staked ATOMs are converted to bonded share units.

The unbonding period is 3 weeks.

Redelegation is allowed twice per unbonding period for any delegation.

Double signing at any height/round/step results in slashing penalty that is
proportional to the total amount of double signing by all validators for that
height/round/step, with evidence collected during the unbonding period; the
penalty will range from +0% to 100%, the latter when 2/3 of voting power
double-signs.

Complex signing failures (those that require +1/3 to coordinate) will result in
complete slashing.

Any inflation of ATOM tokens to the Community Pool or designated Treasury DAO
beyond the default inflation rate described here requires a supermajority vote
of a special inflation governance proposal type.

Liquid staking may only be supported through interchain accounts.

### Rule 13. The PHOTON Token

The PHOTON distribution will be created by burning ATOM tokens in a one-time
event that will last no longer than 3 months. After completion, 20% of the
issued PHOTONs will additionally be inflated and added to the community pool.

Thereafter the PHOTON token will be inflated at a constant fixed rate equal to
2% of the initial distribution, forever, and paid to the bonded ATOM holders.
This inflation rate may be decreased but never increased, except for any
issuance approved by the special governance procedure.

The PHOTON and ATOM tokens will be whitelisted as transaction fee payments for
the hub and all simple-transfer zones.

Any inflation of PHOTON tokens to the Community Pool or designated Treasury DAO
beyond the default inflation rate described here requires a supermajority vote
of a special inflation governance proposal type.

### Rule 14. Inflation

The inflation of additional ATOMs or PHOTONs to the Community Pool or
designated Treasury DAO require a special inflation proposal type, and will
require a two thirds supermajority instead of the default 50%. 

The special inflation proposal can include a description of the purpose of the
inflation, but cannot include any other modifications to the Cosmos Hub or its
Constitution.

### Rule 15. The Tax System

Tax proceeds are sent to the Community Pool.

The tax rate is initially 2%, but can be increased up to 50% by governance
vote.

## Part 4 Final Dispositions

## Rule 17. Updates to the Cosmos Hub

New updates to the hub should be broken down into independent components and
discussed/proposed separately with adequate time between, regardless of any
omnibus whitepaper. 

## Rule 18. The Implementation

The hub should not have any VM functionality, but be plainly implemented in a
single garbage collected language as reference (namely Go; and other clients
can implement it all in another language like Rust).

The only cryptographic assumptions used by the Cosmos Hub including its
consensus shall be Ed25519 and Secp256k1 elliptic curves, and RIPEMD160 and
SHA256 hash functions.

No zero-knowledge proof systems may be adopted on the Cosmos Hub even if they
are composed of the approved primitives.

## Rule 19. Compute/storage/memory limitations

For the sake of decentralization, accessibility, accountability, and security,
the hub and each ICS zone will be restricted such that each can run on a
commodity machine. 

## Rule 20. Amendment of the Constitution

This constitution may be modified or additional parts and rules appended by two
thirds supermajority of Cosmos Hub governance.

<hr />

# COMMENTARY

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

Also, the tax system may be used to allocation a portion of ATOM and PHOTON
inflation to fund the common pool.

### About Security, and the need for ATOM/PHOTON separation

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

I do see the “monification” of ATOM as per ATOM2.0 to be fundamentally flawed,
for a chain whose main selling point is SECURITY. I believe ETH2.0 with its ETH
staking is similarly flawed. I fear that we won’t realize it until it is too
late. We can prevent future disasters.

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

The ATOM -> PHOTON burn event is designed to make ATOM even more deflationary.

Finally, with the rollout of ICS, simple-transfer zones and other application
zones, and PHOTON inflation, the inflation rate of the ATOM token may even
become negative to maintain the target of 2/3 bonding. 

Liquid staking somewhat usurps the point of bonded staking, and thus by nature
its utility is limited. It is already supported through the usage of interchain
accounts, so that is all that needs to be done.

### About consensus-driven investments

Governance driven funding will fail, like central planning fails. - where-ever
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

### About the mark of the beast

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
[(YT)](https://www.youtube.com/watch?v=_BPhYEFGaGM). The "monolithic and
ruthless conspiracy that relies on covert means" was leaked before by JFK who
was assassinated in 1963. [(YT)](https://www.youtube.com/watch?v=RhkjYJAHCjM).
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

# Contributions

* Jae Kwon
* Paul Susman
* Manfred Touron
