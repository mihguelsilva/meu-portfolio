# 💼 Portfólio de Mihguel da Silva Santos Tavares de Araujo

Bem-vindo ao meu portfólio! Sou um desenvolvedor apaixonado por tecnologia, com foco em desenvolvimento web utilizando PHP, MySQL/MariaDB e arquitetura MVC. Este portfólio apresenta um pouco sobre minha trajetória, minhas habilidades e projetos que desenvolvi com dedicação e propósito.

## 👨‍💻 Sobre Mim

Sou desenvolvedor com forte afinidade em redes de computadores e automação, e atualmente tenho direcionado meu foco para o desenvolvimento web, utilizando PHP com boas práticas e orientação a objetos. Tenho como objetivo evoluir constantemente, contribuir com projetos que façam a diferença e construir uma carreira sólida para realizar um sonho pessoal: o casamento com minha futura esposa. 💍

## 🛠️ Tecnologias que utilizo

- PHP 8
- MySQL/MariaDB
- Bootstrap 5
- Composer
- Arquitetura MVC
- Git e GitHub
- Servidores GNU/Linux e Windows

## 🚀 Projetos em Destaque

### 📌 [Cadastro MVC com PHP](https://github.com/mihguelsilva/cadastro-mvc-php)

Sistema de cadastro desenvolvido em PHP puro utilizando a arquitetura MVC. O sistema implementa operações de CRUD (Create, Read, Update, Delete), utiliza PDO para conexão com banco de dados, segue boas práticas e tem estrutura escalável.

**Recursos:**
- Separação em Model, View e Controller
- Utilização de Composer e autoload via PSR-4
- Uso de variáveis de ambiente para segurança
- Templates HTML com Bootstrap
- Boas práticas de segurança com `prepared statements`

### 🔐 [Sistema de Login Seguro com Painel Administrativo](https://github.com/mihguelsilva/php-mvc-login-seguro)

Este projeto implementa um sistema de login seguro utilizando **PHP puro** com a arquitetura **MVC**. Ele oferece um painel administrativo protegido, onde é possível gerenciar usuários e visualizar mensagens recebidas via formulário de contato.

A autenticação é feita com **hash seguro de senha**, controle de **sessões**, e diversas **boas práticas de segurança** como tokens CSRF, validação de dados e proteção de rotas via middleware.

---

#### 🛠 Funcionalidades principais

- 🔒 Login seguro com `password_hash`
- 🧑‍💼 Gestão de usuários cadastrados
- ✉️ Visualização e gerenciamento de mensagens de contato
- 📊 Dashboard com estatísticas do sistema
- 🛡 Proteção de rotas com middleware
- ✅ Segurança aprimorada com tokens CSRF e validações rigorosas

---

#### 📂 Tecnologias utilizadas

- PHP 8+
- Composer (PSR-4 autoload)
- HTML5, CSS3 e Bootstrap 5
- Banco de dados MySQL/MariaDB
- Sessões com `$_SESSION`
- Estrutura MVC personalizada
- PHPMailer para envio de emails

### 🛠️ Reestruturação de Topologia de Rede com Autenticação PPPoE e VPN L2TP/IPSec

#### 📍 Contexto
Ambiente corporativo com múltiplos servidores interligados, utilizando conexão de internet por roteador wireless (Huawei) e infraestrutura de rede baseada em RouterBOARD (RB).

#### ⚠️ Desafio
A conexão estava instável e mal configurada:  
- Topologia incorreta, com roteador wireless gerenciando a autenticação.  
- Falta de segmentação clara entre funções de roteamento, autenticação e comunicação entre servidores.  
- Ausência de VPN para acesso seguro entre unidades ou servidores remotos.

#### 🔧 Solução Implementada
1. **Análise da arquitetura** e identificação do erro de topologia.
2. **Redirecionamento do ponto de autenticação PPPoE**: passou do roteador wireless para a RB.
3. **Configuração da VPN L2TP/IPSec** na RB para conexão segura entre servidores.
4. **Modificação do roteador Huawei para modo Bridge**, garantindo que os IPs públicos fossem entregues diretamente pela RB, com suas interfaces agrupadas em Bridge.
5. Testes de estabilidade, segurança e conectividade entre pontos.

#### ✅ Resultado
- Arquitetura otimizada com funções bem definidas.  
- Conexão autenticada corretamente e com maior estabilidade.  
- Comunicação segura entre servidores via VPN.  
- Eliminação de NAT duplo e conflitos de roteamento.  
- Cliente extremamente satisfeito com a clareza, eficiência e profissionalismo da entrega.

## 📚 Em andamento

Estou aprofundando meus conhecimentos em:
- Framework Laravel
- Testes automatizados
- Boas práticas de Clean Code e SOLID
- Criação de APIs RESTful

## 🔗 Contato

- [LinkedIn](https://www.linkedin.com/in/mihguel-da-silva-santos-tavares-de-araujo/)
- [GitHub](https://github.com/mihguelsilva)
- Email: mihguelaraujo@gmail.com

---

Obrigado por visitar meu portfólio! Fique à vontade para explorar meus projetos, contribuir, ou entrar em contato para trocarmos ideias ou colaborarmos em algo novo.

