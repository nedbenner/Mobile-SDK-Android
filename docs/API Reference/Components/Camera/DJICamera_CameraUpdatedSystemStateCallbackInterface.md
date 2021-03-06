<div class="article"><h1 ><font color="#AAA">class </font>Callback</h1></div>

~~~java
 interface Callback 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.camera</td></tr></table></html>



##### Description:



<font color="#666">Updates the camera's current state. In order to begin updates, call the startCameraStateUpdates method for the respective aircraft.



##### Class Members:



#### Callback Method

<div class="api-row" id="djicamera_didupdatesystemstate"><div class="api-col left">State</div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djicamera_didupdatesystemstate_inline">onUpdate</a></div></div><div class="inline-doc" id="djicamera_didupdatesystemstate_inline"

><div class="article"><h6 ><font color="#AAA">method </font>onUpdate</h6></div>

~~~java
        void onUpdate(@NonNull SystemState systemState)
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.camera</td></tr></table></html>



##### Description:



<font color="#666">Called when the camera's current state has been updated.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">@NonNull <a href="/Components/Camera/DJICamera_DJICameraSystemState.html#djicamera_djicamerasystemstate">SystemState</a> <font color="#000">systemState</td><td><font color="#666"><i>The system state of camera.</i></td></tr></table></html></div>


