# Mwaka Nawila Foundation Website

This is the official website for the Mwaka Nawila Foundation, a Zambian-based NGO dedicated to empowering youth and transforming communities through health, education, and social protection initiatives.

## Features

- **Responsive Design:** Built with Tailwind CSS for a seamless experience across mobile, tablet, and desktop.
- **Modern UI:** Features a clean, professional aesthetic with interactive elements.
- **Impact Focused:** Dedicated sections for programs, impact stories, and community engagement.

## Local Development

Since this is a static website, you can run it locally by simply opening the `index.html` file in your browser.

Alternatively, you can use a local development server for a better experience (e.g., Live Server in VS Code, or `npx serve .`).

## Deployment

This website is configured for hosting on [Vercel](https://vercel.com).

### Deployment Steps:

1.  **Connect to GitHub:** Push this repository to your GitHub account.
2.  **Import to Vercel:** Go to the Vercel dashboard and import the project.
3.  **Automatic Configuration:** Vercel will automatically detect the static files. The `vercel.json` file is already configured with `cleanUrls` enabled, allowing pages to be accessed without the `.html` extension (e.g., `/about_us` instead of `/about_us.html`).

## Project Structure

- `index.html`: The landing page.
- `about_us.html`: Information about the foundation.
- `our_programs.html`: Details of the various initiatives.
- `donate.html`: Secure donation portal.
- `contact_us.html`: Contact information and form.
- `gallery.html`: Visual documentation of our impact.
- `vercel.json`: Configuration for Vercel deployment.
- `.gitignore`: Files to be excluded from version control.

## License

© 2024 Mwaka Nawila Foundation. All rights reserved.
