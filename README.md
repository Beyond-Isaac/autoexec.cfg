# 🎮 Left 4 Dead 2 – Autoexec & Personal CFG

Este repositório contém minha **configuração pessoal (CFG)** para **Left 4 Dead 2**, focada em **performance**, **baixo input lag**, **estabilidade de rede** e **experiência limpa de jogo**.

O projeto usa um **autoexec.cfg** que carrega automaticamente todas as configurações e arquivos personalizados sempre que o jogo inicia.

---

## 📁 Estrutura do projeto

cfg/

├── autoexec.cfg → Configuração principal

├── binds.cfg → Binds personalizados

├── CFG_NoDeath.cfg → Configurações extras

└── CFG_High_Graphics.cfg → Gráficos mais altos (opcional)

---

## ⚙️ O que é o autoexec.cfg?

O `autoexec.cfg` é um arquivo que o jogo executa **automaticamente ao iniciar**, aplicando todas as configurações definidas nele, como:

- Rede (rate, tick, interp)
- Mouse (raw input, aceleração desativada)
- Áudio
- FOV
- FPS
- HUD limpo
- Execução de outros arquivos `.cfg`

Resultado: **abriu o jogo, tudo já está configurado**.

<img width="694" height="437" alt="image" src="https://github.com/user-attachments/assets/5a4a993c-273b-45e6-9793-2686826fd2dd" />



---

## 📥 Instalação

### 1️⃣ Acesse a pasta do jogo

Steam\steamapps\common\Left 4 Dead 2\left4dead2\cfg


### 2️⃣ Copie os arquivos

Coloque **todos os arquivos `.cfg` deste repositório** dentro da pasta `cfg`.

Exemplo final:

left4dead2/cfg/autoexec.cfg
left4dead2/cfg/binds.cfg
left4dead2/cfg/CFG_NoDeath.cfg

---

## ▶️ Ativando o autoexec

### ✔️ Forma automática (recomendada)

O `autoexec.cfg` é executado automaticamente ao iniciar o jogo.  
Não é necessário nenhum comando.

### 🔧 Forma manual (para teste)

Dentro do jogo:

1. Abra o console (`~`)
2. Digite:

```cfg
exec autoexec

Se não aparecer erro no console, o autoexec está funcionando corretamente.
