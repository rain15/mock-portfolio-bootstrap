This is a mobile-first responsive website using Bootstrap CSS that I converted from an existing page I had created in skillcrush 101 course.

The original assignment was to convert a PSD Design file to HTML/CSS.

My process to convert skillcrush-101 site (Jubilee Austen website I did in one of the lessons)

- Downloaded my github solution for the site.
- Downloaded HTML5 Boilerplate
- Unzipped and Renamed folder name to "skillcrush-101-boostrap"
- Copied bootstrap css and dependent JS files into renamed HTML5 Boilerplate.
- Copied image assets from skill crush-101 folder to skillcrush-101-bootstrap’s “img" sub-folder.
- Copied content from skillcrush css and index html file to existing main.css and index.html file in the HTML5 Boilerplate directory. HTML5Boilerplate has other things in its main.css and index.html. So I did not overwrite the files. Instead I copied the contents.
- Looked at http://getbootstrap.com/examples/cover/ which is similar to Jubilee Austen page
    - http://getbootstrap.com/getting-started/#examples
    - Get the source code for every example  by downloading the Bootstrap repository. Examples can be found in thedocs/examples/ directory.
- If you want to be consistent with bootstrap’s media query sizes that it uses for xs, sm, md, lg, then use sizes mentioned here at http://getbootstrap.com/css/#grid-media-queries or at  http://stackoverflow.com/questions/18424798/twitter-bootstrap-3-how-to-use-media-queries
- To use hamburger nav menu in mobile version, I looked at downloaded code for https://getbootstrap.com/examples/navbar/
- I used google chrome Inspect tool a lot to fix alignment and size issues.

TODO TASKS:

- Fix all the px to rem.
- widths should be in percentages.
- Check alignments
- Right now, I made website mobile-first with media query for tablet and greater size. I need to go back and add specific to tablet and desktop after thinking about design changes for each.

