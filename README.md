# Service & Sales Appliance Repair

A clean, modern website for a local appliance repair company specialising in fridge, freezer, washing machine, and oven repairs. Built using **HTML5** and **CSS3**.

![Website mock-up for responsive design](assets/readme-references/mock-up/mock-up.png)

[View the live project here!](https://lukem1aa.github.io/milestone-project-one/)

---

## Table of Contents
1. [Project Overview](#project-overview)
    - [Developer and Business Goals](#developer-and-business-goals)
2. [User Experience (UX)](#user-experience-(ux))
    - [User Stories](#user-stories)
    - [Design Choices](#design-choices)
        - [Colour Palette](#colour-palette)
        - [Typography](#typography)
        - [Imagery](#imagery)
    - [Website Structure & Accessibility](#website-structure--accessibility)
    - [Wireframes](#wireframes)
3. [Features](#features)
    - [Existing Features](#existing-features)
    - [Future Enhancements](#future-enhancements)
4. [Technologies Used](#technologies-used)
    - [Languages](#languages)
    - [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)
5. [Testing](#testing)
    - [HTML Validation](#html-validation)
    - [CSS Validation](#css-validation)
    - [Performance](#performance)
        - [Testing on Devices](#testing-on-devices)
        - [User Story Testing](#user-story-testing)
        - [Bugs & Fixes](#bugs--fixes)
6. [Deployement](#deployment)
7. [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
    - [Code](#code)
    - [Acknowledgement](#acknowledgement)


---
## Project Overview

This website provides users with an easy way to: 
- Learn about appliance repair services
- Contact the business for quotes or bookings
- Find information on common appliance issues

The website is designed to be clear, responsive, and user-friendly for all visitors.

### Developer and Business Goals
- Increase visitor-to-customer conversion by reducing friction in booking and contact
- Build trust through social proof (reviews)
- Encourage quick action with easy contact options
- Strengthen local presence via targeted, helpful contact

## User Experience (UX)

### User Stories
As a **potential customer**, I want to:

1. Quickly see what types of appliances you repair so that I can feel confident your services meets my needs
    * ✅ The home page clearly list major appliance types *(e.g. ovens, fridges, washing machines, dishwashers)*
    * ✅ There's a dedicated **Our Services** page with further detail
    * ✅ Appliance types appear within the first screen on desktop and mobile *(no scrolling required)*
2. See clear pricing or how to get a quote, so that I can make a decision without needing to call first
    * ✅ There is a **Pricing** or **Get a Quote** button visible on the home page
    * ✅ Clicking this takes the user to a form or price guide with estimated costs or a simple quote request form
    * ✅ The form can be completed in under 2 minutes
3. Be able to easily book a repair visit online, so that I don't have to wait to speak to someone
    * ✅ The website has a **Book Now** button on all main pages
    * ✅ Booking form allows selection of appliance type, issue, date, and contact details
    * ✅ Customer receives an email or SMS confirmation after booking
4. See positive reviews or testimonials from real customers, so I feel reassured about the quality of your service
    * ✅ At least 3 customer reviews are visible on the home page
    * ✅ Reviews are real *(from Google, Trustpilot or direct customers)*
    * ✅ There's a link to view more reviews
5. See photos of your work or your team, so I can trust that you're professional and reliable
    * ✅ The home page features at least 1 image of the team or repair work
    * ✅ There is a gallery or **About Us** page with photos that look professional and friendly

As a **customer**, with an urgent repair: 

1. See contact details immediately so that I can reach you fast
    * ✅ A clickable phone number is in the site header and footer
    * ✅ Contact options *(phone, WhatsApp, email)* are visible on the home page without scrolling

As a **returning customer** I want to:

1. Quickly find your contact page or booking form, so I can request another repair without fuss
    * ✅ Contact/booking links are always visible in the main menu
    * ✅ Returning users can book or contact in under 3 clicks/ taps

As a **mobile user** I want your: 

1. Website to load fast and work well on my phone, so I can use it easily when I'm on the go
    * ✅ All key buttons *(book, contact)* are finger-friendly and easy to tap
    * ✅ Content is readable without zooming on small screens

As a **local resident** I want to: 

1. See comments and reviews about common appliance faults and fixes, so I can recognise when I need a repair
2. See social media posts about common appliance faults and fixes, so I can recognise when I need a repair
    * ✅ At least 1 educational/ helpful post per week about appliance faults/ tips
    * ✅ Posts are written in plain language, not technical jargon
  
As a **busy homeowner** I want to: 

1. See your opening hours, service area, and services at a glance, so I know you cover my location and needs
    * ✅ Website list opening hours, main appliance types, and service area *(e.g. **Serving Herts & North London**)*

### Design Choices

#### Colour Palette

The following [colour palette](assets/colour-palette/colour-palette.png) is generated via [Coolors.co](https://coolors.co):

- **Primary Text:** Oxford Blue `#1B2A41`
- **Accent:** Orange (Crayola) `#FF6B35`
- **Secondary Accent:** Giants Orange `#FA591F`
- **Hero Accent:** Celeste `#9BE6EC`
- **Background:** White Smoke `#F5F5F5`
- **Navigation/ Footer:** Anti-flash White `#ECECEC`
- **Content Background:** Silver `#B2B2B2`
- **Body Text:** Jet `#333333`

These colours have been chosen to convey trust, clarity, and a clean modern look suitable for an appliance repair business.

##### Accessibility Contrast

The colour palette has been chosen with the aim to meet [WCAG 2.1](https://www.w3.org/TR/WCAG21) AA contrast requirements for readability and accessibility:

- **Primary #1B2A41** on **backgrounds #F5F5F5** provides strong contrast for headings and key UI elements (12.2:1 contrast ratio / AAA WCAG)
- **Body text #333333** on **backgrounds #F5F5F5** meets recommended contrast for standard text (15.2:1 contrast ratio / AAA WCAG)
- **Accent #FF6B35** is used for buttons and calls to action, always paired with sufficient contrast (e.g. white on orange buttons)
- Small orange text on light backgrounds will be avoided to maintain readability

*All colours have been checked against [Coolors Color Contrast Checker](https://coolors.co/contrast-checker).*

⚠️ If you customise this palette, please check that new combinations maintain sufficient colour contrast for users with visual impairments. 

#### Typography
The following typography is imported from [Google Fonts](https://fonts.google.com/):
- **Primary font:** [Host Grotesk (Medium 500)](https://fonts.google.com/specimen/Host+Grotesk) - used for headings and key UI text
- **Secondary font:** [Source Code Pro](https://fonts.google.com/specimen/Source+Code+Pro) - used for snippets and technical elements
- **Body:** [Inter](https://fonts.google.com/specimen/Inter?query=inter) - used for paragraphs and general content

##### Google Fonts Link

```<style>
@import url('https://fonts.googleapis.com/css2?family=Host+Grotesk:ital,wght@0,500;1,500&family=Inter:ital,opsz,wght@0,14..32,100.900;1,14..32,100..900&family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&display=swap');
    </style>
```

##### Accessibility Typography

The fonts have been chosen with readability and accessibility in mind:

- Provide sufficient letter spacing and clear distinction between characters
- Avoid decorative fonts or excessive stylisation that could impair readability
- Pair with strong colour contrast to support users with low vision or dyslexia

Where possible:

- **Responsive sizing** so text remains readable on all devices
- **Scalable units (e.g. rem/em)** so users can resize text in their browser without breaking layout

*Further accessibility best practices are considered in styling and layout to ensure inclusive design.*

#### Imagery

##### Favicon

Favicon chosen to match elements of the colour palette and give a clean modern look suitable for an appliance repair business - favicon imported via [Fontawesome.com.](fontawesome.com)

![Washing Machine](assets/favicon/washing-machine.png) - 20x20 PNG file

##### Logo

The business logo was used in the navigation bar and across key pages - designed and generated via [Canva.com.](canva.com)

![Business logo](assets/images/logo.svg)

- **File type:** SVG
- **Usage:** The logo is lightweight, scalable, and responsive to ensure clarity on all devices and screen sizes
- **Placement:** Positioned in the navbar to support brand identity without overwhelming content
- **Sizing:** Controlled using CSS to maintain aspect ratio and fit within the navbar layout:

```.logo {height: 4.4em; width: auto;}```

### Website Structure & Accessibility
The **Service & Sales Appliance Repair** website is built with semantic HTML for clear structure and accessibility. 

The website consists of 4 main pages and a section link:

- **Home (Landing Page):** Introduces the business, highlights key services, and features a strong call-to-action.
- **About Us (Section link):** Shares company background and commitment to customers.
- **Our Services (Service Listing Page):** Details the appliance repair services offered, with clear categories (e.g. fridge, washing machine, oven repairs).
- **Contact Us (Form):** Provides a contact form for easy customer enquiries. 
- **Submission Confirmation (Acknowledgement Page):** Confirms that the user's form submission was successful, thanks them, offers next steps, and a link back home.

Key features include:

- **Semantic tags:** `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` for logical page structure.
- **Navigation:** Simple, consistent, with clear link text for easy use with screen readers. 
- **Forms:** All inputs have linked `<labels>` elements, correct types (e.g. email), and logical tab order. 
- **Images:** Informative images have meaningful `alt` text.
- **Colour & Contrast:** Meets WCAG AA standards for readability.
- **Responsive text:** Use relative units (rem, em, & %) to support scaling and zoom.
- **Keyboard:** Visible focus states on links and buttons.

Accessibility is part of the design, not an add-on.

### Wireframes
The wireframes represent the core pages of the appliance repair website, designed to work across larger devices **>769px**, tablet **<768px**, and mobile **<478px** devices. They ensure quick access to booking, contact, and service information. 

<details>
<summary>Home Page</summary>
Features appliance categories, reviews, and contact info. Mobile devices are optimised for thumb-friendly navigation with quick access to contacts.

![Home Wireframes](assets/wireframes/home-page.png)
</details>

<details>
<summary>Our Services Page</summary>
Lists individual services (e.g. oven repairs) with descriptions and images, plus a "Contact Us" button. Mobile layout stacks service info for easy scrolling.

![Our Services Wireframes](assets/wireframes/our-services.png)
</details>

<details>
<summary>Contact Us Page</summary>
Simple form with name, email, and message fields, plus a clear "Send" button.

![Contact Us Wireframes](assets/wireframes/contact-us.png)
</details>

<details>
<summary>Action Page</summary>
Acknowledges the submission of the form, plus a clear "Return Home" button.

![Action Wireframes](assets/wireframes/action.png)
</details>

---

## Features

### Existing Features

<details>
<summary>Logo & Navigation</summary>

- Clear **Service & Sales logo** on every page.
- Consistent **navigation bar** with links to *Home*, *About Us*, *Our Services*, *Contact Us*.
- **Fully responsive** - transforms into a hamburger toggler on smaller screens.
- The **active page link is highlighted** so users can easily see where they are.
![Screenshot](assets/readme-references/screenshots/navbar-logo-feature.png)
</details>

<details>
<summary>Hero Image & Button</summary>

- Large, engaging **hero image** on the home page.
- Encourage quick action through prominent, accessible contact options.
![Screenshot](assets/readme-references/screenshots/hero-feature.png)
</details>

<details>
<summary>Appliances Section & Our Services Link</summary>

- Key appliance icons (e.g. oven, fridge, dishwasher, laundry) displayed on the home page.
- Directs users to the **Our Services** page for more details.
![Screenshot](assets/readme-references/screenshots/home-appliances-feature.png)
</details>

<details>
<summary>Carousel for Customer Reviews</summary>

- A **testimonial slider** displays customer feedback.
- Includes **carousel indicators** to allow users to easily navigate between reviews.
![Screenshot](assets/readme-references/screenshots/customer-reviews-feature.png)
</details>

<details>
<summary>About Us Section (Home Page)</summary>

- Introduces the team and company values to build trust.
![Screenshot](assets/readme-references/screenshots/about-us-feature.png)
</details>

<details>
<summary>Our Services & Why Choose Us</summary>

- Details repair services offered for different appliances.
![Screenshot](assets/readme-references/screenshots/our-services-feature.png)

- Includes a **Why Choose Us** section highlighting key benefits (e.g. local engineers, transparent pricing).
- Features a **Contact Us Now Button** for easy booking.
![Screenshot](assets/readme-references/screenshots/why-us-feature.png)
</details>

<details>
<summary>Contact Us Form</summary>

- Form captures name, email, phone number, appliance type, message, and preferred appointment date if required.
![Screenshot](assets/readme-references/screenshots/form-feature.png)
</details>

<details>
<summary>Thank You Page</summary>

- Confirms form submission with a friendly thank you message. 
- Includes a **Back to Home button**.
![Screenshot](assets/readme-references/screenshots/thank-you-feature.png)
</details>

<details>
<summary>Footer & Call to Action</summary>

- **Footer appears on all pages**, containing contact details, opening times, and a repeated **call-to-action button**.
![Screenshot](assets/readme-references/screenshots/footer-feature.png)
</details>

### Future Enhancements

Planned improvements have been tracked and prioritised using **GitHub Projects**, helping to manage progress and link user stories to development work.

<details>
<summary>GitHub Projects board managing tasks and priorities.</summary>

![GitHub Projects](assets/readme-references/screenshots/git-projects.png)
</details>

#### Integrate External Customer Review Link

##### User Story:
As a customer, I want to leave a review easily via a trusted platform (e.g. Trustpilot), so I can share my experience and help others decide.
<details>
<summary>Screenshot from GitHub Projects</summary>

![Screenshot](assets/readme-references/screenshots/review-task.png)
</details>

##### Enhancement:
Add a visible, accessible button or link on the home page and contact page that directs customers to a trusted external review site (such as Trustpilot or Google Reviews).

#### Show Pricing / Quote Process

##### User Story:
As a customer, I want to see clear pricing or understand how to request a quote, so I know what to expect before booking.

##### Enhancement:
Include a dedicated section or page explaining how quotes are provided, or list example pricing for common repairs.

#### Add Online Booking

##### User Story:
As a customer, I want to book a repair appointment online, so I can confirm a date and time without having to call.

##### Enhancement:
Build a basic booking form or integrate a simple calendar tool to accept appointments.

#### Educational Content Page

##### User Story:
As a customer, I want tips and advice about appliance care, so I can maintain my appliances and prevent breakdowns.

##### Enhancement:
Add a page with articles or FAQs about appliance care, common faults, and prevention tips.

---

## Technologies Used

### Languages
- HTML5
- CSS3

### Frameworks, Libraries & Programs Used
- [Bootstrap v5.3](https://getbootstrap.com/)
    - Used to ensure responsiveness and provide styling across the website.
- [Google Fonts](https://fonts.google.com/)
    - The 'Host Grotesk', 'Source Code Pro', and 'Inter' fonts were imported into the `style.css` file and used throughout the site.
- [Font Awesome](https://fontawesome.com/)
    - Included on all pages to provide icons that enhanced aesthetics and improve user experience.
- [jQuery](https://getbootstrap.com/docs/5.3/getting-started/download/)
    - Bundled with Bootstrap to make the navbar, carousel, and buttons responsive and enable smooth scroll functionality.
- [VS Code](https://code.visualstudio.com/)
    - Visual Studio Code was used as the main code editor for writing and managing the project's HTML, CSS, and other files.
- [Balsamiq Wireframes](https://balsamiq.com/?gad_source=1&gad_campaignid=203404003&gbraid=0AAAAAD3BuzO1_MfAH220pB2sjY8-SH4XY&gclid=Cj0KCQjwvajDBhCNARIsAEE29WqRr6MNJNBlZ2P9yCYgdpEVjwPQac8uQL0IlC2WZUqABjTq6pGe_eQaAismEALw_wcB)
    - Used to create wireframes during the design phase.
- [Git](https://git-scm.com/)
    - Used for version control, with commits made via Gitpod terminal.
- [GitHub](https://github.com/)
    - Hosted the projects code after being pushed from Git. GitHub Projects was used to manage tasks, track progress, and organise workflow during development.
- [Adobe Stock](https://stock.adobe.com/uk/)
    - Provided high-quality visuals and images used across the site.
- [Canva](https://www.canva.com/)
    - Used to design the company logo.
- [Coolors](https://coolors.co/)
    - Used for generating the colour palette and initially review colour contrast for accessibility.
- [Google Developer Tools](https://developer.chrome.com/docs/devtools)
    - Used to test and debug the site across different screen sizes, devices, and browsers to ensure responsiveness and performance.

---

## Testing

### HTML Validation

[W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) was used to validate the HTML of the website. One page failed with an error and another has one warning. All others passed with no errors, no warning to show.

<details>
<summary>Home</summary>

One warning due to a `<section>` lacking a heading. Although not a conventional approach, this section is being used as a secondary navigation mechanism to *Our Services*. 

![Screenshot](assets/readme-references/testing/home-html-val.png)
</details>

<details>
<summary>Our Services</summary>

![Screenshot](assets/readme-references/testing/services-html-val.png)
</details>

<details>
<summary>Contact Us - Error</summary>

One error, no warnings - Stray end tag, caused due to a typo. Removed duplicated `</main>` end tag.

![Screenshot](assets/readme-references/testing/contact-html-stray.png)
</details>

<details>
<summary>Contact Us - Pass</summary>

![Screenshot](assets/readme-references/testing/contact-html-val.png)
</details>

<details>
<summary>Action Page</summary>

![Screenshot](assets/readme-references/testing/action-html-val.png)
</details>

### CSS Validation

[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used to validate the CSS of the website. No errors found, 4 warnings caused by Google Fonts import CSS and CSS variables pointing to Google Fonts import CSS.

<details>
<summary>style.css</summary>

![Screenshot](assets/readme-references/testing/css-val.png)
</details>

<details>
<summary>CSS Warnings</summary>

Line 2: `@import url('https://fonts.googleapis.com/css2?family=Host+Grotesk:ital,wght@0,500;1,500&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Source+Code+Pro:ital,wght@0,200..900;1,200..900&display=swap');`

Line 28: `font-family: var(--body-font);`

Line 50: `font-family: var(--primary-font);`

Line 58: `font-family: var(--primary-font);`

![Screenshot](assets/readme-references/testing/css-warnings.png)
</details>

### Performance

[Google Lighthouse](https://developer.chrome.com/docs/lighthouse/overview) in Chrome DevTools was used as an automated tool to audit the web pages for performance, accessibility, SEO, and best practices. A tool to help improve web page quality overall. 

<details>
<summary>Home</summary>

##### Future Enhancements & Noted Bugs
- **Improve Image Delivery** - Optimise large images to reduce page load time.
- **Network Dependency Tree** - Minimise deep dependency on large third-party libraries

*Future updates will address these issues, with an ongoing focus on enhancing responsiveness and accessibility across all devices.*

![Screenshot](assets/readme-references/testing/lighthouse-home.png)
</details>

<details>
<summary>Our Services</summary>

##### Future Enhancements & Noted Bugs
- **Improve Image Delivery** - Optimise large images to reduce page load time.

*Future updates will address these issues, with an ongoing focus on enhancing responsiveness and accessibility across all devices.*

![Screenshot](assets/readme-references/testing/lighthouse-services.png)
</details>

<details>
<summary>Contact Us</summary>

![Screenshot](assets/readme-references/testing/lighthouse-contact.png)
</details>

<details>
<summary>Action Page</summary>

![Screenshot](assets/readme-references/testing/lighthouse-action.png)
</details>

#### Testing on Devices

The website was tested across multiple devices and tools to ensure responsiveness and usability:

- **iPhone 15 Pro (iOS17)** Tested in both portrait and landscape orientations.
- **Samsung Galaxy A52 (Android 14)** - Tested in both portrait and landscape orientations.
- **iPad Mini 6 (iPadOS17)** - Tested in portrait and landscape modes, with particular attention to form usability. 
- **MacBook Pro M3 14"** - Tested on macOS using multiple browsers (Chrome, Safari).
- **Google Chrome DevTools** - Toggler used to simulate various screen sizes and verify responsiveness at key breakpoints.

Responsiveness and layout consistency were a key focus during development. Navigation, form elements, and interactive components were reviewed across these devices. 

##### Future Enhancements & Noted Bugs

- **iPhone 15 Pro & Samsung Galaxy A52 (Landscape)**: When tilted to landscape mode, the hero image appears cut in half, and the hero text overlaps the appliance feature section.
- **iPad Mini 6 (Contact Form)**: The calendar inputs minimises when selected, reducing accessibility and ease of use.
- **All Devices (Customer Reviews)** The review carousel slides overlap slightly during slide transitions. 

Future updates will address these issues, with an ongoing focus on enhancing responsiveness and accessibility across all devices.

#### User Story Testing

##### Acceptance Criteria & User Story Testing

| **User Story** | **Action** | **Expectation** | **Outcome** |
|----------------|------------|----------------|-------------|
| As a potential customer, I want to quickly see what types of appliances you repair. | Open homepage or Our Services page. | Appliance types visible within first screen on desktop and mobile, no scrolling required. | Appliance types display correctly on tested devices, easily identifiable at a glance. |
| As a potential customer, I want to see positive reviews. | View reviews on homepage. | At least 3 reviews visible; reviews appear genuine. | Reviews visible |
| As a potential customer, I want to see photos of your work or team. | Open homepage or navigate via main menu | Professional image of team shown. | Image is visible, looks professional and friendly. |
| As a customer with urgent repair, I want to see contact details fast. | Open site footer and homepage. | Phone number and contact options visible without scrolling. | Contact details accessible, clickable on all devices. |
| As a returning customer, I want easy access to contact or booking. | Navigate via main menu. | Booking/contact links visible; access within 3 clicks/taps. | Booking/contact form reached within 3 clicks/taps. |
| As a mobile user, I want site to work well on phone. | Open site on phone. | Site loads quickly; buttons are finger-friendly. | Content readable, no zooming needed; buttons easy to tap. |
| As a busy homeowner, I want to see opening hours, service area, services at a glance. | Open site footer and navigate to homepage. | Hours, service area, appliance types listed. | Info is clearly visible on homepage without extra clicks. |

##### Example Testing Summary

- All actions were tested on: **iPhone 15 Pro**, **Samsung Galaxy A52**, **iPad Mini 6**, **MacBook Pro M3 14"**, and **Chrome DevTools (responsive toggler)**.
- Most acceptance criteria met **except** noted bugs and *could-have* user stories in GitHub Projects:

##### Noted Bugs
  - Hero image/text overlap on iPhone 15 Pro / Samsung Galaxy A52 in landscape.
  - Contact form calendar issue on iPad Mini 6.
  - Customer reviews overlapping during slide transitions on all devices.

##### *could-have* User Stories

  - As a potential customer, I want to see clear pricing or how to get a quote.
  - As a potential customer, I want to book a repair visit online.
  - As a local resident, I want to see comments/reviews about faults and fixes.

#### Bugs & Fixes

| **Bugs** | **Fix** |
| --- | --- |
| Home page link stays highlighted when visiting another page | Change `active` attribute to the correct page dynamically |
| The user can submit a contact form input without a message | Add `required` attribute to message input field |
| When viewed on all devices, the contact page has whitespace after the footer | Set `min-height` for html, body `100vh` |
| Hero font size not responsive on different devices | Used `clamp()` to set scalable font-size for hero text |
| Elements not aligned as expected | Check for missing or incorrect `display (e.g. flex, block)`, or add `margin/ padding` |
| Unresponsive layout on larger devices (designed for mobile first) | Use CSS media queries to adjust styles at different breakpoints - avoiding fixed units |
| Text too small or too large on different devices | Used relative units (em, rem) where possible, instead of fixed px sizes |

##### Example Fix Code Snippets

##### Hero font size & responsiveness text

```
.hero-content {
    font-size: clamp(2rem, 8.2vw, 9rem);
}
```
##### Example media query for larger devices

```
@media screen and (min-width: 1024px) {
.hero {
    background-position: center 23%;
}
```

##### Align elements with flex

```
#appliance-grid {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    text-align: center;
    padding-top: 1.7rem;
}
```

---

## Deployment 

The website was deployed using **GitHub Pages**.

### Steps to deploy:

1. Go to your repository on **GitHub**.
2. Click the **Settings** tab.
3. In the sidebar, select **Pages**.
4. Under **Source**, choose:
    - `Deploy from a branch`
    - Select the branch `main`
    - Select the folder `/root`
5. Click **Save**.

##### View Your Live Site:

1. GitHub will generate a URL for your site (e.g. `https://lukem1aa.github.io/milestone-project-one/index.html`).
2. You'll see it displayed in the **Pages** section after a few moments.
3. Visit the link to view your deployed site!

### Fork the Repository

1. Go to the original GitHub repository page in your browser.
2. In the top-right corner, click the **Fork** button.
3. Choose your GitHub account to fork it into your own repository list.

### Clone the Repository

1. Go to the original GitHub repository page in your browser.
2. Click the green **Code** button - near the top right.
3. Under **Clone**, choose **HTTPS**.
4. Click the copy icon to copy the URL.

##### Open your terminal
5. Open **Command Prompt**, **GIT Bash**, or **Terminal**.
6. Run the clone command, type `$git Clone + Copied URL`.
7. Navigate into your project folder.

---

## Credits

### Content
- All content was written by the developer with contribution from Lucy Elliott - my partner who works in the industry. 

### Media
- [Coolors](https://coolors.co) - Color scheme generator for styling
- [Google Fonts](https://fonts.google.com/) - For typography imports
- [Font Awesome](https://fontawesome.com/) - Icons such as star, phone, envelope, and location are sourced via Font Awesome
- [Canva](https://www.canva.com/) - Used to design [company logo](assets/images/logo.svg) and generate SVG file for navigation bar
- Free Icons - Credit to [Hilmy Abiyyu Asad](https://freeicons.io/profile/75801) - Washing Machine [Favicon](assets/favicon/washing-machine.png)
- Adobe Stock - Credit to [Weerapat](https://stock.adobe.com/uk/contributor/212123501/weerapat?load_type=author&prev_url=detail) - Home - Hero [Image](assets/images/hero-image.jpeg)
- Adobe Stock - Credit to [Paworn](https://stock.adobe.com/uk/contributor/211875172/paworn?load_type=author&prev_url=detail) - Appliances - Oven [Image](assets/images/oven.png)
- Adobe Stock - Credit to [Matcha-09](https://stock.adobe.com/uk/contributor/211891082/matcha-09?load_type=author&prev_url=detail) - Appliances - Fridge [Image](assets/images/fridge.png)
- Adobe Stock - Credit to [Alloca Design Studio](https://stock.adobe.com/uk/contributor/212020487/alloca-design-studio?load_type=author&prev_url=detail) - Appliances - Dishwasher [Image](assets/images/dish.png)
- Adobe Stock - Credit to [Jayk](https://stock.adobe.com/uk/contributor/211938241/jayk?load_type=author&prev_url=detail) - Appliances - Washing Machine [Image](assets/images/washing.png)
- Adobe Stock - Credit to [Asier](https://stock.adobe.com/uk/contributor/208410632/asier?load_type=author&prev_url=detail) - Happy Customer "Sarah" [Image](assets/images/review1.png)
- Adobe Stock - Credit to [Asier](https://stock.adobe.com/uk/contributor/208410632/asier?load_type=author&prev_url=detail) - Happy Customer "Amanda" [Image](assets/images/review2.png)
- Adobe Stock - Credit to [Damir Khabirov](https://stock.adobe.com/uk/contributor/206682305/damir-khabirov?load_type=author&prev_url=detail) - Happy Customer "Tom" [Image](assets/images/review3.png)
- Adobe Stock - Credit to [Krakenimages.com](https://stock.adobe.com/uk/contributor/200860971/krakenimages-com?load_type=author&prev_url=detail) - Happy Customer "Emma" [Image](assets/images/review4.png)
- Adobe Stock - Credit to [Studio Romantic](https://stock.adobe.com/uk/contributor/206200351/studio-romantic?load_type=author&prev_url=detail) - Team [Image](assets/images/team-img2.jpeg)
- Adobe Stock - Credit to [Pixel-Shot](https://stock.adobe.com/uk/contributor/207588960/pixel-shot?load_type=author&prev_url=detail) - Engineer Working [Image](assets/images/our-services-img.jpeg\)

### Code
- [Google Fonts](https://fonts.google.com/) - Embedded CSS & JS code for typography
- [Font Awesome](https://fontawesome.com/) - Embedded CSS for icons
- CSS code credited to Greg Ord-Hume for article [CSS: Do not put height 100% on html, body in 2020](https://greggod.medium.com/css-do-not-put-height-100-on-the-body-html-e36bda3551b3)
```
html,
body {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
} 
```
- CSS code credited to Greg Ord-Hum for article [CSS: How to fix the footer to the bottom of the page in 2020](https://greggod.medium.com/keep-that-damn-footer-at-the-bottom-959796fe3d08)
```
body main {
    flex: 1 auto; /* Flex: 1 auto; 
}
```
- CSS code credited to Bashid for contribution to question on [StackOverflow](https://stackoverflow.com/questions/70819649/how-can-i-change-bootstrap-5-carousel-indicators-into-dots/71997944) "How can I change Bootstrap 5 carousel indicators into dots"
```
.carousel .carousel-indicators button { 
    width: 1em;
    height: 1em;
    border-radius: 100%;
    margin: 0 0.5em;
    background-color: var(--accent-color);
}
```
- Navigation CSS style code taken from [Bootstrap v5.3](https://getbootstrap.com/docs/5.3/components/navbar/)
- Carousel CSS style code used for customer review taken from [Bootstrap v5.3](https://getbootstrap.com/docs/5.3/components/carousel/)
- Buttons CSS style code taken from [Bootstap v5.3](https://getbootstrap.com/docs/5.3/components/buttons/)
- Tables CSS style code taken from [Bootstap v5.3](https://getbootstrap.com/docs/5.3/content/tables/)


### Acknowledgement
- [Code Institute](https://codeinstitute.net/global/) - Learning Platform
- [WCAG 2.1](https://www.w3.org/TR/WCAG21) and [Coolors Color Contrast Checker](https://coolors.co/contrast-checker) - Accessibility contrast checker to support and maintain readability
- [WCAG 2..2 Techniques](https://www.w3.org/WAI/WCAG22/Techniques/css/C22) and [WebAim - Typefaces and Fonts](https://webaim.org/techniques/fonts/) - Accessibility typeface and fonts support and maintain readability
- [Syntax](https://syntax.fm/) Podcast and YouTube channel for CSS and industry inspiration
- [Kevin Powell](https://www.youtube.com/kevinpowell) YouTube channel for CSS best practise
- [W3Schools](https://www.w3schools.com/css/css_form.asp) with support targeting input fields with CSS

##### I would also like to acknowledge and thank
- I would like to thank my partner Lucy Elliott for her continued support, industry advice, help with testing on devices, and the days and nights working on the project while she entertained the children
- Services and Sales Appliance Repairs for giving me the opportunity to rebrand and design a new [website](https://www.serviceandsalesbedford.co.uk/)