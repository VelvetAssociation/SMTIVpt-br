# SMTIV pt-br
Pagina para organizar a tradução do Shin Megami Tensei IV.

Para poder editar, excluir, ou fazer upload de arquivos é necessário ter uma conta no GitHub.

Todos os arquivos devem estar no formato ANSI. Se estiver em dúvida, utilize o bloco de notas para fazer a tradução, e, quando for salvar, selecione ANSI na Codificação.

Membros:

RitsuLaw

KRaidou

Pyro Jack

Nico

Bajie


Tradutores: A pasta "notedited" possui as pastas com textos ainda não traduzidos. Se escolher algum para traduzir, você pode: Editar o arquivo diretamente de onde ele está, ou, copiar todo o conteudo do arquivo para um arquivo do bloco de notas com o nome do arquivo original e com a extensão .xml. Depois, exclua o arquivo original daqui do GitHub.
            A pasta "edited" possui as pastas com textos já traduzidos. Quando acabar a tradução de algum arquivo, coloque-o na subpasta correspondente a de onde ele foi retirado.

Os arquivos do texto da história principal ainda não foram colocados pois, como eu estou traduzindo essa parte, ainda devo separar as partes.

Qualquer dúvida entrar em contato com a página Velvet Association no facebook.

----
Traduza sempre sem usar os caracteres especiais das línguas latinas, como acentos, ç, dentre outros.
- 
No momento o jogo só aceita arquivos codificados em japonês, ou seja, se for colocar um ç ou outra letra com algum tipo de acento, o bloco de notas vai alertar que para que esses caracteres especiais sejam salvos, a codificação teria que mudar para Unicode, porém, o jogo não suporta nenhuma codificação além da japonesa.
Então isso quer dizer que o jogo não vai ter esses caracteres?
O jogo VAI ter todas as acentuações e etc. que a nossa língua possui, porém, para isso, é necessária a modificação da fonte que o jogo usa e inserir esses caracteres especiais. Não é algo muito difícil de fazer, mas leva muito tempo, então, essa edição das fontes vai ser trabalhada por mim em segundo plano. O mais importante é a tradução em si, depois que completar a fonte modificada, eu irei mudar todos os ‘’voce’’, ‘’nao’’, ‘’ha’’, etc., para ‘’você’’, ‘’não’’, ‘’há’’, etc. 

E peço que, ao invés de colocar ‘’e’’ no lugar do ‘’é’’, coloquem ‘’eh’’, para facilitar o processo de substituição depois.

Reiterando: O nosso foco atual é traduzir os textos, mesmo que fiquem estranhos sem as acentuações e etc., mas tudo isso vai ser corrigido antes do lançamento da tradução completa.

Observações finais: Não modifique o coding dos arquivos para Unicode ou qualquer outro, sempre mantendo o original.
-Não traduza ou modifique coisas que claramente não tem ligação com o jogo em si, e servem somente como placeholders. 
Alguns exemplos são: Dummy, NOT USED, textos em japonês, etc.

----

Tutorial sobre os arquivos de tradução:
-
Não se deve mexer na grande maioria dos códigos que acompanham o texto. Somente dois podem ser mudados de lugar ou adicionados.

O código {F801} serve como um ''quebra-texto'', dividindo a frase, e formando um novo parágrafo.
Ex: 
Vamos dar nosso melhor para completar essa{F801}missão, Mestre.{F801}

A inclusão do código {F801} no meio e no fim da frase modificou a forma que o texto é exibido na caixa de mensagem do jogo, quebrando a frase para a mesma poder caber na caixa de mensagem, e fazendo que o "missão, Mestre." seja exibido em um novo paragrafo.
O {F801} também deve sempre ficar no fim da frase, pois ele funciona como um ponto final.

O código {F802}, geralmente encontrado após o {F801}, e no meio da linha de texto, serve para dar um ''next'' na mensagem atual, limpando a caixa de texto para que surja o resto da mensagem que não coube na primeira mensagem.

Os códigos {F804,5} e {F804,0} aparecem com mais frequência em tutoriais e telas de missões, e servem para que o texto que fica entre os dois códigos torne-se vermelho, destacando algo de importante.
Ex: 
Selecione {F804,5}Conversar{F804,0} na lista de comando e{F801}então {F804,5}Negociar.{F804,0} Isso irá convidar o demônio{F801}a se juntar a você.{F801}

A inserção desses códigos fez com que as palavras Conversar e Negociar ficarem em vermelho. É importantíssimo prestar atenção se as palavras que você colocar entre esses códigos seja a tradução das que originalmente estavam ali.

Observação: Apesar do limite de caracteres por linha serem de cerda de 36-40, isso varia por conta do tamanho das próprias letras, então recomendo que usem o espaço original da frase como base.

Sobre os parágrafos:
Em todos os arquivos sempre haverá dois parágrafos com o mesmo texto, como:

(source)Let's begin the standard demon-slaying contest.{F801}Don't forget your weapons.{F801}(/source)

(target)Let's begin the standard demon-slaying contest.{F801}Don't forget your weapons.{F801}(/target)

Você não precisa traduzir as duas, só a de baixo, entre os (target)(/target). O parágrafo de cima serve somente para que você tenha uma noção de quando colocar a quebra de página.
Ex: 

(source)Let's begin the standard demon-slaying contest.{F801}Don't forget your weapons.{F801}(/source)

(target)Vamos começar o concurso padrão de matar demônios.{F801}Não esqueçam suas armas.{F801}(/target)

O parágrafo superior é de grande ajuda para saber o tamanho da caixa de mensagem do jogo e impedir que o texto ultrapasse as suas margens. Se uma frase traduzida fica mais longa do que a original, é importante colocar um {F801} e ir para outro parágrafo o mais perto da original possível. No exemplo, pode-se observar que o {F801} foi inserido na tradução um pouco após do original, mas não há problema, pois como a distância foi pouca, provavelmente não haverá texto saindo da caixa de mensagem.
