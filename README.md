# data-javascript-em-uma-unica-linha
retornar data em javascript em uma unica linha

const dataString = new Date().toISOString().slice(0, 10).replace(/-/g, '');
