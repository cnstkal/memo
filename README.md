# Memo

아이폰 메모 앱 느낌의 모바일 메모 웹앱입니다.

## 포함 기능
- 메모 작성 / 수정 / 자동 저장
- 제목 + 본문
- 사진 여러 장 첨부
- Cloudinary 이미지 업로드
- Firebase Authentication 익명 로그인
- Firestore 메모 동기화
- 검색
- 메모 고정
- 메모 삭제
- 모바일 화면 확대 방지
- iOS 키보드가 올라올 때 레이아웃이 튀지 않도록 100dvh/스크롤 구조 적용
- 사진을 클립보드에서 붙여넣기 가능

## Firebase 설정
Firebase Console에서 Authentication > Sign-in method > Anonymous를 활성화하세요.

Firestore Rules에는 저장소의 firestore.rules 내용을 적용하세요.

## Cloudinary
Cloudinary unsigned upload preset 이름을 Everything으로 사용합니다.
