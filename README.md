# audio-to-wave-video

**저장소:** `index.html`, `libs/waviz.umd.js`, `package.json`, `package-lock.json`, README, `.gitignore` — `node_modules` 만 Git에서 제외합니다.

**로컬 개발 / Waviz 갱신:** `npm install` 시 `postinstall`이 `node_modules/waviz/dist/waviz.umd.js` 를 `libs/waviz.umd.js` 로 복사합니다.

**정적 배포:** 호스트에는 보통 `index.html` + `libs/` 만 올려도 동작합니다. (`npm` 실행이 없어도 됨)
