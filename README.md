/* CSS = cores, fontes e animações */

body{
  margin:0;
  font-family: Arial, sans-serif;
  background:#f4f7f2;
}

header{
  background:linear-gradient(to right, #2e7d32, #66bb6a);
  color:white;
  text-align:center;
  padding:40px;
}

.conteudo{
  display:flex;
  justify-content:center;
  margin-top:40px;
}

.card{
  background:white;
  width:300px;
  padding:25px;
  border-radius:12px;
  box-shadow:0 4px 10px rgba(0,0,0,0.2);

  /* animação */
  transition:0.4s;
}

.card:hover{
  transform:scale(1.05);
}

h2{
  color:#2e7d32;
}

button{
  background:#2e7d32;
  color:white;
  border:none;
  padding:12px 20px;
  border-radius:8px;
  cursor:pointer;
  margin-top:15px;
}

button:hover{
  background:#1b5e20;
}
