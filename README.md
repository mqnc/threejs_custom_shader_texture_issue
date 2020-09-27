# threejs_custom_shader_texture_issue
demo of a weird texturing quirk in three.js

Update: Works using this library:

https://github.com/Fyrestar/THREE.extendMaterial

see:

https://mqnc.github.io/threejs_custom_shader_texture_issue/extend_material.html


This is inspired by the gpgpu water demo example and does not work:

https://mqnc.github.io/threejs_custom_shader_texture_issue/uniformsutils_merge.html

This uses ES6 spread syntax to combine the standard uniforms with myTex and works:

https://mqnc.github.io/threejs_custom_shader_texture_issue/spread_uniforms.html

This leaves the myTex uniform completely undefined but instead of a console complaint, myTex weirdly becomes myOtherTex...

https://mqnc.github.io/threejs_custom_shader_texture_issue/undefined_becomes_other.html
