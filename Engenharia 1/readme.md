What precisely do we mean by software engineering? What distinguishes “software engineering” from “programming” or “computer science”? And why would Google have a unique perspective to add to the corpus of previous software engineering literature written over the past 50 years?

The terms “programming” and “software engineering” have been used interchangeably for quite some time in our industry, although each term has a different emphasis and different implications. University students tend to study computer science and get jobs writing code as “programmers.”

“Software engineering,” however, sounds more serious, as if it implies the application of some theoretical knowledge to build something real and precise. Mechanical engineers, civil engineers, aeronautical engineers, and those in other engineering disciplines all practice engineering. They all work in the real world and use the application of their theoretical knowledge to create something real. Software engineers also create “something real,” though it is less tangible than the things other engineers create.

Unlike those more established engineering professions, current software engineering theory or practice is not nearly as rigorous. Aeronautical engineers must follow rigid guidelines and practices, because errors in their calculations can cause real damage; programming, on the whole, has traditionally not followed such rigorous practices. But, as software becomes more integrated into our lives, we must adopt and rely on more rigorous engineering methods. We hope this book helps others see a path toward more reliable software practices.

1. Comentar com suas palavras o segundo trecho do livro Software Engineering at Google, Oreilly:
   
Comentário: É compreesível através da leitura da citação acima compreender que a engenharia é aquilo que transforma algo teórico em algo real, algo prático, com objetivo de melhorar ou desenvolver o ambiente ao seu redor (de acordo com cada área da engenharia). A engenharia de software assim como as demais, existe para que possamos através de softwares, criar, ou melhor nosso ambiente, de acordo com regras, boas práticas e objetivos distintos. Apesar dela não ser tão critica para vidas umas fisicamente, como por exemplo a engenharia aeronautica, a engenharia de software tem sim niveis criticos de preocupação, pois além de estar muito presente a todo momento em nossas vidas, ela pode oferecer riscos à nós em outras formas, como na proteção de dados, e até mesmo fisicos, através de hacking de máquinas e equipamentos que podem ser utilizados de forma criminosa.

Programming Over Time We propose that “software engineering” encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time. What practices can a software organization introduce that will best keep its code valuable over the long term? How can engineers make a codebase more sustainable and the software engineering discipline itself more rigorous? We don’t have fundamental answers to these questions, but we hope that Google’s collective experience over the past two decades illuminates possible paths toward finding those answers.

One key insight we share in this book is that software engineering can be thought of as “programming integrated over time.” What practices can we introduce to our code to make it sustainable—able to react to necessary change—over its life cycle, from conception to introduction to maintenance to deprecation?

The book emphasizes three fundamental principles that we feel software organizations should keep in mind when designing, architecting, and writing their code:

Time and Change How code will need to adapt over the length of its life

Scale and Growth How an organization will need to adapt as it evolves

Trade-offs and Costs How an organization makes decisions, based on the lessons of Time and Change and Scale and Growth

2. Comentar com suas palavras o segundo trecho do livro Software Engineering at Google, Oreilly.
   
Comentário: Através do trecho analisado é necessário fazer uma séria reflexão a respeito da forma como criamos nossos códigos, e através das "boas prática" que não seguem uma linha linear de pensamento, mas que nos direcionam a tomas cuidados enquanto criamos nossos códigos, para que eles não se tornem obsoletos com o tempo, que possam ser adaptados/melhorados, e mais importante: que possam ser compreendidos e alterados por outras pessoas com o passar do tempo.

3. Listar e explicar 3 exemplos de tradeoffs (falamos alguns nas aulas... você pode usá-los ou falar dos seus próprios):
4. 
Exemplo de tradeoff 01: Linux e Windows, nesse caso temos de um lado um sistema totalmente permissivel e editável e do outro um sistema mais fechado e dependende de atualizações.
Exemplo de tradeoff 02: Android e IOS, nesse caso temos um sistema mobile fechado e exclusivo, e do outro um sistema muito mais permissivo e manipulável.
Exemplo de tradeoff 03: Java e Python, onde Java é extremamente portátil pois está mais próximo do hardware e python é mais acesspivel ao usuário porém não tem o mesmo nível de portabilidade, devido a suas camadas de compilação/tradução de códigos.

Slide 57:

A imagem corresponde à uma representação gráfico do comentário de François Chollet, que fiz que o melhor primeiro passo para construção de um sistema end-to-end complexo, é contruir um sistema básico end-to-end, e não um submodelo daquilo que você acha que um sistema complexo é. Com isso ele quer dizer que ao inves de começar com uma grande estruturação e construindo tudo de forma complexa, é mais viavel fazer um sistema funcional mais simples e ir com o tempo aprimorando-o, dessa forma ocorrerá uma evolução gradativa mais natural no processo de criação. A partir dessa refleção é possível de forma intuitiva entendermos que nem sempre aquilo que acreditamos que é complexo e extenso, significa que é a melhor solução ou entrega para o que precisamos criar, logo, temos que quebrar diversos paradigmas nos momentos de desenvolvimento um deles é essa questão
