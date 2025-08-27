# gitkraken-korean
![Translation](https://img.shields.io/badge/Translation-50%25-green)
> GitKraken 한글화


## 주요 변경 사항
- 2023.8.18일 기준, 최신버전의 남은 라인을 기계번역으로 번역하였습니다.
- 이후 문맥에 맞게 수정하고, 오역을 수정할 예정입니다.

## 개요

[GitKraken 한글화](https://github.com/shblue21/gitkraken-korean) 입니다.  
11.3.0 버전 기준입니다.
![Main](.github/images/main.png)



## 언어 변경

### Script 실행
- 원문으로 되돌아가십시오.

### 직접 변경
1. 다음 경로로 이동.
   - 윈도우 : `%LOCALAPPDATA%\gitkraken\app-11.x.x\resources\app.asar.unpacked\src`
   - Mac: `/Applications/GitKraken.app/Contents/Resources/app.asar.unpacked/src/`
2. `app.asar.unpacked\src\en` 폴더 생성.
3. `app.asar.unpacked\src\strings.json` 파일 `src\en` 폴더로 이동.
4. [`resources\ko\lastest\strings.json`](https://raw.githubusercontent.com/shblue21/gitkraken-korean/main/resources/ko/lastest/strings.json) 파일 다운.
5. `app.asar.unpacked/src`에 복사
6. UI Customization 옵션에서 Language를 Korean으로 변경.
* Preferences - UI Customization - Language(English US) 를 Korean KR 로 전환
![uicustomize](.github/images/uicustomize.png)
  

## Contribute

- 원문 URL 은 [GitKraken 한글화](https://github.com/shblue21/gitkraken-korean) 입니다.
#### 이 페이지는 원문을 그대로 가져와 사용자정의로 다음버전을 이행하기 위함입니다.
#### 이 페이지는 사용자정의로 오역이 있으며, 원문을 그대로 유지하기 위함입니다.

## License
[MIT License](https://raw.githubusercontent.com/shblue21/gitkraken-korean/main/LICENSE)
