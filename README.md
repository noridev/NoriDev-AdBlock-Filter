# NoriDev AdBlock Filter - Beta
**[ 경고 ]** Beta 테스트가 진행중인 필터입니다.

Beta 필터는 Stable 필터에 적용 예정인 필터링 구문과 내용을 담고 있으며, Stable 버전 대비 불안정하거나 불필요한 영역까지 차단하는 경우가 발생할 수 있으므로 사용에 주의해 주십시오.  
또한, 이러한 문제가 발생하는 경우 issue 및 Pull Requests를 생성하여 주십시오.

모든 디바이스에서 사용할 수 있는 광고 차단 필터입니다.

브라우저 필터와 겸용으로 사용가능합니다. (브라우저(Safari 호환) + DNS 필터)

### 호환성
- **AdGuard for Windows**
- **AdGuard for Mac**
- **AdGuard for Android**
- **AdGuard for iOS**
- **AdGuard Pro for iOS**
- **AdGuard Home**
- **uBlock Origin**

이외의 환경에서는 테스트가 진행되지 않았으므로, 사용할 수는 있으나 작동을 보장할 수 없습니다.

## 기능
### 필터링
- 카카오톡 채팅 광고, 카카오 나우 및 채널 탭 차단
- 에브리타임 (웹/앱) 광고
- 구글 광고
- 웹 트위터의 프로모션 광고, 나를 위한 트렌드 및 팔로우 추천
- 네이버 애드포스트, 모바일 블로그 배너 광고
- 네이버 웹 광고(배너 광고 포함)
- pixiv (웹/앱) 광고
- 티머니 고속버스/시외버스 앱 배너 광고
- 클리앙 광고
- 디시인사이드 광고
- 에펨코리아 광고
- 나무위키 광고
- 쿠팡 배너, 검색 광고
- 그 외 기타 광고들

### 추가 기능
- 트위터의 이미지 및 동영상 로드 속도 개선 (속도 이슈가 없으므로 현재는 비활성화됨)

## 사용 방법
AdGuard의 설정에 진입한 뒤, 아래 과정을 차례대로 따라해주세요.

아래 과정은 22/01/22 기준 최신 버전의 AdGuard를 기준으로 하고 있습니다.
구버전을 사용하고 계신 분들께서는 구버전을 유지해야 하는 경우가 아니라면, 최상의 필터링을 위해 최신 버전으로 업데이트 할 것을 권장드립니다.

### DNS 필터 추가
#### Windows
1. **설정**에 진입합니다.
2. **DNS 보호**를 클릭합니다.
3. 스위치를 **켭니다**.
4. **DNS 필터 편집기 열기**를 클릭합니다.
5. **+ 버튼**을 클릭합니다.
6. **URL로 필터 추가**를 클릭합니다.
7. **파일 URL 또는 경로 입력**에 아래 링크를 붙여넣고 **설치**를 클릭합니다.
<pre>https://raw.githubusercontent.com/noridev/NoriDev-AdBlock-Filter/beta/filter/filter.txt</pre>

#### macOS
1. **설정**에 진입합니다.
2. **DNS**를 클릭합니다.
3. **DNS 보호**에 체크합니다.
4. **필터**를 클릭합니다.
5. **+ 버튼**을 클릭합니다.
6. **URL 또는 파일 경로 입력**에 아래 링크를 붙여넣고 **다음**을 클릭한 뒤, **구독**을 누릅니다.
<pre>https://raw.githubusercontent.com/noridev/NoriDev-AdBlock-Filter/beta/filter/filter.txt</pre>

#### Android
1. **설정**에 진입합니다.
2. **DNS 필터링**을 클릭합니다.
3. 스위치를 **켭니다**.
4. **DNS 요청 차단 방식**을 클릭합니다.
5. **새 DNS 필터**를 클릭합니다.
6. **URL 또는 경로**에 아래 링크를 붙여넣고 **가져오기**을 클릭한 뒤, 이름에 **NoriDev AdBlock Filter - Beta**를 입력하고 **추가**를 누릅니다.
<pre>https://raw.githubusercontent.com/noridev/NoriDev-AdBlock-Filter/beta/filter/filter.txt</pre>

