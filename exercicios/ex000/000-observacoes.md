# Tópicos abordados na Aula:

- Primeiro script PHP
- Um recado importantíssimo
- Já temos tudo configurado
- Criando o arquivo index.php
- Criando o código base em HTML5
- Entendendo a estrutura criada
- Primeiros comandos em PHP
- Comando echo
- Testando o primeiro programa PHP
- É melhor usar echo ou print?
- PHP moderno é compatível com Unicode
- Testando no Mac OS e Linux
- Testando no OnlinePHP.io
- Testando em versões antigas do PHP
- Mostrando as configurações do servidor
- Usando a função phpinfo()
- Executando o novo script
- Criamos dois scripts

---

### Abordando sobre `echo` vs `print` em PHP

#### **Diferenças Principais:**
1. **Sintaxe:**
   - `echo`: Aceita múltiplos argumentos separados por vírgula.
     ```php
     echo "Olá", " ", "Mundo!";
     ```
   - `print`: Aceita apenas um argumento.
     ```php
     print "Olá Mundo!";
     ```

2. **Retorno:**
   - `echo`: Não retorna valor (é uma construção de linguagem).
   - `print`: Retorna sempre `1`, permitindo uso em expressões.
     ```php
     $resultado = print "Olá Mundo!"; // $resultado = 1
     ```

3. **Desempenho:**
   - `echo`: Mais rápido, pois é mais simples.
   - `print`: Um pouco mais lento devido ao retorno de valor.

4. **Uso em Expressões:**
   - `echo`: Não pode ser usado em expressões.
   - `print`: Pode ser usado em expressões.
     ```php
     if (print "Olá") { /* Válido */ }
     ```

#### **Quando Usar:**
- **`echo`**: Preferido na maioria dos casos por ser mais rápido e flexível (aceita múltiplos argumentos).
- **`print`**: Útil apenas em situações específicas onde o retorno de valor é necessário.

#### **Conclusão:**
- Use **`echo`** para exibir saídas de forma eficiente.
- Use **`print`** apenas se precisar do retorno de valor (`1`) em expressões.