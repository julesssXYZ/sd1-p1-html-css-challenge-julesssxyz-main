# HTML CSS positioning and styling
1. On top of the body in your HTML file, create layers of divs inside each other, create two divs in the last layer. Like this:

````HTML
<div>
    <div>
        <div>
            
        </div>
        <div>
            
        </div>
    </div>
</div>
````

2. Give each div a different class, e.g. big-box, medium-box and small-box (The last layer is 2 divs, so the same class!)

3. Give the following properties to these classes via your CSS file.
   1. big-box, width: 100vw, height: 30vw, background-color: lavender.
   2. medium-box, width: 50%, height: 50%, border: 2px dashed blue.
   3. small-box, width: 20%, height 50%, border: 2px solid green.

4. Evaluate what happened on your webpage. 
5. Then add the following things:
   1. Add position: relative to the medium-box and small-box.
   2. Add display: inline-block to the small-box
   3. Try to center the small-boxes by using the properties "left: ...%", "top: ...%".
   4. If you have one element inside another such as the medium-box in the big-box try the following: left: 50%, top: 50%, transform, translate(-50%, -50%)

## Further theory worth the investigation
* display: flex;
* display: grid;