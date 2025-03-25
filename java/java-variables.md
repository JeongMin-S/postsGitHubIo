---
title: "java variables"
date: "2025-03-20"
category: "Java"
tags: ["Java", "Varialbe"]
---

# _Variable_

## _Variable?_

데이터를 저장할 수 있는 메모리 공간
변수를 선언하면 메모리에 공간이 할당된다. 그 공간에 값을 저장할 수 있다.

```java
//변수 선언
데이터타입 변수이름;
//변수 초기화
데이터타입 변수이름 = 초기값;
int age = 24;
```

변수 초기화?
변수 선언한 후 처음으로 값을 할당(저장)하는 것.

## _변수 종류_

### - 지역 변수

메서드나 블록 내부에서 선언하는 변수.
메서드가 호출될 때 생성되며 종료되면 사라진다.
초기화 후에 사용해야 한다.

```java
public class LocalVariableExample {
    public void printNumber() {
        int number = 10;  // 지역 변수 선언 및 초기화
        System.out.println("Number: " + number);
    }

    public static void main(String[] args) {
        LocalVariableExample example = new LocalVariableExample();
        example.printNumber();
    }
}
```
