# Cookware-Website

# Peer Review Feedback

**Peer Reviewed By:** Robert Grijalva

## Comments

### Navbar

- [] There’s a large margin pushing the text down.
- [] Hover effects are missing.
- [] The logo alignment is slightly off.

### Start Cooking Section

- [] The images are bleeding out of the container.
  - Recommendation: Place the image into a container with `overflow: hidden`.
- **Mobile Issue:** [] The containers overlap the text.

### New Arrivals Section

- [] No hover effect to darken the image.
  - Recommendation: Use a CSS class like:
    ```css
    .darken-on-hover:hover {
      filter: brightness(0.8);
    }
    ```
- [] The color picker is missing padding.
  - Recommendation: Wrap the circle in a container, add padding, and apply a border to the container.

### Best Sellers Section

- [] Missing a zoom effect on hover.
- **Mobile Issue:** [] The card layout breaks, resulting in two cards on one row and one on the next.
- [] The button appearance suggests it may bleed out of the container.

### Reviews Section

- [] Missing margin outside of the container.

### Footer

- [] The text is pushed up to the top of the footer.
  - Recommendation: Use CSS:
    ```css
    margin-top: auto;
    margin-bottom: auto;
    ```
- **Mobile Issue:** [] The height of the footer has issues.

### Mobile Issues (General)

- [] The navigation bar is sticky, which may cause layout problems.
- [] Numerous mobile-specific issues need attention.

---

### Final Thoughts

There are several layout and responsiveness issues, especially on mobile. Focus on fixing the mobile design for better usability.
