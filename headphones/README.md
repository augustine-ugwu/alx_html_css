# Headphones Landing Page

This project is a responsive landing page for a headphone company, designed to be visually appealing and user-friendly. The layout adapts seamlessly between desktop, tablet, and mobile devices, providing a great user experience across all screen sizes.

## Features

- **Responsive Design**: The layout automatically adjusts for different screen sizes, switching to the mobile version when the screen width is 480px or less.
- **Interactive Elements**: Links and buttons include hover/active states for a more dynamic user interaction.
- **Clean and Modern Layout**: The page layout is centered with a maximum content width of 1000px for a polished appearance.

## Design Notes

- Fonts used:

  - `Source Sans Pro`
  - `Spin Cycle OT`

- Interaction Details:

  - **Links Hover/Active State**: Color changes to `#FF6565`.
  - **Button Hover/Active State**: Opacity decreases to `0.9`.

- Content is centered with a maximum width of 1000px for a balanced layout.

## Folder Structure

```
.
├── index.html          # Main HTML file
├── css
│   └── style.css       # Styling for the page
├── js
│   └── script.js       # JavaScript for interactivity
├── assets
│   ├── images          # All image assets
│   └── fonts           # Custom fonts (Source Sans Pro, Spin Cycle OT)
└── README.md           # Project documentation
```

## Responsiveness

The webpage is designed to adapt to the following screen sizes:

- **Desktop**: Default layout with all features fully displayed.
- **Tablet**: Adjusted layout for medium screen sizes.
- **Mobile**: Compact layout for screens 480px wide or less.

### Breakpoints

```css
@media (max-width: 480px) {
  /* Styles for mobile layout */
}
```

### Additional Notes

- Make sure all values in the design are rounded where necessary if they appear as floats in the design specifications.
- The `README.md` serves as a quick reference for project setup, usage, and contribution guidelines.
