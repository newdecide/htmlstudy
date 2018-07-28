4-1 javascript란?
4-2 MDN 사이트 참고
4-3 콘솔 사용
4-4 주석 디버깅

MDN web docs 가 교재가 된다.

javascript는 인터프리터형 언어로 컴파일 프로그래밍 보다는 느리다.
node.js 서버로도 사용될수 있다.

ECMAScript가 원래 이름이다.
자바랑은 전혀다른언어이다.함수형 언어이다.

4-5 선언, 할당
네트워크를 통해 올바르게 선언된지 확인한다.

변수, 참조(할당), reference, assignment
camelCase last_year lastYear

선언방법 var let const
할당은 오른쪽에 값이 왼쪽으로 대입된다.
변수는 값이 변하는것.

4-6 문서객체가 가집값 그리고 변수
사용자가 입력한 값을 가져와 연산을 하려면 
type에 id 속성을 주고 콘솔에서 호출시 문자열데이터 값이 출력이 된다. number함수를 통해서 숫자데이터로 바꿔야 정확한 연산이 된다.

4-7 데이터 유형
원시데이터 유형

null
undefined
number
string
boolean
symbol(es6+)

객체데이터 유형
Function object
new Function()
function(){}
Array object
[]
new Array()
Object
new Object()
{}
객체는 대문자로 시작한다.


4-8 네이밍 컨벤션
변수에는 공백이나 특수문자를 사용할수 없다

4-9 동적 형 지정 언어
넘버타입과 스트링값 자동 형변환되어 처리한다.
window.parsInt('문자',10)
window.parsFloat('문자',10)

boolean 0, '', null, undefined==false 1, -1 == true

902+null 숫자, 902+0 숫자 902+undefined == Non

4-10 동일한 변수 이름 문제
여러사람이 사용할시 값이 최상위 변수로 선언되어 undefined 값이 할당될수 있기때문에 id값 설정하고 프로그래밍 하는 것은 좋지 않다. 

4-11 문서 객체에 접근하는 방법
document.getElementById로 찾으면 id값으로 접근해 값을 집어넣어도 문제없이 발생된다.

ELEMENT_NODE vs NodeList vs HTMLCollection

4-12 함수 - 미리 정의된 함수와 사용자 정의 함수
함수는 절차 거쳐야하는 일정한 차례와 방법

window global.object

alert 경고창 confirm 분기 선택권 준다. true, false로 값 획득함.

prompt 최저시급 입력창 줄수 있다.

console.log info(정보제공)
console 생략불가능
함수정의 선언
함수표현식 : 함수의 이름이 없는 상태 변수에 참조한다.

함수를 변수에 담으면 결과값이 반환이 안된다. 
처리되는 행동을 retrun으로 처리해줘야 된다.

함수로 만들어서 재사용하려면 return으로 처리해준다.

함수표현식도 변수에 만들어 return으로 처리해준다.

4-13
조건문 if~else
거짓 판단되는 값
false, undefined, null, 0, NaN, ''

4-14
비교연산자 논리연산자

=== 강한 긍정 !==간한 부정


4-15
switch

4-16
3항식
조건 ? 참 : 거짓

4-17
이벤트 핸들러 함소의 요소로 넣을 수 있고 js에 구현할수있다.

4-18 클릭이벤트 핸들링

4-19 키보드 이벤트 핸들링