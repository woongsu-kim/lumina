# Privacy Policy · 개인정보 처리방침

_Last updated / 최종 수정: 2026-10-05_

Lumina is an independent third-party app. It has no user accounts, no analytics, no advertising, and no tracking SDKs. We (the developer) do not collect or receive your personal data on any server we operate.

Lumina는 독립적인 서드파티 앱입니다. 계정·분석 도구·광고·추적 SDK가 없으며, 개발자가 운영하는 서버로 개인정보를 수집·전송하지 않습니다.

---

## 1. Data stored only on your device (never uploaded)

- **Vehicle identification number (VIN)** you enter
- **App settings** (skins, panels, units, language)
- **Drive log** the app writes locally for diagnostics

These stay in the app's private storage on your iPhone and are removed when you delete the app.

**기기에만 저장되고 업로드되지 않는 것:** 입력한 VIN, 앱 설정(스킨·패널·단위·언어), 진단용 주행 로그. 앱을 삭제하면 함께 삭제됩니다.

## 2. Vehicle data over Bluetooth

The app connects to your car over Bluetooth LE using the key you registered with your key card. Vehicle data (speed, battery, climate, tire pressure, media, location reported by the car) is read locally and **only displayed**; it is not sent to us.

**블루투스로 읽는 차량 데이터:** 카드키로 등록한 키로 차와 직접(BLE) 연결해 읽고 화면에만 표시합니다. 개발자에게 전송하지 않습니다.

## 3. Location

Location is used only while you use the app, to show your position, follow your route, and look up the road you're on. Location (or a coordinate derived from it) is shared with the third-party services below, which is unavoidable for those features to work.

**위치:** 앱 사용 중에만, 현재 위치 표시·경로 안내·현재 도로 조회를 위해 사용합니다. 아래 제3자 서비스에는 해당 기능 동작을 위해 좌표가 전달됩니다.

## 4. Third-party services that receive data

| Service | What is sent | Why |
|---|---|---|
| **Apple** (MapKit, Core Location, CLGeocoder) | Location, route | Map tiles, directions, address/road lookup |
| **OpenStreetMap Overpass API** (`overpass-api.de`, `overpass.kumi.systems`) | Your current coordinate (bounding-box query) | Look up the speed limit of nearby roads |
| **Open-Meteo** (`api.open-meteo.com`) | Your current coordinate | Weather |
| **Apple iTunes Search API** (`itunes.apple.com`) | Title and artist of the track playing | Look up the album artwork |
| **Media artwork URL** provided by the car | — | Album/station artwork |

These requests contain a coordinate or the title and artist of the track playing, never your name or account. The operators may log request data (e.g. IP address) under their own privacy policies:
- Apple (incl. iTunes Search) — https://www.apple.com/legal/privacy/
- OpenStreetMap Foundation — https://osmfoundation.org/wiki/Privacy_Policy
- Open-Meteo — https://open-meteo.com/en/terms

**제3자 서비스:** Apple(지도·경로·주소), OpenStreetMap Overpass API(현재 좌표 주변 도로의 제한속도 조회), Open-Meteo(날씨), Apple iTunes Search API(재생 중인 곡의 제목·아티스트 → 앨범아트 조회). 전송되는 것은 좌표 또는 곡 제목·아티스트이며 이름·계정은 포함되지 않습니다. 각 서비스 운영자는 자체 정책에 따라 접속 기록(예: IP)을 남길 수 있습니다.

## 5. Permissions

- **Location (when in use)** — position, route, speed-limit lookup.
- **Bluetooth** — connect to your car.

You can revoke both in iOS Settings; the related features then stop working.

**권한:** 위치(사용 중) — 위치·경로·제한속도 조회 / 블루투스 — 차량 연결. iOS 설정에서 언제든 철회할 수 있습니다.

## 6. Children, changes, contact

- The app is not directed at children.
- We may update this policy; the "last updated" date above will change.
- Questions: woongsu@me.com

**아동·변경·문의:** 아동 대상 앱이 아닙니다. 정책이 바뀌면 위 날짜가 갱신됩니다. 문의는 위 이메일로.
