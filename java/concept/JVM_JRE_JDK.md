# JVM JRE JDK

## JVM

- JVM는 컴퓨터 위에서 Java program bytecode를 실행시키는 주체. / 자바 가상 머신

## JRE

- JRE = JVM + Libraries + Other Components   
    - Libraries : 제작하는 any program에서도 사용 가능한 built-in Java utilities   
                    Ex) System.out.println() : java.lang의 method로. utility 이다.
    - Other Components : debugging 이나 code profiling(memory management / performance) 하는 tools
    - Java Program(for example Planet.class file)을 실행시키기 위해 필요함 => Application Users에게 필요한 것

## JDK

- JDK = JRE + Compliers + Debuggers
    - Java Development Kits -> Java Program을 compile 하고 run 한다.
    - Java source file을 실행시키기 위해서 필요함 => Application developers에게 필요한 것

## +

- debug : Application code의 오류 체크
- compiler : source code 전체를 assembly language로 바꿔줌 (Java)
    - 초기 스캔시간이 오래 걸림. 실행 파일 생성 후에는 빠르다.
    - 기계어 번역과정에서 더 많은 메모리 사용
    - 전체 코드를 스캔하는 과정에서 모든 오류를 한꺼번에 출력해주기 때문에 실행 전에 오류를 알 수 있다.
- interpreter : source code 한줄 한줄 assembly language로 바꿔줌 (python)
    - 한번에 한문장씩 번역후 실행 시키기 때문에 실행 시간이 느리다.
    - 컴파일러와 같은 오브젝트 코드 생성과정이 없기 때문에 메모리 효율이 좋다.
    - 프로그램을 실행시키고 나서 오류를 발견하면 바로 실행을 중지 시킨다. 실행 후에 오류를 알 수 있다.

### Ref

[컴파일러(compiler)와 인터프리터(interpreter)의 차이 - jhur98.log](https://velog.io/@jhur98/%EC%BB%B4%ED%8C%8C%EC%9D%BC%EB%9F%ACcompiler%EC%99%80-%EC%9D%B8%ED%84%B0%ED%94%84%EB%A6%AC%ED%84%B0interpreter%EC%9D%98-%EC%B0%A8%EC%9D%B4)