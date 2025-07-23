# Cacau Show 140

## Introdução
Este projeto automatiza testes para o sistema da Cacau Show, focando em cenários como cadastro de usuário, compra de produtos e compra via WhatsApp. O objetivo é garantir a qualidade e o correto funcionamento das principais funcionalidades do sistema.

## Ferramentas Utilizadas
- **Python**: Linguagem principal para desenvolvimento dos testes.
- **Selenium**: Automação de navegação e interação com páginas web.
- **pytest**: Framework para execução e organização dos testes automatizados.

## Como Executar Localmente
1. **Clone o repositório:**
   ```powershell
   git clone <url-do-repositorio>
   cd CacauShow140
   ```
2. **Crie e ative um ambiente virtual (opcional, mas recomendado):**
   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate
   ```
3. **Instale as dependências:**
   ```powershell
   pip install selenium pytest
   ```
4. **Execute os testes:**
   ```powershell
   pytest
   ```

## Estrutura dos Testes
- `test_cadastrousuario.py`: Testes de cadastro de usuário.
- `test_comprarpelowhatsapp.py`: Testes de compra via WhatsApp.
- `test_comprarproduto.py`: Testes de compra de produtos.