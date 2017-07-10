---
layout: page
title : About
permalink: /about/
---

<h2>A Little About Me</h2>
<p>I am a junior at the University of North Carolina at Chapel Hill! I am pursuing a Computer Science B.A and a Cognitive Science minor. 
My Myers-Briggs personality type is INFP. I often overthink things and get anxious about silly stuff. I am kind of shy at first but 
I am an outspoken and loyal friend once I have become comfortable! I love food, art, and music and it shows in everything that I do. I'll get 
into the details of what I like and dislike next!
</p>
<br>
<h3>Music I Like</h3>>
<p>I have a pretty eclectic taste in music. I listen to a lot of different styles and genres, anywhere from electronic-trap to jazz and symphonic. 
I have been particularly interested in k-pop, as I recently learned more about the culture and language. Some artists that I quite like are Norah Jones, 
Blackbear, BTS, Chance the Rapper, Kendrick Lamar, Nat King Cole, and Khalid. 
</p>
<br>
<p>
Here are some links to soundcloud and spotify for the music I generally listen to:
</p>



```
  - Create a .markdown file inside <code class="highlighter-rouge">_posts</code> folder.<br>
  - Name the file according to the format YY-MM-DD-[short name for your post].<br>  <code>2016-03-30-i-love-design.markdown</code><br>
  - Write the <a href="jekyll">Front Matter</a> and content in the file.<br>
  <div class="example">
    <span class='manual'>FORMAT</span><BR>
    <pre>---
```

layout: post | default | page
title:  String<span class="hint"> Post Title</span>
date:   Time Stamp
categories: String | Array of Strings<span class="hint"> Category / Categories </span>
\---</pre>

```
  </div>
  <div class="example">

    <pre>---
```

layout: post
title:  "The One with the Blackout"
date:   2016-03-30 19:45:31 +0530
categories: ["life", "friends"]
\---</pre>

```
  </div>
```

  </div>
</p>
</div>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Create Pages</strong>
  </div>
<p>  <div class="manual-content">

```
  - Create a .md file in the root directory.<br>
  - Name the file with the desired page link name.<br>  <code>about.md</code><br><code>design.md</code><br>
  - Write the <a href="jekyll">Front Matter</a> and content in the file.
  <div class="example">
    <span class='manual'>FORMAT</span><BR>
    <pre>---
```

layout: page
title: String <span class="hint">Title of the webpage</span>
permalink: / String / <span class="hint">Permalink for the webpage</span>
tagline: String <span class="hint">Optional Gravity Feature : Tagline for the page</span>
\---</pre>

```
  </div>
  <div class="example">

    <pre>---
```

layout: page
title:  "Science"
permalink:   /science/
tagline : "Humanity is overrated."
\---</pre>

```
  </div>
```

  </div>
</p>
</div>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Create Archives/ Category Pages</strong><br>
</div><br>
<div class="archiveIntro">
  <p>
    Introducing <strong>Archive Pages</strong>.<br></p>
  <span class="archive-intro">  You can display a list of all the post corresponding to a particular category on a standalone Page using the <code>'archive'</code> layout.
</span>
</div>
<br>

<p>  <div class="manual-content">

```
  - Create a .md file in the root directory.<br>
  - Name the file. Preferred name will be the name of the category<br>  <code>life.md</code><br>
  - Write the <a href="jekyll">Front Matter</a> and content in the file.
  <div class="example">
    <span class='manual'>FORMAT</span><BR>
<pre>---
```

layout: archive<span class="hint"> Archive Page Layout</span>
title: String <span class="hint">Title of the webpage</span>
permalink: / String / <span class="hint">Permalink for the webpage</span>
tagline: String <span class="hint"> Tagline for the page</span>
category : String <span class="hint"> Name of the category of which the page will show posts.</span>
\---</pre>

```
  </div>
  <div class="example">

    <pre>---
```

layout: archive
title:  "Design"
permalink : "Design"
category: "design"
tagline: "It's all about perception."
\---</pre>

```
</div><br>
```

  </div>
</p>
</div>

