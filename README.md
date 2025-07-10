># Projeto GitOps na Prática - PB Compass UOL - ABR 2025 | DevSecOps

## 📝 Descrição do Projeto

Projeto prático de GitOps na trilha de Kubernetes, desenvolvido como parte do Programa de Bolsas da Compass UOL – Abril de 2025 | DevSecOps.

A aplicação Online Boutique foi implantada localmente em um cluster Kubernetes (via Rancher Desktop com WSL2 Ubuntu), utilizando o ArgoCD como ferramenta GitOps para realizar o deploy automatizado da aplicação. O ArgoCD é responsável por sincronizar o estado desejado da aplicação, definido nos manifests YAML versionados no GitHub, com o cluster Kubernetes em tempo real.

---

## 🛠️ Tecnologias Utilizadas

![Rancher Desktop](https://img.shields.io/badge/Rancher%20Desktop-0075A8?style=for-the-badge&logo=rancher)
![WSL2 Ubuntu](https://img.shields.io/badge/WSL2-Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes)
![ArgoCD](https://img.shields.io/badge/ArgoCD-F08705?style=for-the-badge&logo=argo)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode)

---

## 🔽 Sumário


- [Pré-requisitos](#-pré-requisitos)
- [Etapa 1 – Repositório GitHub](#-etapa-1--repositório-github)
- [Etapa 2 – Instalação do ArgoCD no cluster local](#-etapa-2--instalação-do-argocd-no-cluster-local)
- [Etapa 3 – Acessar o ArgoCD localmente](#-etapa-3--acessar-o-argocd-localmente)
- [Etapa 4 – Criar o App no ArgoCD](#-etapa-4--criar-o-app-no-argocd)
- [Etapa 5 – Acessar o frontend da aplicação](#-etapa-5--acessar-o-frontend-da-aplicação)
- [Etapa Extra – Customização do Manifest](#-etapa-extra--customização-do-manifest)
- [Desenvolvido por:](#-desenvolvido-por)

---

## ➤ Pré-requisitos

- Rancher Desktop instalado e configurado (com Kubernetes habilitado);
- WSL2 com Ubuntu instalado e integrado ao Rancher Desktop;
- Git instalado e configurado localmente;
- GitHub com repositório público criado;
- VS Code (ou outro editor) para edição do arquivo YAML;
- Kubectl instalado e configurado;
- ArgoCD instalado no cluster Kubernetes local.

---

## ➤ Etapa 1 – Repositório GitHub

Foi criado um repositório público no GitHub contendo apenas o arquivo de manifest da aplicação Online Boutique.

O conteúdo foi obtido diretamente do arquivo `kubernetes-manifests.yaml`, disponível no repositório oficial da Google:  
🔗 [https://github.com/GoogleCloudPlatform/microservices-demo/blob/main/release/kubernetes-manifests.yaml](https://github.com/GoogleCloudPlatform/microservices-demo/blob/main/release/kubernetes-manifests.yaml)

Esse conteúdo foi copiado e salvo localmente como `online-boutique.yaml`, dentro do diretório `k8s`, e posteriormente enviado ao repositório `gitops-microservices`.

---

## ➤ Etapa 2 – Instalação do ArgoCD no cluster local

---

## ➤ Etapa 3 – Acessar o ArgoCD localmente

---

## ➤ Etapa 4 – Criar o App no ArgoCD

---

## ➤ Etapa 5 – Acessar o frontend da aplicação

---

## ➤ Etapa Extra – Customização do Manifest

---

# 👩‍💻 Desenvolvido por:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/MarcelaLinhares">
        <img src="https://avatars.githubusercontent.com/u/141354578?v=4" width="80px;" alt="Foto de perfil GitHub da Marcela Linhares"/><br />
        <sub><b>Marcela Linhares</b></sub>
      </a>
    </td>
  </tr>
</table>

---