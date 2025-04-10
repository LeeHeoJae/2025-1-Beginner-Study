* git log --oneline : 커밋 목록 요약
* git status : 상태에 따른 변경된 파일 분류
* commit --ammend (-m "커밋 메시지") : 마지막 commit을 변경
* git reset --option "commit id" : commit을 제거할 때 사용
 - soft : 변경 사항이 Staging area로 돌아감
 - mixed(default) : 변경 사항이 working directory로 돌아감
 - hard : 변경 사항을 제거. 완전 이전 커밋으로 돌아감
* git revert : 커밋을 지우는 커밋함