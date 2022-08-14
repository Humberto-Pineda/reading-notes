# Class 11

> Explain how the ability to use video and audio on the web has evolved since the early 2000s.

You needed to use plugins like Flash or Silverlight to have audio or video on the web.

> Describe the use of the src and controls attributes in the *video* element.

***src*** is used for video the exact same way as img. Controls allow you to control (big surprise) video and audio playback

> Why is it important to have fallback content inside the *video* element?

In case the browser doesn't support the video

>Write a very short story where *audio* and *video* are characters.

Once upon a time in the early 2000's, *audio* and *video* wanted to jump into the online world. But they couldn't. They had to jump into a plugin so others could see them but they couldn't be apart of the content family. They were sad. But then JavaScript devs made a way for them to be included. They got along immediatey with *img*. Now they are happy. The end.

> How does Grid layout differ from Flex?

**Flex** allows the manipulation of content either in one row or one column only. In **Grid**, you can manipulate content within a grid and can start content anywhere on that grid in a variety of directions

> Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- Grid Container: The area where the grid envelopes

- Grid Item: Children elements of Grid Container

- Grid Line: The lines that define the grid and the starting and ending points for the rows and columns

> Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

It helps users understand what they should be doing by having visual cues, like selecting an image that changes border color to green vs not choosing an image that chnges color to red

> Define the following *img* attributes srcset and sizes. Write an example of how they are used.

- **srcset** is a set of images and its size that a browser can choose to display

> ex. img srcset = "myself-100w.jpg 100w, myself-200w.jpg 200w, myself-300w.jpg 300w"

- **sizes** defines a set of conditions that will choose the best size image for the browser to display

> ex. size = "(Max width: 400px) 300px"

> How is srcset more helpful for responsive images than CSS or JavaScript?

Responsive images need srcset to work and works faster than js or css
