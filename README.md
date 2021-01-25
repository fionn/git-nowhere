Git Nowhere
===========

Commit like you're in Burkina Faso, Gambia, Ghana, Greenland, Guinea, Guinea-Bissau, Iceland, Ireland, Ivory Coast, Liberia, Mali, Mauritania, Morocco, São Tomé and Príncipe, Senegal, Sierra Leone, Togo, the United Kingdom or part of Antarctica.

Git leaks timezone information via `AuthorDate` and `CommitDate`, which could reveal your location.

Link `post-commit` to `$GIT_DIR/.git/hooks/`. This will change the timezone attached to the commit, putting you in UTC±0000.

Inspired by [gitdate](https://github.com/isislovecruft/scripts/blob/master/gitdate).
