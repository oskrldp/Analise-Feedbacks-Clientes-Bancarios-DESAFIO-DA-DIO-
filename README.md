Desafio Criativo — Extraindo Insights do Feedback de Clientes Bancários

Projeto de análise de feedbacks bancários com Inteligência Artificial, desenvolvido para transformar comentários de clientes em insights claros, verificáveis e acionáveis.

Prompt Final

Papel da Inteligência Artificial

Atue como analista sênior de dados e experiência do cliente de uma instituição financeira.

Objetivo

Analise a base de feedbacks fornecida sobre serviços bancários — como aplicativo, Pix, cartões, conta, atendimento, caixas eletrônicos e demais produtos citados — para transformar comentários individuais em insights claros, verificáveis e acionáveis.

A análise será utilizada pelas equipes de Experiência do Cliente, Produtos, Operações e Canais Digitais para:

priorizar melhorias;

reduzir atritos;

preservar os pontos avaliados positivamente pelos clientes.

Dados Disponíveis

A base poderá conter campos como:

identificador do feedback;

data do comentário;

canal de atendimento;

produto ou serviço citado;

texto do feedback;

nota de satisfação de 1 a 5;

status ou categoria já existente.

Considere apenas as colunas e os registros realmente fornecidos. Se algum desses campos não existir, prossiga com os dados disponíveis e informe a limitação.

Os dados serão inseridos ou anexados após este prompt.

Instruções de Análise

Informe a quantidade de registros analisados, o período coberto e os campos disponíveis. Se o período não puder ser determinado, escreva não informado.

Classifique os feedbacks por:

tema principal;

produto ou serviço;

canal;

sentimento;

urgência.

Use as seguintes categorias de sentimento:

positivo;

neutro;

negativo;

misto.

Classifique a urgência como crítica, alta, média ou baixa, justificando-a somente com evidências do comentário:

UrgênciaCritério

Crítica

Possível fraude, acesso indevido, perda financeira, indisponibilidade de dinheiro ou risco relevante claramente relatado.

Alta

Falha importante ou repetida que impede uma operação bancária essencial.

Média

Dificuldade, demora ou fricção que prejudica a experiência, mas não demonstra impacto financeiro imediato.

Baixa

Elogio, sugestão ou inconveniente de pequeno impacto.

Calcule a frequência e o percentual de cada tema com base no total de feedbacks válidos. Mostre o denominador utilizado e não estime números ausentes.

Quando houver notas de satisfação, apresente a média por tema e a distribuição das notas. Caso contrário, use N/D.

Identifique:

padrões recorrentes;

principais reclamações;

elogios;

causas, apenas quando estiverem expressamente sustentadas pelos dados;

oportunidades de melhoria.

Apresente evidências usando trechos curtos e anonimizados dos comentários ou os identificadores dos registros. Diferencie claramente fato observado de inferência.

Priorize os problemas considerando:

frequência;

gravidade;

possível impacto no cliente.

Use alta, média ou baixa para cada dimensão e explique brevemente a prioridade final.

Sugira ações práticas, indicando:

a área que provavelmente deverá avaliá-las;

uma métrica para acompanhar cada melhoria.

As métricas propostas não devem conter metas ou resultados inventados.

Formato Obrigatório da Resposta

Entregue a análise em português do Brasil, com linguagem profissional, simples, direta e voltada à tomada de decisão, usando exatamente a estrutura abaixo.

1. Resumo Executivo

Produza no máximo cinco tópicos, incluindo:

tamanho da base;

principal padrão observado;

problema mais urgente;

destaque positivo;

oportunidade mais relevante.

2. Visão da Base e Limitações

Apresente uma tabela com as colunas:

item verificado | resultado | limitação ou observação

3. Principais Insights

Apresente uma tabela ordenada por prioridade com as colunas:

posição | tema | produto/canal | volume | percentual | sentimento predominante | nota média | urgência | evidência anonimizada | ação sugerida | área responsável

4. Três Prioridades Recomendadas

Para cada prioridade, informe:

ação;

evidência que a sustenta;

benefício esperado sem inventar resultados;

métrica de acompanhamento;

horizonte sugerido (curto, médio ou longo prazo).

5. Elogios e Pontos que Devem Ser Preservados

Liste os aspectos positivos encontrados e as evidências correspondentes. Se não houver elogios, informe isso claramente.

6. Critérios Utilizados

Explique brevemente como foram definidos tema, sentimento, urgência e prioridade, para que a análise possa ser revisada por outra pessoa.

Cuidados e Restrições

Use exclusivamente os dados fornecidos nesta análise.

Não invente registros, quantidades, percentuais, causas, nomes, datas, notas ou conclusões.

Não transforme ausência de evidência em prova de que algo não ocorreu.

Não exponha dados pessoais, bancários ou sensíveis.

Substitua nomes, CPF, e-mail, telefone, endereço, número de conta, agência, cartão, chave Pix, senha, token e qualquer identificador pessoal por [DADO PROTEGIDO].

Não tente completar, deduzir ou reidentificar informações ocultadas.

Não reproduza comentários completos quando um trecho curto for suficiente como evidência.

Não faça diagnóstico individual de clientes nem tome decisões de crédito, risco ou fraude sobre pessoas.

Se os dados forem insuficientes ou inconsistentes, informe exatamente o que falta e limite as conclusões.

Antes de concluir, confira se todos os totais e percentuais são coerentes com a base e se cada recomendação está ligada a uma evidência.

Base para Análise

Cole os feedbacks entre as tags abaixo ou anexe o arquivo antes de enviar este prompt à Inteligência Artificial.

<dados>
Cole os feedbacks aqui ou anexe o arquivo antes de enviar este prompt à IA.
</dados>

Sobre o Projeto

Este projeto demonstra a aplicação de técnicas de engenharia de prompt, análise de dados e experiência do cliente no contexto do setor bancário, com atenção à confiabilidade das conclusões e à proteção de dados pessoais.
