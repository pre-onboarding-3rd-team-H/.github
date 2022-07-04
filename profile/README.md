![image](https://static.wanted.co.kr/images/events/2144/764914c4.jpg)

## 👋 Team Members
|Name|Github|Email|
|-----|----|-------|
|이정석|https://github.com/sxxk2|sxxklee@gmail.com| 
|김훈희|https://github.com/nmdkims|nmdkims@gmail.com| 
|고희석|https://github.com/GoHeeSeok00|weeds1590@gmail.com| 
|김상백|https://github.com/tkdqor|aumsbk@naver.com| 
|김민지|https://github.com/my970524|my970524@gmail.com|

## 🗓 프리온보딩 진행 기간
```2022.06.27 ~ 2022.07.29```

## 📕 Projects

## ✅ Git Convenvtion
### Commit message
- 모든 팀원들은 동일한 commit message template을 설정하고 따릅니다.
```
# --- 제목(title) - 50자 이내로 ---
# <타입(type)> <제목(title)>
# 예시(ex) : Docs : #1 README.md 수정
# --- 본문(content) - 72자마다 줄바꾸기  ---
# 예시(ex) :
# - Workflow
# 1. 커밋 메시지에 대한 문서 제작 추가.
# 2. commit message docs add.
# --- 꼬리말(footer) ---
# <타입(type)> <이슈 번호(issue number)>
# 예시(ex) : Fix #122
# --- COMMIT END ---
# <타입> 리스트
#   Init    : 초기화
#   Feat    : 기능추가
#   Add     : 내용추가
#   Update  : 기능 보완 (업그레이드)
#   Fix     : 버그 수정
#   Refactor: 리팩토링
#   Style   : 스타일 (코드 형식, 세미콜론 추가: 비즈니스 로직에 변경 없음)
#   Docs    : 문서 (README.md, ignore파일 추가(Add), 수정, 삭제)
#   Test    : 테스트 (테스트 코드 추가, 수정, 삭제: 비즈니스 로직에 변경 없음)
#   Chore   : 기타 변경사항 (빌드 스크립트 수정 등)
#   Rename  : 이름(파일명, 폴더명, 변수명 등)을 수정하거나 옮기는 작업만인 경우
#   Remove  : 파일을 삭제하는 작업만 수행한 경우  
# ------------------
#     제목 첫 글자를 대문자로
#     제목은 명령문으로
#     제목 끝에 마침표(.) 금지
#     제목과 본문을 한 줄 띄워 분리하기
#     본문은 "어떻게" 보다 "무엇을", "왜"를 설명한다.
#     본문에 여러 줄의 메시지를 작성할 땐 "-" 혹은 "번호"로 구분
# ------------------ 
```
### Branch Strategy
- main-feature 의 구성을 따릅니다.<br>
팀의 멤버는 각자의 작업내용에 맞는 feature 브랜치를 만들어서 작업을 진행합니다. <br>
작업이 끝나면 공용 브랜치인 main 브랜치에 작업 완료된 내용을 병합시키겠다는 내용을 팀원들에게 알리고 병합을 진행하면 되겠습니다.

- feature/이슈번호<br>
각자 맡은 기능을 개발하는 브랜치 입니다. <br>
브랜치 이름은 <b>feature/이슈번호</b>로 하고, 작업이 완료되면 pull request를 진행하여 main 브랜치로 병합합니다.

- main<br>
모든 내용이 문제가 없을 경우에는 main 브랜치로 코드를 병합시켜서 보관합니다.

```
❗️ Pull request & Merge 규칙 ❗️
 - Pull request와 Merge는 다른 사람이 하도록
 - Merge하기 전에 Pull request코드 확인하고 리뷰 남기기
```

## ✅ Code Convention
- Class
  - Pascal case
- Model
  - snake case
- Function
  - snake case
- Variables
  - snake case
 
 ### 주석처리
 - Class, Function의 주석은 class, function 하단에 작성
   - 주석으로 Assignee 작성
 - API의 경우, 상단에 주석으로 url 주소 작성
 ```
 <example>
 
# api/v1/jobs/<int:id>/run
class JobTaskView(APIView):
"""
Assignee : 김아무개
"""

"""
여러 줄인 경우
이와같이 주석을
답니다.
너무 길지 않게 작성합니다.
"""

"""한줄로 작성시에는 이와같이 작성"""
 ```

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
