# Basic Trilium Themes

Stylesheets building on Trilium defaults

Licensed under GNU AGPL, since that's the Trilium license and I spent a good long amount of time directly working from the application's original CSS sources.

Requires Trilium to make any sense.

Basic user flow:

- copy the CSS file contents from `build/` into Trilium CSS notes
- Set Menu → Options → Appearance → Theme to your new CSS note

Basic development flow:

```bash
npm install -D
```

- build it
- Copy the CSS file contents into a Trilium CSS note
- Set note property to something appropriate `#appTheme="Basic Dark"`
- Set Menu → Options → Appearance → Theme to your CSS note

On further iterations, `C-r` to refresh the theme.

```bash
npm run build
```

## Quality control

```bash
npm run lint
```

`.stylelintc.json` has been configured for SCSS, with a few rule adjustments to account for `.CodeMirror` and similar externally defined classes.

## License

Trilium Basic Themes — stylesheets for the Trilium note application
Copyright (C) 2023 Brian Wisti <brianwisti@pobox.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
