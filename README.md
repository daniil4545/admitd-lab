# admitd-lab

admitd gate experiment: enforcement on GitHub Free.

This repository is a lab for testing pull-request gate enforcement with the
admitd tool. It intentionally stays minimal: small test changes are submitted
as pull requests against `main` so the gate behaviour can be observed.

## Contents

- `pr1.txt`, `pr2.txt` - placeholder files used as payloads for the test pull
  requests (`pr1: test change`, `pr2: test change`).
- `README.md` - this file.

## Usage

Open a pull request with a small change and watch how the admitd gate treats
it. This repository has no build, test or lint commands; there is nothing to
run locally beyond Git itself.
