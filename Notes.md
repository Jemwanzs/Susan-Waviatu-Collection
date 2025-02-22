<!--PUBLISH AND HOST-->
1. git init <If your project isn’t already a Git repository, initialize it by running this>
2. git add . <Add all your files to the staging area>
3. git commit -m "initial commit" <Commit your changes>
4. git remote add origin <your-repo-url> [link your local project to the GitHub repository by attaching the URL here
5. git push -u origin main <Push your local project to GitHub>


THEN <!--Deploy Your Project on Netlify-->













RATINGS (for items)
Google search:
    <font awesome 4 cdm (
        copy the link and connect it in your html
    )
    <font awesome 4 icons(
        search for 'star icon'
    )

[Make the website responsive:]
    Add menu icon
    Adjust code appropreately
    center akign for smaller screen


HOME page complted;
    now code the <products page>
    Then:
    <Single product page>
    Next create;
    <Cart page>
    Finally;
    <Account page>


NOTE:
    <EmailJS>
    Used emailjs.com to submit forms' data
    USER_ID: <service_ra9936u>
    SERVICE_ID: <service_ra9936u>
    TEMPLATE_ID: <template_yhulkir>




PROTECTION <CODE>
Protecting your React app or website code from being copied when viewed through the browser's developer tools (like Inspect) is challenging because the web's open nature inherently allows users to access the HTML, CSS, and JavaScript that make up the front end of your site. However, there are some strategies to make it more difficult for users to copy or tamper with your code:

1. Minification and Obfuscation
Minification: Compress your JavaScript, CSS, and HTML files to reduce file size, making the code harder to read. Tools like Webpack, UglifyJS, and Terser can help with this.
Obfuscation: Use a JavaScript obfuscator to rename variables and functions to random strings, making the code less understandable. Tools like JavaScript Obfuscator can be used for this purpose.
2. Disable Right-Click and Keyboard Shortcuts
Disabling right-click, keyboard shortcuts like Ctrl+U (view source), Ctrl+Shift+I (open DevTools), etc., can deter casual users, though it won't stop someone determined.
javascript



Copy code


<document.addEventListener('contextmenu', (e) => {
    <e.preventDefault();
});

<document.addEventListener('keydown', (e) => {
    <if (e.ctrlKey && (e.key === 'u' || e.key === 'i' || e.key === 'c')) {
        e.preventDefault();
    }
});




Note: These methods can degrade user experience and can be easily bypassed.

3. Use Server-Side Rendering (SSR)
With SSR, much of the processing is done on the server, sending only the final HTML to the client, making it harder for users to access the original code. Frameworks like Next.js can help implement SSR in your React app.
4. Code Splitting and Lazy Loading
Break your app into smaller chunks and load them only when needed. This approach can help limit access to the entire codebase at once.
5. Content Protection Services
Some services offer protection mechanisms to prevent scraping and unauthorized copying of your content. Services like Cloudflare offer basic protection mechanisms, though these are not foolproof.
6. Watermarking and Logging
Inject watermarks into your content or track suspicious activities. For example, you could dynamically insert unique identifiers in your code to track where leaks occur.
7. Legal Notice
Include a legal notice or copyright statement in your code, stating that unauthorized use or reproduction of the code is prohibited.
8. Backend Validation
Always ensure that critical business logic, sensitive data processing, and validation are done server-side, as front-end protection can only go so far.
Important Considerations:
User Experience: Some of these methods can negatively impact user experience, so use them sparingly and thoughtfully.
Not Foolproof: No method can completely prevent a determined user from copying your code. The goal is to make it more challenging, not impossible.
Would you like to implement any of these methods or discuss further on how to apply them?