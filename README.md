# phis_fhir_introp_agent

PHIS 표준화 실증  Agent(리소스 로딩)

## 2023 의료 표준화 실증 Resource Loader Agent

### 지원 OS

- 윈도우용 (phis_nofhir-win_amd64.exe)
- x86 Linux용(phis_nofhir-linux_amd64)
- Mac OS용(phis_nofhir-darwin_arm64)

### 실행 방법 (linux)
___config 설정___
```
권한 변경(linux, mac용의 경우)
chmod 755 phis_nofhir-linux_amd64
./phis_nofhir-linux_amd64
```

### 실행 방법(Windows)
- config 설정
- 실행

```
phis_nofhir-win_amd64.exe
```

### 연동 테스트
curl --location 'http://localhost:9091/loader/11100338/$loadInstRes
(현재는 error 반환됨, 반응만 확인 가능)
