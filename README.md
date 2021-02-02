# Pod GPU Infra

Kubernetes에서 NVIDIA GPU를 Pod의 자원으로 사용하기 위해 제공되는 가이드입니다.

## NVIDIA Device Plugin

Kubernetes에서 NVIDIA GPU를 인식하고 자원으로 사용하기 위해 설치해야하는 Device Plugin입니다.

- 설치 가이드: [./nvidia-device-plugin/README.md](./nvidia-device-plugin/README.md)

## NVIDIA Pod GPU Metrics Exporter

NVIDIA GPU를 Prometheus를 사용하여 monitoring하기 위해 배포해야하는 exporter입니다.

- 설치 가이드: [./nvidia-pod-gpu-metrics-exporter/README.md](./nvidia-pod-gpu-metrics-exporter/README.md)