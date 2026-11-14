# An illustrated, scroll-driven interpretation of CSS Zen Garden

## The Concept

*The Same House, A New Look* tells a visual story across three chapters. The house and character remain familiar, but their surroundings, colors, and motion evolve as the visitor scrolls. This reflects the central idea behind **CSS Zen Garden**: the same HTML content can take on a different visual identity through CSS alone.

Rather than presenting unrelated designs, I chose a continuous storybook format. Each chapter introduces a new treatment of the same scene, with animated transitions connecting one setting to the next.

## Original Artwork and SVG Process

**I digitally hand-drew the character, house, and landscape specifically for this project.** They are my original illustrations—not artwork provided by the CSS Zen Garden challenge.

After drawing the artwork, I **converted the illustrations into SVG (Scalable Vector Graphics)** and organized them as separate character, house, and landscape assets for each chapter. This approach serves three purposes:

- **Independent animation:** The character, house, and landscape can move separately through CSS background-position animations.
- **Consistent composition:** Reusing the same illustration proportions keeps the house and character recognizable from chapter to chapter.
- **Responsive scaling:** SVGs remain sharp as the illustrations resize between desktop, tablet, and phone layouts.

The hand-drawn illustrations establish the project's visual identity; the SVG conversion makes them practical to position, layer, and animate on the website.

## The Three Chapters

1. **Chapter One — The Beginning:** A muted beige setting introduces the characters. While scrolling, the character exits to the left and the house moves downward, leaving the landscape behind.
2. **Chapter Two — A New Look:** A greener, brighter scene shows the same subjects in a different style. The house enters from above, and the character returns from the left.
3. **Chapter Three — The Transformation:** A warm-toned final scene assembles itself as the landscape rises from below, the house descends, and the character moves into place.

## How It Was Built

- **HTML:** The original challenge's HTML structure remains unchanged.
- **CSS:** Grid layouts, pseudo-elements, custom properties, and responsive media queries control the design.
- **SVG:** Original hand-drawn artwork is converted into layered vector assets.
- **Animation:** CSS keyframes and scroll-driven animation timelines coordinate each chapter's transitions without JavaScript.
- **Accessibility:** Reduced-motion preferences are respected; illustration animations depend on browser support for modern CSS scroll timelines.

On wider screens, text and illustration appear side by side. On smaller screens, the chapters adapt to a single-column layout, with animation timing adjusted for the stacked scenes.

## View the Project

**Live site:** [albany072001.github.io/csszengarden](https://albany072001.github.io/csszengarden/)

**Figma prototype:** [Zen Garden interactive prototype](https://www.figma.com/make/Y0tiZPtx1F0dcxfnPLPQsk/Zen-Garden-interactive-prototype?t=NLvEqgWIJfCm20rV-20&fullscreen=1)

To run the project locally, clone or download the repository and open `index.html` in a browser, or use a local static server. Keep the CSS and SVG asset paths intact. The project is static and does not require a backend or build step.

### GitHub Pages

The implemented website is hosted on **GitHub Pages**, which serves the repository's HTML, CSS, and SVG assets. Updates to the configured publishing branch or workflow are reflected in the deployed site after GitHub Pages completes deployment.

## Credits and Attribution

**CSS Zen Garden**, created by **Dave Shea** in 2003, is the original design challenge that invites designers to transform a page's appearance using CSS while preserving its HTML. See the [CSS Zen Garden website](https://www.csszengarden.com/) and its [source repository](https://github.com/mezzoblue/csszengarden.com).

**My contribution:** The *The Same House, A New Look* concept, original digitally hand-drawn character, house and landscape illustrations, SVG conversion and layering, CSS styling, responsive layouts, and scroll-based animation implementation.

This is an independent interpretation of the CSS Zen Garden challenge, not an official endorsement or collaboration with its creators.