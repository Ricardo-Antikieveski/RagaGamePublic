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
- ⏱️ Gerenciamento de **tempo e deltaTime**
- 🧩 Arquitetura baseada em **interfaces e injeção de dependência**
- 🔄 Engine em formato **DLL**, com bibliotecas separadas por sistema (`Graphics`, `Input`, `Time`, etc.)

---

## 🧱 Estrutura Modular

| Módulo      | Descrição                                     |
|-------------|-----------------------------------------------|
| `Graphics`  | Criação de janelas, suporte a renderização    |
| `Input`     | Captura de teclado e mouse via WinAPI         |
| `Time`      | DeltaTime, FPS, timers escaláveis             |
| `EngineCore`| Núcleo da engine e gerenciamento dos módulos  |
| `Game`      | Executável principal que consome a engine     |

---

## 📸 Imagens

> *(https://drive.google.com/drive/folders/1jjGHlWPCjYo_GG0GlXdX8bBTM902-I7W?usp=sharing)*

---

## 🔒 Sobre o código

O código-fonte completo está hospedado em repositório privado.  
Este repositório serve como vitrine e documentação do progresso da engine.

---

## 📍 Status Atual

- ✅ Sistema de Janela (Graphics::Window)
- ✅ Núcleo funcional da Engine (`EngineCore`)
- 🚧 Em desenvolvimento: `InputManager`, `Time`, `Renderer`
- 🧪 Testes e protótipos sendo realizados no módulo `Game`

---

## 📚 Objetivo do projeto

- Aprofundar o conhecimento em **programação de baixo nível**
- Simular uma engine real de mercado com separação em `.dll` / `.lib` / `.exe`
- Explorar **design patterns profissionais** no C++
- Criar um FPS com recursos como lobby, partidas online e loja

---

## 👤 Autor

**Ricardo Antikieveski**  
📧 antikieveski.ricardo@gmail.com
📷 [@_ricardoan](https://www.instagram.com/_ricardoan/)  
🔒 Projeto pessoal com fins de aprendizado e portfólio

---

## 🗓️ Roadmap (curto prazo)

- [x] Janela criada com suporte a mensagens
- [ ] Integração do `InputManager`
- [ ] Sistema de tempo completo com FPS e delta
- [ ] Começar estrutura do `Renderer` com DirectX
- [ ] Projeto `Game.exe` usando apenas a `RagaEngine.dll`

---

## 📝 Licença

Este projeto está sob licença privada.  
Para mais informações, entre em contato.

