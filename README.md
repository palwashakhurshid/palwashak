
# A first-level heading
## A second-level heading
### A third-level heading
Style	Syntax	Keyboard shortcut	Example	Output
Bold	** ** or __ __	Command+B (Mac) or Ctrl+B (Windows/Linux)	**This is bold text**	This is bold text
Italic	* * or _ _     	Command+I (Mac) or Ctrl+I (Windows/Linux)	*This text is italicized*	This text is italicized
Strikethrough	~~ ~~	None	~~This was mistaken text~~	This was mistaken text
Bold and nested italic	** ** and _ _	None	**This text is _extremely_ important**	This text is extremely important
All bold and italic	*** ***	None	***All this text is important***	All this text is important
Subscript	<sub> </sub>	None	<sub>This is a subscript text</sub>	This is a subscript text
Superscript	<sup> </sup>	None	<sup>This is a superscript text</sup>>
Text that is a quoteUse `git status` to list all new or modified files that haven't yet been committed.Some basic Git commands are:
```
git status
git add
git commit
```
Screenshot of rendered GitHub Markdown showing a code block. The words "git status," "git add," and "git commit" appear in a fixed-width typeface, highlighted in light gray.
The background color is `#ffffff` for light mode and `#000000` for dark mode.
Screenshot of rendered GitHub Markdown showing how HEX values within backticks create small circles of color. #ffffff shows a white circle, and #000000 shows a black circle.

Here are the currently supported color models.

Color	Syntax	Example	Output
HEX	`#RRGGBB`	`#0969DA`	Screenshot of rendered GitHub Markdown showing how HEX value #0969DA appears with a blue circle.
RGB	`rgb(R,G,B)`	`rgb(9, 105, 218)`	Screenshot of rendered GitHub Markdown showing how RGB value 9, 105, 218 appears with a blue circle.
HSL	`hsl(H,S,L)`	`hsl(212, 92%, 45%)`	Screenshot of rendered GitHub Markdown showing how HSL value 212, 92%, 45% appears with a blue circle.
Notes:

A supported color model cannot have any leading or trailing spaces within the backticks.
The visualization of the color is only supported in issues, pull requests, and discussions.
Links
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut Command+K to create a link. When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

You can also create a Markdown hyperlink by highlighting the text and using the keyboard shortcut Command+V. If you'd like to replace the text with the link, use the keyboard shortcut Command+Shift+V.

This site was built using [GitHub Pages](https://pages.github.com/).
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

Context	Relative Link
In a .md file on the same branch	/assets/images/electrocat.png
In a .md file on another branch	/../main/assets/images/electrocat.png
In issues, pull requests and comments of the repository	../blob/main/assets/images/electrocat.png?raw=true
In a .md file in another repository	/../../../../github/docs/blob/main/assets/images/electrocat.png
In issues, pull requests and comments of another repository	../../../github/docs/blob/main/assets/images/electrocat.png?raw=true
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
- George Washington
* John Adams
+ Thomas Jefferson
1. James Madison
2. James Monroe
3. John Quincy Adams
4. 1. First list item
   - First nested list item
     - Second nested list item
     - - [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
Rendered task list
@github/support What do you think about these updates?
If a task list item description begins with a parenthesis, you'll need to escape it with \:
- [ ] \(Optional) Open a followup issue
For more information, see "About task lists.
@octocat :+1: This PR looks great - it's ready to merge! :shipit:
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
  <!-- This content will not appear in the rendered Markdown -->
Ignoring Markdown formatting
You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.

Let's rename \*our-new-project\* to \*our-old-project\*.

Screenshot of rendered GitHub Markdown showing how backslashes prevent the conversion of asterisks to italics. The text reads, "Let's rename our-new-project to our-old-project."

For more information on backslashes, see Daring Fireball's "Markdown Syntax."
