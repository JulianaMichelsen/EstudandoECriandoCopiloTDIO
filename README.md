
# Criando um Copilot com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

Este guia apresenta um passo a passo para criar e personalizar um Copilot com fluxo de conversa customizado, utilizando o [Microsoft Copilot Studio](https://copilotstudio.microsoft.com).

---

## 🆕 Criando um Copilot do Zero

1. **Acesse o Microsoft Copilot Studio**
   Vá para [copilotstudio.microsoft.com](https://copilotstudio.microsoft.com) e faça login com sua conta Microsoft.

2. **Crie um novo agente Copilot**

   * Clique em **"Criar"** para iniciar um novo agente.
   * **Descreva o objetivo** do agente: informe o que ele deve fazer.
   * **Dê um nome** ao seu novo Copilot.
   * **Defina o comportamento do agente** (prompt de sistema): explique como ele deve responder aos usuários.
   * Clique em **"Criar"** para finalizar a criação.

---

## 🛠️ Customizando um Tópico

1. **Acesse a aba "Tópicos"** e clique em **"Novo tópico"** > **"Em branco"**.
2. **Configure frases de gatilho**: escreva exemplos de frases que os usuários podem dizer para ativar o tópico.
3. **Adicione uma nova ação**:

   * Escolha **"Ações avançadas"**.
   * Selecione **"Respostas generativas"**.
   * Em **"Entrada"**, defina como `activity.text` para capturar o que o usuário digitar.
4. **Adicione uma mensagem final** para encerrar o tópico com clareza (ex: “Posso te ajudar com mais alguma coisa?”).
5. **Clique em "Salvar"** para manter as alterações.

---

## ⚠️ Personalizando a Mensagem de Erro do Tópico

1. Vá para a seção **"Fontes de dados"** do agente.
2. Clique em **"Editar"**.
3. **Desative** a opção **"Permitir que a IA use conhecimentos gerais"**.
4. Clique em **"Salvar"**.

Isso fará com que, ao não encontrar uma resposta, o agente use mensagens personalizadas em vez de recorrer à IA genérica da Microsoft.

---

## 🎛️ Ajustando a Qualidade da Resposta com GenAI

É possível controlar o nível de criatividade e precisão das respostas geradas com inteligência artificial:

* Acesse a ação de **Resposta Generativa** dentro de um tópico.
* Clique em **"Configurações avançadas"**.
* Ajuste os parâmetros como:

  * **Temperatura** (criatividade da resposta): valores mais altos (ex: 1.0) deixam as respostas mais criativas; valores baixos (ex: 0.2) tornam as respostas mais objetivas.
  * **Comprimento máximo** da resposta.
  * **Presença e frequência de penalização**, se aplicável.

---

## ✅ Dicas Finais

* Use mensagens claras e objetivas nos tópicos.
* Teste cada fluxo de conversa com diferentes frases para garantir que os gatilhos estejam funcionando corretamente.
* Utilize **variáveis** para armazenar dados temporários da conversa.
* Explore **conectores** e **APIs externas** para expandir as funcionalidades do Copilot.


