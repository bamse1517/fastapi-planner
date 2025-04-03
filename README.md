''' bash
1. python -m venv .venv
2. .venv\Scripts\Activate.ps1
3. pip install fastapi uvicorn beanie
'''

''' git
git init
New-Item .gitignore

git add README.md
git commit -m "first commit!"
git branch -M main
git remote add https://깃허브레포주소.git
git push -u origin main
'''

''' bash
root
 -src/
  --models/
  --routes/
  --main.py
--gitignore
--pyproject.toml
--README.md
'''

'''shell
uvicorn src.main:app --roload
'''

# 플래너 만들기

* `로그인`있으면 좋겠다.
    * `이메일`과 `비밀번호` 있으면 좋겠다.
* `이벤트` 추가, 삭제, 업데이트 좋겠다.
    * `제목`, `이미지`, `설명`, `태그`, `위치`, `날짜`