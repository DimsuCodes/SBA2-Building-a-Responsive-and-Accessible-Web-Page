Accessible Design Co.

A responsive, accessible one-page website for a fictional web design agency. Built for the Per Scholas SBA with semantic HTML, CSS Flexbox and Grid, and JavaScript form validation.

My nav links had no href, so keyboard users couldn't Tab to them. I also had to learn how to connect each form field to its error message with aria-describedby and unique ids.
I wrote mobile-first CSS with breakpoints at 600px and 1024px, and tested by resizing the window. I added a visible focus outline, checked color contrast, and used aria-live so screen readers announce the form result.

Tools like WebAIM contrast checker and browser devtools helped me out a lot.