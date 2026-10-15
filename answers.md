# Control questions – answers

1. **Block vs inline elements.** Block elements (`div`, `p`, `h1`, `section`) start on a new line and take the full available width; width and height can be set. Inline elements (`span`, `a`, `strong`) flow within a line, take only the space they need, and ignore width/height and vertical margins.
2. **CSS box model.** Every element is a box made of content, padding, border and margin (from inside out). With `box-sizing: border-box`, width includes padding and border.
3. **Positioning types.** `static` (default), `relative` (offset from its normal place), `absolute` (relative to the nearest positioned ancestor), `fixed` (relative to the viewport, used for the modal), `sticky` (switches between relative and fixed while scrolling, used for the nav).
4. **`name` attribute in forms.** It is the key under which the field's value is sent to the server (`name=value`). Fields without a name are not submitted. It also groups radio buttons.
5. **margin vs padding.** Padding is the space inside the border, between content and border, and shows the element's background. Margin is the space outside the border, between elements, and is transparent (vertical margins can collapse).
6. **Semantic tags.** HTML5 tags that describe meaning, not just looks: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `figure`. They help accessibility, SEO and code readability.
7. **Specificity.** When rules conflict, the browser picks the more specific selector: inline style > ID selectors > classes, attributes, pseudo-classes > elements and pseudo-elements. On equal specificity the later rule wins; `!important` overrides all.
8. **HTTP methods in forms.** `GET` puts data in the URL (searches, non-sensitive data); `POST` sends it in the request body (logins, messages, changes). The `method` attribute accepts only these two.
9. **Pseudo-classes vs pseudo-elements.** Pseudo-classes (one colon) select an element in a state: `:hover`, `:focus`, `:valid`, `:invalid`, `:nth-child()`. Pseudo-elements (two colons) select a part of an element or generate content: `::before`, `::after`, `::first-line`, `::placeholder`.

# Site structure
Three separate pages linked by the navigation: `index.html` (biography), `career.html` (key dates and achievements), `contact.html` (forms).

# Technologies used
HTML5 semantic markup, CSS3 (custom properties, flexbox, float, position relative/absolute/fixed/sticky, gradients, box-shadow, border-radius, transitions, keyframe animation, `:target`-based modal, form validation pseudo-classes) and responsive media queries. No JavaScript.
