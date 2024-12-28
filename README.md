# Projeto_Dio_Criando-um-Podcast-com-IAs-Generativas 🤖🎙️

<p align="justify">
O presente trabalho faz parte de um dos entregáveis do bootcamp "CAIXA - IA Generativa com Microsoft Copilot", especificamente da seção "Projetos Práticos com IA" e consiste na criação de um Podcast utilizando ferramentas de IA.

Acesso à plataforma: [DIO](https://dio.me)
  
</p>

> ℹ️ **NOTA_1:** Este repositório é para fins de aprendizado. O autor não se responsabiliza pelas informações aqui fornecidas.
<br/>

## Índice 🗃️
- [Tecnologias utilizadas no projeto](#tecnologias_utilizadas_no_projeto)
- [Passo-a-Passo](#passo_a_passo)
- [Resultados](#resultados)
- [Discussão](#discussao)
- [Conclusão](#conclusao)
- [Referências Úteis](#referencias_uteis)
- [Licença](#licenca)
- [Autor](#autor)

## Tecnologias utilizadas no projeto 💻

- [ChatGPT](https://chat.openai.com/) -- Geração de conteúdo e imagens
- [Copilot](https://copilot.microsoft.com/) -- Geração de conteúdo e imagens
- [ImagineArt](https://www.imagine.art) -- Geração de imagens (substituto do MidJourney)
- [Clipchamp](https://clipchamp.com/en/) -- Conversor de texto em fala e editor de vídeo/audio


## Passo-a-Passo

> 1️⃣ **PROMPT #1 [COPILOT] - Usando "Act Commands" para direcionar e explorar as capacidades da ferramenta:**
> Copilot, você agora é um especialista em github, prompt engineering, chatgpt, copilot, imagineArt, elevenlabs, clipchamp, entrevistas de emprego e apresentador de podcasts.
<br/>

> 2️⃣ **PROMPT #2 [COPILOT] - Estruturando a base de prompts:**
> Crie uma estrutura de prompt utilizando a técnica FTAE para que eu possa fazer prompts mais precisos para o projeto que vamos construir.
<br/>

> 3️⃣ **PROMPTs #3 [COPILOT] - Geração de títulos:**
> 3a - Função: Gerar títulos criativos para um novo podcast sobre entrevistas de emprego. Tópico: Entrevistas de emprego. Ação: Liste 10 títulos inovadores que vão capturar a atenção do ouvinte. Expectativa: Liste 10 títulos inovadores que vão capturar a atenção do leitor / público-alvo (profissionais que estão em busca do primeiro emprego ou recolocação profissional). {Regras} > O título deve ser profissional. > O título deve ser igual ao que um profissional de recursos humanos, especialista em recolocação profissional escrevreria.
> 3b - Combine os títulos anteriores e crie versões mais impactantes.
>>>**Output escolhido:** "Entrevistas de Emprego: Seu Passaporte para uma Nova Carreira"
>>>ℹ️ **NOTA_2:** O que foi ensinado na DIO é que FTAE significa função, tipo de texto, assunto e estilo.
<br/>

> 4️⃣ **PROMPT #4 [COPILOT]:**
>"Função: Escrever um prompt para gerar uma imagem para a capa de um podcast no tema "Entrevistas de Emprego: Seu Passaporte para uma Nova Carreira". Tópico: "Entrevistas de Emprego: Seu Passaporte para uma Nova Carreira". Ação: Gerar 4 prompts que podem ser utilizados para gerar uma imagem para a capa de um podcast no tema "Entrevistas de Emprego: Seu Passaporte para uma Nova Carreira". Expectativa: > O prompt deve ser de fácil entendimento para as ferramentas Copilot, ChatGPT e ImagineArt (alternativa ao MidJourney) > O prompt deve ser capaz de fazer essas ferramentas gerarem imagens profissionais e realistas. > O público-alvo das imagens que o prompt deve gerar são profissionais que estão em busca do primeiro emprego ou recolocação profissional. > A imagem deve ser suficientemente boa para ser parte de um podcast que será carregado em plataformas de streaming como Spotify, soundcloud, youtube. > A imagem deve ter uma alta resolução."
>>**Output escolhido:** Prompt 3: "Um jovem profissional sorridente sendo entrevistado, com uma mesa de escritório e ferramentas de trabalho ao fundo. A imagem deve incluir elementos de tecnologia e comunicação, destacando a preparação e a oportunidade. Use cores acolhedoras e alta definição."
<br/>

>5️⃣ **PROMPT #5 [COPILOT], [ChatGPT], [ImagineArt] - Geração de capas para o Podcast:**
>Desenvolva uma capa para um podcast que contenha um jovem profissional sorridente sendo entrevistado, com uma mesa de escritório e ferramentas de trabalho ao fundo. A imagem deve incluir elementos de tecnologia e comunicação, destacando a preparação e a oportunidade. Use cores acolhedoras e alta definição.
>>**Output escolhidos:** Os outputs escolhidos estão na pasta "assets".
>>Copilot -- Gerou 1 imagem
>>ChatGPT -- Gerou 1 imagem
>>ImagineArt -- Gerou 4 imagens
>>>ℹ️ **NOTA_3:** O ImagineArt possui configurações para ajuste da geração das imagens. As relevantes para geração de imagens similares foram Models: "Instagram"; Aspect Ratio: "16:9"; Effects/Lighthing: "Natural"; Enhance Prompt: Ligado.
>>>ℹ️ **NOTA_4:** O ImagineArt gerou imagens extremamente realistas.
<br/>

>6️⃣ **PROMPT #6 [COPILOT], [ChatGPT] - Geração do Roteiro do Podcast:** <br/>
>Contexto: Copilot/ChatGPT, você agora é um especialista em github, prompt engineering, chatgpt, copilot, imagineArt, elevenlabs, clipchamp, entrevistas de emprego e apresentador de podcasts. Você agora é principalmente um roteirista de podcast renomado. <br/>
>Função: Criar um roteiro de podcast cujo tema é "Entrevistas de Emprego: Seu Passaporte para uma Nova Carreira". <br/>
>Tópico: "Entrevistas de Emprego: Seu Passaporte para uma Nova Carreira". <br/>
>Ação: Gerar um roteiro profissional de podcast no tema "Entrevistas de Emprego: Seu Passaporte para uma Nova Carreira". <br/>
>Expectativa:<br/>
> O roteiro deve ser profissional.
> O público-alvo são profissionais que estão em busca do primeiro emprego ou recolocação profissional.
 > O roteiro deverá ser ótimo o suficiente para ser publicado em plataformas como Spotify, soundcloud, youtube.
 > O podcast será apresentado somente por uma pessoa o “Guru Job”
> O podcast não terá mais do que 5 minutos.
> Considera que o texto gerado será convertido para áudio posteriormente.
> A estrutura do roteiro deve ser: <br/>
>[DISCLAIMER] <br/>
>[BOAS-VINDAS] <br/>
>[INTRODUÇÃO DO TEMA] <br/>
>[DESAFIOS AO SE ARRUMAR EMPREGO] <br/>
>[DICA #1] <br/>
>[DICA #2] <br/>
>[DICA #3] <br/>
>[RESUMO/CONCLUSÃO] <br/>
>[DESPEDIDA] <br/>
>{REGRAS} <br/>
>- No bloco [DISCLAIMER], que deve ser considerado como um bloco alheio e anterior ao início do podcast,  substitua por um aviso que o conteúdo do podcast foi gerado por inteligências artificial e que o autor do projeto não se responsabiliza pelo uso da informações contidas no mesmo.
>- No bloco [BOAS-VINDAS] substitua por boas-vindas no estilo talk-show, o nome do podcast é o “Empregando Cast” e o apresentador é o “Guru Job”;
>- No bloco [INTRODUÇÃO DO TEMA] substitua por uma introdução do tema “Mercado de trabalho brasileiro” e “Entrevistas de Emprego”, focando mais na parte de entrevistas de emprego que será o foco do episódio do podcast;
>- No bloco [DESAFIOS AO SE ARRUMAR EMPREGO], destaque os principais desafios para se arrumar o primeiro emprego e/ou se recolocar profissionalmente após uma demissão;
>- No bloco [DICA #1] substitua por uma dica de como superar os problemas do bloco [DESAFIOS AO SE ARRUMAR EMPREGO] e forneça um exemplo prático de como utilizar essa solução em uma entrevista de emprego.
>- No bloco [DICA #2] substitua por uma outra dica de como superar os problemas do bloco [DESAFIOS AO SE ARRUMAR EMPREGO] e forneça um exemplo prático de como utilizar essa solução em uma entrevista de emprego.
>- No bloco [DICA #3] substitua por uma outra dica de como superar os problemas do bloco [DESAFIOS AO SE ARRUMAR EMPREGO] e forneça um exemplo prático de como utilizar essa solução em uma entrevista de emprego.
>- No bloco [RESUMO/CONCLUSÃO] substitua por um resumo das dicas anteriores.
>- No bloco [DESPEDIDA] substitua por uma despedida animada do podcast pelo apresentador, fazer um trocadilho com o tema que foi apresentado e aproveite para pedir que as pessoas sigam o podcast nas redes sociais e indiquem o perfil Luiz Lima - Q&R | VSC / CSV | Compliance & Melhoria Contínua - https://www.linkedin.com/in/luizslima/ como uma fonte de dicas para responder as principais entrevistas de emprego. <br/>
>{REGRAS NEGATIVAS} <br/>
>- Não use muitos termos técnicos
>- Não ultrapasse 5 minutos de duração"
>>**Output escolhido:** Conteúdo gerado pelo ChatGPT.
<br/>

>7️⃣ **AÇÃO #1 - Geração do áudio [ClipChamp]:**
>Conversão do texto para áudio utilizando a ferramenta mencionada.
<br/>

>8️⃣ **AÇÃO #2 - Edição do áudio [ClipChamp]:**
>Edição final do áudio.
>Upload de arquivos para o GitHub.
>Finalização das seções presentes na página (resultados, discussão, conclusão, autor)
<br/> 


## Resultados 🔎📊
<p align="justify">
O resultado do presente trabalho foi o conteúdo presente nesse arquivo readme.md e a gravação "Project - PodCast DIO - Entrevistas de Emprego - Luiz Lima", que se encontra na pasta "outputs" de respositório.
As imagens geradas por IA que eventualmente seriam utilizadas como capa e uploads em plataformas de streaming estão na pasta "assets".
</p>


## Discussão 📑
<p align="justify">
>ℹ️ **NOTA_:** A discussão aqui fornecida não foi gerada por ferramentas de IA. Caso contrário, perderia o propósito de discutir o uso da IA em si para a preparação do e-book e partes desse trabalho/projeto.

> Ao preparar o podcast com auxílio de ferramentas de IA, houve uma sinergia com o conteúdo apresentado durante o bootcamp "CAIXA - IA Generativa com Microsoft Copilot" da DIO, especificamente da seção "Projetos Práticos com IA" onde as expectativas foram estabelecidas logo de início:

> - As ferramentas de IA são **ferramentas** para auxílio e aumento da produtividade (pelo menos no momento atual em que esse trabalho foi elaborado).
> - As ferramentas de IA possuem um resultado que pode ser refinado e aproveitado muito melhor por alguém que possui conhecimento do tema sendo tratado, onde o indivíduo com conhecimento da temática será capaz de definir a qualidade dos outputs gerados pela IA e refinar os prompts conforme a necessidade para resultados mais interessantes.

> Foi possível notar ainda que as ferramentas utilizadas trazem particularidades em suas capacidades:
>> - O Copilot aparenta sair-se melhor em habilidades de sintetizar e organizar a informação, sua capacidade de roteirizar e concatenar/cadenciar as ideias contidas no prompt (Prompt #6) foram de certa forma frustrantes.
>> - O ChatGPT foi **incrível** em sua capacidade de concatenar/cadenciar as ideias/conteúdo do prompt apresentado no STEP 6 (Prompt #6). Não houve necessidade de alterar o conteúdo de fala que foi utilizado na gravação "Project - PodCast DIO - Entrevistas de Emprego - Luiz Lima", foi algo realmente impressionante.
>> - O Imagine Art, com todas as suas capacidades de parametrização, se mostrou uma ferramenta excelente para geração de imagens de acordo com a preferência do usuário, atuando como um ótimo substituto para o Midjourney. No entanto, o realismo que as imagens apresentaram na geração de pessoas foi, de certa forma, preocupamente. As pessoas geradas poderiam facilmente serem tidas como pessoas reais, o que abre espaço para o mau uso da ferramenta por pessoas mal intencionadas.
>> - O Microsoft ClipChamp possui capacidades de conversão de texto para voz que foram suficientes para o projeto,  não havendo a necessidade de usar a ferramenta ElevenLabs, que foi removida do projeto. Além disso, a ferramenta é um editor de vídeo e audio, então a praticidade de ter tudo em apenas uma ferramenta é uma facilidade que ajuda muito o criador de conteúdo. A biblioteca de sons gratuitos também é muito boa. A ferramenta foi/é bem intuitiva e de fácil uso, isso é corroborado pelo fato que foi a primeira vez do autor deste projeto em contato com a ferramenta.

</p>

## Conclusão 📝💡
<p align="justify">
A experiência com as ferramentas de IA utilizadas na preparação do podcast foi enriquecedora e alinhada às expectativas definidas no bootcamp "CAIXA - IA Generativa com Microsoft Copilot". Ficou claro que essas tecnologias, embora ainda dependam da curadoria humana para maximizar seu potencial, são ferramentas poderosas para amplificar a produtividade e elevar a qualidade do trabalho.<br/>
Além disso, a versatilidade e a praticidade de ferramentas como o Imagine Art e a do Microsoft ClipChamp evidenciam como as ferramentas de IA estão se consolidando como aliadas estratégicas na criação de conteúdo. No entanto, as preocupações éticas, como o realismo impressionante de imagens geradas de pessoas e o áudio com voz similar a humana, reforçam a necessidade de um uso responsável dessas tecnologias.<br/>
Mas, em linhas gerais, essa integração de IA ao processo criativo não apenas tornou o trabalho mais eficiente, mas também serviu como uma oportunidade para explorar as potencialidades e limitações das ferramentas, proporcionando um aprendizado valioso para o autor em projetos futuros. <br/>

</p>

## Referências Úteis 📚
- [As 50 perguntas de entrevista de emprego mais comuns ( parte 1 de 3)](https://www.linkedin.com/pulse/50-perguntas-de-entrevista-emprego-mais-comuns-parte-1-luiz-lima/?trackingId=M0hyKwzjRNKiyO4Nnx2Njw%3D%3D) <br/> 
- [As 50 perguntas de entrevista de emprego mais comuns ( parte 2 de 3)](https://www.linkedin.com/pulse/50-perguntas-de-entrevista-emprego-mais-comuns-parte-2-luiz-lima/?trackingId=M0hyKwzjRNKiyO4Nnx2Njw%3D%3D) <br/> 
- [As 50 perguntas de entrevista de emprego mais comuns ( parte 3 de 3)](https://www.linkedin.com/pulse/50-perguntas-de-entrevista-emprego-mais-comuns-parte-3-luiz-lima-hipff/?trackingId=M0hyKwzjRNKiyO4Nnx2Njw%3D%3D) <br/> 
  

## Licença 📄
<p align="justify">
N/A
</p>

## Autor 🤓
<p align="justify">
Luiz Lima - Q&R | VSC / CSV | Compliance & Melhoria Contínua - https://www.linkedin.com/in/luizslima/  
</p>
