# cgmine-README-FPGA-e-ASIC-
configuração de maquinas pra você cria sua propiá mineradora de bitcoins 

NOTA: Este código está licenciado sob a GPLv3. Isso significa que a fonte para qualquer
As modificações que você fizer a este código DEVEM ser fornecidas por lei se você distribuir
Binários modificados. Consulte COPYING para obter detalhes.


TRANSFERÊNCIAS:

Http://ck.kolivas.org/apps/cgminer

ÁRVORE DE GIT:

Https://github.com/ckolivas/cgminer

Fio de suporte:

Http://bitcointalk.org/index.php?topic=28402.0

Canal IRC:

Irc: //irc.freenode.net/cgminer

RESUMO EXECUTIVO SOBRE O USO:

Solo mineração para bitcoind local:


CONSTRUINDO CGMINER PARA SI MESMO

DEPENDÊNCIAS:

 a construção de git:
	Autoconf
	Automake

Construção de janelas:

Instruções de compilação Native WIN32: consulte windows-build.txt, mas essas instruções
Estão agora irremediavelmente desatualizados.
Instruções de uso: Execute "cgminer --help" para ver as opções:

Uso: cgminer [-DdElmpPQqUsTouOchnV]

Dispositivo USB silencioso (ASIC e FPGA):
Consulte FGPA-README ou ASIC-README para obter mais informações sobre estes.
ASIC apenas opções

FPGA apenas opções:
Consulte ASIC-README para obter mais informações sobre estes.
--bfl-range Utilize intervalo nonce em dispositivos bitforce se suportado
Consulte FGPA-README para obter mais informações sobre isso.

CONFIGURAÇÃO DE DISPOSITIVOS USB
JANELAS:

A versão curta:
Sudo cp 01-cgminer.rules /etc/udev/rules.d/
A versão longa:

Depois disso, você pode reiniciar manualmente o udev e reiniciar o login, ou mais facilmente
Apenas reinicie.
OSX:

Opções avançadas de USB:
ENQUANTO CORRENDO:
As seguintes opções estão disponíveis durante a execução com uma única tecla:
[U] SB gestão [P] ool gestão [S] ettings [D] isplay opções [Q] uit

Também muitas questões e FAQs são abordados no tópico do fórum
Dedicado a este programa,
	Http://forum.bitcoin.org/index.php?topic=28402.0

EXIBIÇÃO:

A tela é dividida grosseiramente em duas partes, a janela de status
Janela de registro de rolagem inferior.

JANELA DE ESTADO
A janela de status é dividida em status geral e por status de dispositivo.

Estado geral:
JANELA DE REGISTRO
MULTIPOOL

ESTRATÉGIAS DE FAILOVER COM MULTIPOOL:

API RPC

Para detalhes da API RPC, consulte o arquivo API-README
CONTINUA NO cgmine README FPGA e ASIC............. 



