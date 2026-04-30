# Script

Fiz este script para gerar automaticamente um relatório fotográfico da obra em que eu estava trabalhando. O objetivo é fazer um documento simples, porém formal e padronizado, que minimize o trabalho na hora de elaborar um.

# Modo de usar

*Ajustando o script*

Primeiramente vamos estar atualizando o Script.py para que o titulo e o local da obra estejam corretos.

<img width="660" height="425" alt="image" src="https://github.com/user-attachments/assets/cbd2b718-1390-463b-bfb9-2763da8228b0" />

Atualize para que apareça as informações que preferir nesse caso usarei dados que não existem para gerar um documento de exemplo, aqui você pode ajustar o tamanho e o estilo da fonta para qual preferir nesse caso vou deixar como padrão, lembrando que tem como mudar no documento quando ele for gerado.

*Ajustando as fotos*

Para ajustar as fotos e bem simples primeiro criamos uma pasta no local aonde o Script.py está e renomeamos ela para "Imagens" dentro dela ajustaremos as legendas e a ordem das fotos.

<img width="268" height="187" alt="image" src="https://github.com/user-attachments/assets/08333715-7f6e-4b63-acfd-5f395496d7e4" />

As imagens que serão colocadas na pasta devem ser renomeadas seguindo um padrão, primeiramente colocando a númeração de cada imagem essa númeração sera a ordem que ele aparecera no relatório sendo na ordem do menor para o maior, logo apos colocarmos a númeração devemos adicionar um titulo a imagem esse titulo sera a legenda que vai ficar abaixo das fotos no documento.

<img width="496" height="356" alt="image" src="https://github.com/user-attachments/assets/cc1b2de4-ad88-49e8-80ad-7bb274789735" />

*Gerando o relatório*

Antes de gerar o relatório com o script instale as depedencias dele que no caso e a biblioteca *python-docx* que utlizamos para fazer documentos world com o python, rode o comando abaixo para instalar ela:

pip install python-docx
