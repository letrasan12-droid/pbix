# Guia de Contribuição

Obrigado por considerar contribuir! Siga estas diretrizes para manter o projeto organizado.

## Requisitos
- Power BI Desktop (versão atual)
- Conhecimento básico de Power Query e DAX

## Como Contribuir
1. Faça um fork do repositório
2. Crie uma branch: `git checkout -b feature/minha-melhoria`
3. Faça commits descritivos: `git commit -m "feat: adiciona medida DAX de margem"`
4. Envie a branch: `git push origin feature/minha-melhoria`
5. Abra um **Pull Request** seguindo o template

## Padrões
- **Commits**: use *conventional commits* (feat, fix, docs, chore, refactor, test)
- **Pastas**: mantenha dados em `/datasets`, imagens em `/images`, PBIX em `/pbix`
- **Documentação**: atualize o `README.md` e a aba **“Entendendo o Desafio”** no PBIX
- **Performance**: evite colunas calculadas desnecessárias; prefira medidas DAX

## Boas Práticas Power BI
- Modelo estrela (fato no centro, dimensões nas bordas)
- Tipos de dados e formatos consistentes
- Relacionamentos com cardinalidade correta
- Medidas em tabela dedicada (ex.: `Medidas`)
- Utilize **DIVIDE** para evitar divisão por zero

## Reportando Bugs
Abra uma *issue* usando o template e inclua:
- Passos para reproduzir
- Resultado atual vs esperado
- Prints (se possível)

## Solicitando Funcionalidades
Abra uma *issue* do tipo *feature request* e explique:
- O problema que quer resolver
- A solução proposta
- Impacto para o usuário
