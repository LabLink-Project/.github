# LabLink-BE
### 더 빠르고 더 나은 연구 매칭 플랫폼, LabLink

![브로셔](https://user-images.githubusercontent.com/101865071/236771616-23d0cfe4-5f2d-445d-9feb-802a5755359e.jpeg)
<!-- ![브로셔 연](https://user-images.githubusercontent.com/101865071/236771594-87cefe68-1f44-4e7c-a2df-c0bc4f6ef7d2.jpeg) 
![KakaoTalk_Photo_2023-05-08-12-40-03](https://user-images.githubusercontent.com/101865071/236771627-5f7ad8d0-35af-48b9-9051-5712694554fa.jpeg) -->


**LabLink**는 연구를 위한 지원자를 모집하는 기업/단체와 단기 알바를 원하는 유저간의 매칭을 더 간편하게 도와주는 서비스입니다.

❓실험 연구나 유저테스트 등 테스터를 모집하고 싶었는데 어떻게 모집해야 할 지 모르겠을 때   

❓간단한 테스트로 돈을 벌고 싶을 때   

💡 LabLink를 시작하세요 !   

### ✅ 서비스 핵심 기능

**1. 온라인 오프라인 어디서나 매칭 가능**   

> 오프라인에서 이뤄지는 연구는 물론이고, 온라인상에서 가능한 사용성 테스트, 리서치까지 매칭합니다.   

**2. 복잡한 이력서가 필요없는 쉬운 구인구직**   

> 길고 복잡한 이력어 없이 간단한 이력으로 바로 지원가능합니다.   

**3. 테스트부터 피드백까지 한번에**   

> 온라인의 경우 테스트 이후 피드백까지 한번에 손쉽게 관리할 수 있습니다.   

<!-- ### 📖 IA


![Image](https://user-images.githubusercontent.com/101865071/236615762-16d09584-3a38-447b-a843-a6b55ba16b99.png)
 -->


### 🌐 API 명세서 
[API 명세서 ]()

### 📑 ERD


![Image](https://user-images.githubusercontent.com/101865071/236615682-3d3abf5e-19fc-4094-a67f-25027df383eb.png)


### ⚙️ Service Architecture

![image](https://github.com/LabLink-Project/.github/assets/101865071/9c1ceddd-3107-42f1-b343-5fbb6e59b98e)


### 🛠 Development Environment

### 📌 Branch Strategy

<details>
<summary>Git Workflow</summary>
<div markdown="1">       

```
 1. local - feature에서 각자 기능 작업
 2. 작업 완료 후 local - dev 에 PR 후 Merge
 3. 이후 remote - develop 으로 PR
 4. 코드 리뷰 후 Confirm 받고 Merge
 5. remote - develop 에 Merge 될 때 마다 모든 팀원 remote - dev pull 받아 최신 상태 유지
 ```

</div>
</details>


| Branch Name | 설명 |
| :---: | :-----: |
| main | 초기 세팅 존재 |
| develop | 로컬 develop merge 브랜치 |

### 📌 Commit Convention

##### [TAG] 메시지 

| 태그 이름  |                             설명                             |
| :--------: | :----------------------------------------------------------: |
|  [CHORE]   |                  코드 수정, 내부 파일 수정                   |
|   [FEAT]   |                       새로운 기능 구현                       |
|   [ADD]    | FEAT 이외의 부수적인 코드 추가, 라이브러리 추가, 새로운 파일 생성 |
|  [HOTFIX]  |             issue나 QA에서 급한 버그 수정에 사용             |
|   [FIX]    |                       버그, 오류 해결                        |
|   [DEL]    |                     쓸모 없는 코드 삭제                      |
|   [DOCS]   |                 README나 WIKI 등의 문서 개정                 |
| [CORRECT]  |       주로 문법의 오류나 타입의 변경, 이름 변경에 사용       |
|   [MOVE]   |               프로젝트 내 파일이나 코드의 이동               |
|  [RENAME]  |                파일 이름 변경이 있을 때 사용                 |
| [IMPROVE]  |                     향상이 있을 때 사용                      |
| [REFACTOR] |                   전면 수정이 있을 때 사용                   |

### 📌 Coding Convention
<details>
<summary>변수명</summary>   
<div markdown="1">       
      
 
 1. Camel Case 사용 ex) `lowerCamelCase`
 2. 함수의 경우 동사+명사 사용 ex) `getInformation()`
 3. flag로 사용 되는 변수는 조동사 + flag 종류로 구성 ex) `isNum`
 4. 상수는 모두 대문자로 작성
 5. list 이름 `postList or postlist or posts → **posts**`
 6. 약어는 되도록 사용하지 않는다.
   - 부득이하게 약어가 필요하다고 판단되는 경우 팀원과 상의를 거친다.
 
</div>
</details>

<details>
<summary>주석</summary>
<div markdown="1">       

 한줄 주석은 // 를 사용한다.
  ``` java
    // 한줄 주석일 때
    /**
    * 여러줄
    * 주석일 때
    */
  ```
 
</div>
</details>

### 👩🏻‍💻 Developers   
|엄진식|김성근|이소민|정대철|신도재|
|------|---|---|---|---|
|image|image|image|
|FE|FE|BE|BE|BE|


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
