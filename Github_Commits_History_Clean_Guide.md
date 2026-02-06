# Github_Commits_History_Clean_Guide

## 상황
* 하단의 History처럼 병합, 리베이스되고 동일한 내용의 Commit가 너무 많아서 정리가 필요

  <details><summary>Git Commits History</summary>
    
    ```bash
     # git hist
    * [2026-02-04] [5aaadf6] | Search Rental 모듈 분리 및 Hot Reload 기능 추가 {{Lustiora}}  (HEAD -> main, origin/main, origin/HEAD)
    * [2026-02-04] [5922fd4] | test Search Rental 설계중 {{Lustiora}}
    * [2026-02-04] [83d31a4] | test Window Update {{Lustiora}}
    * [2026-02-04] [2758936] | workflow 분리 {{Lustiora}}
    * [2026-02-04] [dbd94c1] | 3. Search Modules (Core Features) C. Rental Search 추가 (Film Search 제거) {{Lustiora}}
    * [2026-02-04] [5fc42e0] | input event 이후 포커스 연결 {{Lustiora}}
    * [2026-02-03] [8af3f58] | view_search_film => view_search_inventory 통합 {{Lustiora}}
    * [2026-02-03] [8e9fa85] | search query 분리 및 search inventory 재설계 완료 {{Lustiora}}
    * [2026-02-03] [5c35aba] |  Search Inventory: View Table 재생성 및 쿼리 재설정 / 재설계중 tuple index out of range {{Lustiora}}
    * [2026-02-03] [0aa020c] | Search Customer: 검색 화면 재설계 (ID or Name (First or Last Name)) {{Lustiora}}
    * [2026-02-02] [f0ae31a] | Customer ID Query Update 및 IF문으로 출력물에 따른 색상 변동 기능 추가 {{Lustiora}}
    * [2026-02-02] [9cfa526] | Customer ID Query Update 및 IF문으로 출력물에 따른 색상 변동 기능 추가 {{Lustiora}}
    * [2026-02-01] [92a515c] | Hard wrap guide {{Lustiora}}
    * [2026-01-31] [0e4e6d5] | query_current_status module query 단축 및 점포에만 존재하는 재고를 출력 {{Lustiora}}
    * [2026-01-31] [8c5ed1f] | Improved variable and function names {{Lustiora}}
    * [2026-01-31] [669d270] | Update Workflow {{Lustiora}}
    * [2026-01-31] [442f577] | Update .gitignore {{Lustiora}}
    * [2026-01-31] [60619be] | Update {{Lustiora}}
    * [2026-01-31] [455f631] | Update Roadmap {{Lustiora}}
    * [2026-01-31] [3a32b97] | Update Readme.md {{Lustiora}}
    * [2026-01-31] [2e4c166] | Update Basic Logic 2.1 {{Lustiora}}
    * [2026-01-30] [717a2cc] | Search Customer Name > store_id + All Status {{Lustiora}}
    * [2026-01-29] [53dde5d] | Workflow Update {{Lustiora}}
    * [2026-01-29] [6bd998d] | Variable Name Change {{Lustiora}}
    * [2026-01-29] [2a327a1] | Search Film Module Create {{Lustiora}}
    * [2026-01-29] [4e1c716] | Search Inventory Module Create {{Lustiora}}
    * [2026-01-29] [0102578] | Hot Reload Test Create {{Lustiora}}
    * [2026-01-29] [060c43f] | Workflow Update {{Lustiora}}
    * [2026-01-29] [ebf70c9] | Search Customer 모듈 분할 완료 {{Lustiora}}
    * [2026-01-29] [ecf2166] | Search Customer 작성 > search_customer 모듈 분할 필요 {{Lustiora}}
    * [2026-01-28] [ce94918] | Search Customer 작성중 {{Lustiora}}
    * [2026-01-28] [10c569a] | Tile Menu Create {{Lustiora}}
    * [2026-01-28] [31fae0a] | Loading Time Force, 1초 지연 옵션, Close 무한 루프 방지 {{Lustiora}}
    * [2026-01-27] [930db22] | Test Nav Tile {{Lustiora}}
    * [2026-01-27] [13764a3] | Status Bar {{Lustiora}}
    * [2026-01-27] [833f593] | Test {{Lustiora}}
    * [2026-01-27] [53e1dee] | Status Bar 연동상태 색상 강조 {{Lustiora}}
    * [2026-01-27] [c5305c4] | delete {{Lustiora}}
    * [2026-01-27] [80dd646] | db_connect, staff_login TextField autofocus=True 추가 {{Lustiora}}
    * [2026-01-27] [d114df4] | Auto Login 시작 시 Connecting to Database Text 추가 {{Lustiora}}
    * [2026-01-27] [fbc9058] | test Sidebar {{Lustiora}}
    * [2026-01-27] [87e7de5] | page.window.~ > windows Issue 해결 {{Lustiora}}
    * [2026-01-27] [aab323d] | DB Connect ~ Main 까지 이어지는 과정 최적화 / DB Monitor > Main Window 연결 {{Lustiora}}
    * [2026-01-27] [5d14da0] | Linux Flet 호환성 옵션 추가 {{Lustiora}}
    * [2026-01-26] [218877b] | Basic Logic 2.1 Flet GUI {{Lustiora}}
    * [2026-01-26] [30537f9] | Basic Logic 2.0 End {{Lustiora}}
    * [2026-01-24] [6f3ba0b] | Rename {{Lustiora}}
    * [2026-01-24] [258a3e4] | custom tkinter 사용을 위한 demo {{Lustiora}}
    * [2026-01-24] [1a53418] | Update {{Lustiora}}
    * [2026-01-24] [232e5d7] | Update {{Lustiora}}
    * [2026-01-24] [e1ff20e] | Update {{Lustiora}}
    * [2026-01-24] [7381e31] | Update {{Lustiora}}
    * [2026-01-24] [015646b] | Update {{Lustiora}}
    *   [2026-01-24] [da65848] | Merge remote-tracking branch 'origin/main' {{Lustiora}}
    |\
    | * [2026-01-24] [bac86d8] | Update {{Lustiora}}
    * | [2026-01-24] [f7e1417] | Update {{Lustiora}}
    |/
    * [2026-01-23] [d8f7b2d] | Theme Change {{Lustiora}}
    * [2026-01-23] [cf9fb08] | Update Workflow {{Lustiora}}
    * [2026-01-23] [7313eb9] | Update Workflow {{Lustiora}}
    * [2026-01-23] [2024922] | tkinter > customtkinter 변환 {{Lustiora}}
    * [2026-01-23] [2034068] | tkinter > customtkinter 변환전 backup {{Lustiora}}
    * [2026-01-23] [f9570b2] | Import Package 가독성 정리 {{Lustiora}}
    * [2026-01-23] [06c816f] | Update {{Lustiora}}
    * [2026-01-23] [32608fe] | 차후 테마 적용을 위한 Menubar Theme 추가 {{Lustiora}}
    * [2026-01-23] [90d19b6] | 차후 테마 적용을 위한 Class Colors 추가 {{Lustiora}}
    * [2026-01-23] [2671261] | Menubar Status_Frame Login Staff 표시 staff_login > main_window {{Lustiora}}
    * [2026-01-23] [200b068] | Folder 정리 {{Lustiora}}
    * [2026-01-23] [0e64d74] | Update Workflow {{Lustiora}}
    * [2026-01-23] [a9f2cf0] | Menubar Module 별도 py 분리 (Sub Frame change, delete, add) {{Lustiora}}
    * [2026-01-23] [ea969e5] | start_move, on_drag 이전 {{Lustiora}}
    * [2026-01-23] [e446535] | Menubar Module 별도 py 분리 (Sub Frame search) {{Lustiora}}
    * [2026-01-23] [cca4171] | Update Workflow {{Lustiora}}
    * [2026-01-23] [154f5a1] | Linux Compile Test >> Clear {{Lustiora}}
    * [2026-01-22] [9ab9f3e] | Update Workflow {{Lustiora}}
    * [2026-01-22] [bfbbeac] | Update Windows Sandbox Test {{Lustiora}}
    * [2026-01-22] [f7bed7f] | Update {{Lustiora}}
    * [2026-01-22] [32d53e6] | Update {{Lustiora}}
    * [2026-01-22] [50798aa] | Update Workflow {{Lustiora}}
    * [2026-01-22] [4df0c02] | Update Workflow {{Lustiora}}
    * [2026-01-22] [7408a4a] | Update Workflow {{Lustiora}}
    * [2026-01-22] [c467928] | Update Workflow {{Lustiora}}
    * [2026-01-22] [dd87e83] | Windows EXE Compile Restart Error Debug {{Lustiora}}
    * [2026-01-22] [7d52b4c] | Windows EXE Compile Restart Error Debug {{Lustiora}}
    * [2026-01-22] [d94ab58] | Update Workflow {{Lustiora}}
    * [2026-01-22] [1e004ad] | Update + os.chdir(current_dir) {{Lustiora}}
    * [2026-01-22] [6bdde50] | Linux에서 재시작이 성공했으나 Windows에서 재시작이 실패 > 사용하는 os를 확인하는 logic을 추가하여 시도 방법 분기 + connect test 모듈을 차후 재사용가능하게끔 분리 {{Lustiora}}
    * [2026-01-22] [ac12589] | Update {{Lustiora}}
    * [2026-01-22] [78d3606] | Update {{Lustiora}}
    * [2026-01-22] [7d4ff42] | Linux_Sakila_Basic_Logic_2_3 {{Lustiora}}
    * [2026-01-22] [d8be4e0] | Update {{Lustiora}}
    * [2026-01-22] [63a2256] | Update {{Lustiora}}
    * [2026-01-22] [7e78f46] | Linux : DB Disconnect Restart Debug + Status Bar 구현 {{Lustiora}}
    * [2026-01-22] [7d401bd] | center_window_delayed Debug resizable=False > None {{Lustiora}}
    * [2026-01-21] [9128a6f] | Window Array Middle Debug {{Lustiora}}
    * [2026-01-21] [8fd6fc9] | Update {{Lustiora}}
    * [2026-01-21] [4bd8512] | Window Array Middle Debug {{Lustiora}}
    * [2026-01-21] [15279a4] | Linux 호환 설정 if sys.platform == "win32": {{Lustiora}}
    * [2026-01-21] [9dc86c1] | Update {{Lustiora}}
    * [2026-01-21] [c37d12f] | 전역변수, 구분 주석, DB Connect 5s Test, 연결 실패시 db_connect.py 연결 추가 {{Lustiora}}
    * [2026-01-21] [36405f5] | Update {{Lustiora}}
    * [2026-01-21] [9364057] | Update {{Lustiora}}
    * [2026-01-21] [a4af9f0] | change Messagebox.showinfo > showerror {{Lustiora}}
    * [2026-01-21] [143c462] | 메뉴바 작성, main_window 활성화 시 staff_login 종료 로직 수정 {{Lustiora}}
    * [2026-01-21] [bcafa6e] | 메뉴바 작성, main_window 활성화 시 staff_login 종료 로직 수정 {{Lustiora}}
    * [2026-01-21] [c4ac67d] | 주석 수정 {{Lustiora}}
    * [2026-01-20] [9acea16] | Main_window GUI 구현중 {{Lustiora}}
    * [2026-01-20] [033fe08] | Main_window GUI 구현중 {{Lustiora}}
    * [2026-01-20] [69ce2dc] | Main_window GUI 구현중 {{Lustiora}}
    * [2026-01-20] [89aa83c] | Update center_window / resizable + min_size {{Lustiora}}
    * [2026-01-20] [e15fae6] | Update center_window / resizable {{Lustiora}}
    * [2026-01-20] [ad71927] | Update {{Lustiora}}
    * [2026-01-20] [46f3c96] | Rename main.py > main_window.py {{Lustiora}}
    * [2026-01-20] [9e92a24] | Update {{Lustiora}}
    * [2026-01-20] [f172da9] | Update README.md {{Lustiora}}
    * [2026-01-20] [06a6f7a] | Update README.md {{Lustiora}}
    * [2026-01-20] [25b6e5d] | Decode Fail : Last > First {{Lustiora}}
    * [2026-01-20] [85f5711] | Update Image {{Lustiora}}
    * [2026-01-20] [f811811] | Image Upload {{Lustiora}}
    * [2026-01-20] [9fbcafe] | if print "Not Connected Time Out" 순서 오류 수정 {{Lustiora}}
    * [2026-01-20] [61eaa52] | 주석 추가 {{Lustiora}}
    * [2026-01-20] [71d4b46] | 주석 추가 {{Lustiora}}
    * [2026-01-20] [6c0bb87] | 저장정보 암호화 Logic 추가 {{Lustiora}}
    * [2026-01-20] [6a36c5b] | staff_login.py 구현 완료  Basic Logic 2.0 / 1. Login Logic 완료 {{Lustiora}}
    * [2026-01-20] [7626d5b] | save_config edit : if/else Delete {{Lustiora}}
    * [2026-01-20] [2c22402] | Login Config Module 구현 완료 / DB 연결시 ini을 저장+ 재연결시 ini을 확인하여 자동 입력 {{Lustiora}}
    * [2026-01-20] [38b7684] | Login Logic 구현중 {{Lustiora}}
    * [2026-01-19] [1bcb6a0] | Login Logic 구현중 > Load Config Module Error {{Lustiora}}
    * [2026-01-19] [707a2d2] | Update Basic Logic 2.0 Roadmap Create {{Lustiora}}
    * [2026-01-19] [1f09ad7] | Rename project from 'Python-Sakila-Manager' to 'Python-Sakila' {{FUllStar}}
    * [2026-01-18] [4a2613c] | Expand README with future logic and improvement details {{FUllStar}}
    * [2026-01-16] [c63b222] | 구조 변경을 통한 동작 흐름 최적화 {{Lustiora}}
    * [2026-01-16] [a2a672b] | Update {{Lustiora}}
    * [2026-01-16] [fa9c032] | Update {{Lustiora}}
    * [2026-01-16] [004fae4] | 실행시 포커스 이탈 수정 + Sakila Manager Window 강제 포커스 고정 {{Lustiora}}
    * [2026-01-16] [c20b2eb] | 결제기능 구현 + 연체료와 대여료를 합산하여 결제도 가능 + 전역변수 추가 {{Lustiora}}
    * [2026-01-16] [df2f353] | 키보드 입력 최적화 {{Lustiora}}
    * [2026-01-16] [2f5ac3c] | DVD 목록 검색기능 + 계산 버튼 추가 {{Lustiora}}
    * [2026-01-16] [223bf96] | DVD 목록 검색기능 + 계산 버튼 추가 {{Lustiora}}
    * [2026-01-15] [8f7595d] | Update .gitignore {{Lustiora}}
    *   [2026-01-15] [0c3e917] | Merge remote-tracking branch 'origin/main' {{Lustiora}}
    |\
    | * [2026-01-15] [ca83bb2] | Delete .idea directory {{FUllStar}}
    * | [2026-01-15] [81cc847] | 미반납 자료가 없는 경우 출력되는 부분 추가 {{Lustiora}}
    |/
    * [2026-01-15] [1d64772] | Create .gitignore {{Lustiora}}
    * [2026-01-15] [347149c] | 외부 접속 테스트 > 성공 {{Lustiora}}
    * [2026-01-15] [08f15ec] | Main 모듈 + 고객번호 입력값 검사 (숫자입력강제) > 고객 검색 화면 구성 + 미반납이력 출력 {{Lustiora}}
    * [2026-01-15] [280041d] | Main 모듈 + 입력값 검사 > 고객 검색 화면 구성 {{Lustiora}}
    * [2026-01-15] [cf7e77d] | Login 가능횟수(3) 지정, Window 중앙 정렬 Module 추가 {{Lustiora}}
    * [2026-01-15] [ad018fd] | Login GUI 구현 {{Lustiora}}
    * [2026-01-15] [786c789] | GUI Create Test {{Lustiora}}
    * [2026-01-14] [8be2eb8] | Film Cart, Film Cart List, Total Fee {{Lustiora}}
    * [2026-01-14] [47e7c54] | 대여 모듈 장바구니 기능 추가 {{Lustiora}}
    * [2026-01-14] [ce2fad7] | 대여 모듈 추가 {{Lustiora}}
    * [2026-01-14] [3ca6939] | 스파게티 코드의 모듈화 , 사용자 확인 구간에서 종료 커맨드 추가 {{Lustiora}}
    * [2026-01-14] [ed5b78c] | Rename login.py to main_test1.py {{FUllStar}}
    * [2026-01-14] [3b97f99] | Full Return List {{Lustiora}}
    * [2026-01-13] [44f901f] | Return List = 1 , >= 1 {{Lustiora}}
    *   [2026-01-13] [7c8a726] | CLI v1 Return DVD List 추가필요 {{Lustiora}}
    |\
    | * [2026-01-13] [09ff0bf] | CLI v1 {{Lustiora}}
    * [2026-01-13] [8241288] | CLI v1 Return DVD List 추가필요 {{Lustiora}}
    * [2026-01-13] [d4e8a3c] | CLI v1 {{Lustiora}}
    ```
  
  </details>

  <details><summary>Git Commits History Clean</summary>

  ```bash
  # git log --all --graph --decorate --oneline
  * 802d771 (HEAD -> main, origin/main, origin/HEAD) Search Rental GUI View Clear
  * 0384956 Test GUI PostgreSQL Connect
  * 1d57720 Search Rental 모듈 분리 및 Hot Reload 기능 추가
  * 8d13771 test Search Rental 설계중
  * 6c82a35 test Window Update
  * d545106 workflow 분리
  * 95d5713 3. Search Modules (Core Features) C. Rental Search 추가 (Film Search 제거)
  * 8d9c435 input event 이후 포커스 연결
  * 5d340a3 view_search_film => view_search_inventory 통합
  * 73b6813 search query 분리 및 search inventory 재설계 완료
  * 3f0a73f  Search Inventory: View Table 재생성 및 쿼리 재설정 / 재설계중 tuple index out of range
  * 2674806 Search Customer: 검색 화면 재설계 (ID or Name (First or Last Name))
  * f652c27 Customer ID Query Update 및 IF문으로 출력물에 따른 색상 변동 기능 추가
  * cd80402 Hard wrap guide
  * ebbf988 query_current_status module query 단축 및 점포에만 존재하는 재고를 출력
  * f2bb05f Improved variable and function names
  * d6bab30 Update Roadmap
  * 02c6c4d Update Readme.md
  * d9562fc Update Basic Logic 2.1
  * c44e736 Search Customer Name > store_id + All Status
  * d6e6c0d Variable Name Change
  * 6f1c86a Search Film Module Create
  * 26302ce Search Inventory Module Create
  * 88211f6 Hot Reload Test Create
  * 01d580b Workflow Update
  * e6656c2 Search Customer 모듈 분할 완료
  * a27e40e Search Customer 작성 > search_customer 모듈 분할 필요
  * abca10e Search Customer 작성중
  * 95db172 Tile Menu Create
  * bb4f264 Loading Time Force, 1초 지연 옵션, Close 무한 루프 방지
  * 1e56aef Test Nav Tile
  * 5e45bef Status Bar
  * 42533d0 Test
  * 4f18abc Status Bar 연동상태 색상 강조
  * 959d043 delete
  * cc05f03 db_connect, staff_login TextField autofocus=True 추가
  * 3251aaa Auto Login 시작 시 Connecting to Database Text 추가
  * 5188b2e test Sidebar
  * 723eebc page.window.~ > windows Issue 해결
  * 6349827 DB Connect ~ Main 까지 이어지는 과정 최적화 / DB Monitor > Main Window 연결
  * ec38b04 Linux Flet 호환성 옵션 추가
  * 71292e4 Basic Logic 2.1 Flet GUI
  * 365ef18 Basic Logic 2.0 End
  * 5eb20c7 Rename
  * 105f793 custom tkinter 사용을 위한 demo
  * 9d9997f Theme Change
  * aecac99 tkinter > customtkinter 변환
  * 8924ba0 tkinter > customtkinter 변환전 backup
  * 9303651 Import Package 가독성 정리
  * da9a7d1 차후 테마 적용을 위한 Menubar Theme 추가
  * 8dd2401 차후 테마 적용을 위한 Class Colors 추가
  * b1e174f Menubar Status_Frame Login Staff 표시 staff_login > main_window
  * eeb9562 Folder 정리
  * 396ce85 Menubar Module 별도 py 분리 (Sub Frame change, delete, add)
  * a09c97e start_move, on_drag 이전
  * 529159f Menubar Module 별도 py 분리 (Sub Frame search)
  * 74bc3dc Linux Compile Test >> Clear
  * 9325eca Update Windows Sandbox Test
  * 380e9e3 Windows EXE Compile Restart Error Debug
  * 2cb8b47 Update Workflow
  * 72f7c0d Update + os.chdir(current_dir)
  * 3edcd61 Linux에서 재시작이 성공했으나 Windows에서 재시작이 실패 > 사용하는 os를 확인하는 logic을 추가하여 시도 방법 분기 + connect test 모듈을 차후 재사용가능하게끔 분리
  * 9714358 Linux_Sakila_Basic_Logic_2_3
  * 594f3a8 Linux : DB Disconnect Restart Debug + Status Bar 구현
  * 933420e center_window_delayed Debug resizable=False > None
  * c5a46bd Window Array Middle Debug
  * 1fc989a Linux 호환 설정 if sys.platform == "win32":
  * 57873d0 전역변수, 구분 주석, DB Connect 5s Test, 연결 실패시 db_connect.py 연결 추가
  * c6fdddd change Messagebox.showinfo > showerror
  * 5e7a418 메뉴바 작성, main_window 활성화 시 staff_login 종료 로직 수정
  * 6e38a82 주석 수정
  * b7c2355 Main_window GUI 구현중
  * f606313 Update center_window / resizable + min_size
  * fdf5ad7 Update center_window / resizable
  * d36e1db Rename main.py > main_window.py
  * 5e75a84 Update README.md
  * 932c830 Decode Fail : Last > First
  * 933f575 Update Image
  * 63fe480 Image Upload
  * 1add880 if print "Not Connected Time Out" 순서 오류 수정
  * a99f14c 주석 추가
  * bdea92c 저장정보 암호화 Logic 추가
  * 2ec63b9 staff_login.py 구현 완료  Basic Logic 2.0 / 1. Login Logic 완료
  * 3362641 save_config edit : if/else Delete
  * 17588dd Login Config Module 구현 완료 / DB 연결시 ini을 저장+ 재연결시 ini을 확인하여 자동 입력
  * 1a42a38 Login Logic 구현중
  * 084a3d4 Login Logic 구현중 > Load Config Module Error
  * cb7dac0 Update Basic Logic 2.0 Roadmap Create
  * c7ac4a1 Rename project from 'Python-Sakila-Manager' to 'Python-Sakila'
  * e4fb66e Expand README with future logic and improvement details
  * 5e6b49f 구조 변경을 통한 동작 흐름 최적화
  * 5aa5ccb Update
  * 7a136b7 실행시 포커스 이탈 수정 + Sakila Manager Window 강제 포커스 고정
  * b883d5a 결제기능 구현 + 연체료와 대여료를 합산하여 결제도 가능 + 전역변수 추가
  * db67a2b 키보드 입력 최적화
  * 09f64c3 DVD 목록 검색기능 + 계산 버튼 추가
  * be92ac0 Update .gitignore
  * aad9564 미반납 자료가 없는 경우 출력되는 부분 추가
  * 144376a Delete .idea directory
  * ddc7ea2 Create .gitignore
  * 5bdf2ab 외부 접속 테스트 > 성공
  * ad8aec5 Main 모듈 + 고객번호 입력값 검사 (숫자입력강제) > 고객 검색 화면 구성 + 미반납이력 출력
  * 89138d4 Main 모듈 + 입력값 검사 > 고객 검색 화면 구성
  * 08a58b9 Login 가능횟수(3) 지정, Window 중앙 정렬 Module 추가
  * 312d594 Login GUI 구현
  * 2a47c89 GUI Create Test
  * 9b72473 Film Cart, Film Cart List, Total Fee
  * 9bb1727 대여 모듈 장바구니 기능 추가
  * b06d3e5 대여 모듈 추가
  * f21ce79 스파게티 코드의 모듈화 , 사용자 확인 구간에서 종료 커맨드 추가
  * 86eef4e Rename login.py to main_test1.py
  * 8f29df2 Full Return List
  * 46531ae Return List = 1 , >= 1
  * 863c36d CLI v1 Return DVD List 추가필요
  * 5b5eb76 CLI v1
  ```

  </details>

