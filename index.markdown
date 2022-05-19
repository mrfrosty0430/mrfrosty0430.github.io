---
layout: home
author_profile: true
---
<!-- Channel Plugin Scripts -->
<script>
  (function() {
    var w = window;
    if (w.ChannelIO) {
      return (window.console.error || window.console.log || function(){})('ChannelIO script included twice.');
    }
    var ch = function() {
      ch.c(arguments);
    };
    ch.q = [];
    ch.c = function(args) {
      ch.q.push(args);
    };
    w.ChannelIO = ch;
    function l() {
      if (w.ChannelIOInitialized) {
        return;
      }
      w.ChannelIOInitialized = true;
      var s = document.createElement('script');
      s.type = 'text/javascript';
      s.async = true;
      s.src = 'https://cdn.channel.io/plugin/ch-plugin-web.js';
      s.charset = 'UTF-8';
      var x = document.getElementsByTagName('script')[0];
      x.parentNode.insertBefore(s, x);
    }
    if (document.readyState === 'complete') {
      l();
    } else if (window.attachEvent) {
      window.attachEvent('onload', l);
    } else {
      window.addEventListener('DOMContentLoaded', l, false);
      window.addEventListener('load', l, false);
    }
  })();
  ChannelIO('boot', {
    "pluginKey": "1deda9c2-8943-4d35-9924-a29a68b0cfcf"
  });
</script>
<!-- End Channel Plugin -->
<script src="https://developers.kakao.com/sdk/js/kakao.js"></script>
<script>
	console.log(window.location);
  function loginWithKakao() {
  	var getUrl = window.location;
  	console.log(getUrl);
    Kakao.init("f64585f1fa831d622cdc03a67b36193c")
    Kakao.Auth.authorize({
      redirectUri: 'https://sungjunh.me'
    })

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
