---
layout: post
title: 祝Harry Potter生日快乐
date: 2023-07-31 16:07:31
author: Failure
header-img: img/23.7.31 哈利.jpg
catalog: true
tags:
---
#祝Harry Potter生日快乐

7月31日是“大难不死的男孩”哈利·波特的生日，这个特别的日子是一切的开始。在此，由衷地祝愿我们的英雄，生日快乐！
 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>评论</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .comment-form {
            margin-bottom: 20px;
        }
        .comment {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 10px;
        }
        .comment-author {
            font-weight: bold;
        }
        .comment-content {
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <h1>Simple Comment System</h1>
    <div class="comment-form">
        <label for="nickname">Nickname:</label>
        <input type="text" id="nickname" required>
        <br>
        <label for="email">Email:</label>
        <input type="email" id="email" required>
        <br>
        <button onclick="submitComment()">Submit Comment</button>
    </div>
    <div id="comments"></div>

    <script>
        function submitComment() {
            const nickname = document.getElementById('nickname').value;
            const email = document.getElementById('email').value;
            const commentText = prompt('Please enter your comment:');
            if (commentText) {
                const comment = document.createElement('div');
                comment.className = 'comment';
                comment.innerHTML = `<strong class="comment-author">${nickname} (${email}):</strong> ${commentText}`;
                document.getElementById('comments').appendChild(comment);
            } else {
                alert('Please enter a comment.');
            }
        }
    </script>
\```
</body>
</html>

