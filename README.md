<div>데이터를 안보이게 하는 display:none;과 visibility:hidden; 의 차이점에 대해 알았다.</div>
<div>데이터를 안보이게 하기 위해 버튼을 만들고 버튼 클릭 시 display ==none, !==none 을 if문을 사용해 구현했다</div>
<div>하고자 했으나 실패한 구현은</div>
<div>페이지를 새로고침하거나 처음 열었을 당시 display의 현재 값 정보가 없어 처음 누르면 반응이 없다.</div>
<div>페이지를 열자마자 혹은 새로고침 하자마자 데이터의 display 값을 알려주는 방법은 뭘까..</div>
<div>고민하다가 그냥</div>
<div>페이지가 시작하면</div>
<div>클릭 함수를 한번씩 불러서 display 값을 넘겨줘야겠다고 생각했음!</div>
