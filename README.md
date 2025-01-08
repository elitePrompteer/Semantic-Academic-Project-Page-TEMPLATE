# Semantic Academic Project Page Template
This is a semantic HTML5 fork of the Horwitz ['academic paper project page template'](https://github.com/eliahuhorwitz/Academic-project-page-template).


Example project pages built using the original template are:
- https://vision.huji.ac.il/spectral_detuning/
- https://vision.huji.ac.il/podd/
- https://dreamix-video-editing.github.io
- https://vision.huji.ac.il/conffusion/
- https://vision.huji.ac.il/3d_ads/
- https://vision.huji.ac.il/ssrl_ad/
- https://vision.huji.ac.il/deepsim/


## Why the fork?
The original TEMPLATE was discovered on a HuggingFace project page in use for a legitimately impressive academic contribution (I'm sure there are many such cases), however when tracing the thread back, it was discovered that this template was representative of what I have taken to describing as a "div-soup sandwich", which consequently triggered both my inherent latent pedantry outrage, as well as similarly my latent community altruism - so, I decided to help the scientific community to do the RIGHT thing by offering a more semantic alternative.

## Okay... but, why the fork?
Ah, yes. Perhaps a bit more explanation would be useful:

### What is a "div-soup sandwich"?
This is my (only *slightly* derogatory) description of:
div soup sandwich - def: "a webpage that is built with the (unfortunately all too common) code smell/design approach of EXCLUSIVELY painting architecture, functionality, and aesthetics from a pallette of only <div> & <span> elements."

#### So?
SO, this is what my fellow padants, accessibility advocates, HTML snobs, and conscientious coders refer to as "unsemantic" - which is OBVIOUSLY sub-optimal, to say the least!

##### Right. OBVIOUSLY! But what if you said a bit more than the least?
Oh - sorry, of course... well.. I suppose the question is really: "What does 'semantic' mean and why is it important for web architecture & design?" - right?

###### *sigh* That thing you said, please! AKA The Importance of Semantics on the Web
A brief survey response:

"In web design, "semantic" refers to using HTML elements that clearly define the meaning and structure of content on a page, which is crucial for accessibility, search engine optimization (SEO), and overall user experience by making the website more understandable for both users and machines, including screen readers and search engine crawlers; essentially, it provides a logical organization to the content beyond just visual presentation. 
[1, 2, 3, 4, 5, 6, 7, 8]  

Key benefits of using semantic HTML in web design: [3, 4, 7]  

• Accessibility: Semantic elements allow assistive technologies like screen readers to accurately interpret the content hierarchy, providing a better experience for users with disabilities. [3, 4, 7]  

• SEO Improvement: Search engines can easily understand the structure and context of a page with semantic markup, leading to better search rankings. [2, 4, 6]  

• Code Readability: Semantic tags make the HTML code cleaner and easier to understand for developers, improving maintainability. [1, 3, 9]  

• Intuitive User Experience: Users can readily grasp the purpose of different sections on a website due to clear semantic elements like <header>, <nav>, <article>, <section>. [2, 3, 10]  

Examples of semantic HTML elements: [3, 7, 10]  

• <header>: For the introductory section of a page, including the logo and navigation [3, 7, 10]  
• <nav>: For navigation menus [3, 7, 10]  
• <main>: For the primary content of a page [7, 10]  
• <article>: For self-contained content like blog posts or news articles [3, 7, 10]  
• <section>: For distinct sections within a page [3, 5, 10]  
• <h1> to <h6>: For headings with different levels of importance [3, 5, 7]  


[1] - https://www.merkle.com/en/merkle-now/articles-blogs/2023/what--why---how-of-semantic-html.html
[2] - https://artversion.com/blog/the-role-of-semantics-in-web-design/
[3] - https://artversion.com/blog/semantic-html-the-backbone-of-accessible-and-intuitive-web-design/
[4] - https://www.linkedin.com/advice/1/what-role-does-semantic-html-play-responsive-web-rqb4c
[5] - https://momenticmarketing.com/blog/semantic-html
[6] - https://blog.pixelfreestudio.com/the-importance-of-semantic-html-in-modern-web-development/
[7] - https://www.linkedin.com/advice/1/how-does-semantic-html-play-role-responsive-web-etfhf
[8] - https://www.dhiwise.com/post/exploring-the-significance-of-semantic-html-elements
[9] - https://seekbrevity.com/semantic-markup-important-web-design/
[10] - https://www.theedigital.com/blog/what-is-semantic-html-and-why-you-should-use-it
"

## What's the Diff?
Specifically, the following details the main details of my refactoring, and the associated benefits, drawbacks, and trade-offs:

...TBD, WIP.
__ChangeLog__
#. change description - reasoning.
1. changed all classnames containing "publication-*" to "pub-*" - keystroke economy!
2. 

## Start using the template
To start using the template click on `Use this Template`.

The template uses html for controlling the content and css for controlling the style. 
To edit the websites contents edit the `index.html` file. It contains different HTML "building blocks", use whichever ones you need and comment out the rest.  

**IMPORTANT!** Make sure to replace the `favicon.ico` under `static/images/` with one of your own, otherwise your favicon is going to be a dreambooth image of me.

## Components
- Teaser video
- Images Carousel
- Youtube embedding
- Video Carousel
- PDF Poster
- Bibtex citation

## Tips:
- The `index.html` file contains comments instructing you what to replace, you should follow these comments.
- The `meta` tags in the `index.html` file are used to provide metadata about your paper 
(e.g. helping search engine index the website, showing a preview image when sharing the website, etc.)
- The resolution of images and videos can usually be around 1920-2048, there rarely a need for better resolution that take longer to load. 
- All the images and videos you use should be compressed to allow for fast loading of the website (and thus better indexing by search engines). For images, you can use [TinyPNG](https://tinypng.com), for videos you can need to find the tradeoff between size and quality.
- When using large video files (larger than 10MB), it's better to use youtube for hosting the video as serving the video from the website can take time.
- Using a tracker can help you analyze the traffic and see where users came from. [statcounter](https://statcounter.com) is a free, easy to use tracker that takes under 5 minutes to set up. 
- This project page can also be made into a github pages website.
- Replace the favicon to one of your choosing (the default one is of the Hebrew University). 
- Suggestions, improvements and comments are welcome, simply open an issue or contact me. You can find my contact information at the [EPIC WIN Info Hub](https://www.epicwinpromedia.info/)

## Acknowledgments
Parts of the original project template page were adopted from the [Nerfies](https://nerfies.github.io/) page.This project, itself, is a fork of the non-semantic template which can be found at [its GitHub repo](https://github.com/eliahuhorwitz/Academic-project-page-template).

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
