# Help_Desk
<img src="img/help_desk.png" />
Aplicativo para abertura de chamados. Criado para fins de prática e treino. Todas imagens são gratuitas.

Siga as instruções para o funcionamento do aplicativo: 
Utilizar um servidor para subir a aplicação;

Utilizar alguma das seguintes contas:
Sendo estes perfis administrativos:<br>
email: adm@teste.com.br - senha: 1234<br>
email: user@teste.com.br - senha: 1234

E estes usuários comuns:<br>
email: jose@teste.com.br - senha: 1234<br>
email: maria@teste.com.br - senha: 1234

Contas comuns têm permissão para ver somente seus próprios chamados,
contas administrativas têm permissão para ver todos os chamados.

A pasta 'privado' contém os arquivo que autentica os usuários e o 'arquivo.hd' que contém todos os chamados.<br>
Para manter esses arquivos protegidos basta:<br>
Colocar a pasta 'privado' fora do diretório público do servidor e;<br>
No arquivo valida_login.php, na linha 2, ajustar o caminho para a pasta 'privado';<br>
No arquivo registra_chamado.php, na linha 16, ajustar o primeiro parâmetro da função 'fopen' de acordo com o caminho para a pasta 'privado';<br>
No arquivo consulta_chamado.php, na linha 9, ajustar o primeiro parâmetro da função 'fopen' de acordo com o caminho para a pasta 'privado'.<br>
