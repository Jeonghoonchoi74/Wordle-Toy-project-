# Python Wordle Game (파이썬 워들)

파이썬(Python)과 `tkinter`를 사용하여 만든 워들(Wordle) 게임의 클론(Clone) 버전입니다.  
외부 라이브러리 설치 없이 파이썬만 있으면 바로 실행할 수 있는 GUI 게임입니다.

![Wordle Game](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Wordle_196_example.svg/1200px-Wordle_196_example.svg.png)
*(예시 이미지)*

## 주요 기능 (Features)

*   **GUI 인터페이스**: 직관적인 그래픽 사용자 환경 (Tkinter 사용).
*   **방대한 단어장**: A부터 Z까지 수천 개의 5글자 영단어가 포함되어 있어 매번 새로운 게임을 즐길 수 있습니다.
*   **가상 키보드**: 화면 하단에 QWERTY 키보드가 표시되며, 사용한 알파벳의 상태(정답/위치다름/오답)를 실시간으로 보여줍니다.
*   **깔끔한 디자인**: 눈이 편안한 화이트 테마와 직관적인 색상 피드백을 제공합니다.

## 실행 방법 (How to Run)

1.  파이썬(Python 3.x)이 설치되어 있는지 확인합니다.
2.  터미널(또는 CMD, PowerShell)에서 `wordle.py`가 있는 폴더로 이동합니다.
3.  아래 명령어를 입력하여 게임을 실행합니다.

```bash
python wordle.py
```

## 게임 규칙 (Rules)

1.  **목표**: 6번의 기회 안에 무작위로 선정된 **5글자 영어 단어**를 맞춰야 합니다.
2.  **입력**: 키보드로 5글자 단어를 입력하고 `Enter` 키를 누르세요.
3.  **피드백**: 제출 후 각 글자의 색상이 변합니다.
    *   **초록색 (Green)**: 글자와 위치가 모두 정확합니다.
    *   **노란색 (Yellow)**: 글자는 정답에 포함되지만, 위치가 틀렸습니다.
    *   **검정색 (Black)**: 정답 단어에 포함되지 않는 글자입니다.
4.  **종료**: 정답을 맞추거나 6번의 기회를 모두 소진하면 게임이 종료됩니다.
5.  **재시작**: 게임 종료 후 `Enter` 키를 누르면 즉시 새 게임이 시작됩니다.

## 요구 사항 (Requirements)

*   Python 3.x
*   (별도의 `pip install`은 필요하지 않습니다)

## 라이센스 (License)

이 프로젝트는 **MIT License**에 따라 자유롭게 수정 및 배포가 가능합니다. 소스 코드 상단의 라이센스 고지를 참고하세요.

## 출처 (Credits)

*   **단어 리스트 (Word List)**: [WordUnscrambler.net - Wordle Word List](https://www.wordunscrambler.net/word-list/wordle-word-list)에서 가져왔습니다.
