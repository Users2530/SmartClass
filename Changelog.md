## 스마트 클래스 (kr.hs.gimpo.smartclass) 변경 기록

현재 최신 버전: (2018-08-19 기준) <br>
Release : 1.0.0 (2018-08-19)<br>
Beta : 3.5.3-beta (2018-08-19)<br>

- 1.0.0 변경 사항 (2018-08-19)
  - 수정된 사항
    - 최초 릴리스

- 3.5.3-beta 변경 사항 (2018-08-19)
  - 수정된 사항
    - 기능 개선: 인트로 화면이 조금 더 빨라졌습니다! 데이터 초기화 과정에서, 켜질 때마다 초기화하는 대기질 데이터를 제외했거든요.
    - 기능 개선: 이제 급식이 있는 날에는 제대로 급식이 표시됩니다! 중식과 석식이 바뀐다거나 하는 일은 없을 거에요!
    - 기타 알림: 이 버전은 플레이 스토어에 1.0.0 버전으로 정식 출시될 예정이랍니다! 그래도 베타테스트는 계속된답니다
    - 기타 알림: 고양이는 귀여워요! 고양이는 너무나도 귀여운 생물이에요! 중요하니까 두 번 말했어요...

- 3.5.2-beta 변경 사항 (2018-08-03)
  - 수정된 사항
    - 기능 추가: '인트로' 화면이 아주 아름다워졌습니다! 이제 '인트로' 화면에서도 버전 정보를 확인할 수 있습니다.
    - 기능 추가: '학사일정' 화면 또한 아주 아름다워졌습니다! 이제 '학사일정' 화면에서 주 단위로 학사일정을 확인하실 수 있습니다.
    - 기능 개선: 데이터를 받아오는 메커니즘이 다소 변경되었습니다. 이제 '학교 주변 대기상태' 정보는 정시에 받아오지 않고 정시 10분 후에 받아옵니다.
    - 기능 삭제: '메인' 화면과 앱 서랍에서 접근할 수 없었던 '시간표' 기능을 삭제하였습니다.
    - 기능 삭제: '설정' 기능이 삭제되었습니다. 아직 '설정' 화면에서 설정을 해도 작동하지 않아 삭제하였습니다.
    - 기능 삭제: 일본어 번역이 삭제되었습니다.
  - 알려진 버그
    - 중식 내용과 석식 내용이 바뀌어 보이는 일이 있음

- 3.5.1-beta 변경 사항 (2018-06-17)
  - 수정된 사항
    - 기능 추가: 영어, 일본어 번역이 제공됩니다! 이제 시스템 언어가 '영어' 또는 '일본어'인 기기에서는 각각 영어와 일본어로 어플리케이션 정보가 제공됩니다!
    - 기능 개선: '메인' 화면의 레이아웃이 개선되었습니다.
    - 기능 개선: '메인' 화면의 '학교 주변 대기상태' 란의 데이터 업데이트 매커니즘이 개선되었습니다.
    - 기능 개선: '인트로' 화면의 데이터 업데이트 매커니즘이 개선되었습니다.
    - 기능 개선: '메인' 화면의 속도가 향상되었습니다!
    - 버그 수정: '급식 정보' 화면을 오프라인에서 사용할 수 없던 버그를 수정하였습니다.
    - 버그 수정: '급식 정보' 화면에서 날짜를 바꾸었을 때 반응이 느리거나 아예 데이터를 불러올 수 없었던 버그를 수정하였습니다.
    - 버그 수정: '메인' 화면에서 업데이트 공명이 잘못 일어나 한 사람이 '학교 주변 대기상태'를 선택하면 다른 사람에게도 '학교 주변 대기상태'가 표시되는 버그를 수정하였습니다.
    - 기타 개선: 이제 어플리케이션과 소스 코드를 MIT 라이선스로 이용하실 수 있습니다.
    - 기타 개선: 급식 데이터가 2018년 5월부터 연도별/월별로 저장됩니다. 향후 급식 메뉴 빈도분석 등의 기능이 추가될 수 있습니다!
  - 알려진 버그
    - 데이터 업데이트 버튼을 누르면 학교 주변 대기상태의 트래픽이 과부하됨

