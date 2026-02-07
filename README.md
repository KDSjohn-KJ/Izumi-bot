<div align="center">

<img src="./izumi-banner.png" width="100%" alt="Izumi Bot Banner">

# 🌸 Izumi-Bot 🌸

### *O Bot de WhatsApp Mais Completo que Você Vai Conhecer!* ✨

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/+5541996367048)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

**Versão:** 1.0.0 | **Status:** 🟢 Ativo | **Licença:** MIT

---

### 💝 *"Eu... eu posso fazer muito mais do que você imagina!"* - Izumi

---

</div>

## 📖 Sobre o Projeto

**Izumi-Bot** é um bot multifuncional para WhatsApp inspirado na adorável Izumi Sagiri de *Eromanga Sensei*! 🎨

Desenvolvido usando **Baileys** e **Node.js**, o Izumi oferece desde comandos administrativos até um **sistema de RPG completo** com classes, dungeons, guilds, pets e muito mais!

### ✨ Por que Izumi-Bot?

- 🎮 **Sistema RPG Completo** - 10 classes, dungeons infinitas, sistema de guild wars, pets e muito mais!
- 🎭 **Multi-Funcional** - Mais de 150+ comandos em 9 categorias diferentes
- 🔰 **Interface Intuitiva** - Menus interativos com botões para facilitar sua vida
- 💎 **Sistema Premium** - Benefícios exclusivos para usuários VIP
- 🛡️ **Proteção Avançada** - Anti-link, anti-spam, anti-flood e muito mais
- 🌸 **Kawaii** - Interface linda e mensagens inspiradas na Izumi!

---

## 🎯 Funcionalidades Principais

<div align="center">

| 🎭 Categoria | 📝 Descrição | ⭐ Destaques |
|:---:|:---|:---|
| **👑 Admin** | Comandos de moderação de grupo | Ban, Kick, Antilink, Antiflood, Welcome |
| **🧙‍♂️ RPG** | Sistema de RPG completo e imersivo | 10 Classes, PvP, Dungeons, Guilds, Pets |
| **🥳 Diversão** | Entretenimento e interações | Ship, Chance, Memes, Top5, Casal |
| **🎮 Jogos** | Mini-games divertidos | Jogo da Velha, Quiz, Forca, Blackjack |
| **💝 Figurinha** | Criação de stickers | Converter imagem/vídeo/gif em figurinha |
| **🎶 Play** | Sistema de música e vídeo | YouTube, Spotify, Lyrics, Shazam |
| **📥 Downloads** | Baixar conteúdo de várias plataformas | YouTube, Instagram, TikTok, Facebook |
| **🎟️ Suporte** | Sistema de tickets e ajuda | Reportar bugs, sugestões, avaliações |
| **🔱 Dono** | Comandos exclusivos do criador | Broadcast, Ban Global, Eval, Premium |

</div>

---

## 🎮 Sistema RPG - O Coração do Izumi

<details>
<summary><b>🗡️ Clique para ver todos os recursos do RPG</b></summary>

### 🌟 Classes Disponíveis
- ⚔️ **Guerreiro** - Tank com alto dano físico
- 🔮 **Mago** - Especialista em magia destrutiva
- 🏹 **Arqueiro** - Ataque à distância preciso
- 🗡️ **Assassino** - Críticos devastadores
- 🛡️ **Paladino** - Tank e suporte divino
- 💀 **Necromante** - Magia sombria e invocações
- ⛪ **Clérigo** - Suporte e cura poderosa
- 🪓 **Berseker** - Dano brutal sem controle
- 🌿 **Druida** - Magia da natureza
- 🎭 **Ladino** - Sorte e roubo de itens

