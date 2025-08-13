<general_rules>
- This is a Canva-generated static website that requires careful handling of auto-generated code. Avoid modifying the core HTML structure, inline CSS, or JavaScript functionality unless absolutely necessary.
- All static assets (fonts, images, JavaScript files) use hash-based file naming for cache busting (e.g., `01c7ccc81a1289dedbdae34afe3477f60b4bd37c9b8a15eec37e59453e6d6fd3.js`). When adding new assets, follow this naming convention to ensure proper cache invalidation.
- Before making any changes to `index.html`, create a backup copy as this file contains all the website's structure, styling, and content in a single file.
- When adding new images, place them in the `images/` directory and use hash-based naming. Update references in `index.html` accordingly.
- Font files should be placed in the `fonts/` directory and follow the existing hash-based naming pattern. Update `@font-face` declarations in the inline CSS within `index.html`.
- JavaScript modifications should be minimal and tested thoroughly, as the existing scripts handle critical functionality like responsive design and image loading.
- Always validate that the `CNAME` file contains the correct domain (`superdelsol.com.ar`) and avoid modifying it unless changing the deployment domain.
- Update `sitemap.xml` when adding new pages or changing the site structure to maintain SEO optimization.
</general_rules>

<repository_structure>
- **Root Level**: Contains the main website file (`index.html`), domain configuration (`CNAME`), and SEO configuration (`sitemap.xml`)
- **`index.html`**: Single-page website containing all HTML structure, inline CSS styles, and embedded content. This is the primary file that browsers load.
- **`fonts/` directory**: Contains web font files in WOFF2 format with hash-based names for cache busting. These fonts are referenced in the inline CSS within `index.html`.
- **`images/` directory**: Static image assets including logos, product images, and graphics. All files use hash-based naming for optimal caching.
- **`js/` directory**: Contains two minified JavaScript files that handle responsive design, image loading, and interactive functionality. Files use hash-based naming.
- **`CNAME`**: GitHub Pages configuration file specifying the custom domain (`superdelsol.com.ar`) for deployment.
- **`sitemap.xml`**: SEO sitemap file listing the website's URLs for search engine indexing.
- **`.git/`**: Standard Git repository metadata (not for direct modification).

This repository represents a complete, deployment-ready static website with no build process or compilation steps required.
</repository_structure>

<dependencies_and_installation>
This is a static website with no package management system or build tools. No dependencies need to be installed.

The website is ready for deployment as-is and can be:
- Served directly from any web server by pointing to the root directory
- Deployed to GitHub Pages (configured via the `CNAME` file)
- Hosted on any static hosting service (Netlify, Vercel, etc.)

No installation steps, package managers (npm, yarn, etc.), or build processes are required. All assets are pre-compiled and optimized for production use.
</dependencies_and_installation>

<testing_instructions>
No testing framework is configured for this repository. Testing should be performed manually:

**Local Testing:**
- Open `index.html` directly in a web browser to test the website locally
- Test responsive design by resizing the browser window or using browser developer tools
- Verify all images load correctly and fonts render properly
- Test any interactive elements or forms if present

**Cross-Browser Testing:**
- Test in multiple browsers (Chrome, Firefox, Safari, Edge) to ensure compatibility
- Verify the website displays correctly on different screen sizes and devices

**Deployment Testing:**
- After deploying changes, verify the live site at `https://superdelsol.com.ar`
- Check that the custom domain resolves correctly
- Validate that all assets load properly from the production environment

Since this is a Canva-generated website, focus testing on visual consistency and ensuring no functionality is broken after any modifications.
</testing_instructions>

<pull_request_formatting>
</pull_request_formatting>
