# :brazil: Dissertação Mestrado


Esse repositório armazena os artefatos de texto gerados durante a elaboração da minha Dissertação de Mestrado pela PUC Minas.
Todos os artefatos foram escritos utilizando LaTex. :pray:

O texto faz parte do [acervo](https://bib.pucminas.br/acervo/560768) da Biblioteca da PUC Minas e pode ser diretamente acesado por este [link](https://bib.pucminas.br/teses/Informatica_PedroPongelupeLopes_30865_TextoCompleto.pdf), texto em inglês.

## Especificações Técnicas 
- **Título:** PondiônsTracker: A Framework based on GTFS-RT to identify delays and estimate arrivals dynamically in public transportation network
 - **Autor Principal:** Pedro Pongelupe Lopes
 - **Orientador:** Humberto Torres Marques-Neto
 - **Palavras-chave:**
    - Computação Urbana
    - Mobilidade Humana
    - Redes Complexas
    - Rede de Transporte Público
 - **Data da Defesa:** 04/12/2023
 - **Banca Examinadora:**
    - Prof. Dr. Humberto Torres Marques-Neto - PUC Minas (Orientador)
    - Prof. Dr. Silvio Jamil Ferzoli Guimarães - PUC Minas (Banca Examinadora)
    - Prof. Dr. Davide Bacciu - Università di Pisa (Banca Examinadora)

### Resumo
A Rede de Transporte Público de uma cidade inteligente provê serviços para milhoẽs de pessoas diariamente. A computação urbana disponibiliza um ferramental para realizar aquisição, integração e análise desse grande volume de dados gerados traduzindo-se em uma melhoria da mobilidade humana do cidadões sendo por notificar atrasos ou mitiga-los, por exemplo. Sobre a Rede de Transporte Público, muitos métodos são baseados em duas especidicações: General Transit Feed Specification (GTFS) e General Transit Feed Specification Real-Time (GTFS-RT). A primeira representa as informações estáticas sobre o cronograma das viagens e a segunda especificação introduz atualizações em tempo-real sobre viagens, serviços e posição dos veículos. Apesar do salto qualitativo com o GTFS-RT, esta especificaçãop não é tão bem adotada quanto o GTFS devido a inexistência de um identificador que conecte os dados estáticos e os de tempo-real. Nesse contexto, essa dissertação apresenta [PondiônsTracker](https://github.com/Pongelupe/PondionsTracker/) que é um framework Java de baixo acoplamento que enriquece o GTFS com os dados de tempo-real, possibilitando análise de atrasos e estimação de chegadas dinamicamente. Então, é criado o [PondiônsTracker-BH](https://github.com/Pongelupe/PondionsTracker-BH) que uma especialização para lidar com a Rede de Transporte Público de Belo Horizonte, qual foi coletado registros por onze dias em sequência entre Julho e Agosto de 2023, totalizando mais de 246 milhões de registros representando quase 30 Gigabytes. PondiônsTracker-BH teve 76.08% das viagens agendadas correspondidas com as coletadas durante o período observado. As 156.628 viagens correspondidas apontam a concetração de atrasos na cidade e que esses atrasos 
possuem uma relação espacial e temporal, além disso, eles seguem uma distribuição log-normal pela rede. Em outras palavras, a maioria dos atrasos da Rede de Transporte Público em Belo Horizonte acontecem em poucos pontos de ônibus, esses pontos estão próximos entre si e compartilham os mesmos padrões temporais.
 

# :us: Master Dissertation

This repository has all the textual artifacts generated throughout the development of mine Master Dissertation by PUC Minas.
All the artifacts were written using LaTex. :pray:

The manuscript is part of PUC Minas' Library [archive](https://bib.pucminas.br/acervo/560768) and it can be directly accessed in this [link](https://bib.pucminas.br/teses/Informatica_PedroPongelupeLopes_30865_TextoCompleto.pdf).

## Technical Specifications 
- **Title:** PondiônsTracker: A Framework based on GTFS-RT to identify delays and estimate arrivals dynamically in public transportation network
 - **Main Author:** Pedro Pongelupe Lopes
 - **Advisor:** Humberto Torres Marques-Neto
 - **Keywords:**
    - Urban Computing
    - Human Mobility
    - Complex Networks
    - Public Transportation Network
 - **Dissertation Defense Date:** 04/12/2023
 - **Examining Board:**
    - Prof. Dr. Humberto Torres Marques-Neto - PUC Minas (Advisor)
    - Prof. Dr. Silvio Jamil Ferzoli Guimarães - PUC Minas (Examining Board)
    - Prof. Dr. Davide Bacciu - Università di Pisa (Examining Board)

### Abstract
A smart city Public Transportation Network provides mobility services to millions of people daily. 
Urban computing provides a
toolkit to handle acquisition, integration, and analysis, which translates to the improvement of the human mobility
of the citizens, mitigating and notifying delays, for instance.
Regarding the PTN, many methods rely on two specifications: *General Transit Feed Specification* (GTFS) and *General Transit Feed Specification Real-Time* (GTFS-RT). The first represents the static schedule information, and the second introduces real-time updates from trips, services, and vehicle positions. Despite the qualitative leap with the GTFS-RT specification, GTFS-RT
is not as well-adopted as the GTFS because of the non-existence of a matching identifier between the static and real-time data. In this context, we present [PondiônsTracker](https://github.com/Pongelupe/PondionsTracker/) which is a **loose coupling** Java framework designed for enriching GTFS data with real-time data to enable delays analysis and to estimate arrivals. So, we present [PondiônsTracker-BH](https://github.com/Pongelupe/PondionsTracker-BH) that is a **PondiônsTracker**'s specialization created to
deal with Belo Horizonte's PTN particularities originating from Belo Horizonte's real-time Application Programming Interface (API) 
which we collected every minute for eleven days straight in July and August 2023, summarizing over 246 million entries 
representing almost 30 Gigabytes.
*PondiônsTracker-BH* presented a $76.08\%$ of the matched trips for the schedule during the observation period, 
then $156,628$ out of $205,884$ scheduled trips were identified in the real-time data. Analyzing these $156,628$ matched trips,
we show the delays focus and show that the delays in Belo Horizonte are spatial and temporal related
and are **log-normal** distributed. In other words, most of the delays in Belo Horizonte occur at a few bus stops, and these stops are *physically* close to each other and share the same *temporal* patterns.

