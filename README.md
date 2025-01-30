# 📖 483 Anthology  

Welcome to **483 Anthology**, a digital archive showcasing literary analysis projects created by students using [AVAnnotate](https://avannotate.github.io/camille/). This static site, hosted on GitHub Pages, serves as a space to explore, connect, and share these works in an interactive and accessible format.  

---

## 🚀 About the Project  

**483 Anthology** is a collection of 22 student projects analyzing literary materials in audio format. Each project has been developed within **AVAnnotate**, a tool that enables timestamped annotations and personalized categorizations.  

Through this site, visitors can:  
✔ Explore individual projects.  
✔ Access detailed analyses and annotations.  
✔ Discover thematic connections through shared tags and categories.  

Each project is displayed as an **interactive card** linking directly to its AVAnnotate workspace.  

---

## 🔎 Navigation  

Projects are organized in a visual gallery, where each card represents an individual analysis.  
- Click on any card to access the full project on AVAnnotate.  
- Use tags and categories to find specific themes across the anthology.  
- Browse freely and immerse yourself in the students’ interpretations.  

---

## 🎨 Design  

The site follows a minimalist aesthetic, focusing on:  
✔ **Typography differentiation** to highlight key functions.  
✔ **Strategic white space** to enhance readability.  
✔ **Subtle animations** to improve interaction without overwhelming the page.  

For the best experience, we recommend using a modern web browser.  

---

## 🙌 Acknowledgments  

This project is the result of the dedication and effort of each student who contributed to these analyses. We would also like to thank **Mike, Sam and Tanya** for their guidance and support in creating this anthology.  

Thank you for contributing to this digital archive and making this collection of voices and perspectives possible.  

---

## 🔧 How to Add New Projects (For Administrators Only)  

**📌 NOTE:** This section is for repository administrators only and is not visible on the website.  

### 1️⃣ Adding a New Project  
To add a new project to the anthology:  
1. Edit the `index.html` file in the repository.  
2. Locate the section where the project cards are listed.  
3. Add a new entry following this format:  

```html
<div class="project-card">
  <h3>Project Name</h3>
  <p>Brief description of the analysis.</p>
  <a href="URL_TO_THE_PROJECT_ON_AVANNOTATE" target="_blank">Explore Project</a>
</div>
