---
title: 스탠드8 개인정보처리방침 / Stand8 Privacy Policy
---

# 스탠드8 개인정보처리방침

시행일: 2026년 11월 11일

스탠드8(패키지 이름 `com.kreodn.stand8`, 이하 "앱")은 충전 중인 휴대전화의 커버 화면에 시계, 날씨, 일정, 사진을 보여 주는 앱입니다. 개발자는 이용자의 개인정보를 수집하거나 서버에 저장하지 않습니다. 앱에는 회원 가입, 광고, 분석 도구, 개발자가 운영하는 서버가 없습니다.

## 1. 앱이 사용하는 정보

아래 정보는 화면에 표시하기 위해서만 사용합니다. "기기 밖으로 전송"에 따로 적은 경우를 빼면 모두 기기 안에서만 처리합니다.

| 정보 | 사용 목적 | 기기 밖으로 전송 |
|---|---|---|
| 대략적인 위치 (정확한 위치는 사용하지 않음) | 현재 위치의 날씨와 지역 이름 표시 | 전송함 (2번 참고) |
| 캘린더 일정 (제목, 시간, 색) | 날씨·일정 페이지에 다가오는 일정 표시 | 전송하지 않음 |
| 이용자가 직접 고른 사진 | 사진 액자 페이지에 표시 | 전송하지 않음 |
| 재생 중인 미디어 정보 (곡 제목, 아티스트, 앨범 그림) | 대시보드에 표시하고 재생·일시정지·이전·다음 조작 | 전송하지 않음 |
| 연결된 블루투스 기기 이름, 기기 이름 | 기기 정보 페이지에 표시 | 전송하지 않음 |
| 배터리, 메모리, 저장공간, 네트워크 연결 상태 | 기기 정보 페이지에 표시 | 전송하지 않음 |
| 충전 상태, 접힘 상태, 기기의 기울기 | "충전 시 자동 실행", "세로로 들면 닫기" 동작 | 전송하지 않음 |
| 주변 밝기 | 화면 밝기 자동 조절, 야간 모드 | 전송하지 않음 |

- **사진**: 앱은 사진 보관함 전체에 접근하는 권한을 요청하지 않습니다. Android의 사진 선택기에서 이용자가 직접 고른 사진만 읽을 수 있고, 고른 사진의 목록(기기 안의 주소, 찍은 날짜, 크기)만 기기에 저장합니다. 사진 파일을 복사하거나 전송하지 않습니다.
- **알림 접근**: 재생 중인 미디어 정보를 읽으려면 Android의 "알림 접근" 권한이 필요합니다. 앱은 이 권한을 미디어 재생 정보와 재생 조작에만 사용하며, 알림의 내용은 읽거나 저장하지 않습니다.

## 2. 기기 밖으로 전송하는 정보

날씨를 표시할 때만 다음 두 곳에 정보를 보냅니다.

