# NoriDev AdGuard DNS Filter
모든 디바이스에서 사용할 수 있는 AdGuard 전용 필터입니다.

브라우저 필터와 겸용으로 사용가능합니다. (브라우저(Safari 호환) + DNS 필터)

### 호환성
- **AdGuard for Windows** 7.4.2 or higher
- **AdGuard for Mac** 2.4.8 or higher
- **AdGuard for Android** 3.4 or higher
- **AdGuard for iOS** 4.0.1 or higher
- **AdGuard Pro for iOS** 4.0.1 or higher

상기 플랫폼의 버전을 기준으로 테스트가 완료되었습니다.

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

### 추가 기능
- 트위터의 이미지 및 동영상 로드 속도 개선

## 사용 방법
AdGuard의 설정에 진입한 뒤, 아래 과정을 차례대로 따라해주세요.

### DNS 필터 추가
#### Android
1. **설정**에 진입합니다.
2. **DNS 필터링**을 클릭합니다.
3. **DNS 요청 차단 방식**을 클릭합니다.
4. **새 DNS 필터**를 클릭합니다.
5. **URL 또는 경로**에 아래 링크를 붙여넣고 **가져오기**을 클릭한 뒤, 이름에 **NoriDev AdGuard DNS Filter**를 입력하고 **추가**를 누릅니다.
<pre>https://raw.githubusercontent.com/NoriDev/NoriDev-AdGuard-DNS-Filter/master/filter/filter.txt</pre>

#### iOS
##### 개발자 모드 활성화
1. **설정**에 진입합니다.
2. **일반**을 클릭합니다.
3. **개발자 모드**의 스위치를 오른쪽으로 밀어 활성화 해 줍니다.

##### 필터 추가
1. **설정**에 진입합니다.
2. **DNS 보호**를 클릭합니다.
3. **DNS 필터링**을 클릭합니다.
4. **DNS 필터**를 클릭합니다.
5. **필터 추가**를 클릭합니다.
6. **필터 주소**에 아래 링크를 붙여넣고 **다음**을 클릭한 뒤 **추가**를 누릅니다.
<pre>https://raw.githubusercontent.com/NoriDev/NoriDev-AdGuard-DNS-Filter/master/filter/filter.txt</pre>

### 브라우저 필터 추가
#### Android
1. **설정**에 진입합니다.
2. **콘텐츠 차단**을 클릭합니다.
3. **필터**를 클릭합니다.
4. **사용자 지정 필터**를 클릭합니다.
5. **사용자 정의 필터 추가**를 클릭합니다.
6. **URL 또는 경로**에 아래 링크를 붙여넣고 **다음**을 클릭한 뒤 **신뢰할 수 있는 필터**에 체크하고 **추가**를 누릅니다.
<pre>https://raw.githubusercontent.com/NoriDev/NoriDev-AdGuard-DNS-Filter/master/filter/filter.txt</pre>

#### iOS
1. **설정**에 진입합니다.
2. **Safari 보호**를 클릭합니다.
3. **필터**를 클릭합니다.
4. **사용자 정의**를 클릭합니다.
5. **필터 추가**를 클릭합니다.
6. **필터 주소**에 아래 링크를 붙여넣고 **다음**을 클릭한 뒤 **추가**를 누릅니다.
<pre>https://raw.githubusercontent.com/NoriDev/NoriDev-AdGuard-DNS-Filter/master/filter/filter.txt</pre>

## Troubleshooting
### 카카오톡
#### 폰트 목록이 갱신되지 않거나 다운로드를 받을 수 없음
1. DNS 필터링 허용 목록에 **mud-kage.kakao.co.kr**을 추가합니다.
2. 폰트 적용이 완료되면 허용 목록에서 추가했던 도메인을 삭제합니다.
