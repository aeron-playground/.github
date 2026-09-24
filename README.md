# .github

The organization profile and the default community files for
[aeron playground](https://github.com/aeron-playground).

## What's here

| Path | What it does |
| :--- | :--- |
| `profile/README.md` | The page people see at [github.com/aeron-playground](https://github.com/aeron-playground) |
| `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md` | Defaults for every repository in the organization that doesn't have its own |
| `.github/ISSUE_TEMPLATE/`, `.github/pull_request_template.md` | Default issue forms and pull request template |
| `GOVERNANCE.md` | Who decides, and how to become a maintainer |
| `assets/` | Logo, banners and the organization's profile picture |

## How the defaults work

- GitHub uses a file from here only when a repository has no copy of its own in its root,
  `.github/` or `docs/` folder.
- A repository with its own `.github/ISSUE_TEMPLATE/` folder uses none of the default issue forms.
- The issue forms add the labels `bug` and `feature`. A label only gets added in repositories
  where it exists.
- Licenses are never inherited. Every repository needs its own `LICENSE`.

## Assets

| File | Use it for |
| :--- | :--- |
| `banner-light.svg`, `banner-dark.svg` | The profile banner, for light and dark themes |
| `logo-light.svg`, `logo-dark.svg` | The mark on its own, for light and dark backgrounds |
| `avatar.png`, `avatar.svg` | The organization's profile picture |

The text in the banners is converted to outlines (IBM Plex Sans), so it looks the same on every
device. Colors follow GitHub's own light and dark themes.

## License

The text in this repository is licensed under [CC BY 4.0](LICENSE). The Code of Conduct is adapted
from the [Contributor Covenant 3.0](https://www.contributor-covenant.org/version/3/0/) and licensed
under CC BY-SA 4.0. The logo, banners and profile picture in `assets/` are not covered by these
licenses.
