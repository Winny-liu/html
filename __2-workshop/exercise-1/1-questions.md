# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ hello ] `<div><span>hello</div></span>`

NO

b) [ so making some new changes ]

```html
<ul>
<li>one</li>
</ol>
```
NO

c) [ ] `<ul></ul><img/><ol><li>one</li></ol>`

NO

## Q2 - What is a screenreader and why should we care about them?

Screen readers are able to look for and process any kind of text that is displayed on the screen of a computer or mobile device, including website content, icon labels, documents, spreadsheets, file menus and more


A screen reader allows people who are blind or visually impaired to use their computer. ... It has been written to help people determine which is the most appropriate for their needs and includes summary information about the screen readers built into the operating system alongside other free or commercial products.



_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

IMG

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

a li

c) You want to sell designer hats. You need to receive orders from the user.

button ul li

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

NO

A submit button and a submit input ( <input type="submit"> ) are identical in functionality, but different in the sense that an input is unable to contain child elements while a button can.





## Q5 - What is the most generic tag you can use?


the link tag


## Q6 - What do the following achronyms stand for?

a) `a` Anchor, a, tags are for links on a website. They always have an href attribute which corresponds to the destination address.



b) `ol`The ol ("Ordered List") tag is for numbered lists. The children of a ol element should be li elements, same as ul.

c) `ul`The ul tag is for bullet point lists. The children of a ul element should be li elements

d) `li`The li tag is for list elements. The parent of an li element should be a ul or ol element.



e) `tr`tr defines a new table row. Its children are td or th elements.

f) `th`A table cell. Usually placed in the first row. Indicates that it is the header of the column in the table.

g) `td`A table cell. It is always the child of a tr element.

## Q7 - Usually, `td` elements are children of what kind of elements?
tr

## Q8 - What is the difference between td and th?

The TH and TD elements are used for table cells. TH is used for table header cells while TD is used for table data cells. This distinction gives user agents a means to render such cells distinctly, for instance by using a larger or heavier font for header cells. It is also needed when rendering to speech.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1

## Q10 - In which situation can you use self closing tags?

Some closing tags are optional, however. The tags are optional because it’s implied that a new tag would not be able to be started without closing it. These are the following:
html, head, body, p, dt, dd, li, option, thead, th, tbody, tr, td, tfoot, colgroup. There are also tags that are forbidden to be closed: img, input, br, hr, meta, etc.


## Q11 - What is autofilling and why is it important?
Autofill is a software function that automatically enters data in web forms and spreadsheets.

It's understandable why web developers haven't paid much attention to autofill. When you're filling out forms with test data on a regular basis, autofill tends to get in the way. But autofill is an important feature for our users. Google has found that “users complete forms up to 30% faster” when using autofill.

## Q12 - Which attributes are always present in an img element?

src

## Q13 -Which attribute is always present for an anchor tag?
href
