# 멋쟁이사자처럼 수원대학교 14기 아기사자 자기소개 모음집

수원대학교 멋쟁이사자처럼 14기 부원들의 자기소개 모음집입니다.

---

## 실습 가이드

### 1단계: Clone (레포지토리 가져오기)

```bash
git clone https://github.com/likelionusw14/14th-Common.git
cd 14th-Common
```

### 2단계: Branch 생성 (본인 이름으로 브랜치 만들기)

```bash
git checkout -b feature/본인이름
```

> 예시: `git checkout -b feature/jaeryeong`

### 3단계: 자기소개 파일 작성

`members/` 폴더에 본인 이름으로 된 Markdown 파일을 만들어주세요.

> 예시: `members/jaeryeong.md`

`members/example.md` 파일을 참고해서 작성하면 됩니다!

### 4단계: Commit & Push

```bash
git add members/본인이름.md
git commit -m "feat: 본인이름 자기소개 추가"
git push origin feature/본인이름
```

> 예시:
> ```bash
> git add members/jaeryeong.md
> git commit -m "feat: jaeryeong 자기소개 추가"
> git push origin feature/jaeryeong
> ```

### 5단계: Pull Request 생성

1. GitHub 레포지토리 페이지로 이동합니다.
2. **"Compare & pull request"** 버튼을 클릭합니다.
3. PR 제목과 내용을 작성한 후 **"Create pull request"** 를 클릭합니다.

---

## Members

| 이름 | 파일 |
|------|------|
| 예시 | [example.md](members/example.md) |
