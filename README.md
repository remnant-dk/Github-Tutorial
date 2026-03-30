Github_Tutorial - 깃허브 기초
=============


# 새 리포지리 생성

---

## 1. GitHub 접속

* GitHub 홈페이지에 접속 후 로그인.

---

## 2. 새 리포지토리 생성

1. 우측 상단의 **+ (플러스 버튼)** 클릭
2. **"New repository"** 선택

---

## 3. 기본 정보 입력(중요)

### Repository name

* 생성할 저장소 이름 입력

### Description (선택)

* 프로젝트 설명 작성

### Public / Private 선택

* **Public**: 누구나 볼 수 있음
* **Private**: 본인만 접근 가능

---

## 4. 초기 설정 (중요)

### ✅ Add a README file

* 체크하면 README.md 자동 생성

### ✅ Add .gitignore

* 사용 언어 선택 (예: Python, Node 등)

### ✅ Choose a license

* 라이선스 선택 (예: MIT 등)

---

## 5. 생성 완료

* **"Create repository"** 버튼 클릭

---

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

---

## 7. 클론해서 시작하기

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
```

---

## 💡 팁

* README.md는 프로젝트의 첫인상입니다
* 라이선스는 프로젝트 성격에 맞게 선택하세요
* API 키는 절대 업로드하지 마세요 (.env 사용)

---

## 📄 참고

* GitHub 공식 문서: https://docs.github.com/
