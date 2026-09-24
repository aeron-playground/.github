# Contributing

Thanks for helping. This guide applies to every repository in
[aeron playground](https://github.com/aeron-playground). Most repositories also have their own
`CONTRIBUTING.md` with setup steps and project rules. When one does, follow it: it comes first.

By taking part, you agree to follow our
[Code of Conduct](https://github.com/aeron-playground/.github/blob/main/CODE_OF_CONDUCT.md).
Found a security problem? Don't open an issue. Follow the
[security policy](https://github.com/aeron-playground/.github/blob/main/SECURITY.md) instead.
Need help? See [Support](https://github.com/aeron-playground/.github/blob/main/SUPPORT.md).

## Before you start

- For anything bigger than a small fix, open an issue first so we can agree on the approach.
- Keep one change per pull request. Small pull requests (under about 400 changed lines) get
  reviewed faster.
- Issues labeled `good first issue` are a good place to start.

## Branches

Never commit to `main`. Create a branch named `<type>/<scope>-<short-name>`, for example
`feat/api-login` or `fix/docs-setup-link`.

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org): `type(scope): summary`.
The summary is lowercase and imperative, and the whole line is at most 72 characters.

```text
feat(api): add a login endpoint
fix(docs): fix the broken setup link
```

| Type | Use it for |
| :--- | :--- |
| `feat` | A new feature |
| `fix` | A bug fix |
| `perf` | A speed-up that keeps the behavior the same |
| `refactor` | A code change that keeps the behavior the same |
| `test` | Tests only |
| `docs` | Docs only |
| `build` | The build system or dependency setup |
| `ci` | CI configuration |
| `chore` | Maintenance |
| `revert` | Undoing an earlier commit |

Mark a breaking change with `!` after the scope (`feat(api)!: remove the old login`), or with a
`BREAKING CHANGE:` footer. Each repository lists its scopes in its own contributing guide.

We squash-merge pull requests, so the pull request title becomes the commit on `main`.
The title follows the same format.

## Sign off your commits (DCO)

Every commit needs a `Signed-off-by` line with your name and the same email as the commit author:

```text
Signed-off-by: Ada Lovelace <ada@example.com>
```

It means you agree to the [Developer Certificate of Origin](https://developercertificate.org):
you wrote the change, or you have the right to submit it under the repository's license.
Git adds the line for you:

```bash
git commit -s -m "fix(docs): fix the broken setup link"
```

Forgot? Add a sign-off to every commit on your branch, then update the pull request:

```bash
git rebase --signoff origin/main
git push --force-with-lease
```

## Pull requests

1. Run the repository's checks on your machine and fix everything. Don't skip or silence tests
   or lint rules.
2. Fill in the pull request template and link the issue (`Closes #12`).
3. UI changes need screenshots: light and dark theme, phone and desktop.
4. Update the docs when you change something users or developers see.
5. Open the pull request as a draft while you work. Mark it ready for review when the checks pass.

A pull request can merge when every required check passes and every review thread is resolved.

## Reviews

- We try to reply to new issues and pull requests within a few days.
- Reviews are about the code, never the person. Be kind and be specific.
- If you disagree with a review, say why. We'd rather talk it through than guess.

## License

By contributing, you agree that your contributions are licensed under the license of the
repository you contribute to.
