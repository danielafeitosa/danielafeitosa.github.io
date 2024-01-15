---
title: Caracterização de Sustentabilidade e Abertura do Software para Pesquisa na Universidade
theme: simple
layout: "seed"
---

<!-- -------------------------------- -->

<section>

#### Caracterização de Sustentabilidade e Abertura do Software para Pesquisa na Universidade

<small>
_Apresentação para banca de qualificação de mestrado do Programa de Pós-graduação em Ciência da Computação da Universidade Federal da Bahia._
</small>


<p class=authors>Daniela Soares Feitosa</p>

<p class=authors><span style="color:#3d3d3d">Orientadora: Dra. Christina von Flach G. Chavez</span></p>

<p style="text-align:center">
<small><span style="color:#3d3d3d">Salvador/BA, 15 de Janeiro de 2024</span></small>
</p>

{% include footer-slides.html page="capa" %}

</section>

<!-- -------------------------------- -->

<section data-background="#fff7f0">

  <section>

  {% include header-slides.html page="default" %}

  <h3>Definições</h3>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Definições" %}

   <h4>Ciência Aberta</h4>

   <p class="box-gray">Prática da Ciência na qual outros podem colaborar e contribuir, com publicações, dados, software e outros artefatos de pesquisa disponíveis online e gratuitamente, no longo prazo, com base em termos que permitam a sua reutilização e redistribuição, e a reprodução da pesquisa.</p>

  <aside class="notes">
 ``um  construto  inclusivo  que  combina  vários  movimentos  e  práticas  que  têm  o  objetivo  de   disponibilizar   abertamente   conhecimento   científico   multilíngue,   torná-lo  acessível  e  reutilizável  para  todos,  aumentar  as  colaborações  científicas  e  o  compartilhamento de informações para o benefício da ciência e da sociedade, e abrir os processos de criação, avaliação e comunicação do conhecimento científico a atores da sociedade, além da comunidade científica tradicional (UNESCO, 2021)
  </aside>

  <small>
    Recomendação da UNESCO sobre Ciência Aberta (UNESCO, 2021).
  </small>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Definições" %}

  <h4>Software para Pesquisa</h4>

   <p class="box-gray">O software desenvolvido durante o processo de pesquisa e inclui (mas não está limitado a) código-fonte, algoritmos, scripts, fluxos de trabalho computacionais e executáveis.</p>
   <small>GRUENPETER et al., 2021.</small>

  <aside class="notes">
  Geral - o software utilizado durante a pesquisa científica,
  incluindo o software de terceiros usado para coleta, processamento
  e análise de dados (ALLEN et al., 2017)
  Mais restrito - sistemas operacionais, bibliotecas, dependências,
  pacotes e scripts sem intenção clara de pesquisa (GRUENPETER et al., 2021)
  </aside>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Definições" %}

  <h4>Sustentabilidade do Software para Pesquisa</h4>

   <p class="box-gray">O software para pesquisa para ser considerado sustentável deve permanecer disponível e funcional para a comunidade científica durante períodos de tempo significativos, permitindo a reprodutibilidade dos estudos que o utilizaram..</p>

  <small>
    Recomendação da UNESCO sobre Ciência Aberta (UNESCO, 2021).
  </small>

  <aside class="notes">
  Cinco dimensões da sustentabilidade: recursos ambientais, social, bem-estar individual, prosperidade econômica e viabilidade técnica de longo prazo (Becker et al. 2015).
  A sustentabilidade de software está associada a assegurar que o software continue funcional para seus usuários ao longo do tempo, considerando também sua manutenção, inclusão de novos recursos, reparo de \textit{bugs}, e adaptações a novos ambientes de software e hardware
  </aside>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Definições" %}

  <h4>Abertura do Software para Pesquisa</h4>

  <p class="box-gray"><small>Aderência aos princípios FAIR (FAIRness), tornando-os mais fáceis de encontrar, acessíveis, interoperáveis e reutilizáveis (**F**indable, **A**ccessible, **I**nteroperable, **R**eusable ).</small></p>

  <small>
    WILKINSON et al., 2016.
  </small>

   <p class="box-gray"><small>Reformulação dos princípios FAIR para dados abertos, definindo 17 Princípios FAIR para Software de Pesquisa (FAIR4RS)</small></p>

  <small>
    LAMPRECHT et al., 2020; HONG et al., 2022; BARKER et al., 2022
  </small>

  </section>


