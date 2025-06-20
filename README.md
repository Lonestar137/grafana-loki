# Minikube

## Install

```bash
helm upgrade --install loki grafana/loki-stack -f values.yaml
kubectl apply -f log-gen.yaml
```

## Port forward

```bash
kubectl port-forward svc/loki-grafana 3000:80
```

## Aider

[Aider leaderboards](https://aider.chat/docs/leaderboards/)

```
aider --model gemini/gemini-2.5-pro-preview-06-05	 
```