## 1단계: 무한 충돌 해결 (불도저 스크립트)

수백 개의 커밋을 가져오는데 파일 이름 변경 등으로 충돌이 계속 날 때, **"묻지도 따지지도 말고 진행시켜"** 하는 스크립트입니다.

### 📜 `fix_git_final.py` (생성용 파이썬 코드)

* **기능:** `[Linux → restore_final.sh]`,`[Windows → restore_final.bat]` 쉘 스크립트를 생성함.
* **핵심 로직:**
1. `git cherry-pick -Xtheirs`: 충돌 시 "가져오는 쪽(Theirs)" 내용을 무조건 채택.
2. `rm -rf build ...`: 빌드 파일 등 찌꺼기가 길을 막으면 삭제.
3. `commit --allow-empty`: 에러 방지용으로 중간 저장을 강제로 수행.

<details><summary>Linux</summary>
  
  ```python
  #!/usr/bin/env python3
  import subprocess
  import os
  import stat
  
  def run_git_command(command):
      try:
          result = subprocess.check_output(command, shell=True, encoding='utf-8')
          return result.strip()
      except subprocess.CalledProcessError:
          return ""
  
  def generate_final_script():
      print("🤖 [Final-Solver] Git 히스토리 완전 복구 스크립트 생성 중...")
  
      # 머지 커밋 제외하고 가져오기
      log_cmd = 'git log --reverse --no-merges --pretty=format:"%h|%s"'
      logs = run_git_command(log_cmd).split('\n')
  
      seen_subjects = set()
      clean_commits = []
  
      for line in logs:
          if not line: continue
          try:
              parts = line.split('|', 1)
              if len(parts) < 2: continue
              commit_hash = parts[0]
              subject = parts[1].strip()
  
              if subject in seen_subjects: continue
              if "Merge remote-tracking" in subject: continue
  
              seen_subjects.add(subject)
              clean_commits.append((commit_hash, subject))
          except:
              continue
  
      filename = "restore_final.sh"
      with open(filename, "w", encoding="utf-8") as f:
          f.write("#!/bin/bash\n")
          f.write("echo '=== 🚀 Final Auto-Restore Start ==='\n")
          
          # 초기화 (Main으로 이동 후 복구용 브랜치 재생성)
          f.write("echo '[Step 1] Resetting Branch...'\n")
          f.write("git checkout main\n") 
          f.write("git branch -D clean_restored_final 2>/dev/null\n")
          f.write("git checkout --orphan clean_restored_final\n")
          f.write("git rm -rf .\n")
          
          f.write("echo '[Step 2] Aggressive Cherry-picking...'\n")
          
          for commit_hash, subject in clean_commits:
              safe_subject = subject.replace("'", "'\\''")
              f.write(f"echo 'Processing: {safe_subject}'\n")
              
              # [핵심] 찌꺼기 정리 및 강제 진행
              f.write("git add .\n")
              f.write("git commit --allow-empty -m 'Auto-save intermediate state' > /dev/null 2>&1\n")
              f.write(f"git cherry-pick -Xtheirs --allow-empty {commit_hash}\n")
              
              # 충돌 발생 시 자동 해결 (빌드 파일 삭제 후 진행)
              f.write("if [ -f .git/CHERRY_PICK_HEAD ]; then\n")
              f.write("  echo '  ⚠️ Conflict detected. Auto-resolving...'\n")
              f.write("  rm -rf build dist *.spec __pycache__ */__pycache__\n")
              f.write("  git add .\n")
              f.write("  git cherry-pick --continue --no-edit\n")
              f.write("fi\n")
              f.write("echo '--------------------------------'\n")
          
          f.write("echo '=== 🎉 All Done! ==='\n")
  
      st = os.stat(filename)
      os.chmod(filename, st.st_mode | stat.S_IEXEC)
      print(f"🔥 '{filename}' 생성 완료! 실행 명령: ./{filename}")
  
  if __name__ == "__main__":
      generate_final_script()
  
  ```

  ### 👉 실행 방법
  
  ```bash
  python fix_git_final.py
  bash restore_final.sh
  
  ```

