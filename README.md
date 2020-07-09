# BackUp
## macOS 포맷 후 다시 설치할 항목들을 정리해놓은 문서

- 앱스토어 에서 받을 어플  
  - [ ] RunCat
  - [ ] Magnet
  - [ ] Slack
  - [ ] KakaoTalk

  <br/>
  <br/>
- 인터넷에서 받을 어플
  - [ ] AppCleaner
  - [ ] Chrome
  - [ ] itsycal (상세 설정 MMM d일 (E) a h:mm)
  - [ ] keka
  - [ ] notion
  - [ ] petit youTube (iCloud에 올라가 있다.)
  - [ ] postman
  - [ ] sequel pro
  - [ ] Visual Studio Code
  - [ ] zoom

  <br/>
  <br/>
- VSC extenstion
  - [ ] Auto Close Tag
  - [ ] Auto Rename Tag
  - [ ] Better Comments
  - [ ] Bracket Pair Colorizer 2
  - [ ] Color Highlight
  - [ ] CSS Peek
  - [ ] ESLint
  - [ ] Material Icon
  - [ ] Material Theme
  - [ ] Path Intellisense
  - [ ] Prettier
  - [ ] npm intellisense

<br/>

iTerm2 테마 : Brogrammer & 맥 외부 모니터 강제 RGB 모드 설정 파일 -> 둘 다 첨부파일에 같이 있음.

- iTerm 테마 -> Preference/Profiles/colors 에서 우측 하단 Color Presets... 누르고 import 해와서 설정.

- 강제 RGB 모드
  1. 맥 재부팅 하면서 cmd+R 을 눌러 복구모드로 들어가, 터미널에서 ``` csrutil disable ``` 을 입력해 SIP를 해제해준다.<br/><br/>
  2. 파일 다운로드 한 곳에 들어가서 터미널로 ``` ruby patch-edid.rb ``` 입력.<br/><br/>
  3. 만들어진 폴더는 기본적으로 read-only라서 write 권한이 있어야 옮길 수 있다. 터미널에서 ``` sudo mount -uw / ``` 입력.<br/><br/>
  4. 그 후 만들어진 폴더를 Overrides 에다가 집어넣는다.
  이때 터미널 명령어는 ``` sudo mv DisplayVendorID-* /System/Library/Displays/Contents/Resources/Overrides ``` 정도가 되겠다.<br/><br/>
  5. 이후 재부팅하면 적용 되어있음. <br/>
  참고 : https://www.hahwul.com/2020/03/how-to-solv-purple-external-display-on-mac.html
