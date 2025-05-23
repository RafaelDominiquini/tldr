# chpass

> 사용자 데이터베이스 정보, 로그인 셸 및 비밀번호를 추가하거나 변경합니다.
> 같이 보기: `passwd`.
> 더 많은 정보: <https://man.netbsd.org/chpass>.

- 현재 사용자에게 특정 로그인 셸을 대화식으로 설정:

`su -c chpass`

- 현재 사용자에게 특정 로그인 셸 설정:

`chpass -s {{경로/대상/셸}}`

- 특정 사용자에게 로그인 셸 설정:

`chpass -s {{경로/대상/셸}} {{사용자명}}`

- `passwd` 파일 형식으로 사용자 데이터베이스 항목 지정:

`su -c 'chpass -a {{사용자명:암호화된_비밀번호:uid:gid:...}} -s {{경로/대상/파일}}' {{사용자명}}`

- 로컬 비밀번호 파일만 업데이트:

`su -c 'chpass -l -s {{경로/대상/셸}}' {{사용자명}}`

- 데이터베이스 [y]P 비밀번호 데이터베이스 항목을 강제로 변경:

`su -c 'chpass -y -s {{경로/대상/셸}}' {{사용자명}}`
