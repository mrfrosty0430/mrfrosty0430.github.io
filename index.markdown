---
layout: home
author_profile: true
---
<script src="https://developers.kakao.com/sdk/js/kakao.js"></script>



<a id="custom-login-btn" href="javascript:loginWithKakao()">
  <img
    src="//k.kakaocdn.net/14/dn/btroDszwNrM/I6efHub1SN5KCJqLm1Ovx1/o.jpg"
    width="222"
    alt="카카오 로그인 버튼"
  />
</a>

<a id="create-kakaotalk-sharing-btn" href="javascript:;">
  <img
    src="https://developers.kakao.com/assets/img/about/logos/kakaotalksharing/kakaotalk_sharing_btn_medium.png"
    alt="카카오톡 공유 보내기 버튼"
  />
</a>
<script type="text/javascript">
  Kakao.init("609482b2d4bee4f9de3a4fd7d534a526")
  Kakao.Share.createCustomButton({
    container: '#create-kakaotalk-sharing-btn',
    templateId: 79132,
    templateArgs: {
      title:
        '판교 맛집에 들르다. 다양하고 풍부한 퓨전 한정식. 깔끔한 내부 인테리어 라이언',
      description:
        '부담없는 가격에 푸짐하게 즐기는 점심메뉴 런치한정식, 불고기정식, 돼지 김치찌개 등',
      redirectTag: 'abcdefg',
      image:
        'https://referral-bucket-test.s3.ap-northeast-2.amazonaws.com/%E1%84%8C%E1%85%A1%E1%84%89%E1%85%A1%E1%86%AB+2%404x.png'
    },
  })
</script>

<a id="create-kakaotalk-sharing-btn1" href="javascript:;">
  <img
    src="https://developers.kakao.com/assets/img/about/logos/kakaotalksharing/kakaotalk_sharing_btn_medium.png"
    alt="카카오톡 공유 보내기 버튼"
  />
</a>
<script type="text/javascript">
  Kakao.Share.createCustomButton({
    container: '#create-kakaotalk-sharing-btn1',
    templateId: 79108,
    templateArgs: {
      title:
        '판교 맛집에 들르다. 다양하고 풍부한 퓨전 한정식. 깔끔한 내부 인테리어 라이언',
      description:
        '부담없는 가격에 푸짐하게 즐기는 점심메뉴 런치한정식, 불고기정식, 돼지 김치찌개 등',
      redirectTag: 'abcdefg',
      image:
        'https://referral-bucket-test.s3.ap-northeast-2.amazonaws.com/%E1%84%8C%E1%85%A1%E1%84%89%E1%85%A1%E1%86%AB+2%404x.png'
    },
  })
</script>
