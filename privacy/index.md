---
layout: page
title: 개인정보처리방침
permalink: /privacy/
---

# Mychelin 개인정보처리방침

버전: `2026-08-21.1`  
시행일: 2026년 8월 21일

**이대규**(이하 “운영자”)는 Mychelin 서비스 이용자의 개인정보를 중요하게 생각하며, 개인정보 보호법 등 관련 법령을 준수합니다.

## 1. 처리하는 개인정보

### 서비스 가입·인증

| 구분 | 처리 항목 | 처리 목적 |
|---|---|---|
| 카카오 로그인 | 카카오가 발급한 서비스별 사용자 식별정보, OAuth 인증 결과 | 회원 인증과 동일 사용자 식별 |
| Supabase Auth | 사용자 UUID, 세션·JWT·Refresh Token, 로그인 및 세션 기록 | 로그인 유지, 접근 권한 확인, 보안 |
| 가입 프로필 | 사용자가 직접 입력한 닉네임, 선택한 프로필 사진, 언어 설정 | 프로필 제공, 서비스 표시 |
| 약관 기록 | 문서 종류, 버전, 확인·동의 여부 및 시각 | 가입 처리와 동의 이력 관리 |

Mychelin은 카카오 계정 이메일, 카카오 닉네임 및 카카오 프로필 사진을 요청하거나 앱 프로필로 복사하지 않습니다.

### 기록·소셜 기능

| 기능 | 처리 항목 | 처리 목적 |
|---|---|---|
| 식당 방문 기록 | 장소 공급자 ID, 식당명, 주소, 좌표, 카테고리, 방문일 | 기록 저장, 지도와 목록 표시 |
| 개인 취향 평가 | 맛, 가격 만족도, 특별함, 분위기, 재방문 의사 점수 | 개인 취향 기록·통계·랭킹 |
| 상세 기록 | 메모, 사용자가 선택한 사진 | 방문 경험 보관 |
| 소셜 | 프로필 공개 범위, 기록 공개 범위, 팔로우·차단 관계 | 사용자가 선택한 범위의 소셜 기능 |
| 가보고 싶은 곳 | 저장한 식당과 저장 시각 | 개인 위시리스트 제공 |
| 신고 | 신고 사유, 대상, 작성자, 처리 상태 | 이용자 보호와 서비스 운영 |

### 기기 권한과 자동 생성 정보

- 현재 위치는 주변 검색 또는 지도에서 내 위치 기능을 선택한 순간에만 사용하며 지속적인 이동 경로로 저장하지 않습니다.
- 사진·카메라 권한은 사용자가 사진 추가 또는 촬영 기능을 선택할 때만 요청합니다.
- 서비스 운영 과정에서 앱 버전, 오류 분류, 요청 시각과 같은 최소 기술정보가 생성될 수 있습니다. 식당명, 전체 주소, 정확한 좌표, 메모와 사진 원문은 분석 로그에 넣지 않습니다.

## 2. 처리 목적

개인정보는 다음 목적으로만 처리합니다.

- 카카오 로그인과 회원 식별
- 개인 식당 방문 기록의 저장·조회·수정·삭제
- 개인 취향 통계와 랭킹 제공
- 사용자가 설정한 공개 범위에 따른 소셜 기능 제공
- 신고, 차단, 부정 이용 방지와 보안 대응
- 문의 대응, 계정 내보내기 및 탈퇴 처리
- 서비스 장애 분석과 품질 개선

## 3. 보유 및 이용 기간

1. 회원 정보와 사용자 기록은 원칙적으로 회원 탈퇴 또는 해당 기록 삭제 시까지 보관합니다.
2. 회원이 삭제를 요청하면 활성 서비스 영역에서 지체 없이 삭제 절차를 시작합니다. 외부 저장소나 백업에 남은 데이터는 해당 서비스의 안전한 삭제 주기에 따라 제거됩니다.
3. 관계 법령에서 일정 기간 보관을 요구하는 경우 해당 정보만 법정 기간 동안 분리 보관한 뒤 삭제합니다.
4. 계정 삭제 작업 중 일시적 오류가 발생하면 삭제 작업 상태와 최소 식별정보를 삭제 완료 시까지 보관하여 재시도합니다.

## 4. 제3자 제공

운영자는 이용자의 개인정보를 원칙적으로 제3자에게 제공하지 않습니다. 법령에 근거가 있거나 이용자가 별도로 동의한 경우에는 제공받는 자, 목적, 항목 및 보유 기간을 사전에 알립니다.

회원이 OS 공유 기능을 이용해 직접 다른 앱으로 콘텐츠를 전송하는 경우에는 회원의 요청에 따른 전송이며, 이후 처리는 해당 앱의 개인정보처리방침을 따릅니다.

## 5. 외부 서비스 및 국외 이전

| 이전받는 자 | 이전 국가 | 이전 항목·목적 | 일시·방법 | 기간 |
|---|---|---|---|---|
| Supabase, Inc. | 싱가포르 | 1절의 계정·프로필·방문기록·소셜·동의 데이터 / 인증, DB, 파일 저장 및 서버 기능 제공 | 회원이 가입·로그인·기록 저장을 이용할 때 TLS 암호화 통신으로 전송 | 회원 탈퇴 또는 위탁계약 종료 시까지. 백업은 제공자의 안전한 삭제 주기에 따라 제거 |

