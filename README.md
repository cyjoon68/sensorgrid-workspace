# SensorGrid Workspace

SensorGrid는 제조 설비 센서 데이터, 이상 규칙, 시계열 query lab을 보여주는 서비스 프로젝트입니다.

## 저장소 구조

```text
sensorgrid-workspace/
  sensorgrid-fe/  # Next.js 센서 운영 대시보드
  sensorgrid-be/  # Flask MVC + SQLAlchemy async REST API
```

FE/BE는 Git submodule로 연결되어 있습니다.

## 프로젝트 링크

- FE: https://github.com/sensorgrid-labs/sensorgrid-fe
- BE: https://github.com/sensorgrid-labs/sensorgrid-be
- Personal mirror: https://github.com/cyjoon68/sensorgrid-workspace

## 실행

```bash
git clone --recurse-submodules https://github.com/sensorgrid-labs/sensorgrid-workspace.git
```

## 프로젝트 포인트

설비/센서/메트릭/이상 규칙 도메인을 실제 서비스형 FE/BE repo와 workspace submodule 구조로 구성했습니다.