</section>

<!-- -------------------------------- -->

<section data-background="#fff7f0">

  <section>

  {% include header-slides.html page="default" %}

  <h3>Problema</h3>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Problema" %}

  <h4>Impacto na confiabilidade e reprodutibilidade de pesquisas</h4>

   <p class="box-gray">A sustentabilidade e a abertura (aderência aos princípios _FAIR_) dos artefatos de pesquisa, incluindo software, são consideradas essenciais para a confiabilidade e a reprodutibilidade da pesquisa.</p>

  <small>
    Recomendação da UNESCO sobre Ciência Aberta (UNESCO, 2021)
  </small>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Problema" %}

  <h4>Indisponibilidade de artefatos de pesquisa em projetos de pesquisa financiados</h4>

  <p class="box-gray">Informações importantes como dados, fluxos de trabalho, código-fonte do software e outros artefatos da pesquisa nem sempre estão disponíveis, mesmo para projetos de pesquisa financiados por agências e fundações de pesquisa.</p>

  <small>
    A Survey of the state of the practice for Research Software in the United States (CARVER et al., 2022)
  </small>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Problema" %}

  <h4>Falta de conhecimento sobre a prática atual em universidades</h4>

  <p class="box-gray">É importante conhecer e reportar a prática atual em universidades, laboratórios de pesquisa e na indústria sobre o desenvolvimento de software para pesquisa e avaliar sua sustentabilidade e abertura para pesquisas de longo prazo.</p>

  <small>
    Software Sustainability: Beyond the Tower of Babel (VENTERS et al.)
  </small>
  <small>
    A Survey of the state of the practice for Research Software in the United States (CARVER et al., 2022)
  </small>

  </section>

</section>

<!-- -------------------------------- -->

<section>

{% include header-slides.html page="default" %}

### Objetivo Geral

<p>Caracterizar grupos de pesquisa de diferentes áreas do conhecimento da Universidade Federal da Bahia (UFBA),
com respeito ao uso de práticas de Ciência Aberta e à abertura e sustentabilidade do _software para pesquisa_ desenvolvido por pesquisadores de tais grupos, no contexto de uso crescente de princípios e práticas da Ciência Aberta e valorização do software para pesquisa.</p>


</section>
<!-- -------------------------------- -->

<section>

{% include header-slides.html page="default" %}

### Objetivos Específicos

  <p class="item-list"><span>01.</span> Compreender como conceitos, princípios e práticas de **Ciência Aberta** são percebidos por líderes de grupos de pesquisa.</p>

</section>

<!-- -------------------------------- -->

<section>

{% include header-slides.html page="default" %}

### Objetivos Específicos

  <p class="item-list"><span>02.</span> Compreender como conceitos de **sustentabilidade**, **abertura**, e **práticas** relacionadas ao desenvolvimento de _software para pesquisa_ sustentável e aberto são percebidos por líderes de grupos de pesquisa.</p>

</section>

<!-- -------------------------------- -->

<section>

{% include header-slides.html page="default" %}

### Objetivos Específicos

  <p class="item-list"><span>03.</span> Caracterizar _software para pesquisa_ desenvolvido pelos grupos de pesquisa em relação a sustentabilidade e abertura.</p>

</section>

<!-- -------------------------------- -->

<section>

{% include header-slides.html page="default" %}

### Objetivos Específicos

  <p class="item-list"><span>04.</span> Disseminar conceitos, princípios e práticas da Ciência Aberta, recomendações e boas práticas para o desenvolvimento de _software para pesquisa_ aberto e potencialmente sustentável.</p>


