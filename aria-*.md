# aria-\*

- aria-required : 스크린 리더 사용자에게 해당 요소가 필수적으로 입력되어야 함을 알려줌
  <input type="text" aria-required="">

- aria-describedby : 어떤 요소에 대한 설명이 나와 있는 태그를 알려줌(간접적)
<form>
    <input type="text" aria-describedby="int2"/>
    <p id="int2">description</p>
</form>

- aria-label : 요소에 대한 설명(직접적)
  <button aria-label="send email">send</button>

- aria-expanded : 탭이 펼쳐져 있는지를 알려줌
<div role="tabpanel" aria-expanded="true"></div>

- aria-pressed : 해당 요소가 현재 토글 되어 있는지 알려줌
  <button aria-pressed="true"></button>
