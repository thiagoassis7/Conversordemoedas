# 💱 Conversor de Moedas em Java

🎯 Um projeto simples, funcional e direto ao ponto: converta moedas em tempo real com base nas taxas mais recentes da internet!

🔗 Repositório: [github.com/thiagoassis7/Conversordemoedas](https://github.com/thiagoassis7/Conversordemoedas)

---

## 🧠 Sobre o Projeto

Este é um conversor de moedas feito em **Java**, que roda no terminal e utiliza a **ExchangeRate API** para obter as taxas de câmbio em tempo real 🌐. 

O objetivo é permitir que o usuário escolha entre diferentes opções de conversão de moeda, informe um valor e veja o resultado convertido de forma rápida e clara.

---

## 🚀 Funcionalidades

✅ Menu interativo com as seguintes opções:
1 - Dólar Americano → Real Brasileiro
2 - Real Brasileiro → Dólar Americano
3 - Peso Argentino → Real Brasileiro
4 - Real Brasileiro → Peso Argentino
5 - Euro Europeu → Real Brasileiro
6 - Real Brasileiro → Euro Europeu
7 - Sair

✅ Conexão com API externa  
✅ Conversão em tempo real  
✅ Loop contínuo até o usuário sair  
✅ Separação do código em classes organizadas  

---

## 🛠 Tecnologias Utilizadas

- ☕ Java 11+
- 🧠 [Gson](https://github.com/google/gson) – para ler os dados JSON
- 📡 Java `HttpClient` – para consumir a API
- 💻 IntelliJ IDEA – como IDE
- 🔀 Git e GitHub – para versionamento

---

## 🧩 Estrutura do Projeto
📁 Conversordemoedas/
├── Main.java # Menu e entrada do usuário
├── Conversor.java # Lógica de requisição e conversão
├── RespostaAPI.java # Mapeamento do JSON
├── gson-2.x.jar # Biblioteca do Gson adicionada manualmente

---

## ▶️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/thiagoassis7/Conversordemoedas.git
   cd Conversordemoedas
   Abra o projeto no IntelliJ IDEA.

Adicione o gson-2.x.jar ao projeto:

Vá em: File > Project Structure > Modules > Dependencies

Clique em + e selecione o JAR baixado.

Substitua a linha private static final String API_KEY = "SUA_API_KEY_AQUI" com sua chave da API gratuita do ExchangeRate.

Rode a classe Main.java.

📚 Aprendizados
Este projeto me ajudou a entender na prática:

Como ler dados do usuário com Scanner

Como criar menus interativos

Como consumir APIs externas em Java

Como ler e interpretar JSON com Gson

Como organizar código usando classes

Como usar Git e GitHub na prática

🙋‍♂️ Autor
Desenvolvido por Thiago Assis 👨‍💻
Em transição de carreira para a área de TI, focado, determinado e aprendendo algo novo todos os dias.

⭐ Se você curtiu esse projeto, não esquece de dar uma ⭐ no repositório!



