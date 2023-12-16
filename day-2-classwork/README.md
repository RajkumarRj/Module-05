Hosted link : 




1. **HTML Structure:**
   - The document type (`<!DOCTYPE html>`) is specified, and the HTML document has an English language declaration (`<html lang="en">`).
   - The meta tags define the character set (`UTF-8`) and viewport settings.
   - The title of the web page is set to "Day-2-Classwork."

2. **Script Loading:**
   - External scripts for React, ReactDOM, and Babel standalone are loaded from CDN (Content Delivery Network) sources. These scripts are necessary for using React and JSX in the browser.

3. **Body Content:**
   - The body of the HTML document contains an `<h1>` element with the text "Hello" and an empty `<div>` with the ID "root." This div will be the target for rendering React components.

4. **JavaScript Section:**
   - The script type is set to "text/babel," indicating that the content inside should be treated as JSX and transpiled by Babel.
   - The `ReactDOM.createRoot` method is used to create a root instance.
   - JSX syntax is employed to define the structure of the web page within the `page` constant.
   - The `createRoot` instance's `render` method is used to render the JSX content into the specified "root" div.