1. **Open-Meteo (날씨 서버, https://open-meteo.com)**: 소수 둘째 자리까지 줄인 위도와 경도(약 1km 단위). 계정이나 기기 식별자는 보내지 않습니다. 인터넷 통신의 특성상 Open-Meteo는 요청을 보낸 IP 주소를 알 수 있습니다. Open-Meteo의 개인정보 처리는 https://open-meteo.com/en/terms 를 참고해 주세요.
2. **휴대전화의 주소 변환 서비스 (Android Geocoder)**: 지역 이름(예: "강남구")을 표시하기 위해 같은 방식으로 줄인 위도와 경도를 전달합니다. 이 서비스는 휴대전화 제조사나 Google이 제공하며, 해당 제공자의 개인정보처리방침이 적용됩니다.

위치 권한을 허용하지 않으면 이 전송은 일어나지 않고, 날씨가 표시되지 않습니다.

## 3. 기기에 저장하는 정보

다음 정보는 이용자의 기기 안, 앱 전용 저장공간에만 저장합니다.

- 앱 설정
- 마지막으로 받은 날씨와 지역 이름
- 사진 액자에 쓰려고 고른 사진의 목록

앱을 삭제하거나 Android 설정에서 앱 데이터를 지우면 모두 삭제됩니다. 앱은 이 데이터를 클라우드에 백업하지 않습니다.

## 4. 제3자 제공과 처리 위탁

개발자는 이용자의 정보를 제3자에게 판매하거나 제공하지 않으며, 처리를 위탁하지 않습니다. 2번에 적은 날씨 요청이 기기 밖으로 나가는 유일한 정보입니다.

## 5. 권한과 선택

모든 권한은 선택 사항입니다. 허용하지 않으면 해당 기능만 동작하지 않습니다. 허용한 권한은 Android 설정의 앱 정보에서 언제든지 끌 수 있고, 앱의 "앱 정보 > 권한 안내"에서 각 권한의 용도와 상태를 볼 수 있습니다.

| 권한 | 용도 |
|---|---|
| 위치 (대략적인 위치) | 날씨 |
| 캘린더 읽기 | 일정 표시 |
| 알림 접근 | 재생 중인 미디어 표시와 조작 |
| 근처 기기 (블루투스) | 연결된 블루투스 기기 이름 표시 |
| 다른 앱 위에 표시, 알림 | 충전 시 자동 실행 |

## 6. 잠금 화면

앱은 잠금 화면 위에 표시될 수 있습니다. 이때 일정 제목, 사진, 재생 중인 곡, 기기 이름, 지역 이름이 휴대전화를 잠금 해제하지 않은 사람에게 보일 수 있습니다. 메뉴의 "잠금 중 개인 정보 숨기기"를 켜면 잠겨 있는 동안 이 정보를 표시하지 않습니다.

## 7. 어린이

앱은 어린이를 대상으로 하지 않으며, 어린이를 포함한 누구의 개인정보도 수집하지 않습니다.

## 8. 방침의 변경

이 방침이 바뀌면 이 페이지에 새 내용을 올리고 시행일을 고칩니다.

## 9. 문의

개인정보에 관한 문의: [연락처 이메일]

---

# Stand8 Privacy Policy

Effective date: November 11, 2026

Stand8 (package name `com.kreodn.stand8`, "the app") shows a clock, the weather, your calendar and your photos on the cover screen of your phone while it charges. The developer does not collect your personal data and does not store it on any server. The app has no accounts, no ads, no analytics and no server run by the developer.

## 1. Information the app uses

The app uses the information below only to show it on screen. Unless the last column says otherwise, it is processed only on your device.

| Information | Purpose | Leaves the device |
|---|---|---|
| Approximate location (precise location is not used) | Weather and area name for where you are | Yes (see section 2) |
| Calendar events (title, time, color) | Upcoming events on the weather and calendar page | No |
| Photos you choose | Shown on the photo frame page | No |
| Now-playing media (title, artist, album art) | Shown on the dashboard, with play, pause, previous and next controls | No |
| Names of connected Bluetooth devices, device name | Shown on the device page | No |
| Battery, memory, storage and network status | Shown on the device page | No |
| Charging state, fold state and device tilt | "Open when charging" and "Close when held upright" | No |
| Ambient light | Automatic brightness and night mode | No |

- **Photos**: The app does not ask for access to your photo library. It can read only the photos you pick in the Android photo picker, and it stores only a list of those photos (their on-device address, date taken and size) on your device. It does not copy or send the photo files.
- **Notification access**: Android requires the "notification access" permission to read now-playing media. The app uses it only for media information and playback controls. It does not read or store the content of your notifications.

## 2. Information that leaves the device

Information is sent off the device only to show the weather, to these two places:

1. **Open-Meteo (weather server, https://open-meteo.com)**: your latitude and longitude rounded to two decimal places (about 1 km). No account or device identifier is sent. As with any internet request, Open-Meteo can see the IP address the request comes from. See https://open-meteo.com/en/terms for how Open-Meteo handles data.
2. **Your phone's address lookup service (Android Geocoder)**: the same rounded latitude and longitude, to show an area name. This service is provided by your phone's manufacturer or Google, and their privacy policy applies.

If you do not allow the location permission, nothing is sent and the weather is not shown.

## 3. Information stored on the device

The following is stored only on your device, in the app's private storage:

- Your settings
- The last weather received and the area name
- The list of photos you chose for the photo frame

All of it is deleted when you uninstall the app or clear its data in Android settings. The app does not back this data up to the cloud.

## 4. Sharing

The developer does not sell or share your information with third parties and uses no data processors. The weather request in section 2 is the only information that leaves the device.

## 5. Permissions and your choices

Every permission is optional. If you do not allow one, only the related feature stops working. You can turn a permission off at any time in the Android settings for the app, and "About > Permissions" in the app shows what each permission is for and its current state.

| Permission | Used for |
|---|---|
| Location (approximate) | Weather |
| Read calendar | Showing events |
| Notification access | Showing and controlling now-playing media |
| Nearby devices (Bluetooth) | Showing names of connected Bluetooth devices |
| Display over other apps, notifications | Open when charging |

## 6. Lock screen

The app can appear over the lock screen. Event titles, photos, the playing track, the device name and the area name may then be visible to someone who has not unlocked your phone. Turn on "Hide personal info when locked" in the menu to hide them while the phone is locked.

## 7. Children

The app is not directed at children and does not collect personal data from anyone, including children.

## 8. Changes to this policy

If this policy changes, the new version will be posted on this page with a new effective date.

## 9. Contact

Questions about privacy: [contact email]
