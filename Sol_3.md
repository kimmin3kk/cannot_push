[3] https://stackoverflow.com/questions/51976794/git-desktop-error-remote-rejected-master-master-permission-denied (영어)
얘는 일단 나랑 상황이 비슷함
답변 요약
1. 니가 소유하고 있는 repoB(라쿤)으로 push를 했는지 확인
2. repoA(캣)에 마스터 브랜치가 push 보호를 하고 있는지 확인해라
3. 만약 니 브랜치가 옛날 커밋을 가지고 있다면 git push --force를 이용해 리셋을 해라
4. The idea for pushing to a fork remains to push to a repo that you own. The account must match.
가지고 있는 repo에다가 fork를 하라는 말인 거 같은데 당연한 거 아닌ㄴ가?