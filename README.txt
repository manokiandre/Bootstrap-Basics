+--------------------------------------------------------------------------
Bootstrap Basics, Utilities, Forms, and Components Knowledge Check - README
---------------------------------------------------------------------------

OVERVIEW
This project is a single-page HTML site demonstrating various Bootstrap 5 features, 
including responsive navigation, fluid images, responsive utilities, forms, and 
table styling.

FEATURES
1. Navigation Bar
   - Uses Bootstrap's responsive navbar with brand name and collapsible menu.
   - Includes "Home", "About", and "Contact" links.

2. Images
   - Full-width responsive banner image using .img-fluid and .w-100 inside .container-fluid.
   - Centered circular image using .rounded-circle and .img-fluid.

3. Responsive Buttons
   - Primary button always visible on all screen sizes.
   - Secondary button hidden on small screens using .d-none and .d-md-block.

4. Registration Form
   - Uses Bootstrap's grid system to align "First name" and "Last name" side-by-side.
   - Includes "Email" and "Password" fields.
   - Checkbox for Terms of Service agreement.
   - Submit button styled with .btn-success and .w-100.
   - Placeholder .invalid-feedback elements for client/server-side validation messages.

5. Responsive Table
   - Wrapped in .table-responsive for horizontal scrolling on smaller screens.
   - Styled with .table-hover and .table-striped classes.
   - Header row styled with .table-success.

TECHNOLOGIES USED
- HTML5
- Bootstrap 5.3.0 (CSS and JS via CDN)

USAGE
1. Open index.html in any modern web browser.
2. Resize the browser window or use device emulation tools to see responsive 
   behaviors (navbar collapse, button visibility changes, table scroll).
3. Form fields and validation placeholders require server-side or JavaScript 
   logic for actual validation.

NOTES
- The .invalid-feedback messages are hidden until .is-invalid is applied via 
  JavaScript or server-side rendering.
- Images are externally hosted; ensure network access for them to display.
- The secondary button’s visibility is controlled entirely with Bootstrap 
  responsive display utility classes.

---------------------------------------------------------------------------
End of README
--------------------------------------------------------------------------+