#테스트를 하기위한 makefile사용방법

먼저 이 글은 makefile을 사용하기 위한 설명서입니다.
makefile이 실행이 안되시면 이 사이트를 보시면 될겁니다.

https://jstar0525.tistory.com/264

이 사이트에서 보셔서 하셔도 문제 없습니다.
아래 내용은 간단히 정리한 내용입니다.
#make가 설치되지 않은 경우(되신분은 아래로 내려가시면 됩니다.)
1. 위의 사이트 다운받으라는 파일을 다운받는다.
2. 다운로드받은 경로를 복사하고 환경변수에 주소를 저장한다.
3. cmd창에서 `make -v`를 입력후 없다는 말이 없으면 설치성공

#test를 하고 싶은 경우:
`make test`
#이미지 파일을 삭제하고 싶은 경우(윈도우):
`make delete_w`
#이미지 파일을 삭제하고 싶은 경우(맥):
`make delete_m`


