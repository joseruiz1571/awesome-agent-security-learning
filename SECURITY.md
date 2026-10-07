# Security policy

## Report a vulnerability privately

Use [GitHub's private vulnerability reporting form](https://github.com/joseruiz1571/awesome-agent-security-learning/security/advisories/new) for vulnerabilities affecting this repository, its workflows, or its website. Include the affected commit or URL, impact, and minimal reproduction steps using synthetic data.

Do not post credentials, private information, or an unpatched exploit in a public issue or pull request. Never test against other people's systems without authorization. If you encounter an exposed credential, report its location without copying the credential into the report; its owner should revoke it.

This is a volunteer-maintained project. No response-time guarantee or bug bounty is offered. Only the current default branch is maintained.

## Linked resources

Listing a resource is not a security audit, endorsement, or permission to test it. Report vulnerabilities in linked projects through their own disclosure channels. Incorrect links, misleading descriptions, or unsuitable resources can be reported in an ordinary issue, provided the report contains no sensitive information.

## Trust boundaries

- Contributor changes are reviewed through pull requests. Required checks validate the catalog and generated README; CodeQL analyzes Python, JavaScript and GitHub Actions.
- Publishing uses read-only repository access. Only the deployment job receives Pages and identity-token permissions. It does not push to the default branch.
- Discovery proposes changes for human review. It never merges or approves them, executes linked tools, or supplies retrieved content to an autonomous coding agent.
- Treat issue text, PR descriptions, catalog entries and linked content as untrusted data when using an AI assistant to help maintain this repository.

Security checks reduce risk; they do not prove that a resource or contribution is safe.
