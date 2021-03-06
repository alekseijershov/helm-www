---
title: "Helm Plugin Install"
---

## helm plugin install

하나 이상의 헬름 플러그인을 설치한다.

### Synopsis


이 명령을 사용하면 URL에서 VCS 저장소 또는 로컬 경로로 플러그인을 설치할 수 있다.


```
helm plugin install [options] <path|url>... [flags]
```

### 옵션

```
  -h, --help             helm plugin install 명령어의 도움말
      --version string   버전을 강제로 지정. 지정하지 않으면 최신 버전을 설치
```

### 부모 명령어로부터 상속된 옵션

```
      --debug                       자세한 출력 활성화
      --kube-apiserver string       쿠버네티스 API 서버의 주소 및 포트
      --kube-as-group stringArray   작업을 가장(impersonate)하기 위한 그룹. 이 플래그를 반복하여 여러 그룹을 지정 가능
      --kube-as-user string         작업을 가장할 사용자 이름
      --kube-context string         사용할 kubeconfig 컨텍스트 이름
      --kube-token string           인증에 사용할 전달자(bearer) 토큰
      --kubeconfig string           kubeconfig 파일 경로
  -n, --namespace string            이 요청의 네임스페이스 범위
      --registry-config string      레지스트리 구성 파일에 대한 경로 (기본값 "~/.config/helm/registry.json")
      --repository-cache string     캐시된 저장소 색인을 포함하는 파일 경로 (기본값 "~/.cache/helm/repository")
      --repository-config string    저장소 이름 및 URL 이 포함된 파일 경로(기본값 "~/.config/helm/repositories.yaml")
```

### 함께 보기

* [helm plugin](helm_plugin.md)	 - 헬름 플러그인 설치, 나열, 제거

###### Auto generated by spf13/cobra on 29-Oct-2020
