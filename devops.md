# ⚙️ Infraestrutura & DevOps Stack

Ferramentas modernas para desenvolvimento, testes, deploy e monitoramento de aplicações em ambientes automatizados, escaláveis e portáveis.

---

## 🐳 Containerização
- [Docker](https://www.docker.com/) – Padrão de containerização para aplicações isoladas e portáveis
- [Docker Compose](https://docs.docker.com/compose/) – Orquestração de multi-containers localmente
- [Podman](https://podman.io/) – Alternativa rootless ao Docker, compatível com CLI

---

## 🚀 Plataformas de Deploy Automático
- [Coolify](https://coolify.io/) – Plataforma self-hosted estilo Vercel/Render com suporte a Docker e Git
- [Railway](https://railway.app/) – Deploy de backend instantâneo com integrações Git e PostgreSQL
- [Render](https://render.com/) – Alternativa a Heroku com CI/CD embutido e suporte a Web Services
- [Fly.io](https://fly.io/) – Deploy global de containers com foco em latência
- [CapRover](https://caprover.com/) – PaaS autogerenciado com suporte a Docker + UI
- [Portainer](https://www.portainer.io/) – UI para gerenciar containers Docker e Swarm
- [Dokku](https://dokku.com/) – PaaS auto-hospedado baseado em Git push (estilo Heroku)

---

## 📦 Orquestração & Escalabilidade
- [Kubernetes (K8s)](https://kubernetes.io/) – Orquestração de containers em larga escala
- [Minikube](https://minikube.sigs.k8s.io/docs/) – Execução local de clusters Kubernetes
- [Helm](https://helm.sh/) – Gerenciador de pacotes para Kubernetes

---

## ⚙️ Integração Contínua / CI
- [GitHub Actions](https://github.com/features/actions) – CI/CD direto no GitHub com YAML pipelines
- [GitLab CI/CD](https://docs.gitlab.com/ee/ci/) – Pipeline poderosa e nativa do GitLab
- [CircleCI](https://circleci.com/) – CI em nuvem com foco em performance
- [Drone CI](https://www.drone.io/) – CI/CD self-hosted leve e com Docker-first mindset

---

## 🔐 Gerenciamento de Secrets & Variáveis
- [Doppler](https://www.doppler.com/) – Gerenciador de variáveis de ambiente moderno
- [Infisical](https://infisical.com/) – Secrets Manager open-source
- [Vault by HashiCorp](https://www.vaultproject.io/) – Gerenciador avançado de segredos e políticas

---

## 📊 Monitoramento & Logging
- [Grafana](https://grafana.com/) – Visualização de métricas e dashboards
- [Prometheus](https://prometheus.io/) – Coleta de métricas em tempo real (usado com Grafana)
- [Loki](https://grafana.com/oss/loki/) – Logging eficiente, complemento do Prometheus
- [ELK Stack (Elasticsearch + Logstash + Kibana)](https://www.elastic.co/what-is/elk-stack) – Coleta, armazenamento e visualização de logs
- [Wazuh](https://wazuh.com/) – SIEM open-source para segurança e compliance

---

## 🔐 Proxy Reverso & HTTPS
- [NGINX](https://nginx.org/) – Servidor HTTP, proxy reverso e balanceador de carga
- [Caddy](https://caddyserver.com/) – Servidor web com HTTPS automático e configuração simples
- [Traefik](https://traefik.io/) – Proxy reverso moderno com suporte nativo a Docker e K8s

---

## 💡 Extras úteis
- [ngrok](https://ngrok.com/) – Túnel para expor servidores locais via HTTPS
- [tunnelto](https://tunnelto.dev/) – Alternativa open-source ao ngrok
- [GlitchTip](https://glitchtip.com/) – Monitoramento de erros alternativo ao Sentry
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) – Monitoramento de status com UI moderna

---

## ✅ Stack Completa Exemplo
> Coolify + Docker + PostgreSQL + Redis + GitHub Actions + Grafana + Prometheus + Caddy = deploy autônomo e monitorado 100% em código.
