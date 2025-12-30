# Advice for deving authentication in a browser-app

On finding the right decision for the way of authentication in the mass of confusing offers on the net, <br>
this elementary structure and authentication-flow (see below) should be understood.<br>
<br>

It doesn't matter if it's  

- <i>third-party trusted authentication</i> 
- <i>standard network authentication</i> 
- <i>secure ticketing protocol</i> 
- <i>SAML</i> 
- <i>OAuth</i> 
- <i>KeyCloak</i> 
- <i>Kerberos</i> 
- or others,  

or how many other names, signatures, and certificates they invent to be used <br>
and how confusingly complex they are designed and described; <br>
ALL different kinds of authentications (protocols, extensions, frameworks, or apps) <br>
have ONE thing in common. They are grounded on the <a href="https://github.com/Reinerth/Application-Template-MVC-best-Practice" target="_blank" rel="noopener noreferrer">MVC-pattern</a>. <br>
<br>
The Model-View-Controller-Pattern is like a universal STANDARD for all programs or applications. <br>
Even if we don't <a href="https://github.com/Reinerth/Application-Template-MVC-best-Practice" target="_blank" rel="noopener noreferrer">structure our code accordingly to follow this pattern</a>.<br>
In theory, all apps follow  this unavoidable pattern-rule. <br>
This is why some say MVC is not a pattern; it is always a fact. <br>
<br>
If this simple fact and the default-flow below are understood, <br>
you will find it makes more sense to write your own code for your authentication, <br>
instead of integrating another external dependency that regularly needs updates <br>
and that could lead to hard-to-maintain and inflexible code in your apps. <br>
<br>
Because all frameworks have their own strict rules to be followed, <br>
that forces you to restructure your code. Or it even might be <br>
that your new app or module does not has the right interface/API to be connected. <br>
Then you would need to rewrite your app or -<b>still</b>- write your own authentication-flow.<br>
<br>

<img width="1210" height="860" alt="authentication-underlying-fundamentals" src="https://github.com/user-attachments/assets/6bf1c143-9ead-4ba4-bb63-bcb19fd27db4" />


<br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br>















