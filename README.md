## OpenXML Elements

### document.xml

- `<p>`: paragraph
- `<rPr>`:
- `<r>`: "runs" or, text sequence, inside a paragraph that contains no other element (e.g., bold, table, italics, etc)
- `<t>`: the text inside an `<r>`
- `<b />` & `<bCs />`: both were added when I set some text to be bold
- `<proofErr>`: warnings about grammar issues and similar
- `<t xml:space="preserve">` looks like the primitive used to keep spaces around

### settings.xml

- `<proofState>`: holds things like current state of grammar and spelling

### Random Notes

- It is "interesting" that they decided to keep highlights about grammar and spelling issues on the `document.xml` file. After adding a table to evaluate the changes, a lot of grammar and spelling issues were highlighted (because I'm using lorem ipsum), encapsulating every single word inside its own `<r>`.
- Will we have issues with fonts? For example, if they use some custom font or font that is not trivial to find?