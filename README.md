Task Title: Build a Blog Editor Page with Backend & Auto-Save Draft Feature
🎯 Objective:
Design and develop a full-stack application that allows users to write, edit, save, and publish
blogs with an auto-save draft feature.
This task will help us evaluate your skills in frontend development, backend API design,
database integration, and system thinking.

💻 Requirements:
Frontend:
• Use React.js, Next.js, Angular, or Vue.js (Your Choice).
• Create a Blog Editor Page:
o Title field (text input)
o Content field (rich text editor or textarea)
o Tags field (optional, comma-separated)
• Functionality:
o Save as Draft button
o Publish button
o Auto-Save Draft (every 30 seconds or when user stops typing for 5 seconds)
o Display list of All Blogs (published & drafts separately)
o Edit and update existing drafts/posts
Backend:
• Use Node.js with Express.js, Django, Flask, or any other framework of your choice.
• Database: MongoDB, PostgreSQL, or any SQL/NoSQL database.
• Define a Blog schema/model with fields:
o id
o title
o content
o tags
o status (draft or published)
o created_at
o updated_at

📡 Sample API Specifications:
Method Endpoint Description
POST /api/blogs/save-draft Save or update a draft
POST /api/blogs/publish Save and publish an article
GET /api/blogs Retrieve all blogs
GET /api/blogs/:id Retrieve a blog by ID
🎁additionally :
• Auto-save after 5 seconds of inactivity using debouncing.
• Notify the user visually when the article is auto-saved (toast, message).
• Use JWT token or session-based authentication (bonus for protected APIs).
