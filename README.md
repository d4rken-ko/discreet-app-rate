신중한 앱 요금
============

가볍고 방해가 되지 않는 Android용 앱 요금 알림 서비스입니다.

![Screenshot][1]

## 다운로드

```
repositories {
    mavenCentral()
}

dependencies {
    compile 'fr.nicolaspomepuy:discreetapprate:2.0.3@aar'
}
```

## 용법

```
AppRate.with(MyActivity.this).checkAndShow();
```

다음 설정과 작업은 모두 체인으로 연결할 수 있습니다.

## API

전체 API를 읽으려면 [Wiki 섹션](https://github.com/PomepuyN/discreet-app-rate/wiki)을 방문하세요.

## 견본

[Google Play 스토어에서 이용 가능](https://play.google.com/store/apps/details?id=com.npi.discreetapprate.sample)

## 특허

```
 Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
```


[1]: http://nicolaspomepuy.fr/wp-content/uploads/2014/03/screenshot.png
