# FlowPilot — Design & Implementation Decisions

## Product and direction

FlowPilot is a workflow intelligence concept for technical teams. The visual direction uses warm off-white surfaces, deep green ink, restrained lime accents, and a technical mono layer to feel polished without copying another product.

## Main UI/UX choices

The hero introduces the product through a live dashboard, not a decorative image. Preview data is explicitly labelled as illustrative. The page moves from promise to product, capabilities, an interactive workflow simulation, and a low-pressure CTA. Hover and run-state motion supply feedback where it matters.

## Trade-off

To keep the project dependency-light, the component library is deliberately small and icons are inline SVG paths rather than a full icon package.

## With a full week

I would add more dashboard states, richer keyboard navigation within the preview, visual regression checks at target breakpoints, and usability feedback from technical users.

## AI usage and verification

AI assistance was used for the initial component and CSS implementation. The result was reviewed and adjusted for content honesty, responsive layout, dark-theme tokens, semantic controls, and build compatibility.

## Scope and accessibility

This is frontend-only because the assignment is an interface challenge; demo workflow data is local state. Controls use semantic buttons and links, focus rings, labelled toggles, mobile navigation, responsive grids, and reduced-motion rules.
