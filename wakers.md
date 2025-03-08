<link href="wakers.css" rel="stylesheet"/>
<script>
function showImagePopup() {
  const popup = document.createElement('div');
  popup.style.position = 'fixed';
  popup.style.top = '0';
  popup.style.left = '0';
  popup.style.width = '100%';
  popup.style.height = '100%';
  popup.style.backgroundColor = 'rgba(0,0,0,0.8)';
  popup.style.display = 'flex';
  popup.style.justifyContent = 'center';
  popup.style.alignItems = 'center';
  popup.style.zIndex = '1000';
  
  const img = document.createElement('img');
  img.src = 'mymbtis_splash.png';
  img.style.maxWidth = '90%';
  img.style.maxHeight = '90%';
  
  popup.appendChild(img);
  
  popup.onclick = function() {
    document.body.removeChild(popup);
  };
  
  document.body.appendChild(popup);
}
</script>

# 진짜 굿모닝 with Wakers
- 매력적인 AI친구들의 Wake-up call을 통해 즐겁게 아침을 시작해요.
- <button onclick="showImagePopup()">Download</button>