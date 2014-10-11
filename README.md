#tinyisbn

Transforms unwieldy ISBNs into short, hashtaggable codes, or annotags. 

#Introduction

TinyISBN is a simple web app that transforms text identifiers like ISBNs into short, hashtaggable codes, or annotags, suitable for use in microblogging with services like Twitter. Annotags can be used in conjunction with page numbers and paragraph numbers to annotate passages of a book or etext. In this way, decentralized discussion can take place in the virtual margins of a text. The anatomy of an annotag is simple: 

![annotag diagram](http://jonreeve.com/images/annotags/annotag-diagram.jpg)

The first letter declares the type of the book code to follow--encoded ISBN, Google Books ID, or OCLC number. The next chracters represent the book or text, and the characters following the colon are a human-readable notation for a specific text location. A more complete specification is available on the [introductory blog post](http://jonreeve.com/projects/annotags/about.html).  
