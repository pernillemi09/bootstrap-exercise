# Bootstrap Exercises
This repo contains a collection of exercises to practice working with Bootstrap.  
The exercises are based on existing templates, so you can get experience navigating real code, making changes,
and adding new features.

## Exercises

### Portfolio
Solve these exercises on the template in the `portfolio` folder.

<details>
<summary>#1 Change dummy dropdown to "Projects"</summary>

The dummy item **"Dropdown"** in the main menu should be renamed to **"Projects"**.  
Update the dropdown contents to match the structure below.  
The text in parentheses shows the link each item should point to.

  - Projects (projects.html)
    - Web Design (projects/web-design.html)
    - Branding (projects/branding.html)
    - Game Development (projects/game-development.html)
      - Unity (projects/unity-projects.html)
      - Game Jams (projects/game-jams.html)
      - Browser Games (projects/browser-games.html)
    - 3D & Motion (projects/3d-and-motion.html)
      - 3D Modeling (projects/3d-modeling.html)
      - Animations (projects/animations.html)

> [!TIP]
> Just change in the `index.html`, no need to copy-paste to all the files for this exercise.

</details>

<details>
<summary>#2 Change testimonials on about page to be cards</summary>

On the `about.html` page, update the testimonials section to use Bootstrap cards.  
Use the content that’s already there, but fit it into the structure of the card component.

You can start with the example here:  
https://getbootstrap.com/docs/5.3/components/card/#example

> [!TIP]
> To center a card, the utility class `m-auto` is often enough.

</details>

<details>
<summary>#3 Add badges to services</summary>

On the `services.html` page, add badges to two service cards:
- A green badge labeled `Popular`
- A blue badge labeled `New`

The badges should be placed in the top-right corner inside the service card.  
Use Bootstrap's badge component and positioning utilities to make it work.
</details>

---

### Admin
Solve these exercises on the template in the `admin` folder.

<details>
<summary>#4 Add accordion instead of "Daily Sales" and "Users online"</summary>

On the `index.html` page, replace the "Daily Sales" and "Users Online" widgets with a Bootstrap accordion.  
The accordion should have the following 6 sections, and the first one should be open by default:

- Getting Started
- Managing Users
- Understanding Analytics
- Customizing the Dashboard
- Security & Access Control
- FAQs & Troubleshooting

> [!TIP]
> You can use the default accordion content from the documentation - just change the headings.

</details>

<details>
<summary>#5 Add import button in "User Statistics"</summary>

In the "User Statistics" section of `index.html`, add a new button to the left of the existing **Export** button.  
The new button should say **Import**.

Replace the current icons with Font Awesome icons:
- `fa-upload` for the Import button
- `fa-download` for the Export button
</details>

<details>
<summary>#6 Add upgrade modal when clicking "Add Customer"</summary>

On the `index.html` page, clicking the **Add Customer** button should open a modal popup asking the user to upgrade.

The modal should include:
- A title: **Upgrade now**
- Body text: *This feature requires you to upgrade to a Pro version.*
- A **Close** button (secondary style)
- An **Upgrade** button (success style)
- The modal should be vertically centered
</details>

<details>
<summary>#7 Add progress bar</summary>

On the `index.html` page, just above the "User Statistics" widget, add a new row with a Bootstrap progress bar.

- The progress should be at **85%**
- Use a **yellow** color with **animated stripes**

> [!TIP]
> Use Bootstrap's spacing utilities to add margin under the new row.

</details>

---

### Build your own
Solve this exercise in the `index.html` file in this folder.

<details>
<summary>#8 Use Bootstrap components to build your own</summary>

Pick and use components from the docs and the examples to build out a full page.  
Don't worry about content, just make a mockup of components you feel fit together.

- https://getbootstrap.com/docs
- https://getbootstrap.com/docs/5.3/examples/

Ideas for sections:
- Navigation
- Hero area
- Featured
- Pricing
- Footer

> [!TIP]
> If your editor has red lines under something, make sure to hold your mouse
> over, to see what the error is, and fix the errors before you get more errors.

</details>

---

## Links

Find more templates:  
- https://startbootstrap.com/?showPro=false
- https://themewagon.com/theme-framework/bootstrap-5/?pa_price=free
