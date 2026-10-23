# HTTP observations (Lab 4, Task 1)
 
| Question | My answer |
|----------|-----------|
| Request method for index.html | ... |
| Status code with Disable cache ticked | ... |
| Status code on a normal reload | ... |
| Status code for /nothing-here.html | ... |
| Value of the Content-Type response header | ... |
| Remote Address (IP and port) | ... |
| Protocol in the address bar (http or https) | ... |
 
## Why is this address http and not https?
... (two sentences)

## Bug log (Lab 4, Task 6)
 
| # | What was wrong (file and line) | Which tool showed it | My fix |
|---|--------------------------------|----------------------|--------|
| 1 | bugs.html, line 2: the <html> tag  Added lang="en" to make <html lang="en">
| 2 | bugs.html, line 17: I used <h4> right after <h1>. This skips heading levels.   Changed <h4> to <h2>
| 3 | bugs.html, line 18: the image had no alt text.   Added alt="Campus Café logo"
| 4 | bugs.html, line 21: the label said for="mail" but the input id is email. They did not match.   Changed it to for="email"
| 5 | bugs.html, line 25: the paragraph had class="note" but the CSS uses .notes. So the style was not used     Changed it to class="notes"
| 6 | bugs.css, line 14: I wrote colour but CSS only knows color. The button text did not turn white.  Changed colour to color.
| 7 | bugs.css, line 21: a semicolon was missing after 
#0b1f3a. This broke the hover color and the pointer cursor   Added ; after 
#0b1f3a.
| 8 | bugs.css, line 27: the grey 
#999999 is too light on a white page. People cannot read it easily.  Changed it to the darker grey 
#595959

## Live site observations (Lab 4, Task 7)
 
1. Compare localhost (Task 1) with the live site: protocol, server header, and
   Remote Address. What changed and why?
2. What does the padlock and certificate tell the visitor, and what could an
   attacker on the same Wi-Fi do if the site were plain http?
3. Why was the Saved orders table empty on the live site, even though you saved
   orders on localhost? (Hint: storage belongs to an origin.)
4. Which HTTP status code did the missing page return, and who sent it?
