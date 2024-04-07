## Accessibility assigment
Alma mater: [Accessibility Unity](https://accessibilityunity.com/en/)
Website link: https://iuliiaockhama.github.io/a11y-assignment/
TG contact link: [@enemorrian](https://t.me/enemorrian)

### 🐻 Implemented Accessibility Improvements:
1) Semantic HTML Fixation:
Introduced essential semantic tags such as `<main>`, `<header>`, and `<footer>`.
Ensured proper `heading` hierarchy.
Organized navigation links within lists for improved screen reader navigation.
2) Skip-link Integration:
Implemented a skip-link functionality facilitating quick navigation to the main content area.
3) Breadcrumb Enhancement:
Enclosed breadcrumbs within `<ol>` tags in accordance with W3C APG guidelines.
Augmented with relevant ARIA attributes for enhanced accessibility.
4) Form Accessibility Enhancements:
Rectified issues in the product card form by incorporating `<label>` tags, for attributes, and `aria-labelledby` attribute for better form association.
5) Modal Window Improvements:
Addressed accessibility concerns in modal windows by including all requisite ARIA attributes and enhancing focus management.
Augmented modal table content with additional ARIA attributes for improved screen reader comprehension.
Introduced a close button for better user experience. (A little UX improvement ✨)
6) Radio Group Optimization:
Improved radio groups by adding `aria-atomic` and `aria-live` attributes to the group legend.
Provided context to disabled radio buttons for clarity.
7) Stepper Input Refinement:
Rectified issues with stepper input by assigning accessible names to buttons and incorporating built-in validations for quantity input.
8) Accordion Component Enhancement:
Implemented ARIA attributes in the accordion component following W3C APG recommendations for enhanced accessibility.
9) Footer Navigation Fixation:
Reorganized footer navigation by enclosing links within lists and resolving accessibility issues within the form.
10) Alt Attributes for Images:
Added relevant alt attributes to images where necessary to provide alternative text for screen reader users; added additional texts, accessible only for screen readers, to icon-only buttons.

11) Styles improvements:
Improved focus styles for better visibility (removed `outline: none` for links and buttons).

### 🐶 Notes and Queries:
1) The website underwent testing solely with VoiceOver on MacOS.
2) Modal Window query: VoiceOver does not alert about the opening of the modal window. (Is this behavior expected?)

### 🐨 Good to be done:
1) Color Contrast: Ensure that the color contrast between the text and its background meets the WCAG AA standard for better readability. (This issue was marked as critical in `axe devtools` and `IBM Equal Access` checker).
2) Error Identification: Ensure that form validation errors are identified and described to the user in text. Probably, should add a descriptive error message to product form and email form in footer.
3) Resize Text: Make sure the text on the website can be resized up to 200% without loss of content or functionality. (Fonts are not resizable in the current implementation).