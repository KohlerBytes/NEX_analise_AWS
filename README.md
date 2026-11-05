# Análise Avançada de Imagens e Texto com IA na AWS

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Git](https://img.shields.io/badge/Git-Versionamento-red)
![GitHub](https://img.shields.io/badge/GitHub-Portfólio-black)
![IA](https://img.shields.io/badge/IA-Inteligência%20Artificial-blue)

## Sobre o projeto

Este repositório foi criado como parte do desafio prático da **Digital Innovation One (DIO)**, com base no conteúdo *Nexa - Análise Avançada de Imagens e Texto com IA na AWS*.

O objetivo é explorar os recursos de inteligência artificial da Amazon Web Services (AWS) voltados ao processamento de imagens, reconhecimento de informações e extração automatizada de dados de documentos.

Além da aplicação dos conceitos apresentados durante o conteúdo, este projeto busca consolidar conhecimentos sobre organização de código, versionamento e documentação técnica utilizando Git e GitHub.

## Objetivos de aprendizagem

- Compreender como a inteligência artificial pode ser aplicada à análise de imagens e documentos.
- Conhecer o funcionamento de tecnologias de OCR (*Optical Character Recognition*).
- Explorar o Amazon Textract para extração de textos e informações estruturadas.
- Conhecer o Amazon Rekognition para análise e reconhecimento de imagens.
- Identificar possibilidades de automação por meio do processamento inteligente de documentos (IDP).
- Aplicar boas práticas de versionamento e organização de projetos com Git e GitHub.

## Tecnologias e serviços estudados

| Tecnologia | Aplicação |
|---|---|
| Amazon Textract | Extração de textos, tabelas e campos-chave de documentos. |
| Amazon Rekognition | Análise de imagens e reconhecimento de elementos visuais. |
| OCR | Reconhecimento óptico de caracteres em imagens e documentos digitalizados. |
| IDP | Processamento inteligente e automatizado de documentos. |
| Git | Controle de versão e histórico de alterações. |
| GitHub | Hospedagem, compartilhamento e apresentação do projeto. |

## Projetos e possibilidades exploradas

O repositório de referência apresenta quatro atividades práticas que demonstram diferentes possibilidades de aplicação da inteligência artificial.

### 1. OCR de CNH

Aplicação de reconhecimento óptico de caracteres para identificar informações presentes em uma Carteira Nacional de Habilitação.

**Possibilidades de aplicação:**
- Extração de informações de documentos.
- Automatização de cadastros.
- Redução da digitação manual.
- Apoio à conferência de dados.

### 2. OCR de lista escolar

Utilização de reconhecimento de texto para interpretar informações presentes em listas escolares.

**Possibilidades de aplicação:**
- Digitalização de listas.
- Identificação de nomes e informações.
- Conversão de documentos físicos em dados digitais.
- Automatização de processos administrativos.

### 3. Reconhecimento de atacantes

Exploração de recursos de análise de imagens para identificar elementos visuais relacionados a jogadores de futebol.

**Possibilidades de aplicação:**
- Reconhecimento de pessoas em imagens.
- Análise automatizada de conteúdo visual.
- Aplicações em organização de imagens e identificação de elementos.

### 4. Reconhecimento de celebridades

Exploração de funcionalidades de reconhecimento facial e identificação de celebridades em imagens utilizando recursos de inteligência artificial.

**Possibilidades de aplicação:**
- Análise de imagens.
- Identificação de rostos conhecidos.
- Organização e classificação de conteúdo visual.

> Os projetos acima representam as atividades e possibilidades descritas no repositório de referência. Os resultados e evidências da execução neste repositório devem ser registrados individualmente.

## Principais aprendizados

Durante o estudo dos conceitos apresentados, alguns pontos se destacam:

**1. OCR e extração de informações**

O OCR permite transformar textos presentes em imagens e documentos digitalizados em informações que podem ser processadas por sistemas computacionais.

**2. Amazon Textract**

O Textract vai além do reconhecimento simples de caracteres. Ele consegue identificar tabelas, formulários e pares de campos-chave e valores, permitindo estruturar informações extraídas de documentos.

**3. Amazon Rekognition**

O Rekognition oferece recursos de visão computacional para análise de imagens e vídeos, incluindo detecção de objetos, rostos e reconhecimento de celebridades.

**4. Processamento inteligente de documentos (IDP)**

O IDP combina tecnologias de reconhecimento e inteligência artificial para automatizar etapas de leitura, classificação, extração e validação de documentos.

**5. Aplicações no mercado**

Essas tecnologias podem ser utilizadas em setores como educação, saúde, seguros, segurança, comércio e serviços financeiros, contribuindo para a automação de tarefas e a redução de processos manuais.

## A importância do Git e GitHub

O Git é uma ferramenta essencial no desenvolvimento de software porque permite controlar o histórico de alterações de um projeto.

O GitHub complementa esse processo ao disponibilizar uma plataforma para hospedar repositórios, compartilhar códigos e colaborar com outros desenvolvedores.

### Comandos importantes do Git

| Comando | Finalidade |
|---|---|
| `git init` | Inicializa um repositório Git. |
| `git clone` | Clona um repositório existente. |
| `git status` | Exibe o estado dos arquivos. |
| `git add .` | Adiciona alterações à área de preparação. |
| `git commit -m "mensagem"` | Registra um conjunto de alterações. |
| `git push` | Envia commits para o repositório remoto. |
| `git pull` | Atualiza o repositório local com alterações remotas. |
| `git branch` | Lista ou gerencia branches. |
| `git checkout` | Alterna entre branches ou revisões. |
| `git log` | Exibe o histórico de commits. |

### Boas práticas para trabalhar com Git

- Criar commits pequenos e com mensagens objetivas.
- Utilizar mensagens que descrevam claramente as alterações realizadas.
- Manter o repositório organizado em pastas.
- Utilizar o arquivo `.gitignore` para evitar o envio de arquivos desnecessários.
- Não publicar senhas, chaves de acesso, tokens ou credenciais da AWS.
- Criar branches para desenvolver funcionalidades separadamente.
- Atualizar o README sempre que houver mudanças relevantes no projeto.
- Registrar os resultados e evidências dos testes realizados.

### Exemplo de fluxo de versionamento

```bash
# Inicializar o repositório
git init

# Verificar os arquivos modificados
git status

# Adicionar arquivos
git add .

# Registrar as alterações
git commit -m "docs: adiciona documentação inicial do projeto"

# Vincular ao repositório remoto
git remote add origin URL_DO_SEU_REPOSITORIO

# Enviar os arquivos para o GitHub
git push -u origin main
```

## Evidências e resultados

Este espaço deve reunir capturas de tela que comprovem as atividades realizadas durante o desafio.

### OCR de documentos

Adicionar aqui capturas de tela da entrada do documento e das informações efetivamente extraídas.

![Evidência OCR](images/ocr-documentos.png)

### Análise e reconhecimento de imagens

Adicionar aqui capturas de tela das análises realizadas e dos resultados obtidos.

![Evidência Rekognition](images/reconhecimento-imagens.png)

### Repositório GitHub

Adicionar uma captura de tela mostrando a estrutura dos arquivos e o histórico de commits.

![Evidência GitHub](images/repositorio-github.png)

## Possibilidades de evolução

Os conhecimentos estudados permitem imaginar aplicações mais completas, como:

- Sistemas automatizados para leitura e validação de documentos.
- Digitalização de cadastros e formulários.
- Sistemas de reconhecimento e classificação de imagens.
- Integração entre serviços de inteligência artificial e bancos de dados.
- Fluxos de processamento documental com validações automatizadas.
- Aplicações que utilizam APIs da AWS para disponibilizar recursos de IA.

## Repositório de referência

Projeto original disponibilizado pela Digital Innovation One:

[Nexa - Análise Avançada de Imagens e Texto com IA na AWS](https://github.com/digitalinnovationone/nexa-analise-avancada-de-imagens-e-texto-com-ia-na-aws)

## Considerações finais

O desenvolvimento deste desafio contribui para ampliar a compreensão sobre aplicações práticas de inteligência artificial em imagens e documentos, demonstrando como serviços em nuvem podem simplificar atividades que tradicionalmente exigem análise e processamento manual.

Outro aprendizado importante é a utilização do Git e GitHub como ferramentas de organização, versionamento e apresentação de projetos. Manter um histórico de alterações, documentar decisões e apresentar evidências são práticas relevantes para o desenvolvimento profissional na área de tecnologia.

Este repositório representa uma etapa do meu processo de aprendizagem em Engenharia de Software e no aprofundamento dos conhecimentos sobre inteligência artificial, computação em nuvem e desenvolvimento de soluções tecnológicas.

---

**Desenvolvido como parte de um desafio prático da Digital Innovation One (DIO).**
