# Frontend Mentor - QR code component

![Design preview for the QR code component coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

**To do this challenge, you need a basic understanding of HTML and CSS.**

## The challenge

Your challenge is to build out this QR code component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Want some support on the challenge? [Join our community](https://www.frontendmentor.io/community) and ask questions in the **#help** channel.


## QR-code-component-v1

**COMMUNITY FEEDBACK**
There are some important foundational things to learn in this that you'll need to know for every future challenge.

1. All content must be contained within landmarks. Every page should at least have a main element, and in this case you should have the attribution in a footer

2. the image is extremely important content, the most important on the page in fact. That means it must have a proper alt description saying what it is and where it goes. You cannot treat it as decorative and leave the alt blank.

3. the card should have a heading element, it's not two paragraphs

4. link font(s) in the html head. This is more performant than css imports
5. always use a modern css reset at the start of the styles. Look them up
6. you will never want to use width 100vw. That is often wider than the screen because viewport units don't account for things like scrollbars. The body is already full width so you don't need to do anything to it's width
7. never limit the height of elements that contain text, including the body. Instead of height 100vh, use min-height so the element can grow taller as needed
8. remove width and height from the component. The browser can decide how much height is needed. And instead if giving an explicit width in px, use max-width in rem. This allows the component to shrink narrower if needed, and let's it adapt responsively even if users change their font size
9. the component info div isn't actually needed at all, buf if you want to keep it, give it a max width (in rem or ch) and auto margin on the sides.
10. the img doesn't need all those styles. Usually a css reset sets images to be display block and max-width 100%. The only other thing this needs is border radius, and optionally width 100%
