
- [Course Syllabus](<../../../../Downloads/Web Dev Syllabus (1).pdf>)
- [12 Rules to learn](<../../../../Downloads/12+Rules+to+Learn+to+Code+[2nd+Edition]+2022 (1).pdf>)
- Required Software
    - Visual Studio Code
    - VS Code Extensions
        - Live Preview
        - Prettier
        - vscode-icons
    - Google Chrome
### Summary of Key Points

1. **Definition of the Internet**:
   - The Internet is essentially a long piece of wire connecting computers globally.
   - It’s not a cloud or complex entity but a simple physical network.

2. **Servers and Clients**:
   - **Servers**: Special computers online 24/7, serving data and files for websites.
   - **Clients**: Computers used by users to access the Internet.

3. **Analogy**:
   - A web server is like a giant 24/7 library serving website data upon request.

4. **Request Process**:
   - When you type a URL (e.g., google.com), your browser sends a message to your ISP (e.g., AT&T, Comcast).
   - The ISP relays the message to a DNS server, which acts like a phone book to find the IP address of the website.
   - The DNS server returns the IP address to your browser via the ISP, allowing a direct request to the server hosting the website.

5. **IP Addresses**:
   - Every computer on the Internet has a unique IP address, similar to a postal code, for sending and receiving data.

6. **Undersea Cables**:
   - Massive undersea cables connect continents, consisting of hundreds of fiber optic fibers.
   - These cables use lasers to transmit up to 400 gigabytes of data per second.

7. **Technology Marvel**:
   - The Internet involves complex, high-speed data transmission through these cables, enabling rapid access to websites globally.

8. **Practical Exploration**:
   - Tools like nslookup.io can be used to find the IP address of websites.
   - Submarinecablemap.com shows the global network of undersea cables.

9. **Conclusion**:
   - Understanding the Internet's infrastructure is crucial for building websites and web apps.

### Summary of Key Points

1. **Introduction**:
   - The Internet connects client computers with server computers.
   - DNS servers act as a phonebook to look up IP addresses of websites.

2. **Types of Files in Web Development**:
   - **HTML**: Contains the content of the website (text, images, buttons, links). It's the structure or "bricks" of a website.
   - **CSS**: Responsible for styling the website (colors, fonts, layout). It defines the appearance of the HTML content.
   - **JavaScript**: Adds functionality to the website (interactive elements, dynamic content). It makes the website interactive and functional.

3. **Browser Role**:
   - The browser loads HTML, CSS, and JavaScript files to render web pages.
   - HTML provides content, CSS provides styling, and JavaScript provides functionality.

4. **Example: Google Homepage**:
   - HTML: Displays the Google logo, buttons, and text box.
   - CSS: Styles the appearance of these elements.
   - JavaScript: Enables the search functionality.

5. **Practical Exercise with Chrome Developer Tools**:
   - Inspect and modify website elements using Chrome Developer Tools.
   - Example: Changing the "Google Search" button text to "Angela Search."
   - Changes are temporary and revert on page refresh.

6. **Importance of Tools**:
   - Chrome Developer Tools are recommended for web development.
   - Use these tools to inspect and modify HTML and CSS in real-time.

7. **Learning Outcome**:
   - Future lessons will cover creating and hosting your own websites.
   - Emphasis on learning HTML, CSS, and JavaScript to build functional, styled, and interactive websites.

8. **Fun and Practical Application**:
   - Use developer tools to prank friends by temporarily changing website content.
   - Understand that these changes are local and not permanent.

9. **Course Continuation**:
   - Upcoming lessons will delve deeper into web development tools and techniques.

### Summary of Key Points

1. **Introduction to HTML**:
   - Browsers like Chrome, Safari, and Brave render websites using HTML, CSS, and JavaScript.
   - Websites can't be created with just CSS or JavaScript, but an HTML file alone can create a simple website.

2. **HTML Basics**:
   - **HTML**: Stands for Hypertext Markup Language.
   - Defines the content and structure of a website.

3. **Hypertext**:
   - Hypertext refers to text with links (hyperlinks) to other documents.
   - The first websites, such as the one by Sir Tim Berners-Lee, were built with HTML and filled with hyperlinks.

4. **Markup Language**:
   - Markup languages use tags to define elements within the text, similar to how English uses quotation marks or editing symbols.

5. **HTML Tags**:
   - Tags are the building blocks of HTML.
   - Examples of important tags: 
     - **Headings**: `<h1>` to `<h6>`
     - **Paragraph**: `<p>`

