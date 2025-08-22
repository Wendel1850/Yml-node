# Yml-node
node app.js
app.get('/sobre', (req, res) => {
  res.send('Essa é a página sobre!');
});

app.post('/enviar', (req, res) => {
  // Processar o formulário aqui
  res.send('Formulário enviado com sucesso!');
});