#### iOS
##### 개발자 모드 활성화
1. **설정**에 진입합니다.
2. **일반**을 클릭합니다.
3. **개발자 모드**의 스위치를 켭니다.

##### 필터 추가
1. **보호**를 클릭합니다. (하단 4개의 탭 중 방패 모양으로 된 아이콘)
2. **DNS 보호**를 클릭합니다.
3. 스위치를 **켭니다**.
4. **DNS 필터링**을 클릭합니다.
5. **DNS 필터**를 클릭합니다.
6. **필터 추가**를 클릭합니다.
7. **필터 주소**에 아래 링크를 붙여넣고 **다음**을 클릭한 뒤 **추가**를 누릅니다.
<pre>https://raw.githubusercontent.com/noridev/NoriDev-AdBlock-Filter/beta/filter/filter.txt</pre>

### 브라우저 필터 추가
#### Windows
1. **설정**에 진입합니다.
2. **광고 차단**을 클릭합니다.
3. **필터 추가**를 클릭합니다.
4. **URL로 필터 추가**를 클릭합니다.
5. **파일 URL 또는 경로 입력**에 아래 링크를 붙여넣고 **설치**를 클릭한 뒤 **신뢰할 수 있는 필터임**에 체크하고 **설치**를 누릅니다.
<pre>https://raw.githubusercontent.com/noridev/NoriDev-AdBlock-Filter/beta/filter/filter.txt</pre>

#### macOS
1. **설정**에 진입합니다.
2. **필터 구독**을 클릭합니다.
3. **+ 버튼**을 클릭합니다.
4. **사용자 필터 추가**를 클릭합니다.
5. **URL 또는 파일 경로 입력**에 아래 링크를 붙여넣고 **다음**을 클릭한 뒤 **신뢰할 수 있는 필터**에 체크하고 **구독**을 누릅니다.
<pre>https://raw.githubusercontent.com/noridev/NoriDev-AdBlock-Filter/beta/filter/filter.txt</pre>

#### Android
1. **설정**에 진입합니다.
2. **콘텐츠 차단**을 클릭합니다.
3. **필터**를 클릭합니다.
4. **사용자 지정 필터**를 클릭합니다.
5. 스위치를 **켭니다**.
6. **사용자 정의 필터 추가**를 클릭합니다.
7. **URL 또는 경로**에 아래 링크를 붙여넣고 **다음**을 클릭한 뒤 **신뢰할 수 있는 필터**에 체크하고 **추가**를 누릅니다.
<pre>https://raw.githubusercontent.com/noridev/NoriDev-AdBlock-Filter/beta/filter/filter.txt</pre>

#### iOS
1. **보호**를 클릭합니다. (하단 4개의 탭 중 방패 모양으로 된 아이콘)
2. **Safari 보호**를 클릭합니다.
3. 스위치를 **켭니다**.
4. **필터**를 클릭합니다.
5. **사용자 정의**를 클릭합니다.
6. **필터 추가**를 클릭합니다.
7. **필터 주소**에 아래 링크를 붙여넣고 **다음**을 클릭한 뒤 **추가**를 누릅니다.
<pre>https://raw.githubusercontent.com/noridev/NoriDev-AdBlock-Filter/beta/filter/filter.txt</pre>

## Troubleshooting
### 카카오톡
#### 폰트 목록이 갱신되지 않거나 다운로드를 받을 수 없음
1. DNS 필터링 허용 목록에 **mud-kage.kakao.co.kr**을 추가하거나, DNS 보호 기능을 일시적으로 중지합니다.
2. 폰트 적용이 완료되면 허용 목록에서 추가했던 도메인을 삭제하거나 DNS 보호 기능을 다시 활성화 합니다.
