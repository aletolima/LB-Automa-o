# LB Automação Industrial

Site de demonstração criado especialmente para você. Este projeto foi preparado para ser **fácil de usar, editar e publicar**, mesmo que você seja iniciante em tecnologia.

---

## ✅ O que já está pronto
- Página inicial moderna com vídeo de fundo, animações e design profissional
- Seção dedicada à **IHM Allen-Bradley 7\"** com galeria de imagens (clique para ampliar)
- Área **Experiência Interativa** com modelo 3D rotacionável
- Layout responsivo (funciona em celular, tablet e computador)
- Pronto para receber **suas imagens e vídeos reais**

---

## 📁 Estrutura de Pastas

```
lb-automacao-industrial/
  components/
    HomePage.jsx     -> Todo o layout principal
  pages/
    _app.js          -> Carrega estilos globais
    index.js         -> Renderiza a Home
  public/
    images/          -> Coloque suas imagens aqui
    videos/          -> Coloque seus vídeos aqui
    ihm.png          -> Ícone placeholder
    clp.png          -> Ícone placeholder
    delta.png        -> Ícone placeholder
  styles/
    globals.css      -> Tailwind + estilos globais
  package.json       -> Dependências e scripts
  tailwind.config.js -> Configuração Tailwind
  postcss.config.js  -> Requerido pelo Tailwind
  next.config.js     -> Configuração Next.js
```

---

## 🛠 Pré-requisitos

Antes de começar, instale no seu computador:

1. **Node.js** (versão 18 ou mais recente)  
   Baixe em: https://nodejs.org
2. (Opcional) **Visual Studio Code** (editor de código, recomendado)  
   Baixe em: https://code.visualstudio.com

---

## 🚀 Como Rodar o Site no Seu Computador

1. **Extraia o arquivo ZIP** em uma pasta (por exemplo: `C:\lb-automacao` no Windows).
2. Abra um terminal dentro dessa pasta.
3. Rode o comando para instalar as dependências:
   ```bash
   npm install
   ```
4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```
5. Abra o navegador e acesse:
   ```
   http://localhost:3000
   ```

Pronto! Você verá seu site funcionando localmente.

---

## 🖼 Inserindo SUAS Imagens

Substitua os arquivos dentro da pasta **`public/images`**:

| Como está no código | O que colocar | Descrição |
|---|---|---|
| `ab-ihm7-front.jpg` | Foto frontal real da IHM Allen-Bradley 7\" | imagem grande |
| `ab-ihm7-runtime-overview.jpg` | print/screenshot | Tela principal |
| `ab-ihm7-runtime-alarms.jpg` | print | Tela de alarmes |
| `ab-ihm7-runtime-trends.jpg` | print | Tela de gráficos |

> Dica: mantenha os mesmos nomes dos arquivos para não precisar mexer no código.

---

## 🎥 Inserindo Vídeos

Coloque seus vídeos na pasta **`public/videos`** e use estes nomes:

- `automacao.mp4` → vídeo de fundo da Home
- `ab-ihm7-demo.mp4` → vídeo mostrando a IHM 7\" em funcionamento

Arquivos grandes podem deixar o site pesado. Se possível, use vídeos curtos (5–15s) ou reduza o tamanho com https://www.handbrake.fr.

---

## ✏️ Como Editar Textos

Todos os textos estão no arquivo:  
**`components/HomePage.jsx`**

Abra esse arquivo no VS Code e procure pelas frases. Mude o texto entre as aspas que está dentro dos elementos.

Exemplo:
```jsx
<h1 className="text-2xl font-bold text-blue-400">LB Automação Industrial</h1>
```
Troque para:
```jsx
<h1 className="text-2xl font-bold text-blue-400">Seu Novo Título Aqui</h1>
```

Salvou? O site recarrega sozinho quando estiver rodando `npm run dev`.

---

## 📲 Botão de WhatsApp

No final do site tem um botão com link:
```
https://wa.me/5592999999999
```
Troque **5592999999999** pelo número real do seu WhatsApp (código do país + DDD + número).

---

## 🌐 Como Publicar o Site na Internet (Vercel)

**Vercel** é o jeito mais fácil:

1. Crie uma conta em https://vercel.com (use Gmail se quiser).
2. Faça upload do projeto (arraste a pasta ou conecte com GitHub).
3. A Vercel automaticamente instala e publica.
4. Você receberá um endereço tipo: `https://lb-automacao.vercel.app`

> Depois você pode colocar um domínio próprio (ex.: `lbautomacao.com.br`).

---

## ❓ Dúvidas Comuns

**O site abre mas sem imagens. Por quê?**  
→ Verifique se os arquivos estão em `public/images` e os nomes batem com o código.

**Erro de módulo não encontrado?**  
→ Rode `npm install` antes de `npm run dev`.

**Quero mudar cores.**  
→ Edite as classes Tailwind (ex.: `text-blue-400`, `bg-gray-900`, etc.).

---

## 📞 Ajuda

Se travar em alguma etapa, me diga o que aconteceu (de preferência copie a mensagem de erro) e eu te guio.

---

Feito com carinho para você em 2025-07-22 14:39:34 (UTC). Vamos colocar sua LB Automação Industrial online! 🚀
