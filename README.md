# 🎮 RagaEngine

> 🧱 Uma engine modular de FPS feita em C++ com arquitetura profissional, projetada do zero usando WinAPI e DirectX.

---

## 🚀 Visão Geral

A Raga Engine é uma engine independente que está sendo desenvolvida em C++ com foco em performance, modularidade e aprendizado profundo. Inspirada em engines profissionais, seu propósito é construir jogos de tiro em primeira pessoa (FPS) com estrutura de engine própria — sem depender de motores prontos como Unity ou Unreal.

---

## 🛠️ Tecnologias

- 🔧 **C++**
- 🖼️ **WinAPI** para criação de janelas e entrada
- 🎮 Sistema próprio de **input**
- ⏱️ Gerenciamento de **tempo**, com suporte a **deltaTime**, **FPS**, **pausa** e **time scale**
- 🧩 Arquitetura baseada em **interfaces puras** e **injeção de dependência**
- 🔄 Engine em formato **DLL**, com bibliotecas separadas por sistema (`Graphics`, `Input`, `Time`, etc.)
- 🧪 Visualizador de logs real-time via `OutputDebugString` e `RagaDebugViewer`

---

## 🧱 Estrutura Modular

| Módulo        | Descrição                                                    |
|---------------|--------------------------------------------------------------|
| `Graphics`    | Criação de janelas (WinAPI), futuro suporte a renderização   |
| `Input`       | Captura de teclado e mouse via mensagens da WinAPI           |
| `Time`        | Sistema completo de tempo: deltaTime, FPS, pausa, escala     |
| `Logger`      | Centralização de logs para debug em tempo real               |
| `EngineCore`  | Núcleo da engine e gerenciamento dos módulos                 |
| `Game`        | Executável principal que consome a engine (`.dll`)           |

---

## 📸 Imagens

> 📁 [Drive com imagens e progresso](https://drive.google.com/drive/folders/1jjGHlWPCjYo_GG0GlXdX8bBTM902-I7W?usp=sharing)

---

## 🔒 Sobre o código

O código-fonte completo está hospedado em repositório privado.  
Este repositório serve como vitrine e documentação pública do progresso da engine.

---

## 📍 Status Atual

- ✅ Sistema de Janela (`Graphics::Window`) completo e redimensionamento bloqueado
- ✅ `EngineCore` com loop principal, inicialização e shutdown modular
- ✅ `InputManager` funcional (teclado e mouse via WinAPI)
- ✅ `TimerManager` com deltaTime, FPS, time scale e pause/resume
- ✅ Sistema de logs com visualizador auxiliar (`RagaDebugViewer`)
- 🚧 Em planejamento: sistema de renderização com DirectX
- 🧪 Testes ativos no módulo `Game` para validação dos subsistemas

---

## 📚 Objetivo do projeto

- Aprofundar o conhecimento em **programação de baixo nível**
- Simular uma engine real de mercado com separação em `.dll`, `.lib`, `.exe`
- Explorar **design patterns profissionais** no C++
- Criar um FPS com recursos como lobby, partidas online e loja

---

## 🗓️ Roadmap (curto prazo)

- [x] Sistema de janela com título dinâmico e redimensionamento bloqueado
- [x] `InputManager` conectado à janela (teclado + mouse)
- [x] Sistema de tempo completo com pausa e escala (time scale)
- [x] Sistema de logs com debug viewer em tempo real
- [ ] Estrutura base do `Renderer` com DirectX
- [ ] `Game.exe` utilizando exclusivamente a `RagaEngine.dll`
- [ ] Sistema de cenas e gerenciamento de estados da engine

---

## 👤 Autor

**Ricardo Antikieveski**  
📧 antikieveski.ricardo@gmail.com  
📷 [@_ricardoan](https://www.instagram.com/_ricardoan/)  
🔒 Projeto pessoal com fins de aprendizado e portfólio

---

## 📝 Licença

Este projeto está sob licença privada.  
Para mais informações, entre em contato.
