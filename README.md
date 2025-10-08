# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
<!--  - [Links](#links)-->
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./design/screenshot.png)


<!--### Links.

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)
-->
## My process

First, I remembered the previous project where I had centered an element in exactly the same way I needed to for this one. In that earlier project, I had decided to combine Grid to center my card and Flexbox for the elements inside the card. So I decided to use Grid again for my main element. Unfortunately, it didn’t work as I wanted. I did some research, after which I decided to rebuild the project entirely with Flexbox. It was much easier that way.
I also struggled a bit with organizing my HTML tags.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The `<span>` tag is used on text when you don’t want the element to take up the full width.
```html
<span class="tag">Learning</span>
```

I was able to place the image and the text on the same line thanks to the `<span>` tag. If I had used a `<p>` tag instead, the text would have appeared below the image.

```html
<div class="author">
    <img src="./assets/images/image-avatar.webp" alt="Greg Hooper" class="avatar">
    <span>Greg Hooper</span>
</div>
```
I tried to download this font and integrate it into my project, but it didn’t work for some reason, so I just imported it instead.

```css
@import url('https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,300..900&display=swap');
```


If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

I don’t fully master the situations where I should use Grid or Flexbox yet, but that’s not a problem since this is only my second project since I started learning HTML and CSS. I want to get better at using them. Right now, I still rely on AI sometimes. I don’t know if that’s a bad thing, but I suppose it’s normal for a beginner. My goal is to become less and less dependent on AI.


### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.


## Author

<!-- - Website - [Add your name here](https://www.your-site.com) -->
- Frontend Mentor - [@Hightechvisual](https://www.frontendmentor.io/profile/Hightechvisual)
- Twitter - [@mayiwilliam](https://x.com/mayiwilliam?t=Gg_xHm-Ms27YJzwSY646Pg&s=09)

## Acknowledgments

I did it entirely on my own without any outside help, so I give myself all the credit.
