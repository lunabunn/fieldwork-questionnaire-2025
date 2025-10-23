# snu-fl-questionnaire 클래스

snu-fl-questionnaire 클래스는 서울대학교 언어학과의 언어조사 질문지 양식을 LaTeX으로 작성하기 위한 클래스입니다.

## 사용법

**XeLaTeX 혹은 LuaLaTeX**을 사용해야 합니다.
pdfLaTeX은 지원하지 않습니다.

### 예시

XeLaTeX을 사용할 경우 아래와 같이 조판할 수 있습니다.
XeLaTeX을 두 번 실행하면 참조가 처리됩니다.[^1]

[^1]: [Overleaf](https://www.overleaf.com/)를 사용하는 경우 이 과정을 자동으로 처리하는 것 같습니다. 이외에도 [Tectonic](https://tectonic-typesetting.github.io/), [Latexmk](https://mg.readthedocs.io/latexmk.html) 등을 사용하여 자동화할 수 있습니다.

```sh
xelatex example
xelatex example
```

[example.tex](example/example.tex) 파일을 참고하세요.

## 저자

- 박준영 [bloomwayz@snu.ac.kr](bloomwayz@snu.ac.kr)

## 라이선스

snu-ling-ba-thesis 클래스는 MIT 라이선스를 따릅니다.
[LICENSE](LICENSE) 파일을 참고하세요.
