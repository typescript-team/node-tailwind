# Node + TailwindCss

## 1. npm init
```
    "build-css": "tailwindcss build src/styles.css -o public/styles.css"
    :: tailwindcss를 이용한 build 명령
```
## 2. npm install -D tailwindcss
## 3. src/styles.css
```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;

    npm run build-css
    :: src/styles.css를 tailwindcss가 빌드해서
    :: public/styles.css로 스타일 파일을 생성한다.
```