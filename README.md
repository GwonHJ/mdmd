## 시연 시나리오 목차

1. 회원가입 시도
    - 회원가입 모달창
    - 유효성(이메일, 휴대폰, 인증번호, 이름, 아이디, 비밀번호, 비밀번호 확인)
        - Success: 회원가입 성공 알림
        - Fail: 각 실패항목+Fail 메세지
            - 각 항목별 null일때
            - 아이디 중복 체크 버튼
                - Success : 사용가능한 아이디입니다.
                - Fail: 사용중인 아이디입니다.
            - 휴대폰 인증
            - 비밀번호 확인 유효성
                - Success
                - Fail
            - 그 외 유효성 검사
                - Fail
                    - 이메일 : 이메일 형식에 맞게 입력(ex) ㅇㅇㅇ@ㅇㅇㅇ.ㅇㅇㅇ)
                    - 비밀번호 : 영문, 숫자, 특수문자 포함 9자리 이상 16자리 이하
                    - 휴대폰 인증 일치
2. 로그인
    - 유효성
        - Success: 로그인 성공 alert
        - Fail: 아이디와 비밀번호를 확인해주세요 alert
3. 회원정보 관리
    - **본인 확인 절차 선행 필수 (비밀번호로 확인)**
        - Success
        - Fail : 잘못된 비밀번호 입니다.
    - 비밀번호 수정
        - 유효성 검사
            - Success: OK
            - Fail: 비밀번호를 확인하세요
    - 회원정보 수정(비밀번호 제외)
        - 유효성 검사
            - Success: 수정 완료
            - Fail: 각 항목 Fail
    - 회원 탈퇴
        - modal: 탈퇴하시겠습니까?
        - '회원 탈퇴' 를 입력하세요
            - Success
            - Fail

4. 아이디/비밀번호 찾기
    - 아이디 찾기
        - Success

        - Fail
    - 비밀번호 찾기
        - Success
        - Fail
5. 메뉴바 선택
    1. 실시간 버스킹 목록
    2. 선호하는 버스킹 장르 목록 선택
        - 선호하는 장르의 버스킹만 목록에 노출
    3. 랭킹 TOP 5
    4. 버스킹 생성 이력
6. 버스킹 검색
7. 버스킹 생성
    - Success
    - Fail
        - 필수 정보 입력 안한 경우
        - 이미 방을 생성한 사람이 또 방을 생성하는 경우

8. 버스킹 수정
    - Success
    - Fail
        - 필수 정보 입력 안한 경우
9. 버스킹 상세
    1. 버스킹 입장
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

12. 좋아요
    - 좋아요 누르기 : 동전이 위에서 밑으로 떨어지는 애니메이션 효과(1회)
13. 화상 화면


--------------------------------------------------------------------------------------------------------------------------------

# 시연시나리오(with 화면 캡쳐)

