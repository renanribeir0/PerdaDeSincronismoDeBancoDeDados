# Teste de Perda de Sincronismo de Banco de Dados em Página da Web usando Postman

Este documento descreve o procedimento para realizar um teste de perda de sincronismo de banco de dados em uma página da web usando o Postman. O teste simulará uma perda de conexão Wi-Fi e avaliará o comportamento da aplicação web.

## Pré-Condição
- A aplicação web está em execução e conectada a um banco de dados.
- O ambiente de teste está configurado no Postman.
- Conexão Wi-Fi está ativa.

## Procedimento de Teste
1. **Preparação**: Certifique-se de que o Postman está aberto e o ambiente de teste está configurado.
2. **Acesso à Página Web**: Faça uma solicitação GET para a página da web a ser testada.
3. **Captura de Estado Inicial**: Capture uma captura de tela da página da web em seu estado normal.
4. **Simulação de Perda de Conexão Wi-Fi**:
   - Desative a conexão Wi-Fi em seu dispositivo (ou utilize uma ferramenta de simulação de perda de conexão).
   - Execute a mesma solicitação GET novamente.
5. **Captura de Estado Após a Perda de Conexão**: Capture uma captura de tela da página da web após a simulação de perda de conexão Wi-Fi.
6. **Reativação da Conexão Wi-Fi**:
   - Reative a conexão Wi-Fi em seu dispositivo.
   - Execute a mesma solicitação GET novamente.
7. **Captura de Estado Após a Reconexão**: Capture uma captura de tela da página da web após a reconexão.

## Pós-Condição
- As capturas de tela e resultados dos testes são registrados.

## Resultados Esperados
- No estado inicial, a página da web deve ser carregada corretamente e exibir os dados do banco de dados.
- Após a simulação de perda de conexão Wi-Fi, a página deve exibir uma mensagem de erro ou uma página de falha de conexão.
- Após a reconexão, a página da web deve recuperar a funcionalidade normal e exibir os dados corretamente.

## Resultados Obtidos
- As capturas de tela estão anexadas a este documento.
- Os resultados do teste indicam que a aplicação web responde de acordo com as expectativas, mostrando uma mensagem de erro durante a perda de conexão e restaurando a funcionalidade após a reconexão.

### Capturas de Tela
- [Captura de Tela 1: Estado Inicial](url_da_captura_de_tela_1)
- [Captura de Tela 2: Estado Após a Perda de Conexão](url_da_captura_de_tela_2)
- [Captura de Tela 3: Estado Após a Reconexão](url_da_captura_de_tela_3)
