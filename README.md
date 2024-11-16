Olá! Sou Josiely Oliveira 🙋🏽‍♀️
- 💻 Estudante tech com interesse em desenvolvimento web
- 🐾 Apaixonada por pets e voluntária da causa animal
- 🚹 Pronomes: Ela/Dela

<div style="display: flex; gap: 10px;">
    <a href="https://img.icons8.com/?size=100&id=Zp1kU5M1RFlC&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=Zp1kU5M1RFlC&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=ySKxZPvVLJTn&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=ySKxZPvVLJTn&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=knGUaRl2htnL&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=knGUaRl2htnL&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=zrVDw6ULKgD4&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=zrVDw6ULKgD4&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=FlmU3CC19WX7&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=FlmU3CC19WX7&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=knGUaRl2htnL&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=knGUaRl2htnL&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=zrVDw6ULKgD4&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=zrVDw6ULKgD4&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=oXPFYToOw4l1&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=oXPFYToOw4l1&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=oYnIVGck1fBV&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=oYnIVGck1fBV&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
      <a href="https://img.icons8.com/?size=100&id=Zp1kU5M1RFlC&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=Zp1kU5M1RFlC&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=ySKxZPvVLJTn&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=ySKxZPvVLJTn&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=knGUaRl2htnL&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=knGUaRl2htnL&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=zrVDw6ULKgD4&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=zrVDw6ULKgD4&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=FlmU3CC19WX7&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=FlmU3CC19WX7&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
    <a href="https://img.icons8.com/?size=100&id=knGUaRl2htnL&format=png&color=000000" target="_blank">
        <img src="https://img.icons8.com/?size=100&id=knGUaRl2htnL&format=png&color=000000" alt="Ícone de Gato" width="50" height="50">
    </a>
</div>

< canvas  width =" 600 " height =" 400 " > </ canvas >  <!--cria uma tela de 600 x 400 px-->

< roteiro >
	
	var  tela  =  documento . querySelector ( 'canvas' ) ;  //puxa a tela do html para o javascript
	var  brush  =  screen . getContext ( '2d' ) ;  //cria um brush 2d

	//Céu - Céu
	brush . fillStyle  =  'lightblue' ;  //pega a cor azul
	escovar . preencherRect ( 0 , 0 , 600 , 400 ) ;  //desenha um quadrado

	//Chão - Chão
	brush . fillStyle  =  'green' ;  //pega a cor verde
	escovar . preencherRect ( 0 , 395 , 600 , 5 ) ;  //desenha um quadrado

	function  drawCircle ( x ,  y ,  radius ,  color )  {  //função para desenhar círculos
		brush . fillStyle  =  color ;  //pega a cor
		escovar . começarPath ( ) ;  //inicia um caminho
		escovar . arco ( x ,  y ,  raio ,  0 ,  2 * 3,14 ) ;  //define o tamanho
		escovar . preencher ( ) ;  //cria o círculo
	}

	//Flor - Flor
	drawCircle ( 300 ,  200 ,  30 ,  'marrom' ) ;  //desenha círculo marrom
	desenharCírculo ( 300 ,  150 ,  20 ,  'amarelo' ) ;  //desenha círculo amarelo
	desenharCírculo ( 340 , 160 ,  20 ,  '#F2C438' ) ;  //desenha círculo amarelo escuro
	desenharCírculo ( 350 ,  200 ,  20 ,  'amarelo' ) ;  //desenha círculo amarelo
	desenharCírculo ( 340 , 240 ,  20 ,  '#F2C438' ) ;  //desenha círculo amarelo escuro
	desenharCírculo ( 300 ,  250 ,  20 ,  'amarelo' ) ;  //desenha círculo amarelo
	desenharCírculo ( 260 ,  240 ,  20 ,  '#F2C438' ) ;  //desenha círculo amarelo escuro
	desenharCírculo ( 250 , 200 ,  20 ,  'amarelo' ) ;  //desenha círculo amarelo
	desenharCírculo ( 260 , 160 ,  20 ,  '#F2C438' ) ;  //desenha círculo amarelo escuro

	//Caule + Folha - Caule + Folha
	escovar . fillStyle  =  'verdeescuro' ;  //pega a cor verde escuro
	escovar . preencherRect ( 297 ,  270 ,  6 ,  130 ) ;  //desenha um quadrado

	desenharCírculo ( 313 ,  315 ,  10 ,  'verde' ) ;  //desenha círculo verde

</ script >
