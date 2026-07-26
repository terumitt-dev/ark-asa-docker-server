# ark-asa-docker-server

ARK: Survival Ascended の個人サーバーを構築・運用するためのリポジトリ。

## 概要

- ゲーム: ARK: Survival Ascended
- 用途: 個人/プライベートサーバー
- 目標構成: Kubernetes 上でサーバーコンテナを運用

## 現状

作業中。CI/CD 基盤（Drone CI + drone-runner-kube）は整備済み。

## 技術スタック

| カテゴリ | 技術 |
|---|---|
| CI/CD | Drone CI（drone-runner-kube） |
| イメージレジストリ | AWS ECR |
| デプロイ先（予定） | Kubernetes |
