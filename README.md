<h1>Post.js</h1>

<h4> Previously known as Fort.js </h4>

All you do is add the form and Post.js will take care of the rest. Best of all, it's super small. [Check out the demo!](https://idriskhenchil.github.io/)

## Usage
Using Post is so simple, it's simple. All you do is insert `post.min.js` and `post.min.css` into the `<head>` then pop in an `<input>` into `<div class="form">`. Anything outside of the `<div>` won't count. Now you just call the effect (Scroll down to the the "Effects" section for more). Yep, that's all there is to it. Post does the rest.
```html
<head>
  <script src="post.min.js"></script>
  <link rel="stylesheet" href="post.min.css">
</head>
<body>
<div class="form">
  <form method="post">
    <input type="text">
  </form>
</div>
  <script>
      Post.flash("#009DFF", "#000", "#6638F0");
  </script>
</body>
```

**Certain fields:**

If you want to include only certain fields add a class named `ignore` to the field. Post will not detect the field after you do so.
## Effects
 * [Default](http://idriskhenchil.github.io/index.html) - `solid()`
 * [Gradient](http://idriskhenchil.github.io/gradient/index.html) - `gradient()`
 * [Sections](http://idriskhenchil.github.io/sections/index.html) - `sections()`
 * [Flash](http://idriskhenchil.github.io/flash/index.html) - `flash()`
 * [Merge](http://idriskhenchil.github.io/merge/index.html) - `merge()`

**Changing the colors:**
* Solid - `Post.solid("#009DFF")` Keepin' it simple

* Gradient - `Post.gradient("#009DFF", "#47B9FF")` Note that only two values should be passed.

* Sections - `Post.sections("#009DFF", "#4AF2A1", "#FB5229")` The more colors you add, the more sections you get!

* Flash - `Post.flash("#009DFF", "#000", "#6638F0");` Old school, yet unique.

* Merge `Post.merge("#009DFF");` *Tip*: Add a few more colors and see what you get (Not 100% tested)

## Custom Configuration
Post.js now supports custom configuration, which offers the following properties

`height`: Height in any CSS notation

`duration`: Any time like '3s' or '200ms'

`alignment`: Bottom or top

**Example**

    Post.config({
    	height: '20px',
    	duration: '3s',
    	alignment: 'bottom'
    })
    
**Please note an effect must also be selected**

## Browser Support
 * Safari 7.0 
 * Opera 21 
 * Mozila Firefox 29 and up
 * Google Chrome 34 and up
 * Internet Exporer 8.0 and up 
 
## Coming soon
 * More effects. Have an idea? [Twitter](https://www.twitter.com/idriskhenchil) me!

## License
Post.js is licensed under the MIT license (http://opensource.org/licenses/MIT)
It's pretty simple, but here's the definition we get

The MIT License is a permissive license that is short and to the point. It lets people do anything they want with your code as long as they provide attribution back to you and don't hold you liable.
## Acknowledgements

**Post.js** is authored and maintained by [Idris Khenchil](https://www.twitter.com/idriskhenchil),
feel free to check out the demo [here](http://idriskhenchil.github.io/index.html). Used Post in a project? I'd love to see it, [Twitter](https://www.twitter.com/idriskhenchil) me.

