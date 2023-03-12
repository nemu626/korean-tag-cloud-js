# 한국어 nodejs 태그구름 생성기 

## 개요 
한국어 텍스트를 형태소분석하여 출연횟수를 카운팅 후, 태구그름 이미지를 생성해 주는 라이브러리입니다.

## 사용법

```javascript
import { createCrowd } from 'korean-tag-cloud';
const rawString = '한국어 텍스트를 형태소분석하여 출연횟수를 카운팅 후, 태구그름 이미지를 생성해 주는 라이브러리입니다.';
const cloud = createCrowd(rawString, { onlyNoun: true });
```
