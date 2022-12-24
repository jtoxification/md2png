<h1>md2png</h1>
<p>
  Converts Discord Markdown to PNG format (1st draft temporarily hardcoded to specific Progress Tracker emoji)
</p>
<p>
 This tool was made possible by the Mozilla API reference, w3schools, StackOverflow, ShinyHobo's ShinyTracker, Cloud Imperium Games,
 and all the crazy geniuses who standardized, designed, and implemented the wonderful browser features that I gleefully and ignorantly knock together.
</p>
<h2>License</h2>
<pre>
Copyright (C) 2022 jtoxification aka Just Some Rando for the r/StarCitizen news team and the Star Citizen Community.
Not affiliated with Cloud Imperium Games
Use and modify as needed - there really isn't anything special here; it just gets the job done.
I can be reached via Discord.

https://www.gnu.org/licenses/gpl-3.0-standalone.html

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.</pre>
<h2>Changelog</h2>

1. 2022-10-27 - Initial Creation
 
2. 2022-10-30 - Addition and base64 conversion of Progress Tracker-specific emoji

3. 2022-11-09 - Added inline edits & drag & drop

4. 2022-11-23 - Rewrite w/ automatic multicolumn capabilities, credit blurb, legend

5. 2022-11-25 - Reduced column count to fit when a small number of items are present

6. 2022-12-12 - General bugfixes and license

7. 2022-12-23 - Add'l credit blurb, git branch creation

<h2>To Do</h2>

1. Underline support

2. Column count selection

3. Emoji profile create/update/load/save, with automatic conversion of binary to bin64 stream

4. Transparency handling, borders, and background

5. SVG support (with hyperlink support)

6. (??). Proper project structure. Something, something, lint.

7. Convert to TypeScript

8. Make UI-less variant runnable from command-line
