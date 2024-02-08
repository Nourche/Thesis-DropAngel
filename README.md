# 서울대학교 컴퓨터공학부 박사과정을 위한 학위논문 템플릿

서울대학교 컴퓨터공학부 박사 학위논문 작성을 위한 LATEX 템플릿입니다.
이 템플릿은 `zeta709`님께서 전체 학부에서 조금씩만 수정하면 사용할 수 있게끔 만들어 두신 [버전](https://github.com/zeta709/snuthesis)에 기초해서 컴퓨터공학부만을 위해 수정된 버전입니다.

## 사용법
`thesis.tex` 파일을 열어 학부명, 논문 제목, 저자명, 학번, 지도교수님, 학위 수여일, 논문 인준일, 심사위원 다섯 분 성함만 수정하고 그 아래 부분부터 평소 논문 쓰듯 논문을 쓰시면 됩니다. 레퍼런스는 `thesis.bib` 파일을 사용하시면 됩니다.

### 컴파일
- **make를 사용하는 경우**: 위 파일들과 같은 디렉토리에서 `make` 명령을 입력하면, 자동으로 `target` 디렉토리가 생성되면서 그 안에  `thesis.pdf` 파일을 생성해 줍니다.
- **Overleaf 사용하는 경우**: latex compiler는 pdflatex로 하고, texlive는 2021로 설정해줍니다.

## 작성자
- 최초 작성자: [박성재](https://sjp38.github.io/ko/) (2019.08 졸업)
- 추후 편집자: 
    - [김병창](https://bckim92.github.io) (2022.02 졸업)
    - [김현우](https://hyunw.kim) (2023.05 졸업)

[Pull request](https://github.com/skywalker023/thesis-template-snu-cse) 언제나 환영입니다.