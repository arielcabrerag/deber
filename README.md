<!-- AR.js by @jerome_etienne - github: https://github.com/jeromeetienne/ar.js - info: https://medium.com/arjs/augmented-reality-in-10-lines-of-html-4e193ea9fdbf -->
<script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
<script src="https://cdn.rawgit.com/jeromeetienne/AR.js/1.6.0/aframe/build/aframe-ar.js"></script>
<body style='margin : 20px; overflow: hidden;'>
	<a-scene embedded arjs='sourceType: webcam;'>
		<a-box position='0 0.55 0' material='opacity: 0.3;'></a-box>
		<a-marker-camera preset='Arial'></a-marker-camera>
	</a-scene>
</body>
