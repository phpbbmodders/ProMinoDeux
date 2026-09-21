# ProMinoDeux

A CSS-only child style for phpBB 3.3 that re-skins prosilver with a flat, light design: a dark rounded header bar, dark gray category bands, white rows with thin dividers, blue links with a crimson hover, flat uppercase buttons, and card-style posts.

It keeps prosilver's templates, JavaScript and images, and only overrides colours and shapes in `theme/stylesheet.css` (plus a recoloured icon in `theme/en/`), so it follows prosilver through phpBB 3.3 updates.

## Install

1. Copy this folder to `phpBB/styles/prominodeux/`.
2. In the ACP, go to Customise > Styles, install **ProMinoDeux**, and set it as the default style.

## Notes

- Requires phpBB 3.3 with the prosilver style installed. It has not been tested on phpBB 4.0.
- Fonts: `"Droid Sans"`, `"Helvetica Neue"`, Helvetica, Arial, in that order; no font files are bundled.

## Acknowledgments

- Design language and colour palette based on [ProMino](https://github.com/hanakin/ProMino), a GPL-2.0 phpBB style project by [Mike Miday](http://www.midaym.com/), and its design guide (`assets/design/StyleGuide.jpg`). No ProMino code is copied.
- The "online" ribbon icon is prosilver's `icon_user_online` (phpBB Limited, GPL-2.0), recoloured.
- Design and code assisted by [Claude](https://www.anthropic.com/claude).

## License

This project is licensed under the **GNU General Public License v2.0**.

See [license.txt](license.txt) for more information.
