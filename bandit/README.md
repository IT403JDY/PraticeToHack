# Bandit wargame MEMO
## Lv 0 
mac termianl
ssh [접속할 ID]@[접속 주소] -p [port]
cat or vi를 이용해 REAMD.md를 읽어 보자. 보토이 이것이 비밀번호인 경우가 많다.
ssh 포트와 sftp포트는 보통 거의 동일하다. 그래서 ssh가 열려있는 Lv01에서도 sftp로 접속해서 파일을 다운 받을 수 있다.

## Lv01 -> Lv02
ssh접속이후 - 가 리눅스에서 옵션 예약어여서 ./ 상대 or 절대경로를 쓴다음 cat해야한다.
cat을 통한 비밀 번호확인

## Lv02 -> Lv03
특수문자는 이스케이프 문자를 이용하면 된다.
or "file name" 이런식으로 String 처리해주어된다.
## Lv03 -> Lv04
똑같음 그냥 cat으로 확인
숨김 파일은 .으로 시작하고 그냥 ls로는 나오지 않는다.
ls -all 하면 확인 할 수 있다.
## Lv04 -> Lv05
