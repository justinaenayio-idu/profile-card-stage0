
---

## 🧠 `TESTING.md`

```markdown
# TESTING.md — Profile Card Stage 0

This file documents how the **Profile Card Component** was tested to ensure functionality, responsiveness, and accessibility.

---

## ✅ Functional Tests

| Feature            | Test Performed                                                      | Result |
|----------|----------------|--------|
| **User name**      | Verified it displays correctly in the header (`data-testid="test-user-name"`) 
| ✅ Passed |
| **User bio**       | Confirmed the bio text is visible (`data-testid="test-user-bio"`)       
| ✅ Passed |
| **User avatar**    | Image loads correctly with proper alt text (`data-testid="test-user-avatar"`) 
| ✅ Passed |
| **Current time**   | Time updates dynamically every second (`data-testid="test-user-time"`) 
| ✅ Passed |
| **Social links**   | Each link opens in a new tab and is accessible (`data-testid="test-user-social-*`) 
| ✅ Passed |

---

## 📱 Responsiveness Tests

- Tested on screen sizes: **Mobile (375px)**, **Tablet (768px)**, and **Desktop (1440px)**.  
- Layout adjusts gracefully — the avatar and content stack on smaller screens.  
- No horizontal scrolling or overflow detected.  
✅ **All responsive tests passed.**

---

## ♿ Accessibility Tests

- Used semantic HTML5 elements (`<article>`, `<header>`, `<section>`, `<nav>`, `<figure>`, `<figcaption>`).  
- Verified that text contrast meets WCAG standards.  
- All interactive elements (links) are reachable via keyboard navigation.  
✅ **Accessibility confirmed.**

---

## 🌍 Browser Compatibility

| Browser | Tested | Result |
|----------|---------|--------|
| Chrome | ✅ | Works perfectly |
| Edge | ✅ | Works perfectly |
| Firefox | ✅ | Works perfectly |
| Safari | ⚪ | Not tested (no macOS device) |

---

## 🧩 Validation

- **HTML validated** via [W3C Validator](https://validator.w3.org/).  
- **CSS validated** via [Jigsaw Validator](https://jigsaw.w3.org/css-validator/).  
- **JavaScript** passed ESLint basic checks — no console errors or warnings.

---

## 🗒️ Notes
- Project follows semantic and accessible web design standards.  
- The time feature uses `Date.now()` and updates every second.  
- The avatar image (`onyene-justina-enayi.jpg`) is included locally.  

---

**Final Verdict:**  
✅ All functional, responsive, and accessibility checks passed.  
🚀 Ready for deployment and submission.
