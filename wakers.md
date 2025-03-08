---
title: "Wakers"
---
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
  img.src = 'qr.png';
  img.style.maxWidth = '90%';
  img.style.maxHeight = '90%';
  
  popup.appendChild(img);
  
  popup.onclick = function() {
    document.body.removeChild(popup);
  };
  
  document.body.appendChild(popup);
}
</script>

# Happy morning with Wakers
- Start your morning off right with a wake-up call from a charming AI friend.
- <button onclick="showImagePopup()" style="background-color:red;">.     Download Wakers     .</button>
- <img src='wakers_screen_eng_500.png' style="width:25%;background-color:transparent;border-radius:20px;"/>

# Wakers features
## Wake up to pleasant conversations, not loud noises
<img src='wakers_banner_1024_500_en.png' style="width:50%;background-color:transparent;border-radius:20px;"/>

## Befriend and romance different avatars
<img src='avatars.png' style="width:50%;background-color:transparent;border-radius:20px;"/>

## A lot of information while in bed
<svg width="360" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- 동일한 그라데이션 정의 -->
    <linearGradient id="grad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#4A90E2;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#50E3C2;stop-opacity:1"/>
    </linearGradient>
  </defs>

  <!-- 날씨 아이콘 박스 -->
  <g transform="translate(10,10)">
    <!-- 배경 박스 -->
    <rect x="0" y="0" width="100" height="100" rx="12" ry="12" fill="url(#grad)"/>
    <!-- 아이콘 요소(날씨: 태양 + 구름), 중앙 정렬 -->
    <g transform="translate(20,20)" stroke="#ffffff" fill="none" stroke-width="4" stroke-linecap="round" stroke-linejoin="round">
      <!-- 태양 -->
      <circle cx="30" cy="30" r="10" fill="#ffffff"/>
      <!-- 태양 광선 -->
      <line x1="30" y1="5" x2="30" y2="15"/>
      <line x1="30" y1="45" x2="30" y2="55"/>
      <line x1="5" y1="30" x2="15" y2="30"/>
      <line x1="45" y1="30" x2="55" y2="30"/>
      <line x1="12" y1="12" x2="18" y2="18"/>
      <line x1="42" y1="42" x2="48" y2="48"/>
      <line x1="12" y1="48" x2="18" y2="42"/>
      <line x1="42" y1="18" x2="48" y2="12"/>
      <!-- 구름 -->
      <path d="M60,40 
               a10,10 0 0,0 -10,-10
               a10,10 0 0,0 -10,10
               h-20
               a10,10 0 0,0 0,20
               h40
               a10,10 0 0,0 0,-20z"/>
    </g>
  </g>

  <!-- 뉴스 아이콘 박스 -->
  <g transform="translate(130,10)">
    <rect x="0" y="0" width="100" height="100" rx="12" ry="12" fill="url(#grad)"/>
    <g transform="translate(10,10)" stroke="#ffffff" fill="none" stroke-width="4" stroke-linecap="round" stroke-linejoin="round">
      <!-- 신문 외곽 -->
      <rect x="0" y="0" width="80" height="80" rx="8" ry="8"/>
      <!-- 텍스트 라인 -->
      <line x1="10" y1="20" x2="70" y2="20"/>
      <line x1="10" y1="35" x2="70" y2="35"/>
      <line x1="10" y1="50" x2="70" y2="50"/>
      <line x1="10" y1="65" x2="70" y2="65"/>
    </g>
  </g>

  <!-- 옷코디 아이콘 박스 -->
  <g transform="translate(250,10)">
    <rect x="0" y="0" width="100" height="100" rx="12" ry="12" fill="url(#grad)"/>
    <g transform="translate(20,20)" stroke="#ffffff" fill="none" stroke-width="4" stroke-linecap="round" stroke-linejoin="round">
      <!-- 옷걸이 상단 곡선 -->
      <path d="M20,20 Q40,0 60,20"/>
      <!-- 옷걸이 본체 -->
      <line x1="20" y1="20" x2="20" y2="60"/>
      <line x1="60" y1="20" x2="60" y2="60"/>
      <line x1="20" y1="60" x2="60" y2="60"/>
      <!-- 걸이 부분 -->
      <line x1="40" y1="0" x2="40" y2="10"/>
    </g>
  </g>
</svg>

<button onclick="showImagePopup()" style="background-color:red;">.     Download Wakers     .</button>

- [Terms of service](terms_wakers_en), [Privacy Policy](privacy_wakers_en), [Contact](mailto:hello@t-gi.co)
- T-GI.co