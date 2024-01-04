## !! Please update this README.md file for online Repo submission !!
You can edit your `README.md` within Github's online editor, it also has an preview button!  
Check the [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for markdown syntaxes, it's super easy!  

## How to Create a Magisk Module
1. Clone / download this repo
2. Open `config.sh`, follow the instructions written at the beginning of the file. You should at least change `config.sh` and `module.prop`
3. Zip your files, the zipped file is a flashable zip for both Magisk Manager and custom recoveries
4. Please check **Notes** for precautions

## How to Request a New Repo
1. Fork [this repo](https://github.com/topjohnwu/magisk-module-template)
2. Create your own Magisk Module as stated above
3. Push your changes to Github
4. Change the description of the Github repo to **the id of your module. This is important! Never change it to anything else!**
5. Open an issue in [topjohnwu/Magisk_Repo_Central](https://github.com/topjohnwu/Magisk_Repo_Central/issues/new)  
   Please include your repo link so I can check and clone it
6. Your repo should be cloned into [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), and you should receive an email to become the collaborator of that repo so you can edit it in the future.

## Notes
1. (Windows aware!!) This git repo is configured to force Unix endlines on all necessary files. The line endings on these files should remain the Unix format. Please use advanced text editors like Sublime, Atom, Notepad++ etc. to edit the text files
2. In `module.prop`, `version` is any string you like, so any fancy version name (e.g. ultra-beta-v0.0.0.1) is allowed. However, `versionCode` **MUST** be an integer. The value is used for version comparison.
2. Make sure your module ID **doesn't contain any spaces**.
3. (For repo developers) Magisk Manager monitors all repo's `master` branch. So any changes to the branch `master` will be reflected to all users immediately. If you are working on an update for a module, please work on another branch, make sure it works, and then merge the changes back to `master`.

## Best Practice for Updating a Repo
1. Open a new branch, and start update your files on the new branch
2. Test if everything works fine
3. Bump up the `versionCode` in `module.prop`, or Magisk Manager won't know that your module is updated!
4. Merge the changes back to master, all users shall now receive the update in Magisk Manager

=============================== PORTUGUESE ======================================

## !! Por favor, atualize este arquivo README.md para a submissão online do repositório !!
Você pode editar o seu `README.md` no editor online do Github, que também possui um botão de visualização!
Confira a [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) para a sintaxe markdown, é super fácil!

## Como Criar um Módulo Magisk
1. Clone/baixe este repositório
2. Abra o arquivo `config.sh` e siga as instruções escritas no início do arquivo. Você deve pelo menos alterar o `config.sh` e o `module.prop`
3. Compacte seus arquivos, o arquivo compactado é um zip flashável tanto para o Magisk Manager quanto para recuperações personalizadas
4. Por favor, verifique as **Notas** para precauções

## Como Solicitar um Novo Repositório
1. Faça um fork [deste repositório](https://github.com/topjohnwu/magisk-module-template)
2. Crie seu próprio Módulo Magisk conforme indicado acima
3. Faça o push de suas alterações para o Github
4. Altere a descrição do repositório do Github para **o ID do seu módulo. Isso é importante! Nunca o altere para qualquer outra coisa!**
5. Abra um problema em [topjohnwu/Magisk_Repo_Central](https://github.com/topjohnwu/Magisk_Repo_Central/issues/new)
   Inclua o link do seu repositório para que eu possa verificar e cloná-lo
6. Seu repositório deve ser clonado em [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), e você deve receber um e-mail para se tornar o colaborador desse repositório para poder editá-lo no futuro.

## Notas
1. (Atenção ao Windows!!) Este repositório git está configurado para forçar caracteres de fim de linha Unix em todos os arquivos necessários. Os caracteres de fim de linha nesses arquivos devem permanecer no formato Unix. Use editores de texto avançados como Sublime, Atom, Notepad++ etc. para editar os arquivos de texto.
2. Em `module.prop`, `version` pode ser qualquer string que você goste, então qualquer nome de versão sofisticado (por exemplo, ultra-beta-v0.0.0.1) é permitido. No entanto, `versionCode` **DEVE** ser um número inteiro. O valor é usado para comparação de versão.
3. Certifique-se de que o ID do seu módulo **não contenha espaços**.
4. (Para desenvolvedores de repositórios) O Magisk Manager monitora todos os ramos `master` do repositório. Portanto, quaisquer alterações no ramo `master` serão refletidas imediatamente para todos os usuários. Se estiver trabalhando em uma atualização para um módulo, trabalhe em outro ramo, certifique-se de que funciona e depois una as alterações de volta ao `master`.

## Melhores Práticas para Atualizar um Repositório
1. Abra um novo ramo e comece a atualizar seus arquivos no novo ramo
2. Teste se tudo funciona bem
3. Aumente o `versionCode` em `module.prop`, ou o Magisk Manager não saberá que seu módulo foi atualizado!
4. Una as alterações de volta ao master, todos os usuários agora devem receber a atualização no Magisk Manager