- 3.5.0-beta 변경 사항 (2018-06-03)
  - 수정된 사항
    - 기능 추가: 이제 앱을 닫기 전에 '어플리케이션을 종료하시겠습니까?'하고 질문합니다!
    - 기능 추가: '설정' 화면이 생성되었습니다.
    - 기능 개선: '인트로' 화면에서 너무 오랜 시간 있던 것을 수정하였습니다.
    - 기능 개선: 이제 '학사일정' 화면이 구색을 갖추기 시작합니다.
    - 기능 개선: 이제 '메인' 화면의 '학교 주변 대기상태' 에서 각 상태별로 색깔이 다르게 적용됩니다.
  - 알려진 버그
    - '메인' 화면의 '학교 주변 대기상태'를 선택했을 때 가끔씩 강제 종료됨

- 3.4.2-beta 변경 사항 (2018-04-23)
  - 수정된 사항
    - 기능 개선: '메인' 화면의 '학교 주변 대기상태' 에서 대기질 정보를 좀 더 자세히 확인할 수 있습니다. 가독성 또한 개선하였습니다.
    - 버그 수정: 인터넷을 켠 채 앱을 실행하면 강제종료되는 오류를 해결하였습니다.
    - 기능 삭제: 실시간 시간표 기능이 작동하지 않습니다.
  * 알려진 버그
    - '메인' 화면에서 '오늘의 중식/석식'을 선택하였을 때 중식/석식 메뉴가 전부 표시되지 않을 수 있음

- 3.4.1-beta 변경 사항 (2018-04-16)
  - 수정된 사항
    - 기능 추가: "2014년 4월 16일, 잊지 않겠습니다." 이제 매년 4월 16일에 앱에 접속하면 앱의 메인 테마가 노란색이 되고, '메인' 화면의 교훈 칸에는 추모 문구가 달립니다. 4월 16일을 전후하여 사흘 동안 '메인' 화면에는 추모 테마가 적용됩니다. "잊지 않겠습니다."
    - 버그 수정: 급식 및 미세먼지 데이터를 받아올 때 데이터 헤더를 받아오지 못하던 오류를 해결하였습니다.

- 3.4.0-1-beta 변경 사항 (2018-04-16) * 긴급 업데이트
  - 수정된 사항
    - 버그 수정: 급식 관련 오류를 해결하였습니다.

- 3.4.0-beta 변경 사항 (2018-04-15)
  - 수정된 사항
    - 기능 개선: 인트로 화면을 개선했습니다. 이제 중복 데이터를 다운로드하지 않습니다.
    - 기능 개선: 이제 메인 화면에서 항목을 바꾸면 데이터가 바뀌어 보입니다. 스와이프 제스처를 넣는 게 죽을 맛이더군요.
    - 기능 추가: 오프라인 모드가 일부 적용되었습니다. 이제 '메인', '시간표' 화면에서 인터넷 연결이 없어도 이전에 다운로드한 데이터가 표시됩니다.
    - 기능 추가: '메인'화면에 '업데이트 공명'이 적용됩니다. 인터넷에 연결되어 있을 때, 다른 사용자가 데이터를 업데이트하면 나의 데이터도 자동으로 업데이트됩니다.
    - 기능 개선: 이제 '시간표' 화면에서 다시 시간표 업데이트 정보를 확인할 수 있습니다.
    - 기타 개선: 앱이 강제종료될 가능성을 아주 조금 낮추었습니다.

