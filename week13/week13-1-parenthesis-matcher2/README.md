[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/teCxsaE_)
# Parenthesis Matcher 2

'('와 ')'로만 이루어진 입력에서 여는 괄호 '('의 위치와 닫는 괄호 ')'의 위치의 짝을 찾아 위치를 출력하세요.
단, 출력 순서는 닫는 괄호')'가 나오는 순서를 따릅니다.

|1|2|3|4|5|6|7|8|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|(|(|(|)|)|(|)|)|

즉, 위와 같은 입력에 대해서 닫는 괄호를 기준으로 4, 5, 7, 8의 순서로 괄호 쌍의 위치가 출력되어야 합니다.

- 입력의 길이는 최대 5000 글자를 넘지 않는다고 가정합니다.
- 괄호의 짝이 맞지 않는 경우는 입력으로 들어오지 않습니다.
- 입력에는 공백이 전혀 없으며, 출력은 두 위치를 한 칸의 공백으로 구분하여 출력합니다.

## 입출력 예시
(입력 #1)
```
((())())
```
(출력 #1)
```
3 4
2 5
6 7
1 8
```

## 채점 방법

다음의 명령어를 실행하여 채점을 진행합니다.

```Makefile
make clean all test
```

makefile의 내용이 올바르게 설정되어 있는지 확인해주세요.
