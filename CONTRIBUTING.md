# Contributing to Talos

Thanks for helping! Bug reports, example parts and ideas are the most useful contributions.

## Report a bug
Open an [issue](../../issues/new/choose) with:
- your Blender version and operating system,
- the screw settings (type, size, joint) and what you expected,
- a screenshot of the part, and if possible a small .blend file that shows the problem,
- any error from the Info editor or the system console.

## Suggest a feature
Open an issue and describe the fastener or the joint you need, with its standard (ISO, DIN, ASME…) when there is one.

## Pull requests
- Open an issue before a large change, so we can agree on the approach.
- Keep the add-on compatible with Blender 4.3 to 5.3 (Python 3.11: no nested identical quotes in f-strings).
- extensions.blender.org rules apply: no `sys.path` / `sys.modules` changes, no `threading` or `queue`, no network access.
- New interface texts need French, German and Spanish translations (`talos_fasteners/i18n.py`, `i18n_more.py`).
