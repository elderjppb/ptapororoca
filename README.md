# Portal - Prefeitura Municipal de Itapororoca

## Sobre o Projeto
Este projeto é o portal institucional oficial desenvolvido para a Prefeitura Municipal de Itapororoca. O objetivo principal é fornecer uma plataforma pública, rápida e acessível para garantir a transparência da gestão, informar os cidadãos com notícias locais e facilitar o contato com a administração.

O desenvolvimento foi focado em performance e acessibilidade, utilizando uma arquitetura de site estático.

## Tecnologias e Stack

O projeto utiliza uma stack front-end pura e otimizada:
* **HTML5:** Estrutura semântica das páginas.
* **CSS3:** Estilizações customizadas.
* **Bootstrap 5.3:** Framework CSS para componentes responsivos (via CDN).
* **JavaScript (Vanilla):** Comportamentos de interface fornecidos pelo Bootstrap Bundle.

## Padrão de Arquitetura (Estrutura de Arquivos)

O projeto segue um design pattern de separação de responsabilidades para sites estáticos, mantendo assets e páginas em diretórios isolados:

```text
/projeto-itapororoca
│── index.html              # Landing Page principal (Hero, História, Prefeitura)
│── README.md               # Documentação do projeto
│── /pages                  # Páginas internas do portal
│   └── noticia.html        # Template para leitura de notícias completas
│── /assets                 # Arquivos estáticos globais
│   ├── /css
│   │   └── style.css       # Regras de estilo customizadas
│   └── /img                # Mídias e imagens do município
```

## Integração Contínua e Deploy (CI/CD)

O portal conta com um pipeline de **CI/CD** automatizado.

1. **Repositório:** O código-fonte é versionado no **GitHub**.
2. **Deploy Automático:** O repositório está conectado à **Vercel**.
3. **Fluxo:** Qualquer novo `push` ou aprovação de `Pull Request` na branch `main` dispara automaticamente um novo build na Vercel. Em poucos segundos, as alterações entram no ar sem necessidade de intervenção manual nos servidores.

## Funcionalidades Presentes

* **Design Responsivo:** Adaptável a celulares, tablets e desktops.
* **Navegação Âncora (Smooth Scroll):** Menu principal linkado com as seções da página.
* **Seção Histórica:** Resumo sobre a fundação de Itapororoca (Vila São João, rota dos tropeiros).
* **Transparência:** Espaço reservado para atalhos de leis municipais e portal da transparência.
* **Cards de Notícias:** Layout preparado para expansão e leitura em páginas internas.
* **Formulário de Contato:** Interface pronta para futura integração com serviços de envio (ex: Formspree).

## Autores
* Elder
* Nathyane

## Licença
Projeto desenvolvido para fins institucionais/educacionais referente à gestão municipal de Itapororoca - PB (2026).