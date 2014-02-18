LiteBar (LTB) - a fork of Litecoin (LTC) and the silver equivalence of BitBar with fast block time and fast confirmations (only 4 confirmations needed). 

	- 3 minutes block target
	- 4 transactions to confirm
	- Transaction fee = 0.001
	- Uses scrypt as Proof of Work (PoW) Scheme
	- Difficulty retargets once per block (Using Kimoto Gravity Well)
	- Total litebars rewarded = 1350000 (1.35M) only. This is a rare bar!
	- Linear designed litebar production (reward will halve once only to a minimum reward of 1 litebar)
	- Litebar generation process will last for 5 years only after which it will lay in a state of perpetuity (2014-2019)
	- First 7200 starting blocks (15 days) will have 5 litebars per block Hereafter it will drop to 2 litebars per block and /2 once after 2.5 years (or 438000 blocks)
	- The default ports are 9065 (connect) and 9055 (json rpc).


Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 
