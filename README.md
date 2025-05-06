# Personal Portfolio Website

This is a personal portfolio website for Ryan Chung, showcasing educational background, technical skills, projects, and blog posts.

## Project Structure

### HTML Files
- `index.html`: The homepage/landing page
- `about.html`: About me section
- `timeline.html`: Timeline of education and career
- `technical_skills.html`: Technical skills and tools page
- `projects.html`: Portfolio projects showcase
- `blog.html`: Blog posts listing

### CSS Organization
The project uses a modular CSS approach where:

1. `common.css`: Contains common styles used across all pages, such as:
   - Base typography
   - Navigation buttons
   - Common header styles
   - Media queries that apply globally

2. Page-specific CSS files follow a one-to-one relationship with HTML files:
   - `index.css`: Styles specific to the homepage
   - `about.css`: Styles specific to the about page
   - `timeline.css`: Styles specific to the timeline page
   - `blog-styles.css`: Styles specific to the blog listing page
   - `projects.css`: Styles specific to the projects page
   - `technical_skills.css`: Styles specific to the skills page

This organization helps with:
- Better maintainability, as changes to one page don't affect others
- Improved performance, as browsers only need to load the CSS relevant to the current page
- Easier organization for future development

### Media
- `profile_image.png`: Profile picture

## Development

To add a new page:
1. Create a new HTML file
2. Create a corresponding CSS file
3. Include both `common.css` and your page-specific CSS in the HTML file
4. Add a navigation link to the new page in the other HTML files

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For any inquiries, please reach out through the social media links provided on the website.