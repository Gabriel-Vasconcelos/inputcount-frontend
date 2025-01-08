# InputCount Frontend

O **InputCount** é um sistema web simples que permite aos usuários enviar valores a um servidor e visualizar o número de vezes que cada valor foi enviado. Este repositório contém o código referente à interface de usuário (frontend) do projeto, desenvolvido utilizando **HTML5**, **TailwindCSS** e **JavaScript Puro**.

![image](https://github.com/user-attachments/assets/60a2dc13-dc17-48e2-921f-8815cd8a3cdb)

## 🧩 Visão Geral do Projeto
O projeto InputCount é dividido em duas partes principais:
- **Frontend:** Interface web que permite ao usuário inserir um valor em uma caixa de texto e enviá-lo para o backend. Após o envio, o número de vezes que o valor foi recebido pelo servidor é exibido na interface.
- **Backend:** Servidor desenvolvido em Node.js que recebe os valores enviados pelo frontend, armazena a contagem de cada valor e retorna essa informação ao frontend.

> ⚠️ Nota: Este repositório é apenas para o código do frontend. O backend está disponível em um repositório separado:
> [🔗 InputCount Backend](https://github.com/gabriel-vasconcelos/inputcount-backend)

## 🎥 Vídeo do Projeto
https://github.com/user-attachments/assets/206eb209-3076-416b-97d7-09f4b467b25d


## 📚 Tecnologias Utilizadas
- HTML
- CSS (TailwindCSS)
- JavaScript Puro (Vanilla JS)

## 🚀 Funcionalidades do Frontend
- Caixa de texto para o usuário inserir um valor
- Botão que envia o valor ao backend via requisição HTTP (fetch API)
- Exibição do número de vezes que o valor foi enviado ao servidor

## 📂 Como Executar o Projeto
### 🔧 Passo 1: Clone o repositório:
Execute o seguinte comando no terminal para clonar o repositório:
```bash
git clone https://github.com/gabriel-vasconcelos/inputcount-frontend.git
cd inputcount-frontend
```

### 🌐 Passo 2: Executar o Frontend
```bash
yarn && yarn run init
```
Por fim, abra o arquivo ```index.html``` diretamente no seu navegador para visualizar a interface.

## 🔗 Repositórios Relacionados
- 🔄 Backend do InputCount: https://github.com/gabriel-vasconcelos/inputcount-backend
