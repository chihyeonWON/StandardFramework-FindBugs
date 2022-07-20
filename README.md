# StandardFramework-FindBugs
Studying StandardFramework-FindBugs

## 파인드벅스 개념

소프트웨어 공학 분야에서는 소프트웨어 결함(버그) 발견의 시기와 비용 간의 상관관계에 대한 많은 분석을 수행하였고, 그 결과 버그를 빨리 발견할수록 수정하는 데 비용이 적게 든다는 것이 입증되었다.   
파인드 벅스는 미국의 메릴랜드 대학에서 2006년에 개발되었고, 자바 프로그램에서 발생 가능한 100여개의 잠재적인 에러를 탐지하고, 그 결과를 XML로 저장할 수 있도록 지원한다.   
파인드 벅스는 버그가 일어날 부분을 식별하여 잠재적인 에러를 4등급으로 구분한다.
1.scariest
2.scary
3.troubling
4.concern
   
또 파인드 벅스에서는 9가지의 탐지 카테고리를 제공한다.

## 파인드벅스 실습

FindBugs가 없다면 Help -> install Software 메뉴에서 FindBugs를 다운로드해준다.

Window -> Preference -> Java -> FindBugs 메뉴로 들어가면 Reporter configuration 탭에서 9가지의 카테고리를 선택 혹은 해제 할 수 있다.   
4가지 등급은 각각 Error, Warning, Info 중에서 선택할 수 있다.   
![FindBugsSetting](https://user-images.githubusercontent.com/58906858/179902898-9c90dac0-e813-4d8e-bfdc-98d933a6fbc1.png)

   
검사를 시행할 프로젝트를 선택하고 오른쪽마우스 FindBugs -> FindBugs를 선택하여 버그 탐지를 할 수 있다.
