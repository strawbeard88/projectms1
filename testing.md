# PMCBYGG Website – Testing

## Introduction
This document details the testing process carried out for the PMCBYGG website to ensure that it meets the required functionality, design, and accessibility standards.

Testing included manual checks, validation of HTML and CSS, responsiveness assessments, accessibility testing, and performance verification.

---

## Manual Testing

### Navigation
- Verified that all navigation links work and lead to the correct pages.
- Confirmed that navigation is consistent across all pages.
- Checked that the logo links to the home page.

### Hero Section
- Verified that the hero image displays correctly on desktop, tablet, and mobile.
- Confirmed that hero text remains readable against the background image.

### Services Section
- Verified that all service descriptions are displayed correctly.
- Confirmed that icons/images match the related service.

### About Us Section
- Checked that the company description is complete and correctly formatted.

### Contact Page
- Verified that contact details are correct and visible.
- Confirmed that the contact form fields validate correctly (required fields cannot be left blank).
- Ensured that links to email addresses and phone numbers work correctly on mobile devices.

---

## Responsiveness Testing
The site was tested on multiple devices and screen sizes to ensure correct layout and readability.

**Devices tested:**
- Desktop (1920px wide)
- Laptop (1366px wide)
- Tablet (768px wide)
- Mobile (375px wide)

**Browsers tested:**
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Safari (latest, macOS and iOS)

**Findings:**
- Layout adapts correctly on all tested devices.
- No horizontal scrolling present on normal viewports.
- Images resize proportionally.

---

## Accessibility Testing

### Keyboard Navigation
- Confirmed that all links, buttons, and form fields can be accessed using the keyboard (Tab/Shift+Tab).
- Verified visible focus styles.

### Alt Text
- All images include descriptive `alt` attributes.

### Color Contrast
- Checked text and background combinations using a contrast checker.
- Verified that contrast ratios meet WCAG 2.1 AA requirements.

---

## Validation

### HTML Validation
- Used the W3C Markup Validation Service.
- No major HTML validation errors found.

### CSS Validation
- Used the W3C CSS Validation Service.
- No critical CSS validation errors found.

### Lighthouse testing
- Good results with lighthouse testing also
---

## Browser Compatibility
- Website displays consistently across all major browsers tested.
- No browser-specific styling issues detected.

---

## Known Issues
- Largest Contentful Paint (LCP) can be improved by further optimizing the hero image for faster load times.
- Performance can be improved by removing unused CSS
- Some minor layout adjustments may be beneficial for ultra-wide screens (2400px+).

---

## Conclusion
The PMCBYGG website meets the required functionality, design, and accessibility standards. It is responsive across devices and accessible to users with different needs. Minor performance improvements are recommended for optimal loading speed.
