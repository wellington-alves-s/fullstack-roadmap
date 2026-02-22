🧠 O que é HTTP?

HTTP (do inglês Hypertext Transfer Protocol) é o protocolo de comunicação principal da internet usado para trocar informações entre clientes (como navegadores e apps) e servidores (onde os sites e serviços estão hospedados).

Ele define regras de como pedidos e respostas devem ser feitos, permitindo, por exemplo, carregar páginas, imagens, vídeos ou enviar dados em formulários.

🔁 Como funciona

HTTP segue um modelo de comunicação chamado request–response (requisição e resposta):

O cliente (navegador ou app) envia um pedido HTTP ao servidor pedindo um recurso.

O servidor processa esse pedido e envia uma resposta HTTP de volta.

Esse ciclo acontece rápido e repetidas vezes enquanto carregamos um site.

📡 Características principais

Camada de aplicação: HTTP opera no topo do modelo de rede, usando TCP/IP por baixo das pontas para transportar os dados.

Estateless (sem estado): cada pedido é independente — o servidor não “lembra” do que aconteceu antes, a menos que cookies ou sessões sejam usados.

🔤 Mensagem HTTP: pedidos e respostas
📩 Requisição (Request)

Uma requisição HTTP inclui:

Método HTTP — tipo de ação (como GET, POST).

URL — endereço do recurso pedido.

Cabeçalhos — informações extras (como tipo de conteúdo, cookies).

Corpo — dados enviados (opcional, como em formulários).

📬 Resposta (Response)

Uma resposta HTTP contém:

Código de status — informa se o pedido deu certo ou se houve erro.

Cabeçalhos — metadados sobre a resposta.

Corpo — conteúdo retornado (HTML, JSON, imagens etc.).

📊 Códigos de status

Os códigos de status são números que indicam o resultado do pedido:

Categoria Exemplo Significado
2xx 200 OK Pedido bem-sucedido
3xx 301 Redirect Redirecionamento
4xx 404 Not Found Recurso não encontrado
5xx 500 Internal Server Error Erro no servidor
🚀 Versões do HTTP

HTTP evoluiu ao longo do tempo:

HTTP/1.1 – versão mais comum hoje.

HTTP/2 – melhora a performance e a eficiência.

HTTP/3 – usa QUIC em vez de TCP para ainda mais velocidade.

🌐 Onde HTTP é usado

HTTP não é só usado no navegador — aplicativos e APIs também usam HTTP para se comunicar com servidores e obter dados.

📌 Resumo final

HTTP é o protocolo que rege a troca de informações na web.

Ele usa um ciclo requisição → resposta entre cliente e servidor.

As mensagens têm métodos, cabeçalhos, corpo e códigos de status para indicar o resultado de cada interação.

Exemplo de requisição:

POST / HTTP/1.1
Host: www.codigofonte.com.br/
User-Agent: Mozilla/5.0 (X11; Linux i686) AppleWebKit/537.36 (KHTML, like Gecko) Ubuntu Chromium/76.0.3809.87 Chrome/76.0.3809.87 Safari/537.36
Accept: text/html,application/xml;q=0.9,_/_;q=0.8
Accept-Language: pt-br
Accept-Encoding: gzip,deflate
Accept-Charset: utf-8;q=0.7,\*;q=0.7
Keep-Alive: 300
Connection: keep-alive
Pragma: no-cache
Cache-Control: no-cache

nome1=vanessa&nome2=gabriel

Exemplo de resposta do servidor:

HTTP/1.1 200 OK
Date: Mon, 27 Jul 2009 12:28:53 GMT
Server: nginx
Content-Length: 17
Content-Type: text/html; charset=utf-8
Connection: close

<h1>OLA CDF!</h1>
