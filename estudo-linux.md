## 📚 Índice

- [🏁 Introdução ao Linux (Módulo 1 – Capítulo 01)](#-antes-de-comecar-e-introducao-ao-linux-modulo-1--capitulo-01)
- [🧠 Sistemas Operacionais (Módulo 2 – Capítulo 02)](#-sistemas-operacionais-modulo-2--capitulo-02)
- [💻 Trabalhando no Linux (Módulo 3 – Capítulo 03)](#-trabalhando-no-linux-modulo-3--capitulo-03)
- [📚 Capítulo 4 – O Mundo Open Source](#capitulo-4--o-mundo-open-source)
- [🔧 Capítulo 5 – Trabalhando com o Shell (CLI)](#-capitulo-5--trabalhando-com-o-shell-cli https://github.com/jonasferreira-silva1/Fundamentos-do-Linux/blob/bf59736bf14b6d5e236ad4f04b66458c3c559ea3/estudo-linux.md#-cap%C3%ADtulo-5--trabalhando-com-o-shell-cli)
- [🧠 Capítulo 6 – Encontrando Ajuda no Linux](#-capitulo-6--encontrando-ajuda-no-linux)
- [🧪 Laboratório Capítulo 7 – Navegando no Sistema de Arquivos](#-laboratorio-pratico--capitulo-7-navegando-e-explorando-o-sistema-de-arquivos)

## 🏁 **Antes de começar e Introdução ao Linux (Módulo 1 – Capítulo 01)**

- **O que é Linux?**  
  👉 _Analogia:_ Pense no Linux como o **motor invisível** de muitos dispositivos — está por trás de celulares, servidores e até geladeiras inteligentes.

- **Distribuições (distros):**  
  👉 _Exemplo:_ Ubuntu, Fedora, Debian — como diferentes "sabores" de sorvete feitos com a mesma base (o kernel).

- **Comunidade e código aberto:**  
  👉 É como um grande grupo de pessoas que compartilham receitas de bolo e todos podem adaptar do seu jeito.

---

## 🧠 **Sistemas Operacionais (Módulo 2 – Capítulo 02)**

- **Função de um sistema operacional:**  
  👉 _Analogia:_ Ele é como o **gerente de uma empresa** — organiza os funcionários (programas) e recursos (memória, processador).

- **Tipos de sistemas:**

  - Monousuário/monotarefa (como um quarto com uma cama)
  - Multiusuário/multitarefa (um dormitório com várias camas organizadas)

- **Componentes básicos:**
  - **Kernel:** o núcleo — o "cérebro" que conversa com o hardware.
  - **Shell:** o "tradutor" entre você e o kernel.

---

## 💻 **Trabalhando no Linux (Módulo 3 – Capítulo 03)**

### **3.1 Navegando no Desktop**

- Linux pode ser usado no dia a dia como Windows ou macOS.  
  👉 _Exemplo:_ você pode escrever textos, navegar na internet e editar imagens usando o Linux.

- Instalar uma distribuição é como colocar um novo sistema operacional num computador antigo — e dá vida nova à máquina.

### **3.1.1 Acessando o Terminal**

- **GUI Terminal:** janela de terminal dentro da interface gráfica.  
  _Analogia:_ como abrir o WhatsApp Web em uma aba do navegador.

- **Virtual Terminal:** acessado com Ctrl + Alt + F2...  
  _Analogia:_ como sair do navegador e usar um telefone analógico direto na central.

---

### **3.2 Aplicações e Ferramentas**

- **Tipos de Aplicações:**

  - **Servidores (back-end):** ex: Apache, MariaDB  
    _Analogia:_ Cozinha de um restaurante — o cliente não vê, mas tudo é preparado ali.

  - **Desktop (front-end):** ex: LibreOffice, GIMP  
    _Analogia:_ É como usar lápis, papel, calculadora e régua digitais.

  - **Ferramentas:** editores, shells, gerenciadores  
    _Exemplo:_ o terminal é a caixa de ferramentas do administrador.

---

### **3.3 Ferramentas de Console**

- Ser um administrador Linux é entender como escrever pequenos scripts (como **receitas** que o sistema segue).

- **Shell scripts** automatizam tarefas.  
  👉 _Exemplo:_ criar um script que faz backup todo dia às 18h, sem você precisar lembrar.

### **3.3.2 Editores de Texto**

- **Vim e Emacs:** como usar um estúdio profissional de edição.
- **Nano:** como usar o Bloco de Notas — simples e direto.
  👉 _Dica:_ Se está começando, vá de Nano 😉

---

### **3.4 Gerenciamento de Pacotes**

- **Pacotes** são como caixas com um aplicativo + tudo que ele precisa para funcionar.
- Ferramentas como **apt (Debian/Ubuntu)** ou **dnf (Red Hat/Fedora)** instalam automaticamente o que for necessário.

### **3.4.2 RPM (Red Hat Package Manager)**

- `.rpm` é como um "ZIP" pronto para ser instalado.
- Ferramentas como **yum** ou **dnf** cuidam da instalação, atualização e remoção.

---

### **3.6 Segurança e Privacidade**

- Cookies e rastreadores são como pegadas digitais — podem seguir você pela internet.
- **Dicas práticas:**
  - Use senhas fortes (como cofre com código).
  - Ative o firewall (porteiro da sua casa digital).
  - Use modo anônimo e ajuste as configurações do navegador.

---

### **3.7 Nuvem e Linux**

- A nuvem é como **alugar espaço em um prédio ao invés de ter o seu próprio**.
- Linux é o sistema mais usado na nuvem por ser leve, gratuito e escalável.
- Conceitos importantes:
  - **Virtualização:** várias "máquinas" rodando dentro de uma.
  - **Contêineres:** como marmitas empilhadas, cada uma com sua função.

---

📚 Capítulo 4 – O Mundo Open Source
4.1 Introdução ao Código Aberto
👉 Analogia: O código-fonte é como a receita de um bolo: legível para humanos, cheia de ingredientes e instruções.

Compilador: transforma a receita (código-fonte) em um bolo (programa executável) que o computador entende.

Software proprietário: você recebe o bolo pronto, mas nunca vê a receita.

Software open source: você recebe o bolo e a receita completa — pode adaptar, melhorar e compartilhar.

💡 Curiosidade: O Linux nasceu dentro dessa filosofia — feito em C, inspirado no UNIX, com colaboração global impulsionada pela internet.

4.2 Licenciamento Open Source
👉 Pense assim: Quando você "compra" software, você não compra o código, e sim uma licença de uso, como um ingresso que determina:

Onde pode usar,

Se pode compartilhar,

E se pode modificar.

Licenças:
GPL (Free Software Foundation): você pode modificar, mas tem que manter o código aberto (copyleft).

BSD/MIT (OSI): mais permissiva — você pode fechar o código modificado, desde que dê crédito ao autor.

🎭 FLOSS ou FOSS?

FOSS = Free and Open Source Software

FLOSS = Free/Libre/Open Source Software 📌 "Free" pode ser "livre" ou "de graça" — por isso a confusão!

4.2.2 The Open Source Initiative (OSI)
Criada por Bruce Perens e Eric Raymond em 1998.

Rejeita ideias muito rígidas da FSF, mas defende a liberdade de usar e modificar o código sem restrições de uso.

A OSI não cria licenças, mas reconhece as que seguem seus princípios.

👉 Licenças BSD: > "Use como quiser, só não diga que foi você quem criou."

4.3 Modelos de Negócio com Open Source
👉 Analogia: Você pode ter a receita de bolo grátis, mas pode ganhar dinheiro vendendo o bolo pronto, decorado e com entrega expressa.

Formas de monetização:

Suporte e garantias: Red Hat, Canonical (Ubuntu) vendem ajuda técnica premium.

Produtos derivados: DVRs, câmeras, roteadores e outros dispositivos usam Linux por trás.

Consultoria e integrações: empresas contratam especialistas em Linux/Open Source para implementar soluções sob medida.

Patrocínio de projetos: empresas grandes investem em projetos de que dependem (como bancos, Google, Amazon etc).

📌 Resumo do Capítulo 4: O software livre libera o conhecimento, gera comunidades inovadoras e cria novas formas de negócio, onde o lucro não vem da exclusividade, mas do valor agregado — seja por suporte, personalização ou integração.

Claro, Jonas! Vamos atualizar o nosso documento agora com os conteúdos do **Capítulo 5 – Trabalhando com o Shell (CLI)**, mantendo o estilo didático com analogias e exemplos simples para facilitar a assimilação:

---

## 🔧 Capítulo 5 – Trabalhando com o Shell (CLI)

### **5.1 Introdução ao CLI**

👉 _Analogia:_ A linha de comando é como uma **linguagem secreta do sistema**.  
Pode parecer intimidadora no início, mas permite **velocidade, automação e controle total** do sistema.  
✅ Comandos são universais entre distros — quem domina o terminal, domina qualquer Linux.

---

### **5.3 Comandos**

- **O que é um comando?**  
  👉 Um comando é como um **verbo** no idioma do Linux. Ex: `ls` = listar.

- **Formato padrão:**
  ```bash
  comando [opções] [argumentos]
  ```

---

### **5.3.1 Argumentos**

- São os **alvos da ação** do comando.  
  👉 Exemplo: `ls /etc/ppp` → lista os arquivos dessa pasta.

- Com múltiplos argumentos:
  ```bash
  ls /etc/ppp /etc/ssh
  ```

---

### **5.3.2 Opções**

- Ajustam o **modo de execução** do comando.  
  👉 Exemplo: `ls -l` mostra detalhes como tamanho, permissões e data.

- Combinando opções:
  ```bash
  ls -lh   # Detalhado e legível
  ls -lr   # Detalhado + ordem reversa
  ```

---

### **5.3.3 Histórico de Comandos**

- Use `↑` para navegar no histórico.
- Execute novamente com:
  - `!!` → último comando
  - `!3` → comando nº 3 da lista
  - `!-2` → 2º do fim
- Veja a lista: `history`  
  👉 _Exemplo:_ `!ls` executa o último comando `ls`.

---

### **5.4 Variáveis**

#### **5.4.1 Variáveis Locais**

- Criadas assim:
  ```bash
  cor='azul'
  echo $cor
  ```
- Só existem na sessão atual do terminal.

#### **5.4.2 Variáveis de Ambiente**

- Afetam o sistema todo. Exemplos: `$PATH`, `$HOME`, `$HISTSIZE`
- Promova uma variável local:

  ```bash
  export minha_var='teste'
  ```

- Remova:
  ```bash
  unset minha_var
  ```

---

### **5.4.3 A variável PATH**

👉 _Analogia:_ Um mapa de pastas onde o terminal busca comandos.  
✅ Exemplo:

```bash
echo $PATH
```

✅ Adicionando diretórios:

```bash
PATH=/meu/novo/caminho:$PATH
```

---

### **5.5 Tipos de Comandos**

#### **5.5.1 Comandos Internos (built-in)**

👉 Já estão embutidos no shell. Ex: `cd`

Verifique:

```bash
type cd   # cd is a shell builtin
```

#### **5.5.2 Comandos Externos**

👉 São arquivos em `/bin`, `/usr/bin`, etc. Ex: `ls`

Veja o caminho:

```bash
which ls
type -a ls
```

---

### **5.5.3 Aliases**

👉 _Analogia:_ Atalhos personalizados.

- Exemplo:

  ```bash
  alias l='ls -CF'
  alias mycal='cal 2030'
  ```

- Veja todos: `alias`
- Temporários (somem ao fechar o terminal)
- Permanentes: adicionar no `.bashrc`

---

### **5.5.4 Funções**

👉 _Analogia:_ Um botão que executa **vários comandos**.

- Exemplo:

  ```bash
  relatorio () {
    ls Documents
    date
    echo "Documentos listados"
  }
  ```

- Execute com: `relatorio`
- Também são temporárias, a não ser que salve no `.bashrc`

---

### **5.6 Aspas e Substituições**

#### **5.6.1 Aspas Duplas (`" "`):**

- Protegem glob (`*`, `?`)
- Ainda interpretam:
  - Variáveis: `$PATH`
  - Comandos: `$(date)`

#### **5.6.2 Aspas Simples (`' '`):**

- Protegem **tudo**, inclusive variáveis.  
  👉 Exemplo:
  ```bash
  echo '$USER'   # Exibe: $USER
  ```

#### **5.6.4 Crase / Backquotes (`` ` ` ``):**

👉 Usado para substituir o conteúdo de um comando:

```bash
echo Hoje é `date`
```

➡️ Melhor usar: `$(date)`

---

### **5.7 Operadores de Comando**

#### **5.7.1 `;` (ponto e vírgula)**

- Executa todos, na ordem, mesmo que algum falhe:

```bash
comando1; comando2; comando3
```

#### **5.7.2 `&&` (E lógico)**

- Executa o segundo **só se o primeiro der certo**

```bash
mkdir pasta && cd pasta
```

#### **5.7.3 `||` (OU lógico)**

- Executa o segundo **só se o primeiro falhar**

```bash
ls /erro || echo "Pasta não encontrada"
```

---

📌 **Resumo do Capítulo 5:**  
O shell é uma linguagem poderosa que transforma o usuário em **comandante direto do sistema**. Aprender sua lógica — comandos, variáveis, operadores, funções — é como pegar as chaves do carro da administração do Linux.

Claro, Jonas! Aqui está um **resumo atualizado e completo do Capítulo 5** do laboratório, com explicações práticas baseadas em todos os passos que você explorou:

---

## 🧩 **Capítulo 5 – Trabalhando com o Shell e Comandos**

### **5.3 – Histórico de Comandos**

- **`history`** exibe os comandos utilizados. Você pode limitar, como em `history 5` (últimos 5 comandos).
- Para **reexecutar um comando antigo**:
  - `!9` → executa o 9º comando da lista
  - `!!` → repete o último
  - `!ls` → executa o último comando que começa com `ls`
- Use as **setas ↑ e ↓** para navegar entre comandos anteriores e editá-los facilmente.

---

### **5.4 – Variáveis de Ambiente**

- O comando **`echo`** exibe textos, variáveis ou resultados de comandos.
- Use `echo $HISTSIZE` para ver quantos comandos são guardados no histórico (ex: 1000).
- `echo $PATH` mostra onde o sistema procura executáveis.
- O comando **`which`** identifica o caminho de um executável (ex: `which date` → `/bin/date`).

---

### **5.5 – Tipos de Comandos**

Existem **quatro tipos principais**:

1. **Internos (built-in)**  
   Ex: `cd` → parte do shell Bash

2. **Externos (executáveis)**  
   Ex: `ls`, `vi`, `cp` → armazenados em diretórios como `/bin`

3. **Aliases (atalhos)**  
   Ex: `alias ll='ls -alF'` → atalho para comandos longos

4. **Funções**  
   Blocos de comandos definidos pelo usuário.

Use:

- `type comando` para identificar o tipo.
- `type -a comando` para ver todas as origens (alias + binário).
- `alias` → lista os aliases atuais.

---

### **5.6 – Uso de Aspas (Quoting)**

**Tipos de aspas:**

| Tipo                    | Interpreta variáveis? | Interpreta `*`? | Executa comandos? | Exemplo                       |
| ----------------------- | --------------------- | --------------- | ----------------- | ----------------------------- |
| **Aspas simples** `' '` | ❌                    | ❌              | ❌                | `'Olá $USER' → Olá $USER`     |
| **Aspas duplas** `" "`  | ✅                    | ❌              | ✅                | `"Olá $USER"` → Olá jonas     |
| **Crases** `` ` ` ``    | ❌                    | ❌              | ✅                | `` `date` `` → executa `date` |

- Também é possível **escapar caracteres individuais** com `\`, como em `\*` ou `` \` ``.

---

### **5.7 – Separadores Lógicos de Comando**

Você pode **encadear comandos** na mesma linha com:

- **`;`** → executa todos em sequência, mesmo se algum falhar  
  `echo A; echo B; echo C`

- **`&&`** → executa o próximo **só se o anterior tiver sucesso**  
  `mkdir pasta && cd pasta`

- **`||`** → executa o próximo **só se o anterior falhar**  
  `cd inexistente || echo "Erro: pasta não existe"`

Exemplos:

```bash
false; echo A       # Executa ambos
false && echo B     # Só executa false
false || echo C     # Executa echo C
```

---

# 🧠 Capítulo 6 — Encontrando Ajuda no Linux

## 6.1 Introdução

**Resumo:**  
A linha de comando é muito poderosa, mas também complexa. Portanto, **saber encontrar ajuda é essencial**.

**Analogia:**  
👉 Como dirigir um carro esportivo cheio de botões — potência sem manual pode te deixar travado. O sistema de ajuda é esse manual!

---

## 6.2 Páginas de Manual (man pages)

### 6.2.1 Visualizando man pages

```bash
man comando
```

**Analogia:**  
👉 É como abrir o manual impresso do produto. Explica o básico, recursos e como usar cada botão.

---

### 6.2.2 Seções dentro das man pages

- NAME → nome e descrição breve
- SYNOPSIS → como usar
- DESCRIPTION → o que faz
- OPTIONS → parâmetros disponíveis
- AUTHOR, FILES, SEE ALSO...

**Analogia:**  
👉 Igual ao índice de um livro técnico, cada parte da página tem seu foco — só precisa saber onde procurar.

---

### 6.2.3 Buscando termos dentro de man pages

Use `/palavra` para procurar uma palavra na man page, `n` para próxima ocorrência e `Shift + N` para voltar.

**Analogia:**  
👉 Como usar "Ctrl + F" num PDF gigante.

---

### 6.2.4 Seções por número

Se um mesmo nome tem man pages diferentes, use o número da seção:

```bash
man 5 passwd
```

**Analogia:**  
👉 Como procurar "banco" no dicionário: pode ser assento (seção 1) ou instituição financeira (seção 5).

---

## 6.3 Encontrando comandos e documentação

### 6.3.1 Comando `whereis`

Mostra onde o comando e suas man pages estão no sistema:

```bash
whereis ls
```

**Analogia:**  
👉 Como perguntar pro sistema: "onde estão os arquivos e o manual desse comando?"

---

### 6.3.2 Comando `locate`

Busca por qualquer arquivo, muito rápido, usando um banco de dados:

```bash
locate passwd
```

**Analogia:**  
👉 Um "Google offline" do seu sistema — mas ele não sabe das novidades do dia, a menos que seja atualizado.

---

## 6.4 Documentação `info`

### 6.4.1 Visualizando com `info`

```bash
info ls
```

Apresenta explicações mais completas e estruturadas.

**Analogia:**  
👉 É como ler um livro com índice clicável e capítulos explicativos — mais fácil de entender do que o manual técnico (`man`).

---

### 6.4.2 Navegação no `info`

- `n` → próximo capítulo
- `p` → anterior
- `u` → subir nível
- `l` → voltar ao último
- `Enter` → seguir link
- `q` → sair

**Analogia:**  
👉 Um e-book interativo, com índice e botão "voltar".

---

### 6.4.3 Explorando o `info`

Executar `info` sem argumentos abre o "livro-mãe" da documentação.

**Analogia:**  
👉 Como abrir a enciclopédia Linux. Você pode passear livremente pelos temas e aprender algo novo mesmo sem estar buscando nada específico.

---

## 6.5 Outras fontes de ajuda

### 6.5.1 Opção `--help`

Mostra uma descrição simples do comando diretamente no terminal:

```bash
comando --help
```

**Analogia:**  
👉 É como o adesivo que vem colado no produto, com as instruções rápidas — não tão completo quanto o manual, mas suficiente pra começar.

---

### 6.5.2 Documentação extra do sistema

Arquivos locais de ajuda nos diretórios:

```bash
/usr/share/doc
```

Arquivos como `README`, `INSTALL`, `CHANGELOG`, etc.

**Analogia:**  
👉 Como o encarte dentro da caixa de um aparelho novo — às vezes tem dicas valiosas não encontradas em mais lugar nenhum.

---

# 🧩 Capítulo 6 + Laboratório 6 — A Arte de Obter Ajuda e Encontrar Arquivos no Linux

## 6.1 Introdução

Saber usar o terminal é importante. Mas **saber pedir ajuda ao terminal é essencial**.  
Esse módulo ensina a usar ferramentas internas do Linux para encontrar informações sobre comandos, arquivos e funcionamento geral do sistema — sem depender da internet.

---

## 6.2 Como obter ajuda no Linux

### 💬 `man` – A página do manual

- Use `man comando` para abrir o manual técnico de um comando.
- Seções incluem: NAME, SYNOPSIS, DESCRIPTION, OPTIONS…
- Dentro do `man`, use:
  - `/palavra` para buscar termos
  - `n` / `N` para navegar pelos resultados
  - `q` para sair

**Exemplo prático:**

```bash
man date
```

👨‍🏫 _Analogia:_ O `man` é o "manual técnico de bolso" do Linux.

---

### 📘 `info` – A explicação em forma de livro

- Use `info comando` para acessar um guia estruturado com capítulos, exemplos e links entre tópicos.
- Comandos úteis:
  - `n` → próximo tópico
  - `u` → subir nível
  - `l` → voltar ao último ponto
  - `Enter` → seguir link
  - `q` → sair
  - `h` → ajuda da navegação (diferente do `man`!)

**Exemplo prático:**

```bash
info date
```

👨‍🏫 _Analogia:_ O `info` é como um livro digital interativo, com navegação por tópicos e explicações mais amigáveis.

---

### ⚡ `--help` – O adesivo colado no produto

- Rápido, direto e disponível na maioria dos comandos GNU:

```bash
date --help
```

��‍🏫 _Analogia:_ É a "cola rápida" de como usar o comando, ideal para lembrar as flags e ver exemplos.

---

### 🔍 `man -k` e `whatis` – Caça ao comando pelo nome

- Quando você não lembra o nome exato:

```bash
man -k senha
whatis passwd
```

👨‍🏫 _Analogia:_ São como sumários ou índices automáticos do sistema.

---

### 🔢 `man` com seções numeradas

- Um mesmo nome pode ter várias man pages (ex: `passwd (1)`, `passwd (5)`)

```bash
man 5 passwd
```

👨‍🏫 _Analogia:_ Como "manga" no dicionário — pode ser fruta ou parte da camisa.

---

### 📂 Documentação adicional

- Navegue até:

```bash
ls /usr/share/doc
```

- Acesse arquivos como `README`, `changelog`, `COPYING` com `less`.

👨‍🏫 _Analogia:_ É o encarte detalhado que vem na caixa do software.

---

## 6.3 Encontrando Arquivos e Comandos

### 🚀 `locate` – Busca rápida por nome

- Usa um banco de dados indexado:

```bash
locate crontab
```

- Use `-b "\nome"` para buscar somente pelo nome exato:

```bash
locate -b "\crontab"
```

📌 _Atenção:_ Não encontra arquivos criados recentemente, a menos que você atualize o banco com `sudo updatedb`.

---

### 🧠 `whereis` – Encontre o comando, suas man pages e localização

```bash
whereis passwd
```

👨‍🏫 _Analogia:_ É como perguntar "onde está o comando, seu manual e seus anexos?"

---

## 📘 **Capítulo 7 – Trabalhando com o Sistema de Arquivos**

---

### 🗃️ **7.1 – Introdução**

No Linux, **tudo é tratado como arquivo**: documentos, imagens, programas, diretórios e até dispositivos.

📦 **Analogia:** Pense em um armário onde tudo — até o próprio armário — é um item armazenado.

---

### 🌳 **7.2 – Estrutura de Diretórios**

#### 🧭 7.2.1 **Diretório Home**

- Cada usuário tem uma **pasta pessoal** localizada em `/home/nomedousuário`.
- Ela é representada por `~` e é o local onde o usuário tem **controle total**.

🏡 **Analogia:** É o seu "quarto privado" dentro da casa Linux.

---

#### 📍 7.2.2 **Diretório Atual**

- Use `pwd` para descobrir **onde você está** no sistema de arquivos.

🧭 **Analogia:** É o "você está aqui" no mapa do shopping.

---

#### 🔁 7.2.3 **Mudando de Diretório**

- Use `cd` para navegar entre pastas.
- `cd` sozinho retorna ao diretório pessoal (`~`).
- Se tentar acessar algo que não existe, o terminal avisa.

🚪 **Analogia:** É como abrir portas para entrar em outros cômodos do sistema.

---

### 🛣️ **7.3 – Caminhos**

#### 📌 7.3.1 **Caminhos Absolutos**

- Começam com `/` e indicam o **trajeto completo** a partir da raiz.

🗺️ **Analogia:** É o endereço completo com CEP.

---

#### 🧾 7.3.2 **Caminhos Relativos**

- Começam do diretório atual.
- Não usam `/` no início.

📍 **Analogia:** "Vire à direita na próxima esquina".

---

#### 🔼 7.3.3 **Atalhos `.` e `..`**

- `..` = sobe um nível
- `.` = representa o diretório atual

🧗 **Analogia:** `..` é subir uma escada para o andar de cima; `.` é permanecer onde está.

---

### 📋 **7.4 – Listando Arquivos**

#### 🔎 7.4.1 **Arquivos Ocultos**

- Começam com `.` e são exibidos com `ls -a`.

🎭 **Analogia:** Itens nos bastidores — importantes, mas fora dos holofotes.

---

#### 🧾 7.4.2 **Listagem Longa (`ls -l`)**

- Mostra detalhes: tipo, permissões, dono, tamanho, data e nome.

🔬 **Analogia:** É como um raio-X completo de cada arquivo.

---

#### 📏 7.4.3 **Tamanhos Legíveis (`-h`)**

- `ls -lh` mostra os tamanhos em K, M, G.

📐 **Analogia:** É como medir a distância entre cidades em quilômetros, não em polegadas.

---

#### 📁 7.4.4 **Listando o Próprio Diretório (`-d`)**

- Exibe informações da pasta em si, e não de seu conteúdo.

📦 **Analogia:** Ver a caixa, não o que tem dentro dela.

---

#### 🌳 7.4.5 **Listagem Recursiva (`-R`)**

- Mostra todos os arquivos **e** subpastas.

⚠️ **Cuidado:** Usar em `/` pode inundar o terminal.

---

#### 📊 7.4.6 **Ordenações**

- **`ls -S`** → por tamanho (maior primeiro)
- **`ls -lSh`** → detalhado, tamanho legível
- **`ls -t`** → por data de modificação (mais recente)
- **`ls -t --full-time`** → data e hora completas
- **`-r`** → inverte a ordem (ex: menor para maior)

🗃️ **Analogia:** Como reordenar documentos por peso, data ou ordem alfabética.

---

Claro, Jonas! Aqui está o **resumo oficial do módulo prático do laboratório do Capítulo 7**, com um título claro para destacar que se trata da parte **executada dentro do terminal**, com comandos e saídas reais:

---

## 🧪 **Laboratório Prático – Capítulo 7: Navegando e Explorando o Sistema de Arquivos**

Este módulo coloca em prática os conceitos vistos em teoria, guiando o aluno por meio de comandos reais para navegar, localizar e investigar arquivos e pastas no Linux. Ao final, o usuário ganha confiança para interagir com o sistema **sem interface gráfica**, utilizando apenas o terminal.

---

### 🗃️ **7.1 – Introdução**

Você será capaz de:

- Entrar e sair de diretórios com `cd`
- Descobrir sua localização atual com `pwd`
- Visualizar conteúdos com `ls`

📦 **Analogia:** É como aprender a andar por uma cidade desconhecida com mapa e lanterna na mão.

---

### 🧭 **7.2 – Arquivos, Diretórios e Caminhos**

#### 7.2.1 🔍 `pwd` – Mostra onde você está

- Exibe o caminho completo do diretório atual.
- Exemplo: `/home/sysadmin`

---

#### 7.2.2 🚪 `cd /` – Vai para a raiz do sistema

- Sobe ao ponto mais alto da estrutura de diretórios.

---

#### 7.2.3 🏡 `cd` – Retorna para sua home

- Sem argumentos, `cd` leva direto para seu diretório pessoal (`~`).

---

#### 7.2.4 🗺️ `cd /home` – Caminho absoluto

- Caminho completo começando por `/`.

---

#### 7.2.5 🌀 `cd ~` – Usando `~` para voltar pra casa

- Atalho que representa o diretório pessoal.
- Também funciona com `~usuario`.

---

#### 7.2.6 📫 `echo ~usuario` – Ver o caminho da home de qualquer usuário

- O sistema expande o `~nome` para mostrar onde fica a pasta home daquele usuário.

---

#### 7.2.7 ⛔ `cd ~root` – Tentativa sem permissão

- Usuários comuns não podem acessar `/root`.

---

#### 7.2.8 🔧 `cd /usr/bin` – A sala de comandos do sistema

- Diretório cheio de executáveis como `ls`, `pwd`, `mv`, etc.

---

#### 7.2.9 📂 `cd /usr` – Subindo um nível

- Passa da pasta de comandos (`/usr/bin`) para sua pasta mãe.

---

#### 7.2.10 🧭 `cd /usr/share/doc` – Caminho completo para diretório profundo

- Exemplo de navegação usando **caminho absoluto**.

---

#### 7.2.11 🚶 `cd bash` – Caminho relativo

- Funciona dentro de `/usr/share/doc` para entrar em `bash`.

---

#### 7.2.12 🔙 `cd ..` – Voltar uma pasta

- Sobe um nível na estrutura de diretórios.

---

#### 7.2.13 ↕️ `cd ../dict` – Subir e descer em um só comando

- Combina a ida para cima (`..`) com a entrada em outra pasta (`dict`).

---

### 📁 **7.3 – Listando Arquivos com `ls`**

#### 7.3.1 👁️ `ls` – Lista arquivos visíveis

- Cores indicam tipo: azul (diretório), verde (executável), ciano (link), branco (arquivo comum).

---

#### 7.3.2 🎭 `ls -a` – Inclui arquivos ocultos

- Arquivos que começam com `.` (como `.bashrc`) aparecem.

---

#### 7.3.3 🔍 `ls -l` – Listagem detalhada

- Mostra permissões, tamanho, dono e data de modificação.

---

#### 7.3.4 🌲 `ls -R` – Listagem recursiva

- Mostra o conteúdo das subpastas também.

---

#### 7.3.5 ✳️ `ls -d /etc/s*` – Usando `*` como coringa

- Lista itens do `/etc` que começam com "s".

---

#### 7.3.6 ❓ `ls -d /etc/????` – Usando `?` para tamanho exato

- Exibe arquivos com exatamente 4 caracteres no nome.

---

#### 7.3.7 🔠 `ls -d /etc/[abcd]*` – Filtrando por letras específicas

- Mostra arquivos que começam com "a", "b", "c" ou "d".

---
