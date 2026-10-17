# 웹툰 포트폴리오 — GitHub Pages

## 구성
- `index.html`: 사이트 전체. 별도 설치/로그인 불필요
- `images/`: 표지와 회차별 원고 이미지 저장

## 이미지 넣기
예시:
```
images/
  work01/
    cover.jpg
    ep01/
      001.jpg
      002.jpg
      003.jpg
    ep02/
      001.jpg
      002.jpg
  work02/
    cover.jpg
    ep01/
      001.jpg
      002.jpg
```
폴더와 파일명은 `index.html` 맨 아래 `const works = [...]`에 적힌 경로와 정확히 일치해야 합니다.
이미지 파일이 없는 상태에서는 표지가 임시 표시되고, 회차 원고가 없다는 안내가 뜹니다.
작품과 회차를 추가하려면 `works` 배열에 항목을 추가하고 해당 이미지를 업로드하세요.

## GitHub Pages 공개
1. GitHub에서 새 **Public** 저장소를 만듭니다.
2. 이 폴더의 `index.html`과 `images` 폴더를 저장소 최상위에 업로드합니다.
3. 저장소 Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
4. 표시된 Pages 주소로 접속합니다.

참고: GitHub 파일당 크기 제한과 저장소 사용 정책이 있습니다. 웹툰 원고는 적절히 분할·압축하세요.
