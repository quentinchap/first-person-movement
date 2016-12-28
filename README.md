# first-person-movement
ThreeJs library to help the implementation of a application that use first personn movement

## Usage 

Include the library in your html file

```javascript
<script src=".../FirstPersonMovement.js"></script>
```


Instantiate the class and link it with you camera
```javascript
var camControls = new FirstPersonMovement(camera,"AZERTY");
```

Launch Update in yoru render loop

```javascript
var clock = new THREE.Clock();
var delta = this.clock.getDelta();
camControls.update(delta); 
```