1. 회원가입 시도
    ![1 메인에서회원가입 버튼 누르는거](https://user-images.githubusercontent.com/45057466/130065904-80672d66-b71f-4db4-991e-9fda25764df4.png)

    - 회원가입 모달창

        ![2 회원가입모달창](https://user-images.githubusercontent.com/45057466/130065908-95861e80-43df-42f2-aaa0-417b708ea2f4.png)

    - 유효성(이메일, 휴대폰, 인증번호, 이름, 아이디, 비밀번호, 비밀번호 확인)
        - Success: 회원가입 성공 알림

            ![1 회원가입 성공 PNG](https://user-images.githubusercontent.com/45057466/130123275-0eb8be24-ad3e-47c2-a7f3-e0820cc1dfaf.png)

        - Fail: 각 실패항목+Fail 메세지
            - 각 항목별 null일때
            
                ![3 각항목별 null](https://user-images.githubusercontent.com/45057466/130065912-894174c6-caa6-4838-8c51-bd8759aa22d3.png)

            - 아이디 중복 체크 버튼
            
                ![4 아이디중복확인버튼 캡쳐](https://user-images.githubusercontent.com/45057466/130065894-989b9c53-9964-4609-a5f4-b3d70bb50d43.png)

                - Success : 사용가능한 아이디입니다.
                    
                    ![5 사용가능한 아이디입니다](https://user-images.githubusercontent.com/45057466/130065913-d09913d7-28a3-424b-8387-dea621e9b86e.png)

                - Fail: 사용중인 아이디입니다.
                    
                    ![6 사용중인 아이디입니다](https://user-images.githubusercontent.com/45057466/130065914-89603a64-33d8-49ab-8a3d-c0d52e325efb.png)
                    
            - 휴대폰 인증

                ![7 휴대폰인증번호가 전송되었습니다](https://user-images.githubusercontent.com/45057466/130065850-5bc19d43-4125-4d29-97bc-7f444279000d.png)
                
                ![8 휴대폰 인증 폰 캡쳐](https://user-images.githubusercontent.com/45057466/130065852-029088ca-fd55-4279-ad56-fa8339af5094.png)

            - 비밀번호 확인
                - Success
                    
                    ![9 비밀번호확인o](https://user-images.githubusercontent.com/45057466/130065885-382a64a7-43bc-4145-87d1-3e2fa5616207.png)

                - Fail
                    
                    ![10 비밀확인x](https://user-images.githubusercontent.com/45057466/130065887-5d0251d8-3f26-4519-80c8-66c7f40194ea.png)
                    
            - 그 외 유효성 검사
                - Fail
                    - 이메일 : 이메일 형식에 맞게 입력(ex) ㅇㅇㅇ@ㅇㅇㅇ.ㅇㅇㅇ)
                    - 비밀번호 : 영문, 숫자, 특수문자 포함 9자리 이상 16자리 이하
                    - 휴대폰 인증 일치하지 않을때
                    
                    ![11 유효성검사실패](https://user-images.githubusercontent.com/45057466/130065916-f88524ac-df5f-4773-b45b-93e1529882d6.png)
           

2. 로그인
    
    ![12 로그인화면](https://user-images.githubusercontent.com/45057466/130065855-c9c6df46-11c3-4541-98ce-41df21b0e19c.png)


    - 유효성
        - Success: 로그인 성공 alert

            ![2 로그인성공 PNG](https://user-images.githubusercontent.com/45057466/130123274-f317ad82-47a1-42c2-a3c8-c267b300773e.png)


        - Fail: 아이디와 비밀번호를 확인해주세요 alert
            
            ![13 로그인실패](https://user-images.githubusercontent.com/45057466/130065857-2e8a7e3f-aeae-4a9e-85f5-b47ead596cbf.png)


3. 회원정보 관리
    - **본인 확인 절차 선행 필수 (비밀번호로 확인)**
        
        ![14 회원정보모달창](https://user-images.githubusercontent.com/45057466/130065860-555141ab-205e-4ff9-be7b-72f93d6abf12.png)


        - Success

            ![회원정보 들어가기전 비밀번호 입력 성공 PNG](https://user-images.githubusercontent.com/45057466/130123740-5a430cb0-ae43-473a-b500-ba7b7f3b1da7.png)

            
            ![15 회원정보창](https://user-images.githubusercontent.com/45057466/130065862-7468a6da-df60-47f0-af76-b86b94ea6746.png)


        - Fail : 잘못된 비밀번호 입니다.
            
            ![16 회원정보창잘못된비밀번호](https://user-images.githubusercontent.com/45057466/130065865-b76af819-75bc-44a0-a6d9-6a942095ddcb.png)

    - 비밀번호 수정

        ![비밀번호 변경 창 캡쳐 PNG](https://user-images.githubusercontent.com/45057466/130123273-d0abf03d-3a56-44a8-9e4b-d2cd0d24c7ed.png)
        
        - 유효성 검사
            - Success: OK

                ![비밀전호 수정 성공 PNG](https://user-images.githubusercontent.com/45057466/130123271-72e1ac8a-e060-4beb-91ae-3bb7fc90d5e7.png)

            - Fail: 비밀번호를 확인하세요

                ![비밀번호 수정 유효성 검사 PNG](https://user-images.githubusercontent.com/45057466/130123269-256ac718-f749-4086-9d17-b844d0c1e1a0.png)
        
    - 회원정보 수정(비밀번호 제외)

        ![회원정보수정(비밀번호x)](https://user-images.githubusercontent.com/45057466/130123268-32b38b4e-57f2-4d5d-81a7-c48130fd933b.png)
    
        - 유효성 검사
            - Success: 수정 완료

                ![회원정보 수정 성공 PNG](https://user-images.githubusercontent.com/45057466/130123266-f84b58fe-2c1b-4772-9bea-4dc916123abd.png)
    
            - Fail: 각 항목 Fail

                ![회원정보 수정 유효성 검사 실패 PNG](https://user-images.githubusercontent.com/45057466/130123264-e00b31b1-3a1c-479b-b17f-9c07a9369153.png)



    - 회원 탈퇴
        - modal: 탈퇴하시겠습니까?

            ![회원탈퇴 창 캡쳐 PNG](https://user-images.githubusercontent.com/45057466/130123262-028166d4-8569-4a4b-913c-491107f48795.png)

        - '회원 탈퇴' 를 입력하세요
            - Success

                ![회원탈퇴 성공 PNG](https://user-images.githubusercontent.com/45057466/130125125-f03a91c7-9c28-4c03-8f40-97b6e3a3285b.png)

            - Fail

                 ![회원탈퇴 실패 PNG](https://user-images.githubusercontent.com/45057466/130125137-79f095c0-1ee6-4b85-b770-894621180e5f.png)

4. 아이디/비밀번호 찾기
    - 아이디 찾기

        ![아이디찾기 PNG](https://user-images.githubusercontent.com/45057466/130123255-3e82ed70-5f74-4b19-813a-cca1c5bb8b42.png)

        - Success

            ![아이디 찾기 성공 PNG](https://user-images.githubusercontent.com/45057466/130123254-96b5e7fc-18be-445b-8aca-223e02b26690.png)

        - Fail

            ![아이디찾기fail PNG](https://user-images.githubusercontent.com/45057466/130123253-b652c1b3-5892-4b18-aef7-1dfd0912092e.png)

    - 비밀번호 찾기

        ![비밀번호찾기 캡쳐 PNG](https://user-images.githubusercontent.com/45057466/130123252-b1e4cd89-0903-4985-ba04-43f5b1541118.png)

        - Success

            ![비밀번호 찾기 성공 PNG](https://user-images.githubusercontent.com/45057466/130123250-071f6f83-c980-4db4-8be4-558ce91e64e5.png)

            ![임시비밀번호 휴대폰 캡쳐](https://user-images.githubusercontent.com/45057466/130163332-27a1f266-a57c-4802-9217-e90b457c17ec.png)

        - Fail

            ![비밀번호 찾기 실패 PNG](https://user-images.githubusercontent.com/45057466/130123249-b1da3481-ebfc-41c8-ba8d-802a3616af28.png)


            

5. 메뉴바 선택

    ![17 메뉴바](https://user-images.githubusercontent.com/45057466/130065866-6c4eafdd-8642-4d53-8a09-8121f5c4b5dd.png)


    1. 실시간 버스킹 목록

        ![실시간 버스킹 목록](https://user-images.githubusercontent.com/45057466/130164536-e8574b51-0319-4768-b7bf-f7c99b86f546.png)


    2. 선호하는 버스킹 장르 목록 선택

        ![선호하는 장르 선택전 PNG](https://user-images.githubusercontent.com/45057466/130123248-ab96a3f3-56b9-46a1-94e9-b93d8180117a.png)
        ![선호하는 장르 선택 PNG](https://user-images.githubusercontent.com/45057466/130123244-dda592d1-184a-4bdd-b0a8-63cbc5804460.png)
        ![선호하는 장르 선택 결과화면 PNG](https://user-images.githubusercontent.com/45057466/130123241-f5d76018-2fa0-476d-87e6-7292a3369200.png)
        

        - 선호하는 장르의 버스킹만 목록에 노출

            ![선호하는 장르 목록 전에 기존의 화면 PNG](https://user-images.githubusercontent.com/45057466/130123285-46f989ba-1bc7-451a-b3a8-246d191f414a.png)
            ![선호하는 장르 목록화면 후 PNG](https://user-images.githubusercontent.com/45057466/130123278-ce46b58c-235a-40d6-8a61-8de9c9acb6bb.png)
   
    3. 랭킹 TOP 5

        ![랭킹 top5](https://user-images.githubusercontent.com/45057466/130164544-c04d35d2-aad6-4034-bde0-e13ed17e61e3.png)
        
    4. 버스킹 생성 이력

        ![18 회의이력](https://user-images.githubusercontent.com/45057466/130065875-3a7e73db-f604-4c0e-83e5-e67f4404b53e.png)


6. 버스킹 검색
    
    ![버스킹 검색 PNG](https://user-images.githubusercontent.com/45057466/130123319-d9af6861-3822-441f-881e-17febc813bcb.png)


7. 버스킹 생성

    ![19 버스킹생성](https://user-images.githubusercontent.com/45057466/130065880-d0229a94-748d-4199-896f-5714ac32a51e.png)

    - Success

        ![버스킹 생성 성공](https://user-images.githubusercontent.com/45057466/130165045-0e2e2b29-9124-4127-a231-be06a67f5938.PNG)

    - Fail
        - 필수 정보 입력 안한 경우
        - 이미 방을 생성한 사람이 또 방을 생성하는 경우

            ![버스킹생성Fail](https://user-images.githubusercontent.com/45057466/130163459-5bc836d9-fcda-4202-a658-c45716cbc0af.PNG)

8. 버스킹 수정

    ![버스킹 정보 수정](https://user-images.githubusercontent.com/45057466/130163550-c963e5ff-37a1-4e80-917a-9aaf05488763.PNG)

    - Success


    - Fail
        - 필수 정보 입력 안한 경우
        - 이미 방을 생성한 사람이 또 방을 생성하는 경우

            ![버스킹 수정 Fail](https://user-images.githubusercontent.com/45057466/130163833-cb216fce-8bd2-4378-83d7-57d9921c7e64.PNG)



9. 버스킹 상세
    1. 버스킹 입장

        ![20 버스킹입장](https://user-images.githubusercontent.com/45057466/130065881-2c77a72f-17d0-424b-bb77-4f8e9ff18ca5.png)

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

        ![21 채팅](https://user-images.githubusercontent.com/45057466/130065896-04af6030-4436-41fd-ae77-7d4f3dd9ddce.png)


12. 좋아요

    ![22 좋아요](https://user-images.githubusercontent.com/45057466/130065890-b692bdab-ad46-4b15-af3d-27c7f5bea404.png)


    - 좋아요 누르기 : 동전이 위에서 밑으로 떨어지는 애니메이션 효과(1회)
13. 화상 화면

    ![23 화상화면](https://user-images.githubusercontent.com/45057466/130065902-d3ef6bbc-fec4-4364-ba5c-5bfce0ed386f.png)

