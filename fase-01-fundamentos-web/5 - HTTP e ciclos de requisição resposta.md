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

Categoria	Exemplo	Significado
2xx	200 OK	Pedido bem-sucedido
3xx	301 Redirect	Redirecionamento
4xx	404 Not Found	Recurso não encontrado
5xx	500 Internal Server Error	Erro no servidor
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