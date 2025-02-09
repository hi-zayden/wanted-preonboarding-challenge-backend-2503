# 원티드 프리온보딩 백엔드 챌린지 사전과제

## 과제

1. 서비스를 운영한다면 무엇을 모니터링 해야한다고 생각하는가? 각 항목은 어떻게 모니터링 할 것인가?

2. 다음 코드에서 테스트를 어렵게하는 요인은 무엇때문이라고 생각하는가? 수정 방향은 어떻게 되어야하는가?

```kotlin
class UserService {
    fun registerUser(email: String, password: String) {
        val emailObj = Email(email)
        val passwordObj = Password(password)
        Database.saveUser(emailObj, passwordObj)
        EmailSender.sendConfirmation(emailObj)
    }
}
```

## 과제 제출 방법

- 저장소의 Issues 탭 클릭하고, New issue 버튼을 클릭합니다.
- 템플릿으로 등록해 놓은 사전 과제의 답변을 작성합니다.
  - 제목: `제출일`과 `이름`수정
  - <img width="756" alt="스크린샷 2025-02-10 오전 12 22 09" src="https://github.com/user-attachments/assets/667daf2e-b3b1-435f-b69b-01c5b440cf5d" />

- 사전 과제 제출!
