## Git Bash

 1. Git Config -> diz ao git hub quem fez os commits
    * git config -- global user.name "usuarionogit" 
    * git config -- global user.email "email do git sem as aspas"

2. Git Init 

   * cria um repositório git dentro de uma pasta já existente, possibilitando trabalhar com git nela

3. Git Clone

   * clona um repositório do git hub para máquina
   * ex: git clone [url]

4. Git Add

   * diz para o git monitorar um arquivo ou pasta e os deixa prontos para o commit
   * se colocar * ele já adiciona todas as alterações

5. Git Status

   * para saber em que patamar estão os arquivos
   * já indica o próximo passo

6. Git rm

   * remove os arquivos da àrvore de trabalho

   * tag útil: 

   * ```
     git rm Documentation/\*.txt
     ```

     Remove todos os arquivos `* .txt` do índice que estão no diretório `Documentation` e em qualquer um dos seus subdiretórios.
