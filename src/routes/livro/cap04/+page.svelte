<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        h3 {
            text-align: center;
            font-family: 'Georgia', serif;
            color: #4A90E2;
            font-size: 2.5rem;
            margin-top: 50px;
        }
        h6 {
            font-family: 'Times New Roman', serif;
            color: #333;
            font-size: 1.2rem;
            line-height: 1.6;
            margin: 20px 40px;
        }
        p {
            font-family: 'Arial', sans-serif;
            font-size: 1.1rem;
            line-height: 1.8;
            color: #444;
        }
        .stars {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .star {
            font-size: 2rem;
            color: #ccc;
            cursor: pointer;
            transition: color 0.3s;
        }
        .star.selected {
            color: #FFD700;
        }
        .star.hovered {
            color: #FFDA44;
        }
    </style>
    <title>O Começo</title>
</head>
<body>
    <header>
        <h3>O Começo</h3>
    </header>

    <br>
    <br>
    <br>
    <br>
    <h6>A sala estava silenciosa, como de costume nos últimos dias de aula, uma constante solidão, um sussurro de algo que se encerrava. Os alunos tendo saído das salas para jogar a tão esperada partida de vôlei na quadra. Ao meu redor as suaves risadas dos meus amigos preenchiam o ambiente como uma canção de ninar calmante, dando sossego a alma. 
    <br> 
     <br>
    -Sinceramente, o amor é algo estanho. - A voz de Luísa soou pelo ambiente, abri ligeiramente meus olhos. Observando seus rebeldes cabelos bagunçados flutuarem com o vento que entravava da janela, o piercing em sua boca emitindo um brilho prateado. Ela estava linda.
    <br>
    <br>
    -Olha quem fala. - Retrucou Vick, seus olhos nunca desgrudando do joguinho, desde que ganhará esse tablet como presente de dia das crianças não parara de baixar jogos e filmes para assistir. Ela é uma criança feliz.
    <br>
    <br>

    -Pessoas que estão namorando não possuem opinião. - Minha voz soou baixa, o cansaço e a falta de sono já me tornando distante. A dias que não durmo direito, o estresse do trabalho somando as provas finais, sobre estressando meu corpo. Parecia um zumbi, uma zumbi bonita, mas mesmo assim uma zumbi.
    <br>
    <br>

    - Quem nunca beijou também não. - Ananda disparou. Sua câmera apontada para minha cara, sua risada ressoando em malicia. Desde que concertara essa relíquia, fez como o propósito de sua vida registrar todos os momentos de nosso ensino médio.
    <br>
    <br>

    Levantei o dedo do meio para ela, erguendo-me da posição desconfortável em que estava. Sentei-me encima da carteira de Luísa, que, automaticamente apoiou a cabeça em minha perna, enquanto eu passava meus dedos por seus fios castanhos rebeldes:
    <br>
    <br>

    -Convenhamos. - Comecei. - Nenhum de nós tem o direito de falar alguma coisa sobre os diferentes tipos de amor. - Olhei para todos, com um sorriso. - Os únicos que ainda poderiam dar opinião seria é o Biel e a Vick. - Ela estreitou os olhos quando ouviu seu apelido. Lhe dediquei um sorriso amarelo, amava a irritar, tão fodidamente bom a ver com raiva.
    <br>
    <br>

    - Mas, realmente, o amor é algo estranho, doido e completamente insano. - Murmurou Luísa, seus olhos fixos ao meu, segredos e amores que apenas nos duas conhecemos. Noites apaixonantes com estrelas no luar.
    <br>
    <br>

    - Disso não discordo. - A olhei de volta, meus dedos se entrelaçando mais profundamente em seus cachos. - O Amor é como os velhos contos mitológicos; não se sabe onde surgiu, o que realmente é e como sabemos que amamos. Só sentimos um sentimento verdadeiramente magico e avassalador que nos perdemos nele.
    <br>
    <br>

    -Verdade. - Ana balançou a cabeça. - E você, jovem escritora, não poderia nos dar alguns exemplos dessas formas de ‘amor’? - Me questionou, a câmera novamente apontada para mim. Estava ficando irritada já com essa câmera, e seu sorriso debochado.
    <br>
    <br>

    -Agora? - Questionei, ela acenou com a cabeça. Luísa levantou-se de meu colo e no lugar colocou seu braço, enquanto Vick deixou de lado seu querido tablet pela primeira vez naquela tarde para prestar atenção ao que falaria. - Bom... por onde começo?? - Respondi, começando a refletir.
    <br>
    <br>

    Sinceramente não sei o que contar para eles e a vocês. Tem tantos contos, sonhos e experiencias magicas, que minhas palavras pouco fazem para escolher esse começo. Focando novamente meu olhar em Luísa, as palavras começaram a brotar de meus lábios e papel.
    <br>
    <br>

    Que melhor começo do que um amor devastador e efêmero que ocorreu de um jeito que não se pode descrever completamente bem. Um sonho que se gostaria de continuar sonhando, mesmo quando esse não permite. Lembrem-se caros leitores, a visão é de quem as vivenciou, mergulhem juntos comigo nessas mitologias de amor. </h6>

    <br>
    <br>

    <div class="stars">
        <span class="star" data-value="1">&#9733;</span>
        <span class="star" data-value="2">&#9733;</span>
        <span class="star" data-value="3">&#9733;</span>
        <span class="star" data-value="4">&#9733;</span>
        <span class="star" data-value="5">&#9733;</span>
    </div>

    <script>
        const stars = document.querySelectorAll('.star');
        
        stars.forEach(star => {
            // Adiciona efeito de hover
            star.addEventListener('mouseover', () => {
                clearStarColors();  // Limpa as cores antes de colorir
                let value = star.getAttribute('data-value');
                highlightStars(value);
            });

            star.addEventListener('mouseout', () => {
                clearStarColors();
                // Após o mouse sair, restaura as estrelas à seleção
                let selectedValue = getSelectedValue();
                highlightStars(selectedValue);
            });

            // Ação ao clicar na estrela
            star.addEventListener('click', () => {
                let rating = star.getAttribute('data-value');
                alert('Você deu uma nota de ' + rating + ' estrela(s)!');
                setSelectedValue(rating);
            });
        });

        function highlightStars(value) {
            for (let i = 0; i < value; i++) {
                stars[i].classList.add('hovered');
            }
        }

        function clearStarColors() {
            stars.forEach(star => {
                star.classList.remove('hovered');
            });
        }

        function getSelectedValue() {
            for (let i = 0; i < stars.length; i++) {
                if (stars[i].classList.contains('selected')) {
                    return stars[i].getAttribute('data-value');
                }
            }
            return 0;  // Retorna 0 se não houver seleção
        }

        function setSelectedValue(value) {
            stars.forEach(star => {
                star.classList.remove('selected');
            });
            for (let i = 0; i < value; i++) {
                stars[i].classList.add('selected');
            }
        }
    </script>

</body>
</html>
