# aula-23-02

index.test.js
/*const calcularDOBRO = require("../index")

test("O dobro de 4 é 8", () =>{
    expect(calcularDOBRO(4)).toBe(8)
}) */

   test('2+3 deve ser 5', ()=> {
        expect( 2+3 ). toBe(5)
    })

    test("objetos iguais", () => {
     const aluno = {nome: "Ana", idade:22}
    expect(aluno).toEqual({nome: "Ana", idade:22})
  })




  test("Variável existe", () =>{
    let valor = 10
    expect(valor).toBeDefined ()
  })


  test ("Variável indefinida", () => {
    let valor
    expect(valor).toBeUndefined()
  })


  test ("Testa verdadeiro e falso", () => {
    expect(true).toBeTruthy()
     expect(false).toBeFalsy()
  })


  test("10 é maior que 5", () => {
    expect(10).toBeGreaterThan(5)
  })



index.js
function calcularDOBRO (valor) {
  return valor * 2   
}

module.exports = calcularDOBRO
