Desafio de projeto (Criar repositório, Atualizar, Sincronizar) :woman_technologist:

## # Crie um novo repositório na linha de comando
echo "#name" >> README.md
git init
git add README.md
git commit -m "primeiro commit"
git branch -M main
git remote add origin https://github.com/name/...
git push -u origem principal

…ou envie um repositório existente a partir da linha de comando
git remote adicionar origem
git branch -M main https://github.com/name/..
git push -u origem principal

…ou clonando repositório
git clone https://github.com/name/..

## # Carregando repositório no GitHub via linha de comando
#Passo a passo rápido

-Certifique-se de que seu git está instalado.
No terminal ou no prompt de comando, verifique o comando:
git -v
-No GitHub, crie um novo repositório. Na tela de upload ou criar arquivos, salve o link HTTPS que será gerado no GitHub
-Abra o Git Bash ou terminal na pasta onde seu projeto está
-Inicie a pasta como um repositório Git através do comando:
git init
-Em seguida, adicione os arquivos de configuração para preparar o commit:
git add
-Opcional: Adicione um arquivo leia-me se você não iniciou o repositório com ele:
git add README.md
-Crie um novo commit para os arquivos que serão enviados para o repositório:
git commit -m "primeiro commit"
- Carregue seus arquivos usando a URL gerada na etapa 2 no seguinte comando:
git remote add origin
-Autorize o upload com seu login e senha:
git push -u mestre de origem
