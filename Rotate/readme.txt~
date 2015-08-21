This project allows you to simply rotate image by any degree.
 It uses CSS3 where applicable and falls back to a CANVAS (old firefox, some less known browsers) or VML (IE6) solution where possible. 
It also gives some simple interface to animate rotation. 
Keep in mind that primary usage of this plugin is to only rotate "IMG" elements, 
however experimental version of plugin (ver.3) also rotates other elements (yet does not support so many older browsers).




example:
var rotation = function (){
  $("#img").rotate({
    angle:0,
    animateTo:360,
    callback: rotation,
    easing: function (x,t,b,c,d){        // t: current time, b: begInnIng value, c: change In value, d: duration
      return c*(t/d)+b;
    }
  });
}
rotation();


