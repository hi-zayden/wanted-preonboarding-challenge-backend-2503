---
name: 프리온보딩 챌린지 사전과제
about: Describe this issue template's purpose here.
title: "[제출일을 입력해주세요.] 챌린지 사전 과제 - [이름을 입력해주세요.]"
labels: ''
assignees: ''

---

### 1. 서비스를 운영한다면 무엇을 모니터링 해야한다고 생각하는가? 각 항목은 어떻게 모니터링 할 것인가?

### 2. 다음 코드에서 테스트를 어렵게하는 요인은 무엇때문이라고 생각하는가? 수정 방향은 어떻게 되어야하는가?

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
