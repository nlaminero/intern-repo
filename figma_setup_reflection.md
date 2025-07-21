# Figma Setup Reflection

## What are the core features of Figma, and how is it different from other design tools?
Figma is a cloud-based UI/UX design tool that works directly in the browser (or desktop app), which means no installs or file sharing issues. Its core features include frames, vector editing, prototyping, commenting, and real-time collaboration. What makes it different from tools like Adobe XD or Sketch is that it’s fully collaborative — multiple people can work on the same file at once, and all changes are saved instantly in the cloud.

## How does Figma support collaboration between designers, developers, and PMs?
Figma allows comments to be added directly to designs, which is great for giving feedback. Designers can tag developers or product managers, and everyone sees updates in real-time. Developers can inspect elements, see spacing, colors, fonts, and copy the CSS directly. There’s no need to send screenshots or exports — everything is live.

## What are components, variants, and auto-layout, and how do they improve design efficiency?
- Components are reusable design elements (like buttons or cards) that can be updated once and reflect across the whole file.
- Variants are different states or styles of a component (e.g., default, hover, disabled) grouped into one master component, making it easier to switch styles.
- Auto-layout helps maintain spacing, resizing, and alignment when content changes. It saves time when designing responsive layouts and keeps everything consistent.

## How do you share and hand off designs to developers using Figma?
Developers just need view access to the file. They can inspect design elements, check measurements, see specs, and even copy values like hex codes and padding. Designers can organize everything into named pages, use components clearly, and leave notes or redlines to guide devs through tricky parts. Figma also integrates with tools like Zeplin or Storybook if needed.

---

## Reflection

### How would you organize a design system in Figma to ensure consistency?
I’d create a separate page or file for the design system, with categories like Colors, Typography, Components, and Icons. I’d use naming conventions (e.g., `Button/Primary`, `Form/Input/Error`) and group reusable elements into components with variants. I’d also apply auto-layout to all major components to make scaling easier. Documenting usage rules (e.g., spacing, when to use what) helps make it clear.

### If a developer needs details about a design component, how would you provide that using Figma?
I’d make sure the component is labeled properly and placed in an organized frame. Then I’d use the Inspect panel — which developers can access by clicking an element — to show exact specs, sizes, colors, and text styles. I’d also leave comments if there’s anything custom or important to note (like hover behavior or interaction flow). I could even create a dev handoff page if needed.

### What challenges might arise when collaborating in Figma, and how can you avoid them?
One challenge is when too many people edit the same frame or make changes without communicating. Another is unclear organization, which leads to devs not knowing where to look. To avoid this, I’d lock final frames, use version history when needed, label pages and components clearly, and always communicate major changes to the team before editing shared files.
