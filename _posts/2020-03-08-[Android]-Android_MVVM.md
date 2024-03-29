---
layout: post
title: "[AndroidView] Android에 MVVM 패턴"
category: Android
tags: [Android]
---
-------------------
  
안드로이드에 MVVM 패턴을 적용하는 방법인 통일되어 있지 않다.<br/>
AAC가 도입되면서 이를 기반으로 적용했다는 MVVM 패턴이 있고, AAC를 배제하고 적용한 MVVVM 패턴도 있다.<br/>
뭐가 맞는지는 모르겠으나 MVVM패턴의 개념부터 적용방법들은 모두 보면서 공부하고자 한다.<br/>
<br/><br/><br/>
  
# MVVM 패턴
-------------------
 : 
 - MVVM 패턴은 View와 Model 사이의 의존성이 없음
 - Command 패턴과 Data Binding을 사용하여 View와 View Model 사이의 의존성 또한 없음
 - 각각의 부분은 독립적이기 때문에 모듈화 하여 개발가능하다
<br/><br/>
#### Command 패턴
<br/><br/>
#### Data Biding
<br/><br/>


## Adapter Structure in Android
 - [여기](https://m.blog.naver.com/PostView.nhn?blogId=gi_balja&logNo=221162720020&proxyReferer=https%3A%2F%2Fwww.google.com%2F&view=img_2) 엄청 그림으로 잘 그려놓으셨습니다.
<br/>
<br/>
<br/>
  
# AAC없이 안드로이드에 MVVM패턴 적용하기
-------------------
 :  
 - MVVM 을 아무런 도움 없이 구현한다면 기존의 문제점을 개선하는 과정에서 새로운 문제를 일으킬 수 있습니다. 때문에 Databinding 이라는 툴을 이용함으로써 서로간의 의존성을 낮춤으로써 유닛테스트를 더욱 쉽게 작성할 수 있고 UI 코드는 네이티브 코드에 관여하지 않아도 되게 하였습니다.
  
## Android DataBiding
- 

<br/>
<br/>
<br/>
  
-------------------
## 참조

**MMVM패턴**<br/>
* MVC, MVP, MVVM 패턴 : <https://beomy.tistory.com/43>
* Command 패턴 : <https://victorydntmd.tistory.com/295>
* 데이터 바인딩 : <https://zetawiki.com/wiki/%EB%8D%B0%EC%9D%B4%ED%84%B0_%EB%B0%94%EC%9D%B8%EB%94%A9>
* AAC없이 안드로이드에 MVVM패턴 적용하기 : <https://medium.com/@jsuch2362/android-%EC%97%90%EC%84%9C-mvvm-%EC%9C%BC%EB%A1%9C-%EA%B8%B4-%EC%97%AC%EC%A0%95%EC%9D%84-82494151f312>
* Android MVVM 을 위한 Databinding : <https://medium.com/@jsuch2362/android-mvvm-%EC%9D%84-%EC%9C%84%ED%95%9C-databinding-34cd9be44c63>
<br/><br/>
**AAC DataBiding**<br/>
* MVVM AAC Databinding 사용법(1.세팅편) : <https://medium.com/@gus0000123/android-databinding-%EC%82%AC%EC%9A%A9%EB%B2%95-9a3480a3bfc7>
* MVVM AAC Databinding 사용법(2.활용편) : <https://medium.com/@gus0000123/android-jetpack-databinding-%EC%82%AC%EC%9A%A9%EB%B2%95-2-%ED%99%9C%EC%9A%A9%ED%8E%B8-de0343cced26>
* MVVM AAC Databinding 사용법(3.상세편) : <https://medium.com/@gus0000123/android-jetpack-databinding-%EC%82%AC%EC%9A%A9%EB%B2%95-3-%EC%83%81%EC%84%B8%ED%8E%B8-afcc96ac3690>
* AAC DataBiding 출시 배경&문법 : <https://dundun-dev.tistory.com/16>
* 간단&간결 DataBiding 기초 설명(Activity, Fragment에 DataBinding적용) : <https://itpangpang.xyz/353>
**AAC ViewModel**<br/>
* ViewModel사용법 : <https://woovictory.github.io/2019/05/02/What-is-ViewModel/>
* ViewModel사용법 + 커스텀 생성자 : <https://medium.com/@jungil.han/%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-viewmodel-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-2e4d136d28d2>
* **Helper Class** : <https://overface.tistory.com/436>
<br/>

* Annotation Processing with Kotlin : <https://kotlinlang.org/docs/reference/kapt.html>
