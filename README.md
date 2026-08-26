### Part 1: Set Up the Repository[](https://ps-lms.vercel.app/curriculum/se/302/lab-1#part-1-set-up-the-repository)

Your team has set up a shared GitHub repository for the project, but you need to start working on it locally.

1. **Create a New Local Repository**:
    
    - Navigate to your working directory and create a new Git repository:
        
        `$ mkdir website-project$ cd website-project$ git init`
        
2. **Create a Simple HTML File**:
    
    - Your project manager has provided you with the basic structure of the homepage. Create an `index.html` file with this basic HTML structure:
        
```html
    <html>  
        <head>    
            <title>Website</title>  
        </head>  
        <body>    
            <h1>Welcome to Our Website</h1>  
        </body>
    </html>
```
        
3. **Commit the Initial Version**:
    
    - Stage and commit the file as your first contribution to the project:
        
        `$ git add index.html$ git commit -m "Initial commit with basic HTML structure"`


---
### Part 2: Create Branches

> Create a new branch for each feature and merge them into the main branch one by one. Ensure that you resolve any conflicts that arise.

- [X] feature/navigation-bar
- [X] feature/footer
- [X] feature/hero-section
- [X] feature/contact-form
- [X] feature/testimonials
