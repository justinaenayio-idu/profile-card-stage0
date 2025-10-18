## 🧪 TESTING.md

### Automated Testing
This project includes `data-testid` attributes for all required elements to allow automated testing.

**Test IDs include:**
- `test-profile-card`
- `test-user-name`
- `test-user-bio`
- `test-user-time`
- `test-user-avatar`
- `test-user-social-links`
- `test-user-hobbies`
- `test-user-dislikes`

These attributes make it possible for automated tools to query and validate the component structure and data.

### Manual Testing
To test manually:
1. Open the live project link in a browser.
2. Inspect elements (Right-click → Inspect → Elements tab).
3. Search (`Ctrl + F`) for each `data-testid` to confirm they exist.
4. Verify:
   - The current time updates correctly (in milliseconds).
   - Avatar image displays properly with an alt attribute.
   - All social links open in a new tab and are keyboard-accessible.
   - The layout remains responsive on mobile, tablet, and desktop.

### Accessibility
- Semantic HTML tags were used (`<article>`, `<header>`, `<figure>`, `<nav>`, `<section>`).
- Links and buttons are fully keyboard-focusable.
- Alt text added for images.
