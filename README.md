# first-person-movement
ThreeJs library to help the implementation of a application that use first personn movement

## Usage 

Include the library in your html file

’<script src=".../FirstPersonMovement.js"></script>’


Instantiate the class and link it with you camera
’camControls = new FirstPersonMovement(camera,"AZERTY");’

Launch Update in yoru render loop

‘            var delta = this._clock.getDelta();
            this._camControls.update(delta);
            ‘
