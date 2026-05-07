# Use case description: 로그인

**Precondition**: 사용자는 등록된 회원이거나 관리자 계정(`admin / admin`)으로 인증할 수 있는 상태이다.

**Basic Flow**:

| Actor Action | System Response |
|---|---|
|   | 1. ID와 비밀번호 입력 필드가 포함된 로그인 화면을 표시한다 |
| 2. ID와 비밀번호를 입력하고 [로그인] 버튼을 누른다 |   |
|   | 3. 로그인을 완료하고 사용자 권한에 해당하는 메인 화면을 표시한다 |

**Alternative Courses**:
- 3a. ID 또는 비밀번호가 일치하지 않는 경우: 시스템은 "ID 또는 비밀번호가 올바르지 않습니다" 안내를 표시한다. Actor는 단계 2로 돌아간다.

**Postcondition**: 사용자는 로그인된 상태가 되며, 권한(회원 또는 관리자)에 따른 기능을 이용할 수 있다.