### 🎯 Sistemas Principais
- 📊 **100 Níveis de Progressão**
- ⚔️ **Sistema de Combate Tático** (PvE e PvP)
- 🏰 **6 Dungeons Épicas** (Fácil → Impossível)
- 👥 **Sistema de Guilds** (Wars, Raids, Rankings)
- 🐾 **Sistema de Pets** (Evolução, Skills, Treino)
- 💍 **Casamento entre Players**
- 🛠️ **Craft & Profissões** (Ferreiro, Alquimista, etc)
- 💎 **Sistema de Encantamento**
- 📜 **Quests Épicas** (História, Diárias, Semanais)
- 🏆 **Rankings Globais**
- 🎪 **Eventos Especiais**
- ⭐ **Sistema de Prestígio**

### 🎁 Raridades de Itens
```
⚪ Comum → 🟢 Incomum → 🔵 Raro → 🟣 Épico → 🟠 Lendário → 🔴 Mítico → 🟡 Divino
```

</details>

---

## 🚀 Instalação

<details>
<summary><b>📋 Pré-requisitos</b></summary>

<br>

Você precisa ter instalado:

- 📦 [Node.js](https://nodejs.org/) v16 ou superior
- 📱 [Git](https://git-scm.com/)
- 🗄️ [MongoDB](https://www.mongodb.com/) (ou conta no MongoDB Atlas)
- 📲 WhatsApp instalado no celular
- 💻 Termux (Android) ou Terminal (PC/Linux)

</details>

<details>
<summary><b>📱 Instalação no Termux (Android)</b></summary>

<br>

```bash
# 1. Atualizar pacotes do Termux
pkg update && pkg upgrade

# 2. Instalar dependências necessárias
pkg install git nodejs-lts ffmpeg imagemagick yarn

# 3. Clonar o repositório
git clone https://github.com/seu-usuario/izumi-bot.git

# 4. Entrar na pasta do projeto
cd izumi-bot

# 5. Instalar dependências do projeto
npm install
# ou
yarn install

# 6. Configurar variáveis de ambiente
cp .env.example .env
nano .env
# Edite as configurações necessárias

# 7. Iniciar o bot
npm start
```

</details>

<details>
<summary><b>💻 Instalação no PC/VPS (Windows/Linux)</b></summary>

<br>

```bash
# 1. Clonar o repositório
git clone https://github.com/seu-usuario/izumi-bot.git

# 2. Entrar na pasta
cd izumi-bot

# 3. Instalar dependências
npm install
# ou
yarn install

# 4. Instalar FFmpeg (Windows)
# Baixe em: https://ffmpeg.org/download.html
# Adicione ao PATH do sistema

# 4. Instalar FFmpeg (Linux)
sudo apt update sudo apt install ffmpeg

# 5. Configurar .env
cp .env.example .env
nano .env  # ou use seu editor favorito

# 6. Iniciar o bot
npm start
```

</details>


<details>
<summary><b>📲 Primeira Execução</b></summary>

<br>

1. **Execute o bot:** `npm start`
2. **Escaneie o QR Code** com seu WhatsApp:
   - Abra o WhatsApp
   - Toque em **⋮** (menu) > **Aparelhos conectados**
   - Toque em **Conectar um aparelho**
   - Escaneie o QR Code que apareceu no terminal

3. **Pronto!** 🎉 O Izumi-Bot está online!

</details>

---

## 📚 Como Usar

<details>
<summary><b>🎯 Comandos Básicos</b></summary>

<br>

```bash
# Ver menu principal
!menu

# Ver menu específico
!menuadm          # Comandos de administração
!menurpg          # Sistema RPG completo
!menudiversao     # Entretenimento
!menujogos        # Mini-games
!menufigurinha    # Criar stickers
!menuplay         # Música e vídeo
!menudownloads    # Downloads
!menusuporte      # Ajuda e suporte
!menudono         # Apenas para o dono

# Ajuda sobre comando específico
!ajuda comando
```

</details>

<details>
<summary><b>🧙‍♂️ Começar no RPG</b></summary>

<br>

```bash
# 1. Registrar-se
!registrar

# 2. Ver seu perfil
!perfil

# 3. Escolher classe
!classe guerreiro
# Opções: guerreiro, mago, arqueiro, assassino, paladino,
#         necromante, clerigo, berseker, druida, ladino

# 4. Começar a aventura!
!batalhar          # Lutar contra monstros
!daily             # Recompensa diária
!trabalhar         # Ganhar gold
!quest             # Ver missões disponíveis
```

</details>

<details>
<summary><b>🎮 Exemplos de Uso</b></summary>

<br>

```bash
# 📥 Downloads
!play Izumi Sagiri theme             # Baixar música
!instagram https://instagram.com/... # Baixar post do Instagram
!tiktok https://tiktok.com/@...      # Baixar vídeo TikTok

# 💝 Figurinhas
!sticker                             # Responder a uma imagem
!attp Olá Mundo                      # Texto animado

# 🎮 Jogos
!quiz                                # Quiz de conhecimentos
!velha @user                         # Jogo da velha
!ppt pedra                          # Pedra, papel ou tesoura

# 🥳 Diversão
!ship @user1 @user2                  # Calcular compatibilidade
!gay @user                           # Porcentagem aleatória
!meme                                # Meme aleatório

# 👑 Admin (Apenas admins)
!ban @user                           # Banir membro
!antilink on                         # Ativar antilink
!marcar Reunião importante!          # Marcar todos
```

</details>

<details>
<summary><b>🎨 Menus Estilizados</b></summary>

<br>

**🌸 Exemplo do Menu Principal:**

```
╭═════════════════━╮
║•⪩ 𝘿𝘼𝙏𝘼: Sábado, 01/02/2025            
║•⪩ 𝙃𝙊𝙍𝘼: 15:30
║•⪩ 𝙐𝙎𝙐𝘼́𝙍𝙄𝙊: @user
║•⪩ 𝙂𝙍𝙐𝙋𝙊: Nome do Grupo
┝═════════════════━╯
║ ╭══════•⪩ 𝐌𝐄𝐍𝐔𝐒
║ ┃⏤͟͟͞͞ ⩺👑 !𝑴𝒆𝒏𝒖 𝑨𝒅𝒎
║ ┃⏤͟͟͞͞ ⩺🧙‍♂️ !𝑴𝒆𝒏𝒖 𝑹𝒑𝒈
║ ┃⏤͟͟͞͞ ⩺🥳 !𝑴𝒆𝒏𝒖 𝑫𝒊𝒗𝒆𝒓𝒔𝒂̃𝒐
║ ┃⏤͟͟͞͞ ⩺🎮 !𝑴𝒆𝒏𝒖 𝑱𝒐𝒈𝒐𝒔
║ ┃⏤͟͟͞͞ ⩺💝 !𝑴𝒆𝒏𝒖 𝑭𝒊𝒈𝒖𝒓𝒊𝒏𝒉𝒂
║ ┃⏤͟͟͞͞ ⩺🎶 !𝑴𝒆𝒏𝒖 𝑷𝒍𝒂𝒚
║ ┃⏤͟͟͞͞ ⩺📥 !𝑴𝒆𝒏𝒖 𝑫𝒐𝒘𝒏𝒍𝒐𝒂𝒅𝒔
║ ┃⏤͟͟͞͞ ⩺🎟️ !𝑴𝒆𝒏𝒖 𝑺𝒖𝒑𝒐𝒓𝒕𝒆
║ ┃⏤͟͟͞͞ ⩺🔱 !𝑴𝒆𝒏𝒖 𝑫𝒐𝒏𝒐
║ ╰══════════════〢
╚══════════════〢

💡 Digite !ajuda <comando> para mais informações
```

</details>

---

## 🛠️ Tecnologias Utilizadas

<details>
<summary><b>📦 Stack Completo</b></summary>

<br>

<div align="center">

| Tecnologia | Versão | Uso |
|:---:|:---:|:---|
| ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) | v18+ | Runtime JavaScript |
| ![Baileys](https://img.shields.io/badge/Baileys-25D366?style=flat&logo=whatsapp&logoColor=white) | Latest | Conexão WhatsApp |
| ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) | v6+ | Banco de dados |
| ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat&logo=ffmpeg&logoColor=white) | Latest | Processamento de mídia |
| ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white) | Latest | Requisições HTTP |

