# karukaru
<!DOCTYPE html>
<html lang="ja">
<head>  
  <script src="https://aframe.io/releases/1.0.2/aframe.min.js"></script>
  <script src="./js/aframe-ar.js"></script>
  <script src="./js/aframe-extras.js"></script>
  
  <title>A-Frame</title>

</head>

   <html>
    
      <body style='margin: 0; overflow: hidden;'>
    
        <a-scene>
    
          <a-assets>
          <a-asset-item id="model" src="./prot/object1/prot.gltf"></a-asset-item>
          </a-assets>
        
            <a-marker preset="hiro">
        
              <a-entity gltf-model="#model" scale="1 1 1" rotation="0 0 0" position="0 0.5 0" animation-mixer="loop:pingpong" ></a-entity>
    
            </a-marker>

    <!-- ⑥ カメラを追加 -->
          <a-entity camera></a-entity>
        </a-scene>

      </body>

    </html>
