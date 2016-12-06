Run the index.html file directly in Chrome or any other browser.
There will be two sections of forms, One is developed with core java script and second one is using React API.
Try to enter the value into the text fields of both where you will see the actual difference.
Whole Core Javascript form will re-render for every second when the time changes.
Where as React form will re-render the specific part of the page as it compares the previous html tree with new html tree in browser DOM and writes only the difference in browser DOM. This where you will see the power of Virtual DOM concept.
