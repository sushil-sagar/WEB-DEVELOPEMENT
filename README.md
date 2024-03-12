Here's a template for your README.md file with HTML questions and answers:

---

# HTML Interview Questions

1. **What is HTML?**
   - HTML (Hypertext Markup Language) is the standard markup language for creating web pages and web applications. It defines the structure and content of a web page using a system of tags and attributes.

2. **What are the new features in HTML5?**
   - Some of the new features in HTML5 include:
     - New semantic elements (`<header>`, `<footer>`, `<nav>`, `<article>`, `<section>`, `<aside>`, `<figure>`, `<figcaption>`)
     - Native support for video and audio playback (`<video>`, `<audio>`)
     - Support for offline web applications using the Application Cache (`<appcache>`)
     - New form input types (`<input type="date">`, `<input type="email">`, `<input type="url">`, etc.)
     - Canvas and SVG graphics support
     - Improved accessibility features
     - Web storage and local storage support

3. **What are the different types of HTML elements?**
   - HTML elements can be classified into several categories, including:
     - Structural elements (e.g., `<div>`, `<span>`, `<header>`, `<footer>`, `<nav>`)
     - Text-level elements (e.g., `<p>`, `<h1>` to `<h6>`, `<strong>`, `<em>`)
     - Form elements (e.g., `<form>`, `<input>`, `<button>`, `<select>`, `<textarea>`)
     - Multimedia elements (e.g., `<img>`, `<video>`, `<audio>`)
     - Table elements (e.g., `<table>`, `<tr>`, `<td>`, `<th>`)

4. **What is the purpose of the `<head>` tag in HTML?**
   - The `<head>` tag is used to contain meta-information about the document, such as its title, links to stylesheets, scripts, and other metadata. It is not displayed as part of the main content of the page.

5. **Explain the difference between `<div>` and `<span>`.**
   - The `<div>` and `<span>` elements are both used for grouping and applying styles to content, but they have different purposes:
     - `<div>`: Used for grouping block-level elements and creating sections of content.
     - `<span>`: Used for grouping inline elements and applying styles to specific parts of text or other inline content.

6. **What is the purpose of the `alt` attribute in the `<img>` tag?**
   - The `alt` attribute in the `<img>` tag is used to provide alternative text for an image. This text is displayed if the image cannot be loaded or if the user is using a screen reader.

7. **How do you create a hyperlink in HTML?**
   - To create a hyperlink in HTML, you use the `<a>` (anchor) tag with the `href` attribute to specify the URL of the link. For example:
     ```html
     <a href="https://www.example.com">Click here</a>
     ```

8. **What is the purpose of the `<meta>` tag?**
   - The `<meta>` tag is used to provide metadata about the HTML document. This can include information such as the character encoding, viewport settings, author, description, and keywords for the page.

9. **Explain the difference between HTML and XHTML.**
   - HTML (Hypertext Markup Language) is a markup language used for creating web pages. XHTML (Extensible Hypertext Markup Language) is a stricter, more XML-like version of HTML that follows the rules of XML syntax.

10. **What is the purpose of the `<form>` tag in HTML?**
    - The `<form>` tag is used to create an HTML form for collecting user input. It can contain various form elements such as text fields, checkboxes, radio buttons, and submit buttons.


11. **How do you create a table in HTML?**
    - To create a table in HTML, you use the `<table>` tag to define the table, `<tr>` tags to define rows, `<th>` tags to define header cells, and `<td>` tags to define data cells. Here's an example:
      ```html
      <table>
        <tr>
          <th>Name</th>
          <th>Age</th>
        </tr>
        <tr>
          <td>John</td>
          <td>25</td>
        </tr>
        <tr>
          <td>Jane</td>
          <td>30</td>
        </tr>
      </table>
      ```

12. **Explain the difference between `<ol>`, `<ul>`, and `<dl>`.**
    - `<ol>`: Ordered list, used to create a list where each item is numbered.
    - `<ul>`: Unordered list, used to create a list where each item is bulleted.
    - `<dl>`: Definition list, used to create a list of terms and their definitions.

13. **What is the purpose of the `<input>` tag?**
    - The `<input>` tag is used to create interactive form controls for collecting user input. It can create text fields, checkboxes, radio buttons, buttons, and more.

14. **How do you create a checkbox in HTML?**
    - To create a checkbox in HTML, you use the `<input>` tag with a `type="checkbox"` attribute. For example:
      ```html
      <input type="checkbox" id="myCheckbox" name="myCheckbox" value="checkboxValue">
      ```

