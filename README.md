# Korean Keyboard3
한국어 키보드 레이아웃을 유니코드 LDML Keyboard3 표준으로 구현해 정리하는 프로젝트입니다.

## About LDML Keyboard3
기존에는 다국어 입력 등 로케일을 위한 일관된 표준 체계가 없었으며, 제조사 및 환경별로 고유한 방식으로 키보드 레이아웃을 구현했습니다.

이에 유니코드에서 플랫폼에 종속되지 않는, 일관된 로케일 기반을 구축하기 위해서 LDML(로케일 데이터 마크업 언어)를 정의했습니다. 그 중 하나로 키보드 레이아웃을 일관되게 정의하는 Keyboard 3.0 사양을 공개하고 있습니다.

본 프로젝트에서는 해당 사양을 바탕으로 모든 한국어 자판 레이아웃을 구현하여, 컴퓨터 체계와 상관없이 일관된 한국어 입력 환경을 공개적으로 제공하고자 합니다.

## List
```
Work In Process!
```

## Contributing
자유로운 기여를 환영합니다!
  * 이슈 트래커에서 레이아웃 문제를 신고하거나, 프로젝트에 대해 자유롭게 제안할 수 있습니다.
  * 신규 레이아웃 / 레이아웃 수정 관련 풀 리퀘스트를 제출할 수 있습니다.

## Thanks to
  * [k3lp](https://codeberg.org/k3lp/k3lp) 
    * 본 프로젝트 파일들의 유효성 검증을 위해 쓴 파서 및 렌더링 엔진인 [justcontributor/k3lp](https://codeberg.org/justcontributor/k3lp)의 원본 코드베이스입니다.
    * 관련 프로젝트인 [FlorisBoard](https://github.com/florisboard/florisboard)는 Android에 Keyboard 3.0 기반으로 레이아웃을 정의할 수 있는 키보드를 만드려 합니다. (2026-07-15 기준) 아직 미완성이지만 주목해볼 만합니다.

## Reference
  * [Unicode LDML Part 7: Keyboards](https://unicode.org/reports/tr35/tr35-keyboards.html)
    * 국제적 표준인 Unicode에서 정의한 LDML 키보드 스펙 시트입니다.
  * [CLDR](https://cldr.unicode.org/)
    * Unicode에서 진행하는 상위 프로젝트입니다.
  * 나무위키 [두벌식](https://namu.wiki/w/두벌식/자판%20종류), [세벌식](https://namu.wiki/w/세벌식/자판%20종류), [휴대전화 입력기](https://namu.wiki/w/휴대전화%20입력기) 문서
    * 입력기 목록을 참고할 때 활용했습니다.
  * [Keyman](https://keyman.com/)
    * 비슷한 공개 레이아웃 및 자판 프로그램입니다.

## Disclaimer
  * 모종의 이유로 자판 레이아웃에 대한 독점적 권리를 주장하고 싶으신 경우, 이슈 트래커에 문의해 주세요. 프로젝트에서 제외하는 등의 조치를 진행할 수 있습니다.
  * 본 프로젝트에는 상용 키보드 레이아웃을 재구현한 Keyboard 3 파일이 포함되어 있습니다. 사용 시 발생할 수 있는 잠재적인 문제에 대해서는 [LICENSE.md](https://github.com/justcontributor/Korean-Keyboard3/LICENSE.md)를 참고해주시기 바랍니다.
