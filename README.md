# Horiseon Website 

## HTML Changes 

The first step I took to refactor this website was to start with the HTML file. I started with the head and found that this website was missing a title. I replaced the title, website, with the name of the company, Horiseon. This changed the name on the browser tab. When a customer searches for this website, the name of the company should be on the browser tab. 

Moving to the body, I noticed that the first div tag had a class attribute equal to header. Following semantic HTML rules, I replaced the div tag for a header tag which got rid of the class attribute. Next, I replaced the following div tag with a nav tag. This made it easier to distinguish the navigation bar from the header. Then, I got rid of the div tag with the content class and changed it to an article tag. I changed the div tags to section tags. Made sure the id's matched to the links in the nav bar. Then, I changed the div tag to an aside tag. I saw that an img tag had two tags. An image tag is a self-closing tag therefore it does not need the extra ending tag. Finally, I got rid of the footer class attribute in the last div tag. I replaced the div tag with a footer tag. 

## CSS Changes 

In the CSS file, I had to look back at the changes I made in the HTML file. The first change I made was the div tag to header tag. The CSS selector for the header was set for a class attribute. Simply, I removed the dot before the header for all the CSS rulesets involving the header. The next change was the div tag containing the class attribute, content. I replaced this tag with article. The new CSS ruleset would just be the article selector instead of .content. For the benefit portion, I found that certain rules were being repeated. I removed the repeated CSS rules, went back and made a universal class attribute called benefit. This helped reduce repetitive code in the stylesheet. As mentioned before, I went back to the HTML file and changed the classes within the article section. The class attribute I came up equals purpose. This helped me eliminate unnecessary CSS rules in one shot. The final change I made was the .footer selector, I just removed the dot in front of footer.