15. **What is the purpose of the `<label>` tag?**
    - The `<label>` tag is used to provide a label for form elements such as checkboxes, radio buttons, and text fields. It improves accessibility by associating the label with the form element.

16. **How do you create a dropdown list in HTML?**
    - To create a dropdown list in HTML, you use the `<select>` tag to define the list and `<option>` tags to define the options. For example:
      ```html
      <select>
        <option value="1">Option 1</option>
        <option value="2">Option 2</option>
        <option value="3">Option 3</option>
      </select>
      ```

17. **Explain the difference between a block-level element and an inline element.**
    - Block-level elements start on a new line and take up the full width available, such as `<div>` and `<p>`. Inline elements are contained within block-level elements and do not start on a new line, such as `<span>` and `<a>`.

18. **What is semantic HTML?**
    - Semantic HTML refers to using HTML elements that carry meaning, such as `<header>`, `<nav>`, `<article>`, `<section>`, and `<footer>`. It helps search engines and assistive technologies understand the structure and content of a web page.

19. **What is the purpose of the `<canvas>` tag?**
    - The `<canvas>` tag is used to draw graphics, animations, or other visual images on a web page using JavaScript.

20. **How do you embed a video in HTML?**
    - To embed a video in HTML, you use the `<video>` tag and specify the source (URL) of the video. For example:
      ```html
      <video controls>
        <source src="movie.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      ```

21. **What is the purpose of the `<audio>` tag?**
    - The `<audio>` tag is used to embed audio content in a web page. It can include controls for playing, pausing, and adjusting the volume of the audio.

22. **How do you create a link that opens in a new tab?**
    - To create a link that opens in a new tab, you add the `target="_blank"` attribute to the `<a>` tag. For example:
      ```html
      <a href="https://www.example.com" target="_blank">Visit Example</a>
      ```

23. **What is the purpose of the `<blockquote>` tag?**
    - The `<blockquote>` tag is used to indicate that a block of text is a quotation from another source. It is often used to format longer quotations in a visually distinct way.

24. **How do you create a horizontal line in HTML?**
    - To create a horizontal line in HTML, you use the `<hr>` tag. It is a self-closing tag that creates a horizontal line across the page.

25. **Explain the purpose of the `<fieldset>` and `<legend>` tags.**

    - The `<fieldset>` tag is used to group related form elements together, and the `<legend>` tag is used to provide a caption or title for the `<fieldset>` element. They are used to improve the accessibility and organization of forms.


26. **How do you create a comment in HTML?**
    - To create a comment in HTML, you use `<!--` to start the comment and `-->` to end it. For example:
      ```html
      <!-- This is a comment -->
      ```

27. **What is the purpose of the `<abbr>` tag?**
    - The `<abbr>` tag is used to define an abbreviation or acronym, and it can optionally provide a full explanation or expansion of the abbreviation. It helps improve the accessibility and understanding of abbreviations on a web page.

28. **How do you create a subscript and superscript in HTML?**
    - To create a subscript, you use the `<sub>` tag, and to create a superscript, you use the `<sup>` tag. For example:
      ```html
      H<sub>2</sub>O
      X<sup>2</sup>
      ```

29. **What is the purpose of the `<noscript>` tag?**
    - The `<noscript>` tag is used to provide alternative content for browsers that do not support JavaScript or have JavaScript disabled. It allows you to display content or instructions for users who cannot view JavaScript-enabled content.

30. **Explain the purpose of the `<pre>` tag.**
    - The `<pre>` tag is used to define preformatted text, which is displayed in a fixed-width font and preserves both spaces and line breaks. It is often used for displaying code snippets or ASCII art.

31. **How do you create a responsive image in HTML?**
    - To create a responsive image in HTML, you can use the `<img>` tag with the `width` attribute set to a percentage value or use CSS to style the image to be responsive. For example:
      ```html
      <img src="image.jpg" alt="Responsive Image" style="max-width: 100%;">
      ```

32. **What is the purpose of the `<time>` tag?**
    - The `<time>` tag is used to define a specific time or date, which can be displayed in a human-readable format. It is useful for indicating dates, times, or durations in a standardized way.

33. **Explain the purpose of the `<address>` tag.**
    - The `<address>` tag is used to define contact information for the author or owner of a document. It is often used in the footer of a web page to provide contact details such as an email address or physical address.

34. **How do you create a progress bar in HTML?**
    - To create a progress bar in HTML, you use the `<progress>` tag and specify the value and max attributes to indicate the current progress and total progress. For example:
      ```html
      <progress value="50" max="100"></progress>
      ```

