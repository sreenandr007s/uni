
<!DOCTYPE html>
<html>
  <head>
    <script src="https://aframe.io/releases/1.4.2/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <!-- Existing Box -->
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      
      <!-- Bird Model on top of the box -->
      <a-gltf-model src="https://your-web-server.com/path/to/bird.gltf" position="-1 1.5 -3" scale="0.1 0.1 0.1"></a-gltf-model>
      
      <!-- New Rectangular Box -->
      <a-box position="2 0.5 -3" rotation="0 0 0" color="#FF5733" width="2" height="1" depth="0.5"></a-box>
      
      <!-- Existing Sphere -->
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      
      <!-- Existing Cylinder -->
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      
      <!-- Existing Plane -->
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      
      <!-- Existing Sky -->
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
