---
date: "2020"
title: "Contattami"
---
<style>
input[type=text], select {
  width: 80%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 80%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  width: 80%;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}

textarea {
  width: 80%;
  height: 150px;
  padding: 12px 20px;
  box-sizing: border-box;
  border: 2px solid #ccc;
  border-radius: 4px;
  background-color: #f8f8f8;
  resize: none;
}
</style>
<div>
<form method="post" name="Contact" data-netlify="true" netlify-honeypot="bot-field">
    <p style="visibility: hidden">
        <label>Don't Fill This out if you're human: <input name="bot-field" /></label> 
    </p>
    <label for="fname">Nome</label>
    <br>
    <input type="text" id="fname" name="firstname" placeholder="Tuo nome.." >
    <br>
    <br>
    <label for="lname">Cognome</label>
    <br>
    <input type="text" id="lname" name="lastname" placeholder="Tuo cognome..">
    <br>
    <br>
    <label for="email">Email</label>
    <br>
    <input type="text" id="email" name="email" placeholder="email@example.com">
    <br>
    <br>
    <label for="subject">Testo</label>
    <br>
    <textarea id="words" name="words" placeholder="Write something.." style="height:200px"></textarea>
    <br>
    <br>
    <div data-netlify-recaptcha></div>
    <br>
    <br>
    <input type="submit" value="Invia" style="">
</form>
</div>