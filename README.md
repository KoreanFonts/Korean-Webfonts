# Korean-Webfonts

소개
========

환영합니다!! 여긴 공개된 한국어 폰트들을 웹폰트화 시켜서 집대성하는 프로젝트의 공식 Repo입니다. 추후 안정화시 [jsdelivr](http://www.jsdelivr.com)에 동기화됩니다.

기존의 연습겸으로 만들어서 걸레가 되었던 repo는 제거하였으며, 앞으로는 커밋 삭제 없이 신중하게 커밋을 수행하는, 공식 채널로 관리하고자 새 Repo로 아예 리셋하였으니, 이전 repo에 watch, favorite 해주신 분들께 죄송하단 말씀을 드립니다.


폰트 종류 정보 안내
========

일단 기본적으로 woff, woff2 포맷만 탑재합니다.


CDN 경로 정보
========

CDN의 기본 경로는 //cdn.jsdelivr.net/korean-webfonts/latest/ 이하의 상대 경로는 https://github.com/jsdelivr/jsdelivr/tree/master/files/korean-webfonts/1 에 맞추시면 됩니다. 이 주소는 추후 업데이트가 이뤄지면서 변경될 수 있습니다.

현재 작동하는 예) https://cdn.jsdelivr.net/korean-webfonts/latest/orgs/othrs/kpa/BareunBatang/BareunBatangOTFB.woff2


목표
========

본 프로젝트의 목표는 [Google Fonts](http://www.google.com/fonts) 의 한국어버전을 만드는 것입니다. CSS Import API를 구글 폰트의 방식을 따와 비슷하게 추후에 제공할 예정입니다.

jsdelivr가 전세계 대상의 CDN이므로 잦은 업데이트를 부담스러워하여 프로젝트를 장기화하여 모을 수 있는 만큼 최대한 모아서 1분기당 폰트들의 추가/업데이트를 할 생각입니다. 첫 업데이트는 5월 마지막날로 예정되어 있습니다.

저는 타이포그래피 전문가가 아닙니다. 타입 디자이너 등 전문가분들이 보실 때 문제가 있다고 생각하신다면 언제든지 Issues에 신고/지적을 해주시면 정말 감사하겠습니다.

**여기에서 제공되는 무료 웹폰트에 대한 최종 라이센스는 개인을 기준으로 허용여부를 판단해 업로드하였습니다. 법인 및 기타 단체의 경우에는 반드시 _탑재 이전_에 해당 Foundry에 명확한 라이센스 가능 여부를 검토하셔야 합니다.**

본 프로젝트는 계속 비영리로 운영됩니다. 다만 차후에 CSS API 서버 운영을 결정하게 될 경우, 서버 운영비 충당을 위한 제한적인 웹 홈페이지 광고가 탑재될 수 있으나 API 자체에 직접적으로 광고를 삽입하진 않습니다.

그 밖에 참고 사항
========

* 오래된 이전 버전의 브라우저에서 웹폰트 힌팅이 으그러지는 경우 https://gist.github.com/letorbi/5177771 아이디어를 추가해보세요~
