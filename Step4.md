# WebXR NL Workshop
## Step 4
### Cursor

``` html
<a-camera position=“0 1.6 0”​
  <a-entity cursor="fuse: true; fuseTimeout: 500“​
    position="0 0 -1"​
                  geometry="primitive: ring; radiusInner: 0.02; radiusOuter: 0.03"​
                  material="color: purple; shader: flat">​
  </a-entity>​
</a-camera>​
```