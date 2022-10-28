# Code Refactor With Starter Code

## Challenge Description
This week's challenge is about accessibility and semantic structuring.  Given starter code, I was able to identify some issues with the HTML and CSS files.  For example, when I read my HTML file, I noticed that almost all of the elements were labeled "div".  My first step was rewriting the elements to follow semantic structure.  More specifically, I included elements such as "header", "nav", "main", "section", "p" and more.  Doing this allowed me to read the code much clearer.

Once I rewrote the elements in the HTML file, I checked how the webpage looked to see if it matched what my finished product should be, and it did not.  So, my next challenge was looking at the CSS code.  When I looked at the CSS code I figured out that there were certain selectors targetting the divs I got rid of in my HTML.  Through some debugging using chrome devtools, I found which HTML elements needed to be adjusted in my CSS.  For example, in my CSS selector I had to change the old "div" element to "nav" because that is how I relabeled it in my HTML.  After consolidating the selectors and properties in the CSS so as not to have excess code, I took another look at my webpage and was happy to find that it matched the mock-up and was functioning correctly.  

Lastly, for the purpose of accessibility, I also added alt attributes to all of the images.

Doing this challenge has allowed me to read HTML and CSS code comprehensively, understand how they work together, and even debug some mistakes.  Since it is very important to follow a semantic structure while you are coding, I appreciated this exercise because I was able to see what poor semantic structure looked like and improve it.  I also appreciated how there were extra CSS selectors that could be consolidated because it helped put me in the mindset of finding the most efficient way to write code.

## Installation
N/A

## Usage
N/A

## Credits
N/A

## License
N/A