6. **Historical Context**:
   - Early HTML had few tags, but more have been added over time.
   - Despite many tags existing, only a few essential ones are commonly used.

7. **Learning Approach**:
   - Focus on essential HTML tags necessary for projects and exercises.
   - Start with learning the heading tag (`<h1>`), one of the first and most fundamental HTML tags.

8. **Next Steps**:
   - Future lessons will cover the usage and functionality of key HTML tags.

1. **HTML Overview**: HTML stands for Hypertext Markup Language and is used to define the content and structure of a website.
2. **Browser Function**: Browsers like Chrome, Safari, and Brave render HTML, CSS, and JavaScript files to display websites.
3. **Tags and Elements**: Tags are enclosed in angle brackets (e.g., `<h1>`) and come in pairs with an opening tag (`<h1>`) and a closing tag (`</h1>`). The content and the tags together form an element.
4. **Heading Tags**: HTML provides six levels of headings, from `<h1>` (most important) to `<h6>` (least important), used to create a hierarchical structure.
5. **Importance of Headings**: Headings help organize content, similar to the hierarchy in a table of contents in a book.
6. **Coding Practice**: Always use one `<h1>` per page, as it represents the top-level heading. Subsequent headings should follow in order (e.g., `<h2>`, `<h3>`).
7. **Exercise Example**: Create an HTML file with various heading levels to structure content. The goal is to understand the hierarchical use of heading tags.
8. **Live Preview**: Use the Live Preview extension in VS Code to see real-time updates of your HTML code.
9. **File Management**: Create a dedicated folder for Web Development Projects and ensure you extract downloaded resources properly.
10. **VS Code Setup**: Open the project folder in VS Code to begin editing the HTML files. Save changes frequently to see updates.
11. **Practical Challenge**: Modify provided HTML code to include correct heading tags, ensuring proper hierarchy and formatting.
12. **Best Practices**: Avoid skipping heading levels (e.g., don't go from `<h1>` to `<h3>` without an `<h2>`). This maintains a clear and logical structure.
13. **Documentation**: Refer to the Mozilla Developer Network (MDN) Web Docs for detailed information on HTML elements and best practices.
14. **Future Lessons**: Upcoming lessons will cover other important HTML elements, such as the paragraph element, and further explore web development.
15. **Learning Approach**: Experiment with code, make mistakes, and learn from them. The goal is to build a solid understanding of HTML fundamentals.

### Short note

1. **Paragraph Element**: The paragraph element `<p>` is used to define paragraphs in HTML, ensuring text is properly separated and formatted.
2. **Tag Structure**: Similar to headings, paragraph elements have an opening tag `<p>` and a closing tag `</p>`.
3. **Plain Text Issue**: Without paragraph tags, text runs together on a single line, making it difficult to distinguish between paragraphs.
4. **Accessibility**: Paragraph tags are essential for screen readers, helping visually impaired users navigate content more easily.
5. **Exercise Overview**: Download and extract the provided exercise files, open the index.html file in VS Code, and use paragraph tags to format text.
6. **Live Preview**: Use the Live Preview extension in VS Code to see real-time updates of your HTML code.
7. **Formatting Text**: Insert `<p>` tags around each paragraph to separate them clearly on the webpage.
8. **Lorem Ipsum**: Placeholder text used in web design to simulate real content. It's derived from classical Latin literature by Cicero.
9. **Placeholder Text Tools**: Websites like lipsum.com generate Lorem Ipsum text in various languages and formats.
10. **Novelty Placeholder Texts**: Alternatives like baconipsum.com and broipsum.com generate themed placeholder text for fun.
11. **Customization Challenge**: Generate your own Lorem Ipsum text and use it to create an article with properly formatted paragraphs.
12. **Engagement**: Share interesting or funny Lorem Ipsum generators in the Q&A sections for community engagement.
13. **Learning Resources**: Refer to the Mozilla Developer Network (MDN) Web Docs for more information on HTML elements and best practices.
14. **Best Practices**: Follow proper tag structure and hierarchy in HTML to ensure clarity and accessibility.
15. **Upcoming Lessons**: Future lessons will cover additional HTML elements and their applications in web development.

1. **Void Elements Definition**: Void elements in HTML, such as `<hr>` and `<br>`, do not have closing tags and cannot contain any content between their tags.
   
2. **Tag Structure**: Void elements are self-closing, indicated by a forward slash before the closing angle bracket (e.g., `<hr />`, `<br />`).

3. **Differentiation from Non-Void Elements**: Unlike non-void elements like `<p>` or `<h1>`, void elements cannot contain text or other elements inside them.

4. **Purpose of Horizontal Rule (`<hr>`)**: Used to create a thematic break or divider between content sections on a webpage, enhancing readability and structure.

5. **Purpose of Line Break (`<br>`)**: Inserts a line break within a paragraph, useful for formatting text where content should appear on separate lines without starting a new paragraph.

6. **Exercise Overview**: Downloaded exercise files typically include existing content needing formatting using void elements to achieve proper structure and readability.

7. **Formatting Address**: Example used an address within a `<p>` tag where `<br>` elements were used to separate lines of the address, maintaining its single paragraph nature.

8. **Adding Horizontal Rule**: Placed `<hr>` to visually separate different content sections, providing clarity and organization to the webpage layout.

9. **Validation and Best Practices**: Emphasized creating new `<p>` tags for separate paragraphs instead of relying solely on `<br>` for line breaks to enhance accessibility, particularly for screen readers.

10. **Optional Closing Tag**: Mentioned that HTML5 allows omitting the closing slash (`<hr>` instead of `<hr />`), but recommended including it for clarity and consistency in code readability.

11. **Tips for Checking Code**: Suggested using tools like diffchecker.com to compare your code with the provided solution to catch syntax errors or discrepancies in formatting.

12. **Preference for Readability**: Encouraged using the standard `<tag />` format for void elements to avoid confusion and ensure clear distinction from non-void elements in HTML code.

13. **HTML5 Compatibility**: Noted HTML5's tolerance for omitting closing slashes on void elements but advocated for including them for developer clarity.

14. **Conclusion**: Void elements serve crucial roles in structuring HTML documents by defining breaks and separators, optimizing both visual presentation and accessibility for users.

### Sumarry of key points

1. **Types of Lists in HTML**:
   - **Ordered List (`<ol>`)**: Used for lists where the order of items is important. Each list item is numbered automatically.
   - **Unordered List (`<ul>`)**: Used for lists where the order of items does not matter. Items are usually marked with bullets.
   - **Description List (`<dl>`)**: Used for lists of terms and their descriptions. Each term is enclosed in `<dt>` (description term) and its description in `<dd>` (description detail).

2. **Ordered List (`<ol>`)**:
   - **Syntax**:
     ```html
     <ol>
       <li>First item</li>
       <li>Second item</li>
       <li>Third item</li>
     </ol>
     ```
   - **Attributes**:
     - `type`: Defines the type of numbering (e.g., `1`, `A`, `a`, `I`, `i`).
     - `start`: Specifies the starting number.
     - `reversed`: Reverses the order of numbering.

3. **Unordered List (`<ul>`)**:
   - **Syntax**:
     ```html
     <ul>
       <li>Item one</li>
       <li>Item two</li>
       <li>Item three</li>
     </ul>
     ```
   - **Attributes**:
     - `type`: Defines the type of bullet (e.g., `disc`, `circle`, `square`).

4. **Description List (`<dl>`)**:
   - **Syntax**:
     ```html
     <dl>
       <dt>Term 1</dt>
       <dd>Description for term 1</dd>
       <dt>Term 2</dt>
       <dd>Description for term 2</dd>
     </dl>
     ```
   - **Usage**: Ideal for creating glossaries or lists of questions and answers.

5. **Nested Lists**:
   - Lists can be nested inside each other for more complex structures.
   - **Example**:
     ```html
     <ul>
       <li>Item one
         <ul>
           <li>Sub-item one</li>
           <li>Sub-item two</li>
         </ul>
       </li>
       <li>Item two</li>
     </ul>
     ```

6. **Accessibility Considerations**:
   - Use appropriate list types to ensure content is meaningful and accessible.
   - Screen readers rely on list semantics to interpret content correctly.

7. **Examples of List Customization**:
   - **Custom Bullets**:
     ```html
     <ul type="square">
       <li>Square bullet item</li>
     </ul>
     ```
   - **Custom Numbering**:
     ```html
     <ol type="A" start="3">
       <li>Third item</li>
       <li>Fourth item</li>
     </ol>
     ```

8. **Semantic HTML**:
   - Using the correct list type enhances the semantic structure of HTML, making it easier to understand and maintain.

9. **Practical Uses**:
    - **Ordered Lists**: Step-by-step instructions, ranking items.
    - **Unordered Lists**: Grouping related items, menu lists.
    - **Description Lists**: Glossaries, FAQs, metadata.

By using the appropriate list element and attributes, you can effectively organize and present content in a clear and accessible manner.

### Notes on Nesting and Indentation in HTML

1. **Nesting in HTML**:
   - **Definition**: Nesting refers to placing one HTML element inside another element. This is commonly used for structuring lists, forms, tables, and other complex layouts.
   - **Syntax**:
     ```html
     <parent-element>
       <child-element>
         <nested-child-element>
         </nested-child-element>
       </child-element>
     </parent-element>
     ```
   - **Example**:
     ```html
     <ul>
       <li>Item 1
         <ul>
           <li>Subitem 1.1</li>
           <li>Subitem 1.2</li>
         </ul>
       </li>
       <li>Item 2</li>
     </ul>
     ```

2. **Indentation in HTML**:
   - **Purpose**: Indentation improves the readability of HTML code by visually representing the nested structure.
   - **Best Practices**:
     - Use consistent indentation (commonly 2 or 4 spaces per level).
     - Avoid mixing spaces and tabs.
     - Indent child elements inside their parent elements.
   - **Example**:
     ```html
     <div>
       <p>This is a paragraph.</p>
       <ul>
         <li>Item 1</li>
         <li>Item 2</li>
       </ul>
     </div>
     ```

3. **Nesting Lists**:
   - **Nested Ordered Lists**:
     ```html
     <ol>
       <li>First item
         <ol>
           <li>First subitem</li>
           <li>Second subitem</li>
         </ol>
       </li>
       <li>Second item</li>
     </ol>
     ```
   - **Nested Unordered Lists**:
     ```html
     <ul>
       <li>Item 1
         <ul>
           <li>Subitem 1.1</li>
           <li>Subitem 1.2</li>
         </ul>
       </li>
       <li>Item 2</li>
     </ul>
     ```

4. **Combining Ordered and Unordered Lists**:
   - **Example**:
     ```html
     <ul>
       <li>Unordered Item 1
         <ol>
           <li>Ordered Subitem 1.1</li>
           <li>Ordered Subitem 1.2</li>
         </ol>
       </li>
       <li>Unordered Item 2</li>
     </ul>
     ```

5. **Nesting Other HTML Elements**:
   - **Nesting in Forms**:
     ```html
     <form>
       <fieldset>
         <legend>Personal Information</legend>
         <label for="name">Name:</label>
         <input type="text" id="name" name="name">
       </fieldset>
     </form>
     ```
   - **Nesting in Tables**:
     ```html
     <table>
       <tr>
         <td>
           <table>
             <tr>
               <td>Nested Table Cell</td>
             </tr>
           </table>
         </td>
       </tr>
     </table>
     ```

6. **Considerations for Nesting and Indentation**:
   - **Readability**: Proper nesting and indentation make the code easier to read and maintain.
   - **Validation**: Ensure all tags are properly closed and nested according to HTML specifications to avoid validation errors.
   - **Accessibility**: Correctly nested elements enhance the accessibility of the web page, making it easier for screen readers to interpret the content.

By following these guidelines, you can create well-structured and readable HTML documents that are easy to maintain and understand.

### Anchoer element 
### Notes on Anchor Element and Attributes in HTML

#### 1. **Anchor Element (`<a>`)**
   - **Definition**: The anchor element (`<a>`) is used to create hyperlinks, which are clickable links that navigate to other web pages, files, or sections within the same page.
   - **Syntax**:
     ```html
     <a href="URL">Link Text</a>
     ```

#### 2. **Attributes of Anchor Element**
   - **`href`**:
     - **Description**: Specifies the URL of the page the link goes to.
     - **Example**:
       ```html
       <a href="https://www.example.com">Visit Example</a>
       ```
   
   - **`target`**:
     - **Description**: Specifies where to open the linked document.
     - **Values**:
       - `_self`: Default. Opens in the same frame/tab as it was clicked.
       - `_blank`: Opens in a new tab or window.
       - `_parent`: Opens in the parent frame.
       - `_top`: Opens in the full body of the window.
     - **Example**:
       ```html
       <a href="https://www.example.com" target="_blank">Visit Example in New Tab</a>
       ```

   - **`rel`**:
     - **Description**: Specifies the relationship between the current document and the linked document.
     - **Values**:
       - `nofollow`: Tells search engines not to follow the link.
       - `noopener`: Prevents the new page from accessing the `window.opener` property.
       - `noreferrer`: Prevents the browser from sending the HTTP referer header.
     - **Example**:
       ```html
       <a href="https://www.example.com" target="_blank" rel="noopener noreferrer">Secure Link</a>
       ```

   - **`title`**:
     - **Description**: Provides additional information about the link, often displayed as a tooltip when the mouse hovers over the link.
     - **Example**:
       ```html
       <a href="https://www.example.com" title="Visit Example Website">Visit Example</a>
       ```

   - **`download`**:
     - **Description**: Specifies that the target will be downloaded when a user clicks on the hyperlink. The value of the attribute will be the name of the downloaded file.
     - **Example**:
       ```html
       <a href="path/to/file.pdf" download="example.pdf">Download PDF</a>
       ```

   - **`hreflang`**:
     - **Description**: Specifies the language of the linked document.
     - **Example**:
       ```html
       <a href="https://www.example.com" hreflang="en">Visit English Example</a>
       ```

   - **`type`**:
     - **Description**: Specifies the media type of the linked document.
     - **Example**:
       ```html
       <a href="https://www.example.com/file.pdf" type="application/pdf">Open PDF</a>
       ```

#### 3. **Special Uses of Anchor Element**
   - **Linking to Sections Within the Same Page**:
     - **Description**: Uses an anchor (`id`) to link to a specific section within the same page.
     - **Example**:
       ```html
       <a href="#section1">Go to Section 1</a>
       ...
       <h2 id="section1">Section 1</h2>
       ```

   - **Email Links**:
     - **Description**: Creates a link that opens the user's email client with a pre-filled email address.
     - **Example**:
       ```html
       <a href="mailto:example@example.com">Send Email</a>
       ```

   - **Telephone Links**:
     - **Description**: Creates a link that initiates a phone call on devices that support telephony.
     - **Example**:
       ```html
       <a href="tel:+1234567890">Call Us</a>
       ```

#### 4. **Styling and Interaction**
   - **CSS Styling**:
     - **Description**: Anchor elements can be styled using CSS to change their appearance (color, font, decoration).
     - **Example**:
       ```html
       <style>
         a {
           color: blue;
           text-decoration: none;
         }
         a:hover {
           text-decoration: underline;
         }
       </style>
       <a href="https://www.example.com">Styled Link</a>
       ```

   - **Interactive States**:
     - **Description**: Anchor elements have several interactive states that can be styled separately: `:link`, `:visited`, `:hover`, `:active`.
     - **Example**:
       ```html
       <style>
         a:link { color: blue; }
         a:visited { color: purple; }
         a:hover { color: red; }
         a:active { color: green; }
       </style>
       <a href="https://www.example.com">Interactive Link</a>
       ```

By understanding and utilizing these attributes and features of the anchor element, you can create effective and user-friendly hyperlinks in your web pages.

### ol attributes
### Notes on Attributes of `<ol>` Tag in HTML

#### 1. **Ordered List (`<ol>`)**
   - **Definition**: The ordered list element (`<ol>`) is used to create a list of items where the order or sequence is important. Each item within an `<ol>` is typically represented using the `<li>` (list item) element.
   - **Syntax**:
     ```html
     <ol>
       <li>First item</li>
       <li>Second item</li>
       <li>Third item</li>
     </ol>
     ```

#### 2. **Attributes of `<ol>` Tag**

   - **`type`**:
     - **Description**: Specifies the kind of marker to use in the list.
     - **Values**:
       - `1`: Decimal numbers (default).
       - `A`: Uppercase letters.
       - `a`: Lowercase letters.
       - `I`: Uppercase Roman numerals.
       - `i`: Lowercase Roman numerals.
     - **Example**:
       ```html
       <ol type="A">
         <li>First item</li>
         <li>Second item</li>
         <li>Third item</li>
       </ol>
       ```

   - **`start`**:
     - **Description**: Specifies the start value of the first list item.
     - **Example**:
       ```html
       <ol start="5">
         <li>Fifth item</li>
         <li>Sixth item</li>
         <li>Seventh item</li>
       </ol>
       ```

   - **`reversed`**:
     - **Description**: Specifies that the list order should be descending (9, 8, 7, ...).
     - **Example**:
       ```html
       <ol reversed>
         <li>First item</li>
         <li>Second item</li>
         <li>Third item</li>
       </ol>
       ```

   - **`compact`** (Deprecated):
     - **Description**: Was used to reduce the spacing between list items. This attribute is no longer supported in HTML5 and should be avoided.