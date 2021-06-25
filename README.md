# Mastering Markdown

_When you can't do something in Markdown, you can just write regular HTML and it is going to work_

## Paragraphs 

Lanre is a front end developer and also a web designer. 

Markdown needs a full line space in between each line of texts in order to become a paragraph element.

## Text Decoration

This is a **bold** text, this is also a __bold__ text.

This is an *emphasized* text, this is also an _empasized_ text.

I prefer using **double asterisk** for bold and _single set of underscore_ for italics because I don't want to ever mess things up.

This is a ~~strike-through~~ text using double set of tilde.


## Creating + Linking Headings
The best way to do headings in markdown is by using the hash or pound (#) sign:
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


The second method only works for headings 1 and 2 by using (=) for heading 1 and (-) for heading 2 underneath the texts:

Heading 1
=============

Heading 2
-------------


## Links
There are four ways we can write links in markdown:
1. https://google.com or <https://google.com>

2. Heare are links to my works:
   - [My GitHub Account](https://github.com/lanre-waju)
   - [My Medium Account](https://lanrewaju.medium.com/) 
   - [My LinkedIn Account](https://www.linkedin.com/in/lanrewaju/)
   - [My Codepen Account](https://codepen.io/lanrewaju)
   - [My Twitter Account](https://twitter.com/lanre__waju)
   - [My Dev.to Account](https://dev.to/lanrewaju)
   - [My Hashnode Account](https://hashnode.com/@Lanre_waju)
   - [My Facebook Account](https://www.facebook.com/tonialanre)
   - [My Instagram Account](https://www.instagram.com/lanre__waju/)
   - [My Figma Account](https://www.figma.com/lanrewaju/)
   - [My Dribbble Account](https://dribbble.com/Lanre__waju)

We can also add title attributes to our links, like so:

[Google](https://google.com "This takes you to google's site")

1. We can put a token or key, numbers or words to replace the links especially if it is  going to occur in more than one place, this is recommended for readability as well as links that may change:
2. 
[Lanre][code] loves to code you can find some of her works very useful and helpful.

You can check out [Lanre][code] and her [designs][1] right there, her [designs][1] are really cool.

## Images
They are pretty much exactly the same as links:

https://images.pexels.com/photos/169573/pexels-photo-169573.jpeg?cs=srgb&dl=pexels-negative-space-169573.jpg&fm=jpg

![Laptop](https://images.pexels.com/photos/169573/pexels-photo-169573.jpeg?cs=srgb&dl=pexels-negative-space-169573.jpg&fm=jpg)

![Hitesh](https://images.pexels.com/photos/879109/pexels-photo-879109.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940 "This is Hitesh choudhary holding code in his hand")

![Cute Pup][pup]

You can make a link link to the larger version of the photo:

[![](https://images.pexels.com/photos/5282269/pexels-photo-5282269.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=50&w=940)](https://images.pexels.com/photos/5282269/pexels-photo-5282269.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=50&w=940)

OR We can use the image source:

[<img src="https://images.pexels.com/photos/5282269/pexels-photo-5282269.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" width="200" height="200">](https://images.pexels.com/photos/5282269/pexels-photo-5282269.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=50&w=940)

We can use the style tag to style the image, we can also use figure and figcaption tags just like in regular HTML

## Lists

Just like in HTML, we have unoredered lists and ordered lists:

### Unordered Lists
We  can use *, -, or + sign for unordered lists, it's just a personal preference like so:

#### Ingredients

* Milk 
* Sugar
* Tea
* Coffee
* Honey

OR

- Salt
- Onion
- Pepper
- Curry
- Thyme

OR

+ Flour
+ Egg
+ Sugar
+ Butter
+ Milk


### Ordered Lists

1. Combine Ingredients
1. Lick the bowl...
1. Gently stir together
1. Bake at 350 for 20 minutes

OR

1. Combine Ingredients
2. Lick the bowl...
3. Gently stir together
4. Bake at 350 for 20 minutes

### Contents in between Lists

1. Combine Ingredients
   - Dice
      This is inline 
      ![Laptop](https://images.pexels.com/photos/169573/pexels-photo-169573.jpeg?cs=srgb&dl=pexels-negative-space-169573.jpg&fm=jpg)
2. Lick the bowl...
3. Gently stir together
   - Fry
  
    Add content here. This is a paragrah. ![Laptop](https://images.pexels.com/photos/169573/pexels-photo-169573.jpeg?cs=srgb&dl=pexels-negative-space-169573.jpg&fm=jpg)

    ```JS
    var x = 100;
    ```

4. Bake at 350 for 20 minutes

 
### Nested/Indented Lists

- Tea
  - Milk
  - Milo
  - Sugar
- Coffe
  - Cocoa
  - Butter
  - Cream
- Honey
- Ginger

OR

1. Wake Up
   - Pray 
   - Meditate
1. Exercise
     - Run
     - Skip
     - Jog
2. Eat breakfast
3. Ready to go 



## Line Breaks
Lanre is cool. <br>
She is a fun person.

## Horizontal Rule
Hello World

----------

## Block Quotes

>The fear of the Lord is the beginning of knowledge but fools despise wisdom and instruction.  -  **Proverbs 1:7**


## Code Blocks + Syntax Highlighting

Here is my code

```HTML
<h1>Hello World</h1>
<p>What's up people</p>
<span>HEY</span>
<span>HEY</span>
```

```CSS
h1 {
  color: #fff;
}

p {
  color: #000;
}
```

```JS
    var x = 100;
    const dog = "sneakers"; 
```

```Python
print(code)
```


```
  echo  "hello"
```

We can wrap it in inline code here:

Did you try `var x =100;`  

We can show someone that we deleted a line and added a line here:

```diff
var x = 100;
- var y = 200;
+ var y =300;
```

### Tables 

|Name|Age|Sex|
|:----------|:------:|:---------:|
|John|30|M|
|Jane|25|F|
|Jill|20|F|


## Checkboxes

- [x] Get Milk
- [x] Crack Eggs
- [x] Beef
- [ ] Meat
- [ ] Steak






[code]:https://github.com/lanre-waju 
[1]: https://dribbble.com/Lanre__waju
[pup]: https://images.pexels.com/photos/5961947/pexels-photo-5961947.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