- 3.3.3-beta 변경 사항 (2018-04-09)
  - 수정된 사항
    - 기능 개선: 인트로 화면을 개선했습니다. * 꿀팁: 인터넷 접속을 끊은 채로 앱을 시작하면 인트로 화면에서 바로 메인 화면으로 넘어갑니다. 더 빠르게 켤 수 있겠죠?
    - 기능 추가: 통신 속도가 빠른 Firebase DB를 적용하였습니다. 아직 기능을 완전히 추가한 것은 아니지만, 앞으로 데이터 헤더를 분석해서 더 빠르고 효율적으로 데이터를 다운로드할 수 있도록 해서 여러분의(사실 저의) 모바일 데이터를 최대한 절약하도록 노력하겠습니다.
    - 기타 개선: 시간표 기능을 다시 사용할 수 있습니다. 아직도 느리지만 그래도 이제 다시 작동하니 다행입니다. 하지만 #6을 해결하지 못한 것은 너무 찜찜하군요.
  - 알려진 버그
    - 메인 화면에서 항목을 바꾸어도 데이터가 보이지 않음
    - 메인 화면에서 '학교 주변 대기상태' 항목을 한 번이라도 선택했을 경우 항목이 바뀌지 않음
    - 앱이 강제종료될 가능성 높음

