# Local Storage

## Why would a developer use local storage for a web application?

Local storage allows developers to store and retrieve data in the browser. The data stored in local storage will not expire. This means the data will persist even if the tab or the browser window is closed
https://www.section.io/engineering-education/how-to-use-localstorage-with-javascript/#:~:text=Local%20storage%20allows%20developers%20to,the%20browser%20window%20is%20closed.

## What information should not be stored in local storage?

Personally Identifiable Information (PII), authentication tokens, user locations and API keys, etc., should never be stored in the local storage.
https://www.horangi.com/blog/misuse-of-local-storage#:~:text=Given%20the%20potential%20vectors%20where,stored%20in%20the%20local%20storage.

## Local storage can store what type of data? How would you convert it to that type before storing?

localStorage can store only strings. Even if you need to store an integer you need to convert it into a string and have to store it.
https://javascript.plainenglish.io/storing-different-datatypes-in-localstorage-in-js-ee7f4c5318ff#:~:text=Literally%2C%20localStorage%20can%20store%20only,and%20have%20to%20store%20it.
