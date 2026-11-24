# Política de privacidade — Pega ou Passa

Última atualização: 24 de novembro de 2026

O Pega ou Passa é um aplicativo para motoristas de aplicativo calcularem o lucro das corridas. Ele não tem cadastro nem login. Os dados das corridas, das ofertas lidas, do veículo e do SOS **não são enviados para a internet**. As únicas exceções são as métricas de uso, os anúncios e a assinatura, descritos abaixo.

## Serviço de acessibilidade

Com a sua autorização, o Pega ou Passa usa a API de Acessibilidade do Android (AccessibilityService) para ler o texto das telas de oferta de corrida dos aplicativos **Uber Driver, 99 Motorista, inDrive, DiDi Motorista, iFood para Entregadores, Rappi Entregador, 99Food Entregador e Lalamove Driver**, e somente deles.

- **O que é lido:** o valor, a distância e o tempo da corrida oferecida. Quando o aplicativo de corrida não entrega o texto da oferta, o Pega ou Passa tira uma imagem da tela (Android 11 ou mais novo), somente com o aplicativo de corrida aberto, lê os números no próprio celular e descarta a imagem. Se a opção "Print de cada oferta" estiver ligada, a imagem da oferta fica guardada **só no seu celular**, no histórico de ofertas (os 300 prints mais recentes); você pode desligar essa opção quando quiser. Nenhuma imagem é enviada.
- **Para quê:** calcular o lucro estimado e mostrar o semáforo (verde, amarelo ou vermelho) num balão por cima do aplicativo de corrida.
- **O que não é feito:** o Pega ou Passa não aceita, não recusa, não clica e não digita nada em outros aplicativos. Não lê telas de outros aplicativos.
- **Para onde vai:** os dados são usados na hora, no próprio celular. Não são enviados, vendidos nem compartilhados.

O serviço pode ser desligado a qualquer momento em Configurações → Acessibilidade → Pega ou Passa.

## Leitura de prints

Quando você compartilha ou escolhe um print de uma oferta, o texto da imagem é reconhecido no próprio celular (ML Kit do Google, modelo instalado junto com o app). A imagem não é enviada para nenhum servidor nem guardada pelo Pega ou Passa.

## SOS e localização

A localização só é usada na tela de SOS, quando você a abre, para montar uma mensagem com o link do mapa. O Pega ou Passa não envia essa mensagem sozinho: ele abre o seu app de SMS ou WhatsApp com o texto pronto, e você decide se envia. A localização não é guardada nem rastreada em segundo plano.

Os contatos de confiança são escolhidos um a um na agenda. O app não lê a lista completa de contatos. O nome e o número escolhidos ficam guardados só no seu celular.

## Dados guardados no celular

O histórico de corridas, os gastos e ganhos que você lançar, as metas, os dados do veículo e os contatos de SOS ficam guardados apenas no armazenamento do aplicativo, no seu celular. Eles são apagados quando o aplicativo é desinstalado.

## Métricas de uso e falhas

Para melhorar o app, o Pega ou Passa envia ao desenvolvedor, de forma **anônima**, informações de uso e de falhas:

- um código aleatório criado na instalação (não é o seu nome, telefone, e-mail nem o ID de publicidade);
- versão do app, marca e modelo do celular, versão do Android, idioma e fuso horário, e se o app veio da Play Store;
- quando o app foi instalado e aberto, quais telas foram abertas e por quanto tempo, se o leitor de ofertas foi ligado, se a tela de assinatura foi aberta e se a assinatura foi feita;
- um resumo diário com **contagens**: quantas ofertas foram analisadas, quantas ficaram verdes, amarelas ou vermelhas, de quais aplicativos e quantos minutos o app de corrida ficou aberto;
- erros que fecharam o app e falhas do leitor, com a descrição técnica do erro.

Essas mesmas informações também são enviadas ao **Google Firebase**: o **Firebase Analytics** (estatísticas de uso, com o identificador do app no aparelho, informações do aparelho e país e região aproximados) e o **Firebase Crashlytics** (registro técnico do erro quando o app trava, com informações do aparelho e do sistema). O Google guarda esses dados pelo prazo definido no Firebase (até 14 meses para as estatísticas) e trata-os conforme a política dele: https://firebase.google.com/support/privacy.

**Não são enviados:** valores das corridas, endereços, localização, textos ou imagens das telas, contatos ou dados do SOS. Os dados ficam numa planilha do desenvolvedor (Google) e no Firebase, não são vendidos, e servem só para corrigir falhas e entender o uso do app. Para pedir a exclusão, escreva para o contato abaixo informando o código que aparece em Mais → Diagnóstico.

Se você tocar em "Enviar relatório" (Mais → Diagnóstico), o texto das últimas telas que o app não entendeu, que pode conter endereços e valores de ofertas, é enviado pelo aplicativo que você escolher (WhatsApp, e-mail), só quando você toca no botão.

## Anúncios

A versão gratuita mostra um banner do Google AdMob. Para exibir e medir os anúncios, o Google pode coletar o identificador de publicidade do aparelho, dados aproximados de localização pelo IP e informações de interação com o anúncio, conforme a política do Google: https://policies.google.com/technologies/ads. Você pode redefinir ou excluir o ID de publicidade nas configurações do Android. Assinantes não veem anúncios.

## Assinatura

A assinatura Pega ou Passa Pro é feita e cobrada pela Google Play. O Pega ou Passa não recebe nem guarda dados de pagamento. O teste grátis, a renovação e o cancelamento são controlados pela Google Play (Play Store → Pagamentos e assinaturas).

## Contato

patreseoficial@gmail.com
