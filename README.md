# Road to Frontend Development for Getting Hired as a Fresher
-------------
## Skills to be Learnt
- HTML
- CSS
- Tailwind CSS
- Javascript | React JS | Redux
- Git and GitHub
---------------------
## Video Reference
[HTML Tutorial](https://www.youtube.com/watch?v=rklidcZ-aLU&list=PL78RhpUUKSwfYr_bKHq7SWfTCBGad_xxP)

-----------
## 09-12-2024
### Level 0
Basic introduction to IDE and why do we need it. Installation of **VS Code for Code Editing** and Installation. **Extensions** required are **Prettier for Formatting** and **Live Server for Auto Refresh**.

Fundamentals of **Web Development** and **Client Browser** structure. What is HTML, CSS and Javascript and What actually does these tech do.

### Level 1
- Tags in HTML
- Emmet Shortcuts
- MDN Documentation for Resources
- Comments **<!-- -->**

### Level 2
- Attributes in HTML
- The **id Property**

--------------------

#### Tag 1: h1, h2, h3, h4, h5, h6 Tag
The heading tag is used to define headings of a web page. There are 6 levels of heading available and each has different sizes. However the size here represents the importance of the heading to the browser and has nothing to do with font size. Highly important for **Search Engine Optimization**.

#### Tag 2: p Tag
Used to write a paragraph in HTML Document. It adds spaces between the lines automatically and also has word-wrap feature. Commonly used in text heavy content.

#### Tag 3: br Tag
It is used to as line break. By default HTML ignores any extra spaces and any kind of formatting related to spaces in normal tags. The **br** tag is used as **Enter** key of keyboard. The **br** is and self-enclosing tag.

#### Tag 4: hr Tag
It is used to draw a horizontal line **horizontal rule** and it is also a self-enclosing tag.

#### Tag 5: img Tag
The **img** tag is basically used to insert a **Image** in a html document. It is also a self-enclosing tag. It usually has 2 main attributes. One is **src** which defines the source of the image and the other is **alt** which is a text that is shown if the **src** attribute doesn't work properly. It can be resized with attributes like **width** and **height**. It is usually to recommended to either set **height** or **width** attribute only so that the aspect ratio of the image remains unified.

#### Tag 6: video Tag
Used to insert a video in a document and has lots of attributes. The main are **src** that contains video source, **width and height** to resize for better display, **controls** to see various in-video options, **autoplay** to automatically start video on page load, **muted** to mute video by default. Apart from these there are also a lot of attributes.

#### Tag 7: a Tag
The **a** tag also known as **anchor** tag is used to create navigational link either to same website or any external website. It has a attribute **href** the contains full address of the destintion. The other important attribute is **target** which helps browser to understand whether to open this page in the same tab or in new tab. By default the value of **target** is **main** which means to open in the same tab.

#### Tag 8: b, i, u, s or strike Tag
Since these tags are used for formatting or styling so it is generally recommended not to use in HTML document because that is the work of CSS.

#### Tag 9: pre Tag
Used to display a text in the **Exact Same Format in Which it Has Been Written**. No spaces or tabs are removed.

#### Tag 10: big and small Tag
Not usually used because styling is done in CSS.

#### Tag 11: sub and sup Tag
The **sub** is used to insert **Subscript** and the **sup** is used to **Superscript**. Generally, used to write Mathematical or Chemical formulas.

---------------------
### Level 2

#### Character Entity Reference
Used to dsplay special characters or symbols. Usually starts with **&** and ends with a **;**. If we want to display more than one white space at a time then we can use "&nbsp;M &nbsp; &nbsp;" this. 

-----------------
### Level 3
Browser Tools
- View Page Source
- Inspect Element
- Responsive Design
- Validating Web Pages

------------------------------------------
### Level 4
#### 1.) Semantics and Non-Semantic Tags
**Semantic** tags are those tags that are meaningful and helps browsers to understand that a partucular tag is used for what purpose. Eg:, header, footer, navigation, article, aside. It is more for SEO purposes.

**Non-Semantics** tags are those tags that don't carry any meaning but it does not mean they are not important. Eg:, div, span, etc.

#### 2.) Body Tags
These are the tags to be used in body for best HTML Structure. These tags can be defined multiple times and can contain itself in a nested structure. These tags don't add any kind of functionality but helps browsers and search engines to understand a web document with more clarity.

- header
    - nav (Navigational Links)
- main (Should Only Occur Once Per HTML Page)
    - section
        - article (Blog Posts)
        - article
    - section
        - article
        - section
    - aside (Widgets, Links, Advertisement)
        - section
        - section
- footer

#### 3.) Inline Element vs Block Element
**Inline Element** ocuupies width and size as per the content. Eg:, span, a, etc.
**Block Elements** occupies full width of the screen and height as per content. Always starts on new line. Eg:, p, div, etc.

#### 4.) div Tag
It is a container for other tags. It is a block level element. It con contain anything including itself.

#### 5.) span Tag
It is a inline element and work as a container for other tags. Basically used for small text manipulations to make websites more attractives.

------------------------------------------------------
