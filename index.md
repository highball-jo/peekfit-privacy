# PeekFit — Privacy Policy

**Effective date: October 19, 2026** (previous version: September 28, 2026)

PeekFit ("the app") is a virtual try-on camera app for iPhone and Android,
published by JoCoding, Inc. This policy explains what information the app
handles and how.

## The short version

- PeekFit has **no accounts** and never asks for your name, email, or password.
- Your **photos never leave your device**. All image processing (clothing
  detection, erasing, compositing) happens on-device.
- **Face data** — if you use the face figure, the app keeps one picture of your
  head on your device so the closet can dress it. It is never uploaded or
  shared, and you can replace it or delete it with the app (see
  [Face data](#face-data)).
- The free version shows ads (Google AdMob). A one-time purchase removes them.
- We measure how the app is used (PostHog) and how our ads perform (Meta),
  using a random identifier — never your name or photos.
- We do not sell your data.

## Camera and photos

- **Camera** — used only to show the live view behind your photo and to
  capture a picture when you press the shutter. The camera feed is not
  recorded, stored, or transmitted.
- **Photo library** — you pick a photo through the system photo picker, which
  gives the app access only to the photos you choose. Merged captures are
  saved back to your library only when you take a shot.
- All person-detection and image editing runs **entirely on your device**
  (Apple Vision and Core ML on iPhone; on-device ML Kit and ONNX Runtime models
  on Android). No photo or camera data is ever uploaded to us or anyone else.

## Face data

PeekFit has an optional **face figure**: if your photo is not full-body, the
app can cut your head out of it and place it on a standard body so you can
still try clothes on. This section describes everything the app does with
face data.

- **What is collected.** When you choose the face figure, the app cuts the
  head (face and hair) out of the photo you picked and stores **one image of
  it**, together with the position of the face inside that image (four numbers:
  a rectangle). The face is found by an on-device model that labels each pixel
  of the photo as face, hair, skin, clothing and so on. The app does **not**
  create face geometry, face landmarks, a face template, a faceprint, or any
  biometric identifier, and it does not use the TrueDepth camera or ARKit face
  tracking. It does not recognize or identify who is in the photo.
- **How it is used.** Only to draw the face figure on the try-on screen and in
  the in-app closet, so that saved garments can be shown on you. It is not used
  for advertising, analytics, profiling, identification, authentication, or to
  train any model.
- **Where it is stored.** Only on your device, in the app's private storage
  (Application Support on iPhone, app-internal storage on Android). It is never
  uploaded to JoCoding or to any server. Like all other app data, it may be
  included in the device backup you make with your own iCloud or Google
  account, if you have device backups turned on; JoCoding has no access to
  those backups.
- **Sharing.** Face data is **never shared** with JoCoding or with any third
  party, including our analytics (PostHog), advertising (Google AdMob),
  ad-measurement (Meta) and purchase (RevenueCat) providers. None of these
  receive any image or face data.
- **Retention.** The app keeps only the most recent face. It is kept until you
  replace it by choosing the face figure with another photo, or until you
  delete the app.
- **Deletion.** Deleting PeekFit from your device deletes the stored face
  immediately and permanently (on iPhone, also remove it from any iCloud backup
  you keep). Because we never receive face data, there is no copy on our side
  to delete.

## Daily try-on counter

Your free try-on count is stored locally on your device only. It contains no
personal information.

## Product analytics (PostHog)

To understand which parts of the app work and where people get stuck, the app
sends usage events to PostHog, an analytics service that processes this data
on our behalf. Events describe actions in the app — for example "a photo was
confirmed", "the clothing cut-out succeeded or failed", "the paywall was
shown", "a rewarded ad was completed", "a purchase was made" (with its price
and currency).

Each event includes:

- a random identifier for your copy of the app (the same anonymous ID our
  purchase service uses — see below);
- the app version, device model, operating system and language;
- your IP address, which PostHog uses to derive an **approximate location**
  (country and city).

PostHog never receives your photos, camera images, or anything you type. The
app does **not** record your screen or sessions. Data is stored on PostHog's
servers in the United States.

See PostHog's policy: <https://posthog.com/privacy>

## Advertising (Google AdMob)

The free version shows banner ads and optional rewarded ads served by Google
AdMob. AdMob may collect device information such as device identifiers,
diagnostics, and ad-interaction data to serve and measure ads.

On iPhone, the app asks for App Tracking Transparency permission. If you
decline, ads are served **without** your device's advertising identifier. On
Android, you can reset or delete your advertising ID in the system settings.

See Google's policy: <https://policies.google.com/technologies/ads>

Purchasing the unlimited unlock removes all advertising permanently.

## Ad measurement (Meta)

We advertise PeekFit on Instagram and Facebook. The app includes Meta's app
events SDK so Meta can tell us how many people installed and opened the app,
and made a purchase, after seeing an ad. It sends app install and open events,
purchase events (amount, currency and product), and device information. On
iPhone, your advertising identifier is included only if you allowed tracking;
otherwise Meta measures installs through Apple's privacy-preserving
SKAdNetwork. On Android, the advertising ID is included unless you have
deleted or reset it in system settings.

See Meta's policy: <https://www.facebook.com/privacy/policy>

## Purchases (Apple, Google Play and RevenueCat)

Payments are processed by Apple or Google Play. We use RevenueCat to validate
purchases and keep your unlock working across your devices. RevenueCat
receives an anonymous random identifier and your purchase history for this
app — never your name, Apple ID, Google account, or payment details.

See RevenueCat's policy: <https://www.revenuecat.com/privacy>

## What we never collect

- Names, email addresses, phone numbers, or contacts
- Precise (GPS) location
- Photos, camera imagery, or any content you create in the app
- Face data of any kind (it stays on your device — see [Face data](#face-data))
- Browsing history or data from other apps

## Your choices and requests

You can decline tracking on iPhone, reset your advertising ID on Android, or
remove the app at any time. To ask us to delete analytics data associated with
your copy of the app, email us; we will delete what we can link to you.

## Children

PeekFit is not directed at children under 13 and does not knowingly collect
personal information from children.

## Changes

If this policy changes, the updated version will be posted at this page with a
new effective date.

## Contact

Questions? Email **highball@jocoding.net**.

---

# PeekFit — 개인정보 처리방침 (한국어)

**시행일: 2026년 10월 19일** (이전 버전: 2026년 9월 28일)

PeekFit(이하 "앱")은 JoCoding, Inc.가 배포하는 iPhone·Android용 가상 피팅
카메라 앱입니다.

## 요약

- 앱에는 **계정이 없으며** 이름, 이메일, 비밀번호를 요구하지 않습니다.
- **사진은 기기 밖으로 전송되지 않습니다.** 옷 인식·지우기·합성 등 모든
  이미지 처리는 기기 내에서만 이루어집니다.
- **얼굴 데이터** — 얼굴 피규어를 사용하면, 옷장에서 옷을 입혀 보여주기 위해
  얼굴(머리) 이미지 한 장을 기기에만 보관합니다. 업로드·공유되지 않으며,
  교체하거나 앱 삭제로 지울 수 있습니다(아래 「얼굴 데이터」 참고).
- 무료 버전에는 Google AdMob 광고가 표시되며, 1회 구매로 광고를 없앨 수
  있습니다.
- 앱 사용 방식(PostHog)과 광고 성과(Meta)를 무작위 식별자로 측정합니다.
  이름이나 사진은 절대 사용하지 않습니다.
- 이용자의 데이터를 판매하지 않습니다.

## 카메라와 사진

- **카메라**는 사진 뒤 실시간 화면 표시와 셔터를 누를 때의 촬영에만
  사용됩니다. 카메라 영상은 녹화·저장·전송되지 않습니다.
- **사진 보관함**은 시스템 사진 선택기를 통해 이용자가 고른 사진에만
  접근하며, 합성 결과물은 촬영 시에만 보관함에 저장됩니다.
- 인물 인식과 편집은 전부 **기기 내에서** 실행되며(iPhone은 Apple Vision·
  Core ML, Android는 기기 내 ML Kit·ONNX Runtime 모델) 어떤 사진도 업로드되지
  않습니다.

## 얼굴 데이터

PeekFit에는 선택 기능인 **얼굴 피규어**가 있습니다. 전신 사진이 아닐 때
사진에서 머리 부분을 오려 표준 몸에 얹어 옷을 입혀 볼 수 있게 하는
기능입니다. 앱이 얼굴 데이터로 하는 일은 아래가 전부입니다.

- **수집 항목.** 얼굴 피규어를 선택하면, 이용자가 고른 사진에서 머리(얼굴과
  머리카락)를 오려 낸 **이미지 한 장**과, 그 이미지 안에서 얼굴의 위치(사각형을
  나타내는 숫자 4개)를 저장합니다. 얼굴은 사진의 각 픽셀을 얼굴·머리카락·피부·
  옷 등으로 구분하는 기기 내 모델로 찾습니다. 앱은 얼굴 기하 정보, 얼굴 특징점,
  얼굴 템플릿·얼굴 인식 정보 등 생체 식별 정보를 만들지 않으며, TrueDepth
  카메라나 ARKit 얼굴 추적을 사용하지 않고, 사진 속 인물이 누구인지 식별하지
  않습니다.
- **이용 목적.** 피팅 화면과 앱 내 옷장에서 얼굴 피규어를 그려 저장한 옷을
  입혀 보여주는 용도로만 사용합니다. 광고, 분석, 프로파일링, 신원 확인, 인증,
  모델 학습에는 사용하지 않습니다.
- **저장 위치.** 기기 안 앱 전용 저장 공간(iPhone은 Application Support,
  Android는 앱 내부 저장소)에만 저장되며, JoCoding이나 어떤 서버에도 업로드되지
  않습니다. 다른 앱 데이터와 마찬가지로, 이용자가 기기 백업을 켜 둔 경우 본인의
  iCloud 또는 Google 계정 기기 백업에 포함될 수 있으며, JoCoding은 이 백업에
  접근할 수 없습니다.
- **제3자 제공.** 얼굴 데이터는 JoCoding을 포함해 **어떤 제3자에게도 제공되지
  않습니다.** 분석(PostHog), 광고(Google AdMob), 광고 성과 측정(Meta), 구매
  (RevenueCat) 서비스도 이미지나 얼굴 데이터를 받지 않습니다.
- **보관 기간.** 가장 최근 얼굴 한 장만 보관하며, 다른 사진으로 얼굴 피규어를
  다시 선택해 교체하거나 앱을 삭제할 때까지 보관합니다.
- **삭제.** 기기에서 PeekFit을 삭제하면 저장된 얼굴이 즉시 영구 삭제됩니다
  (iPhone에서는 보관 중인 iCloud 백업에서도 삭제하세요). 당사는 얼굴 데이터를
  받지 않으므로 당사 측에 삭제할 사본이 없습니다.

## 제품 분석 (PostHog)

앱의 어떤 기능이 잘 작동하고 어디서 막히는지 파악하기 위해, 앱은 사용
이벤트를 당사를 대신해 데이터를 처리하는 분석 서비스 PostHog로 전송합니다.
이벤트는 앱 안의 동작을 나타냅니다(예: 사진 확정, 옷 오려내기 성공·실패,
결제 화면 표시, 보상형 광고 시청 완료, 구매 및 그 가격·통화).

각 이벤트에는 다음이 포함됩니다.

- 앱 설치본마다 부여되는 무작위 식별자(아래 구매 서비스와 같은 익명 ID)
- 앱 버전, 기기 모델, 운영체제, 언어
- IP 주소 — PostHog는 이를 이용해 **대략적 위치**(국가·도시)를 추정합니다.

PostHog는 사진, 카메라 이미지, 이용자가 입력한 내용을 받지 않으며, 앱은
화면이나 세션을 녹화하지 않습니다. 데이터는 미국에 있는 PostHog 서버에
저장됩니다. 자세한 내용: <https://posthog.com/privacy>

## 광고 (Google AdMob)

무료 버전은 Google AdMob의 배너 및 보상형 광고를 표시합니다. AdMob은 광고
제공·측정을 위해 기기 식별자, 진단 정보, 광고 상호작용 데이터를 수집할 수
있습니다. iPhone에서는 앱 추적 투명성(ATT) 권한을 요청하며, 거부하면 광고
식별자 없이 광고가 제공됩니다. Android에서는 시스템 설정에서 광고 ID를
재설정하거나 삭제할 수 있습니다. 자세한 내용:
<https://policies.google.com/technologies/ads>

## 광고 성과 측정 (Meta)

PeekFit은 Instagram·Facebook에 광고를 게재합니다. 광고를 본 뒤 몇 명이 앱을
설치·실행·구매했는지 측정하기 위해 Meta 앱 이벤트 SDK가 포함되어 있으며,
설치·실행 이벤트, 구매 이벤트(금액·통화·상품), 기기 정보를 전송합니다.
iPhone에서는 추적을 허용한 경우에만 광고 식별자가 포함되며, 그렇지 않으면
Apple의 SKAdNetwork로 측정됩니다. Android에서는 광고 ID를 삭제·재설정하지
않은 경우 포함됩니다. 자세한 내용: <https://www.facebook.com/privacy/policy>

## 구매 (Apple, Google Play 및 RevenueCat)

결제는 Apple 또는 Google Play가 처리합니다. 구매 검증과 기기 간 구매 상태
유지를 위해 RevenueCat을 사용하며, RevenueCat은 익명 무작위 식별자와 이 앱의
구매 내역만 전달받습니다. 이름, Apple ID, Google 계정, 결제 정보는 전달되지
않습니다.

## 수집하지 않는 정보

이름·이메일·전화번호·연락처, 정밀(GPS) 위치, 사진 및 앱에서 만든 콘텐츠,
얼굴 데이터(기기에만 보관), 다른 앱의 데이터는 수집하지 않습니다.

## 이용자의 선택과 요청

iPhone에서 추적을 거부하거나, Android에서 광고 ID를 재설정하거나, 언제든
앱을 삭제할 수 있습니다. 앱 설치본과 연결된 분석 데이터의 삭제를 원하시면
이메일로 요청해 주세요. 연결 가능한 데이터를 삭제해 드립니다.

## 문의

**highball@jocoding.net**
