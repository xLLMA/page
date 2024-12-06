```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#121212">
  <title>My GitHub Blog</title>
  <style>
    /* Base Styles */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      background-color: #121212;
      color: #f1f1f1;
      line-height: 1.6;
    }

    a {
      color: #42a5f5;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    h1, h2, h3 {
      font-weight: bold;
      margin: 1.5rem 0 1rem;
    }

    p {
      margin: 0.5rem 0;
    }

    /* Container */
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }

    /* Header */
    .header {
      text-align: center;
      padding: 2rem 1rem;
      background-color: #1e1e1e;
      border-radius: 15px;
      margin-bottom: 2rem;
    }

    .header h1 {
      margin: 0;
      color: #f9f9f9;
    }

    .header p {
      color: #b3b3b3;
      font-size: 1.2rem;
    }

    /* Blog Post Cards */
    .blog-post {
      background-color: #1e1e1e;
      margin: 1rem 0;
      padding: 1.5rem;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .blog-post:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.5);
    }

    .blog-post h2 {
      color: #e0e0e0;
      margin: 0 0 0.5rem;
    }

    .blog-post p {
      color: #b3b3b3;
      font-size: 0.9rem;
    }

    .blog-post a {
      display: inline-block;
      margin-top: 1rem;
      font-size: 0.9rem;
      background-color: #42a5f5;
      color: #fff;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      transition: background-color 0.2s;
    }

    .blog-post a:hover {
      background-color: #1e88e5;
    }

    /* Footer */
    .footer {
      text-align: center;
      margin-top: 2rem;
      padding: 1rem 0;
      font-size: 0.9rem;
      color: #b3b3b3;
    }

    .footer a {
      color: #42a5f5;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <div class="header">
      <h1>My GitHub Blog</h1>
      <p>Welcome to my personal blog hosted on GitHub.</p>
    </div>

    <!-- Blog Posts -->
    <div class="blog-post">
      <h2>Post Title 1</h2>
      <p>Posted on: December 6, 2024</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla accumsan urna sit amet elit commodo...</p>
      <a href="#">Read More</a>
    </div>

    <div class="blog-post">
      <h2>Post Title 2</h2>
      <p>Posted on: December 5, 2024</p>
      <p>Curabitur vel sem id orci feugiat placerat at at lacus. Vestibulum ante ipsum primis in faucibus...</p>
      <a href="#">Read More</a>
    </div>

    <!-- Footer -->
    <div class="footer">
      <p>Made with ❤️ by <a href="https://github.com/your-username">Your GitHub</a></p>
    </div>
  </div>
</body>
</html>

```
