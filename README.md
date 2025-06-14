
📝 Group Task Instructions: Build a Three-Page Website for Delizz
Client: Delizz
Due Date: Monday
Pages:
1️⃣ Home (index.html)
2️⃣ About (about.html)
3️⃣ Contact (contact.html)
CSS: Only one CSS file (styles.css).

🎯 Project Overview
Delizz has asked our team to build a simple, clean website with the following:

✅ A Home page that welcomes visitors.
✅ An About page that shares information about Delizz.
✅ A Contact page with Delizz’s contact details.
✅ A consistent navigation bar linking all three pages.
✅ Styling should be in one CSS file for all pages.

🚀 Team Member Requirements
✅ Each team member must make at least one commit in the project repository.
✅ Ensure your commit is meaningful (e.g., adding a section, fixing a link, styling improvement).
✅ Clearly document your commits with descriptive messages.

Example commit message:

vbnet
Copy
Edit
feat: added contact page structure and content
🗂 Project Structure
arduino
Copy
Edit
/project-root
  ├── index.html
  ├── about.html
  ├── contact.html
  ├── styles.css
  └── README.md  (optional)
⚙️ Development Steps
1️⃣ Create the project directory and initialize Git:

bash
Copy
Edit
mkdir delizz-website
cd delizz-website
git init
2️⃣ Assign tasks to team members:

Page creation: Divide pages (e.g., one person takes Home, another About, another Contact).

CSS styling: One member can set up the initial styles.css with basic styles.

Navigation: Ensure the navigation bar is present on every page.

3️⃣ Create HTML files:

Use semantic HTML (<nav>, <main>, <footer> if needed).

Example structure:

html
Copy
Edit
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <nav>...</nav>
  <main>...</main>
</body>
</html>
4️⃣ Set up the CSS file (styles.css) and link it to all HTML files.

5️⃣ Test navigation links to ensure they work correctly across pages.

⚠️ Important Guidelines
✅ Use relative paths for linking pages (href="about.html").
✅ Keep consistent naming and file structure.
✅ Make sure the CSS file is linked properly in all pages.
✅ Avoid duplicate CSS files — only use styles.css for all pages.

🔄 Collaboration
Use Git for version control.

Push your commits to the main branch (or a shared branch if preferred).

Pull and merge changes from other team members before making new commits to avoid conflicts:

bash
Copy
Edit
git pull origin main
📅 Submission
✅ Submit the complete project directory (index.html, about.html, contact.html, styles.css) by Monday.
✅ If needed, zip the folder and share via email or upload to the designated platform.

💡 Tips for Smooth Collaboration
✅ Communicate on your progress and avoid duplicate work.
✅ Review your code before pushing — ensure no broken links or missing CSS.
✅ Test the final site in the browser to confirm everything works.
