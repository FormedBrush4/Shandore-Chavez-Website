PORTFOLIO SETUP

Included pages: index.html (main page), five separate project pages, and get-to-know-me.html. Shared styles and mobile navigation are in style.css and script.js.

BEFORE PUBLISHING
1. Replace https://www.linkedin.com/in/your-profile/ with your real LinkedIn profile URL in every HTML page.
2. Put your resume PDF at assets/resume.pdf.
3. Media panels are placeholders; replace them with your photos/videos.

ADD A PHOTO
On a project page, replace a <div class="media-placeholder">...</div> with: <img src="assets/projects/recovery-cad.jpg" alt="CAD model of the rocket recovery system">. Keep the image in the assets/projects folder and update the filename. On the personal page use assets/about/your-photo.jpg.

ADD A VIDEO
Replace a placeholder div with: <video controls preload="metadata"><source src="assets/projects/recovery-test.mp4" type="video/mp4">Your browser does not support video.</video>

EDIT CAPTIONS
Edit the text inside each <figcaption>. For example, change <strong>Caption title 1</strong> to a meaningful title and the following text to a short explanation of what you were doing, the tool/process used, and the result. Duplicate a <figure> block to add more items.

RUN LOCALLY
Keep all HTML files, style.css, script.js, and assets together. In VS Code, open index.html using Live Server at an HTTP address such as http://127.0.0.1:5500/index.html (not https).