35. **What is the purpose of the `<details>` and `<summary>` tags?**
    - The `<details>` tag is used to create a disclosure widget that can be toggled open and closed to reveal or hide additional content. The `<summary>` tag is used as the visible heading or summary for the details element.

36. **How do you create a tooltip in HTML?**
    - To create a tooltip in HTML, you can use the `title` attribute on elements such as `<a>`, `<span>`, or `<div>`. For example:
      ```html
      <a href="#" title="This is a tooltip">Hover over me</a>
      ```

37. **Explain the purpose of the `<mark>` tag.**
    - The `<mark>` tag is used to highlight or mark a specific section of text within a document. It is often used to indicate search terms or important information.

38. **What is the purpose of the `<bdi>` tag?**
    - The `<bdi>` tag is used to isolate a span of text that might be formatted in a different direction from the surrounding text. It is often used in internationalization to ensure text is displayed correctly in right-to-left languages.

39. **How do you create an image map in HTML?**
    - To create an image map in HTML, you use the `<map>` tag to define the map area and the `<area>` tag to define the clickable areas on the image. For example:
      ```html
      <img src="planets.jpg" usemap="#planetmap">
      <map name="planetmap">
        <area shape="rect" coords="0,0,82,126" href="sun.htm" alt="Sun">
        <area shape="circle" coords="90,58,3" href="mercur.htm" alt="Mercury">
        <area shape="circle" coords="124,58,8" href="venus.htm" alt="Venus">
      </map>
      ```

40. **What is the purpose of the `<track>` tag?**
    - The `<track>` tag is used to specify text tracks for media elements such as `<audio>` and `<video>`. It is used to provide subtitles, captions, descriptions, or chapters for the media content.

41. **Explain the purpose of the `<output>` tag.**
    - The `<output>` tag is used to represent the result of a calculation or user action. It is often used in forms to display the result of a calculation or the output of a script.

42. **How do you create a draggable element in HTML?**
    - To create a draggable element in HTML, you can use the `draggable` attribute on elements such as `<div>` or `<img>`. For example:
      ```html
      <div draggable="true">Drag me!</div>
      ```

43. **What is the purpose of the `<wbr>` tag?**
    - The `<wbr>` tag is used to specify a word break opportunity within a line of text. It allows browsers to break long words or URLs at specific points to improve readability.

44. **Explain the purpose of the `<rp>` and `<rt>` tags.**
    - The `<rp>` tag is used to provide fallback parentheses for browsers that do not support the `<ruby>` tag, which is used for displaying ruby annotations. The `<rt>` tag is used to define the pronunciation or meaning of the base text in a ruby annotation.

45. **How do you create a meter in HTML?**
    - To create a meter in HTML, you use the `<meter>` tag and specify the value and min/max attributes to define the range and value of the meter. For example:
      ```html
      <meter value="6" min="0" max="10">6 out of 10</meter>
      ```

46. **What is the purpose of the `<dialog>` tag?**
    - The `<dialog>` tag is used to create a modal dialog box or popup window within a web page. It is often used for displaying interactive messages or forms that require user input.

47. **Explain the purpose of the `<datalist>` tag.**


    - The `<datalist>` tag is used to provide a list of predefined options for input elements such as `<input>` and `<textarea>`. It allows users to select an option from the list or enter a custom value.

48. **What is the purpose of the `<keygen>` tag?**
    - The `<keygen>` tag is used to generate a key pair for forms. It is often used in conjunction with the `<form>` tag to create a secure form that can be used for authentication or encryption.

49. **How do you create a responsive table in HTML?**
    - To create a responsive table in HTML, you can use CSS to style the table and make it responsive by setting the `overflow-x` property to `auto` or `scroll` on the table container. You can also use media queries to adjust the table layout based on the screen size.

50. **What is the purpose of the `<track>` tag?**
    - The `<track>` tag is used to specify text tracks for media elements such as `<audio>` and `<video>`. It is used to provide subtitles, captions, descriptions, or chapters for the media content.

      **51. What is the purpose of the `<iframe>` tag?**
   - The `<iframe>` tag is used to embed another document or webpage within the current HTML document. It allows you to display content from another source, such as a video, map, or external website, within your webpage.

