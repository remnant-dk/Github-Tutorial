Github_Tutorial - 깃허브 기초
=============


새 리포지리 생성
-------------

## 1. GitHub 접속

* GitHub 홈페이지에 접속 후 로그인.



## 2. 새 리포지토리 생성

1. 우측 상단의 **[+]** 클릭
2. **[New repository]** 선택



## 3. 기본 정보 입력(중요)

### Repository name

* 생성할 저장소 이름 입력

### Owner

* 렘넌트 단체 팀 프로젝트일 경우 **remnant-dk** 선택, 개인 프로젝트일 경우 **자기 닉네임** 선택

### Description (선택)

* 프로젝트 설명 작성(선택사항)

### Public / Private 선택

* **Public**: 누구나 볼 수 있음
* **Private**: 본인만 접근 가능



## 4. 초기 설정 (중요)

### Add a README file

* 체크하면 README.md 자동 생성

### Add .gitignore

* 사용 언어 선택 (예: Python, Node 등)

### Choose a license(매우매우중요)


1. MIT Licence
* 누구나 내 코드를 가져가서 개인적, 상업적 용도로 마음껏 사용 가능한 자유 라이선스. 대신 쓰는 사람이 책임을 지게 됨

2. GNU GPL v3
* MIT와 비슷하지만, 코드 배포 및 수정 시 모두에게 같은 라이선스( GNU GPL v3)로 공개해야 함(몰래 쓰는거 불가능).

3. Apache License 2.0
* 기여자 특허 까지 인정(복잡하니까 쓰지마)

4. No License
* 깃허브 기본 라이선스를 자동으로 적용해준다. 문제 생길 일이 거의 없으니 이쪽을 가장 추천한다




## 5. 생성 완료

* **"Create repository"** 버튼 클릭



## 6. 로컬에서 연결 (선택)

이미 로컬 프로젝트가 있다면:

```bash
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/REPOSITORY.git
git push -u origin main
```



## 7. 클론해서 시작하기

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
```



## 팁


* API 키 절대 업로드 금지

---

## 참고

* GitHub 공식 문서: https://docs.github.com/
