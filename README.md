# python-wasm
*Exemplo de uso de Python no front-end com WASM via Pyodide*

Pyodide é uma distribuição de Python para browser por meio do Web Assembly.

Adicionando uma *script tag*, conferimos à pagina o suporte ao Pyodide, e após o carregamento, podemos rodar código Python. Dentro do Python, o módulo js permite acesso ao **DOM** para manipulação de objetos. É possível também o caminho contrário, fazendo com que código JavaScript acesse variáveis declaradas no Python.

O exemplo é bem simples: a troca dos valores A e B por meio de um botão que roda código Python. Feito apenas como exemplo.

Licença MIT - Douglas Modena - 2022
