# Análise de Sentimentos com Language Studio no Azure AI

## Crie um recurso de idioma

Abra o portal do Azure em https://portal.azure.com, entrando com a conta da Microsoft associada à sua assinatura do Azure.

Clique no botão ＋Criar um recurso e procure por serviço de idioma. Selecione criar um plano de serviço de idiomas. Você será levado a uma página para selecionar recursos adicionais. Mantenha a seleção padrão e clique em Continuar para criar seu recurso.

Na página Criar Idioma, configure-o.

Selecione Revisar + criar e depois Criar e aguarde a conclusão da implantação.

## Configure seu recurso no Azure AI Language Studio

Abra o Language Studio em https://language.cognitive.azure.com e entre.

Quando solicitado com Selecione um recurso do Azure, faça as seguintes configurações:

Diretório Azure: Diretório Padrão, o diretório que você está usando
Assinatura do Azure: selecione a assinatura que você está usando
Tipo de recurso: Idioma
Nome do recurso: selecione o recurso de serviço de idioma que você acabou de criar

Em seguida, selecione Concluído.

## Analise avaliações no Language Studio

Navegue até Language Studio em https://language.cognitive.azure.com.

Na página inicial Bem-vindo ao Language Studio, selecione a guia Classificar texto e, em seguida, selecione o bloco Analisar sentimento e extrair opiniões.

Em Selecionar idioma do texto, selecione Português.

Em Selecione o seu recurso Azure, selecione o seu recurso.

Em Digite seu próprio texto:

> Hotel Gran Corona
> São Paulo, Brasil
> 
> A localização é do lado da Estação da República (metrô). O hotel é fácil de localizar (o que facilita para quem não conhece a cidade). Hotel bem silencioso, apesar de se localizar em uma região mais agitada do centro. O pessoal do hotel foi bem tranquilo, inclusive quando pedi para estender mais um dia. Os quartos parecem bastante com as fotos, e apesar de eu gostar de um chuveiro mais forte, o cômodo quarto era bem espaçoso. E tem luz boa tanto no espelho do banheiro como na escrivaninha. Voltaria.

Marque a caixa para confirmar que a demonstração incorrerá em uso e poderá incorrer em custos e selecione Executar.

Revise a saída. 

## Limpar

Se você não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.
