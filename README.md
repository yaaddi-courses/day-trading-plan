# Day Trading Plan

A complete-beginner path to building and following a real day trading plan — market mechanics, reading charts, risk and money management, and the psychology and discipline that make a plan actually stick.

Part of the [Yaaddi](https://github.com/yaaddi-courses) course catalog — a
spaced-repetition flashcard course, ready to build and validate with the
standard Yaaddi course tooling.

## Structure

- `meta.json` — course metadata (title, description, cover image, version)
- `source/` — authoring source (`meta.csv`, `units.csv`, `cards.csv`, `glossary.csv`, images/)
- the built `.zip` — generated from `source/` via `build_course_zip.py`

## Editing this course

1. Edit `source/units.csv` / `source/cards.csv` / `source/glossary.csv` directly.
2. Run `python validate_course.py . --source` and fix anything it flags.
3. Run `python build_course_zip.py .` to regenerate the shipped `.zip`.
4. Commit both the `source/` changes and the rebuilt `.zip`.
