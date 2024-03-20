<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Documentação do Gitflow</h1>

<ol>
  <li><strong>Inicialização do Projeto:</strong>
    <ul>
      <li>Crie um novo repositório Git para o seu projeto.</li>
      <li>Inicialize o repositório.</li>
    </ul>
  </li>
  <li><strong>Criar os Branches Principais:</strong>
    <ul>
      <li>Crie o branch <code>master</code> como o branch principal de produção.</li>
      <li>Crie o branch <code>develop</code> como o branch principal de desenvolvimento.</li>
    </ul>
  </li>
  <li><strong>Desenvolvimento de Funcionalidades:</strong>
    <ul>
      <li>Desenvolva novas funcionalidades em branches de feature criadas a partir da branch <code>develop</code>.</li>
      <li>Faça commits das alterações na branch de feature.</li>
    </ul>
  </li>
<li><strong>Integração e Preparação para Lançamento:</strong>
    <ul>
      <li>Após concluir o desenvolvimento de uma funcionalidade, ou quando estiver pronto para fazer um lançamento, mesclar a branch de feature de volta para a branch <code>develop</code>.</li>
      <li>Quando estiver pronto, escolha uma das seguintes opções:</li>
      <ul>
        <li>Mesclar as alterações da branch <code>develop</code> diretamente para a branch <code>master</code>.</li>
        <li>Ou, se preferir, crie uma branch de release a partir da branch <code>develop</code> para realizar procedimentos de preparação para lançamento, como testes finais e atualizações de documentação.</li>
        <li>Em seguida, quando estiver pronto, mesclar a branch de release de volta para <code>develop</code> e <code>master</code>.</li>
      </ul>
    </ul>
</li>
  <li><strong>Correções de Hotfix:</strong>
      <ul>
        <li>Se ocorrerem problemas críticos em produção, crie uma branch de hotfix a partir da branch <code>master</code>.</li>
        <li>Corrija o problema na branch de hotfix e faça o merge de volta para <code>master</code> e <code>develop</code>.</li>
      </ul>
  </li>
  <li><strong>Limpeza:</strong>
    <ul>
      <li>Após o merge, exclua branches de feature e de release que não são mais necessárias.</li>
    </ul>
  </li>
  <li><strong>Padrões de Nomes de Branches:</strong>
    <ul>
      <li>Mantenha um padrão de nomenclatura claro e consistente para branches.</li>
      <li>Por exemplo, utilize prefixos como <code>feature/</code> para branches de funcionalidades, <code>release/</code> para branches de release e <code>hotfix/</code> para branches de correção de bugs.</li>
      <li>Isso ajuda a organizar e identificar facilmente o propósito de cada branch no fluxo de trabalho do Gitflow.</li>
    </ul>
  </li>
  <li><strong>Atualização do Repositório Remoto:</strong>
    <ul>
      <li>Após todas as operações, faça push das branches para o repositório remoto.</li>
    </ul>
  </li>
</ol>

<h1>Diagrama Git Flow</h1>

<img src="https://www.alura.com.br/artigos/assets/git-flow-o-que-e-como-quando-utilizar/imagem3.png" alt="Diagrama Git Flow">


</body>
</html>
