## Tailwind CSS 01
## Chapter 1: Introduction & Tailwind CSS Setup
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 Tailwind CSS 資源
https://github.com/gitdagray/tailwind-css-course

### Dave Gray 的 Tailwind CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6M8znNpim8dRiICRrP5HPft&si=TYz4MlVwoMJZuO69

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## Quick Concept offline
###  1. Intro
        教學影片開頭和介紹

###  2. Welcome

###  3. What is Tailwind CSS?

###  4. Course Prerequisites
        HTML Tutorials for Beginners
        https://youtube.com/playlist?list=PL0Zuz27SZ-6OlAwitnFUubtE93DO-l0vu&si=6In0EgHZHvOrzT9M

        CSS Tutorials for Beginners
        https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit&si=WhmdFjy0aW1P3P58

###  5. Web Dev Tools & Settings
        (1)安裝 Google Chrome 瀏覽器
        https://www.google.com/intl/zh-TW/chrome/
        (2)安裝 VS code 編譯器
        https://code.visualstudio.com/
        (3)安裝 node.js
        https://nodejs.org/zh-tw
        (4)在 terminal 輸入 node -v 確認版本
        (5)安裝 Live Server
        (6)點擊設定，選擇 Extension Settings，輸入並勾選 Full Reload

###  6. Tailwind CSS Config file
        (1)在 terminal 輸入 npx tailwindcss init
        (2)新增資料夾 build
        (3)新增資料夾 src

        index.html
        (4)新增 index.html
        (5)輸入!，使用 Emmet Abbreviation

        tailwind.config.js
        (6)加入 html 路徑為 ./build/*.html

###  7. input.css file
        (1)新增 input.css
        (2)新增 base
        (3)新增 components
        (4)新增 utilities
        (5)選取 File >> Preference >> Settings
        (6)更改 CSS > Lint: Unknown At Rules 設定為 ignore

###  8. Compile the style.css file
        (1)在 terminal 輸入 npx tailwindcss -i ./src/input.css -o ./build/css/style.css
        (2)加入 style.css 於 index.html

###  9. Compiling with --watch
        (1)新增 div 元素，
        設定 div 元素的 Class，
        新增 bg-emerald-500 為 background-color: rgb(16 185 129);
        新增 w-52 為 width: 13rem;
        新增 h-52 為 height: 13rem;
        (2)在 terminal 輸入 npx tailwindcss -i ./src/input.css -o ./build/css/style.css --watch

### 10. Starting Live Server

### 11. Tailwind CSS Intellisense
        (1)安裝 Tailwind CSS IntelliSense
        (2)新增 rounded-full 為 border-radius: 9999px;
        新增 shadow-2xl 為 box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.25);

### 12. Using Tailwind docs to find class names
        (1)前往官方文件 https://tailwindcss.com/
        (2)搜尋 min-Height
        (3)設定 body 元素的 Class
        新增 min-h-screen 為 min-height: 100vh;
        新增 grid 為 display: grid;
        新增 place-content: center; 為 place-content-center

### 13. Creating a bullseye with Tailwind
        (1)設定 div 元素的 Class，
        新增 grid 為 display: grid;
        新增 place-content: center; 為 place-content-center
        (2)新增第二層 div 元素，
        設定 div 元素的 Class，
        新增 bg-teal-200 為 background-color: rgb(153 246 228);，
        新增 w-32 為 width: 8rem;
        新增 h-32 為 height: 8rem;
        新增 rounded-full 為 border-radius: 9999px;
        新增 grid 為 display: grid;
        新增 place-content: center; 為 place-content-center
        (3)新增第三層 div 元素，
        設定 div 元素的 Class，
        新增 bg-red-500 為 background-color: rgb(239 68 68);，
        新增 w-16 為 width: 4rem;
        新增 h-16 為 height: 4rem;
        新增 rounded-full 為 border-radius: 9999px;

### 14. Adding a custom class to input.css
        (1)搜尋 Linear gradients
        (2)搜尋 Radial gradients，但找不到
        (3)新增 .radial-blue 的 Class，
        背景漸層為亮黃和天空藍 
        (4)設定 body 元素的 Class
        新增 radial-blue

### 15. Handling class clutter in your HTML
        安裝 Inline fold