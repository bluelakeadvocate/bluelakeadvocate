---
layout: home
---

## Downtown Blue Lake, live

<img id="camera-feed" src="https://pub-1343ea4220db4e1dabb0dadd1d8ef728.r2.dev/camera.jpg" alt="Live view of downtown Blue Lake" style="max-width: 100%; border-radius: 4px;">

<script>
  document.getElementById('camera-feed').src += '?t=' + Date.now();
</script>
