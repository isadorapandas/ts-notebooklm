# ts-notebooklm
Caderno temático sobre a artista Taylor Swift criado via NotebookLM para fins de aprendizado do curso "Explore o Poder do NotebookLM" da DIO. 

*CONTEXTO E OBJETIVO(S)*: Criar um espaço de conhecimento, com fontes confiáveis, sobre a história de vida e carreira de Taylor Swift, como forma de acesso interativo aos interessados pelo conteúdo. A curadoria da bibliografia foi baseada principalmente no impacto da cantora como compositora e artista na indústria musical, além de sua influência na cultura pop mundial até os dias atuais. 

*FONTES PRINCIPAIS UTILIZADAS*: 
- Taylor Swift Brasil: https://taylorswift.com.br/
- Swiftie Cast: https://open.spotify.com/show/77dCNfJDGYa8GzcwqiodfY?si=ebe4e899c977407e

Obs.: Todas as fontes utilizadas foram a partir desses dois domínios principais, como:
- https://open.spotify.com/episode/0wikZ3ryGCmbvDv1SszTZ2?si=20e9dee2eb0f4180
- https://taylorswift.com.br/taylor-swift-registra-voz-e-imagem-como-marca-registrada-para-se-proteger-contra-inteligencia-artificial/
- https://taylorswift.com.br/billboard-afirma-que-taylor-swift-e-a-maior-estrela-pop-do-mundo-atualmente/
- https://taylorswift.com.br/karma-youll-all-get-yours-videos-da-infame-ligacao-entre-kanye-west-e-taylor-swift-vazam-na-internet/

Para facilitar o acesso da IA às letras dos álbuns da cantora, foi criado o arquivo todas_as_letras_ts.txt com as letras de todas as músicas de todos os seus álbuns (versões originais e traduzidas). Para tal, foi utilizado o código em Python (letras-taylor.py) para extrair de cada aba do site do TSBR, dedicadas a cada álbum. Porteriormente, o arquivo .txt foi adicionado como fonte no Notebook LM.

Conforme novas fontes foram sendo adicionadas ao Notebook, respostas mais embasadas e completas foram fornecidas. 
Alguns prompts solicitados foram: 

- **"Qual é o impacto de Taylor Swift na indústria musical?"**

*Taylor Swift revolucionou a indústria ao lutar pela propriedade intelectual, criando o projeto "Taylor's Version" para recuperar o controle de seus masters. Esse movimento forçou grandes gravadoras a revisarem contratos, tentando dificultar regravações futuras de novos artistas. Em 2018, ela garantiu a "Cláusula Taylor Swift", obrigando a UMG a distribuir lucros de ações do Spotify com todos os seus músicos. A "The Eras Tour" quebrou recordes históricos, tornando-se a turnê mais lucrativa da história ao arrecadar mais de US$ 2 bilhões. Ela inovou na distribuição cinematográfica ao negociar o filme da turnê diretamente com cinemas, ignorando estúdios tradicionais. Swift foi pioneira ao registrar sua voz e imagem como marcas para se proteger contra o uso indevido de Inteligência Artificial. Como compositora, elevou a narrativa confessional ao nível de arte literária, sendo incluída no hall dos maiores compositores vivos. Sua dominância comercial revitalizou o mercado de discos de vinil, alterando padrões de consumo e vendas mundiais. Através do documentário Miss Americana, ela transformou a percepção pública sobre o engajamento político e ativismo de artistas pop. Sua trajetória consolidou a ideia de que a autonomia e a transparência com os fãs são ferramentas poderosas de negociação.*

- **"De qual música é a letra: "you're hanging from my lips like the gardens of babylon""**

*Essa letra pertence à música "cowboy like me". A canção faz parte do nono álbum de estúdio de Taylor Swift, o evermore, lançado em dezembro de 2020. Na composição, Swift utiliza a metáfora dos Jardins da Babilônia para descrever a natureza de um relacionamento entre dois "bandidos" ou "vigaristas" que acabam se apaixonando. A letra explora a ideia de que, para esses personagens acostumados a enganar os outros, o amor verdadeiro parece ser o "golpe mais doce" (sweetest con) de todos. O álbum é descrito como uma "irmã mais nova" do folklore e foca em atmosferas místicas e narrativas ficcionais complexas.*

- **"Fale sobre a música "marjorie""**

*A música "marjorie" é a 13ª faixa do nono álbum de estúdio de Taylor Swift, o evermore (2020). Ela é descrita como uma das canções mais profundas e emocionais da discografia da artista, servindo como uma homenagem à sua avó materna, Marjorie Finlay. Aqui estão os detalhes principais sobre a obra, conforme documentado nas fontes:*

*1. Inspiração e Conexão Familiar*

- *A Avó Marjorie: Marjorie Finlay foi uma cantora de ópera que influenciou Taylor Swift a começar a se apresentar em karaokês e festivais quando ela tinha apenas 10 anos. A conexão com a avó é um tema central na vida pessoal de Taylor, e fotos de Marjorie decoram seu apartamento em Nova York.*
- *Presença Sonora: Um dos detalhes mais tocantes da faixa é que ela inclui gravações reais da voz de Marjorie Finlay cantando ópera, permitindo que avó e neta "dividam" a canção.*

*2. Temas e Composição Lírica*

*A letra da música explora o luto, a sabedoria passada entre gerações e o arrependimento por não ter aproveitado mais o tempo com quem se foi:*

- *Conselhos de Vida: O refrão traz conselhos atribuídos à avó, como: "Nunca seja tão gentil a ponto de esquecer de ser esperta / Nunca seja tão esperta a ponto de esquecer de ser gentil".*
- *A Dor da Perda: Taylor canta sobre a dificuldade de aceitar a morte, afirmando que "o que morreu não permaneceu morto / você está viva na minha cabeça".*
- *Arrependimentos: A canção descreve o desejo de Taylor de ter feito mais perguntas à avó enquanto ela estava viva: "Eu deveria ter te feito perguntas / Eu deveria ter te perguntado como ser".*

*3. Impacto na "The Eras Tour" e Documentário*

- *Performance Emocional: Na The Eras Tour, a música faz parte do bloco dedicado aos álbuns folklore e evermore (frequentemente fundidos como o ato "folkmore"). Durante as apresentações, os fãs costumam ligar as luzes dos celulares em um tributo silencioso que emociona a plateia e a própria Taylor.*

