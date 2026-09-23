# C언어의 정석

## 📑 Table of Contents

- [Chapter 01 C언어를 시작하기 전에](#ch01)
- [Chapter 02 변수 variable](#ch02)
- [Chapter 03 연산자 operator](#ch03)
- [Chapter 04 조건문과 반복문](#ch04)
- [Chapter 05 배열 array](#ch05)
- [Chapter 06 함수 function](#ch06)
- [Chapter 07 포인터 pointer](#ch07)
- [Chapter 08 함수와 포인터](#ch08)
- [Chapter 09 구조체 structure](#ch09)
- [Chapter 10 표준 라이브러리와 전처리기](#ch10)
- [Chapter 11 파일 입출력](#ch11)

---

## <a id="ch01"></a>Chapter 01 C언어를 시작하기 전에 
| Term & Category | Definition, Role & Example |
| :--- | :--- |
| **C언어로 프로그램을 만드는 과정** | 1. 편집기로 C언어 코드를 작성해서 소스파일(\*.c)에 저장한다. <br> 2. 작성한 소스 파일을 컴파일해서 목적 파일(\*.obj)을 만든다. <br> 3. 2에서 생성된 목적 파일을 링크하여 실행파일(\*.exe)을 만든다. |

---

## <a id="ch02"></a>Chapter 02 변수 variable
| Term & Category | Definition, Role & Example |
| :--- | :--- |
| **변수(variable)** | 단 하나의 값을 저장할 수 있는 메모리 공간 |
| **변수의 명명규칙** | 1. 알파벳(A~Z, a~z), 숫자(0~9), 밑줄(_)만 포함될 수 있다. <br> 2. 대소문자가 구별된다. <br> 3. 숫자로 시작해서는 안 된다. <br> 4. 예약어를 사용해서는 안 된다.|
| **자료형의 종류** | • **기본형(basic type)**<br>&nbsp;&nbsp;├── **문자형:** 문자를 저장하는데 사용되며, 변수당 하나의 문자만 저장할 수 있다.(e.g., `char`)<br>&nbsp;&nbsp;├── **정수형:** 정수를 저장하는데 사용되며, 주로 int가 사용된다.(e.g., `short`, `int(접미사: 없음)`, `long(접미사: L)`, `long long(접미사: LL)`)<br>&nbsp;&nbsp;└── **실수형:** 실수를 저장하는데 사용되며, 주로 double형이 사용된다.(e.g., `float(접미사: F)`, `double(접미사: 없음)`, `long double(접미사: L)`) <br> • **파생형 (derived type):** 기본형으로부터 파생된 것<br>&nbsp;&nbsp;├── **배열(array):** 같은 타입의 여러 변수를 하나로 묶은 타입<br>&nbsp;&nbsp;├── **구조체(structure):** 다른 타입의 여러 변수를 하나로 묶은 타입<br>&nbsp;&nbsp;├── **공용체(union):** 다른 타입의 여러 변수가 하나의 저장공간을 공유하는 타입<br>&nbsp;&nbsp;├── **포인터(pointer):** 메모리 주소를 저장하기 위한 타입<br>&nbsp;&nbsp;└── **함수(function):** 함수를 선언하기 위한 타입. |
| **상수(constant)** | 한 번만 값을 저장할 수 있는 공간 |
| **리터럴(literal)** | 그 자체로 값을 의미하는 것 |
| **전처리(preprocessing)** | 컴파일 직전에 소스코드에 가하는 작업 |
| **전처리기(preprocessor)** | 전처리를 하는 프로그램(컴파일러에 포함) |
| **전처리기 지시자(preprocessor directive)** | 전처리 명령어(#으로 시작하는 라인) |
~p.44
| **** |  |
| **** |  |


---

## <a id="ch03"></a>Chapter 03 연산자 operator

---

## <a id="ch04"></a>Chapter 04 조건문과 반복문

---

## <a id="ch05"></a>Chapter 05 배열 array

---

## <a id="ch06"></a>Chapter 06 함수 function

---

## <a id="ch07"></a>Chapter 07 포인터 pointer

---

## <a id="ch08"></a>Chapter 08 함수와 포인터

---

## <a id="ch09"></a>Chapter 09 구조체 structure

---

## <a id="ch10"></a>Chapter 10 표준 라이브러리와 전처리기

---

## <a id="ch11"></a>Chapter 11 파일 입출력.
