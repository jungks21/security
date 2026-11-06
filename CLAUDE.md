# 이 저장소에서 작업할 때

이 저장소의 `.claude/skills/`에는 프로젝트 스킬이 들어 있다. 요청에 답하거나 작업을 시작하기 전에, 관련된 스킬이 있는지 먼저 확인하고 있으면 그 스킬을 불러서 따른다. 해당될 가능성이 조금이라도 있으면 쓴다.

| 상황 | 스킬 |
|---|---|
| 새 기능이나 변경을 만들기 전, 요구사항과 설계가 불분명할 때 | `brainstorming` |
| 여러 단계로 된 작업의 계획을 세울 때 | `writing-plans` |
| 세운 계획을 실행할 때 | `executing-plans`, `subagent-driven-development` |
| 기능이나 버그 수정을 구현할 때 | `test-driven-development` |
| 버그, 테스트 실패, 예상과 다른 동작을 만났을 때 | `systematic-debugging` |
| 서로 독립적인 작업이 2개 이상일 때 | `dispatching-parallel-agents` |
| 격리된 작업 공간이 필요할 때 | `using-git-worktrees` |
| 작업을 마치고 리뷰를 받을 때, 리뷰 의견을 받았을 때 | `requesting-code-review`, `receiving-code-review` |
| 완료나 통과를 말하기 전 | `verification-before-completion` |
| 구현이 끝나고 브랜치를 정리할 때 | `finishing-a-development-branch` |
| 스킬을 만들거나 고칠 때 | `writing-skills` |
| 코드를 쓰거나 리뷰하거나 리팩터링할 때 | `karpathy-guidelines` |
| 글을 다듬거나 AI가 쓴 티를 없앨 때 | `humanizer` |

스킬 사용법 전반은 `using-superpowers`를 따른다. 사용자가 스킬 이름을 직접 말하면 그 스킬을 우선한다.
