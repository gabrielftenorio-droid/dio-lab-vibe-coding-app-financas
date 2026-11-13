# 💸 Trilha do Bom Bolso - App de Finanças Pessoais com Vibe Coding

> **Projeto desenvolvido como entrega do desafio prático da [DIO (Digital Innovation One)](https://dio.me)**  
> 🚀 **App em Produção:** [trilha-do-bom-bolso.lovable.app](https://trilha-do-bom-bolso.lovable.app)  
> 🛠️ **Ferramenta utilizada:** [Lovable.dev](https://lovable.dev) + Engenharia de Prompt / Vibe Coding

---

## 📌 1. Resumo do Aplicativo

O **Trilha do Bom Bolso** é um aplicativo de organização financeira pessoal projetado com uma abordagem *chat-first*. O objetivo é eliminar planilhas complexas e formulários cansativos, permitindo que qualquer pessoa controle suas finanças por meio de conversas naturais com o **Tostão**, o assistente virtual amigável do app.

O produto foi pensado especialmente para **jovens e iniciantes** em gestão financeira, adotando um tom leve, descontraído e acessível, guiado pelos princípios de **Design Universal** e **Acessibilidade Digital**.

### 🌟 Principais Funcionalidades:
- **Agente Virtual "Tostão":** Uma mascote amigável que orienta o usuário passo a passo com linguagem humana e didática.
- **Registro por Linguagem Natural:** O usuário registra despesas e receitas apenas digitando no chat (ex.: *"Gastei 11,94 com Uber"* ou *"Gastei 491,47 com o financiamento da Caixa"*).
- **Classificação e Feedback Instantâneo:** O assistente identifica automaticamente a categoria (Transporte, Moradia, etc.) e confirma o registro na hora.
- **Dicas do Tostão & Insights:** Análise preventiva de gastos (ex.: alertar qual categoria está pesando mais no mês).
- **Dashboard Visual e Descomplicado:** Cartões claros de *Entrou*, *Saiu* e *Sobrou*, acompanhados de gráficos de distribuição simples de entender.
- **Metas Financeiras Acompanhadas:** Definição e visualização de progresso para objetivos reais (reserva de emergência, viagens, quitação de dívidas).

---

## 📸 2. Demonstração e Telas do Aplicativo

Confira abaixo as telas reais do MVP gerado no [Lovable](https://lovable.dev) a partir do PRD:

### 🚀 Onboarding Guiado e Acessível
O aplicativo recebe o usuário de forma calorosa, perguntando como prefere ser chamado e qual é seu objetivo financeiro prioritário:

| 1. Apresentação do Tostão | 2. Escolha de Objetivo Inicial |
| :---: | :---: |
| ![Passo 1 Onboarding](assets/01-onboarding-nome.jpg) | ![Passo 2 Onboarding](assets/02-onboarding-objetivo.jpg) |

---

### 💬 Experiência Conversacional (Chat-First)
Sem formulários manuais: o usuário pode usar sugestões rápidas ou digitar do seu jeito, e o assistente classifica a transação automaticamente:

| Tela Inicial do Chat | Interação Real e Classificação Automática |
| :---: | :---: |
| ![Chat Inicial](assets/03-chat-inicial.png) | ![Chat com Registros](assets/04-chat-interacao.png) |

---

### 📊 Painel Geral (Dashboard) e Acompanhamento de Metas
Visão consolidada das finanças com gráficos intuitivos, dicas personalizadas e controle de metas:

| Painel com Gráficos e "Dicas do Tostão" | Acompanhamento Visual de Metas |
| :---: | :---: |
| ![Painel e Métricas](assets/05-dashboard-painel.png) | ![Gestão de Metas](assets/06-metas.png) |

---

## 📄 3. Prompt Final (PRD Completo)

Abaixo está o documento de requisitos (**Product Requirements Document**) utilizado como briefing estratégico para guiar a IA na geração do MVP:

<details>
<summary><b>Clique aqui para visualizar o PRD completo</b></summary>

```markdown
# PRD - Assistente de Finanças Pessoais Conversacional

## 1. Visão do Produto
Criar um aplicativo de finanças pessoais baseado em conversação (chat-first), permitindo que usuários registrem despesas, receitas, acompanhem metas financeiras e recebam orientações de economia por meio de linguagem natural.
O objetivo é substituir formulários complexos e planilhas por uma experiência simples, intuitiva e conversacional.
O produto deve seguir os princípios de Design Universal e Acessibilidade desde o MVP, priorizando simplicidade, clareza e inclusão, para que pessoas com diferentes níveis de conhecimento financeiro, experiência digital e necessidades de acessibilidade consigam utilizá-lo com autonomia e confiança.

---

## 2. Problema
Muitas pessoas desejam organizar suas finanças, mas abandonam rapidamente os aplicativos financeiros existentes devido a:
- Excesso de entrada manual de dados;
- Interfaces complexas;
- Pouca personalização;
- Baixo engajamento ao longo do tempo.
Como consequência, perdem controle sobre seus gastos e encontram dificuldades para atingir seus objetivos financeiros.

---

## 3. Objetivo do Produto
Permitir que qualquer pessoa consiga controlar suas finanças conversando com um assistente virtual, sem precisar aprender conceitos financeiros complexos ou utilizar planilhas.

### Objetivos de Negócio
- Aumentar a frequência de registro financeiro.
- Melhorar o engajamento dos usuários iniciantes.
- Criar uma experiência educativa e acessível.
- Gerar recomendações financeiras úteis e personalizadas.
- Reduzir o atrito de entrada de dados financeiros.

---

## 4. Público-Alvo
### Persona Principal
Pessoas iniciantes em organização financeira.

### Características
- Entre 20 e 45 anos;
- Utilizam smartphone diariamente;
- Nunca utilizaram aplicativos financeiros ou desistiram deles;
- Desejam economizar dinheiro e entender melhor seus hábitos financeiros.

### Principais Dores
- Esquecem de registrar gastos;
- Não sabem categorizar despesas;
- Têm dificuldade para interpretar relatórios financeiros;
- Não acompanham metas financeiras de forma consistente.

---

## 5. Proposta de Valor
"Organize suas finanças simplesmente conversando."
O aplicativo atua como um Agente Financeiro Virtual capaz de:
- Entender linguagem natural;
- Registrar receitas e despesas automaticamente;
- Organizar transações em categorias;
- Acompanhar metas financeiras;
- Fornecer insights e sugestões de economia.

---

## 6. Princípios de Design
### Design Universal
O produto deve ser projetado para ser utilizado pelo maior número possível de pessoas, independentemente de idade, escolaridade, nível de alfabetização financeira, familiaridade com tecnologia ou limitações visuais, motoras, auditivas ou cognitivas.

### Linguagem Simples
- Evitar jargões financeiros;
- Utilizar frases curtas e claras;
- Explicar conceitos de forma didática;
- Priorizar comunicação amigável (ex.: trocar "déficit no fluxo de caixa" por "você gastou mais do que recebeu").

### Interface Inclusiva
- Alto contraste e tipografia legível;
- Botões acessíveis e navegação consistente;
- Hierarquia visual clara.

### Múltiplas Formas de Interação e Tolerância a Erros
- Entrada por texto, voz e sugestões rápidas;
- Compreensão flexível de mensagens (ex: "Gastei 20 no Uber", "Paguei vinte reais de transporte", "Usei R$20 para ir ao trabalho").

---

## 7. Funcionalidades do MVP
1. **Registro de Gastos via Chat:** Identificação automática de valor, categoria, data e tipo.
2. **Classificação Automática:** Categorias iniciais (Alimentação, Transporte, Moradia, Saúde, Lazer, Educação, Compras, Outros).
3. **Cadastro de Receitas:** Registro natural de salários e rendas extras.
4. **Metas Financeiras:** Criação de objetivos com valor-alvo, progresso percentual e acompanhamento.
5. **Agente Financeiro:** Geração de alertas e sugestões de economia.
6. **Dashboard Financeiro:** Resumo de saldo, receitas, despesas e distribuição por categoria.

---

## 8. Telas do MVP
- **Tela 1 - Onboarding:** Apresentação e objetivo principal.
- **Tela 2 - Chat Financeiro:** Interface central conversacional.
- **Tela 3 - Dashboard:** Resumo visual das métricas financeiras.
- **Tela 4 - Metas Financeiras:** Acompanhamento das metas.
- **Tela 5 - Perfil e Configurações:** Preferências e acessibilidade.

---

## 9. Métricas de Sucesso & Critérios de Validação
- Usuários conseguem registrar gastos sem necessidade de treinamento.
- O chat é a principal via de interação.
- Alta precisão na categorização automática de transações.
- Retenção e retorno de uso após a primeira semana.
```

</details>

---

## 🧠 4. Reflexão sobre o Processo de Vibe Coding

### 🟢 O que funcionou bem?
- **O impacto de um PRD bem estruturado:** A estruturação detalhada de personas, fluxos e regras de negócio antes de pedir a geração do código permitiu que a IA gerasse uma aplicação concisa, com os componentes certos e sem alucinações de escopo.
- **Agilidade na criação do MVP:** A velocidade para transformar requisitos de produto em uma aplicação web totalmente responsiva e navegável através do Lovable superou qualquer fluxo convencional de prototipagem.
- **Aderência ao tom descontraído:** A IA compreendeu perfeitamente a diretriz de fugir do "economês", criando uma interface amigável e acessível para iniciantes.

### 🟡 O que não funcionou como o esperado de início?
- **Refinamento de detalhes específicos:** Pequenos ajustes visuais e alinhamentos de componentes exigiram comandos extras mais diretos e descritivos.
- **Otimização do limite diário:** No plano gratuito de ferramentas como o Lovable, cada interação conta. Foi necessário pensar criticamente antes de cada prompt para evitar gastar interações com pedidos genéricos.

### 💡 O que aprendi sobre conversar com IAs?
- **A qualidade da resposta reflete a clareza da intenção:** Programar com IA (*Vibe Coding*) não significa não planejar; significa que o planejamento textual (briefing/PRD) passa a ser a peça central da engenharia de software.
- **Iterações incrementais e atômicas:** Em vez de pedir tudo de uma vez ou solicitar correções vagas, pedir alterações específicas passo a passo gera resultados muito mais consistentes.

---

## 🔗 5. Como Testar o App

1. Acesse o link da aplicação: **[trilha-do-bom-bolso.lovable.app](https://trilha-do-bom-bolso.lovable.app)**
2. Faça a etapa de boas-vindas / onboarding.
3. Teste o chat enviando frases como:
   - *"Gastei R$ 42 na padaria"*
   - *"Recebi 1500 de salário hoje"*
4. Confira a atualização das métricas no Dashboard e na aba de Metas!

---

## 👤 Autor

Desenvolvido por **Gabriel Fernandes Tenório**  
GitHub: [@gabrielftenorio-droid](https://github.com/gabrielftenorio-droid)  
Repositório forked para entrega do desafio na plataforma da **[DIO](https://dio.me)**.
