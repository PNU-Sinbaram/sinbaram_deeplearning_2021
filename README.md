# Sinbaram DeepLearning Study 2021
![LOGO](logo.png)

신바람 딥러닝 스터디에서 각자 Andrew Ng 교수님의 강의를 보고 파이썬 코드 실습 세션을 따라해보고 
그 코드를 업로그하기 위한 레포지터리입니다.

## How to upload your codes
Git 사용이 익숙치 않은 분들을 위해 여러분들의 코드를 저장소에 업로드하는 방법을 알려드리겠습니다.

Git이 로컬에 설치되어 있지 않는 분은 아래 링크에서 설치해주세요
https://git-scm.com/downloads

설치가 끝나면 CMD에 들어가서 자신의 github 닉네임과 이메일을 설정해주세요.
```bash
git config --global user.name "닉네임"
git config --global user.email "이메일"
```

CMD를 켜서 원하는 directory에 이동 후, 아래 명령어를 입력해주세요.
```bash
git clone https://github.com/snowapril/sinbaram_deeplearning_2021
```

clone 한 신바람 알고리즘 저장소 폴더를 가지고 되도록 다른 사람 코드는 건들지 않고 
자신의 코드가 적힌 파일을 정해진 위치에 옮기고 다시 CMD를 킵니다.

working directory를 저장소 폴더로 해놓고, 자신이 방금 추가한 파일을 staging 해줍니다.
```bash
git add Your/Path/file.cpp
```

방금 staging한 파일들을 commit 해줍니다.
```bash
git commit -m "방금 추가한 파일들의 설명"
```

이제 Committed 된 파일들을 remote 저장소에 반영해주어야 하는데요. 
반드시, 실수로 저장소 폴더의 다른 사람들 코드를 건드리진 않았는지 확인하고 업로드 해주세요.
remote 저장소에 업로드는 아래 명령어를 입력해줍니다.
```bash
git push origin main
```

명령어를 입력하면 비밀번호를 치라고 문구가 뜨는데 본인의 Github 비밀번호를 치시면 됩니다.

## Members
* [신지홍](https://github.com/snowapril)
* [이종목](https://github.com/hyunyunV)
* [윤우섭](https://github.com/lijm1358)
* [홍명신](https://github.com/MyeongsinHong)