# Today-Famous-Saying
### 오늘의 명언 안드로이드 앱

#### 화면을 스와이프하며 오늘의 명언들을 볼 수 있는 앱 입니다.
### Blog
* <https://hwayomingdlog.tistory.com/228>
* <https://hwayomingdlog.tistory.com/234>
</br>

#### ⚠️ 주의사항
Firebase 프로젝트에서 다운받은 google-services.json 파일을 추가해야합니다.
</br>

## 주기능
### 오늘의 명언 보기
* 화면을 좌우로 스와이프하여 명언과 명언을 말한 인물을 볼 수 있습니다.
* 무한 스와이프를 지원하여 계속해서 넘기며 명언들을 볼 수 있습니다.
</br>

## 활용 기술
* Firebase Remote Config - Firebase console에 정의한 매개변수 값들을 Remote Config를 통해 앱으로 받아와 명언과 인물을 화면에 적용하였습니다.
* ViewPager2 - ViewPager2를 활용하여 명언이 담긴 페이지를 무한 스와이프하며 볼 수 있도록 구현하였습니다.
* PageTransformer - 0, 0~1, 1 각각의 포지션마다 다른 alpha 값을 적용하여 페이지를 스와이프 시 흐려졌다가 다시 보이는 애니메이션을 적용하였습니다.

***
<img src="/img/img0.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img1.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img2.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img3.png" width="300px" height="600px" title="" alt=""></img>
<img src="/img/img4.png" width="300px" height="600px" title="" alt=""></img>
