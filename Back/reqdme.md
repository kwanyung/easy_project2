이 폴더는 권영이 만든 백앤드 폴더입니다.

유저 관리
1. 회원가입 버튼을 누르면 비밀번호와 비밀번호 확인만 체크하고 회원가입 처리를 함.
 => 아이디 중복 확인 버튼을 클릭해야 회원가입 가능하도록

 2. 로그인 버튼을 클릭하면 jwt토큰을 res값에 넣어서 줌.
 => 따로 쿠키에 넣거나 하지 않기 때문에 프론트에서 처리해주면 좋겠음.
 (관리 방법도 생각해 봐야함.)

 3. 아이디 중복 확인 버튼을 클릭하면 중복이 있는 경우와 없는 경우 모두 200의 status를 가지는데 이부분을 확인해보면 좋겠음.

 8월 8일 테스트 완료, 로그인, 회원가입, 아이디 중복확인 기능 구현 완료.