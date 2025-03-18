# Como funciona o PHP? ⚙️

## Fluxo básico:
1. **Requisição do navegador**: O usuário acessa uma página (ex: `index.php`). 🌐
2. **Processamento no servidor**: O servidor identifica o código PHP (`<?php ... ?>`) e o interpretador PHP processa as instruções. 💻
3. **Geração do HTML**: O PHP gera conteúdo HTML dinâmico (ex: dados de banco de dados). 📄
4. **Exibição no navegador**: O HTML é enviado ao navegador e exibido ao usuário. 🖥️

## Características:
- **Linguagem server-side**: Executada no servidor, não no navegador. 🖥️
- **Dinâmica**: Gera conteúdo dinâmico (ex: formulários processados, consultas a bancos de dados). 🔄
- **Integração**: Funciona com MySQL, APIs, e outras tecnologias web. 🔗

## Exemplo básico:
```php
<!DOCTYPE html>
<html>
<body>
    <?php
        echo "Olá, mundo!";
    ?>
</body>
</html>
```

---

## Resumo de Fluxo

1. Requisição → 2. Processamento no servidor → 3. Geração de HTML → 4. Exibição no navegador. 🔄