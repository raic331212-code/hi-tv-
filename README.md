# HI TV - Web IPTV Player 📺

Um reprodutor de IPTV moderno, leve e direto no navegador. Criado em um único arquivo (Single Page Application) utilizando React, Tailwind CSS e HLS.js. Ideal para rodar no GitHub Pages e ser acessado por celulares, computadores e Smart TVs.

---

## ✨ Funcionalidades

* **Leitura Local de M3U:** Carregue suas listas `.m3u` ou `.m3u8` diretamente da memória do dispositivo, evitando bloqueios de segurança (CORS) do navegador.
* **Organização Inteligente:** Separa o conteúdo automaticamente em TV Ao Vivo, Filmes e Séries com base nas informações da lista.
* **Favoritos e Histórico:** Salva seus canais favoritos e memoriza o tempo em que você parou de assistir seus filmes ou episódios.
* **Controle Parental:** Bloqueio por senha (PIN de 4 dígitos) para categorias com conteúdo adulto.
* **Dois Motores de Vídeo:** Escolha entre o motor HLS.js (recomendado para a maioria dos navegadores) e o Nativo (ideal para navegadores de Smart TVs).
* **Interface Moderna:** Design responsivo e escuro inspirado nas maiores plataformas de streaming da atualidade.

---

## 🚀 Como Hospedar no GitHub Pages

Como este aplicativo é 100% Front-end (não exige servidor ou banco de dados), ele pode ser hospedado de graça no GitHub:

1. Crie um repositório público no seu GitHub.
2. Faça o upload do arquivo do código e certifique-se de nomeá-lo como `index.html`.
3. Acesse as configurações (**Settings**) do seu repositório.
4. No menu lateral esquerdo, vá até a seção **Pages**.
5. Em *Build and deployment* > *Branch*, selecione `main` (ou `master`) e clique em **Save**.
6. Aguarde alguns minutos e o GitHub fornecerá o link do seu site no topo da página.

---

## 📂 Como Adicionar sua Lista IPTV

Ao acessar o seu site publicado, você terá as seguintes opções na tela de login:

* **Carregar Arquivo Local (Recomendado):** Permite selecionar um arquivo `.m3u` que já esteja baixado no seu celular ou computador. Essa opção funciona sempre, pois não depende da internet para fazer o download da lista e burla as restrições de rede.
* **Via Link (URL):** Útil se você tiver um link que permita o download direto da lista (é necessário que o servidor da lista tenha as políticas de CORS liberadas).

---

## 🛠️ Tecnologias Utilizadas

* **React 18** (Standalone via CDN)
* **Tailwind CSS** (via CDN para estilização rápida)
* **Babel** (Compilação do JSX no navegador)
* **HLS.js** (Motor principal para reprodução de streams M3U8)
* **LocalForage** (Armazenamento em cache para salvar progresso, favoritos e configurações)

---

> **Aviso:** Este aplicativo é apenas um reprodutor de mídia (Player). Ele não inclui, fornece ou distribui nenhum tipo de conteúdo, lista de canais ou material protegido por direitos autorais. O usuário é o único responsável por fornecer suas próprias listas de reprodução.# hi-tv-
