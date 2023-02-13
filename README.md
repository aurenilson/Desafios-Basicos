
# DESAFIOS BÁSICOS


1 - Remover duplicatas de um array, note que tem um dos cosméticos sem acento. Crie 2 lógicas diferentes para remover "Cosmeticos" da repetição, lembre-se de deixar o correto com o acento;

    const array = ["Cosméticos", "Remédios", "Cosmeticos", "Sapato"];
    // output : ["Cosméticos", "Remédios", "Sapato"];


2 - Criar um Modal, usando programação Orientado a Objeto, criando componentes com DOM e executando o modal quando quiser, em qualquer página. Note no exemplo abaixo que só temos o "button" como único elemento HTML, toda lógica e criação de elemento deve ser criado na class modal. O modal deve ter o botão de fechar e deve passar os parâmetros titulo e descrição.


    //!# index.html
    <html>
	    <head>Teste de modal</head>
	    <body>
		    <button onclick="modal("Aviso", "Isso é um Modal aberto")">
			    <span>Abrir Modal</span>
		    </button>
		    <script>
			    //!# class modal
				class modal {
					...
				}
				const modal = (titulo, descricao) => {
					return new modal(titulo, descricao);
				}
			</script>
	    </body>
    </html>
