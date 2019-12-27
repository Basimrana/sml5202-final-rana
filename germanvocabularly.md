<h1>Vocabularly on different topics</h1>

<h2>Numbers 1-20</h2>

<p>Learning how to count in German is a great goal for beginners, because you can find some fun ways to commit the sequences to memory. Whether you count out the page numbers in a book or how many German TED Talks you’ve seen, numbers are all over the place for your using.
Some learners find counting rudimentary, so they simply learn the numbers and move onto more advanced words and phrases. However, we can’t stress enough how essential it is to commit German counting to habit, because it comes up in life more than you would expect. See below some benefits in learning how to count;
<ul>
<li>Counting is almost always required if you plan on getting a job in Germany</li>
<li>It’s easier to count money during travels</li>
<li>You may need, or want, to complete math and science classes in German</li>
<li>Recipes written in German have lots of numbers and metrics</li>
</ul>
See below a table for counting in German 1-20 after which there will be a link provided to an external website to practice pronunciation
</p>

<p>
<table>
  <tr><th>Number</th><th>German</th><th>Pronunciation</th></tr>
   <tr><td>1</td><td>eins</td><td>eyns</td></tr>
   <tr><td>2</td><td>zwei</td><td>tsvey</td></tr>
   <tr><td>3</td><td>drei</td><td>dry</td></tr>
   <tr><td>4</td><td>vier</td><td>feer</td></tr>
  <tr><td>5</td><td>fünf</td><td>fuhnf</td></tr>
  <tr><td>6</td><td>sechs</td><td>zex</td></tr>
  <tr><td>7</td><td>sieben</td><td>ZEE-bin</td></tr>
  <tr><td>8</td><td>acht</td><td>akt</td></tr>
  <tr><td>9</td><td>neun</td><td>noin</td></tr>
  <tr><td>10</td><td>zehn</td><td>tsayn</td></tr>
  <tr><td>11</td><td>elf</td><td>elf</td></tr>
  <tr><td>12</td><td>zwölf</td><td>tsvolf</td></tr>
  <tr><td>13</td><td>dreizehn</td><td>DRY-tsain</td></tr>
  <tr><td>14</td><td>vierzehn</td><td>FEAR-tsain</td></tr>
  <tr><td>15</td><td>fünfzehn</td><td>FUHNF-tsain</td></tr>
  <tr><td>16</td><td>sechszehn</td><td>ZEX-tsain</td></tr>
  <tr><td>17</td><td>siebzehn</td><td>ZEEB-tsain</td></tr>
  <tr><td>18</td><td>achtzehn</td><td>AKT-tsain</td></tr>
  <tr><td>19</td><td>neunzehn</td><td>NOIN-tsain</td></tr>
  <tr><td>20</td><td>zwanzig</td><td>TSVAN-zig</td></tr>
  </table>
</p>
<p>Follow the link below to an external website to further practice pronunciations</p>
<a href="https://www.youtube.com/watch?v=JoMqhdYcgZ4">German counting 1-20</a>

<h2>German Verbs with Explanation</h2>
<p>In order to understand verbs it is essential to break them down. In order to conjugate a verb, you first need to identify the verb stem. The stem is the part of the verb that, in most cases, remains constant. In German, you usually find the stem by taking the infinitive of the verb and removing the –en, or -n ending.

German verbs can fall in two categories:
<ul>
<li>Weak (regular)</li>
<li>Strong (irregular)</li>
</ul>
Weak verbs are regular verbs and their stem never changes.
Strong verbs change their stem. The stem may only change in the past tense conjugation or in the present tense as well. <br>
Let's see these two groups in more detail. <br>
<br>
German weak verbs; <br>
As we've seen, weak verbs are entirely regular, and the good news is that the majority of German verbs fall in this category. To find their stem, you simply remove the -en or -n ending. Here are a few example verbs.</p>
<p>
<table>
  <tr><th>Verb</th><th>Stem</th></tr>
   <tr><td>machen (to do)</td><td>mach-</td></tr>
   <tr><td>suchen (to search)</td><td>such-</td></tr>
   <tr><td>brauchen (to need)</td><td>brauch-</td></tr>
   <tr><td>bezahlen (to pay)</td><td>bezahl</td></tr>
  <tr><td>kaufen (to buy)</td><td>kauf-</td></tr>
  <tr><td>segeln (to sail)</td><td>segel-</td></tr>
  <tr><td>arbeiten (to work)</td><td>arbeit-</td></tr>
