# 👋🏻 Leonardo de Moura Fuseti

Estudante de Defesa Cibernetica no Polo Estacio Piumhi MG . Formação tecnica em Tecnico em Redes de Computadores no IFMG Bambui MG , intusiasta na programação gostando muito de Python e evoluindo dia a dia .

### Conecte-se comigo

[![Perfil DIO](https://img.shields.io/badge/-Meu%20Perfil%20na%20DIO-30A3DC?style=for-the-badge)](https://www.dio.me/users/mourafuseti)
[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=microsoft-outlook&logoColor=E94D5F)](mailto:mourafuseti@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=30A3DC)](https://www.linkedin.com/in/leonardo-moura-fuseti-4052b0359/)

### Habilidades

![HTML](https://img.shields.io/badge/HTML-000?style=for-the-badge&logo=html5&logoColor=30A3DC)
![CSS3](https://img.shields.io/badge/CSS3-000?style=for-the-badge&logo=css3&logoColor=E94D5F)
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript&logoColor=F0DB4F)
![Sass](https://img.shields.io/badge/SASS-000?style=for-the-badge&logo=sass&logoColor=CD6799)
![Bootstrap](https://img.shields.io/badge/bootstrap-000?style=for-the-badge&logo=bootstrap&logoColor=553C7B)
[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc)
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)

### GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mourafuseti&theme=transparent&bg_color=000&border_color=30A3DC&show_icons=true&icon_color=30A3DC&title_color=E94D5F&text_color=FFF)

# ClickFix 1.0

# 🛡️ Página de Verificação de Segurança (Captcha/Desafio de Humanidade)

Este repositório contém o código de uma página estática projetada para atuar como uma tela de verificação de segurança, simulando os desafios de humanidade encontrados em sites protegidos por serviços como o Cloudflare. O objetivo é criar uma representação de front-end do processo de "verificação de que você é humano" antes de conceder acesso ao conteúdo principal.

## 🌟 Recursos Principais

* **Design de Verificação:** Simula uma interface de verificação de segurança com um carregador (`preloader`), um campo de seleção "Eu não sou um robô" e um passo de verificação subsequente.
* **Fluxo de Múltiplas Etapas:** O JavaScript simula a transição entre as etapas:
    1.  Carregando (`Checking if you are human...`)
    2.  Check-box (`I'm not a robot`)
    3.  Verificação (Spinner)
    4.  Desafio Avançado (Instruções falsas de `Win + R` / `Ctrl + V`)
    5.  Sucesso (`Successfully.`)
* **Estrutura Cloudflare-Like:** Inclui elementos de rodapé que simulam a exibição de um "Ray ID" e menção à **Cloudflare** para maior autenticidade visual.
* **Desafio de Verificação Falso:** Apresenta um desafio de verificação complexo e incomum que simula uma etapa de segurança avançada ou maliciosa. **Este desafio não é funcional e deve ser considerado apenas para fins de simulação.**

---

## 🛑 AVISO LEGAL E USO ÉTICO 🛑

### Propósito Exclusivo de Estudo e Defesa Cibernética

**Este código é fornecido estritamente para fins educacionais, de pesquisa e para estudo de Defesa Cibernética e Testes de Penetração (Pentesting) em ambientes controlados e autorizados.**

O código simula interfaces de segurança para que desenvolvedores e analistas de segurança possam entender como esses mecanismos funcionam, como eles podem ser explorados e, mais importante, **como eles podem ser defendidos e mitigados**.

### Proibição de Uso Malicioso (Crime Cibernético)

Qualquer uso deste código para fins indevidos, maliciosos, ilegais, como **phishing, fraude, coleta não autorizada de dados, ou qualquer tipo de ataque cibernético**, é estritamente proibido e constitui **CRIME**.

**O autor deste código e mantenedor deste repositório não se responsabiliza por qualquer uso indevido e incentiva a todos os usuários a cumprirem as leis locais e internacionais de segurança cibernética.** Use esta ferramenta com responsabilidade e dentro dos limites da lei.

---

## 📁 Estrutura do Projeto

O projeto é composto por três arquivos principais:

| Arquivo | Descrição |
| :--- | :--- |
| `index.html` | O arquivo HTML principal que define a estrutura e o layout da página, incluindo a importação dos arquivos CSS e JS. |
| `styles.css` | Contém toda a estilização da página, incluindo o layout, as cores, o design do checkbox e as animações de carregamento (spinners). |
| `main.js` | Contém a lógica JavaScript para controlar o fluxo de verificação: alternar entre as etapas, gerenciar cliques nos botões e simular os temporizadores de verificação. |

## ⚙️ Configuração e Uso

### Pré-requisitos

O projeto requer apenas um navegador web moderno.

### Instruções

1.  Crie uma pasta local para o seu projeto (ex: `security-challenge-study`).
2.  Crie os seguintes arquivos dentro desta pasta, utilizando os códigos fornecidos na resposta anterior:
    * **`index.html`** (Seu código HTML original)
    * **`styles.css`** (Código CSS fornecido)
    * **`main.js`** (Código JavaScript fornecido)
3.  Abra o arquivo **`index.html`** no seu navegador para visualizar e interagir com o fluxo de verificação simulado.

> **Dica:** Você pode personalizar o nome do domínio exibido na página alterando a variável `DEFAULT_DOMAIN` dentro do arquivo `main.js`.
