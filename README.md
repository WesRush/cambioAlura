# 💱 Câmbio Alura - Java Console

Este projeto é um **conversor de moedas interativo via console**, desenvolvido em **Java**, que consome uma API externa para realizar conversões em tempo real e faz parte do desafio do programa Oracle Generation One. Ele utiliza a [ExchangeRate API](https://www.exchangerate-api.com/) para buscar as taxas de câmbio atualizadas.

## 🚀 Funcionalidades

- Obtenção de taxas de câmbio atualizadas em tempo real via API;
- Interface de texto simples e intuitiva no console;
- Múltiplas opções de conversão entre moedas populares;
- Uso de `HttpClient` para requisições HTTP e `Gson` para leitura de JSON;
- Implementação com Java moderno e registros (`record`).

## 🔁 Conversões Disponíveis

Atualmente, o programa permite as seguintes conversões:

- BRL → USD (Real para Dólar Americano)
- BRL → EUR (Real para Euro)
- BRL → CAD (Real para Dólar Canadense)
- USD → BRL (Dólar Americano para Real)
- USD → EUR (Dólar Americano para Euro)
- USD → CAD (Dólar Americano para Dólar Canadense)

## 🧰 Tecnologias Utilizadas

- Java 17+
- API pública: ExchangeRate API
- `HttpClient` (Java nativo para chamadas HTTP)
- `Gson` (para desserialização do JSON)

## 🛠️ Como Executar

1. Clone o repositório:
   ```bash
   git clonehttps://github.com/WesRush/cambioAlura.git

2. Importe o projeto na sua IDE Java (ex: IntelliJ ou Eclipse);
3. Certifique-se de que você tem o `Gson` adicionado no seu projeto (via Maven, Gradle ou `.jar`);
4. Execute a classe `Main` com o menu no console;
5. Escolha a moeda base e a moeda de destino para realizar a conversão.]

## 🔐 Observação
Para funcionar corretamente, o projeto requer uma **API Key válida da ExchangeRate API.** Você pode conseguir uma gratuita em https://www.exchangerate-api.com.



