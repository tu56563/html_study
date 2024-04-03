# Visual Studio Code(VScode)
* vs code 실행 시 가장 먼저 확인해야 할 것!
* 왼쪽 탐색기가 당일 작업폴더로 연결되어 있는지 확인하기!
* (위) 안되어있다면 -> 파일 -> 작업폴더닫기 후 -> 폴더열기 다시진행!
# html 시작
* git, github 개념공부
* `<태그>` 웹페이지에서 의미적인 정보를 가지는 대상
## HTML5 버전선언
* `<!doctype html>`
## HTML 구조태그
* html : 웹의 시작과 끝. 문서 자체 의미.
* head : 웹 문서의 정보, 제목 포함
* meta : 웹 문서의 정보 기록
* title : 웹 문서의 제목(브라우저 상단 표시)
* body : 웹 문서 내용(실제 대부분의 서비스가 들어가는 본문)
## 구조 태그 속성
* `lang="ko"` html문서 언어 설정
* `charset="utf-"8` 다국어 문자열 설정
* `description` 사이트 요약 설명
* `keywords` 사이트 검색 키워드 설정
## 속성 문법
* `<태그 속성="값" 속성="값"></태그>`
* 태그와 속성 사이 공백
* 속성과 속성 사이 공백(속성 개수 제한없음)
* 속성은 시작태그에만 작성하기!
## 구조태그의 `title` 작성방법
* 메인페이지 -> 사이트명
* 메인페이지 -> 사이트명 | 광고문구추가
* 서브페이지 -> 페이지명 | 사이트명
* ex) 책이름-저자명 | 서점명
* ex) 판매아이템명 | 사이트명
## h1~h6 제목태그(block tag)
* h1~h3 태그는 meta keywords와 동일한 검색키워드로 활용된다.(대제목일수록 높음)
* h4~h6 태그는 거의 사용하지 않는다.
* h1 대제목은 사이트의 로고 및, 서브 페이지 제목에서 주로 사용한다.
* h 제목의 1~6레벨은 순서대로 작성해야 한다.
## 단락 p(block tag)
* 한 줄 또는 여러 줄 단락 묶을 때 사용하는 태그
* 제목(h)태그 종류와는 형제 태그 관계로 사용해야 한다. 부모-자식(x)
## 인라인태그 br, em, strong, del, s, sup, sub
* `br` : 블록 내 줄바꿈 태그
* `em` : 블록 내 강조 태그, 주로 내용 태그(p) 등에서 자식으로 사용
* `strong` : 블록 내 경고용 강조 태그(위와 특징 동일)
* `del` : 삭제 텍스트, 쇼핑몰의 할인 전 가격 등에 사용
* `s` : 교체 텍스트, 쇼핑몰의 할인 전 가격 등에 사용(del 자주사용)
* `sup`,`sub` : 윗첨자(sup) 아래첨자(sub) 수학, 과학등의 기호에 사용
## 인용문 처리 blockquote, q
* `blockquote(block)` : 단락 자체가 인용문에 해당할 때 사용, p태그와 부모-자식 관계로 사용해선 안된다.
* `q(inline)` : 단락(p) 내에서 일부가 인용문에 해당할 때 사용
* 공통특성 `cite="URL"` : `blockquote`, `q`로 인용문 처리할 경우 출처 표시용도로 주소(URL)을 담아주는 속성.