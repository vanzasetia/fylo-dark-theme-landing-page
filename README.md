# Fylo Dark Theme Landing Page

## Disclaimer

This project is solely for learning purposes. I take no any responsibility or liability for the accuracy, completeness, or usefulness of any information provided in this project. You should not use it as a reference for creating your project.

I am currently no longer working on this project.

## Feedback and Live Review

- [Live Review](https://fylodarkthemevs.netlify.app/)
- [Give feedback on Frontend Mentor platform](https://www.frontendmentor.io/solutions/fylo-dark-theme-landing-page-html5-css3-sass-71fZb3LhF)

## The Story When Doing This Challenge

I got a problem on `icon-security.svg`, this icon is weird. The size is not the same as the other icon, so if you take a deeper look into all icons in `features` section, you will notice that weird thing. So, what I did instead of setting the `width`, I set the `height`. In my opinion, has different **width** is better than different **height**.

The `testimonials` section and `footer` on the `mobile-design` in my opinion the `font-size` is too small. So I make it bigger.

About the **inline svg**, I have to use those as inline svg so that I can change the color when it is on `:hover`. But if you have a better way feel free to let me know in the [community feedback section](https://www.frontendmentor.io/solutions/fylo-dark-theme-landing-page-html5-css3-sass-71fZb3LhF).

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

I also used [Mailgo](https://mailgo.dev/), which is a light JavaScript library for `mailto` and `tel`. It will give you a nice popup for every `mailto` and `tel` link.

## Useful Resources

[Form Validation UX in HTML and CSS](https://css-tricks.com/form-validation-ux-html-css/)
