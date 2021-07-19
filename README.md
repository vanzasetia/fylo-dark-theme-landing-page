# Fylo Dark Theme Landing Page

<p align="left">
  <img src="https://img.shields.io/badge/Difficulty-Junior-brightgreen?style=for-the-badge" alt="Difficulty">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/vanzasetia/fylo-dark-theme-landing-page?style=for-the-badge">
  <a href="https://twitter.com/vanzasetia" target="_blank"><img src="https://img.shields.io/twitter/follow/vanzasetia?logo=twitter&style=for-the-badge" alt="Twitter followers." /></a>
  <img alt="Netlify" src="https://img.shields.io/netlify/66d088be-8d5b-415d-9b2e-58d778b0c09f?style=for-the-badge">
</p>
<p>
  <a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="Valid CSS!" />
    </a>
</p>

## Feedback and Live Review
* [🌍 Live Review]()
* [👉 Give feedback on Frontend Mentor platform]()
* [🐦 Give Feedback on Twitter]()

## The Story When Doing This Challenge

I got a problem on `icon-security.svg`, this icon is weird. The size is not the same as the other icon, so if you take a deeper look into all icons in `features` section, you will notice that weird thing. So, what I did instead of setting the `width`, I set the `height`. In my opinion, has different **width** is better than different **height**.

The `testimonials` section and `footer` on the `mobile-design` in my opinion the `font-size` is too small. So I make it bigger.

About the **inline svg**, I have to use those as inline svg so that I can change the color when it is on `:hover`. But if you have a better way feel free to let me know in the [community feedback section]().

Something is also happening to `icon-location.svg`, where I have to give `margin-top` to make it align correctly with the paragraph.

```css
.info__physical-address .info__icon {
  margin-top: 0.5rem;
}
```


## What I Learned
* **Email validation**, I learned on how to add email input validation without using JavaScript.


## Built With
This project is created using **HTML5**, **CSS3**, and **Sass**. 

I used one of the form features from [Netlify which Forms Spam Filters](https://docs.netlify.com/forms/spam-filters/), using **Honeypot field**.

I also used [Mailgo](https://mailgo.dev/), which is a light JavaScript library for `mailto` and `tel`. It will give you a nice popup for every `mailto` and `tel` link. I really ❤️ love this library, since it is **easy** and **simple** to use.
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="" width="auto" height="70px">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="" width="auto" height="70px">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="" width="auto" height="70px">
  <img src="./images/mailgo.png" alt="" width="auto" height="70px">
</p>

## Useful Resources
* [Form Validation UX in HTML and CSS](https://css-tricks.com/form-validation-ux-html-css/)

## Continued development

I'm gonna take a look at feedback from other people to improve this site.