</details>

<details><summary>Windows</summary>
  
  ```python
  #!/usr/bin/env python3
  import subprocess
  import os
  
  def run_git_command(command):
      try:
          result = subprocess.check_output(command, shell=True, encoding='utf-8')
          return result.strip()
      except subprocess.CalledProcessError:
          return ""
  
  def generate_final_script_win():
      print("🤖 [Windows-Solver] Git 히스토리 복구 스크립트(Batch) 생성 중...")
  
      # 머지 커밋 제외하고 가져오기
      log_cmd = 'git log --reverse --no-merges --pretty=format:"%h|%s"'
      logs = run_git_command(log_cmd).split('\n')
  
      seen_subjects = set()
      clean_commits = []
  
      for line in logs:
          if not line: continue
          try:
              parts = line.split('|', 1)
              if len(parts) < 2: continue
              commit_hash = parts[0]
              subject = parts[1].strip()
  
              if subject in seen_subjects: continue
              if "Merge remote-tracking" in subject: continue
  
              seen_subjects.add(subject)
              clean_commits.append((commit_hash, subject))
          except:
              continue
  
      # 배치 파일(.bat) 작성
      filename = "restore_final.bat"
      with open(filename, "w", encoding="utf-8") as f:
          f.write("@echo off\n")
          f.write("chcp 65001 > nul\n")  # 한글 깨짐 방지
          f.write("echo === 🚀 Final Auto-Restore Start (Windows) ===\n")
          
          # 1. 초기화
          f.write("echo [Step 1] Resetting Branch...\n")
          f.write("git checkout main\n") 
          f.write("git branch -D clean_restored_final 2>nul\n")
          f.write("git checkout --orphan clean_restored_final\n")
          f.write("git rm -rf .\n")
          
          f.write("echo [Step 2] Aggressive Cherry-picking...\n")
          
          for commit_hash, subject in clean_commits:
              # 배치 파일에서 %는 %%로 이스케이프 해야 함
              safe_subject = subject.replace("'", "").replace("%", "%%")
              f.write(f"echo Processing: {safe_subject}\n")
              
              # [핵심 1] 찌꺼기 정리 (Windows 명령어)
              f.write("git add .\n")
              f.write("git commit --allow-empty -m \"Auto-save intermediate state\" > nul 2>&1\n")
              
              # [핵심 2] 체리픽 시도
              f.write(f"git cherry-pick -Xtheirs --allow-empty {commit_hash}\n")
              
              # [핵심 3] 충돌 감지 및 해결 (errorlevel 확인)
              f.write("if %ERRORLEVEL% NEQ 0 (\n")
              f.write("  echo   ⚠️ Conflict detected. Auto-resolving...\n")
              # 윈도우용 삭제 명령어
              f.write("  if exist build rmdir /s /q build\n")
              f.write("  if exist dist rmdir /s /q dist\n")
              f.write("  if exist *.spec del /f /q *.spec\n")
              f.write("  if exist __pycache__ rmdir /s /q __pycache__\n")
              f.write("  git add .\n")
              f.write("  git cherry-pick --continue --no-edit\n")
              f.write(")\n")
              
              f.write("echo --------------------------------\n")
          
          f.write("echo === 🎉 All Done! ===\n")
          f.write("pause\n") # 창이 바로 꺼지지 않게 대기
  
      print(f"🔥 '{filename}' 생성 완료!")
      print(f"👉 실행 방법: 탐색기에서 더블클릭하거나 터미널에서 .\\{filename} 입력")
  
  if __name__ == "__main__":
      generate_final_script_win()
  ```
  
  ### 👉 실행 방법
  
  ```bash
  python fix_git_final.py
  .\Hot_Reload_for_Windows.bat
  
  ```

