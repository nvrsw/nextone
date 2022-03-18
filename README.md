# nextone

NEXTONE 홈페이지 웹사이트

## 개발 도구 설치

[Hugo](https://gohugo.io/getting-started/installing/),
[Visual Studio Code](https://code.visualstudio.com/) 도구를 사이트를 참고해서 설치합니다.

## 업데이트 / 테스트

Hugo 서버 실행하고,

```sh
hugo server
```

웹 브라우저로 다음 주소에 접속합니다.

http://127.0.0.1:1313/

참고로, 현재 페이지의 소스 파일을 에디터로 수정하면 웹 브라우저가 자동으로 현재 내용을 다시 읽어 옵니다.

## 빌드

웹 사이트를 빌드하면,

```sh
hugo
```

`public` 폴더에 결과물이 저장됩니다.

## 폴더 구조

`content` 폴더는 실제 내용이 들어 있고, 다음과 같은 섹션 폴더로 구성됩니다.

- `company`: 회사소개
- `business`: 사업분야
- `products`: 제품
- `contribution`: 사회공헌
- `home`: 홈 페이지
- `categories`: 카테고리 정보 (NVR / 카메라 등)

각 섹션 폴더는 실제 문서 폴더나 문서 파일을 포함합니다. 그림이 없는 문서는 `ip-cameras.md` 등과 같은 파일로 작성합니다. 그림이 포함된 문서는 폴더로 구성되고 문서의 텍스트를 담고 있는 `index.md` 파일을 포함해야 합니다. 참고로, 폴더 이름이나 파일 이름은 웹에서 접속하는데 사용하는 URL 이름으로 사용됩니다.

문서의 그림 파일은 가능한 PNG 형식을 추천하고, 가로 크기는 `960` 픽셀로 조정합니다. 문서 폴더 안의 `featured.png` 또는 `featured.jpg` 파일은 상위 페이지에서 표시되는 작은 그림인데, `480x320` 픽셀 크기로 조정합니다.

## 참고 자료

- [The world’s fastest framework for building websites | Hugo](https://gohugo.io/)
- [Academic Theme](https://sourcethemes.com/academic/)
- [블로그 구축기 1 (Hugo + github.io) | ialy's blog](https://ialy1595.github.io/post/blog-construct-1/)
- [블로그 구축기 2 (Hugo Theme Custormizing) | ialy's blog](https://ialy1595.github.io/post/blog-construct-2/)
