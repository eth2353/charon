# Contributing to Obol Charon

🎉 Thanks for taking the time to contribute, we really appreciate it.

To get started with DV tech, check out the
[Obol book](https://docs.obol.tech/docs/intro) and [Go docs](https://pkg.go.dev/github.com/obolnetwork/charon).

We keep a simple set of guidelines to streamline the contribution process,
loosely based on the [Atom contributing guide](https://github.com/atom/atom/blob/master/CONTRIBUTING.md).

## Responsible Disclosure

⚠️ We take the security of our users very seriously.
If you believe you have found a security issue, please **responsibly disclose** it to `security@obol.tech`
instead of opening a public issue or PR on GitHub.

## Coordinating work flows

- If you have found a bug...
  - Check for existing bug reports of the same issue in GitHub.
  - Do not post about it publicly if it is a suspected vulnerability to protect Obol's users; 
    instead use `security@obol.tech`.
  - Maybe send a message in relevant community channels if you are unsure whether you are seeing a technical issue.
  - Open a GitHub issue if everything else checks out 🤓
- Are you thinking of a small change that just makes sense? Feel free to submit a PR.
- If you're envisioning a larger feature or are just looking for a discussion,
  let's chat in the [Obol Discord](https://discord.gg/n6ebKsX46w/) under `#dev-community`.
  - A quick sync before coding avoids conflicting work and makes large PRs much more likely to be accepted.
  - 👀 The Discord channel is currently _invite-only_ to prevent spam. Please ping a team member to get access.

## Submitting changes

### Community Contributions (Pull Requests)

Feel free to fork the Charon repo and submit a pull request with your suggested changes.

Please include a PR description mentioning everything important (according to your best judgement).

### Core Dev Contributions

- Publish your work in a branch under the main repo (ObolNetwork/charon).
- Try to keep track of work in Jira issues.
- Suggested branch names: `<name>/<feature>`, e.g. `oisin/OB1-1234` or `richard/fix-discv5-panic`.
- Delete your merged branches.
- Configure Git to use your `obol.tech` email.

## Style Guide

### Git commit messages

- Use a concise summary line.
- Prefix the summary with a Jira ticket ID like `[OB1-1234]` if applicable.
- Feel free to use `Co-Authored-By` and `Signed-Off-By` lines.

### Go code

- Make sure your tests pass.
- Make sure new code paths/modules are also covered by tests.

## Anything missing?

This is a living document. Feel free to improve the contribution guide.