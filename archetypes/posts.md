---
title: '{{ .Name }}'
date: '{{ .Date }}'
slug: '{{ .Name }}'
# Path to your thumbnail image (relative to static/ folder)
# Example: images/my-post/thumbnail.jpg
image: "images/FOLDER/IMAGE.jpg"
categories: ["General"]
author: "Joe Wong"
draft: true
---

> Add a catchy quote or summary here. This will appear at the top of your post.

<!--more-->

### Introduction
Start writing your main content here. Everything before the `<!--more-->` tag above will appear on the home page card.

```ruby
# You can add code blocks like this
puts "Hello I Wonder!"
```

<br>
<!--Keywords-->
<hr>
### Keywords
- **Term**: Description of the term.
- **Another Term**: Description of another term.

<br>
<!--Images-->
<hr>
### Images
<div class="row">
  <div class="column">
    <img src="{{ "images/FOLDER/IMAGE1.jpg" | absURL }}" alt="Description">
  </div>
  <div class="column">
    <img src="{{ "images/FOLDER/IMAGE2.jpg" | absURL }}" alt="Description">
  </div>
</div>

<br>
<!--References-->
<hr>
### References
1. [Link Title](https://example.com)
2. [Another Link](https://example.com)
