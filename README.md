
# READ ME - Horiseon Website </h1>

User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

Updates:

HTML Changes -> Accessibility and Search Engine Optimisation Optimization:

Changed website tittle to Horiseon - before was "website";
Added alt text on images and icons for SEO and accessibility;
Removed the heart emoticon from the footer - added the word "love" instead for accessibility;

.CSS stylesheet changes.

Removed unused CSS


I added device width to the head meta HTML to improve readability on mobile and added a meta discription to help with general SEO.
Matched the page < title > to the < H1 > to optimise for google.
Organised the H tags 1-6 where appropiate.
Added "alt" text to images.
Added device width to the head meta HTML to improve readability on mobile and added a meta discription to help with general SEO. Images in the assest folder were too large and slowed loading speed, the original images are still in ./asset incase we need to revert but are not linked in the HTML and "-min" was added to new file names to identify compressed files. See outline below:
original	updated
search-engine-optimization.jpg (14.9MB)	search-engine-optimization-min.jpg (2.5MB)
online-reputation-management.jpg (6.9MB)	online-reputation-management-min.jpg (1MB)
social-media-marketing.jpg (14.2MB)	social-media-marketing-min.jpg (1.7MB)
digital-marketing-meeting.jpg (14.2MB)	digital-marketing-meeting.jpg (1.4MB)
HeadingHTML/body changes.
Code added to the li items in the navigation menu can be removed to quickly disable the hover css animation if innapropriate.
.CSS stylesheet changes.
Added a max width of 1100px (larger than any individual element) to the * css tag to keep the content sized correctly on desktop view.
added a relitive position to the body css and a fixed position to the header tag. My goal was to keep the navigation prominant to help with accesability.
Margins on the * tag changed to auto to center the content.
MISC.
