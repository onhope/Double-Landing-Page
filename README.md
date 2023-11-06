# Double-Landing-Page
<img src="./Double-Landing-Page.gif">

## 기능
마우스 오버를 하면 각 화면의 왼쪽과 오른쪽 이미지가 확대되는 효과 

<br>

## 학습
### 1. css : backdrop-filter
배경에 <span style="background-color:pink; font-weight:bold">반투명 효과</span>를 적용  
<br>
|속성값|의미| 
|------|---| 
|blur()|흐림 효과. (숫자 커질수록 더 흐릿해짐)| 
|brightness()|명도 효과| 
|contrast()|대비 효과| 
|drop-shadow()|그림자 효과| 
|grayscale()|흑백 효과| 
|hue-rotate()|색조 회전 효과| 
|invert()|색 반전 효과| 
|opacity()|불투명도 효과| 
|sepia()|갈색톤 효과| 
|saturate()|채도 효과| 
|url()|SVG 필터 URL|


<br>

### 2. css : white-space
<span style="background-color:pink; font-weight:bold">공백 문자를 처리</span>    
<br>
|속성값|개행 문자|스페이스, 탭|자동 줄 바꿈|줄 끝의 공백|
|------|---|---|---|---|
|normal|병합|병합|예|제거|
|nowrap|병합|병합|아니오|제거|
|pre|유지|유지|아니오|유지 
|pre-wrap|유지|유지|예|넘침
|pre-line|유지|병합|예|제거
|break-spaces|유지|유지|예|줄 바꿈


<br>

### 3. css : background-size
요소의 <span style="background-color:pink; font-weight:bold">배경 이미지 크기</span>를 설정    
<br> 
|속성값|의미| 
|------|---| 
|contain|이미지를 자르거나 늘리지 않고 컨테이너 내에서 이미지 크기를 최대한 크게 조정|
|cover|이미지의 비율을 유지하면서 컨테이너를 채울 수 있는 가장 작은 크기<br>(즉, 높이와 너비가 모두 컨테이너를 완전히 덮음 )로 빈 공간을 남기지 않고 크기를 조정합|
|auto|고유한 비율이 유지되도록 해당 방향으로 배경 이미지의 크기를 조정|

<<br>>

### 4. js : mouseenter, mouseleave VS  mouseover, mouseout
<span style="background: pink; font-weight: bold">mouseenter, mouseover</span>  
: 어떤 요소 안으로 마우스가 들어오는 순간을 감지하는 마우스 이벤트   
<br>
<span style="background: pink; font-weight: bold">mouseleave, mouseout</span>  
: 마우스가 어떤 요소 밖으로 이동하는 순간을 감지하는 마우스 이벤트  
<br>
|속성|차이점|
|---|---|
|MouseOver/Out|지정된 태그 요소(혹은 자신)는 물론이며, 자식 요소가 있다면 해당 자식요소의 영역까지 포함|
|MouseEnter/Leave|지정된 태그 요소(혹은 자신)의 영역에만 해당되며, 만약 자식요소가 있다면 해당 자식요소의 영역은 제외|

## 학습출처 
유튜브  
- https://www.youtube.com/@JavaScriptKing  

mouse이벤트  
- https://velog.io/@commi1106/MouseOver%EC%99%80-MouseEnter%EC%9D%98-%EC%B0%A8%EC%9D%B4-%EC%9D%B4%EB%B2%A4%ED%8A%B8-%EB%B2%84%EB%B8%94%EB%A7%81  
- https://rgy0409.tistory.com/3028

csc 관련  
- https://www.w3schools.com/
- https://developer.mozilla.org/
