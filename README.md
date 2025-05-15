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
  <li>산술: + - * / %(나머지) //(몫) **(제곱)</li>
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
    <b>if</b> score >= 90<b>:</b>&ensp;  <br>
    &ensp;&nbsp;print('A') <br>
    <b>elif</b> score >= 80<b>:</b>&ensp; <br>
    &ensp;&nbsp;print('B') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&nbsp;print('C') <br>
  </li>

  <li>중첩 if 문 <br>
    <b>if</b> score >= 80<b>:</b>&ensp;  <br>
    &ensp;&ensp;&nbsp;<b>if</b> score >= 90<b>:</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('A') <br>
    &ensp;&ensp;&nbsp;<b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;&ensp;&ensp;print('B') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&ensp;&nbsp;print('C') <br>
  </li>
  

## [5주차 실습&nbsp;-&nbsp;다중 조건문과 문자열](https://github.com/baek-study/python/blob/main/source/week4.ipynb)
### [조건문]()
<ul> 
  <li> if ~ else 문</li>
  <li>연속 if 문 : if~elif~else문 </li>
  <li>중첩 if 문 : if 문 안에 if 문 </li>
</ul>

### [서식 : f-문자열]()
<ul>
  <li> print(f'hi. {name}, age {25}') </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li>
  <li> 자릿수: {25:5d} &ensp; #다섯자리 확보 </li>
  <li> 정밀도: {3.145:.2f} &ensp; #소수점 몇자리 <br>
    &ensp;print(f'hi.{name:10s}, age {25:5d}, {PI:.2f}’)
  </li>  
</ul>

### [print 함수 : 키워드 인수]()
<ul>
  <li> 키워드 인수 sep(구분문자), end(마감문자) <br>
   print('hello', 'world', sep=' ', end='\n') </li>
</ul>

## [5주차 실습&nbsp;-&nbsp;다중 조건문과 문자열](https://github.com/baek-study/python/blob/main/source/week4.ipynb)
### [다중조건문]()
<ul> 
  <li> if ~ else 문</li>
  <li>연속 if 문 : if~elif~else문 </li>
  <li>중첩 if 문 : if 문 안에 if 문 </li>
</ul>

### [서식 : f-문자열]()
<ul>
  <li> print(f'hi. {name}, age {25}')&ensp; # { } 사용 </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li>
  <li> 자릿수: {25:5d} &ensp; #다섯자리 확보 </li>
  <li> 정밀도: {3.145:.2f} &ensp; #소수점 두째자리 <br>
    &ensp;print(f'hi.{name:10s}, age {25:5d}, {PI:.2f}’)
  </li>  
</ul>

### [print 함수 : 키워드 인수]()
<ul>
  <li> 키워드 인수 sep(구분문자), end(마감문자) <br>
   print('hello', 'world', sep=' ', end='\n') </li>
</ul>


## [월요반-5주차 실습&nbsp;-&nbsp;다중 조건식과 문자열](https://github.com/baek-study/python/blob/main/source/week4.ipynb)
### [다중조건문]()
<ul> 
  <li>중첩 if 문 : if 문 안에 if 문 </li>
  <li>연속 if 문 : if~elif~else문 <br>
    <b>if</b> score >= 80<b>:</b>&ensp;  <br>
    &ensp;&nbsp;print('우수') <br>
    <b>elif</b> score >= 60<b>:</b>&ensp; <br>
    &ensp;&nbsp;print('보통') <br>
    <b>else :</b>&ensp; <br>
    &ensp;&nbsp;print('fail') <br>
  </li>
</ul>

### [서식 : f-문자열]()
<ul>
  <li> print(f'hi. {name}, age {25}')&ensp; # { } 사용 </li>
  <li> 형식지정: 정수 d, 실수 f, 문자 s </li>
  <li> 자릿수: {25:5d} &ensp; #다섯자리 확보 </li>
  <li> 정밀도: {3.145:.2f} &ensp; #소수점 두째자리 <br>
    &ensp;print(f'hi.{name:10s}, age {25:5d}, {PI:.2f}’)
  </li>  
  <br>
  <li> 키워드 인수 sep(구분문자), end(마감문자) <br>
   print('hello', 'world', sep=' ', end='\n') </li>
</ul>

### [반복문:while]()
<ul>
  <li>조건 반복 : 조건이 만족하는 동안 실행</li>
  <li> count = 0 # 초기화<br>
  <b>while</b> count < 5 <b>:</b> # 조건 만족하는지? <br>
  &ensp;&ensp;print(f'{count}회') <br> 
  &ensp;&ensp;count += 1 # count 증가 <br> 
  </li>
  <li> <b>while TRUE :</b> #  무한 루프<br>
  &nbsp; &nbsp; 문장들<br>
</li>
<li>보조제어문<br>
  break(반복문 탈출) <br>
  continue(반복 다시 시작) <br>
</li>
</ul>

### [print 함수 : 키워]()
<ul>
<li>조건 반복 while 문 <br>
  &nbsp; <b>while</b> 조건문 <b>:</b> <br>
  &nbsp; &nbsp; &nbsp;문장들<br>
  &nbsp;- &nbsp; while pw!='12':&ensp; pw=input()<br>
  &nbsp;- &nbsp; i=0;&ensp; while i<5:&ensp; i=i+1; print('hi')
</li>
</ul>

### [리스트 생성 및 연산]()
<ul>
<li> 생성 : temps=[28, 31, 33, 35, 27, 26, 25]  </li>
<li>인덱싱[index] : temps[3], temps[-1]  </li>
<li>슬라이싱[start:end]: temps[2:4]  </li>
<li>연산 : +(연결), *(요소반복), in/not in(존재여부)</li>  
<li>함수/메소드 : len(temps), temps.append(55) </li>
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


## [9주차 실습&nbsp;-&nbsp;반복문2](https://github.com/baek-study/python/blob/main/source/week7.ipynb)

<br>

### [반복문:for]()
<ul>
  <li><b>for</b> i <b> in</b> range(0,5,1):&ensp; #0,1,2,3,4 <br>
  &ensp;&ensp;print(f'{i=}')</li>
  <li><b>for</b> ch <b> in</b> 'hello':&ensp; # 문자열<br>
  &ensp;&ensp;print(f'{ch=}')</li>
  <li><b>for</b> i <b> in</b> [0,1,2,3,4]:&ensp;#리스트 <br>
  &ensp;&ensp;print(f'{i=}')</li>
</ul>

### [중첩 for]()
<ul>
<li><b>for</b> i <b>in</b> range(1, 9)<b>:</b> <br>
  &ensp;&ensp; <b>for</b> j <b>in</b> range(1, 9)<b>:</b><br>
  &ensp;&ensp;&ensp;&ensp;print(f"{i}*{j}={i*j}")  # 구구단<br>  
</li>
</ul>

### [보조제어 break, continue]() 


<ul>
<li><b>while True:</b>  <br>
  &ensp;&ensp;num = int(input('입력'))
  &ensp;&ensp;if num == 3 :  <br>
  &ensp;&ensp; &ensp;&ensp;<b>break</b> # 제어를 벗어남 <br>
  &ensp;&ensp;if num%2 == 0 :  <br>
  &ensp;&ensp; &ensp;&ensp;<b>continue</b> # 현재 반복 중단하고 다음반복 시작
  &ensp;&ensp;print(f'{num=}')
</li>

</ul>

<br>

<ul>
<li> break : 반복문 탈출 </li>
<li>continue : 반복 다시 시작 </li>
</li>
</ul>
< br>

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

### [함수 정의&함수 호출]()
<ul>
<li>함수 정의 <br>
  &nbsp; <b>def get_area(radius) :</b> <br>
  &nbsp; &nbsp; area = radius*radius*3.14 <br>
  &nbsp;&nbsp;  <b>return area</b>
  <br>
</li>  
<li>함수 호출 <br>
   &nbsp; result = get_area(10)
   <br>
</li>
</ul>

### [매개변수&반환값]()
<ul>
  <li><b>매개변수:</b> 함수 정의시 값을 전달받는 변수  <br>
  <b>인수:</b> 함수 호출시 실제로 전달되는 값    </li>
  <li><b>반환값:</b>(함수 정의) 함수 결과로 돌려주는 값 <br> 
  <b>결과변수:</b> 함수호출 후 결과대입   </li>
</ul>

### [키워드 인수&디폴트 인수&가변 인수 ]()
<ul>
<li> 기본값 인수 : 함수 정의시 기본값(디폴트값)이 설정됨</li>
<li> 키워드 인수 : 함수 호출시 '키워드 = 값'로 호출 </li>
<li> 가변 인수 : 인수의 갯수가 정해지지 않음</li>
</li>
</ul>

<br>

## [10주차 실습&nbsp;-&nbsp;함수와변수&모듈 ](https://github.com/baek-study/python/blob/main/source/week10.ipynb)

### [지역변수vs전역변수]()
<ul>
<li>  <b>지역변수</b> - 함수<b>내</b>에서 생성된 변수 <br>
  &nbsp; - 함수내에서만 사용 가능
</li>
<li> <b>전역변수</b> : 함수<b>외</b>에서 생성된 변수 <br>
  &nbsp; - 모든 함수에서 사용 가능<br>
  &nbsp; - 함수 내에서 변경시: <b>global</b> 키워드 <br>
</li>
</ul>

### [모듈(module)]()
<ul>
<li> 연관된 함수와 변수를 모아 놓은 파일 </li>
<li> 모듈 가져오는 방법<br>
- <b>import</b> myModule  &ensp;&ensp;# 기본 방법 <br>
- <b>import</b> myModule <b>as</b> 별명  &ensp;&ensp;# 별명(alias)지정   <br>
- <b>from</b> myModule <b>import</b> myFunc &ensp;&ensp; # 특정요소만 <br>
- <b>from</b> myModule <b>import *</b>  &ensp;&ensp; # 전부가져오기 <br>
<li> 모듈 종류 <br>
- 사용자 정의 :직접 작성, .py로 저장<br>
- 표준 모듈 :파이썬 기본 제공 ex)  random <br>
- 외부 모듈 : 설치 필요, pip install <br>
</ul>





<br>


### [모듈(module)]()
<ul>
<li> 정의 : 연관된 함수와 변수를 모아 놓은 파일 </li>
<li> <b>import</b> myModule  &ensp;&ensp;# 기본 방법 </li>
<li><b>import</b> myModule <b>as</b> 별명  &ensp;&ensp;# 별명(alias)지정   </li>
<li><b>from</b> myModule <b>import</b> myFunc &ensp;&ensp; # 특정요소만 </li>
<li><b>from</b> myModule <b>import *</b>  &ensp;&ensp; # 전부가져오기 </li>
</ul>


## [11주차 실습&nbsp;-&nbsp;리스트](https://github.com/baek-study/python/blob/main/source/week11.ipynb)

### [리스트 생성 및 조작]()
<ul>
<li> 생성 : temps=[28, 31, 33, 35, 27]  </li>
<li>인덱싱[index] : temps[3], temps[-1]  </li>
<li>슬라이싱[start:end]: temps[2:4]  </li>
<li>연산 : +(연결), *(반복), in/not in</li>  
<li>복사 : list1 = temps, list2 = list(temps)  
<li>수정: temps[3] = 5, temps[2:4] = [1, 2, 3] 
</ul>


### [리스트 메소드]()
<ul>
  <li> 삽입 : temps.append(55) </li>
  <li> 삭제 : del temps[1]</li>
  <li> temps.sort(), temps.count(33) 등 </li>
</ul>
<br>
  
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

### [파일 읽기]()
<ul>
<li>열기: infile = open('ex.txt', 'r')  </li>
<li>읽기 : contents = infile.read() # 모든 내용을 문자열로<br>
  - infile.readlines() # 각 줄을 리스트로 한꺼번에
  - infile.readline() # 각 줄을 문자열로 하나씩
<li>닫기: infile.close() </li>
</ul>

### [파일 쓰기]()
<ul>
<li>열기: outfile = open('ex.txt', 'w')  </li>
<li>쓰기 : outfile.write() # 문자열 그대로 파일에 씀<br>
  - outfile.writeslines() # 문자열 리스트를 파일에 씀
<li>닫기: outfile.close() </li>
</ul>
<br>


### [with를 이용한 파일 처리]()
<ul>
<li> with 명령어 : 자원 안전하고 효율적 관리 </li>
<li> with open('ex.txt', 'r') as file : 
  while True:
     line = file.readline()
     if line  == ' ' 
       break
<li>닫기: outfile.close() </li>
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

  