**52. How do you create a favicon for a webpage?**
   - To create a favicon for a webpage, you need to create a small icon file (usually named `favicon.ico`) and place it in the root directory of your website. You can also use the `<link>` tag in the `<head>` section of your HTML document to specify the location of the favicon. For example:
     ```html
     <link rel="icon" href="favicon.ico" type="image/x-icon">
     ```

**53. Explain the purpose of the `<base>` tag.**
   - The `<base>` tag is used to specify a base URL for all relative URLs within a document. It allows you to set a default URL for links, images, and other resources, which can be useful when working with multiple pages or directories within a website.

**54. How do you create a meta viewport tag for responsive design?**
   - To create a meta viewport tag for responsive design, you use the following `<meta>` tag in the `<head>` section of your HTML document:
     ```html
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     ```
     This tag tells the browser to set the viewport width to the device width and to set the initial scale to 1.0, which ensures that the webpage is displayed correctly on different devices and screen sizes.

**55. What is the purpose of the aria-* attributes in HTML?**
   - The aria-* attributes in HTML are used to enhance the accessibility of web content for users with disabilities. They provide additional information about the structure and purpose of elements on a webpage, making it easier for screen readers and other assistive technologies to interpret and navigate the content.

**56. How do you create a text input field that only accepts numbers?**
   - To create a text input field that only accepts numbers, you can use the `type="number"` attribute in the `<input>` tag. For example:
     ```html
     <input type="number" name="quantity" min="1" max="10">
     ```

**57. Explain the difference between the `<strong>` and `<b>` tags.**
   - The `<strong>` tag is used to indicate strong importance or emphasis, typically displayed in bold by browsers. It is used to convey that the enclosed text is more important or has stronger emphasis than surrounding text. The `<b>` tag, on the other hand, is used to stylistically apply bold formatting to text, without necessarily indicating any semantic importance or emphasis.

**58. How do you create a button in HTML?**
   - To create a button in HTML, you use the `<button>` tag. For example:
     ```html
     <button type="button">Click Me!</button>
     ```

**59. What is the purpose of the rel attribute in the `<a>` tag?**
   - The `rel` attribute in the `<a>` tag is used to specify the relationship between the current document and the linked document. It is often used to indicate the type of link, such as `rel="stylesheet"` for a CSS stylesheet link or `rel="nofollow"` for a link that should not be followed by search engines.

**60. How do you create a background image in HTML?**
   - To create a background image in HTML, you can use the `background-image` CSS property in a `<style>` tag or an external CSS file. For example:
     ```html
     <style>
       body {
         background-image: url('background.jpg');
       }
     </style>
     ```

**61. Explain the purpose of the defer attribute in the `<script>` tag.**
   - The `defer` attribute in the `<script>` tag is used to defer the execution of a script until after the document has been parsed. This can improve the loading performance of a webpage by allowing other resources to load first.

**62. How do you create a text area in HTML?**
   - To create a text area in HTML, you use the `<textarea>` tag. For example:
     ```html
     <textarea rows="4" cols="50">
       Enter text here...
     </textarea>
     ```

**63. What is the purpose of the readonly attribute in the `<input>` tag?**
   - The `readonly` attribute in the `<input>` tag is used to make an input field read-only, meaning that the user can view the value but cannot modify it. This is useful for displaying information that should not be changed by the user.

**64. How do you create a responsive navigation bar in HTML?**
   - To create a responsive navigation bar in HTML, you can use

 a combination of HTML, CSS, and JavaScript. You can use CSS media queries to adjust the navigation bar layout based on the screen size, and JavaScript to add interactivity, such as a toggle button for mobile devices.

**65. Explain the purpose of the <optgroup> tag.**
   - The `<optgroup>` tag is used to group related `<option>` elements within a `<select>` dropdown list. It allows you to create nested groups of options, making it easier for users to navigate and select options in the dropdown list.

**66. How do you create a radio button in HTML?**
   - To create a radio button in HTML, you use the `<input>` tag with `type="radio"`. Radio buttons are typically used in groups, where only one option can be selected at a time. For example:
     ```html
     <input type="radio" id="option1" name="radio-group" value="option1">
     <label for="option1">Option 1</label>
     <br>
     <input type="radio" id="option2" name="radio-group" value="option2">
     <label for="option2">Option 2</label>
     ```

**67. What is the purpose of the required attribute in the `<input>` tag?**
   - The `required` attribute in the `<input>` tag is used to specify that an input field must be filled out before submitting a form. It is used to enforce data validation and ensure that important information is provided by the user.

