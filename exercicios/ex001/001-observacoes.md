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

### Resumo: `phpinfo()` em PHP

#### **O que é:**
- Função que exibe informações detalhadas sobre a configuração do PHP no servidor.

#### **Uso Básico:**
```php
phpinfo();
```

#### O que exibe:
   - Versão do PHP.
   - Configurações do **`php.ini`**.
   - Extensões carregadas.
   - Informações do servidor (Apache, Nginx, etc).
   - Variáveis de ambiente.
   - Diretórios e paths.

#### Parâmetros Úteis:

   - **`INFO_GENERAL`**: Informações gerais (versão, sistema, etc.).

   - **`INFO_CONFIGURATION`**: Configurações do php.ini.

   - **`INFO_MODULES`**: Extensões carregadas.

   - **`INFO_ENVIRONMENT`**: Variáveis de ambiente.

   - **`INFO_VARIABLES`**: Variáveis globais (**`$_GET`**, **`$_POST`**, etc.).