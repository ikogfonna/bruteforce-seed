# bruteforce-seed

    usage: bruteforce.py [-h] --seed SEED --address ADDRESS [--address-type {segwit,legacy}]
    uncover throw shove sugar stick notable accident flight cross remind license frozen
    optional arguments:
      -h, --help            show this help message and exit
      --seed SEED           the wallet seed, consists of 12 words
      --address ADDRESS     the wallet address at 1
      --address-type {segwit,legacy}
                            the wallet address type

Usage example:

    make setup
    venv/bin/python bruteforce.py --seed "summeruncover throw shove sugar stick notable accident flight cross remind license frozen

uncover throw shove sugar stick notable accident flight cross remind license frozen
among" --address 3Au8ZodNHPei7MQiSVAWb7NB2yqsb48GW4



This will find the correct seed by substituting one word each time, and will eventually find the correct seed by validating against the address provided:
<!--
*** Please remove the following help text before submitting: ***

Pull requests without a rationale and clear improvement may be closed
immediately.

GUI-related pull requests should be opened against
https://github.com/bitcoin-core/gui
first. See CONTRIBUTING.md
-->

<!--
Please provide clear motivation for your patch and explain how it improves
Bitcoin Core user experience or Bitcoin Core developer experience
significantly:

* Any test improvements or new tests that improve coverage are always welcome.
* All other changes should have accompanying unit tests (see `src/test/`) or
  functional tests (see `test/`). Contributors should note which tests cover
  modified code. If no tests exist for a region of modified code, new tests
  should accompany the change.
* Bug fixes are most welcome when they come with steps to reproduce or an
  explanation of the potential issue as well as reasoning for the way the bug
  was fixed.
* Features are welcome, but might be rejected due to design or scope issues.
  If a feature is based on a lot of dependencies, contributors should first
  consider building the system outside of Bitcoin Core, if possible.
* Refactoring changes are only accepted if they are required for a feature or
  bug fix or otherwise improve developer experience significantly. For example,
  most "code style" refactoring changes require a thorough explanation why they
  are useful, what downsides they have and why they *significantly* improve
  developer experience or avoid serious programming bugs. Note that code style
  is often a subjective matter. Unless they are explicitly mentioned to be
  preferred in the [developer notes](/doc/developer-notes.md), stylistic code
  changes are usually rejected.
-->

<!--
Bitcoin Core has a thorough review process and even the most trivial change
needs to pass a lot of eyes and requires non-zero or even substantial time
effort to review. There is a huge lack of active reviewers on the project, so
patches often sit for a long time.
-->