</div>

</details>

<details>
<summary><b>📁 Estrutura do Projeto</b></summary>

<br>

```
izumi-bot/
├── 📂 src/
│   ├── 📂 commands/      # Todos os comandos organizados
│   ├── 📂 rpg/           # Sistema RPG completo
│   ├── 📂 handlers/      # Gerenciadores de eventos
│   ├── 📂 database/      # Models e controllers
│   ├── 📂 utils/         # Utilitários e helpers
│   └── 📂 config/        # Configurações
├── 📂 data/              # Dados salvos (JSON/DB)
├── 📂 assets/            # Imagens, fontes, áudios
├── 📂 logs/              # Logs do sistema
├── 📂 auth_info/         # Sessão do WhatsApp
├── 📄 index.js           # Arquivo principal
├── 📄 package.json       # Dependências
└── 📄 .env               # Variáveis de ambiente
```

</details>

---

## 🐛 Reportar Bugs

<details>
<summary><b>🔧 Encontrou um problema?</b></summary>

<br>

Encontrou um bug? Use o comando `!bug` no bot ou abra uma [Issue](https://github.com/KDSjohhn-KJ/izumi-bot/issues) no GitHub!

**Como reportar:**
1. Descreva o problema
2. Passos para reproduzir
3. Screenshots (se possível)
4. Versão do bot

</details>

---

## 💎 Sistema Premium

<details>
<summary><b>✨ Quer benefícios exclusivos?</b></summary>

<br>

Adquira o Premium e aproveite!

### Benefícios:
- ✨ Sem cooldown em comandos
- 🎮 +15% XP e Gold no RPG
- 📦 +20% Drop Rate
- 🎨 Badge exclusiva
- 🎯 Comandos Premium
- ⚡ Prioridade no suporte

**Contato:** [WhatsApp](https://wa.me/+5541996367048)

</details>

---

## 📞 Suporte

<details>
<summary><b>💬 Precisa de ajuda?</b></summary>

<br>

Entre em contato através de:

- 📱 **WhatsApp:** [Clique aqui](https://wa.me/+5541996367048)
- 💬 **Grupo do Bot:** [Entrar](https://chat.whatsapp.com/https://chat.whatsapp.com/EV30YiFCaTxFQS8LaN7yK2?mode=gi_t)
- 🐛 **Issues:** [GitHub Issues](https://github.com/seu-usuario/izumi-bot/issues)
- 📧 **Email:** seu-email@exemplo.com

</details>

---

## 📜 Licença

<details>
<summary><b>⚖️ Informações Legais</b></summary>

<br>

Este projeto está sob licença. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

</details>

---

## ❤️ Agradecimentos

- 🌸 **Izumi Sagiri** - Inspiração para o bot
- 👥 **Comunidade Baileys** - Pela incrível biblioteca
- 👨‍💻 **Equipe** - Por tornarem o projeto realidade
- 💖 **Você** - Por usar o Izumi-Bot!

---

## ⭐ Estatísticas

<div align="center">

![GitHub Issues](https://img.shields.io/github/issues/KDSjohn-KJ/izumi-bot)
![GitHub License](https://img.shields.io/github/license/KDSjohhn-KJ/izumi-bot)

</div>

---

## 👨‍💻 Desenvolvedor

<div align="center">

### 🌸 Criado com 💖 por [KDSjohn-KJ]

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KDSjohn-KJ)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/KDSjohhn-KJ)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/cwb._kj)

</div>

---

<div align="center">

### 🌟 Se gostou do projeto, deixe uma ⭐!

**"N-não é como se eu quisesse sua estrela ou algo assim...!"** - Izumi 💝

---

**© 2025 Izumi-Bot | Todos os direitos reservados**

*Feito com Node.js, café e muito amor* ☕💖

</div>
