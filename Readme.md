Blockchain From Scratch
=======================

Learn the fundamentals of blockchain by building it from scratch. In Rust.

Solutions are available on the `solutions` branch.

Contents
--------

Currently in place:
* State Machines
* The hash-linked blockchain data structure
* Blocks track state
* PoW Consensus
* Batching extrinsics in blocks

Upcoming:
* Managing rich state (and genesis state)
* Abstract interface so blockchain can run any state machine
* full client and transaction pool

Hopefully Somewhere:
* Fork choice rule - could be a one-function exercise in one of the lessons
* Proof of authority
* Abstract Consensus interface
* Free execution (on_initialize, on_finalize)
* "Invalid" transactions - transactions that don't cause a transition from this state even though they would from another state.
* light client. tracks headers doesn't store state. We don't need real merkle proofs, jsut send the full state.
* Merklized storage

Context
-------

This content was written to accompany the Module 3: Blockchain in the Polkadot Blockchain Academy.

It strives to be useful stand-alone content as well.