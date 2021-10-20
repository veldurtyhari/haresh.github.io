<!DOCTYPE html>
<html lang="en">

<head>
	<title>WebXR Demo</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
	<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r126/three.js" crossorigin="anonymous"></script>
  <script type="module" src="GLTFLoader.js"></script> 
  <script src="OrbitControls.js"></script> 
  <script type="module">


     
  </script> 

  <style>

	  body{
		  margin: 0;
		}

	  canvas{
		  display: block;
		  width: 100%;
		  height: 100%;
		}
  </style>
</head>


<body>
	<script type="module">

        import {GLTFLoader} from "./GLTFLoader.js"
		let camera, scene, renderer;
        let mesh;
		var obj;
		let controller;
		init();
		animate();

		function init() {
			const container = document.createElement('div');
			document.body.appendChild(container);

			scene = new THREE.Scene();
			camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.01, 1000);
			renderer = new THREE.WebGLRenderer({ antialias: true, alpha: true });
			renderer.setPixelRatio(window.devicePixelRatio);
			renderer.setSize(window.innerWidth, window.innerHeight);
			container.appendChild(renderer.domElement);

			controller = new THREE.OrbitControls(camera,renderer.domElement);

			var light = new THREE.HemisphereLight(0xffffff, 0xbbbbff, 2);
			light.position.set(0.5, 1, 0.25);
			scene.add(light);

			


        var loader = new GLTFLoader();
         loader.load("automoor.gltf", function(gltf){
             obj = gltf.scene
			 scene.add(gltf.scene);

		});

        camera.position.set(0,0,50);


			window.addEventListener('resize', onWindowResize, false);
		}

		function onWindowResize() {
			camera.aspect = window.innerWidth / window.innerHeight;
			camera.updateProjectionMatrix();

			renderer.setSize(window.innerWidth, window.innerHeight);
		}

		
		function animate() {
		
			requestAnimationFrame(animate);
			//obj.rotation.y += 0.01;
			renderer.render(scene, camera);
		}

		
	animate();
	</script>
</body>

</html>