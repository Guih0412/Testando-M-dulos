# Diferenças entre os dois tipos de módulos





# CommonJS (require)

#### É o padrão antigo do Node.js e ainda é usado por padrão.

#### Para importar módulos, usa-se require('./modulo').

#### Para exportar, usa-se module.exports = objeto.

#### Não é obrigatório colocar a extensão .js ao importar um módulo.

#### Não precisa configurar nada no package.json para funcionar.



# ES Modules (import/export)

#### É o padrão moderno do JavaScript (ES6) e funciona no Node.js 14+.

#### Para importar módulos, usa-se import from './modulo.js'.

#### Para exportar, usa-se export { objeto } ou export default objeto.

#### É obrigatório colocar a extensão .js ao importar um módulo.

#### O package.json precisa ter "type": "module" para que o Node.js aceite ES Modules.



