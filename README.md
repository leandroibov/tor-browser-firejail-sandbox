Hashs sha256

23bb0587b47818b1b0fc04e378b5537a7733c99001f062cc87ff4f3fbcabd554  tor-ram-jail1


0f60a012e5c54418b3489809d8012464798b40d2921da7a1badf6616072d4a30  tor-ram-jail2


###################################################3

executar:

###################################################


[tor-ram-jail1] -> configurado firejail que permite ouvir som dos vídeos e músicas etc...


[tor-ram-jail2] -> configurado firejail mais seguro, mas mais restrito. Sem som e sem vídeo --nosound --novideo


sudo chmod +x tor-ram-jail1 tor-ram-jail2;


sudo cp -r tor-ram-jail1 tor-ram-jail2 /bin;


tor-ram-jail1 

tor-ram-jail2


ou

dentro da pasta que estão os scripts


./tor-ram-jail1 

./tor-ram-jail2



###################################################


Como operar:


###################################################

Use o https://github.com/leandroibov/mullvad-browser-firejail-anti-forense/blob/main/mullvad-mac-ram e https://github.com/leandroibov/gerador-de-enderecos-mac/blob/main/mac-random.html para gerar endereços mac spoofados para melhorar a camada de anonimidade e anti metadados.


Colete bridges em https://bridges.torproject.org e mantenha elas no gedit ou .txt sem salvar enquanto usa seu linux para ficar os registros 100% na ram e não gravar no HD!


Gere o mac por mac-random.html e adicione na conexão do tor browser solicitada no script!


Obs: tor browser em ~/Downloads/tor-browser deve ser zerado, ou seja, sem nenhuma bridge cadastrada.


Após acionar o programa tor-ram-jail1 ou tor-ram-jail2, com mac spoofing adicional, adicione a bridge e se conecte!


Resultado: mac diferente dos usados nas interfaces normais do sistema para cada sessão do tor browser, diminui coleta de metadados das bridges.


As Bridges são conectadas nos macs temporários não relacionados com o mesmo mac usado nas outras conexões que podem lhe identificar!


Ex: mac 00:16:6C:77:8c:1c - Samsung Electonics Digital Video System Division - usado nas suas conexões do firefox com facebook, youtube logado por exemplo!


Se usar as bridges conectando pelo mesmo mac 00:16:6C:77:8c:1c, o isp poderá coletar esse metadado e descobrir cedo ou tarde que o ip era de uma bridge tor e descobrirá que você estava usando o tor.


Ex: Se para cada sessão do tor você usar um mac diferente, e sempre usando bridges distintas, ficará mais difícil lhe identificar pelos registros dos sniffers!


O objetivo por meio das bridges é impedir que o ISP ou administrador da rede saiba que você esteja usando o tor para garantir seu anonimato, por isso, deverá usar mac spoofing diferente das outras conexões do seu linux e sem deixar rastros de nada, por isso, rodamos o tor browser na memória compartilhada e apagamos ao finalizar o uso do tor browser (ram). Isso fica similar ao Tails!






##################################################################################################

Doe monero para nos ajudar: 

87JGuuwXzoMGwQAcSD7cvS7D7iacPpN2f5bVqETbUvCgdEmrPZa12gh5DSiKKRgdU7c5n5x1UvZLj8PQ7AAJSso5CQxgjak




Página oficial de segurança digital:

https://traderprofissional.com.br/seguranca-digital.aspx

Vídeo tutorial youtube: 

https://www.youtube.com/watch?v=4JPKRkO5eLw&t=3s



























