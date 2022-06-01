### 1. python 가상환경 생성

- python -m venv 가상환경명
- ex) python -m venv ./venv

### 2. jupyter note 생성 후 markdown 생성까지 code

- c:/Users/lazio1900/Desktop/venv/venv_ver1/Scripts/activate.bat      # activate code
- C:/Users/lazio1900/Desktop/blog/lazio1900.github.io/_posts/ipynb    # ipynb code path
- jupyter nbconvert --to markdown JUPYTER_NOTEBOOK.ipynb              # jupyter notebook file to markdown file

### 3. markdown 생성 후 Git 실행 Code

- C:/Users/lazio1900/Desktop/blog/lazio1900.github.io   # git 실행할 path

- git add .                           # 변경내용 추가
- git status                          # 상태 확인
- git commit -m "commit message"      # 변경 상태 commit. commit message를 상세히 작성하자
- git push                            # commit한 내용을 web에 업로드


