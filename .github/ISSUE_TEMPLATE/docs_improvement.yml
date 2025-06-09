name: 📚 Melhoria na Documentação
description: Sugira atualizações, correções ou expansões para a documentação.
title: '[DOCS] Breve descrição da melhoria na documentação'
labels:
  - documentação
  - refatoração
assignees: []

body:
  - type: input
    id: local_documentacao
    attributes:
      label: Qual parte da documentação precisa de melhoria?
      description: Forneça o link ou o caminho do arquivo da documentação que você está se referindo.
      placeholder: Ex. docs/api/autenticacao.md ou https://meuprojeto.com/docs/guia-de-inicio
    validations:
      required: true

  - type: textarea
    id: problema_documentacao
    attributes:
      label: O que está incorreto/ausente/pouco claro?
      description: Descreva o problema específico na documentação. É um erro de digitação, informação desatualizada, falta de exemplos, ou algo que não está claro?
      placeholder: >
        Ex. A seção de autenticação via token JWT não menciona o cabeçalho Authorization corretamente.
    validations:
      required: true

  - type: textarea
    id: sugestao_melhoria
    attributes:
      label: Sugestão de Melhoria
      description: Proponha como a documentação pode ser melhorada. Se possível, inclua o texto corrigido ou o que você gostaria de ver adicionado.
      placeholder: >
        Ex. Adicionar um exemplo completo de requisição cURL com o cabeçalho Authorization: Bearer <token_jwt_aqui>.
    validations:
      required: true

  - type: textarea
    id: contexto_adicional
    attributes:
      label: Contexto Adicional (Opcional)
      description: Adicione qualquer outro contexto que possa ser útil.
      placeholder: >
        Ex. Encontrei essa inconsistência ao tentar integrar um novo serviço e a documentação atual me causou confusão.
    validations:
      required: false
