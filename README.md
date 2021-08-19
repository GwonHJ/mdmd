# mdmd
![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/09f3d43e-d9e3-4cb1-8687-f214c72345ab/Untitled.png)

1. 회원가입 시도

    ![회원가입 버튼 누르는거.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3292e2b1-215f-4d73-af6f-f3d54ea31c1a/회원가입_버튼_누르는거.png)

    - 회원가입 모달창

        ![회원가입 화면 버튼 화살표.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5827c89e-1734-4dfb-b3ec-c62d056c06c0/회원가입_화면_버튼_화살표.png)

    - 유효성(이메일, 휴대폰, 인증번호, 이름, 아이디, 비밀번호, 비밀번호 확인)
        - Success: 회원가입 성공 알림
        - Fail: 각 실패항목+Fail 메세지
            - 각 항목별 null일때

                ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b16635d1-687f-4745-9b21-576ac99db9c2/Untitled.png)

            - 아이디 중복 체크 버튼

                ![중복확인버튼 캡쳐.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/998d9391-9503-407b-aacc-e353bde79ed9/중복확인버튼_캡쳐.png)

                - Success : 사용가능한 아이디입니다.

                    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fa3434f5-9242-4c8f-a694-bf00c2225173/Untitled.png)

                - Fail: 사용중인 아이디입니다.

                    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b9a05392-3673-4fea-8504-c1aafc5cc145/Untitled.png)

            - 유효성 검사
                - Fail
                    - 이메일 : 이메일 형식에 맞게 입력(ex) ㅇㅇㅇ@ㅇㅇㅇ.ㅇㅇㅇ)
                    - 비밀번호 : 영문, 숫자, 특수문자 포함 9자리 이상 16자리 이하
                    - 휴대폰 인증 일치

                    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/82a046cd-30da-49fd-b6e4-39f139f80528/Untitled.png)

                - 비밀번호 확인
                    - Success

                        ![비밀번호확인o.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5bc927fb-4b1c-4a32-8bf0-1a8715986acc/비밀번호확인o.png)

                    - Fail

                        ![비밀확인x.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4f0b0a4c-4650-498b-84a0-25feb19037d9/비밀확인x.png)

            - 휴대폰 인증

                ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f02d00e3-4a4e-49d6-97c0-21783d65bb3d/Untitled.png)

                ![휴대폰 인증 캡쳐.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f6773d29-818a-4fea-a260-26d42272d36b/휴대폰_인증_캡쳐.png)

2. 로그인

    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8d73283c-d859-42d2-8d06-3a1ee23f682a/Untitled.png)

    - 유효성
        - Success: 로그인 성공 alert
        - Fail: 아이디와 비밀번호를 확인해주세요 alert

            ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/926e72ef-ca0d-4961-9a2e-62ab50bb4852/Untitled.png)

3. 회원정보 관리
    - **본인 확인 절차 선행 필수 (비밀번호로 확인)**

        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aec8a446-c220-4c2d-9532-12d9a5bb9bfc/Untitled.png)

        - Success

            ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/04aaf247-e327-4881-9ebc-baa77ec91ca6/Untitled.png)

        - Fail : 잘못된 비밀번호 입니다.

            ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/83c18f2c-7d4c-43e3-b1c4-763e45c3b42c/Untitled.png)

    - 비밀번호 수정
        - 유효성 검사
            - Success: OK
            - Fail: 비밀번호를 확인하세요
        - Success:
        - Fail: 비밀번호를 확인하세요
    - 회원정보 수정(비밀번호 제외)
        - 유효성 검사
            - Success: 수정 완료
            - Fail: 각 항목 Fail
    - 회원 탈퇴
        - modal: 탈퇴하시겠습니까?
        - '탈퇴합니다' 를 입력하세요
4. 아이디/비밀번호 찾기
    - 아이디 찾기
        - Success
        - Fail
    - 비밀번호 찾기
        - Success
        - Fail
5. 메뉴바 선택

    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/adca3247-8615-4f07-9a67-a575f98d638e/Untitled.png)

    1. 실시간 버스킹 목록
    2. 선호하는 버스킹 장르 목록 선택
        - 선호하는 장르의 버스킹만 목록에 노출
    3. 랭킹 TOP 5
    4. 버스킹 생성 이력

        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b574f35e-bb90-450d-b011-7a413e3a007a/Untitled.png)

6. 버스킹 검색
7. 버스킹 생성

    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0da40e90-9a75-49d0-8e8d-2b0aed852e0e/Untitled.png)

    - 버스킹 정보 입력
        - 이름, 썸네일, 장르, 참여인원, 상세설명 입력
            - 썸네일 '파일 선택' 추가
            - Success
            - Fail
                - 필수 정보 입력 안한 경우
                - 이미 방을 생성한 사람이 또 방을 생성하는 경우
8. 버스킹 수정
    - 이름, 썸네일, 장르, 참여인원, 상세설명 입력
        - 썸네일
            - '파일 선택' 추가
            - (추후) 실시간 라이브 썸네일
        - Success
        - Fail
            - 필수 정보 입력 안한 경우
9. 버스킹 상세
    1. 버스킹 입장

        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9b4f3ffa-79f9-4719-916f-dd313fd75586/Untitled.png)

        - Success
        - Fail
            - 인원 수 꽉참 : 접근 권한이 없습니다.
            - 종료된 버스킹 : 세션이 만료되었습니다.
    2. 버스킹 나가기
        - 나가기 버튼 누르기
        - 뒤로가기 버튼 누르기
10. 버스킹 종료
    - 뒤로가기 버튼 누르기
    - 종료하기 버튼 누르기
        - 종료하시겠습니까? 확인 창
            - Success: OK
            - Fail: Cancel
11. 채팅
    - 이름-내용

        ![채팅.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d58e951e-3004-4ace-a8eb-a1eb40975a30/채팅.png)

12. 좋아요

    ![좋아요.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b0bf8350-610e-495d-8804-9a77f61c0755/좋아요.png)

    - 좋아요 누르기 : 동전이 위에서 밑으로 떨어지는 애니메이션 효과(1회)
13. 화상 화면

    ![화상화면.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0e6b8342-eafe-4d2f-9e45-c4a838693923/화상화면.png)
