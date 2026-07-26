# Query String Parameters

QueryString specify a set of values that specify parameters from a part of a web address (URL) and passes them to a web server.



https://example.com/page.html?key=value&key=value%20value



1. **Question mark (?)** is used to start the query string.
2. **Ampersand (&)** is used to separate multiple key-value pairs within the query string.
3. **Equal sign (=)** is used to separate the key from the value within each key-value pair.



The special characters are used to represent spaces, other special characters (as @) for the query string. URLs use the ASCII character-set, so we must use it to some exploit actions such as server-side parameter pollution:




| Item                 | Encoding |
| -------------------- | -------- |
| space                | %20      |
| hashtag #            | %23      |
| monetary symbol $$$$ | %24      |
| percentage %         | %25      |
| plus +               | %2B      |



See more in [HTML URL Encoded Characters Reference](https://www.freecodecamp.org/news/url-encoded-characters-reference/)
