




''' // variaveis
const mensagem = 'Oi, tudo bem?'
//Tipos de dados
  //Number
  //String
// função
alert(mensagem)


// obejto javascript
const participante = {
  nome: "Lucas Fernandez",
  email: "lucas@gmail.com",
  datainscricao: new Date(2024, 0, 17, 19, 20),
  datacheckin: new Date(2024, 0, 20, 22, 00)
}

//array
let participantes = [
  {
  nome: "Lucas Fernandez",
  email: "lucas@gmail.com",
  datainscricao: new Date(2024, 0, 17, 19, 20),
  datacheckin: new Date(2024, 0, 20, 22, 00)
}
]

// estrutura de repetição
for(let participante of participantes) {
  output = output + criarnovoparticipante(participante)
}