- 3.3.2-beta 변경 사항 (2018-04-07)
  - 수정된 사항
    - 기능 추가: 이제 인트로 화면이 표시됩니다. 아직은 그냥 빈 화면입니다. 하지만 그 밑에서는 열심히 데이터를 다운로드하고 있습니다.
    - 기능 삭제: '시간표' 화면의 기능을 일시정지했습니다. (#6 참조)
    - 기타 개선: 현재 오프라인 모드의 시범 버전을 운영하기 시작했습니다. 기대해 주세요!
  - 알려진 버그
    - '시간표' 화면이 작동하지 않음 (#6)
    - '메인' 화면에서 '시간표' 이외의 다른 항목을 선택해도 내용이 표시되지 않음

- 3.3.1-beta 변경 사항 (2018-03-18)
  - 수정된 사항
    - 버그 수정: '시간표' 화면 관련 오류 수정 (#5의 일부) (임시: 재발 가능성 높음)
    - 기능 추가: '시간표' 화면에서 시간표 하단에 '표시된 기간', '마지막 업데이트(서버/사용자)'가 표시됩니다. '표시된 기간'에는 표시된 시간표가 적용되는 기간의 월요일부터 토요일 날짜가 표시되어 있습니다.
    - 기능 추가: '메인' 화면에서 '오늘의 중식/석식'을 선택하면 시간에 따라 데이터가 표시됩니다. 오후 2시 이전에는 중식 메뉴를, 이후에는 석식 메뉴를 표시합니다.
    - 기타 개선: '메인' 화면에 있는 버튼의 위치와 크기를 조정했습니다. 이제 더 잘 눌릴 거라구요!
  - 알려진 버그
    - '시간표' 화면에 들어가는 데 시간이 오래 걸림 (#5)

- 3.3.0-beta 변경 사항 (2018-03-17)
  - 수정된 사항
    - 버그 수정: 인터넷이 연결되어 있지 않을 때 '시간표' 화면에 접속할 수 없는 버그 수정(#4)
    - 기능 추가: 이제 '학사일정' 화면에 무언가가 생기기 시작했습니다. 시작은... 연합뉴스입니다. 인터넷만 연결되어 있으면 그날의 연합뉴스 누리집의 기사 제목들이 표시됩니다.
    - 기능 추가: '시간표' 화면에서 그 주 기준으로 변경된 시간표를 실시간 확인할 수 있습니다. 변경된 수업은 굵은 글씨로 표시됩니다.
    - 기능 개선: '급식 정보' 화면에서 '|<' 또는 '>|' 버튼을 누르면 변경되는 날짜가 한 달에서 한 주로 바뀌었습니다. 이제 버튼을 누르면 다음 주 급식이 나옵니다.
    - 기타 개선: '시간표' 화면에서 주로 1교시, 6교시, 7교시에 줄이 뒤틀리던 것을 수정했습니다. 이제 올곧게 볼 수 있습니다. 하지만 조금 느려진 것은 기분 탓입니다. 암암.
    - 기타 개선: 모든 화면에서 버튼의 디자인을 개선했습니다. 이제 더 미적인 버튼이 여러분을 맞이합니다! 하지만 아마 운이 나쁘면 롤리팝(안드로이드 5.0: API Level 21) 이상이 아닌 휴대폰에서는 안 예쁘게 나올 거예요... ㅠㅜ
  - 알려진 버그
    - '시간표' 화면에서 가끔씩 시간표를 받아오는 도중에 어플리케이션이 종료될 수 있습니다. (#5)
    - '시간표' 화면을 선택하고 나서 화면이 바뀔 때까지 시간이 더 걸립니다. (#5)
    - '시간표' 화면이 업데이트되지 않을 수도 있습니다. (#5)

- 3.2.5-beta 변경 사항 (2018-03-15)
  - 수정된 사항
    - 기능 추가: 이제 '학급 시간표' 화면에서 각 학급의 시간표를 확인할 수 있습니다. 인터넷이 연결되어 있을 때 학급 시간표 화면에 들어가면 처음에 최대 약 5초의 지연 후 시간표가 표시됩니다. 그 뒤의 지연은 없습니다.
    - 기능 개선: '학급 시간표' 화면에 들어가면 시간표에 뜨던 'mon 1' 등을 삭제했습니다.
    - 기능 개선: 이제 젤리빈(4.1.0: API Level 16) 이상 버전의 안드로이드 휴대전화에서 앱을 실행할 수 있습니다.
  - 알려진 버그
    - 인터넷이 연결되어 있지 않을 때 '시간표' 화면에 접속할 수 없음 (#4)

- 3.2.4-beta 변경 사항 (2018-03-10)
  - 수정된 사항
    - 버그 수정: 급식 정보 화면에서 '|<' 버튼을 누르면 강제 종료되는 버그 수정됨 (#3)
    - 버그 수정: 메인 화면의 '학교 주변 대기상태' 탭에서 학교 주변 데이터가 나오지 않고 다른 데이터가 나오는 버그 수정됨 (#2)
    - 버그 수정: 석식 정보가 없을 때 급식 정보 화면에 들어가면 강제 종료되는 버그 수정됨 (#1)
    - 버그 수정: 메인 화면에서 '<' 또는 '>' 버튼으로 '학교 주변 대기상태'를 선택하지 못하는 버그 수정됨
    - 개선 사항: 메인 화면의 '학교 주변 대기상태'에 표시되는 정보의 가독성을 개선하였습니다. 이제 측정 시간과 측정 위치를 확인할 수 있습니다.
    - 개선 사항: 급식 정보 화면의 가독성을 개선하였습니다. 이제 점심과 저녁을 따로 확인할 수 있으며, 알레르기 정보를 밑에서 확인할 수 있습니다.
    - 기능 추가: 이제 급식 정보 화면에서 날짜를 변경할 수 있습니다. 인터넷이 연결되어 있을 때 날짜를 변경하면 최대 5초 이내로 갱신됩니다.
    - 기능 추가: 이제 메인 화면이 아닌 곳에서도 탐색 창을 통해 다른 화면으로 이동할 수 있습니다.
    - 기능 추가: 이제 학사일정 화면에서도 탐색 창을 통해 어플리케이션 버전을 확인할 수 있습니다.

- 3.2.3-beta 변경 사항 (2018-03-10)
  - 수정된 사항
    - 급식 정보 화면에서 그날의 급식 정보를 받아옵니다. 아직 날짜를 바꿀 수 없지만 그날그날 볼 수 있는 게 어딥니까.
    - 메인 화면에서 선택할 수 있는 표시 내용 "학교 주변 대기상태"가 추가되었습니다. 항목을 선택하면 학교 주변의 대기상태를 받아옵니다.
  - 알려진 버그
    - 석식이 없는 날에 급식 정보 화면을 들어가면 강제 종료됨 (#1)
    - 학교 주변 대기상태의 내용이 실제 대기상태와 다름 (#2)
    - 급식 정보 화면에서 버튼을 누르면 강제 종료됨 (#3)

- 3.2.2-beta 변경 사항 (2018-03-04)
  - 수정된 사항
    - 시간표 화면 기능 구현을 시작하였습니다. 시간표 화면을 켜면 표에서 요일/교시 정보를 확인할 수 있습니다.
    - 급식정보 화면 기능 구현을 시작하였습니다. 현재 크롤링(인터넷 사이트에서 자동으로 데이터를 받아오는 것)을 테스트하는 중입니다. 크롤링 대상이 되는 사이트는 연합뉴스 누리집이며, 크롤링 대상이 되는 데이터는 뉴스의 헤드라인입니다.

- 3.2.1-beta 변경 사항 (2018-03-04)
  - 수정된 사항
    - 시간표 화면 틀이 완성되었습니다. 하지만 아직 작동하지는 않습니다.
    - 시간표 화면에서 버튼을 누르면 학년/반이 변경됩니다. 바깥쪽 버튼이 학년 변경, 안쪽 버튼이 반 변경입니다.
    - 디자인이 개선되었습니다.

- 3.2.0-beta 변경 사항 (2018-03-03)
  - 수정된 사항
    - 한국어가 적용되었습니다. 이제 시스템 언어가 영어로 설정되지 않았다면 한국어가 표시됩니다.
    - 메인 화면에서 좌/우측의 버튼을 누르면 카드 내용을 변경할 수 있습니다.
    - 사이드 메뉴에서 [어플리케이션 정보]를 선택할 시 어플리케이션 버전이 표시됩니다.

- 3.1.0-beta 변경 사항 (2018-02-26)
  - 수정된 사항
    - 탐색 창이 추가되었습니다. 이제 화면 좌측 상단의 버튼을 누르거나 화면을 왼쪽에서 스와이프하여 탐색 창을 사용할 수 있습니다.
    - 하드웨어 메뉴 버튼에 응답합니다. 이제 화면 우측 상단의 옵션 버튼을 누르거나 휴대전화의 메뉴 버튼을 눌러 설정 메뉴를 볼 수 있습니다.
    - Home 화면 레이아웃이 개선되었습니다.
    - Home 화면에서 중앙부의 스피너를 통해 카드 내용을 변경할 수 있습니다.

- 3.0.0.1a-beta 변경 사항 (2018-02-23)
  - 수정된 사항
    - 개발 도구를 MIT App Inventor에서 Android Studio로 변경
    - 패키지명을 appinventor.ai_jeongid2530.smart_class_system에서 kr.hs.gimpo.smartclass로 변경
    - 메인 메뉴에서 버튼을 눌러 표시할 데이터의 제목을 변경할 수 있음
    - 오른쪽 버튼을 누르다 보면 "Error(code:1001)"이라고 표시되는 버그를 수정

- 2.0 변경 사항 (2017-07-08)
  - 수정된 사항
    - 메인 화면의 레이아웃 변경

- 1.0.6 변경 사항 (2017-05-21)
  - 수정된 사항
    - 급식표 화면에 무의미한 선택 기능이 표시되는 오류 수정
    - 급식표 데이터를 받아오면 {Day=""}의 틀이 나타나는 오류 수정
    - 급식표 데이터에서 점심 부분만 초기화되는 오류 수정

- 1.0.5 변경 사항
  - 수정된 사항
    - 온라인 데이터를 받아오지 못하는 오류 수정
    - 급식표 데이터에서 점심과 저녁이 구별되지 않는 오류 수정

- 1.0.4 변경 사항
  - 수정된 사항
    - 시간표 화면에서 '불러오기' 버튼 삭제

- 1.0.3 변경 사항
  - 수정된 사항
    - 설정 화면에서 설정한 반만 학년이 바뀔 때 자동으로 데이터가 바뀌는 오류 수정

- 1.0.2 변경 사항
  - 수정된 사항
    - 시간표가 표시되지 않는 오류 수정

- 1.0.1 변경 사항
  - 수정된 사항
    - 급식 식단표에 접근할 수 없는 오류 수정

- 1.0.0 변경 사항 (2017-02-20)
  - 수정된 사항
    - 최초 릴리즈
