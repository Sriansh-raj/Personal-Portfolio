## My Personal Portfolio ✨
### Feel free to use it as a template and suggest customization :)

Built with HTML, Flexbox (and soon to be a bit of JS)

To view a live demo, **[click here](https://sriansh-raj.github.io/Personal-Portfolio/)**

This repo is a easily customizable personal portfolio template. Feel free to use it as-is or customize it as much as you want. I wanted to build a very simple template without any unnecessary bloat. 

---

There are 8 customizable sections:
---
**Jumbotron** - Edit the `h1` and `p` in the jumbotron-text `div`
```
<div class="jumbotron-text">
  <h1>Brandon Morelli</h1>
  <p>Full-Stack Web Developer in Boston, Ma.</p>
</div>
```
---
**About** - Edit the `h2` and `p`, or add more, in the main-content `div`
```
<div class="main-content">
  <div class="content-header">
    <a class="anchor" name="about"></a>
    <h2>About</h2>
  </div>
  <div class="content-body">
    <p>text here</p>
    <p>text here</p>
  </div>
</div>
```
---
**Experience** - Experiences are organized in content-body `div`. There is an `h4` and a `p` that you can edit.
```
          <div class="content-body">
            <div class="card">
              <div class="card-header">
                <h4>Company <span class="job-title">Job Title</span></h4>
              </div>
              <div class="card-content">
                <p>Paragraph text</p>
              </div>
            </div>
```
---
**Education** - Stored in a card `div`. Edit the `h4` and `p` tags
```
            <div class="card">
              <div class="card-header">
                <h4>School <span class="job-title">Dates Attended</span></h4>
              </div>
              <div class="card-content">
                <p>Paragraph Text</p>
              </div>
            </div>
```
---
**Project** - Projects are stored in project-card `div`s. Edit the `image`, `h4`, and `p`
```
            <div class="project-card">
              <div class="project-image">
                <img src="http://placehold.it/250x350">
              </div>
              <div class="project-content">
                <h4>Project Name</h4>
                <p>Paragraph text</p>
                <a href="#">Link Text</a>
              </div>
            </div>
```
---
**Skills** - Simply list items. Add or remove `li` to add/remove skills.
```
            <ul class="ul-skills">
              <li class="li-skills">Javascript</li>
            </ul>
```
---
**Contact** - Simply change the `address` to include your email address
```
<form method="POST" action="https://formspree.io/email@email.com">
```
---
**Footer** - content-body `div` with an editable `p`
```
          <div class="content-body">
            <p>Copyright YOUR NAME 2017</p>
          </div>
```
---

##### To do
- [x] Make responsive
- [x] Scroll to top button
- [ ] Other effects?


---

A very simple portfolio template, made with 🖤 and HTML
