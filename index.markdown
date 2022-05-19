---
layout: home
author_profile: true
---

<script src="https://developers.kakao.com/sdk/js/kakao.js"></script>

<script>
  function loginWithKakao() {
    Kakao.init("f64585f1fa831d622cdc03a67b36193c")
    Kakao.Auth.authorize()
  }
</script>


<a id="custom-login-btn" href="javascript:loginWithKakao()">
  <img
    src="//k.kakaocdn.net/14/dn/btroDszwNrM/I6efHub1SN5KCJqLm1Ovx1/o.jpg"
    width="222"
    alt="카카오 로그인 버튼"
  />
</a>