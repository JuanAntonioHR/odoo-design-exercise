# Odoo Landing Page – Frontend Exercise

## Live Demo
[View deployed project](https://odoo-design-exercise-y263.vercel.app/)



## Setup
```bash
git clone https://github.com/JuanAntonioHR/odoo-design-exercise
cd odoo-design-exercise
npm install
npm run build
```

You can open the project by simply opening `index.html` in your browser.
For a better development experience, you can use a local server:
```
npx serve .
```

##  Development

If you want to automatically recompile SCSS on changes:

```
npm run dev
```

## Comments & Notes

-   When it comes to the navigation bar, I noticed that none of the buttons corresponded to any specific section on the page, so I didn't link them to anything.
- The typeface I found that best matched the text design is Magnum Sans Pro. I also noticed that the iconography was very similar to the icon styles in Lucide, so both were used in the final product.
- The final version was tested and optimized to be responsive on mobile, tablet, and desktop screens


## What I find good in the mock-up

-   **Well-structured layout**  
    The overall section flow is logical and well planned (Hero, Features, Reasons to Buy, FAQ, Final CTA), making the content easy to follow.
    
-   **Consistent spacing and grouping**  
    Spacing and border usage feel cohesive. It is clear which elements belong together, and visual grouping is handled consistently across sections.
    
-   **Clear and consistent color usage**  
    The design makes good use of a defined color system. Primary, secondary, and tertiary colors are easy to identify, and buttons remain consistent by mainly using the primary color and white.
    
-   **Simplicity and minimalism**  
    The page follows a clean and minimal approach, focusing on the key messages without unnecessary visual noise.

##  What I find could be improved

-   **Lack of mobile design considerations**  
    There is no explicit mobile version provided. While this is not necessarily a blocker, it introduces ambiguity during development.  
    Ideally, responsive behavior should be defined during the design phase to avoid assumptions and reduce development time.
    
-   **Inconsistent feature section block**  
    One of the feature blocks breaks the visual consistency: it lacks a clear title, and the paragraph text visually resembles a heading.  
    This affects readability and consistency. I would align it with the structure used in other sections.
    

##  What I would change

-   **Design-to-development workflow improvement**  
    Instead of building directly from a static image, I would first recreate the design in a tool like Figma with a defined design system (spacing, typography, colors).  
    This would significantly streamline development, as components and styles would already be clearly defined and aligned with the chosen framework (Bootstrap in this case).
        
-   **Missing language selector**  
    As an international product, adding a language selector (at least English/Spanish) would improve accessibility and usability.
    
-   **Feature section lacks problem-oriented messaging**  
    The features focus mainly on capabilities rather than user pain points.  
    Emphasizing problems and how the product solves them would create a stronger connection with users.

-   **Weak final CTA (Call to Action)**  
    The CTA should be one of the strongest sections of a landing page, reinforcing the value proposition and encouraging conversion.  
    However, this section feels like the simplest one: a plain background with a very generic message (“I want to start a new project”) and two conflicting actions (“Buy now” and “Learn more”).  
    The intent is unclear, and the visual weight does not match its importance. I would redesign this section to make it more compelling and focused on a single clear action.
    
-   **Redundant CTAs in the footer**  
    The footer includes “Documentation” and “Purchase now” buttons, which are already present in the navbar (“Docs” and “Buy now”).  
    This repetition feels unnecessary and slightly aggressive from a UX perspective. I would simplify this section.
    
-   **“Buy now” as the primary navbar action**  
    Highlighting “Buy now” as the main action may not be the best choice without first presenting pricing or value clearly.  
    I would suggest introducing a **pricing section** or page. If a free tier exists, a “Start for free” CTA would likely be more effective and user-friendly.
    
-   **Brand identity misalignment**  
    Although this is a landing page for Odoo, it does not strongly reflect the brand identity.  
    After further research, I would adjust:
    -   Color palette (closer to Odoo branding)
    -   Typography
    -   Component styling and grouping (using more distinctive shapes and layouts)  
        This would make the page feel less like a generic template and more like a branded experience.
