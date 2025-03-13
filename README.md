# Flask Blog

This is a simple blog application built with Flask. It allows users to create, view, and manage blog posts.

## Project Structure

```
flask-blog
├── app.py                # Entry point of the application
├── static                # Contains static files
│   ├── css
│   │   └── style.css     # CSS styles for the blog
│   └── js
│       └── main.js       # JavaScript for client-side functionality
├── templates             # Contains HTML templates
│   ├── base.html         # Base template for the blog
│   ├── index.html        # Homepage displaying a list of blog posts
│   ├── post.html         # Template for displaying a single blog post
│   └── create.html       # Template for creating a new blog post
├── models.py             # Defines data models for the blog
├── requirements.txt      # Lists project dependencies
└── README.md             # Documentation for the project
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd flask-blog
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   python app.py
   ```

4. Open your web browser and go to `http://127.0.0.1:5000` to view the blog.

## Usage

- Navigate to the homepage to view all blog posts.
- Click on a post to view its details.
- Use the create post page to add new blog posts.

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.