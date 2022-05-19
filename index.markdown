---
layout: home
author_profile: true
---

<script src="https://developers.kakao.com/sdk/js/kakao.js"></script>
<script>
	console.log(window.location);
  function loginWithKakao() {
  	var getUrl = window.location;
  	console.log(getUrl);
    Kakao.init("f64585f1fa831d622cdc03a67b36193c")
    Kakao.Auth.authorize()

    // SDK 초기화 여부를 판단합니다.
    console.log(Kakao.isInitialized());
  }
</script>


<a id="custom-login-btn" href="javascript:loginWithKakao()">
  <img
    src="//k.kakaocdn.net/14/dn/btroDszwNrM/I6efHub1SN5KCJqLm1Ovx1/o.jpg"
    width="222"
    alt="카카오 로그인 버튼"
  />
</a>