# python 프로그래밍 입문
파이썬 프로그래밍 입문 수강자가 핵심 내용을 쉽게 알고, 실행 시켜 보는 페이지 입니다. <br> <br>
핵심 : 변수 - 연산자 - 문자열 - 조건문(if) - 반복문(while,for) - 함수 - 모듈 - 복합자료형(리스트, 딕셔너리, 튜플) - 파일 - 객체

<hr size = "10px", width ="500px">

## [12주차 실습&nbsp;-&nbsp;리스트메소드&딕셔너리](https://github.com/baek-study/python/blob/main/source/week12.ipynb)  
<ul>
<li>  리스트 메소드 : 리스트 객체의 함수 <br>
  &emsp;추가 : append(값), insert(삽입위치, 값)<br>
  &emsp;삭제 : del 리스트[인덱스], remove(값), clear(), [:]<br>
  &emsp;찾기 : index(값)<br>
  &emsp;개수 : count(값) # 없는 경우 0
</li>
<br>
<li> 딕셔너리: 키와 쌍으로 구성, 순서없음, 키는 유일<br>
  &emsp;생성 : dic = {키1:값1, 키2:값2,... }<br>
  &emsp;요소접근 : dic[키], dic.get(키)<br>
  &emsp;추가 : dic[새로운 키] = 값<br>
  &emsp;수정 : dic[기존 키] = 새로운 값<br>
  &emsp;삭제 : del dic[키], dic.clear()<br>
  &emsp;유효성 검사 : 키 in dic
</li>
<br>
<li>리스트 반복 <br>
  &emsp;키 목록 : d.keys()<br>
  &emsp;값 목록 : d.values()<br>
  &emsp;키:값 목록 : d.items()<br>
  &emsp;for 반복분 : dic 객체 이용, 키 목록 이용
</li>
</ul>

<hr size = "10px", width ="500px">

<br>

## 1주차
파이썬 소개 - 대화형, 객체지향 언어

<br>

