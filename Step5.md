# WebXR NL Workshop
## Step 5
### Custom Component

``` javascript
AFRAME.registerComponent('change-color', {​
  schema: {​
    color: {default: 'green'}​
  },​
​
  init: function () {       ​
  this.el.addEventListener('click',() => {​
     this.el.setAttribute('material', 'color', this.data.color);​
  })​
  }​
});​
```

``` html
<a-sphere color="blue" change-color="color:pink"...​
```