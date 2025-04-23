#1 -

Today we begin a new series: "A Quarto tip a day keeps the docs away" -- a playful attempt to share Quarto tips daily for the next month.
Follow along:

🐦 #quartotip 🔗 https://rstd.io/quartotip

And, of course, don't keep the docs away, they're incredibly helpful and thorough!

------------------------------------------------------------------------

#2 -

#quartotip 1: Use the layout-ncol chunk option to organize output in columns, e.g. layout-ncol: 2 for two tables side-by-side.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/01-side-by-side-tables/

\[insert-image\]

alt-text: R code for generating two tables from mtcars and cars datasets and placing them next to each other as well as the output tables side-by-side.
Code and tables can be found in the linked blog post.

------------------------------------------------------------------------

#3 -

#quartotip 2: Use the echo: fenced chunk option to display the fences around your code chunks in your output.
Super useful for teaching Quarto!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/01-side-by-side-tables/

\[insert-image\]

alt-text: Two R chunks are displayed.
The top R chunk is the output, and shows the chunk options label: simple-arithmetic, results: hide.
The R code in the chunk is 1 + 1.
Also visible are the fences of the R chunk.
The bottom R chunk is the input, which shows the same content as the top chunk, plus an additional chunk option: echo: fenced.
The text reads "To get code chunks printed out as \[the top chunk\], add the echo: fenced option to your chunk".
Code and text can also be found in the linked blog post.

------------------------------------------------------------------------

#4 -

#quartotip 3: Use the freeze: true or freeze: auto execution option for finer control over when documents in Quarto projects are re-rendered.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/03-freeze/

\[insert-image\]

alt-text: YAML file with two execute options.
The first one is freeze: true and the comment that goes with it reads "never re-render during project render".
The other one is freeze: auto and the comment reads "re-render only when source changes".

------------------------------------------------------------------------

#5 -

#quartotip 4: Use the include shortcode to include content from a file in another file.
Helpful for including repeated content in multiple documents.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/04-freeze/

\[insert-image\]

alt-text: A file called content-to-repeat.qmd is shown.
The file includes one sentence: Look at me, I'm content to be repeated.
This sentence is in italics.
Arrows and file icons depict how this file can be included in two different files with the same include shortcode.
The code can be found in the linked blog post.

------------------------------------------------------------------------

#6 -

#quartotip 5: Use the output-location chunk option to control where code output is shown -- delayed (fragment), in the next slide (slide), in the next column (column), or delayed in the next column (column-fragment).

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/05-output-location/

\[insert-image\]

alt-text: Slide with content presented in two columns.
On the left is the code, which has the chunk options output-location: column as well as fig-width: 6 and fig-height: 4.
The code uses ggplot2 to create a scatterplot of penguin bill depth vs. length, colored by species.
On the right is output showing this plot.

------------------------------------------------------------------------

#7 -

#quartotip 6: Customize which documents are included in a listing by using the contents option, which allows you to provide a set of input files (or globs of input files) that should be included in the listing.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/06-listing-contents/

\[insert-image\]

alt-text: YAML file showing listings as the top field and contents as a sub-field under that with the value posts/\*/index.qmd.
An arrow points to the contents sub-field and text annotation for the arrow says customizable.

#8 -

#quartotip 7: Use the chalkboard: true option for revealjs slides to annotate your slides by drawing on them or opening up an empty chalkboard within your presentation.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/07-slide-annotation/

\[insert-image\]

alt-text: Two slides.
First one is a slide with the title Penguins and a plot that shows the relationship between bill depth and bill length for penguins, colors by species.
Clusters of species are marked with red annotation on the slide.
The second one is slide with chalkboard background and the word Hello!
is written in white chalk.

------------------------------------------------------------------------

#quartotip 8: Switching over from #rmarkdown to Quarto?
Read the reading the FAQ for R Markdown Users!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/08-rmd-switch/

\[insert-image\]

alt-text: Screenshot of the FAQ for R Markdown users page.
with the description 'Answers to R Markdown users' most frequently asked questions about Quarto.' The questions answered are: What can I use Quarto for?,
Quarto sounds similar to R Markdown.
What is the difference and why create a new project?,
Is R Markdown going away?
Will my R Markdown documents continue to work?,
Should I switch from R Markdown to Quarto?,
I use X (bookdown, blogdown, etc.).
What is the Quarto equivalent?,
Can you create custom formats for Quarto like you can for R Markdown?,
When would be a good time to start new projects in Quarto rather than R Markdown?,
Does the RStudio IDE support Quarto?,
Does RStudio Connect support Quarto?

------------------------------------------------------------------------

#quartotip 9: If you want to create an entirely self-contained HTML document (with images, CSS, etc. embedded into the HTML file), set self-contained: true in the YAML of your document.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/09-self-contained/

