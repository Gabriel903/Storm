# Storm


- Usei o plugin Slick para o carrosel;

- Reduzi as imagens usando o Tiny PNG , não minifiquei o código para ele ser analisado;



- Não fiz o POST pois estava sem servidor claro, mas segue abaixo um escopo do mesmo:

function enviaDados(){
	$($.ajax({
		url: '',
		type: 'POST',
		dataType: '',
		data: {
			nome: 'nome',
			email: 'email',
			mensagem: 'mensagem'
		},
	})
	.done(function() {
		console.log("success");
	})
	.fail(function() {
		console.log("error");
	})
	.always(function() {
		console.log("complete");
	});
	)
}


Qualquer dúvida por favor me contacte!