**68. How do you create a progress bar in HTML?**
   - To create a progress bar in HTML, you can use the `<progress>` tag. For example:
     ```html
     <progress value="50" max="100"></progress>
     ```
     This creates a progress bar with a value of 50 out of a maximum value of 100.

**69. Explain the purpose of the placeholder attribute in the `<input>` tag.**
   - The `placeholder` attribute in the `<input>` tag is used to provide a hint or example text for the user. It is typically used to indicate the expected format or content of an input field, such as a sample email address or phone number.

**70. How do you create a responsive image slider in HTML?**
   - To create a responsive image slider in HTML, you can use a combination of HTML, CSS, and JavaScript. You can use CSS to style the slider and make it responsive, and JavaScript to add functionality such as sliding images and navigation controls.

**71. What is the purpose of the autocomplete attribute in the `<input>` tag?**
   - The `autocomplete` attribute in the `<input>` tag is used to enable or disable autocomplete functionality for an input field. When autocomplete is enabled, the browser can suggest or automatically fill in the input field based on the user's previous inputs.

**72. How do you create a dropdown list with multiple selections in HTML?**
   - To create a dropdown list with multiple selections in HTML, you can use the `<select>` tag with the `multiple` attribute. For example:
     ```html
     <select multiple>
       <option value="option1">Option 1</option>
       <option value="option2">Option 2</option>
       <option value="option3">Option 3</option>
     </select>
     ```

**73. Explain the purpose of the download attribute in the `<a>` tag.**
   - The `download` attribute in the `<a>` tag is used to specify that the target of the link should be downloaded when clicked, rather than navigated to. It is typically used for links to downloadable files, such as PDFs, images, or documents.

**74. How do you create a responsive video in HTML?**
   - To create a responsive video in HTML, you can use the `<video>` tag with CSS to make the video player responsive. For example:
     ```html
     <video width="100%" height="auto" controls>
       <source src="video.mp4" type="video/mp4">
       Your browser does not support the video tag.
     </video>
     ```

**75. What is the purpose of the open attribute in the <details> tag?**
   - The `open` attribute in the `<details>` tag is used to specify that the details in a `<details>` element should be visible by default. It is used to show or hide additional information in a collapsible section.
**76. How do you create a responsive grid layout in HTML?**
   - To create a responsive grid layout in HTML, you can use CSS frameworks like Bootstrap or Flexbox. These frameworks provide classes and utilities that allow you to create grid-based layouts that automatically adjust to different screen sizes. For example, using Bootstrap's grid system:
     ```html
     <div class="container">
       <div class="row">
         <div class="col-sm-6">Column 1</div>
         <div class="col-sm-6">Column 2</div>
       </div>
     </div>
     ```

**77. Explain the purpose of the `<ruby>`, `<rt>`, and `<rp>` tags.**
   - The `<ruby>` tag is used to define a ruby annotation, which is typically used in East Asian typography to annotate characters with pronunciation or meaning. The `<rt>` tag is used to define the pronunciation of the characters, and the `<rp>` tag is used to provide fallback content for browsers that do not support ruby annotations.

**78. How do you create a hyperlink that sends an email in HTML?**
   - To create a hyperlink that sends an email in HTML, you use the `<a>` tag with the `mailto:` attribute in the `href` attribute. For example:
     ```html
     <a href="mailto:example@example.com">Send Email</a>
     ```

**79. What is the purpose of the `<canvas>` tag in HTML5?**
   - The `<canvas>` tag in HTML5 is used to draw graphics, animations, and other visual elements on a webpage using JavaScript. It provides a drawing surface that can be manipulated dynamically to create interactive and visually appealing content.

**80. How do you create a responsive login form in HTML?**
   - To create a responsive login form in HTML, you can use a combination of HTML and CSS to style the form and make it responsive to different screen sizes. You can use media queries in CSS to adjust the layout and styling of the form based on the screen size.

**81. Explain the purpose of the `maxlength` attribute in the `<input>` tag.**
   - The `maxlength` attribute in the `<input>` tag is used to specify the maximum number of characters that can be entered into a text input field. It is commonly used to limit the length of input for fields such as names, emails, and passwords.

**82. How do you create a dropdown list with a search box in HTML?**
   - To create a dropdown list with a search box in HTML, you can use the `<select>` tag for the dropdown list and add a text input field for the search box. You can then use JavaScript to filter the dropdown options based on the text entered in the search box.

**83. What is the purpose of the `defer` attribute in the `<script>` tag?**
   - The `defer` attribute in the `<script>` tag is used to specify that the script should be executed after the document has been parsed, but before the `DOMContentLoaded` event is fired. This allows scripts to be loaded asynchronously without blocking the rendering of the page.

