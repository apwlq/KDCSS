# KDCSS

## Install
<p><strong><a href="https://github.com/BetterDiscord/Installer/releases/latest">이 링크</a></strong>로 들어가서 플랫폼에 맞게 <strong><a href="https://github.com/BetterDiscord/Installer/releases/latest">BetterDiscord</a></strong>를 다운로드합니다.</p>
다운로드한 파일을 실행 후 이용약관을 읽고 동의합니다.<br>
가장 위에 <strong>Install BetterDiscord</strong>를 선택합니다.<br>
설치하려는 디스코드 버전을 알맞게 선택하고, <strong>Install</strong>합니다.<br>
설치가 시작되면, 디스코드가 재시작되고 <strong>BetterDiscord</strong>의 설치가 끝납니다.

## Apply
```css
@import url('https://gitea.kanami.pw/superonline/KDCSS/raw/branch/master/kdcss.css');
```
디스코드에 들어가신 후, 설정에 가장 아래에 있는 Custom CSS 탭을 클릭합니다. <br>
위의 코드를 **CUSTOM CSS EDITOR**에 입력하고,  <br>
아래의 Save, Update를 눌러주면 적용됩니다.
테마의 세부사항은 <a href="#config">설정</a>을 참조하십시오.


## Config
```css
@import url('https://gitea.kanami.pw/superonline/KDCSS/raw/branch/master/kdcss.css');
:root {
    --font-display: 'NEXON Lv2 Gothic';
    --font-size: 90%;
    --background-image: url('https://wallpapercave.com/wp/wp3194549.png');
    --background-transparency: rgba(0, 0, 0, 0.7);
    --home-icon-image: url('https://gitea.kanami.pw/superonline/KDCSS/raw/branch/master/svg/discord.svg');
    --phone-visible: none;
    --avatar-shape: 50%;
    --blur-range: 0px;
    --blur-speed: 0ms;
    --button-visible: flex;
    --help-button-visible: flex;
    --hide-block-user-message: block;
}
```
<p><strong>font-display</strong>는 폰트를 변경합니다.<br>
    폰트이름을 넣어 폰트를 변경하실 수 있습니다.
    
<p><strong>font-size</strong>는 폰트의 크기를 변경합니다.<br>
    <strong>백분율</strong>을 조정하여 바꿀 수 있습니다.</p>
    
<p><strong>background-image</strong>는 배경 이미지를 변경합니다.<br>
    <strong>이미지 주소</strong>를 넣어서 변경하실 수 있습니다.</p>

<p><strong>background-transparency</strong>는 배경 이미지의 투명도를 조절합니다.<br>
    1은 최대, 0은 최소입니다. <strong>소숫점을 조절</strong> 할 수 있습니다.</p>

<p><strong>home-icon-image</strong>는 홈 버튼의 아이콘을 변경합니다.<br>
    <strong>이미지 주소</strong>를 넣어서 변경하실 수 있습니다.</p>

<p><strong>phone-visible</strong>은 모바일 유저의 아이콘을 끄고 켭니다.<br>
    <strong>flex</strong>는 보이기, <strong>none</strong>은 숨기기입니다.</p>

<p><strong>avatar-shape</strong>는 유저 아이콘의 둥글기를 설정합니다.<br>
    0%나 100%에 가까울수록 각져집니다.</p>
    
<p><strong>blur-range</strong>는 스포일러 이미지의 블러 강도를 조절합니다.<br>
    <strong>0px</strong>는 해제, <strong>숫자의 크기에 따라</strong>블러가 세집니다.</p>
    
<p><strong>blur-speed</strong>는 블러된 스포일러 이미지에 마우스를 올렸을때, 블러가 해제되는 속도입니다.<br>
    <strong>0ms</strong>는 즉시, <strong>숫자의 크기에 따라</strong>해제가 느려집니다.</p>
    
<p><strong>button-visible</strong>은 메세지 옆에 GIF나 니트로 선물을 설정합니다.<br>
    <strong>flex</strong>는 보이기, <strong>none</strong>은 숨기기입니다.</p>
    
<p><strong>help-button-visible</strong>은 도움말 버튼을 끄고 켭니다.<br>
    <strong>flex</strong>는 보이기, <strong>none</strong>은 숨기기입니다.</p>
    
<p><strong>hide-block-user-message</strong>는 차단한 유저의 메세지를 완전히 숨깁니다.<br>
    <strong>flex</strong>는 보이기, <strong>none</strong>은 숨기기입니다.</p>
