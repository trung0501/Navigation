🏷️ Program name: The navigation bar interface has a dropdown and underline effect in HTML & CSS

🎯 Program Purpose: Create a beautiful, modern navigation bar, with an intuitive effect (dynamic bricks when mouse and menu falling down when hover) to serve introduction websites, portfolio or personal information page, without using JavaScript.

🧩 The main component of the program:

📄 HTML:

    . nav: Tag containing the entire navigation bar.

    . a.item: Main items such as Home, About, Skills, Contact.

    . div.dropdown: Submenu of Skills item (including skills: C#, Angular, Javascript).

    . div.underline: Dynamic underline effect bar below.

🎨 CSS:

    . Color variable (:root) to define the main color.

    . Flexbox to layout horizontal and centered menu.

    . Hover effect to control the display of dropdown and underline.

    . Transition effect for underline.

⚙️ Principle of operation:

  1. When the user accesses:

     . The navigation bar is displayed in the middle of the screen, with the items: Home, About, Skills, Contact.

  2. When the user hovers:

     . Go to the “Skills” item: The dropdown appears with 3 options.

     . Go to any item: A small underline bar runs below that item, creating a sense of interaction.

  3. The dropdown is displayed using CSS:

     . Hidden by default (display: none).

     . When hovering over the parent item (.item), the child dropdown will be displayed (display: flex).

  4. Underline is controlled by CSS--hover-index:

     . Calculating the underline position according to the position of the section being hover (Home is 0, about is 1 ...).

     . The effect runs smoothly by transition.

✅ Advantages:

    . Beautifully harmonious color interface, corner, shady, smooth effect.

    . Works entirely with HTML + CSS without JavaScript, easy to deploy.

    . Intuitive and friendly Dropdown when Hover, Underline run smoothly, creating a sense of interaction.

    . Easy to expand can add more items or discoloration, easy content. 

⚠️ Limit: 

    . Not responsive not optimized for mobile or small screens.

    . No real links Items have no href, just empty <a> tags.

    . No keyboard controls Dropdown cannot be accessed by tab/key, because there is no JavaScript support.

    . Fixed number of items If more items are added, the underline needs to be recalculated manually (because width: 25% is fixed).
