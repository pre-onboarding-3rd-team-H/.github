![image](https://static.wanted.co.kr/images/events/2144/764914c4.jpg)

## ๐ Team Members
|Name|Github|Email|
|-----|----|-------|
|์ด์ ์|https://github.com/sxxk2|sxxklee@gmail.com| 
|๊นํํฌ|https://github.com/nmdkims|nmdkims@gmail.com| 
|๊ณ ํฌ์|https://github.com/GoHeeSeok00|weeds1590@gmail.com| 
|๊น์๋ฐฑ|https://github.com/tkdqor|aumsbk@naver.com| 
|๊น๋ฏผ์ง|https://github.com/my970524|my970524@gmail.com|

## ๐ ํ๋ฆฌ์จ๋ณด๋ฉ ์งํ ๊ธฐ๊ฐ
```2022.06.27 ~ 2022.07.29```

## ๐ Projects

## โ Git Convenvtion
### Commit message
- ๋ชจ๋  ํ์๋ค์ ๋์ผํ commit message template์ ์ค์ ํ๊ณ  ๋ฐ๋ฆ๋๋ค.
```
# --- ์ ๋ชฉ(title) - 50์ ์ด๋ด๋ก ---
# <ํ์(type)> <์ ๋ชฉ(title)>
# ์์(ex) : Docs : #1 README.md ์์ 
# --- ๋ณธ๋ฌธ(content) - 72์๋ง๋ค ์ค๋ฐ๊พธ๊ธฐ  ---
# ์์(ex) :
# - Workflow
# 1. ์ปค๋ฐ ๋ฉ์์ง์ ๋ํ ๋ฌธ์ ์ ์ ์ถ๊ฐ.
# 2. commit message docs add.
# --- ๊ผฌ๋ฆฌ๋ง(footer) ---
# <ํ์(type)> <์ด์ ๋ฒํธ(issue number)>
# ์์(ex) : Fix #122
# --- COMMIT END ---
# <ํ์> ๋ฆฌ์คํธ
#   Init    : ์ด๊ธฐํ
#   Feat    : ๊ธฐ๋ฅ์ถ๊ฐ
#   Add     : ๋ด์ฉ์ถ๊ฐ
#   Update  : ๊ธฐ๋ฅ ๋ณด์ (์๊ทธ๋ ์ด๋)
#   Fix     : ๋ฒ๊ทธ ์์ 
#   Refactor: ๋ฆฌํฉํ ๋ง
#   Style   : ์คํ์ผ (์ฝ๋ ํ์, ์ธ๋ฏธ์ฝ๋ก  ์ถ๊ฐ: ๋น์ฆ๋์ค ๋ก์ง์ ๋ณ๊ฒฝ ์์)
#   Docs    : ๋ฌธ์ (README.md, ignoreํ์ผ ์ถ๊ฐ(Add), ์์ , ์ญ์ )
#   Test    : ํ์คํธ (ํ์คํธ ์ฝ๋ ์ถ๊ฐ, ์์ , ์ญ์ : ๋น์ฆ๋์ค ๋ก์ง์ ๋ณ๊ฒฝ ์์)
#   Chore   : ๊ธฐํ ๋ณ๊ฒฝ์ฌํญ (๋น๋ ์คํฌ๋ฆฝํธ ์์  ๋ฑ)
#   Rename  : ์ด๋ฆ(ํ์ผ๋ช, ํด๋๋ช, ๋ณ์๋ช ๋ฑ)์ ์์ ํ๊ฑฐ๋ ์ฎ๊ธฐ๋ ์์๋ง์ธ ๊ฒฝ์ฐ
#   Remove  : ํ์ผ์ ์ญ์ ํ๋ ์์๋ง ์ํํ ๊ฒฝ์ฐ  
# ------------------
#     ์ ๋ชฉ ์ฒซ ๊ธ์๋ฅผ ๋๋ฌธ์๋ก
#     ์ ๋ชฉ์ ๋ช๋ น๋ฌธ์ผ๋ก
#     ์ ๋ชฉ ๋์ ๋ง์นจํ(.) ๊ธ์ง
#     ์ ๋ชฉ๊ณผ ๋ณธ๋ฌธ์ ํ ์ค ๋์ ๋ถ๋ฆฌํ๊ธฐ
#     ๋ณธ๋ฌธ์ "์ด๋ป๊ฒ" ๋ณด๋ค "๋ฌด์์", "์"๋ฅผ ์ค๋ชํ๋ค.
#     ๋ณธ๋ฌธ์ ์ฌ๋ฌ ์ค์ ๋ฉ์์ง๋ฅผ ์์ฑํ  ๋ "-" ํน์ "๋ฒํธ"๋ก ๊ตฌ๋ถ
# ------------------ 
```
### Branch Strategy
- main-feature ์ ๊ตฌ์ฑ์ ๋ฐ๋ฆ๋๋ค.<br>
ํ์ ๋ฉค๋ฒ๋ ๊ฐ์์ ์์๋ด์ฉ์ ๋ง๋ feature ๋ธ๋์น๋ฅผ ๋ง๋ค์ด์ ์์์ ์งํํฉ๋๋ค. <br>
์์์ด ๋๋๋ฉด ๊ณต์ฉ ๋ธ๋์น์ธ main ๋ธ๋์น์ ์์ ์๋ฃ๋ ๋ด์ฉ์ ๋ณํฉ์ํค๊ฒ ๋ค๋ ๋ด์ฉ์ ํ์๋ค์๊ฒ ์๋ฆฌ๊ณ  ๋ณํฉ์ ์งํํ๋ฉด ๋๊ฒ ์ต๋๋ค.

- feature/์ด์๋ฒํธ<br>
๊ฐ์ ๋งก์ ๊ธฐ๋ฅ์ ๊ฐ๋ฐํ๋ ๋ธ๋์น ์๋๋ค. <br>
๋ธ๋์น ์ด๋ฆ์ <b>feature/์ด์๋ฒํธ</b>๋ก ํ๊ณ , ์์์ด ์๋ฃ๋๋ฉด pull request๋ฅผ ์งํํ์ฌ main ๋ธ๋์น๋ก ๋ณํฉํฉ๋๋ค.

- main<br>
๋ชจ๋  ๋ด์ฉ์ด ๋ฌธ์ ๊ฐ ์์ ๊ฒฝ์ฐ์๋ main ๋ธ๋์น๋ก ์ฝ๋๋ฅผ ๋ณํฉ์์ผ์ ๋ณด๊ดํฉ๋๋ค.

```
โ๏ธ Pull request & Merge ๊ท์น โ๏ธ
 - Pull request์ Merge๋ ๋ค๋ฅธ ์ฌ๋์ด ํ๋๋ก
 - Mergeํ๊ธฐ ์ ์ Pull request์ฝ๋ ํ์ธํ๊ณ  ๋ฆฌ๋ทฐ ๋จ๊ธฐ๊ธฐ
```

## โ Code Convention
- Class
  - Pascal case
- Model
  - snake case
- Function
  - snake case
- Variables
  - snake case
 
 ### ์ฃผ์์ฒ๋ฆฌ
 - Class, Function์ ์ฃผ์์ class, function ํ๋จ์ ์์ฑ
   - ์ฃผ์์ผ๋ก Assignee ์์ฑ
 - API์ ๊ฒฝ์ฐ, ์๋จ์ ์ฃผ์์ผ๋ก url ์ฃผ์ ์์ฑ
 ```
 <example>
 
# api/v1/jobs/<int:id>/run
class JobTaskView(APIView):
"""
Assignee : ๊น์๋ฌด๊ฐ
"""

"""
์ฌ๋ฌ ์ค์ธ ๊ฒฝ์ฐ
์ด์๊ฐ์ด ์ฃผ์์
๋ต๋๋ค.
๋๋ฌด ๊ธธ์ง ์๊ฒ ์์ฑํฉ๋๋ค.
"""

"""ํ์ค๋ก ์์ฑ์์๋ ์ด์๊ฐ์ด ์์ฑ"""
 ```

<!--

**Here are some ideas to get you started:**

๐โโ๏ธ A short introduction - what is your organization all about?
๐ Contribution guidelines - how can the community get involved?
๐ฉโ๐ป Useful resources - where can the community find your docs? Is there anything else the community should know?
๐ฟ Fun facts - what does your team eat for breakfast?
๐ง Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
