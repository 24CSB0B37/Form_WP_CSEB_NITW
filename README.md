# CW_1_Form

This repository contains two distinct forms: one for **Internships** and another for **Research Opportunities**.

### 1. **Internship Form**
This is the main form designed for internship registrations.

[Go to Internship Form](form_internship.html)

---

### 2. **Research Form**
This auxiliary form is for research opportunities and offers an improved user interface.

[Go to Research Form](form_research.html)

---

### Additional Features:
- **Marquee with Hyperlink**: A scrolling marquee that contains a clickable hyperlink for navigation.
- **Image with Hyperlink**: An image embedded in the form that acts as a clickable link.
- **Bidirectional Hyperlinks**: Seamless navigation between the internship and research forms via hyperlinks.
- **Hidden Fields**: Hidden form fields that can be dynamically shown or hidden based on user interactions. This functionality can be powered by JavaScript onclick. These are temporarily hidden.
- **Centered and better alternative interface**: Research form is centered and with a better user interface.

---

### JavaScript Function for Hidden Fields:
The hidden fields functionality can be achieved adding the following JavaScript function: (Not added yet since the assignment is only html with inline css)

```javascript
function clickref(id, action) {
    if (action === 'show') {
        document.getElementById(id).style.display = 'block';
    } else if (action === 'hide') {
        document.getElementById(id).style.display = 'none';
    }
}
