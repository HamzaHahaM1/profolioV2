# profolioV2
 a clean and professional single-page portfolio for a Front-End Engineer named Jordan Parker. It's built using HTML, styled with Tailwind CSS, and includes dynamic features powered by JavaScript libraries.

Key Features:

    Clean & Modern Design: The layout is spacious, using a clear typographic hierarchy and a consistent color scheme.

    Responsive Layout: It's fully responsive, ensuring a great user experience on desktops, tablets, and mobile phones.

    Interactive UI: Features include a mobile-friendly navigation menu, an animated skills chart, and subtle on-scroll animations.

    Component-Based Structure: The code is well-organized into logical sections like About, Skills, and Projects, making it easy to manage.

How It's Built

The website is a single HTML file divided into several key sections.

Header and Navigation (<header>)

    A sticky navigation bar that stays at the top of the viewport when scrolling, with a semi-transparent, blurred background.

    The main navigation links smoothly scroll to the corresponding sections on the page.

    A mobile menu button (hamburger icon) toggles a dropdown menu for smaller screens. The icon cleverly transforms into an "X" when the menu is open.

Hero Section (<section>)

    This is the introduction, featuring a large headline, a professional summary, and primary call-to-action buttons ("Let’s Talk" and "View Work").

    It also includes social media links (GitHub, LinkedIn, Email) and a circular portrait image.

About Section (<section id="about">)

    Provides a more detailed biography, highlighting experience and key strengths.

    Uses a two-column layout to separate a paragraph of text from a bulleted list of key skills or philosophies.

Skills Section (<section id="skills">)

    This section showcases technical abilities.

    It features a bar chart to visually represent proficiency in different technologies (e.g., React, Vue, Node).

    Next to the chart, a list of technologies is categorized into Front-End, Back-End, and Tools for clarity.

Projects Section (<section id="projects">)

    Displays a portfolio of work in a grid of project cards.

    Each card has a project image, a title, a short description, and a "View Case" link. The image zooms in slightly on hover for a nice interactive effect.

Contact Section (<section id="contact">)

    A two-column section for getting in touch.

    One column contains a contact form with fields for name, email, and message.

    The other column provides alternative contact information like location, email, and phone number, each accompanied by an icon.

Footer (<footer>)

    Contains the copyright notice, with the year automatically updated by JavaScript, and another set of social media links.

Scripts (<script>)

The JavaScript at the end of the file powers the site's dynamic functionality:

    Lucide Icons: Renders the icons used throughout the page.

    Mobile Navigation: Manages the showing and hiding of the mobile menu and switches the icon between "menu" and "x".

    Chart.js: Creates and configures the animated bar chart for the skills section.

    Intersection Observer: Handles the staggered fade-in and slide-up animations for each section as the user scrolls down the page.

    Dynamic Year: Ensures the copyright year in the footer is always current.

How to Use and Customize It

This template is very easy to personalize. Follow these steps to make it your own:

Personal Information

    Name and Title: Change "Jordan Parker" and the job title ("Product-minded Front-End Engineer") in the <title> tag, the <header>, and the <h1> in the hero section.

    Text Content: Rewrite the text in the hero, about, and skills sections to reflect your own background, skills, and experience.

    Contact Details: Update the email address, location, and phone number in the contact section and the mailto: links.

Images

    Portrait Image: In the hero section, replace the src URL in the <img> tag with a link to your own photo. For best results, use a square image.

    Project Images: In the "Projects" section, update the src URL for each <article> to a screenshot from your own work.

Projects

    Modify the project cards by changing the title (<h4>), description (<p>), and the link (<a>) for each one.

    You can easily add or remove projects by duplicating or deleting the <article> elements.

Skills Chart

Customize the bar chart in the JavaScript section to match your skills:

    Labels: Edit the skill names in the labels array:
    JavaScript

labels: ['JavaScript', 'HTML/CSS', 'Python', 'SQL', ...],

Data: Adjust the corresponding proficiency scores (out of 100) in the data array:
JavaScript

    data: [90, 95, 70, 80, ...],

Links

    Social Media: In both the hero section and the <footer>, replace the href values for the GitHub and LinkedIn links with your personal profile URLs.

    Case Studies: Update the href="#" in the project cards to link to your live projects or detailed case studies.

Styling and Colors

The visual style is controlled by Tailwind CSS classes.

    Primary Color: The main accent color is blue-600. You can perform a find-and-replace to change this to another color like teal-600 or indigo-600 to quickly change the site's theme.

    Fonts: The site uses a default sans-serif font stack. You can import a custom font (like from Google Fonts) in the <head> and apply it by changing the font-sans class on the <body> tag.

