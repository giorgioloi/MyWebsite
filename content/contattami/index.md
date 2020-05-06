---
date: "2020"
title: "Contattami"
---


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
    <label for="subject">Words</label>
    <br>
    <textarea id="words" name="words" placeholder="Write something.." style="height:200px"></textarea>
    <br>
    <br>
    <div data-netlify-recaptcha></div>
    <br>
    <br>
    <input type="submit" value="Invia" style="">
</form>