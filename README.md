# svg-animation
Micro-animation to practice creating svgs and animations || The original illustration was made by Ray Oranges

You can see the result on my [Codepen](https://codepen.io/Aggie/full/exmXbv).

<br/>
<hr/>
<br/>

#### Personal notes:
* svgs elements stuck in order: from top to bottom - it is possible to use z-index only on svg tag but it doesn't work for paths etc. inside svg; without using JS the only trick that could work is to duplicate element later on in a document using: 
```
<use id="example-duplicate" xlink:href="#example" />
```
* xlink:href="" works with IDs,
* to translate a few elements it's better to wrap them in a group - that can be also nested in another group
