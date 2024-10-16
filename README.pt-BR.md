# Pipeline de Conformidade de Segurança

## Objetivo do Projeto

Este projeto visa garantir que todo código enviado para o repositório passe por verificações de segurança automatizadas, incluindo análise estática de código, verificação de vulnerabilidades de dependências e auditoria de segurança de containers.

## Funcionalidades

- Análise estática de código com SonarQube.
- Verificação de vulnerabilidades em dependências com OWASP Dependency-Check.
- Auditoria de segurança de containers com Trivy.
- Geração de relatórios de conformidade.

## Ferramentas Utilizadas

- [SonarQube](https://www.sonarqube.org/): Para análise estática de código.
- [OWASP Dependency-Check](https://owasp.org/www/tools/OWASP_Dependency_Check/): Para verificação de vulnerabilidades em dependências.
- [Trivy](https://github.com/aquasecurity/trivy): Para auditoria de segurança de containers.
- [GitHub Actions](https://github.com/features/actions): Para automação do pipeline.

## Pré-requisitos

Antes de começar, verifique se você tem os seguintes itens instalados:

- Docker
- Java (para SonarQube)
- Node.js 

## Instalação

Clone este repositório:

```bash
git clone https://github.com/SeuUsuario/security-compliance-pipeline.git
cd security-compliance-pipeline
```

## Contribuição
Se você deseja contribuir com este projeto, fique à vontade para abrir um pull request ou criar uma issue.