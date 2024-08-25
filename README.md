# Decodificador de Texto

Este é um projeto de um decodificador de texto que permite criptografar e descriptografar mensagens utilizando uma substituição de letras simples. Este projeto faz parte de um desafio de programação e é implementado com HTML, CSS e JavaScript.
[Clique aqui para acessar a versão hospedada na Vercel](https://desafio-decodificador-alura.vercel.app/)

## Funcionalidades

- **Criptografar Mensagens**: Converte texto normal em texto criptografado usando substituição de letras.
- **Descriptografar Mensagens**: Converte texto criptografado de volta ao texto original.
- **Copiar Texto**: Permite copiar o texto resultante para a área de transferência.

## Como Usar

1. **Digite seu texto**: No campo de entrada, insira o texto que deseja criptografar ou descriptografar.
   - Nota: Apenas letras minúsculas sem acentos são permitidas.
2. **Escolha uma ação**:

   - Clique em **Criptografar** para converter o texto em uma forma criptografada.
   - Clique em **Descriptografar** para converter um texto criptografado de volta ao seu estado original.

3. **Copiar o resultado**:
   - Após criptografar ou descriptografar, você pode copiar o resultado clicando no botão **Copiar**.

## Exemplo de Criptografia

A criptografia é baseada na substituição de algumas letras por palavras. Aqui estão os mapeamentos usados:

- `a` -> `ai`
- `e` -> `enter`
- `i` -> `imes`
- `o` -> `ober`
- `u` -> `ufat`

Por exemplo, a palavra "gato" se torna "gaitober".

## Tecnologias Utilizadas

- **HTML5**: Estrutura básica da página.
- **CSS3**: Estilização da interface do usuário.
- **JavaScript**: Lógica para criptografia e descriptografia de texto.

## Estrutura do Projeto

O projeto é dividido em três principais arquivos:

- `index.html`: Contém a estrutura HTML da página.
- `style.css`: Arquivo de estilo para a página.
- `script.js`: Contém a lógica JavaScript para criptografar, descriptografar e copiar texto.

## Como Executar o Projeto

1. Clone este repositório para o seu ambiente local.
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