\[insert-image\]

alt-text: YAML with format html and option self-contained set to true.

------------------------------------------------------------------------

#quartotip 10: To publish a file not explicitly linked from pages in your Quarto site (or if the auto-detection of a linked file fails), add a `resources` entry to the `_quarto.yml` file of your project or an individual page's metadata.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/10-site-resources/

\[insert-image\]

alt-text: Two YAML entries.
First one is for the project configuration, the second one is metadata for a single page.
First one defines project, type: website, resources: "\*.pdf".
Second one defined title: "Syllabus", resources: "syllabus.pdf".

------------------------------------------------------------------------

#quartotip 11: You can apply styles to inline text by creating spans using `[]` to surround the text you want to style and `{}` to define the style you want to apply.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/11-spans/

\[insert-image\]

alt-text: Two pieces of source code an the output of each.
The first one shows the sentence To draw attention to a specific part of the text, you might want to make it red with a yellow background; like this.
spans used to change color of the text.
The second one shows code for a slide with three separate fragments.
Both examples are in the linked blog post.

------------------------------------------------------------------------

#quartotip 12: Want to embed an iframe on a webpage or a slide deck?
Plop the sharing code in a raw html block!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/12-html-block/

\[insert-image\]

alt-text: On top, a screenshot of the Insert Anything tool in the RStudio Visual Editor to insert an HTML block.
An arrow from this points to the bottom image, which is an HTML block containing raw HTML code for including the Quarto Documentation at quarto.org in an iframe.
The complete code can be found in the linked blog post.

------------------------------------------------------------------------

#quartotip 13: If you're a Homebrew person, chances are you'd like to install and update Quarto with Homebrew.
Read on for a couple options for doing so!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/13-homebrew/

\[insert-image\]

alt-text: On top, the homebrew logo, an orange heart, and the Quarto logo.
Underneath the code for two options for installation via Homebrew.
Option 1 is brew install --cask quarto.
Option 2 is brew tap rundel/quarto-cli followed by brew install quarto.
And at the bottom the code for updating Quarto with Homebrew: brew upgrade quarto.
The complete code can be found in the linked blog post.

------------------------------------------------------------------------

#quartotip 14: Yet another way to highlight a portion of a slide: slide zoom with Alt+Click!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/14-slide-zoom/

\[insert-image\]

alt-text: Find the bunny among the cats slide from the post, being zoomed in and out three times.

------------------------------------------------------------------------

#quartotip 15: Need help with something Quarto related?
Post a question on GitHub Discussions or open an issue!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/15-help/

\[insert-image\]

alt-text: Screenshot of Discussions page for the quarto-dev/quarto-cli repo with the word Questions next to it and the screenshot issues page for the same repo with the word bug reports next to it.

------------------------------------------------------------------------

#quartotip 16: Link to the source code on your document using code-tools: true, or customize how you link to it with various options.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/16-code-tools/

\[insert-image\]

alt-text: Three ways of linking to source code from within your document, each presented with its associated YAML.
(1) Make source code available on page.
(2) Link to source code on repo.
(3) Link to any file as source code.
The associated YAML fields are provided in the linked blog post.

------------------------------------------------------------------------

#quartotip 17: Quarto websites support light and dark themes and automatically add a light/dark toggle if you supply both themes.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/17-dark-mode/

\[insert-image\]

alt-text: Switching between light and dark mode using the toggle on the blog homepage navbar.

------------------------------------------------------------------------

#quartotip 18: Including Font Awesome icons in Quarto documents is now easy peasy lemon squeezy 🍋 with the Font Awesome extension.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/18-font-awesome/

\[insert-image\]

alt-text: Code for installing the Font Awesome extension for Quarto: quarto install extension quarto-ext/fontawesome and a table that shows the input syntax and output icon for the icons brands apple, calendar, user-doctor, and door-closed.

------------------------------------------------------------------------

#quartotip 19: Need some Quarto inspiration?
Want to see examples of what others are creating with Quarto?
And importantly, *how* they're creating them?
Take a look at the newly refreshed Quarto Gallery!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/19-gallery/

\[insert-image\]

alt-text: Scrolling through the Quarto Gallery at quarto.org/docs/gallery.

------------------------------------------------------------------------

#quartotip 20: YAML intelligence, including completion and diagnostics, make writing project files, YAML front matter, and executable cell options easy for experts and new learners.
Available in the RStudio IDE and in VS Code!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/20-yaml-intelligence/

\[insert-image\]

alt-text: Three code chunks with YAML chunk options being edited.
The first one showcases YAML completion for fields \-- typing e brings up options that start with e.
The second one showcases YAML completion for options \-- eval can be set to true or false.
The third one showcases diagnostics that are provided in the case of errors \-- setting eval to FALSE (with capital letters) prompts a message that says it should be true or false.

