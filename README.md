# Shadertoy To Flixel

# How to convert shadertoy to haxe 

Shadertoy  --> Converted to flixel 


mainImage -->  main 


texture   -->  flixel_texture2D


iChannel0 -->  bitmap 


iChannel1 -->  bitmap


iChannel2 -->  bitmap


iChannel3 -->  bitmap


fragCoord / iResolution.xy --> openfl_TextureCoordv 


fragCoord.xy / iResolution.xy --> openfl_TextureCoordv 


fragCoord --> openfl_TextureCoordv*openfl_TextureSize (make sure to make it a vec2 if make it kind of like a variable)


iResolution --> openfl_TextureSize (make sure to make it a vec2 if make it kind of like a variable)


fragColor --> gl_FragColor 
