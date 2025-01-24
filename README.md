# karty-podskazhut

This is a flexible layout project that supports light and dark themes. [A layout](https://www.figma.com/file/GWuqAvaONsjQPXz53n9d0L/%235-%D0%9A%D0%B0%D1%80%D1%82%D1%8B-%D0%BF%D0%BE%D0%B4%D1%81%D0%BA%D0%B0%D0%B6%D1%83%D1%82/duplicate)

## What has already been done in the project:

- fonts,
- script,
- folder with pictures.

You can see the draft of the project at this [link](https://code.s3.yandex.net/web-developer/verstka/zipki/karty-podskazhut-main.zip). 

The script switches the color theme. It sets or removes the `.theme_dark` class from the `<body>` tag depending on the conditions. You need to monitor the class names of all the elements that are being laid out for the script to work. It is important to enable the script when the layout is complete, so as not to be distracted by it during the process.

## My tasks that I did in this project:

- Switching the theme is done via CSS variables, so I prepared them at the beginning of the layout.
- Used adaptive fonts with the `clamp()` function.
- Stylized the first letters of paragraphs with `::first-letter`.
