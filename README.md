<h1>서비스 시나리오</h1>
<p>기능적 요구사항</p>
<ol>
  <li>고객이 커피를 주문한다.</li>
  <li>주문되면 커피 제조를 시작한다.</li>
  <li>커피가 완료되면 알림톡이 나간다.</li>
  <li>고객은 커피 제조 상태에 따라 커피를 취소할 수 있다.</li>
  <li>커피를 취소하면 제조를 취소하고 취소 알림톡이 나간다.</li>
  <li>고객은 중간 조회가 가능하다.</li>
</ol>

<p>비기능적 요구사항</p>
<ol>
  <li>커피의 제조 상태가 확인되지 않으면 취소가 되지 않는다.(sync)</li>
  <li>제조 시스템이 비정상적이여도 주문은 받을 수 있다.(async)</li>
  <li>제조 상태가 확인되지 않을 때는 취소 요청을 보류한다.(circuit break)</li>
</ol>