</section>

<!-- -------------------------------- -->

<section data-background="#fff7f0" data-transition="zoom">

  <section>

  {% include header-slides.html page="default" %}

  <h3>Questões de Pesquisa</h3>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Questões de pesquisa" %}

  <p class="item-list"><span>Q1:</span> Qual é a percepção de líderes de grupos de pesquisa da UFBA sobre Ciência Aberta e _software para pesquisa_?</p>
  <p class="fragment fade-up item-list subitem"><span>Q1.1:</span> Qual é a percepção sobre conceitos, princípios e práticas de Ciência Aberta?</p>
  <p class="fragment fade-up item-list subitem"><span>Q1.2:</span> Qual é a percepção sobre conceitos e práticas para o desenvolvimento de _software para pesquisa_ sustentável e aberto?</p>
  <p class="fragment fade-up item-list subitem"><span>Q1.3:</span> Quais são os incentivos e desafios para o grupo de pesquisa na adoção de práticas Ciência Aberta e para o desenvolvimento de software para pesquisa?</p>
  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Questões de pesquisa" %}

  <p class="item-list"><span>Q2:</span> Quão sustentável e aberto é o _software para pesquisa_ desenvolvido nos grupos de pesquisa da UFBA?</p>
  <p class="fragment fade-up item-list subitem"><span>Q2.1:</span> Quão sustentável é o _software para pesquisa_ desenvolvido nos grupos de pesquisa da UFBA?</p>
  <p class="fragment fade-up item-list subitem"><span>Q2.2:</span> Quão aberto é o _software para pesquisa_ desenvolvido nos grupos de pesquisa da UFBA?</p>
  </section>
</section>

<!-- -------------------------------- -->

<section data-background="#fffefb">

{% include header-slides.html page="default" %}

### Visão Geral da Pesquisa

<p style="text-align: center;max-height: 15em;">
  <img src="{{ site.baseurl }}/files/slides/fluxo.jpg" alt="Fluxo da pesquisa" style="max-height: 12em;" />
</p>


</section>

<!-- -------------------------------- -->

<section data-background="#fff7f0" data-transition="zoom">

  <section>

  {% include header-slides.html page="default" %}

  <h3>Contribuições Esperadas</h3>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Contribuições Esperadas" %}

  <h4>Gestores da UFBA</h4>

  <p>Servir como ponto de partida para um planejamento institucional sobre Ciência Aberta e condições necessárias para sua adoção na UFBA.</p>
  <p style="text-align:center"><img class="contributions" src="{{ site.baseurl }}/files/slides/managers.png" /></p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Contribuições Esperadas" %}

  <h4>Grupos de pesquisa da UFBA</h4>

  <p>Estimular auto-avaliação e melhorias no _software para pesquisa_ desenvolvido pelo grupo.</p>
  <p style="text-align:center"><img class="contributions" src="{{ site.baseurl }}/files/slides/research-group.png" /></p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Contribuições Esperadas" %}

  <h4>Pesquisadores</h4>

  <p>Estimular o reuso e adaptação para diferentes contextos e instituições, e auto-avaliação do _software para pesquisa_ desenvolvido.</p>
  <p style="text-align:center"><img class="contributions" src="{{ site.baseurl }}/files/slides/researcher.png" /></p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Contribuições Esperadas" %}

  <h4>Sociedade</h4>

  <p>Estimular a disseminação de conceitos, princípios e práticas da Ciência Aberta, conforme recomendação da UNESCO.</p>
  <p style="text-align:center"><img class="contributions" src="{{ site.baseurl }}/files/slides/sociedade.png" /></p>

  </section>
</section>

<!-- -------------------------------- -->

<section>

{% include header-slides.html page="default" %}

### Estratégia de Pesquisa

  <p class="item-list"><span>01.</span> Entrevista</p>
  <p class="item-list"><span>02.</span> Avaliação de Software</p>
  <p class="item-list"><span>03.</span> Síntese de Resultados</p>

