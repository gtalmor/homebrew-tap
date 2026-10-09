# gtalmor/tap

Homebrew tap for [Assume Keycloaker](https://github.com/gtalmor/assume-keycloaker), a macOS menu bar app
that keeps Keycloak (saml2aws) and AWS SSO sessions alive.

```bash
brew install --cask gtalmor/tap/assume-keycloaker
```

Updates: the app updates itself through Homebrew, or run `brew upgrade --cask assume-keycloaker`.
It was called `assume-cloaker` before 0.2; `brew update` moves existing installs to the new name.

`teams/` holds encrypted team configurations; they can only be opened with an invite from the team.
