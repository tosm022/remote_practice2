# 반갑습니다practice2
 
원격저장소1: origin
원격저장소2: github2

- git push (원격저장소) master
  = 현재 로컬 master 브랜치의 commit 기록을 (원격저장소)가 가리키는 저장소로 보내라

- 로컬 저장소:
            Desktop
            └── git-practice
                ├── README.md
                └── .git


- 두 개의 원격 저장소 연결:
  
                  내 컴퓨터

            git-practice (로컬 저장소)
                    |
            -------------------
            |                 |
        origin           github2
            |                 |
            ↓                 ↓
    remote_practice2   remote_practice3
        (GitHub)          (GitHub)

- 명령어 모음:
| `git init` | 로컬 저장소 생성 | git-practice 생성|
| `git add` | commit 대상 등록 | README 추가 |
| `git commit` | 변경 이력 저장 | first commit 생성 |
| `git remote add` | GitHub 연결 | origin 추가 |
| `git push origin master` | origin으로 업로드 | remote_practice2 업로드 |
| `git remote add github2` | 두 번째 원격 저장소 연결 | remote_practice3 연결 |
| `git push github2 master` | 두 번째 저장소로 업로드 | remote_practice3 업로드 |



