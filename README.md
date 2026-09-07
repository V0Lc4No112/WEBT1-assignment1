# Assignment 1 - Space Notes

Mereikhan Sholanbayev, IT-2511

A three-page website made with HTML5 and one external CSS file.
Open index.html in a browser. No installation or build command is needed.

## Files

- index.html: introduction, two sections, two lists and two photos.
- about.html: Apollo 11 history, a figure, quotation, local audio and mission table.
- contact.html: a practice form using native browser validation.
- css/style.css: all page styling.
- images/: NASA photographs stored locally.
- media/small-step.mp3: NASA audio stored locally.

The form does not send messages. The text, email, number, date, textarea and
checkbox controls deliberately omit name attributes so their values are not
included in the GET request. The radio controls share name="topic" to form one
group; only that non-personal preference appears in the query string.

## Sources and credits

Facts: https://www.nasa.gov/specials/apollo50th/missions.html
Apollo 11: https://www.nasa.gov/missions/apollo/apollo-11/apollo-11-mission-overview/
Landing quotation: https://www.nasa.gov/history/alsj/a11/a11.landing.html
Photos: https://www.nasa.gov/wp-content/uploads/static/history/ap11ann/kippsphotos/apollo.html
aldrin.jpg: NASA / Neil Armstrong, AS11-40-5903.
launch.jpg: NASA, S69-39526.
Audio: https://www.nasa.gov/historical-sounds/
Media use: https://www.nasa.gov/nasa-brand-center/images-and-media/
NASA is credited as the source; no NASA endorsement is implied.

## GitHub Pages

Repository: https://github.com/V0Lc4No112/WEBT1-assignment1
Site address: https://v0lc4no112.github.io/WEBT1-assignment1/
Publish from the main branch, root directory, in Settings > Pages.

## Short defense notes

- header, nav, main and footer describe the role of each page area.
- alt text describes images; figcaption supplies the visible credit/context.
- th and scope connect table headings to their rows or columns.
- colspan="2" joins two cells in the table footer.
- for and id connect each form label to its control.
- required, type="email", min/max and minlength use browser validation.
- The radio inputs share a name so only one choice can be selected.
- Element selectors affect tags, class selectors are reusable, and #intro
  styles one unique introductory paragraph.
- px is used for borders and maximum width; % gives fluid widths; rem scales
  text and spacing with the root font; em scales control spacing with its font.
- margin is outside a border; padding is inside it.
- A hover effect helps mouse users; a focus outline helps keyboard users.

Before the defense, read each file and practice changing a heading, a CSS
spacing value and one table row. Review the report's learning conclusion and
adapt it to your own understanding before submission.
