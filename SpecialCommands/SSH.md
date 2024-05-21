## SSH 원격 접속

```bash
# ~/.ssh 경로에 pem 키 저장

$ chmod 400 ~/.ssh/<key name> # 권한 수정
$ ssh -i ~/.ssh/<key name> <user>@<ip> # 접속
```

<br>

## 전송

```bash
# 로컬 -> 서버
$ scp <파일 경로> <user>@<ip>:<저장 경로> # 파일 하나
$ scp -r <폴더 경로> <user>@<ip>:<저장 경로> # 폴더 전체

# 서버 -> 로컬
$ scp <user>@<ip>:<파일 경로> <저장 경로> # 파일 하나
$ scp -r <user>@<ip>:<폴더 경로> <저장 경로> # 폴더 전체
```