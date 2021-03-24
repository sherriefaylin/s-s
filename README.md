# soulmates + strangers


## conceptual web design, a visual walkthrough

<br>

<h3>"TELL US A SECRET"</h3>
<br>
<p>when user enters, they will be prompted with the first interaction </p>
<img width="600px" src="s-s/readme_assets/part-1_1.gif">
<br>
<p>on type, user's words will appear at random within the ellipse (space keycode = word break)</p>
<p>string is logged on firebase as newPerson, along with their "secret" and "location" (not pictured)</p>
<br>
<p>on enter, words fade with starting ellipse and venn diagram appears with second prompt</p>


<br>
<p>user is presented with 2 options that lead to two different dynamic interfaces</p>
<img width="600px" src="s-s/readme_assets/part-1_2.gif">
<br>
<br>
<h3>OPTION 1 ————— "FIND YOUR SOULMATE"</h3>
<br>
<img width="600px" src="s-s/readme_assets/part-2a-sm_1.gif">
<p>if user chooses to "find your soulmate," the interface only shows other inputs that have >==2 of the same words (non-articles) in their "secret"</p>
<p>each shows up as a small pulsing dot, opacity 10%-100% based on how similar their inputs are (ie. a "secret" that is exactly the same as yours would be a 100% opacity dot)</p>

<img width="600px" src="s-s/readme_assets/part-2a-sm_2.gif">
<p>user can click on the dots to view anonymous "secrets"</p>

<br>
<br>
<h3>OPTION 2 ————— "BE A STRANGER"</h3>
<br>
<img width="600px" src="s-s/readme_assets/part-2a-str_1.gif">
<p>if user chooses to "be a stranger," the interface only shows other inputs that have <==2 of the same words (non-articles) in their "secret"</p>
<p>each shows up as a random colored pulsing dot, located randomly on the DOM</p>

<img width="600px" src="s-s/readme_assets/part-2a-str_2.gif">
<p>user can click on the dots to view anonymous "secrets"</p>


