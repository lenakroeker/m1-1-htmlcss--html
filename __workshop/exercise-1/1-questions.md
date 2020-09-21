# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [true] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

A screen reader is a technology that Interprets web content into audio for visually impared people.
We should be concious of using the most appropriate tags for content in order to make it easier for people using screen readers to navigate the page.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
  <img/>
b) You want to create a website that lists all the art gallery websites in your city and links to their website.
 <ul></ul> *or* <ol></ol>, <a></a>
c) You want to sell designer hats. You need to receive orders from the user.
  <form></form>, <input></input>
## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
  No, because interactive content cannot have descendants.
## Q5 - What is the most generic tag you can use?
  <div></div>
## Q6 - What do the following achronyms stand for?

a) `a` 
    - anchor
b) `ol`
    - ordered list
c) `ul`
    -unordered list
d) `li`
    -list item
e) `tr`
    -table row
f) `th`
    -table header
g) `td`
    -table data
## Q7 - Usually, `td` elements are children of what kind of elements?
    tr
## Q8 - What is the difference between td and th?
    th contains the title of a column, td contains the data in a row
## Q9 - Which tag makes the text appear bigger: h1 or h3?
  <h1></h1>
## Q10 - In which situation can you use self closing tags?
    tags which have no content
     (ex. <iframe/>)
## Q11 - What is autofilling and why is it important?
    autocomplete(?) allows browsers to predict values for input fields based on previously entered values. It makes filling out forms super easy and reduces the amount of time people have to change their mind about it!
## Q12 - Which attributes are always present in an img element?
      src, alt, width, height
## Q13 - Which attribute is always present for an anchor tag?
href=""
