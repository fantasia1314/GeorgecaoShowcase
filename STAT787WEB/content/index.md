---
title: "Home"
date: 2023-03-30
output: html_document
---

<div class="horizontal-links">
  <a href="homework1.pdf">Homework 1</a>
  <a href="homework2.pdf">Homework 2</a>
  <a href="homework3.pdf">Homework 3</a>
  <a href="Shinyapp.pdf">Shiny App</a>
</div>

<div class="intro-container">
  <div class="avatar-container">
    {{< figure src="avatar.jpg" alt="avatar" width="500" >}}
  </div>
  <div class="text-container">
    <p>
      Hi, I'm Chenliang Cao, but you can call me George. 
      I'm currently in my first year as a graduate student at RIT, studying Applied Statistics. 
      I've already earned a Master's degree in Data Science last year. 
      This is my showcase website for my STAT 787 course.
      Feel free to browse around and get to know more about my work!
    </p>
  </div>
</div>

<style>
.horizontal-links {
  display: flex;
  justify-content: space-around;
  margin-bottom: 20px;
}

.intro-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.avatar-container {
  flex: 1;
}

.text-container {
  flex: 2;
  padding-left: 20px;
}
</style>
