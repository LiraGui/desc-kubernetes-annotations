# Descomplicando Kubernetes - Repositório de Estudos

Este repositório contém materiais de estudo baseados no curso **"Descomplicando Kubernetes"** da [Linux Tips](https://linuxtips.io/), ministrado pelo Jeferson Fernando.

## 📚 Sobre o Curso

O "Descomplicando Kubernetes" é um curso completo que aborda desde conceitos básicos até tópicos avançados do Kubernetes, uma das principais plataformas de orquestração de containers do mercado.

## 🗂️ Estrutura do Repositório

O repositório está organizado por dias de estudo, cada um focando em diferentes aspectos do Kubernetes:

### Day 1 - Primeiros Passos
- **`nginx-pod-yml`**: Exemplo básico de Pod com nginx
- **`kind/`**: Configurações para ambiente Kind (Kubernetes in Docker)

### Day 2 - Pods
- **`pod.yaml`**: Definições e configurações de Pods

### Day 3 - Deployments
- **`deployment.yaml`**: Configurações de Deployment

### Day 4 - Probes e DaemonSets
- **`deployment-challenge.yaml`**: Desafio prático com Deployments
- **`deployment-liveness-probe.yaml`**: Configuração de Liveness Probe
- **`deployment-readiness-probe.yaml`**: Configuração de Readiness Probe
- **`node-exporter-daemonset.yaml`**: Exemplo de DaemonSet com Node Exporter

### Day 6 - Storage
- **`persistent-volume.yaml`**: Configuração de Persistent Volume
- **`storageclass.yaml`**: Definição de Storage Class

## 🎯 Objetivos de Aprendizado

- Compreender os conceitos fundamentais do Kubernetes
- Praticar a criação e gerenciamento de recursos Kubernetes
- Implementar probes para monitoramento de aplicações
- Configurar storage persistente
- Trabalhar com DaemonSets e outras cargas de trabalho

## 🚀 Como Usar

1. Clone este repositório
2. Navegue pelos diretórios organizados por dia
3. Estude os arquivos YAML e suas configurações
4. Aplique os manifests em um cluster Kubernetes para prática

```bash
# Exemplo de aplicação de um manifest
kubectl apply -f day-1/nginx-pod-yml
```

## 📖 Recursos Adicionais

- [Documentação Oficial do Kubernetes](https://kubernetes.io/docs/)
- [Linux Tips](https://linuxtips.io/)
- [Canal da Linux Tips no YouTube](https://www.youtube.com/linuxtips)

## 🤝 Contribuições

Este é um repositório de estudos pessoais. Sinta-se à vontade para fazer fork e adaptar para seus próprios estudos.

---

**Nota**: Este repositório é destinado exclusivamente para fins educacionais e de estudo, baseado no conteúdo do curso "Descomplicando Kubernetes" da Linux Tips.