**84. How do you create a responsive image gallery in HTML?**
   - To create a responsive image gallery in HTML, you can use CSS to create a grid layout for the images and make them responsive using media queries. You can also use JavaScript to add functionality such as image lightboxes or sliders.

**85. Explain the purpose of the `tabindex` attribute in HTML.**
   - The `tabindex` attribute in HTML is used to specify the order in which elements should receive focus when the user navigates through the page using the Tab key. It can also be used to make non-focusable elements focusable for accessibility purposes.

**86. How do you create a responsive carousel in HTML?**
   - To create a responsive carousel in HTML, you can use a combination of HTML, CSS, and JavaScript. You can use CSS to style the carousel and make it responsive, and JavaScript to add functionality such as sliding images and navigation controls.

**87. What is the purpose of the `checked` attribute in the `<input>` tag?**
   - The `checked` attribute in the `<input>` tag is used to specify that a checkbox or radio button should be checked by default when the page loads. It is commonly used to preselect options in a form.

**88. How do you create a sticky footer in HTML?**
   - To create a sticky footer in HTML, you can use CSS to position the footer at the bottom of the page and make it stick to the bottom even when the content is not enough to fill the entire viewport height. For example:
     ```html
     <style>
       footer {
         position: fixed;
         left: 0;
         bottom: 0;
         width: 100%;
         background-color: #f1f1f1;
         text-align: center;
       }
     </style>
     <footer>Footer content here</footer>
     ```

**89. Explain the purpose of the `target` attribute in the `<a>` tag.**
   - The `target` attribute in the `<a>` tag is used

 to specify where the linked document should be opened when the link is clicked. It can be set to `_blank` to open the link in a new tab or window, or to `_self` to open the link in the same tab or window.

**90. How do you create a responsive table in HTML?**
   - To create a responsive table in HTML, you can use the `<table>` tag with CSS to make the table responsive. You can use media queries in CSS to adjust the layout and styling of the table based on the screen size.

**91. What is the purpose of the `autofocus` attribute in the `<input>` tag?**
   - The `autofocus` attribute in the `<input>` tag is used to specify that an input field should automatically receive focus when the page loads, allowing the user to start typing without having to click on the input field.

**92. How do you create a responsive accordion in HTML?**
   - To create a responsive accordion in HTML, you can use a combination of HTML, CSS, and JavaScript. You can use CSS to style the accordion and make it responsive, and JavaScript to add functionality such as expanding and collapsing accordion sections.

**93. Explain the purpose of the `list` attribute in the `<input>` tag.**
   - The `list` attribute in the `<input>` tag is used to associate an input field with a `<datalist>` element, which provides a list of predefined options for the input field. It is commonly used for autocomplete functionality.

**94. How do you create a responsive modal in HTML?**
   - To create a responsive modal in HTML, you can use a combination of HTML, CSS, and JavaScript. You can use CSS to style the modal and make it responsive, and JavaScript to add functionality such as opening and closing the modal.

**95. What is the purpose of the `<meta charset>` tag in HTML?**
   - The `<meta charset>` tag in HTML is used to specify the character encoding for the document. It ensures that the browser interprets the text correctly and displays special characters and symbols properly.

**96. How do you create a responsive form in HTML?**
   - To create a responsive form in HTML, you can use CSS to style the form and make it responsive to different screen sizes. You can use media queries in CSS to adjust the layout and styling of the form based on the screen size.

**97. Explain the purpose of the `role` attribute in HTML.**
   - The `role` attribute in HTML is used to define the role or purpose of an element for accessibility purposes. It is used to describe the function of an element to assistive technologies such as screen readers.

**98. How do you create a responsive image map in HTML?**
   - To create a responsive image map in HTML, you can use the `<map>` and `<area>` tags to define clickable areas on an image. You can use CSS to make the image map responsive and adjust the clickable areas based on the screen size.

**99. What is the purpose of the `alt` attribute in the `<img>` tag?**
   - The `alt` attribute in the `<img>` tag is used to provide alternative text for an image, which is displayed if the image cannot be loaded or if the user is using a screen reader. It is important for accessibility and SEO purposes.

**100. How do you create a responsive timeline in HTML?**
    - To create a responsive timeline in HTML, you can use CSS to style the timeline and make it responsive, and JavaScript to add functionality such as scrolling and navigation. You can use media queries in CSS to adjust the layout and styling of the timeline based on the screen size.
