# Code Refactor Starter Code
Prework-Study Guide Webpage
Description
A repo project that's been debugged for an assignment. There was a bad link, a couple of syntax errors and repeated code. I fixed the code by simplifying it and correcting some of the incorrect code. Most of the former code is commented out but still visable. 

Installation
N/A

Usage
I looked over the website HTML first as I noticed that one of the links was not working, unlike the others. I found that the div id should have been a div class on the "search-engine-optimization" link. I changed it to an id and the link began to work. I then changed the div class footer to just a regular foot tag. Changing the CSS back to a regular foot tag without the period. The code that the footer has does not require a div class.
 
I then moved to the CSS folder. I looked at the code and realized that it was really long. Each tag was written and a lot was duplicated. First I changed the H1 header title. Certain parts of the word were emphasized with span, but there was no code that justified a reason for that. So I added the color in .header h1 .seo to the header h1 tag. This lessened the tags on my page, but did not change the website visually. All three of the benefit tags had the exact same code for the margin and color. I shortened the code to not represent each individual one but instead to just benefit in Html. Then I commented on all the duplicates and had one tag for .benefit. This enabled me to do the same to the .benefit h3 tags. Now that there was only a .benefit class I could comment out the rest. I also noticed that two of the images in the benefits section had some incomplete syntax. Luckily this did not affect the images display, but I corrected that by finishing the img tag brackets.
 
I then noticed the header links boxes in the body had duplicated code in CSS. So I combined .online-reputation-management, .social-media-marketing, .search-engine-optimization  with commas and added the code once. The max height of the boxes in the image is 200px. This was again written out thrice, so I deleted the three and put it under one tag with the parent content. I created another tag for the parent and put the code rules for h3 under and commented out the duplicates.

Feeling done with the important refracter part of this assignment with shortening the code and fixing any bugs, I looked over the HTML as a whole. I noticed that there was an extreme amount of div tags and that it be helpful to replace some with some easier to read tags. I replaced the first div tags in the header with a section tag. I then went to my CSS and changed every header tag with a div. I then chnaged the div for the hero image to a img class. I then replaced the content div parent with a article tag and the smaller sections into section tabs. I was not required to change the CSS code for this. I did the same with the benefits section. Turning thr parent into a article tag and the sections to section tags. I also changed the margin-bottom becuase I wanted the borders to be at a even length. With this I feel satified that I improved the code for this assignment.


Credits
N/A

License
Please refer to the LICENSE in the repo.

