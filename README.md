## Logseq Sepia Theme

This theme is a work in progress to provide a **default Sepia theme** for Logseq based on [pull request 2644](https://github.com/logseq/logseq/pull/2644).

The idea is for others to further develop this theme and get the pull request approved once we are done.

## How To Contribute

**Option 1**
1. Clone/download this repository
2. Load the folder as a plugin
3. Change to light theme
4. Adjust the theme as needed
5. Create a pull request for `mschmidtkorth/sepia-theme`

**Option 2**
1. Download `sepia.css`
2. Remove the following section:
```css
.white-theme,
html[data-theme='light'] {}
```
3. Update section
```css
.sepia-theme,
html[data-theme='sepia']
```
to
```css
.white-theme,
html[data-theme='light'] {}
```
4. Adjust the theme as needed
5. Create a pull request for `mschmidtkorth/sepia-theme`