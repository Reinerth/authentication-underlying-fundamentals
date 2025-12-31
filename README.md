# Advice for deving authentication in a browser-app :key:

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
and how <a href="https://github.com/Reinerth/entropy-disorder-spreads-easier-than-order">confusingly complex</a> they are designed and described; <br>
ALL different kinds of authentications (protocols, extensions, frameworks, or apps) <br>
have ONE thing in common. They are grounded on the <a href="https://github.com/Reinerth/Application-Template-MVC-best-Practice">MVC-pattern</a>. <br>
<br>
The Model-View-Controller-Pattern is like a universal STANDARD for all programs or applications. <br>
Even if we don't <a href="https://github.com/Reinerth/Application-Template-MVC-best-Practice">structure our code accordingly to follow this pattern</a>.<br>
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

<img width="1210" height="860" alt="authentication-underlying-fundamentals" src="https://github.com/user-attachments/assets/7cc9331b-011c-490f-9e08-dca356f515bb" />


<br><br><br>

### BTW: Yes, I know about the <ins>Single</ins>-Sign-On troubles.<br>
From my point of view, this is the wrong direction.<br>
<ins>Same</ins>-Sign-On is the right way. One key to open all doors.<br>
But not at the same time.<br>

### <ins>Same</ins>-Sign-On means:<br>
I log in to all my apps with my credentials registered in the Active Directory.<br>
Different apps but same credentials. If I change my key (password),<br>
then I can use the new key for all my apps without needing to change it too for every app I use.<br>
Same key, different doors.<br>

### In reality this would be like this:<br>
For my flat, I got one key to open:<br>
the door to my apartment, the door to my garage,<br>
the door to my garbage-container and the door to my cellar.<br>
Why should I want to open all the doors at the same time if I enter my appartment?!<br>

There might be some strange constellations where I permanently<br>
switch between my apartment and my cellar when I clean up, or whatever,<br>
but I don't see the point. Where is the trouble to open both doors,<br>
and keep them open? Why should I need to open all the doors that I don't use?<br>
I can’t be at two places at the same time. Some people claim they can.<br>

I imagine a point on a time-line is crossing a point of a place-line (position)<br>
but even if there was a wormhole to shorten the way to another point on the place-line,<br>
me, myself and I (and that is always the same guy) can only be at one place at one time.<br>

### <ins>Single</ins>-Sign-On is a weak solution for a rarely fantastic claimed purpose of little use.<br>
When I log in to my PC, I can use all the programs, but they all are „in the same room“.<br>
That is a difference. The apps on the net spreaded all over the world are not in the same room.<br>


<br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br>
<br><br><br><br><br><br><br><br><br><br>















