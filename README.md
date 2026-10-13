# NexaTech Solutions — CSS Group Assignment

A four-page fictional technology agency website, based on the supplied CSS assignment.

## Run
Open `index.html` in a browser. Navigate to About, Services, and Contact using the shared header. No build tools required.

## Assignment compliance
- Four pages: Home, About, Services, Contact
- Semantic HTML5, shared header and footer, external vanilla CSS
- Flexbox layouts only; **no CSS Grid or JavaScript**
- Roboto font imported from Google Fonts
- Required colors: #1F2937, #F9FAF8, #E5E7EB, #3882F6
- 48px desktop hero heading, 36px information heading and testimonial
- CSS-only checkbox + label mobile burger navigation
- Responsive SVG illustrations with `<picture>` and `<source>` for narrow screens; `max-width:100%; height:auto` prevents distortion
- Media queries for 800px and 480px breakpoints

## Testing checklist
1. Test at 375px, 768px, and 1200px using browser developer tools.
2. Verify no horizontal scroll, overlapping sections or distorted images.
3. Verify the burger menu opens and closes without JavaScript.
4. Check keyboard focus and navigation on each page.
5. Contact form is a demonstration `mailto:` form, not a deployed backend.

## Team collaboration / AI evidence
Create a shared GitHub repository, invite teammates, assign page ownership, use feature branches and pull requests. Record at least four actual AI-assisted stages (idea review, navigation concept, responsive image choice, final code review), including team attempts, AI suggestions, decisions and test results. Do not claim unperformed tests or collaboration.

## Explanation
The mobile menu uses a visually hidden checkbox. Its associated label toggles the checked state; the CSS sibling selector displays the navigation only while checked. The `<picture>` element chooses a simpler mobile illustration at widths <=600px; scalable SVGs stay crisp and retain aspect ratio.
