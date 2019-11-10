# 잊지말자 표기법
    1. 카멜 표기법
        - 맨 앞에오는 단어만 소문자로 표기하고, 뒤에오는 단어는 대문자로 표기하는 방법.
         ex) appleJam

    2. 파스칼 표기법
        - 모든 단어가 대문자로 시작하는 방법. 
        ex) AppleJam
    
    3. 스네이크 표기법
        - 언더바를 붙여 단어를 구분짓는 방법. 
        ex) apple_jam

## 여러가지 중요 html태그들

#### 텍스트 관련 태그

**h1~h6**
제목 태그, 제목 용도 이외에는 사용하지 않기

**b**
글자를 굵게 표시해주고 싶을 때 사용, 하지만 지양하기. 아무 의미가 없기 때문.

**strong**
글자를 굵게 표시해주고 싶을 때 사용, 지향하기. 강하다라는 의미를 가짐.

**small**
텍스트를 작게 지정함.

**mark**
형광펜으로 그은 것 처럼 노랗게 강조해줌.

**del**
텍스트 가운데에 선을 그어 지운 것처럼 표현해줌.

**i**
기울임체 지정. 지양하기. 아무 의미가 없기 때문.

**em**
기울임체 지정. 지향하기. emphasized(강조, 중요한)의 의미를 가짐.

**ins**
글자에 밑줄을 긋고 싶을 때 사용. 지향하기. inserted(added)의 의미를 가짐.

**u**
글자에 밑줄을 긋고 싶을 때 사용. 지양하기. 아무 의미가 없기 때문.

**sub**
글자를 아래로 내려 보여줌. subscripted(아래에 쓰인)의 의미를 가짐. 

**sup**
글자를 위로 올려 보여줌. superscripted(위에 쓰인)의 의미를 가짐.

#### 본문 태그

**p**
단락(Paragraphs)을 지정함. 

**br**
강제 개행을 지정함. 빈 요소임. 종료태그 없음.

**pre**
그대로 브라우저에 표현됨.

**hr**
수평줄을 삽입함.

**q**
짧은 인용문(quotation)

**blockquote**
긴 인용문. 들여쓰기를 함.

#### input태그
**굵은 글씨**는 모두 type어트리뷰트 값이다.

**button**
버튼 생성

**checkbox**
체크박스 생성

**color**
컬러 선택 버튼 생성

**date**
년월일 입력 칸 생성

**email**
이메일 입력 

**image**
이미지로 되어있는 submit botton

**radio**
radio button 생성

**range**
범위 선택 form 생성

**reset**
초기화 버튼

**submit**
제출 버튼

**search**
검색어 입력

**tel**
전화번호 입력

**text**
텍스트 입력

**url**
url 입력 form 생성

**week**
주 선택 입력 form 생성

#### select

여러 개의 리스트에서 여러 개의 아이템을 선택할 때 사용.
select form 안에 option을 생성하여 사용한다.

tag | Description
-----|-----
select | select form 생성
option | 고르는 option 생성
optgroup | option을 그룹화하여 분류

#### textarea

여러 줄의 글자를 입력할 때 사용한다.
이름 그대로 **글자의 공간**을 만들어준다.

#### button

클릭할 수 있는 버튼을 생성한다. input type 속 button과는 다르다.
        
    <button type="button" onclick="alert('Hello World!')">Click Me!</button>

    <input type="button" value="Click Me!" onclick="alert('Hello world!')">

type 어트리뷰트는 반드시 지정하는 것이 바람직하다. button 태그의 어트리뷰트 값으로 button, reset, submit등을 지정할 수 있다.

#### fieldset / legend

`fieldset `
**관련된 입력 양식들을 그룹화**할 때 사용한다. 

`legend`
**fieldset 태그 내에서** 사용되야 하며 그룹화된 **fieldset의 제목을 정의**한다.