------------------------------------------------------------------------

#quartotip 21: Create diagrams in Quarto documents using Mermaid or Graphviz in executable code cells, similar to how you create figures.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/21-diagrams/

\[insert-image\]

alt-text: Diagram depicting how Quarto orchestrates rendering of documents: start with a qmd file, use the Knitr or Jupyter engine to perform the computations and convert it to an md file, then use Pandoc to convert to various file formats including HTML, PDF, and Word.

------------------------------------------------------------------------

#quartotip 22: You can create interactive Quarto documents using Shiny.
To do so:

-   add server: shiny to the YAML of your document
-   define Shiny UI elements in plain code chunks
-   place Shiny server code in chunks with option context: server

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/22-shiny/

\[insert-image\]

alt-text: Code and output for a radioInput() widget that asks the question Are you a cat or dog person?
with choices Cat person, Dog person, Don't make me choose, and Neither.
An arrow points to code for defining output\$radio_output that places the widget value in a renderPrint() function.
Finally, code and output for rendering the widget value with verbatimTextOutput().
Complete code can be found in the blog post.

------------------------------------------------------------------------

#quartotip 23: If you have revealjs slides with no titles and you want them to have informative URLs and placeholder titles on the presentation outline, define a slide ID and data-menu-title.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/23-titleless-slides/

\[insert-image\]

alt-text: A slide with no title but slide ID and data-menu-title defined.
Arrows point to where these pieces of information go on the slide URL and presentation outline.
The screenshots are from Slide 3 of the example in the blog post, where the complete code can be found.

------------------------------------------------------------------------

#quartotip 24: Add citations with \@rstudio's Visual Editor directly from a DOI.
Paste DOI and let it find the reference and place in a bib file for you!

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/24-citations/

\-\--

Alt-text for GIF: Inserting citation from DOI with Visual Editor.
Steps in blog post.

\[insert-gif\]

------------------------------------------------------------------------

#quartotip 25: Add aria-labels to your navigation icons to make them accessible to screen readers as a YAML field.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/25-aria-labels/

\[insert-image\]

alt-text: YAML definition for adding the twitter icon and aria-label to the Quarto documentation site.
The resulting html which shows an icon, a link, and an aria-label.
And the output, the Twitter icon on the navbar.

------------------------------------------------------------------------

#quartotip 26: Add alt-text to images that will be displayed in places like blog post thumbnails, social cards, etc. with image-alt.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/26-image-alt/

\[insert-image\]

alt-text: YAML for adding the alt text for the blog featured image.
The resulting html which shows the alt text for the image.
And the output, blog post listing with the featured image.

------------------------------------------------------------------------

#quartotip 27: Add audio indicator to your slides that plays as you progress from one slide to next or from incremental build to next.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/27-slide-tone/

\[insert-image\]

alt-text: Slide with an incremental list with three items.
Arrows between each item and a loudspeaker icon at each arrow indicates audio would be played as you progress through items.
Also shown is the YAML required for this feature, which is available in the linked blog post.

------------------------------------------------------------------------

#quartotip 28: Add alternative text to figures created in Knitr, Jupyter, and Observable chunks with fig-alt.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/28-fig-alt/

\[insert-image\]

alt-text: YAML for adding the alt text for a figure created with code.
The resulting figure as well as the HTML which shows the alt text for the image.

------------------------------------------------------------------------

#quartotip 29: Use a11y as an accessible syntax highlighting style and have it automatically adapt to light/dark setting of your webpage.

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/29-a11y-theme/

\[insert-image\]

alt-text: YAML for setting highlight-style to a11y as well as for light and dark theme (also provided in the blog post) and the resulting webpage in light and dark mode showing how the a11y theme adapts.

------------------------------------------------------------------------

#quartotip 30: Curious about Quarto?
Browse @thomas_mock 's slides from Day 1 on #rstudioconf2022 and don't miss Day 2 talks!

Link to slides: http://rstd.io/quarto-curious

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/30-quarto-curious/

\[insert-image\]

alt-text: Cover slide with the words Quarto for the curious and photo of an old quarto style printed book.\

------------------------------------------------------------------------

#quartotip 31: Don't miss @juliesquid and I talk about Quarto at #rstudioconf2022 at 9am ET.
Join us in Potomac A or on the live stream at rstd.io/conf.
#rstudioconf #rstats

Link to slides: https://mine.quarto.pub/hello-quarto

Read more: https://mine-cetinkaya-rundel.github.io/quarto-tip-a-day/posts/31-hello-quarto/

\[insert-image\]

alt-text: Illustration of two penguins, one blue and one orange, taking a selfie with a selfie stick.
The moon in the background looks like the Quarto logo.
Art by Allison Horst.
