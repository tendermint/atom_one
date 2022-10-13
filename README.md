# ATOM ONE CONSTITUTION 

_This document is a work in progress. This document assumes familiarity with the
current workings of cosmoshub4 as of Oct 11th 2022. What is described here are
modifications to what already is. This clause will be removed with future
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

### Rule 3. General Objective and Mission

The objective of the Cosmos Hub is the creation of a new and unique world
allowing for interactions between cosmonauts of Cosmos where people can act
freely and develop. The mission of the Cosmos Hub is to provide a classical BFT
proof-of-stake multi-token payment and transfer system; and to provide the
security of the platform to applications hosted in other chains (zones); for as
many people as possible in the Sol system.

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

The ICS system must enable geographically regional validator sets, at least 
in the following regions;

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

Redelegation is allowed once per unbonding period for any delegation.

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

The ATOM distribution will be 1:1 airdropped into the PHOTON distribution.  The
PHOTON distribution will also be airdropped to IBC chains with no need to transfer
any ATOMs back to the hub.

Thereafter the PHOTON token will be inflated at a constant fixed rate equal to
5% of the initial distribution, forever, and paid to the bonded ATOM holders.
This inflation rate may be decreased but never increased, except for any
issuance approved by the special governance procedure.

The PHOTON and ATOM tokens will be whitelisted as transaction fee payments for
the hub and all simple-transfer zones.

Any inflation of PHOTON tokens to the Community Pool or designated Treasury DAO
beyond the default inflation rate described here requires a supermajority vote
of a special inflation governance proposal type.

### Rule 14. Inflation

The inflation of additional ATOMs or PHOTONs to the Community Pool or
designated Treasury DAO require a special inflation proposal type, and the
threshold shall be 67% instead of the default 50%. The special inflation
proposal can include a description of the purpose of the inflation, but cannot
include any other modifications to the Cosmos Hub or its Constitution.

### Rule 15. The Tax System

Tax proceeds are sent to the Community Pool.

The tax rate is initially 2%, but can be increased up to 50% by governance vote.

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

## Rule 19. Amendment of the Constitution

This constitution may be modified or additional parts and rules appended by two
thirds supermajority of Cosmos Hub governance.

# NOTES

For discussion, see
https://forum.cosmos.network/t/atom-one-constitution-proposal/7514 and
cosmoshub@googlegroups.com