</details>


---

## 2단계: 로그 세탁 (Auto-save 지우기)

1단계에서 생긴 수많은 `Auto-save intermediate state` 커밋을 없애고, 알맹이만 남기는 과정입니다.

### 📜 `clean_log.py` (청소부 스크립트)

* **기능:** Git Rebase가 열릴 때, 사람이 편집하는 대신 이 스크립트가 리스트를 수정함.
* **핵심 로직:**
1. 맨 처음(`First Commit`)이 `Auto-save`면? -> **`drop` (버림)**
2. 중간에 나온 `Auto-save`면? -> **`fixup` (앞 커밋에 내용만 합치고 메시지 삭제)**
3. 나머지는? -> **`pick` (그대로 유지)**



```python
#!/usr/bin/env python3
import sys

filepath = sys.argv[1]

with open(filepath, 'r') as f:
    lines = f.readlines()

new_lines = []
is_first_commit = True

for line in lines:
    if line.strip().startswith('#') or not line.strip():
        new_lines.append(line)
        continue

    if "Auto-save intermediate state" in line:
        if is_first_commit:
            new_lines.append(line.replace("pick", "drop", 1)) # 첫 줄은 삭제
        else:
            new_lines.append(line.replace("pick", "fixup", 1)) # 나머지는 합치기
    else:
        new_lines.append(line)
        if is_first_commit:
            is_first_commit = False # 정상 커밋 나오면 플래그 해제

with open(filepath, 'w') as f:
    f.writelines(new_lines)

```

### 👉 실행 방법 (Rebase)

```bash
GIT_SEQUENCE_EDITOR="python3 clean_log.py" git rebase -i --root

```

---

## 3단계: 깃허브 강제 업로드 (마무리)

로컬은 깨끗한데 깃허브(Remote)는 더러워서, IDE(파이참 등)에서 "거부됨" 경고가 뜰 때 해결법입니다.

### 🚫 주의사항

* IDE의 "병합(Merge)"이나 "리베이스" 버튼은 **절대 클릭 금지!** (도로묵 됨)
* **터미널**을 사용해야 함.

### 👉 실행 명령어

```bash
# 로컬의 main을 깨끗한 브랜치로 교체 (필요시)
git branch -D main
git branch -m main

# 깃허브에 '내 말이 법이다'라고 강제로 밀어넣기
git push -f origin main

```
