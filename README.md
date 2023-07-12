# Bodyscan
Bodyscan script Python que analisa a segurança de um determinado site inspecionando seus cabeçalhos HTTP e registros DNS.  O script gera um relatório de segurança com recomendações para lidar com possíveis vulnerabilidades.

# Casos de teste
O script abrange os seguintes casos de teste:

1- Script do mesmo site

2- registros SPF

3- registros DMARC

4- Página de administração pública

5- Listagem de diretório

6- Cabeçalhos de segurança ausentes

7- Configurações de cookies inseguras

8- Divulgação de informação

9- Erros de configuração do Cross-Origin Resource Sharing (CORS)

10- detecção de tipo de conteúdo

11- Controle de cache

# Dependências
O Bodyscan possui as seguintes dependências:

Python 3.6 ou superior
requestsbiblioteca
beautifulsoup4biblioteca
dnspythonbiblioteca
Você pode instalar essas dependências usando pip:

pip install requests beautifulsoup4 dnspython

# uso
Para usar o script EasyScan, siga estas etapas:

Salve o código em um arquivo chamado easyscan.py.
Abra um terminal ou prompt de comando e navegue até o diretório que contém o script.
Execute o script usando Python:

python3 bodyscan.py

# Digite a URL do site que deseja analisar quando solicitado.
Revise o relatório de segurança gerado para possíveis vulnerabilidades e recomendações.
O relatório de segurança exibirá o cabeçalho ou caso de teste, o status (Ausente, Acessível, Ativado etc.), a gravidade (Baixa, Média ou Alta) e a recomendação para resolver o problema.


