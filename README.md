# code-refactor-project
We are given a line of code that needs multiple adjustments. These adjustments make the code more organized, efficient, correct, and will make the code meet accessibilty standards. The user story is from a marketing company that wants a sustainable website. By fixing code within the provided html and css code, future web developers will have an easier understanding reading the new efficient lines of code.

## Site pictures
![Top-home-screen](Homescreen.png)
![Rest-of-website](website.png)

### Technologies used
- HTML
- CSS
- Markdown
- Visual Studio Code

### Installing
Step 1 git Clone UCB repository in terminal
```
git clone [git link of UCB repository]
```
You have now received the necessary UCB files you are ready to get started.

### Getting Started

Step 1 once files are finished downloading change directory into the UCB repository
```
cd UCB-BER-FSF-FT-06-2020-U-C
```
Step 2 Locate Develop folder
```
cd course-content
```
```
cd 01-html-git-css
```
```
cd homework
```
```
cd Develop
```
Step 3 Once in Develop folder you can now launch in VS Code using this command
```
code .
```
## Code Snippets
```
<div id="search-engine-optimization" class="search-engine-optimization">
        <!-- removed class attribute and moved into css -->
        <!-- adding alt attributes to image -->
        <img class="searchengine" src="./assets/images/search-engine-optimization.jpg" alt="Seo notebook gameplan" />
            <h2>Search Engine Optimization</h2>
                <p>The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.</p>
 </div>
 ```
 * Cleaned up HTML code with comments on what was changed from original code




## Built With
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link
* [See live site](https://kionling.github.io/code-refactor-project/)

## Authors 
* **Daniel Jauregui** 
- [Link to github](https://github.com/Kionling)
- [Link to LinkedIn](https://www.linkedin.com/in/daniel-jauregui-velazquez-b64a80172/)

## Special thanks to 
**Jerome**, wonderful teacher.
* [Markdown Guidelines](https://ucb.bootcampcontent.com/UCB-Coding-Bootcamp/ucb-ber-fsf-ft-06-2020-u-c/blob/master/course-content/02-css-bootstrap/activities/06-2-markdown-breakdown/template.md)
* [w3 schools semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)

### Summary
The objective was clear, we are given HTML and CSS that is not meeting the proper semantic definition for HTML code. As well as many other aspects that would make the browser have to do more work interpreting certain attributes located within HTML tags and images not meeting accessibility standards. Those accessibilty standards include filling in 'alt=""' tags into images. When looking at the provided code we are also assigned to organize the HTML code better than how we were given it. This is done by reducing the number of lines used by excessively spread code, creating a more compact, but easily readable line of code. There were button issues that required our knowledge of collaboratively using HTML and CSS, removing CSS attributes found in HTML tags, and creating new class identifiers, then moving the new classes into CSS. Overall, this assignment tests the logic, detail-oriented, and problem-solving skills to create an efficient, organized, and accessible website for a client. 