# 코딩테스트
코딩테스트
오늘 1223 확인용 f스트링 이용 \\n 직접입력되도록 

본 문제는 python 의 빠른 기초 학습을 위해 설계된 문제로서 python 코드 제출을 기준으로 설명되어 있습니다. 
------

출력문 연습의 마지막 문제이다.
(생각과 시도를 많이 해야하는 문제들은 한 두 문제씩 넘겼다가 나중에 풀어보면 된다.)

이번에는 다음과 같은 python프로그램의 소스코드를 출력해보자.

print("Hello\nWorld")

위 코드를 정확히 그대로 출력하시오.(공백문자 주의)

 

print 명령 안에 서식 문자로 \n을 사용하면 줄 바꿈(new line) 문자로 사용된다.

그렇다면 \n을 화면에 그대로 출력하려면 어떻게 해야될까?

** 주의 : 본 화면에서 복사하여 붙여넣기하면 제대로 되지 않을 수 있으니 직접 소스코드를 작성해 넣어야 한다.
a = "\\n"
b = f'"Hello{a}World"'
c = f'print({b})'
print(c)
