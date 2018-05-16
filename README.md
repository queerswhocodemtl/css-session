# CSS Session

## Basic syntax

### In HTML file

```
<div class=”class-name”> ... </div>

<div id=”id-name”> ... </div>
```

### In css file
```
.class-name {
    property-name: value; 
}

#id-name {
    property-name: value; 
}

Example:
.title {
   color: #4286f4;
   font-decoration: underline; 
}
```

-----

## Before starting

* Clone repository: 
`git clone git@github.com:queerswhocodemtl/css-session.git`

* Create a branch from `master` named: 
`git checkout -b css-session/johndoe`, where `johndoe` is your github username

* When your exercices are finished push your code and create a pull request from your branch into `master`
```
git commit -m “CSS session”
git push --set-upstream origin css-session/johndoe (if first time)
git push (if it’s not first time you push on your branch)
```


## First Exercise

In `index.html`, after the last comment add:

* A paragraph (`p` tag) that contains the following text: _This is a test with HTML in bold without css_ and where the word **HTML** is actually bold without css 
  * Surround the word with `b` tag
* A paragraph that contains the following text: _This is a test where there is a word in red_ and where _red_ is in red color:
  * Surround the _red_ word with a `span` tag and add a css class called `my-color`
  * Update `styles.css` file and add the proper css for this class
* A paragraph that contains the following text: _This is a test where the font color is white and the background color is red_
  * Add a class named `my-custom-class` to the paragraph
  * Update `styles.css` and add the proper css for this class

  ### Reference

  * [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)


