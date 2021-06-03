# note
글쓰기
* 마크다운 연습
  * 마크다운이란 - [깃헙](https://gist.github.com/ihoneymon/652be052a0727ad59601)
  * 마크다운의 장점 - 간결하며 별도의 도구 없이도 작성 가능
  * 마크다운의 단점 - 핵심문법을 제외하고는 사용자마다 결과물이 달라질 수 있음
* 마크다운 필수문법 - [개인깃헙](https://theorydb.github.io/envops/2019/05/22/envops-blog-how-to-use-md/)
  * 제목 - # > ## > ### > #### > 이후로는 크기변화x
  * 내용구분 - '---' 수평선 사용
  * 리스트 만들기
    * 순서리스트 - '1.첫번째 2.두번째 3.세번째
    * 순서x리스트 - + > - > # > 이후로는 처음부터 반복
  * 강조
    * 진하게 - '__쓸말__'
    * 기울이기 - '_쓸말_'
    * 취소선 - '~~쓸말~~'
    * 밑줄 - '<u>내용</u> '
      * 볼드체 안에 이탤릭체 사용 가능 - '__내에에*내용*에에에에용__'
  * 인용구 - >내용(중복 사용 가능)
  * 링크
    * 유형1 - [주소이름](URL "마우스 커서 올리면 보이는 내용")  
    * 유형2 - <URL>  
    * 유형3(동일한 파일 내 `문단 이동`) : [문단이름](#해당문단) 
      * 문단 지정 방법 - 제목 복사 붙여넣기 > 특수문자제거 > 띄어쓰기 개수만큼 -로 변경 > 대문자는 소문자로 변경


* 코딩 컨벤션이란 -[파이썬코딩컨벤션](https://spoqa.github.io/2012/08/03/about-python-coding-convention.html)
    * 코딩 컨벤션: 코드 작성시 사용되는 기준
    ex. 'a=1'과 'a = 1', 들여쓰기할 때 tap과 space
    실행 결과에는 큰 차이가 없지만, 코드의 일관성을 위해 세운 기준

* 모던 웹을 위한 HTML5+CSS3 바이블
  * 0강
    * 책소개. 1단원은 기초지식, 2단원은 실전, 3단원은 실전에서는 거의 다루지 않는 논문급 전문내용
    * 이 책 내용의 절반을 대학교재로 만든 것이 1학기 내용임.
  *1강
    * 프로그램을 할 때 필요한 프로그램 두 가지(텍스트 에디터, 코드실행 프로그램)
    * 위의 두 프로그램을 함께 제공하는 경우도 있음(통합 개발 환경) ex.visual studio code
    * ctrl+n 파일생성 > ctrl+s 저장(확장자 이름은 .html) > html:5+엔터 코드입력
    * <body></body> 사이에 <h1>Hello world<h1>입력 후 저장 > 저장한 파일을 구글크롬에 드래그 하면 실행
    * 한국어 언어팩 설치 방법
      * 왼쪽 메뉴에서 다섯 번째 아이콘 클릭하고 Korean 검색 후 Install
    * 폴더 열기 기능
      * 왼쪽 메뉴에서 첫번째 아이콘 클릭하고 폴더 열기
      * 컴퓨터 폴더에서 마우스 오른쪽키 눌러 open with code 클릭
      * visual studio 왼쪽에 뜨는 파일 목록에서 파일 드래그해서 구글크롬에 올리면 바로 결과 확인 가능
    * 코딩 전용 폰트(고정폭 글꼴)
      * visualstudio에서는 한글폰트 지원하지 않으므로 네이버에서 지원하는 D2Coding 글꼴 설치
      * 파일 > 기본설정 > 설정 > 텍스트 편집기 > 글꼴에서 D2Coding 입력