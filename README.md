# MarkDown
## 1. 마크다운 사용법(문법)
* 큰제목: 문서 제목
  
# This is an H1
* 작은제목: 문서 부제목
  
### This is an H2
# This is an H2



* ### 글머리: 1~6까지만 지원
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
####### This is a H7 (지원하지 않음)

## 2. BlockQuote
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

## 3. 목록 
* ### 순서있는 목록(번호)
1. 첫번째
2. 두번째
3. 세번째

현재까지는 어떤 번호를 입력해도 순서는 내림차순으로 정의된다.

1. 첫번째
3. 세번째
2. 두번째

딱히 개선될 것 같지는 않다. 존 그루버가 신경안쓰고 있다고...

* ### 순서없는 목록(글머리 기호: *, +, - 지원)

* 빨강
  * 녹색
    * 파랑
+ 빨강
  + 녹색
    + 파랑
- 빨강
  - 녹색
    - 파랑

혼합해서 사용하는 것도 가능하다(내가 선호하는 방식)

* 1단계
  - 2단계
    + 3단계
      + 4단계
## 4. 코드
4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속된다.

This is a normal paragraph:

    This is a code block.
    
end code block.

한줄 띄어쓰지 않으면 인식이 제대로 안되는 문제가 발생합니다.

This is a normal paragraph:
    This is a code block.
end code block.

## 5.코드블럭
* ### 코드블럭은 다음과 같이 2가지 방식을 사용할 수 있습니다:

<pre>
<code>
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }

}
</code>
</pre>

* ### 코드블럭코드("'''")을 이용하는 방법
```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

* ### 깃헙에서는 코드블럭코드("```") 시작점에 사용하는 언어를 선언하여 문법강조(Syntax highlighting)이 가능하다.
```java
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

## 6. 수평선 <hr/>

* * *

***

*****

- - -

---------------------------------------
  