</section>
<!-- -------------------------------- -->

<section data-background="#fff7f0" data-transition="zoom">

  <section>

  {% include header-slides.html page="default" %}

  <h3>Entrevista</h3>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Entrevista" %}

   <h4>Seleção de Participantes</h4>

   <p class="item-list">Líderes de grupos de pesquisa com envolvimento direto no desenvolvimento de software utilizado em seus grupos de pesquisa;</p>
   <p class="item-list subitem">Busca no Diretório dos Grupos de Pesquisa no Brasil do CNPq</p>
   <p class="item-list subitem">Citações de software na seção **Programas de computador registrado** ou **Programas de computador sem registro** do currículo do pesquisador na Plataforma Lattes.</p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Entrevista" %}

   <h4>Guia de Entrevista</h4>

  <p class="item-list">Entrevistas semiestruturadas com perguntas abertas;</p>
  <p class="item-list">Informações sobre o que é esperado de cada pergunta e questões de acompanhamento.</p>

  </section>

  <section>
  {% include header-slides.html page="subsection" parent="Entrevista" %}

   <h4>Análise dos Dados</h4>

   Codificação qualitativa descrito por Schreier (2012) para identificação de padrões combinando duas estratégias:
   <p class="item-list"><span>(i)</span> orientada por conceitos, ou seja, com base no que já sabemos;</p>
   <p class="item-list"><span>(ii)</span> orientada pelos dados, ou seja, deixando a codificação emergir das respostas.</p>

  </section>
</section>

<!-- -------------------------------- -->

<section data-background="#fff7f0" data-transition="zoom">

  <section>

  {% include header-slides.html page="default" %}

  <h3>Avaliação do Software</h3>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Avaliação do Software" %}

   <h4>Seleção do Software</h4>

   O líder de pesquisa entrevistado será solicitado a sugerir projetos de _software para pesquisa_ para avaliação e análise.

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Avaliação do Software" %}

   <h4>Avaliação de Sustentabilidade</h4>

   <p class="center">
    <img class="big" src="{{ site.baseurl }}/files/slides/dev-praticas.png" alt="Avaliação de sustentabilidade baseada em práticas" />
    <small>
      Avaliação de sustentabilidade do software para pesquisa baseada em práticas (FLACH et al., 2023).
    </small>
   </p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Avaliação do Software" %}

   <h4>Avaliação de Abertura</h4>

   <h5>Localizável (Findable)</h5>

   <p class="center">
    <img class="big" src="{{ site.baseurl }}/files/slides/fairness-f.png" alt="Avaliação de abertura baseada nos princípios FAIR" />
    <small>
      Princípios FAIR para Software (BARKER et al., 2022).
    </small>
   </p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Avaliação do Software" %}

   <h4>Avaliação de Abertura</h4>

  <h5>Acessível</h5>

   <p class="center">
    <img class="big" src="{{ site.baseurl }}/files/slides/fairness-a.png" alt="Avaliação de abertura baseada nos princípios FAIR" />
    <small>
      Princípios FAIR para Software (BARKER et al., 2022).
    </small>
   </p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Avaliação do Software" %}

   <h4>Avaliação de Abertura</h4>

   <h5>Interoperável</h5>

   <p class="center">
    <img class="big" src="{{ site.baseurl }}/files/slides/fairness-i.png" alt="Avaliação de abertura baseada nos princípios FAIR" />
    <small>
      Princípios FAIR para Software (BARKER et al., 2022).
    </small>
   </p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Avaliação do Software" %}

   <h4>Avaliação de Abertura</h4>

   <h5>Reusável</h5>

   <p class="center">
    <img class="big" src="{{ site.baseurl }}/files/slides/fairness-r.png" alt="Avaliação de abertura baseada nos princípios FAIR" />
    <small>
      Princípios FAIR para Software (BARKER et al., 2022).
    </small>
   </p>

  </section>

  <section>

  {% include header-slides.html page="subsection" parent="Avaliação do Software" %}

   <h4>Análise dos dados</h4>

   Faremos uma análise qualitativa de todas as tabelas preenchidas na avaliação de Sustentabilidade e Abertura do _software para pesquisa_ para respondermos a questão **Q2**

  </section>
