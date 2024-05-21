
```bash
$ nohup python filename.py & # 오류 발생 시 python3. 그래도 발생 시, usr/bin/python3.
$ nohup 실행문 > 로그파일명 & # 원하는 파일에 로그 기록

# print문 바로 확인
$ nohup python -u filename.py & 
$ tail -f nohup.out
```