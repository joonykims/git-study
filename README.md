# Git 버전관리 에센셜

VScode 를 통한 git 사용법과 git bash를 통한 사용법을 테스트하고 실험하는 git repo 입니다.  

CLI 방식을 통한 명령어와 GUI 환경에서의 git 명령을 비교하면서 작업하니 개념을 잡기가 더 쉬운것 같습니다.   

## VScode vs Sublime Text

VScode 가 좋다 서브라임텍스트가 좋다. 이렇게 단편적으로 결론을 짓기는 어렵다.  
둘 다 장점이 있으며 둘 다 좋다.  
당분간 두 편집기를 교차하면서 사용해 볼 것이다.

일단 sublime text 가 메모리를 덜 사용하고 약간 더 가벼운 느낌이다.

git 관련 부분은 sublime merge가는 별도 앱을 사용해야 하고 유료다 - 물론 무료 상태에서도 상당부분 편리한 부분이 있다 - 그게 좀 단점이긴 해도 sublime 은 정말 가볍고 빠르다.

상대적으로 vscode 는 메모리 사용량이 약 500메가 정도 된다. 부담이 약간 되긴 하지만....그렇다 엄청 무겁다는 생각은 안든다.  

> VScode에서 PHP 코딩할때 HTML이나 CSS코딩할때 자동완성(Autocomplete)기능이 안된다. 이때는 [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client) 플러그인을 설치하면 해결 된다.

## VSCode bugs
아무래도 GUI 툴이 버그가 좀 있는 것 같다.   
1. fetch 명령이 잘 안됨
2. 원인은 모르겠는데 파일 내용을 수정했는데도  git history 에서 변경 사항이 보이지 않는 경우가 있음. vscode 를 재실행하니 변경 사항이 보임.  

또 다른 버그가 있는지 찾아 보자.
