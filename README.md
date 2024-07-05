# Buffer-Particle-System
 A ready to use buffer particle system

<h3>Using the already existing particle systems</h3>
Drag the prefab onto your avatar<br>
Unpack the prefab<br>
Take the 2 particle systems out of it, if you want<br>
Each time you enable the Buffer Particle game object (after it was disabled), it will make the "Sub Emitter" emit particles.<br>
Your particle system should be the "Sub Emitter" in this case.<br>
<br>
<h3>Using your own particle system</h3>
1.) Drag it under the Buffer Particle game object<br>
2.) Go to the sub emitter section of the Buffer Particle<br>
3.) Add your system as one of the Sub Emitters and make sure it is set to "Birth"<br>
4.) Make your own particle system not "Play on Awake"<br>
5.) Set your particle system's emission to be 0 on both Rate over Time, and on Rate over Distance<br>
6.) Add a burst to your particle system
