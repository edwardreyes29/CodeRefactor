# My Contribution
Edward Reyes

So I added sectioning elements such as `<nav>`, `<section>`, and `<aside>` where I thought were appropriate. I also included semantic elements like `<header>`, `<article>`, `<main>`, and `<footer>` following the guidelines specified from W3.org: https://www.w3.org/TR/html52/. From my understanding, the sectioning elements gives more semantic meaning to html pages, allowing programs to have a better understanding of the html document. The semantic elements describe the purposes of elements and types of content inside them. 

I have also implemented WAI-ARIA landmark roles which according to the w3.org specifications (https://www.w3.org/TR/wai-aria-1.1/#landmark_roles) are "regions of the page intended as navigational landmarks." Doing this should allow assistive technologies, such as screen readers, to convey appropriate information to those who have disabilities.

On the images on this document, I've added alt tags for screen readers as well that describe the images displayed as detailed as possible.


# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
