# python 프로그래밍 입문
파이썬 프로그래밍 입문 수강자가 핵심 내용을 쉽게 알고, 실행 시켜 보는 페이지 입니다. <br> <br>
핵심 : 변수 - 연산자 - 문자열 - 조건문(if) - 반복문(while,for) - 함수 - 모듈 - 복합자료형(리스트, 딕셔너리, 튜플) - 파일 - 객체

<hr size = "10px", width ="500px">

<br>

## 1주차
파이썬 소개 - 객체지향 언어, 인터프리터 언어

<br>

## [2주차 실습&nbsp;-&nbsp;기본 구조](https://github.com/baek-study/python/blob/main/source/week2.ipynb) 
<ul>
  <li>주석: 한줄(#), 여러줄(''', """) </li>
  <li>문장: 처리를 수행하는 명령어 <br>
  <li>표준출력함수 print()<br>
    &nbsp;- &nbsp; print('hello'); print(1004) <br>
    &nbsp; - &nbsp; 여러개 값: print(2, '+', 3)<br>
    &nbsp; - &nbsp; 문자열간 +: print('파이썬을'+'배운다') <br> 
    &nbsp; - &nbsp; 출력제어문자: print('탭키\t줄바꿈\n')<br>
    &nbsp; - &nbsp; 키워드 sep: print('hello', sep='/') <br>  
    &nbsp; - &nbsp; 키워드 end: print('hello', end=' ') 
 </li>
</ul>
<br>


## [3주차 실습&nbsp;-&nbsp;변수와 연산자](https://github.com/baek-study/python/blob/main/source/week3.ipynb)

### [변수 개념]()
<ul>
  <li>변수 : 데이터를 저장하는 공간 </li>
  <li>이름 규칙 : 알파벳(a~z, A~Z), 숫자(0~9), 밑줄(_)로 구성 </li>
  <li> 시작시 숫자 안됨, 이름내 공백 안됨, 예약어 안됨 </li>
</ul>

### [파이썬에서 변수]()
<ul>
  <li>변수이름 = 값 &ensp; </li>
  <li> 왼쪽은 항상 변수이름 </li>

  <li> x=1; y=3.14; z='hi'; b=True; </li>
</ul>

### [표준 입력함수 input()]()
<ul>
   <li>키보드를 통해 입력한 값을 하나의 '문자열' 형태로 반환</li>
    <li> msg = input('[안내메시지] 나이는?')&ensp;#문자열로 반환</li>
    <li> age = int(msg)&ensp;#정수변환</li>
    <li> fage = float(msg)&ensp;#실수변환</li>
</ul>

### [연산자]()
<ul>
    <li>산술: + - * / %(나머지) //(몫) **(제곱)</li>
    <li>대입: x=3; x=x+1; &ensp; # 왼쪽은 항상 변수이름 </li> 
</ul>

<br>



## [4주차 실습&nbsp;-&nbsp;조건문](https://github.com/baek-study/python/blob/main/source/week5.ipynb)

### [연산자]()
<ul>
  <li>대입: x=3; x=x+1; x=y=z=1;<br>
   &ensp; x,y = 1, 2; x, y = y,x; </li> 
  <li>복합: x+=3 &ensp;# x=x+3 같은의미  <br>
  &ensp;- 대입과 산술 연산자 결합 </li>
  <li>비교 : == != > < >= <= <br>
  &ensp;- ==(같다), !=(같지않다)<br>
  &ensp;- >=, <=에서 =가 항상 뒤 </li>
  <li>논리 : and or not</li>
</ul>

### [조건문]()
<ul>    
  <li>if 문<br>
    <b>if</b> score >= 60<b>:</b>&ensp;<br>
    &ensp;&nbsp;  print('pass') <br>
  </li>
  <li>if~else 문<br>
    <b>if</b> score >= 60<b>:</b>&ensp;<br>
    &ensp;&nbsp;  print('pass') <br>
    <b>else:</b>&ensp; <br>
    &ensp;&nbsp;  print('fail')
  </li>
<br>
</ul>

  <li>연속 if 문 <br>
    <b>if</b> score >= 80<b>:</b>&ensp;  <br>
    &ensp;&nbsp;print('우수') <br>
    <b>elif</b> score >= 60<b>:</b>&ensp; <br>
    &ensp;&nbsp;print('보통') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&nbsp;print('fail') <br>
  </li>

  <li>중첩 if 문 <br>
    <b>if</b> score >= 80<b>:</b>&ensp;  <br>
    &ensp;&ensp;&nbsp;<b>if</b> score >= 90<b>:</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('우수') <br>
    &ensp;&ensp;&nbsp;<b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('보통') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;print('fail') <br>
  </li>
  

## [5주차 실습&nbsp;-&nbsp;다중 조건문과 문자열](https://github.com/baek-study/python/blob/main/source/week4.ipynb)
### [다중조건문]()
<ul>    
  <li>연속 if 문 : if~elif~else문 </li>
  <li>중첩 if 문 : if 문 안에 if 문 </li>
</ul>

### [문자열 생성 및 조작]()
<ul>
 <li>생성: msg = 'Hello, World' <br>
   &ensp; 한줄(', "), 여러줄(''', """) 
 </li>
 <li>인덱싱 [index]: msg[3]</li>
 <li>슬라이싱 [start:end:step]: msg[3:5:1]</li>
 <li>연산+,*: 'hi'+'mju', 'hi'*3 </li>

</ul>

### [문자열 서식 : f-문자열]()
<ul>
  <li> print(f'hi. {name}, age {25}') </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li>
  <li> 자릿수: {name:10d} </li>
  <li> 정밀도: {3.145:.2f} &ensp; #소수점 몇자리 <br>
    &ensp;print(f’{num:5d}’), print(f’{PI:.2f}’)
  </li>
  
</ul>




## [5주차 실습&nbsp;-&nbsp;다중 조건식과 문자열](https://github.com/baek-study/python/blob/main/source/week4.ipynb)
### [다중조건문]()
<ul>    
  <li>연속 if 문 <br>
    <b>if</b> score >= 80<b>:</b>&ensp;  <br>
    &ensp;&nbsp;print('우수') <br>
    <b>elif</b> score >= 60<b>:</b>&ensp; <br>
    &ensp;&nbsp;print('보통') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&nbsp;print('fail') <br>
  </li>
<br>
  <li>중첩 if 문 <br>
    <b>if</b> score >= 80<b>:</b>&ensp;  <br>
    &ensp;&ensp;&nbsp;<b>if</b> score >= 90<b>:</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('우수') <br>
    &ensp;&ensp;&nbsp;<b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('보통') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;print('fail') <br>
  </li>
</ul>

### [문자열 생성 및 조작]()
<ul>
 <li>생성: msg = 'Hello, World' <br>
   &ensp; 한줄(', "), 여러줄(''', """) 
 </li>
 <li>인덱싱 [index]: msg[3]</li>
 <li>슬라이싱 [start:end:step]: msg[3:5:1]</li>
 <li>연산+,*: 'hi'+'mju', 'hi'*3 </li>

</ul>

### [문자열 서식 : f-문자열]()
<ul>
  <li> print(f'hi. {name}, age {25}') </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s, 지수 e </li>
  <li> 자릿수: {name:10d} </li>
  <li> 정밀도: {3.145:.2f} &ensp; #소수점 몇자리</li>
</ul>


<br>
<ul>
<li>조건식을 위한 연산자 <br>
  &nbsp; - &nbsp; 비교 : == != > < >= <=<br>
  &nbsp; - &nbsp; 논리 : and or not
</li>
<br>
<li>if~else 문<br>
  &nbsp; <b>if</b> score >= 60<b>:</b>&ensp;<br>
  &ensp; print('pass') <br>
  &nbsp; <b>else:</b>&ensp; <br>
  &ensp;print('fail')
</li>
<br>
<li>중첩 if<br>
  &nbsp; <b>if</b> score >= 60 <b>:</b>&ensp;<br>
  &nbsp; &nbsp; &nbsp; &nbsp; if score >= 80: print('우수') <br>
  &nbsp; &nbsp; &nbsp; &nbsp; else : print('보통')<br>
  &nbsp; <b>else:</b>&ensp; <br>
  &ensp;print('fail')
</li>
<br>
<li>연속 if <br>
  &nbsp; <b>if</b> score >= 80<b>:</b>&ensp;  print('우수') <br>
  &nbsp; <b>elif</b> score >= 60<b>:</b>&ensp; print('보통') <br>
  &nbsp; <b>else :</b>&ensp; print('fail') <br>
</li>
</ul>


## [6주차 실습&nbsp;-&nbsp;반복문1](https://github.com/baek-study/python/blob/main/source/week6.ipynb)
<ul>
<li>횟수 반복 for 문 <br>
  &nbsp; <b>for</b> 변수 <b>in</b> 범위표현 <b>:</b> <br>
  &nbsp; &nbsp;&nbsp; 문장들<br>
  &nbsp;- &nbsp; for i in range(5):&ensp; print('hi')<br>
  &nbsp;- &nbsp; for ch in 'hi':&ensp; print(ch)<br>
  &nbsp;- &nbsp; for i in [1,2,3]:&ensp; print(i)
<li>조건 반복 while 문 <br>
  &nbsp; <b>while</b> 조건문 <b>:</b> <br>
  &nbsp; &nbsp; &nbsp;문장들<br>
  &nbsp;- &nbsp; while pw!='12':&ensp; pw=input()<br>
  &nbsp;- &nbsp; i=0;&ensp; while i<5:&ensp; i=i+1; print('hi')
</li>
</ul>

<br>

## [7주차 실습&nbsp;-&nbsp;반복문2](https://github.com/baek-study/python/blob/main/source/week7.ipynb)
<ul>
<li>중첩 for <br>
  &nbsp; <b>for 변수 in 범위표현:</b> <br>
  &nbsp; &nbsp; <b>for i in 범위표현:</b><br>
  &nbsp;&nbsp;&nbsp;문장들<br>
  
<li>무한루프 - while <br>
  &nbsp; <b>while TRUE :</b> <br>
  &nbsp; &nbsp; &nbsp;문장들<br>
</li>

<li>보조제어 - break, continue<br>
  &nbsp;break(반복문 탈출), continue(반복 다시 시작) <br>
</li>
</ul>

<br>

## [4주차 실습&nbsp;-&nbsp;문자열](https://github.com/baek-study/python/blob/main/source/week4.ipynb)
<ul>
<li>문자열 생성 및 조작 <br>
  &nbsp; - &nbsp; 생성: 한줄(', "), 여러줄(''', """)<br>
  &nbsp; - &nbsp; 인덱싱 [index]: msg[3]<br>
  &nbsp; - &nbsp; 슬라이싱 [start:end:step]: msg[3:5:1]<br>
  &nbsp; - &nbsp; 연산+,*: 'hi'+'mju', 'hi'*3 
</li>
<li>문자열 서식 : f-문자열<br>
  &nbsp; - &nbsp; print(f'hi. {name}, age {25}') <br>
  &nbsp; - &nbsp; 혛식지정: 정수 d, 실수 f, 문자 s, 지수 e <br>
  &nbsp; - &nbsp; 자릿수: {name:10d} <br>
  &nbsp; - &nbsp; 정밀도: {3.145:.2f} &ensp; #소수점 몇자리
</li>
<li>문자열 함수/메소드 <br>
  &nbsp; - &nbsp; 내장함수: len(s), max(s), min(s)<br>
  &nbsp; - &nbsp; 메소드 - s.split(), s.count(), s.find()
</li>
</ul>

<br>

## [9주차 실습&nbsp;-&nbsp;함수](https://github.com/baek-study/python/blob/main/source/week9.ipynb)
<ul>
<li>함수 정의 - def 함수이름(매개변수) : <br>
  &nbsp; <b>def get_area(radius) :</b> <br>
  &nbsp; &nbsp; area = radius*radius*3.14 <br>
  &nbsp;&nbsp;  <b>return area</b>
  <br>
  - 매개변수 : 함수 정의시 입력 변수<br>
  - 반환값 : 함수 정의시 수행후 출력 값<br>
</li>  
<li>함수 호출 - 함수이름(인수) <br>
   &nbsp; result = get_area(10)
   <br>
  - 인수 : 함수 호출시 입력되는 실제 값<br>
</li>
<li>키워드 인수, 디폴트 인수, 가변 인수 
<br> 정의 : print(*args, sep = ' ', end = '\n' .... )  # sep, end는 디폴트 인수, args는 가변인수
<br> 호출 : print(2, end = ' ')  # end 는 키워드 인수
<br> 호출 : print(2, 3, 4 )  # end 는 디폴트 값 이용
</li>

</ul>

<br>

## [10주차 실습&nbsp;-&nbsp;함수와모듈](https://github.com/baek-study/python/blob/main/source/week10.ipynb)
<ul>
<li>  지역변수 - 함수내에서 생성된 변수 & 매개변수 <br>
  &nbsp; 함수내에서 사용가능, 함수외에서 사용 불가
</li>
<br>
<li>전역변수 : 함수외에서 생성된 변수 <br>
  &nbsp; 모든 함수에서 접근 가능<br>
  &nbsp; 함수 내에서 변경시 - global 키워드 사용 <br>
</li>
<br>
<li>모듈(함수 정의/변수 모아 놓은 파일) 가져오기 <br>
  &nbsp; <b>import</b> myModule <br>
  &nbsp; <b>import</b> myModule <b>as</b> 별명<br>
  &nbsp; <b>from</b> myModule <b>import</b> myFunc<br>
  &nbsp; <b>from</b> myModule <b>import *</b><br>
  &nbsp; <b>from</b> myModule <b>import</b> myFunc <b>as</b> 별명<br>
</li>
<br>
<li>표준 모듈 :파이썬이 제공한 모듈 <br>
  &nbsp; import random;   &emsp;       # 난수모듈<br>
  &nbsp; random.randint(1, 6) &nbsp;   # 정수 난수함수<br>
</li>

<li>외부 모듈 :파이썬 개발자들이 개발하여 공유 <br>
  &nbsp; pip install 라이브러리이름   &emsp;       # 외부 모듈 설치 후 사용<br>
  &nbsp; ex) pip install matplotlib  # 그래프 그리는 라이브러리<br>
  &nbsp; ex) pip install pillow      # 이미지 처리 라이브러리(<br>
</li>
</ul>

<br>

## [11주차 실습&nbsp;-&nbsp;리스트](https://github.com/baek-study/python/blob/main/source/week11.ipynb)
<ul>
<li>  리스트 : 여러 데이터를 하나로 묶어 순번에 따라 저장 <br>
  &nbsp; 생성 : temps=[28, 31, 33, 35, 27]  <br>
  &nbsp; 인덱싱[index] : temps[3], temps[-1]  <br>
  &nbsp; 슬라이싱[start:end:step]: temps[2:4:1]  <br>
  &nbsp; 앝은복사 : list1 = temps # 주소 복사  <br>
  &nbsp; 깊은복사 : list2 = list(tmeps) or temps[:) # 요소도 복사  <br>
  &nbsp; 연산 : +(연결), *(요소반복), in/not in(존재여부)  
  
</li>
<br>
<li> 리스트 수정<br>
  &nbsp; 요소 하나 수정: temps[3] = 5 <br>
  &nbsp; 요소 여러개: temps[2:4] = [1, 2, 3] <br>
  &nbsp; 요소 하나를 리스트로 수정 : temp[1] = [1, 2] # 주의
</li>
<br>
<li>리스트 반복 <br>
  &nbsp;for element in temps : print(element) <br>
  &nbsp;- 리스트 객체 이용 - 변수는 요소 값 <br>
  &nbsp;for i in rangle(0, len(temps)) : print(temps[i]) <br>
  &nbsp;-range() 함수 이용 - 변수는 인덱스 값 <br>
</li>
<br>
<li>리스트 함수 <br>
  &nbsp;내장함수 : len(리스트 이름)   &emsp;       # 리스트 길이<br>
  &nbsp;메소드 : temps.append(25)    &emsp;  # 리스트 끝에 추가<br>
</li>
</ul>

<br>

## [12주차 실습&nbsp;-&nbsp;리스트메소드&딕셔너리](https://github.com/baek-study/python/blob/main/source/week12.ipynb)
<ul>
<li>  리스트 메소드 : 리스트 객체의 함수 <br>
  &nbsp;추가 : append(값), insert(삽입위치, 값)<br>
  &nbsp;삭제 : del 리스트[인덱스], remove(값), clear(), [:]<br>
  &nbsp;찾기 : index(값)<br>
  &nbsp;개수 : count(값) # 없는 경우 0
</li>
<br>
<li> 딕셔너리: 키와 쌍으로 구성, 순서없음, 키는 유일<br>
  &nbsp;생성 : dic = {키1:값1, 키2:값2,... }<br>
  &nbsp;요소접근 : dic[키], dic.get(키)<br>
  &nbsp;추가 : dic[새로운 키] = 값<br>
  &nbsp;수정 : dic[기존 키] = 새로운 값<br>
  &nbsp;삭제 : del dic[키], dic.clear()<br>
  &nbsp;유효성 검사 : 키 in dic
</li>
<br>
<li>리스트 반복 <br>
  &nbsp;키 목록 : d.keys()<br>
  &nbsp;값 목록 : d.values()<br>
  &nbsp;키:값 목록 : d.items()<br>
  &nbsp;for 반복분 : dic 객체 이용, 키 목록 이용
</li>
</ul>

<br>

## [13주차 실습&nbsp;-&nbsp;리스트와함수&파일](https://github.com/baek-study/python/blob/main/source/week13.ipynb)  
<ul>
<li>  리스트와 함수 <br>
  &nbsp;매개변수 : def func1(list)  <br>
  &nbsp;- 함수내 리스트 요소 변경 가능<br>
  &nbsp;- 함수내 리스트 객체 변경 - 새로운 객체로 간주<br>
  &nbsp;리턴형 : def func2():... return lst<br>
  &nbsp;- result = func2()
</li>
<br>
<li> 딕셔너리와 함수<br>
  &nbsp;매개변수 : 딕셔너리와 키 필요 <br>
  &nbsp;- def func3(dic, key) :<br>
  &nbsp;- 유효성 검사 필요 (key in dic)
</li>
<br>
<li>파일  <br>
  &nbsp;3단계: open()-read()-close()<br>
  &nbsp;파일읽기:in = open("file", <b>"r"</b>)<br>
  &nbsp;- in.read(), readlines(), readline()<br>
  &nbsp;파일쓰기:out = open("file", <b>"w"</b>)<br>
  &nbsp;- out.write(), writelines()
</li>
</ul>


<br>

## [14주차 실습&nbsp;-&nbsp;파일2&클래스와객체](https://github.com/baek-study/python/blob/main/source/week14.ipynb)  

<ul>
<li>  파일2 <br>
  - 파일 읽기: 파일 객체(변수) 이용 <br>
  &ensp;for line in infile:<br>
  &ensp;&emsp; print(line.strip())<br>
  - with 명령문: 파일 안전하게 처리 <br>
  &ensp;with open('a.txt', 'r') as file:
</li>
<br>
<li> 클래스와 객체 <br>
  - 클래스: 설계도, 데이터+메소드 <br>
  - 객체 : 클래스에서 생성된 실체<br>
</li>
<br>
<li>클래스 정의 - 메소드 정의  <br>
  - <b>class</b> Counter : # class 이름: <br> 
  &emsp; def func1(<b>self</b>, ... ) : <br> 
  &emsp;&emsp; <b>self.</b>b>count = 1, ...  <br> 
</li>
<br>
<li>객체 생성 & 객체 접근  <br>
  - 객체생성 : 객체 = 클래스 이름()  <br> 
  &ensp; a = Counter() <br> 
  - 객체 접근 : . 연산자 이용 <br> 
  &ensp; a.func1()  # 메소드 접근<br> 
  &ensp; print(a.count) # 데이터 접근
</li>
<br>
</ul>

  