</table>
<p> 
<br>
<p>German Strong verbs <br>
Strong verbs are irregular verbs, so their stem can sometimes change depending on the tense. Let's take gehen, to go, as an example: its stem in the present tense is regular, geh-, but in the simple past tense it becomes ging-. Sometimes it's the stem in the past participle that changes, and other times the verb has an irregular stem in the present tense.</p>
<p>
<table>
  <tr><th>Verb</th><th>Stem(present tense/past tense)</th></tr>
   <tr><td>gehen</td><td>geh-/ging-/gegangen</td></tr>
   <tr><td>kommen</td><td>komm-/kam-/gekommen</td></tr>
   <tr><td>denken</td><td>denk-/dach-/gedacht</td></tr>
   <tr><td>sehen</td><td>sieh-/sah-/gesehen</td></tr>
  </table>
</p>

<p>When you have the stem by itself, have a look at the table of verb endings for each tense and add the appropriate ending, according to who is performing the action. Simply breaking it down makes it easier to understand.</p>
<p>See below a sentence generator including names verbs and adverbs in German</p> 

<button onclick="makeSentence()">Generate Sentence</button>

<p id="demo"></p>

<script>
function makeSentence() {

var person = {
names: [ "Basim", "Rana", "Naseer", "Marvin", "Sam" ],
verbs: [ "spricht", "isst", "läuft", "geht", "Getränke" ],
adverbs: ["langsam", "schnell", "schön", "geräuschvoll", "viel" ]

};

var i;
var text = "";
for (i = 0; i < person.names.length; i++) {

name = person.names[i];
verb = person.verbs[Math.floor(Math.random() * person.verbs.length)];
adv = person.adverbs[Math.floor(Math.random() * person.adverbs.length)];

text +=name + " " + verb + " " + adv + "<br>";

document.getElementById("demo").innerHTML = text;
}


}

</script>
<p>Here are a few recommended videos for further study on German verbs</p>
<a href="https://www.youtube.com/watch?v=AJxieXyATaY">German lesson on 100 verbs</a>
<a href="https://www.youtube.com/watch?v=a0ddmj8N3ns">German verb pronunciations</a>
<a href="https://www.youtube.com/watch?v=VFgreeRqSkg">25 must know German verbs</a>

<h2>Days of the week</h2>
<p>Learning German is easy if you approach it the right way, and the German days of the week are easy to learn too. Most of them are similar to English, and the rest aren't too hard to memorize. Below we will look at a table of German days of the week followed by pronunciations of each day. </p>
<p>
<table>
  <tr><th>Day</th><th>German</th></tr>
  <tr><td>Monday</td><td>Montag</td></tr>
   <tr><td>Tuesday</td><td>Dienstag</td></tr>
   <tr><td>Wednesday</td><td>Mittwoch</td></tr>
   <tr><td>Thursday</td><td>Donnerstag</td></tr>
  <tr><td>Friday</td><td>Freitag</td></tr>
  <tr><td>Saturday</td><td>Samstag</td></tr>
  <tr><td>Sunday</td><td>Sonntag</td></tr>
</table>
</p>
<audio controls>
  <source src="https://basimrana.github.io/sml5202-final-rana/dataset/daysoftheweek.mp3" type="audio/mpeg">
  </audio>
<p>Test your pronunciations with an H5P speak the word exercise</p>
<iframe src="https://h5p.org/h5p/embed/685906" width="1090" height="289" frameborder="0" allowfullscreen="allowfullscreen"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>
