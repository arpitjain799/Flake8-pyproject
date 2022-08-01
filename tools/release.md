﻿Steps to take when releasing a new version:
* Bump version number in `meta.py`.
* Add dedicated commit for the version bump.
* Tag commit with version number, e.g. `git tag 1.0.0`.
* Push to GitHub: `git push && git push --tags`.
* Create GitHub release from tag and add release notes.
* Publish to PyPI: `tools/publish.py`.
