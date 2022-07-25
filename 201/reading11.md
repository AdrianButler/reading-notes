# Reading 11

## Video and Audio Content

- Explain how the ability to use video and audio on the web has evolved since the early 2000s
  - You used to have to use third party solutions like flash or silverlight but now there is native html support.
- Describe the use of the `src` and `controls` attributes in the `<video>` element.
  - `src` is the path or url to the video and `controls` lets the user control audio and video playback
- Why is it important to have fallback content inside the `<video>` element?
  - If the browser doesn't support `video` it will show the fallback instead
- Write a very short story where `<audio>` and `<video>` are characters.
  - Audio is yin while video is yang, and together they combine to create an amazing source of media.

## CSS Grid

- How does Grid layout differ from Flex?
  - Grid is about giving certain things certain space while flex is about aligning things
- Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
  - grid container is the main container that will decide where everything goes and how much space they take up. grid item is just something inside the grid and grid line is how much space that item takes up

## Responsive Images

- Besides, making a site visually appealing across different screen sizes, why should developers make images responsive?
  - You don't need large images on smaller devices
- Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.
  - `srcset` lets you specify different sources for different variables (screen width). `sizes` lets you define the conditions to pick a certain image
- How is `srcset` more helpful for responsive images than CSS or JavaScript?
  - The browser downloads all images before reading the css so you would have wasted data by including it in either JS or CSS.

