# BKC
Sure! Here's a simple HTML code for a personal blog page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .post {
            background: #fff;
            margin: 20px 0;
            padding: 20px;
            border: 1px solid #ddd;
        }
        .post h2 {
            color: #333;
        }
        .post p {
            color: #666;
            line-height: 1.6;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to My Blog</h1>
        </div>
    </header>

    <div class="container">
        <div class="post">
            <h2>Post Title 1</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nec eros eget nisl fringilla commodo. Morbi tortor risus, vulputate vitae porttitor nec, rhoncus ac nulla. Nullam imperdiet vestibulum urna, at feugiat mauris vestibulum a.</p>
        </div>
        <div class="post">
            <h2>Post Title 2</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nec eros eget nisl fringilla commodo. Morbi tortor risus, vulputate vitae porttitor nec, rhoncus ac nulla. Nullam imperdiet vestibulum urna, at feugiat mauris vestibulum a.</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 My Personal Blog</p>
    </footer>
</body>
</html>
```

This code creates a simple personal blog page with a header, two blog posts, and a footer. The CSS styles are included in the `<style>` tags within the `<head>` section to keep it all in one file for simplicity.
