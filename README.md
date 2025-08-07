# Commit Convention

커밋 타입 작성 시 글자 또는 이모지만 작성하여 표현합니다.<br/>
그리고 괄호 사이에 이슈번호를 작성합니다.<br/>
커밋 메시지는 영문 명령 형식으로 작성합니다.

### Good
> `feat :: (#11) implement login logic` or `🧩 :: (#11) implement login logic`

### Bad
> `feat :: implement login logic` or `🧩 :: login logic`

---

## Commit
| Commit Type | Emoji | Description |
| --- | --- | --- |
| build :: | 🔨 | 시스템 또는 외부 종속 파일에 영향을 미치는 설정을 변경합니다. |
| ci :: | ♻️ | ci 구성 파일 및 설정을 변경합니다. |
| chore :: | 🗂 | build 관련, 패키지 설정 등 잡것들을 수행합니다. |
| design :: | 🎨 | 디자인 수정 |
| docs :: | 📝 | 프로젝트 관련 문서 등을 수정/추가합니다. (README.md 등) |
| feat :: | ✨ | 새로운 기능을 추가합니다. |
| fix :: | 🐛 | 기존 프로젝트의 버그를 수정합니다. |
| perf :: | 🛩 | 기존 애플리케이션의 성능을 개선합니다. (예 : 메모리 누수 방지) |
| refactor :: | 🛠 | 사용하지 않는 코드(import, non-used 함수) 제거, 결과의 변화가 없는 코드의 품질을 개선합니다. |
| style :: | 🪄 | 코드를 정리합니다. (예 : 화이트스페이스 제거 등) |
| test :: | 🧪 | 누락된 테스트의 수정을 진행, 기존 테스트를 수정합니다. |
| revert :: | 🧲 | 커밋을 되돌립니다. |
| merge :: | 🔗 | 현재 브랜치를 main/develop 브랜치에 병합합니다. |
| project :: | 🗂 | 프로젝트를 세팅합니다. |
| delete :: | 🗑 | 파일 등을 삭제합니다. |

## Issue, PR
이슈 메시지의 형식에는 제한이 없으며, 주로 기능 구현에 관해 작성합니다.

PR 메시지는 이슈 메시지와 동일하게 작성합니다.<br/>
PR 메시지은 커밋규칙의 형식과 동일합니다.

### Good
> `🖇 :: (#32) 로그인 로직 구현` or `PR :: (#32) implement login logic)`

### Bad
> `🖇 :: 로그인 로직 구현` or `PR :: 로그인 로직 구현`
> 
