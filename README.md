# 🚀 Projeto DevOps Cloud: Implementação de Repositórios Git com AWS CodeCommit

## 📌 Introdução  
A jornada para a nuvem não envolve apenas migração de sistemas, mas também modernização de práticas de desenvolvimento e operações. Neste projeto, inspirado em um **cenário real de SaaS (Software as a Service)**, implementei uma prova de conceito (PoC) utilizando **AWS CodeCommit** para armazenamento e versionamento de códigos de **aplicação** e **infraestrutura**.  

O objetivo foi validar os processos de **commit, push e revert** em um ambiente que integra desenvolvedores e engenheiros DevOps, garantindo rastreabilidade, governança e escalabilidade.  

---

## ☁️ Provedor Cloud e Tecnologias Utilizadas  

**Provedor Cloud:**  
- AWS (Amazon Web Services)  

**Serviços e Tecnologias:**  
- AWS CodeCommit  
- GitHub  
- Git  
- Kubernetes  
- Docker  
- Terraform  
- Ansible  

---

## 🏗️ Arquitetura da Solução  

A solução foi estruturada em dois repositórios distintos dentro do **AWS CodeCommit**:  
- **human-gov-application** → armazenamento do código da aplicação (Python).  
- **human-gov-infrastructure** → armazenamento da infraestrutura (Kubernetes, Terraform, Docker, Ansible).  

Esse desenho permitiu separar responsabilidades, garantindo governança e clareza entre times de **desenvolvimento** e **engenharia DevOps**.  

📊 **Fluxo implementado:**  
1. Desenvolvedor realiza **commit** da mudança.  
2. Alteração é enviada para o repositório via **push**.  
3. Caso necessário, a mudança pode ser revertida (**revert**).  
4. O histórico fica versionado e rastreável, permitindo colaboração segura.  

![Arquitetura da Solução](<coloque_aqui_o_link_da_imagem>)  

---

## ⚙️ Práticas DevOps Aplicadas  

- **Integração entre Dev e Ops:** separação clara de aplicação e infraestrutura.  
- **Versionamento padronizado:** rastreabilidade de todas as alterações.  
- **Rollback seguro:** possibilidade de desfazer mudanças de forma ágil.  
- **Base para CI/CD:** repositórios estruturados para evolução futura com pipelines.  

---

## ✅ Resultados da Prova de Conceito  

- Validação de processos críticos do Git (**commit, push e revert**) em ambiente corporativo.  
- Maior segurança no versionamento de aplicações SaaS.  
- Criação de um modelo replicável para **migração de monólitos para microsserviços**.  
- Base sólida para práticas de **IAC (Infraestrutura como Código)** com Terraform e Ansible.  

---

## 🔮 Próximos Passos  

Como evolução deste projeto, destaco possíveis melhorias:  
- Integração com **AWS CodePipeline e CodeBuild** para automação de deploy.  
- Observabilidade com **CloudWatch** e **AWS X-Ray**.  
- Práticas de **FinOps** para monitorar custos em tempo real.  
- Integração com ferramentas de qualidade de código e testes automatizados.  

---

## 💡 Conclusão  

Esse projeto demonstra como uma arquitetura simples, porém bem planejada, pode servir como base para **colaboração entre times, escalabilidade e automação de processos**.  

Mais do que uma PoC, foi um exercício prático de **engenharia DevOps em nuvem**, combinando versionamento, infraestrutura como código e governança.  

---

✍️ *Publicado por Arlindo Ramos — Arquiteto de Infraestrutura de TI & Cloud*  
