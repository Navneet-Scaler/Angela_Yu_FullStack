
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

