# Code Refactor Starter Code
According to the Challenge the HTML code and CSS code were reviewed to add any missing functionality and to optimize the code by removing redundant fragments of code and consolidation them into a single class. See check list below <br/>

### Check List
- [✓] Add HTML semantics
- [✓] Structurized HTML logically
- [✓] Add alt text to images
- [✓] Check headings are in sequential order
- [✓] Title of webpage is concise

### Changes done
1. Added semantics to meet accessibility standards.
2. Fixed missing id in search-engine optimization.
3. Added alt text to images in both content and benefit sections.
4. Consolidated redundant content classes.
5. Consolidated redundant benefit classes.
6. Organized CSS classes by header, content and footer

**Below are <span style="color:red">ONLY fragments</span> of the code changes listed above.<br />**
To see all the changes please see the html and css code in [Horiseon html code](https://github.com/darkjuanjo/Horiseon)

To see the webpage in brower please click the following link: <br/>
[Horiseon website](https://darkjuanjo.github.io/Horiseon/)

```
See below for example HTML changes
<div class="header">  <!--Changed div to header in-->
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>  <!--Changed div to nav-->
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
     <div class="hero"></div> <!--Changed div to section-->
  <div class="content"> <!--Changed div to section-->
        <div class="search-engine-optimization"> <!--Changed div to article and added id to fix broken navigation-->
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" /> <!--Added alt text to image-->
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>

```
See below for example CSS class consolidation
```
/* Unconsolidated CSS classes*/
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

/*Consolidated CSS class...as a note the classes above were removed once the consolidate class was updated and the references in the html changed*/
.benefits-details {
    margin-bottom: 32px;
    color: #ffffff;
}
```
## Horiseon web site preview
![alt Horiseon web page preview](./assets/images/01-html-css-git-homework-demo.png)