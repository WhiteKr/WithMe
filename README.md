# With Me

시각장애 보조 서비스 애플리케이션입니다.


# Daily Development
개발 일지

## ~ 05.28
기본적으로 Vision AI를 이용한 서비스이기 때문에 카메라를 구현할 필요가 있습니다.\
기본 내장 카메라 앱을 사용하면 카메라에서 부가기능을 즉시 사용하기 힘들기 때문에 직접 <b>커스텀 카메라</b>를 만들어야 합니다.

Android Developers에 [카메라 제어](https://developer.android.com/training/camera/cameradirect)라는 공식 문서가 존재하지만\
참고하기에는 정보가 다소 부족하다고 느껴 stack overflow, GitHub, Blog, YouTube 등 여러 자료들을 뒤져가며 공부중입니다.

## ~ 06.01
안드로이드 4.4 환경에서는 커스텀 카메라 개발이 힘들어 5.0 환경에서 프로토타입용 카메라 앱을 구현하였습니다.\
CameraX를 사용해 개발하니 코드가 훨씬 짧아지고 개발도 손쉬웠습니다.

CameraX의 안드로이드 지원 버전이 5.0 이상이라 4.4 프로젝트에선 사용이 불가합니다.\
프로토타입용 프로젝트이므로 추후 실제 앱 개발 시 다시 4.4 환경에서 개발해야 합니다.

현재 CameraX를 사용해 5.0 버전에서 개발중이며 [WithMe5.0](https://github.com/WhiteKr/WithMe5.0) 깃허브에서 확인할 수 있습니다.\
앱에 적용하기 위해 연습한 기술들([CameraX](https://github.com/WhiteKr/CameraX) 등) 또한 다른 Repositories에서 확인할 수 있습니다.


## 10.01
NUGU 캔들과 함께 사용하는 WithMe_NUGU 프로젝트가 끝났습니다.\
이건 원래 위 프로젝트를 위한 repository였는데, 새로 만든 비공개 repository에서 작업을 끝냈기 때문에 NUGU가 없는 버전을 저장하는 용도로 사용하려 합니다.\
목적과 사용법은 이전과 크게 바뀌지 않되, 캔들 없이 안드로이드 기기와 인터넷만 있으면 어디서든 사용 가능하게 개발하는 것이 우선 목표입니다.

## 10.06
GitHub에 업로드 되어있던 기존 WithMe 파일을 초기화 하였습니다.\
.gitignore 정리를 하였습니다. IDE나 finder에서 폴더를 엶으로서 생기는 잡다한 파일까지 Git에 포함되지 않도록 하기 위함입니다.