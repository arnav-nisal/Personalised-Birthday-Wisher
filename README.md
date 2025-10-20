# Personalized Birthday Wisher (Web Archive)

This repository contains the source code for a small, personal website I built (circa 2020-2021). The project's simple, fun goal was to wish friends and family a happy birthday with a unique and personal touch, moving beyond just a static "Happy Birthday" text or image.

## Repository Status

**Please Note:** This is a public archive and is **not actively maintained**. The code is preserved here for historical and personal reference and **does not reflect my current skill level.**

This was an early web development project. The code is provided as-is, and any dependencies (if any) are likely outdated.

---

## Project Concept: The "Personal Touch"

The core idea was to create a reusable birthday webpage that could be customized for each person.

### How It Works

Instead of creating a separate page for everyone, the site was designed to dynamically pull information (like the recipient's name) and display it on the page.

1.  **Custom Link:** The sender (myself) would craft a special URL for the birthday person (e.g., `.../birthday.html?name=Alex`).
2.  **Dynamic Content:** The JavaScript on the page would read the `name` (or other details) from the URL's query parameters.
3.  **Personalized Greeting:** The script would then inject this name directly into the page's HTML, so the visitor would be greeted with a message like "Happy Birthday, Alex!" alongside any animations or special messages.

This allowed a single webpage to provide a custom-feeling experience for many different people.

### Technologies Used

This project is a simple, front-end-only site built with:

* **HTML5:** For the page structure.
* **CSS3:** For styling and visual elements (e.g., animations, colors, layout).
* **JavaScript (ES6+):** For the core logic of reading URL parameters and dynamically updating the page content.
