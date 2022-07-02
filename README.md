# Random-Quote-Generator
 I created it using HTML CSS & JavaScript. To show random quotes, I used a free API named quotable (https://quotable.io/random).
 <br>let’s understand the main JavaScript codes and concepts behind creating this random quote generator. In the JavaScript codes, first: I called a randomQuotes() function on the new quote button clicked.
 <br>Inside this function, using the quotable API I fetched the random quotes and showed them on the Quote App. Second: for the TTS (Text To Speech) functionality, there is no external API is used and it’s possible with the Web Speech API of JavaScript.
<br> Third: to copy the quote, I used the writeText() property of the navigator object. Last: for sharing to Twitter, I passed the quote text in the Tweet URL, and using the window open() method, I opened this URL in the new tab.