## [2주차 실습&nbsp;-&nbsp;기본 구조](https://github.com/baek-study/python/blob/main/source/week2.ipynb) &emsp; &emsp; [- &nbsp; 1Page 요약](https://github.com/baek-study/python/blob/main/summary/lec2.JPG)
<ul>
  <li>주석: 한줄(#), 여러줄(''', """) </li>
  <li>문장: 처리를 수행하는 명령어 <br>
  <li>표준출력함수 print()<br>
    &ensp; - &nbsp; print('hello'); print(1004) <br>
    &ensp; - &nbsp; 여러개 값: print(2, '+', 3)<br>
    &ensp; - &nbsp; 문자열간 +: print('파이썬을'+'배운다') <br> 
    &ensp; - &nbsp; 출력제어문자: print('탭키\t줄바꿈\n')<br>
    &ensp; - &nbsp; 키워드 sep: print('hello', sep='/') <br>  
    &ensp; - &nbsp; 키워드 end: print('hello', end=' ') 
 </li>
</ul>

<br>

## [3주차 실습&nbsp;-&nbsp;변수와 연산자](https://github.com/baek-study/python/blob/main/source/week3.ipynb)
<ul>
  <li>변수(variable) <br>
    &ensp; - &nbsp; 자료형: 정수, 실수, 문자열, 논리형<br>
    &ensp; - &nbsp; x=1, y=3.1, z='hi', b='True'<br>
    &ensp; - &nbsp; 자료형: type(x)<br>
    &ensp; - &nbsp; 참조값(주소): id(x)
  </li>
  <li>연산자(operator) <br>
    &ensp; - &nbsp;산술: + - * / %(나머지) //(정수나눗셈)<br>
    &ensp; - &nbsp;대입: x=3; x=x+1; x,y=3,5 <br>
    &ensp; - &nbsp;복합: x += 3 &ensp;# x=x+3 <br>
    &ensp; - &nbsp;타입변환: int(3.14), float(3)
  <li>표준 입력 함수 input()<br>
    &ensp;- &nbsp; msg = input('나이는?')&ensp;#문자열리턴<br>
    &ensp;- &nbsp;정수변환: age = int(msg)
  </li>
</ul>
<br>

## [4주차 실습&nbsp;-&nbsp;문자열](https://github.com/baek-study/python/blob/main/source/week4.ipynb)
<ul>
<li>문자열 생성 및 조작 <br>
  &ensp; - &nbsp; 생성: 한줄(', "), 여러줄(''', """)<br>
  &ensp; - &nbsp; 인덱싱 [index]: msg[3]<br>
  &ensp; - &nbsp; 슬라이싱 [start:end:step]: msg[3:5:1]<br>
  &ensp; - &nbsp; 연산+,*: 'hi'+'mju', 'hi'*3 
</li>
<li>문자열 서식 : f-문자열<br>
  &ensp; - &nbsp; print(f'hi. {name}, age {25}') <br>
  &ensp; - &nbsp; 혛식지정: 정수 d, 실수 f, 문자 s, 지수 e <br>
  &ensp; - &nbsp; 자릿수: {name:10d} <br>
  &ensp; - &nbsp; 정밀도: {3.145:.2f} &ensp; #소수점 몇자리
</li>
<li>문자열 함수/메소드 <br>
  &ensp; - &nbsp; 내장함수: len(s), max(s), min(s)<br>
  &ensp; - &nbsp; 메소드 - s.split(), s.count(), s.find()
</li>
</ul>

<br>

## [5주차 실습&nbsp;-&nbsp;조건문](https://github.com/baek-study/python/blob/main/source/week5.ipynb)
<ul>
<li>조건식을 위한 연산자 <br>
  &ensp; - &nbsp; 비교 연산자 : == != > < >= <=<br>
  &ensp; - &nbsp; 논리 연산자 : and or not
</li>
<li>제어문 기본 구성<br>
  &ensp;<b>제어키워드</b> 조건<b>:</b>  &ensp; #헤더<br>
  &ensp; &ensp; 문장들 &emsp;&emsp;&emsp;&ensp; #스위트
</li>
<li>단순 if<br>
  &ensp; <b>if</b> 조건<b>:</b>&ensp; 문장 
</li>
<li>if~else 문<br>
  &ensp; <b>if</b> 조건<b>:</b>&ensp; 문장 <br>
  &ensp; <b>else:</b>&ensp; 문장 
</li>
<li>중첩 if<br>
  &ensp; <b>if</b> 조건<b>:</b>&ensp; if 조건: 문장 <br>
  &ensp; <b>else:</b>&ensp; if 조건: 문장 
</li>
<li>연속 if <br>
  &ensp; <b>if</b> 조건<b>:</b>&ensp;  문장 <br>
  &ensp; <b>else if</b> 조건<b>:</b>&ensp; 문장 <br>
  &ensp; <b>else :</b>&ensp; 문장 <br>
</li>
</ul>

<br>

## [6주차 실습&nbsp;-&nbsp;반복문1](https://github.com/baek-study/python/blob/main/source/week6.ipynb)
<ul>
<li>횟수 반복 for 문 <br>
  &ensp; <b>for</b> 변수 <b>in</b> 범위표현 <b>:</b> <br>
  &ensp; &ensp;&ensp; 문장들<br>
  &ensp;- &nbsp; for i in range(5):&ensp; print('hi')<br>
  &ensp;- &nbsp; for ch in 'hi':&ensp; print(ch)<br>
  &ensp;- &nbsp; for i in [1,2,3]:&ensp; print(i)
<li>조건 반복 while 문 <br>
  &ensp; <b>while</b> 조건문 <b>:</b> <br>
  &ensp; &ensp; &ensp;문장들<br>
  &ensp;- &nbsp; while pw!='12':&ensp; pw=input()<br>
  &ensp;- &nbsp; i=0;&ensp; while i<5:&ensp; i=i+1; print('hi')
</li>
</ul>

<br>

## [7주차 실습&nbsp;-&nbsp;반복문2](https://github.com/baek-study/python/blob/main/source/week7.ipynb)
<ul>
<li>중첩 for <br>
  &ensp; <b>for 변수 in 범위표현:</b> <br>
  &ensp; &nbsp; <b>for i in 범위표현:</b><br>
  &ensp;&ensp;&ensp;문장들<br>
  
<li>무한루프 - while <br>
  &ensp; <b>while TRUE :</b> <br>
  &ensp; &ensp; &ensp;문장들<br>
</li>

<li>보조제어 - break, continue<br>
  &ensp;break(반복문 탈출), continue(반복 다시 시작) <br>
</li>
</ul>

<br>

## [9주차 실습&nbsp;-&nbsp;함수](https://github.com/baek-study/python/blob/main/source/week9.ipynb)
<ul>
<li>함수 정의 - def 함수이름(매개변수) : <br>
  &ensp; <b>def get_area(radius) :</b> <br>
  &ensp; &ensp; area = radius*radius*3.14 <br>
  &ensp;&ensp;  <b>return area</b>
  <br>
  - 매개변수 : 함수 정의시 입력 변수<br>
  - 반환값 : 함수 정의시 수행후 출력 값<br>
</li>  
<li>함수 호출 - 함수이름(인수) <br>
   &ensp; result = get_area(10)
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
  &emsp;&emsp; 함수내에서 사용가능, 함수외에서 사용 불가
</li>
<br>
<li>전역변수 : 함수외에서 생성된 변수 <br>
  &emsp;&emsp; 모든 함수에서 접근 가능<br>
  &emsp;&emsp; 함수 내에서 변경시 - global 키워드 사용 <br>
</li>
<br>
<li>모듈(함수 정의/변수 모아 놓은 파일) 가져오기 <br>
  &emsp;&emsp; <b>import</b> myModule <br>
  &emsp;&emsp; <b>import</b> myModule <b>as</b> 별명<br>
  &emsp;&emsp; <b>from</b> myModule <b>import</b> myFunc<br>
  &emsp;&emsp; <b>from</b> myModule <b>import *</b><br>
  &emsp;&emsp; <b>from</b> myModule <b>import</b> myFunc <b>as</b> 별명<br>
</li>
<br>
<li>표준 모듈 :파이썬이 제공한 모듈 <br>
  &emsp;&emsp; import random;   &emsp;       # 난수모듈<br>
  &emsp;&emsp; random.randint(1, 6) &nbsp;   # 정수 난수함수<br>
</li>

<li>외부 모듈 :파이썬 개발자들이 개발하여 공유 <br>
  &emsp;&emsp; pip install 라이브러리이름   &emsp;       # 외부 모듈 설치 후 사용<br>
  &emsp;&emsp; ex) pip install matplotlib  # 그래프 그리는 라이브러리<br>
  &emsp;&emsp; ex) pip install pillow      # 이미지 처리 라이브러리(<br>
</li>
</ul>

<br>

## [11주차 실습&nbsp;-&nbsp;리스트](https://github.com/baek-study/python/blob/main/source/week11.ipynb)
<ul>
<li>  리스트 : 여러 데이터를 하나로 묶어 순번에 따라 저장 <br>
  &emsp; 생성 : temps=[28, 31, 33, 35, 27]  <br>
  &emsp; 인덱싱[index] : temps[3], temps[-1]  <br>
  &emsp; 슬라이싱[start:end:step]: temps[2:4:1]  <br>
  &emsp; 앝은복사 : list1 = temps # 주소 복사  <br>
  &emsp; 깊은복사 : list2 = list(tmeps) or temps[:) # 요소도 복사  <br>
  &emsp; 연산 : +(연결), *(요소반복), in/not in(존재여부)  
  
</li>
<br>
<li> 리스트 수정<br>
  &emsp; 요소 하나 수정: temps[3] = 5 <br>
  &emsp; 요소 여러개: temps[2:4] = [1, 2, 3] <br>
  &emsp; 요소 하나를 리스트로 수정 : temp[1] = [1, 2] # 주의
</li>
<br>
<li>리스트 반복 <br>
  &emsp;for element in temps : print(element) <br>
  &emsp;&emsp;- 리스트 객체 이용 - 변수는 요소 값 <br>
  &emsp;for i in rangle(0, len(temps)) : print(temps[i]) <br>
  &emsp;&emsp;-range() 함수 이용 - 변수는 인덱스 값 <br>
</li>
<br>
<li>리스트 함수 <br>
  &emsp;내장함수 : len(리스트 이름)   &emsp;       # 리스트 길이<br>
  &emsp;메소드 : temps.append(25)    &emsp;  # 리스트 끝에 추가<br>
</li>
</ul>

<br>

## [12주차 실습&nbsp;-&nbsp;리스트메소드&딕셔너리](https://github.com/baek-study/python/blob/main/source/week12.ipynb)
<ul>
<li>  리스트 메소드 : 리스트 객체의 함수 <br>
  &emsp;추가 : append(값), insert(삽입위치, 값)<br>
  &emsp;삭제 : del 리스트[인덱스], remove(값), clear(), [:]<br>
  &emsp;찾기 : index(값)<br>
  &emsp;개수 : count(값) # 없는 경우 0
</li>
<br>
<li> 딕셔너리: 키와 쌍으로 구성, 순서없음, 키는 유일<br>
  &emsp;생성 : dic = {키1:값1, 키2:값2,... }<br>
  &emsp;요소접근 : dic[키], dic.get(키)<br>
  &emsp;추가 : dic[새로운 키] = 값<br>
  &emsp;수정 : dic[기존 키] = 새로운 값<br>
  &emsp;삭제 : del dic[키], dic.clear()<br>
  &emsp;유효성 검사 : 키 in dic
</li>
<br>
<li>리스트 반복 <br>
  &emsp;키 목록 : d.keys()<br>
  &emsp;값 목록 : d.values()<br>
  &emsp;키:값 목록 : d.items()<br>
  &emsp;for 반복분 : dic 객체 이용, 키 목록 이용
</li>
</ul>

<br>

