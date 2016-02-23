# Cordova App To Take Photo
App is implementede using cordova-plugin-camera plugin.

## Installation

This requires cordova 5.0+

    cordova plugin add cordova-plugin-camera 


    camera.getPicture(function (imageuri) {
            
    var container = document.getElementById('lastPhoto');
           
     container.innerHTML = "<img src='" + imageuri + "' />";
   
         }, null, null);



