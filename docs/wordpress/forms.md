# Gravity Forms Documentation Guide

##  Quick Start

### Form Content Organization
- **Questions**
- **Surveys and Events**

### Questions Anatomy
Learn the structure of form questions and how to design them for clarity and usability.

---

##  Form Design Guide

### Design Resources
- **Gravity Forms Docs:** [https://docs.gravityforms.com/](https://docs.gravityforms.com/)
- **Form Design Principles:** [How to Style Gravity Forms](https://www.gravitykit.com/how-to-style-gravity-forms/#h-why-form-styles-are-important-to-think-about)
- **Official CSS Guide:** [Gravity Forms CSS Reference](https://gravityforms.s3.us-east-1.amazonaws.com/support/docs/css_guide/css_guide.html)
- **Elementor Integration Guide:** [Gravity Forms + Elementor](https://www.gravitykit.com/gravity-forms-elementor/)
- **Gravity Forms Styling Widget:** [Gravity Forms Elementor Widget](https://www.gravitykit.com/products/gravity-forms-elementor-widget/)

### Consistent Styling Across the Site
To make all forms follow the same styling:
- [Where to Put Your Custom CSS](https://docs.gravityforms.com/where-to-put-your-custom-css/)
- [How to Find the WordPress CSS File](https://zellwk.com/blog/find-wordpress-css/)

### Surveys
- [Creating Surveys with Gravity Forms](https://www.gravityforms.com/blog/creating-surveys-with-gravity-forms/)
- [Gravity Forms Survey Add-On](https://www.gravityforms.com/add-ons/survey/)

---

##  Initial Styling (Base CSS)

> This initial style defines the basic visual foundation for Gravity Forms.  
> Adjust this CSS to maintain visual consistency across all pages and platforms.
*Note this will change

```css
body .gform_wrapper {
  font-family: 'Alegreya';
  color: black;
}

body .gform_wrapper input:focus,
body .gform_wrapper textarea:focus,
body .gform_wrapper select:focus {
  border-color: #F16E22 !important;
  box-shadow: 0 0 0 0.1px #F16E22 !important;
  outline: none !important;
}

/* Radio and checkbox accent color */
body .gform_wrapper input[type="radio"]:checked::before,
body .gform_wrapper input[type="checkbox"]:checked::before {
  background-color: #F16E22 !important;
  border-color: #F16E22 !important;
  color: #fff;
}

/* Newer versions (modern inputs) */
body .gform_wrapper .gfield-choice-input:checked {
  accent-color: #ff7a00 !important;
}

/* Submit button color */
body .gform_wrapper .gform_button {
  background-color: #F16E22 !important;
  border: none;
  color: #fff;
  transition: background-color 0.3s ease;
}

/* Submit button hover color */
body .gform_wrapper .gform_button:hover {
  background-color: #F16E22 !important;
}

/* Accessibility focus outline */
body .gform_wrapper .gform_button:focus {
  box-shadow: 0 0 0 1px #F16E22 !important;
}
```