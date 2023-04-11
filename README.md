# portfolio
## Web Development II Final and personal portfolio 

**Tell us about your process, challenges you faced during development and how you overcame those changes?**

The process was rather starighforward for the most part. I will admit that I did struggle with the use of Bootstrap at first as I was not familer with the Bootstrap calls - I was also not used to haveing the Bootstrap CSS in my html due to the fact that, thus far, having in-line CSS was highly discouraged, and since the Bootstrap calls act as sort of in-line styles I kept getting confused as to why certain elements had padding or margins when my CSS file never applied those styles. For example, I would apply the mb-5 (*margin bottom*) call on a heading element, style other elements and then change my mind about the margin spacing and would look in my main.css file without realizing the call was in my html.

Likewise, I had issues trying to style the default primary Bootstrap buttons as I assumed I could apply styles as easily as a non-bootstrap button but eventually came to the realization I would have to modify the SASS and other source code files - which I deemed out of my scope for now.

Through time I overcame these challenges as every issue I encoutered I looked at the Bootstrap API/Documentation and became more accustomed to it, as well, I was also able to more accurately search my issues since I better understood what possible conflicts could cause my issues.

To continue, a specific issue I had was with styling my About page, specifically the banner-about section as I had to use position absolute in order to overlap a part of the div but this was the first time I had used it in such as way, that I didn't fully understand how the bottom and top attributes worked. I eventually came to understand after trial and error and now better understand how they are used.

I also had an issue with GitHub not being able to display my banner image, this issue was resolved when I notoiced I didn't have the quotation marks present in the url. 

Lastly, another issue I had was with my primary CSS buttons. In the button styles I have two z-indexs that are negative values for my hover affect to work, but this resulted in the buttons hiding under the main content of my page, but if I increased the values to postive integers the link text would fall under. I eventually looked on Stack Overflow and found a solution in which I had to target the anchor tage, make the position relative and I increased the z-index to about 99 so that way it displays on top of the buttons and main content of the page.

## What have you learned by creating your web portfolio?

I have learned how fun and enjoyable it is to go from a low-fidelity wireframe of my wesbite to coding the finished product. I would also add I learned the importnace of reviewing the framework API/Documentation - I was feeling a bit pressed for time and didn't read the Bootstrap documentation as well as I should have, but I know for next time to take a day and read the API/Documentaion in order to save a lot of headaches further down the line. 

## Citation

All of my images are created by me with the exception of the banner image which I retrived from Pexels.com - I did edit the image to make it darker for contrast purposes. 

As well, the code for my primary CSS buttons is borrowed from James LeVie's codepen [Button Hover Effects](https://codepen.io/JamesLeVie/pen/eYPYZNY) 

I have also used the [Animate On Scroll Library](https://michalsnik.github.io/aos/) for the addtional CSS library.

All the fonts I have used are from Adobe Fonts

Icons are from [Font Awesome](https://fontawesome.com/)

## Notes

I have a few buttons that like to a page called work-in-process, this page was not apart of any of my UX-Designs such as low/hi-fi wireframes, Journy Maps or Site Diagrams. My UX-Professor Mary Bulkowski-Rose suggested to just focus on the Home, About, and Contact page for the final and add addtional pages over the summer when I have time. 



