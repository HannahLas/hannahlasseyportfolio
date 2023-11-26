# hannahlasseyportfolio

## My second challenge with the edX Bootcamp

I completed this task for the second challenge in my Skills Boot Camp in Front-End Web Development. The purpose of this task was to create a work portfolio for employers to see my work. I can add to the page as I complete more projects during the course. I was provided with starter code and needed to complete the code. I used the skills I have taught in the live lessons: flexbox, media queries and CSS variables. 

## Usage
Click on the links in the navigation bar to be directed to the relevant section of the website. See the screenshot below to see the navigation bar: 

[linktoscreenshot](assets/images/screenshot.png)

Here is a link to the final webpage: https://hannahlas.github.io/hannahlasseyportfolio/

## Acknowledgements

I used stack overflow to help me understand how to move the 'Websites for you' subtitle to the bottom right of the hero image:
.hero-banner h2  {
text-align: right;
bottom: 300px;
right: 100px;
margin: 20px; 
}

I used chat GPT (OpenAI. (2023). ChatGPT [Large language model]. https://chat.openai.com) to help me style the columns. I learnt the 'flex' property is shorthand for flex-grow,flex-shrink and flex-basis. In the example below flex grow and shrink are at 0. According to Chat GPT the flex basis is set as (calc 33.33% -20px as: 'This defines the initial size of the item before free space is distributed. In this case, it's calculated as 33.33% of the container width minus 20 pixels. This allows the items to take up approximately one-third of the container width with a 20-pixel margin on each side.'

.column {
  flex: 0 0 calc(33.33% - 20px); 
  margin: 10px;
  overflow: hidden;
  display:inline-block;
  justify-content: space-evenly;
}

Here I used chatgpt to create a faded grey border. I understood the linear-gradient as I had learnt about that through the 'CSS CheatSheet Challenge.' I hadn't learnt about how to use 'border-image-slice' before but learnt that 'border-image-slice ensures that the entire linear gradient specified in border-image is used to create the border around the image.' 
.column img, .column1 img {

  padding: 5px; 
  border: 18px solid transparent; 
  border-image: linear-gradient(to bottom, #ddd, #888);
  border-image-slice: 1; 
  margin: 50px auto; 
  background-color: white; 
}
## License
MIT License

Copyright (c) 2023 Hannah Lassey]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Badges

https://img.shields.io/badge/Hannah_Lassey-bluee.
