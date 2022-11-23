# LIGHTING-JEK

## Run the project
* `jekyll serve`

## Work flow

#### Adding a specific theme for a post or page
To get or display data in the browser we will have to add a line of code for each and every main page in out website.

`---`
`layout: post` -> this is the layout name
`title: home` -> the mage name
`permalink: /home` -> the link
`---`

#### How to add a new page
To add a new page we will have to create the page in the root folder of the theme. And to access that specific page we will have to...

`http://127.0.0.1:4000/about.html`

If you have a lot of files you can add them in a sub folder. but the the url will change to something like this.

`http://example.com/design/draft.html`

You can specify a permalink if you need to change the URL.