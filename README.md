📄 Ferramentas PDF

Aplicação desktop desenvolvida em Python para unificação de arquivos PDF por matrícula, com interface moderna utilizando CustomTkinter.

Desenvolvido por GEABE

✨ Funcionalidades

✅ Unificação automática de múltiplos PDFs com base na matrícula

✅ Importação em massa via planilha Excel

✅ Seleção de pasta raiz para busca recursiva de PDFs

✅ Relatório detalhado ao final da unificação:

Quantidade de PDFs encontrados

Número de páginas por arquivo

Total de páginas do PDF final

Status (Sucesso / Erro)

✅ Indicador visual de status por matrícula

✅ Barra de progresso

✅ Splash screen personalizada

✅ Interface moderna (modo escuro)

🖥️ Interface

A aplicação possui:

Aba principal: Unificar PDFs

Lista dinâmica de matrículas

Importação via Excel

Relatório final em janela popup

Ícone personalizado da aplicação

📦 Tecnologias Utilizadas

Python 3.x

CustomTkinter

TkinterDnD2

PyPDF

Pandas

📊 Formato da Planilha Excel

A planilha deve conter as seguintes colunas:

Matrícula	Nome PDF
12345	João
67890	Maria

O nome da aba deve ser informado ao importar.

As colunas devem estar exatamente com esses nomes.

⚙️ Como Funciona

Selecione a pasta raiz onde estão os PDFs.

Adicione manualmente as matrículas ou importe via Excel.

Clique em UNIFICAR PDFs.

O sistema irá:

Buscar recursivamente arquivos contendo a matrícula no nome

Unificar os PDFs encontrados

Gerar um novo PDF com o nome informado

Exibir relatório detalhado

📂 Estrutura Esperada

A aplicação procura por arquivos .pdf que contenham a matrícula no nome, exemplo:

pasta/
 ├── documento_12345.pdf
 ├── contrato_12345.pdf
 ├── ficha_67890.pdf

🚀 Geração de Executável (Opcional)

Para gerar um .exe:

pip install pyinstaller
pyinstaller --onefile --windowed --icon=icone.ico nome_do_arquivo.py


O executável ficará na pasta:

dist/

📄 Licença

Este projeto é de uso interno do GEABE.

Se quiser, posso também gerar:

✅ requirements.txt

✅ Versão mais corporativa do README

✅ Versão pública/open-source

✅ Badges para GitHub

✅ Estrutura ideal de pastas

✅ Modelo de licença
