# ODROID_C4_navigation_bar
Outsourcing

① 상태바(시계줄 및 알림 바) 숨기기
adb shellsetting put global policy_control immersive.status=*

② 내비게이션 바 (하단 홈키) 숨기기
adb shellsetting put global policy_control immersive.navigation=*

③ 둘다 (상태바, 내비게이션 바) 숨기기
adb shellsetting put global policy_control immersive.full=*

④ 다시 원상태로 돌리기
adb shellsetting put global policy_control null*



source : https://himadesign.tistory.com/entry/ADB를-이용한-상단-및-하단-바-숨기기 [himadesign]
