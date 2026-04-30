# Script
Fiz este script para gerar automaticamente um relatório fotográfico da obra em que eu estava trabalhando. O objetivo é criar um documento simples, porém formal e padronizado, que minimize o trabalho na hora de elaborá-lo.

# Modo de usar
*Ajustando o script*

Primeiramente, vamos atualizar o Script.py para que o título e o local da obra estejam corretos.

<img width="660" height="425" alt="image" src="https://github.com/user-attachments/assets/cbd2b718-1390-463b-bfb9-2763da8228b0" />

Atualize para que apareçam as informações que preferir. Nesse caso, usarei dados fictícios para gerar um documento de exemplo. Aqui, você pode ajustar o tamanho e o estilo da fonte conforme preferir; neste caso, vou manter o padrão. Lembrando que é possível alterar isso no documento após ele ser gerado.

*Ajustando as fotos*

Para ajustar as fotos, é bem simples: primeiro, criamos uma pasta no local onde o Script.py está e a renomeamos para “Imagens”. Dentro dela, ajustaremos as legendas e a ordem das fotos.

<img width="268" height="187" alt="image" src="https://github.com/user-attachments/assets/08333715-7f6e-4b63-acfd-5f395496d7e4" />

As imagens que serão colocadas na pasta devem ser renomeadas seguindo um padrão. Primeiramente, coloque a numeração de cada imagem; essa numeração será a ordem em que elas aparecerão no relatório, do menor para o maior. Logo após inserir a numeração, adicione um título à imagem; esse título será a legenda que ficará abaixo das fotos no documento.

<img width="496" height="356" alt="image" src="https://github.com/user-attachments/assets/cc1b2de4-ad88-49e8-80ad-7bb274789735" />

*Gerando o relatório*

Antes de gerar o relatório com o script, instale as dependências dele, que, neste caso, são a biblioteca *python-docx*, utilizada para criar documentos Word com o Python. Execute o comando abaixo para instalá-la:
```bash
pip install python-docx
```
Após isso, com o script já ajustado e as imagens colocadas dentro da pasta, abra o terminal no local em que você está e digite o comando para executar o script:
```bash
python Script.py
```
O relatório será gerado automaticamente. Agora é só abrir e conferir para ver como ele ficou.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ca2f3f2b-fe80-45c8-bcf9-5f47ada3a961" />

Pronto, aqui está o nosso documento gerado. Se quiser alterar alguma coisa, basta editá-lo no Word.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/59744836-61a5-4bb5-beb8-47c6371711cc" />
