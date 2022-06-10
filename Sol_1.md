[1] https://stackoverflow.com/questions/31351359/how-to-log-out-of-one-github-account-and-use-another-account  (영어)
요약
1. git bash 실행 
2. git config --global --edit 입력
[user]
        name = kimmin1kk
        email = rudals1888@naver.com
[difftool "sourcetree"]
        cmd = '' \"$LOCAL\" \"$REMOTE\"
[mergetool "sourcetree"]
        cmd = "'' "
        trustExitCode = true
[credential "helperselector"]
        selected = manager-core
라고 뜸

이걸 설정하려면 https://git-scm.com/book/ko/v2/Git%EB%A7%9E%EC%B6%A4-Git-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0 참고

근데 이거 설명이 부족해서 막 건들였다간 큰일 날 거 같아서 일단은 킵