</section>


<!-- -------------------------------- -->

<section>

{% include header-slides.html page="default" %}

### Síntese de Resultados

  <p class="item-list"><span>Por grupo de pesquisa:</span> síntese e discussão com base no cruzamento das entrevistas e a análise de documentos.</p>
  <p class="item-list"><span>Todos os grupos:</span> discussão geral sobre as práticas mais/menos utilizadas considerando todos os grupos.</p>

</section>

<!-- -------------------------------- -->

<section>

  {% include header-slides.html page="default" %}


   <h3>Estudo Piloto</h3>

   <h4>Desafios, Aprendizados e Ajustes</h4>

   <p class="item-list">Duração e Disponibilidade do Participante</p>
   <p class="item-list">Priorização de perguntas</p>
   <p class="item-list">Formulação de Perguntas Abertas</p>
   <p class="item-list">Falta de Domínio dos Conceitos</p>
   <p class="item-list">Avaliação manual do software</p>

</section>

<!-- -------------------------------- -->

<section data-background="#fff7f0" data-transition="zoom">

  <section>
  {% include header-slides.html page="default" %}


   <h3>Resultados Parciais</h3>

  </section>
  <section>

  {% include header-slides.html page="subsection" parent="Resultados Parciais" %}

   <h4>Publicações</h4>

   <h5 class="fragment fade-up">
     "Understanding Practices and Challenges of Developing Sustainable Research Software: A Pilot Interview"
     <br/><small>[Artigo] OpenScienSE, 2023. **DOI**: <span class="url">https://doi.org/10.5753/opensciense.2023.235677</span></small>
   </h5>

  <h5 class="fragment fade-up">
    "Understanding Practices and Challenges of Developing Sustainable Research Software: A Pilot Interview"
    <br/><small>[Artigo] OpenScienSE, 2023. **DOI**: <span class="url">https://doi.org/10.5753/opensciense.2023.235707</span></small>
  </h5>
  <h5 class="fragment fade-up">
     "Princípios e Práticas para Sustentabilidade do Software de Pesquisa"
     <br/><small>[Capítulo de livro] JAI, 2023. **DOI**: <span class="url">https://doi.org/10.5753/sbc.12853.0.3</span></small>

  </h5>


  </section>
  <section>

  {% include header-slides.html page="subsection" parent="Resultados Parciais" %}

   <h4>Depósito de artefatos de pesquisa</h4>

   Os artefatos da pesquisa, incluindo o guia da entrevista, a estrutura de codificação e a planilha com os grupos de pesquisa encontrados segundo a estratégia de seleção de participantes estão disponíveis no Zenodo:
   <p>DOI: <span class="url">https://doi.org/10.5281/zenodo.10467948</span></p>

  </section>
</section>

<!-- -------------------------------- -->

<section data-transition="zoom">

{% include header-slides.html page="default" %}

### Cronograma

<img src="{{ site.baseurl }}/files/slides/cronograma.png" alt="Cronograma" />

</section>

<!-- -------------------------------- -->

<section data-background="#ffc981">

#### Caracterização de Sustentabilidade e Abertura do Software para Pesquisa na Universidade

<p color="#fff">Daniela Soares Feitosa (PGCOMP-UFBA)</p>
<p><span class="url">dfeitosa@ufba.br</span></p>


<p><small>Disponível em:<span class="url"> https://danielafeitosa.github.io/caracterizacao-sustentabilidade-abertura-software-pesquisa</span><small></p>

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

{% include footer-slides.html page="capa" %}

</section>

<!-- -------------------------------- -->

<section>

{% include header-slides.html page="default" %}

### Créditos

  Imagens utilizadas nesta apresentação

  <p>Storyset: <span class="url">https://stories.freepik.com</span></p>

</section>