i have make the ai section in three part 
first i make the design with the help of ai 
then using the design i have told ai to make the html fine
after completin the html file i have told ai to make css file


so the promp:1 is for the design
prompt:1
I am designing a modern developer conference landing page in Figma. The page already includes a Hero section, a Speakers section, and a Pricing section. I need a new section that naturally fits between the Pricing section and the Footer.

Design a clean and modern Conference Schedule section that matches the existing visual style of the website. Use a minimalist white and blue color palette, rounded corners, subtle shadows, clean typography, and plenty of whitespace. The design should feel like it was part of the original landing page.

The section should include:
- A small blue label above the heading.
- A large heading introducing the conference schedule.
- A short descriptive paragraph.
- A simple Day 1, Day 2, and Day 3 navigation styled as buttons (visual only, no functionality required).
- A list of schedule cards showing the time, an icon, session title, speaker name (where applicable), and a short description.
- A primary call-to-action button at the bottom labeled "View Full Schedule".

The design must be fully implementable using only HTML and CSS. Use Font Awesome icons instead of custom image assets to keep the implementation simple. The overall layout should be clean, professional, and consistent with the rest of the conference website.

prompt:2 is for the html file

prompt:2
Generate the semantic HTML structure for a modern Conference Schedule section for a developer conference landing page.

The section should match a minimalist white-and-blue design with rounded cards and clean typography. It will be placed between the Pricing section and the Footer.

Requirements:
- Use semantic HTML5 elements.
- Wrap everything inside a <section> with an appropriate class name.
- Include a heading area with:
  - A small blue label.
  - A large heading.
  - A short descriptive paragraph.
- Create a row of three buttons labeled "Day 1", "Day 2", and "Day 3" (visual only, no JavaScript functionality).
- Create five schedule cards.
- Each schedule card should contain:
  - The event time.
  - A Font Awesome icon.
  - The session title.
  - The speaker name when applicable.
  - A short description.
- Add a "View Full Schedule" button at the bottom using the existing class "common-btn".
- Use meaningful and readable class names.
- Do not include CSS or JavaScript.
- Use Font Awesome `<i>` tags for icons instead of image files.
- Keep the HTML properly indented and well commented so it is easy for a beginner to understand.

prompt:3 is the css
prompt:3
Generate modern CSS for a Conference Schedule section of a developer conference landing page.

The HTML structure is already created. Write only the CSS.

Requirements:
- Use a clean, modern, and minimalist design.
- Match the visual style of the rest of the website, which uses a white background, blue accent color (#2962FF), rounded corners, subtle shadows, and generous spacing.
- The section should have:
  - A centered heading with a small blue label, a large bold title, and a descriptive paragraph.
  - Three day buttons (Day 1, Day 2, Day 3) displayed in a horizontal row using Flexbox. Style them as visual tabs only (no JavaScript functionality).
  - A vertical list of schedule cards.
- Each schedule card should:
  - Use Flexbox for layout.
  - Display the event time on the left.
  - Show a Font Awesome icon inside a light-blue rounded square.
  - Display the session title, speaker name (if available), and description.
  - Have rounded corners, a soft box shadow, and a subtle hover effect using transform and transition.
- The "View Full Schedule" button should be centered at the bottom and use the existing `.common-btn` class without overriding its main styles.
- Use meaningful spacing, padding, margins, and typography.
- Keep the CSS well organized with comments for each section.
- Do not use CSS frameworks such as Bootstrap or Tailwind.
- Do not use JavaScript.
- Write clean, beginner-friendly CSS that is easy to understand and maintain.