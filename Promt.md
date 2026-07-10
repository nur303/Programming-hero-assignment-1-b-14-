Generate the complete HTML and CSS for a tech conference "Schedule at a Glance" section. 

**HTML Structure:**
Create a `<section class="schedule-glance">` containing a `.timeline` div and a bottom `.cta-box`. 
- Inside the timeline, create 3 `.timeline-item`s for March 15, 16, and 17, 2026. 
- Each item needs a `.timeline-marker` and a `.timeline-content` card. 
- Inside the card include: a `.day-badge`, `.day-title`, `.day-date`, and a `.day-highlights` container with 4 `.highlight-item`s (each containing a `.time` and `.event`).
- The `.cta-box` should have a text prompt and a `.btn-primary` download button.

**CSS Layout & Styling:**
- **Timeline:** Max-width 900px, centered. Use a `::before` pseudo-element to draw a 4px vertical line down the exact center.
- **Alternating Layout:** Use flexbox on `.timeline-item`. Make odd items `flex-direction: row` and even items `row-reverse` to zig-zag the `.timeline-content` cards (45% width, white bg, 16px radius, soft shadow) across the center line.
- **Markers:** Center the 24px `.timeline-marker` circles over the line with 4px white borders. Color Day 1 #667eea, Day 2 #764ba2, and Day 3 #f59e0b.
- **Theme & Gradients:** Use a linear gradient from #667eea to #764ba2 for the timeline center line, badges, and the `.cta-box` background.
- **Inner details:** Give `.highlight-item`s a light gray background (#f9fafb), 8px border-radius, and a 3px solid #667eea left border. The CTA button should be white with purple text, turning yellow (#fbbf24) with brown text on hover.

Please output only the HTML and CSS code.