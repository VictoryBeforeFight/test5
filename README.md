# 깃 연습

## Git workflow

### 전체 플로우
1. github main repo create (open repo(main branch))
2. local PC main clone (local pull only branch)
3. local PC SUB Branch create (local my branch)
4. github SUB Branch push (local my branch -> open repo)
5. github에서 pull request (local my branch -> main branch)
=> github main repo(main branch)에 추가됨

---

6. local PC main pull
=> 업데이트 된 main repo 적용

---
### info
- 원격 저장소가 자신의 소유이거나 collaborator로 등록되어 있는 경우에 가능
- master에 직접 개발하는 것이 아니라, 기능별로 브랜치를 따로 만들어서 개발
- Pull Request를 같이 사용하여 팀원 간 변경 내용에 대한 소통