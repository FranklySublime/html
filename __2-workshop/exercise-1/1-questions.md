# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [False] `<div><span>hello</div></span>`
Fixed : `<div><span>hello</span></span>`

b) [False]

```html
<ul>
<li>one</li>
</ol>
```

Fixed : 
```html
<ul>
<li>one</li>
</ul>

c) [False] `<ul></ul><img/><ol><li>one</li></ol>`

Fixed:
```html
<ul>
<img/>
<ol>
<li>one</li>
</ol>
</ul>

## Q2 - What is a screenreader and why should we care about them?

A screen reader is an accessibility tool for the visually impaired that allows them text on screen to be read out to them through either their speakers or their headphones.
This is important for us because screenreaders pick up text from the `<p>` tags versus if we were to use the `<div>` tag.


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

### You will most likely need the following tags: `<html>`, `<h1>`, `<h2>`, `<p>`, but most importantlly `<img>` with src and alt attributes

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

### you will need `<html>`, `<li>`, `<ul>`, `<ol>`, and `<a>` with an href attribute

c) You want to sell designer hats. You need to receive orders from the user.

### you will need `<html>`, `<li>`, `<ul>`, `<ol>`, and `<a>` with an href attribute to link to your secured checkout pages, and a `<button>` tag to confirm the payment.

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No. This is because a button's decendants cannot be clickable

## Q5 - What is the most generic tag you can use?

`<div>`

## Q6 - What do the following achronyms stand for?

a) `a`

anchor

b) `ol`

ordered list

c) `ul`

unordered list

d) `li`

list

e) `tr`

table row

f) `th`

table head

g) `td`

table data

## Q7 - Usually, `td` elements are children of what kind of elements?

`tr`

## Q8 - What is the difference between td and th?

The `th` is usually a cell in the first row of the table to indicate the header of a column, whereas `td` is typically a specific cell that could be found in any row `<tr>.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1 typically displays bigger text than h3. However, there are better styling options that can be used with CSS to make text bigger or bolder with more oomph.

## Q10 - In which situation can you use self closing tags?

When the tag doesn't require any text to be input within the tag before closing

## Q11 - What is autofilling and why is it important?

Autofilling is important because it helps save time for conveniance sake.

## Q12 - Which attributes are always present in an img element?

The atributes always present are the `src` and `alt`

## Q13 - Which attribute is always present for an anchor tag?

The attribute that is alwayus present for an anchor tag would be `href`
