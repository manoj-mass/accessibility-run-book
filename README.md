# WIP: Cooking something good here :rocket: :de: 

# Web Accessibility Run Book

The Accessibility Run book serves as a guide to ensure that all digital assets, including web applications, documents, code, and other resources, are designed and maintained with accessibility in mind. Accessibility ensures that individuals with disabilities can access, understand, and interact with our digital content effectively and independently.

Free and Open Source Repo. Feel free to contribute. 

## What is web accessibility

Web accessibility refers to the practice of designing and developing websites, web applications, and digital content in a way that ensures they can be used and understood by as many people as possible, including those with disabilities. The goal of web accessibility is to create a barrier-free online environment, making the internet more inclusive for individuals with various impairments or limitations.

## Different types of disabilities

As per WHO (World health organization) an estimated 1.3 billion people experience significant disability. This represents 16% of the world’s population, or 1 in 6 of us.

Also as per Lighthouse international research study one in six Americans which is approximately 17% of Americans, 45 years of age or older, representing 16.5 million middle age and older adults, report some from of vision impairment, even wearing glasses or contact lenses. 7.9 million personas (age 6 and older) have difficulty seeing worlds and letters in ordinary newspaper print.

    * Physical disabilities
    * Speech and Language disabilities
    * Deaf or hearing disabilities
    * Blindness or vision impairments
    * Brain injuries
    * Attention deficit/ Hyperactivity disorders

## Ways you can browser web
    * Screen readers
    * Keyboard shortcuts
    * Mouth stick / Head wand
    * Single switch
    * Magnification
  
## Keyboard shortcuts

### Tabbable elements
    Idea is hitting Tab key will move one tabbable item ahead.
    Where as shift + tab will move one tabbable item backwards.
```html
    * <a>
    * <button>
    * <select>
    * <textarea>
    * <iframe>
    * <form>
    etc.
```
### Tabindex
   ```html
    <div tabindex="0">Tabbable element</div>
   ```

   Tabindex may contain three different types of values. 
   1.  **0** - element should be focused
   2.  **Positive value** - element is focusable. Focused order defined by the positive number/value attribute. If two elements contain same value, their relative order follows their relative position in the document.
   3.  **Negative values** - element should not be focused.
   
   **Maximum value of tab index is 32767 as per W3C section 17.11.1** Some times you may need to use javascript in certain occasions depending on the situation to use javascript to focus onto an element manually.

### Visual focus

It should always indicate which element are currently focused visually. You may often see when you are focused onto a button or an input field light blue boarder wraps the element indicating the current element focus.

### Skip links

Idea is to have a link at the top of the page which would jump users directly to other sections. For an instance if a visually impaired user uses keyboard or tab to navigate through a website, user may have to tab through all of navigation section or all of page header section to come to the main content area.

Skip links enable users to skip navigation section straight away. To achieve this we have to place a link as the first element of the navigation.


```html
<body>
<a href="#maincontent">Skip to main content</a>
...
<main id="maincontent">
<h1>Heading</h1>
<p>This is the first paragraph</p>
```
