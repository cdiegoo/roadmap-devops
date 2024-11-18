# Roadmap

## O que é DevOps?

Para entender melhor o que é DevOps, recomendo este artigo da Red Hat:  
[O que é DevOps? - Red Hat](https://www.redhat.com/pt-br/topics/devops)

---

## Indicação de Livros

Se você gosta de livros, aqui estão algumas recomendações valiosas:

- **Manual de DevOps: Como obter agilidade, confiabilidade e segurança em organizações tecnológicas**  
  [Comprar na Amazon](https://www.amazon.com.br/Manual-DevOps-confiabilidade-organiza%C3%A7%C3%B5es-tecnol%C3%B3gicas/dp/8550802697)

- **O Projeto Fênix: Um romance sobre TI, DevOps e sobre ajudar o seu negócio a vencer**  
  [Comprar na Amazon](https://www.amazon.com.br/projeto-f%C3%AAnix-Gene-Kim/dp/8550801895)

- **Engenharia de Confiabilidade do Google**  
  [Visualizar no Google Livros](https://books.google.com.br/books/about/Engenharia_de_Confiabilidade_do_Google.html?id=dGrgDAAAQBAJ&printsec=frontcover#v=onepage&q&f=false)

- **Effective DevOps: Building a Culture of Collaboration, Affinity, and Tooling at Scale**  
  [Comprar na Amazon](https://www.amazon.com/Effective-DevOps-Building-Collaboration-Affinity/dp/1491926309)

---

## Vídeos do YouTube

### O que é DevOps
- [O que é DevOps? - Vídeo 1](https://www.youtube.com/watch?v=iwf6kcvxeD4&pp=ygUPbyBxdWUgw6kgZGV2b3Bz)  
- [O que é DevOps? - Vídeo 2](https://www.youtube.com/watch?v=bwO8EZf0gLI&pp=ygUPbyBxdWUgw6kgZGV2b3Bz)

### O que é CI/CD?
- [Introdução ao CI/CD - Vídeo 1](https://www.youtube.com/watch?v=AZtTd3pFVTY&pp=ygUObyBxdWUgw6kgY2kvY2Q%3D)  
- [Introdução ao CI/CD - Vídeo 2](https://www.youtube.com/watch?v=nI3IjYcBGiU&pp=ygUObyBxdWUgw6kgY2kvY2Q%3D)  
- [Introdução ao CI/CD - Vídeo 3](https://www.youtube.com/watch?v=QGcuXYztFSA&pp=ygUObyBxdWUgw6kgY2kvY2Q%3D)

### O que são contêineres?
- [O que são contêineres? - Vídeo 1](https://www.youtube.com/watch?v=85k8se4Zo70&pp=ygUVbyBxdWUgc8OjbyBjb250ZWluZXJz)  
- [O que são contêineres? - Vídeo 2](https://www.youtube.com/watch?v=-pUZBovqRcU&pp=ygUVbyBxdWUgc8OjbyBjb250ZWluZXJz)

### Curso AWS
- [Curso AWS Completo](https://www.youtube.com/watch?v=HiBCv9DolxI&list=PLtL97Owd1gkQ0dfqGW8OtJ-155Gs67Ecz)

### Curso Azure
- [Curso Azure Fundamentos](https://www.youtube.com/watch?v=4ub1uGKQK6U&pp=ygUYYXp1cmUgZnVuZGFtZW50YWxzIGN1cnNv)

---

## Roadmap Indicado para Sandy & Júnior

Após entender o que é DevOps, além de aprender mais sobre Cloud, plataformas e SRE, recomendo seguir este plano de estudos:

- **Git**

- **CI/CD**
  - GitHub Actions  
  - Jenkins  
  > Escolha um para começar. Existem outros, como GitLab e Harness, mas esses dois são mais acessíveis para iniciantes, já que não precisam de licenciamento.

- **Infraestrutura como Código (IaC)**  
  - Terraform

- **Linux**

- **Docker**

- **Kubernetes**

- **Scripting**  
  - Python  
  - Go  
  - PowerShell  
  - Bash  

---

## Sugestão de Projeto para Praticar DevOps

### Descrição
Crie um pipeline CI/CD completo para uma aplicação web simples (ex.: um aplicativo de lista de tarefas).

### Ferramentas e Tecnologias
1. **GitHub/GitLab**: Para versionamento do código.  
2. **GitHub Actions/Jenkins**: Para configuração do pipeline CI/CD.  
3. **Docker**: Para criar e gerenciar contêineres da aplicação.  
4. **Kubernetes**: Para orquestrar os contêineres.  
5. **Terraform**: Para provisionar a infraestrutura necessária (ex.: clusters Kubernetes na nuvem).  
6. **AWS/Azure/Google Cloud**: Para hospedar a aplicação.  
7. **Python/Bash**: Para automação de scripts.  

### Passos
1. Desenvolva uma aplicação web básica (ou utilize uma existente).  
2. Configure um repositório Git e crie branches para desenvolvimento e produção.  
3. Configure um pipeline CI/CD que:
   - Execute testes automatizados em cada push.
   - Gere imagens Docker da aplicação.  
   - Faça deploy em um ambiente Kubernetes usando Helm Charts.  
4. Use o Terraform para provisionar um cluster Kubernetes em uma nuvem pública.  
5. Configure o monitoramento básico da aplicação com ferramentas como **Prometheus** e **Grafana**.  
6. Documente o projeto e apresente as etapas em um README.md no repositório.

---

## Considerações

Este roadmap cobre o básico para um profissional júnior começar a se candidatar a vagas.  

Um profissional focado em DevOps não precisa, necessariamente, saber desenvolver sistemas, mas, caso saiba, será um enorme diferencial. Isso pode destacá-lo no mercado, embora não seja obrigatório.

Se tiver dúvidas, entre em contato para conversarmos! :)  

**Bons estudos!**  
*Em breve trarei conteúdos proprietários.*
