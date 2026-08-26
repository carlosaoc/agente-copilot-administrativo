# Agentes Customizados para GitHub Copilot Chat

Coleção de agentes de IA customizados para o GitHub Copilot Chat no VS Code, criados para automatizar tarefas especificas do dia a dia como estudante de Python e dados.

## Por que criei isso

Comecei a explorar como configurar agentes de IA especializados para tarefas recorrentes, ao inves de sempre reescrever o mesmo contexto em cada conversa. Cada agente abaixo tem um proposito e um "modo de pensar" proprio.

## Agentes disponiveis

### 1. Assistente Administrativo

Organiza tarefas, cria checklists e agendas, revisa documentos e identifica pendencias. Segue regras estritas: nunca inventa responsaveis, prazos ou compromissos que nao foram informados.

Arquivo: `.github/agents/assistente-administrativo.agent.md`

**Exemplo de uso:**

### 2. Revisor de Codigo Python

Revisa trechos de codigo Python, sugerindo melhorias de legibilidade, boas praticas (PEP 8) e apontando possiveis bugs, com explicacoes didaticas.

Arquivo: `.github/agents/revisor-codigo-python.agent.md`

**Exemplo de uso:**

Codigo enviado:
```python
def calcula(a,b):
    x = a+b
    y = a-b
    z = a*b
    w = a/b
    return x,y,z,w
```

Resposta do agente:

## Como usar

1. Instale a extensao GitHub Copilot Chat no VS Code.
2. Abra o Chat do Copilot.
3. No seletor de agentes, escolha o agente desejado.
4. Descreva a tarefa ou cole o codigo para revisao.

Se o agente nao aparecer na lista, use `Ctrl+Shift+P` > `Developer: Reload Window`.

## Estrutura do projeto

## Sobre este projeto

Criado como parte dos meus estudos em automacao com IA e ferramentas de desenvolvimento, explorando como configurar agentes customizados para diferentes tipos de tarefa.