Supabase는 프로젝트 리전 `ap-southeast-1`(싱가포르)에서 인증·DB·Storage를 제공합니다. 국외 이전을 원하지 않는 이용자는 가입을 진행하지 않거나 회원 탈퇴를 요청할 수 있습니다. 다만 이 경우 Supabase를 이용하는 계정과 기록 저장 기능을 제공할 수 없습니다.

카카오 로그인·지도·장소 검색 요청은 이용자의 선택에 따라 Kakao Corp.의 시스템과 통신하며, 카카오가 직접 처리하는 정보는 카카오의 개인정보처리방침을 따릅니다.

## 6. 개인정보의 파기

1. 보유 목적이 달성되거나 보유 기간이 끝난 정보는 복구하기 어려운 방법으로 삭제합니다.
2. 전자 파일은 재생할 수 없도록 삭제하고, 출력물이 있는 경우 파쇄 또는 소각합니다.
3. 회원 탈퇴 시 Supabase 세션을 철회하고, 프로필·방문 기록·사진·팔로우·가보고 싶은 곳·동의 기록 및 Auth 사용자를 삭제하며 카카오 연결 해제를 요청합니다.
4. 여러 사용자가 공동으로 참조하는 식당 기본정보는 특정 회원의 개인정보가 아닌 범위에서 유지될 수 있습니다.

## 7. 이용자의 권리와 행사 방법

이용자는 서비스 설정 또는 아래 문의처를 통해 개인정보의 열람, 정정, 삭제, 처리정지, 동의 철회, 기록 내보내기 및 회원 탈퇴를 요청할 수 있습니다. 법정대리인은 관련 법령이 허용하는 범위에서 권리를 행사할 수 있습니다.

운영자는 본인 확인 후 관련 법령이 정한 기간 내에 요청을 처리하고, 처리할 수 없는 정당한 사유가 있으면 그 사유를 안내합니다.

## 8. 만 14세 미만 아동

Mychelin은 원칙적으로 만 14세 이상을 대상으로 하며 가입 시 이를 확인합니다. 만 14세 미만 이용자의 정보가 법정대리인 동의 없이 처리된 사실을 알게 되면 확인 후 삭제 등 필요한 조치를 합니다.

## 9. 안전성 확보조치

- Supabase UUID와 RLS를 이용한 사용자별 데이터 접근 통제
- 전송 구간 암호화와 인증 세션 관리
- 앱에 관리자용 `service_role` 및 카카오 Client Secret을 포함하지 않음
- 사진 저장 경로와 DB 행에 대한 소유자 검증
- 민감 원문을 분석·오류 로그에서 제외
- 계정 삭제와 외부 연결 해제를 위한 재시도 가능한 서버 절차

## 10. 공개 범위와 주의사항

회원이 프로필이나 기록을 공개로 설정하면 닉네임, 프로필 사진 및 허용된 방문 기록이 다른 회원에게 표시될 수 있습니다. 개인 메모, 정확한 현재 위치와 비공개 기록은 공개하지 않습니다. 회원은 설정에서 공개 범위를 변경할 수 있습니다.

## 11. 개인정보 보호 문의

- 개인정보처리자: **이대규**
- 개인정보 보호 책임자: **이대규**
- 개인정보 보호 문의 이메일: **leedstar89@gmail.com**

개인정보 침해에 대한 상담이나 신고가 필요한 경우 개인정보침해 신고센터, 개인정보분쟁조정위원회, 경찰청 등 관계 기관에 문의할 수 있습니다.

## 12. 변경 고지

이 방침의 내용이 변경되면 시행일과 변경 내용을 서비스 내 공지합니다. 수집 항목, 이용 목적, 제3자 제공 등 이용자의 권리에 중요한 변경이 있는 경우 관련 법령에 따라 별도 안내 또는 필요한 동의를 받습니다.

---

# Mychelin Privacy Policy (English Reference Translation)

Version: `2026-08-21.1`  
Effective date: August 21, 2026. The Korean version governs unless mandatory law requires otherwise.

Mychelin uses a Kakao provider identifier and a Supabase UUID to authenticate members. It does **not** request Kakao account email, Kakao nickname, or Kakao profile image. Members directly provide a nickname and may optionally choose a profile image.

The service processes restaurant identifiers, names, addresses and coordinates, visit dates, five taste-rating fields, notes, selected photos, visibility settings, follows, blocks, wishlists, reports, consent versions, and limited technical records. Current location is used only when the member invokes nearby search or “my location” and is not stored as a movement history.

Data is used to provide authentication, personal records, taste analysis, maps, user-controlled social features, safety, export, and deletion. It is generally retained until the member deletes the record or account, subject to legal retention duties and provider backup deletion cycles.

Supabase, Inc. provides authentication, database, storage, and server functions in the `ap-southeast-1` Singapore region. Kakao Corp. provides login, maps, and place search.

Members may request access, correction, deletion, suspension, withdrawal, export, and account deletion. Mychelin is intended for users aged 14 or older.

Controller: **Daegyu Lee (Lee Daegyu / 이대규)**  
Privacy contact: **leedstar89@gmail.com**

