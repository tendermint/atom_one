# ATOM ONE CONSTITUTION 

## The Preamble

We the people of the Cosmos, in order to create a free world, enable voluntary
transactions, facilitate permissionless innovation, ensure economic security,
and maintain order among sovereign zones, do ordain and establish this
Constitution for the Cosmos Hub.

This document is a work in progress. This document assumes familiarity with the
current workings of cosmoshub4 as of Oct 11th 2022. What is described here are
modifications to what already is. This clause will be removed with future
revisions, and the corresponding parts of the document updated with a full
description of the constitution of the hub.

## The Mission

The mission of the Cosmos Hub is to provide a classical BFT proof-of-stake
multi-token payment and transfer system; and to provide the security of the
platform to applications hosted in other chains (zones); for as many people as
possible in the Sol system.

## The Economic Model

The one and only economic incentive model is the collection of market-based
transaction fees from a large number of transactions across all the blockchains
secured by the bonding of ATOM tokens, first and foremost from simple intra and
inter-zone token transfers.

## The COSMOS HUB Chain

The main hub is uniquely identified by chainid "cosmoshub". 
This chain will serve the following functions:

 * ATOM staking
 * flat PHOTON inflation
 * intra-hub token transfers
 * IBC token transfers
 * ICS service
 * governance proposals

## The ATOM Token

The ATOM token functions as voting shares, economic incentive shares, and
security bond for the Cosmos Hub.

To preserve the security and identity of the acting governance and validator
set, the inflation rate of the ATOM token is made to vary to target 2/3 of all
ATOMs. The maximum inflation rate is 20% non-compounded per year. There is no
minimum inflation rate, and it can even be negative.

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

## The PHOTON Token

The ATOM distribution will be 1:1 airdropped into the PHOTON distribution.  The
PHOTON distribution will also be airdropped to IBC chains with no need to transfer
any ATOMs back to the hub.

Thereafter the PHOTON token will be inflated at a constant fixed rate equal to
5% of the initial distribution, forever, and paid to the bonded ATOM holders.
This inflation rate may be decreased but never increased, except for any
issuance approved by the special governance procedure.

The PHOTON and ATOM tokens will be whitelisted as transaction fee payments for
the hub and all simple-transfer zones.

## The ICS System

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
 * Afrika

## The Governance Process

Air-drops or forks of the ATOM token to new chains is freely allowed. The
air-drop may be modified based on consensus voting and governance voting
activity according to the philosophy of the new chain.

## The Cryptographic Assumptions

The only cryptographic assumptions used by the Cosmos Hub including its
consensus shall be Ed25519 and Secp256k1 elliptic curves, and RIPEMD160 and
SHA256 hash functions.
