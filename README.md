# p5-shaders
A few basic shaders in a p5 sktech

# Color shader example
´´´glsl
// frag.txt
// p5-shader-examples 
// Author Matthias Jäger
// Date 2020-09-08

precision mediump float;

varying vec2 fragCoords;

void main() 
{
  // Center uv coordinates
  vec2 uv = fragCoords - 0.5;
   
  // returns a variable (red, green, blue, alpha)
  gl_FragColor = vec4(vec3(0.0), 1.0);
}
´´´



