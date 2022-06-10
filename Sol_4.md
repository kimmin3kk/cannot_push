[4]https://localcoder.org/remote-rejected-master-master-permission-denied (영어)
제목부터가 해결했다고 돼있다.
해결방안 1:
1. git bash 실행 후 git config --global --edit 입력
2. 마지막 줄 수정
[credential]
	helper = osxkeychain
	useHttpPath = true
근데 1번 사이트에서 봤을 땐 helper = osxkeychain <- Mac용이라 제외해도 될 듯
이걸 한 번 해봐야겠다!

수정 방법 : C:\Users\ASUS 에서 .gitconfig 드가서 수정
해결~