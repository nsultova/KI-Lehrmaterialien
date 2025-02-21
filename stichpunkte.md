### Brainstorm BA

* Was versteht ihr unter KI? -> 
	* --> vibecheck, rausfinden was der Stand ist, Gefühl für Verständnis(lücken) bekommen
* Unterschied zwischen KI und konventioneller Programmiererei
	* --> Wichtige Frage ist erstmal das Warum/Weshalb..was ist dieses Ding (und was ist es nicht)
* kurze Geschichte (?)
	* --> Eventuell hilfreich, Dinge wie KI-Winter und den Herkunftsbegriff kurz vorzustellen, damit man eine initiale Zuordnung hat
		* --> Unterschied zwischen AGI (SciFi), sehr fortgeschrittene Modelle (DeepSeekR1, OpenAI o1) und maschinellem Lernen
		* --> Ansetzen beim maschinellen Lernen, weil das die Grundlage ist, auf die Späteres aufbaut und ein guter Fixpunkt auf den man immer wieder zurück kann. 
		* 
* Wie funktioniert das? der technische Aspekt
	* --> Basisbausteine -> Architektur, Trainingsdaten
	* --> Pipeline -> wie aneinandergereiht
	* --> Prozess -> Training, Inferenz
	* --> Modell == was mithilfe von maschinellem Lernen aus den obigen Bausteinen rausfällt (das Gesamtpaket) \
	* --> Unterscheidung zwischen Bausteinen,  dem Prozess und dem fertigen Ding wichtig -> hier wieder in Bezug setzen, wo Unterschied zu klassischer Software - und wo ähnlich.

	Software :                                                                   
	* man programmiert dediziert das WIE                
	Modell:
	* Man bestimmt ein Ziel und das Modell erlernt mithilfe von Trainingsdaten + vielen Iterationen fancy Mathe, wie es dahin kommt

* Kurze Einordnung supervised vs non-supervised  
* --> Zuordnung zu welchem Baustein und welcher Stelle in Pipeline das gehört
* Supervised learning (drum vorher Begriffsklärung, um erstmal beim maschinellen Lernen anzufangen)

* Wie funktioniert das? der soziale Aspekt
* --> sehr sehr wichtig, sich dessen bewusst zu sein, um diese Tools navigieren zu können
* --> scam, wo einbauen, wo nicht, AI-SEC, Kompetenzbereiche und wo nicht
* --> Einführung in die relevanten kognitiven Biases --> Verbindung herstellen, wie sich das aus dem Interface (interaktion via normaler Sprache ergibt)
* – > Brain-Rot, Relevanz von Denken und Lernen
* --> eventuell minimale Einführung durch einfache Beispiele für embodiment, relevance realization ..es ist weder menschlich noch klassische software und das dazwischen zu platzieren ist SEHR wichtig um vielen daraus resultierenden Fehleinschätzungen vorzubeugen

Beispiele:
deep fakes
Memes, tiktok

##### TODO
Ressourcen + explizite BSP bereitstellen


-------


## Wie führt man Fünftklässler an die Grundlagen von KI heran?

### TEIL I

Ansatz:
* Die meisten haben von ChatGPT gehört
* Was ist ChatGPT?
* Wie funktioniert ChatGPTt?
	* Relevante Begriffe: LLM, Foundation Models, Transformer, GPT (Generative Pretarining Transformer)

Ziel: Wie führt man Fünftklässler an die Grundlagen von KI heran?

### TEIL I

Ansatz:
* Die meisten haben von ChatGPT gehört
* Was ist ChatGPT?
* Wie funktioniert Chatgpt?
	* Relevante Begriffe: LLM, Foundation Models, Transformer


Fragen:
* Wer von euch hat schon mal von ChatGPT gehört?

**Erklärbär**
Es ist wie ein Computerprogramm, das fast wie ein Mensch mit euch sprechen kann.  Fast, weil es kein Mensch ist und auch nicht wie ein Mensch denkt, aber sehr wie einer klingt. Aber auch wenn es definitiv kein Mensch ist, ist es auch nicht ganz wie andere Computerprogramme.

Denkt an einen Taschenrechner. Wenn ihr 2+2 eingebt, kommt immer 4 heraus, weil er festen Regeln folgt - аlso Mathe. Normale Computerprogramme sind genauso - sie führen automatisch genau das aus, was wir ihnen Schritt für Schritt vorgeben. Aber ChatGPT ist eine andere Art von Computerprogramm - es ist wie ein Schulkind, das sehr viele Bücher gelesen hat, Millionen, um genau zu sein, und dann versucht, 
vorherzusagen, welche Wörter als nächstes in einem Satz kommen könnten. Das heißt aber nicht, dass es das so versteht wie ihr, damit es das kann. Und wofür ist das überhaupt gut? Darauf kommen wir noch.

Was bedeutet denn Wörter vorhersagen? Wenn ich sage 'Hänschen klein, ging...' - Welches Wort kommt dann? 
Die meisten von uns wissen, dass dann wahrscheinlich  'allein' kommt, weniger wahrscheinlich "gemein" oder "Stein" und vermutlich sehr unwahrscheinlich "Besen". Darüber müsst ihr gar nicht aktiv nachdenken, das wisst ihr, weil ihr dieses Lied oder ähnliche kennt und das Muster gelernt habt - was reimt sich, könnte folgen  - und was wäre sinnvoll, wenns um Weihnachten geht. Sprachmodelle (also das auf das ChatGPT aufbaut) machen etwas Ähnliches, aber mit Milliarden von Mustern, die sie aus Texten gelernt haben. Dafür wissen sie aber nicht ganz so gut wie wir, ob das, was sie da sagen, Sinn ergibt, denn sie haben ja keinen Sinn oder Körper, so wie ich oder ihr, und auch kein Gehirn in dem Sinn, sondern ganz viel Mathematik zu einem dichten Knäuel zusammengepackt.

Das ist ganz schön verwirrend. Wenn es doch wie ein Mensch klingt und auch so Sachen beantworten kann, auch wenn es keinen Körper hat, heißt es, dass es dann denken kann und vielleicht sogar Gefühle hat?

Auch wenn diese Programme Geschichten schreiben und Fragen beantworten können, verstehen sie die Dinge nicht wirklich wie ihr - denn um etwas zu verstehen, reicht Lesen alleine ja bekanntlich nicht aus. Man muss Dinge wahrnehmen und erfahren und anwenden. Dass es nicht so schlau ist, die heisse Herdplatte anzufassen, haben sicher viele von euch sehr eindrücklich gelernt - indem sie es ausprobiert haben. Das hat sich nicht gut angefühlt und so ein Körper ist schon super wichtig, um so eine Erfahrung zu machen - und vor allem, zu bestimmen, ob sie gut oder schlecht ist. Da Modelle keinen Körper haben, keine Schmerzen empfinden oder sich vor Lachen schütteln können, bis ihnen der Bauch wehtut, können sie auch nicht zwischen Gut oder Böse unterscheiden. Sie sind eher wie sehr fortgeschrittene Muster-Erkennungs Maschinen. Noch ein Beispiel:
Wenn ich euch nach eurer Lieblingseis-Sorte frage, könnt ihr den Geschmack in eurem Kopf schmecken und euch daran erinnern, wie es sich angefühlt hat. Aber wenn ChatGPT über Eis spricht, reiht es nur Wörter aneinander, die es vorher über Eis gesehen hat - es hat noch nie wirklich etwas geschmeckt! 
Da Himbeer und Vanille und Schokoeis sehr verbreitet sind, wird es sehr wahrscheinlich sagen, dass es Schokoeis mag, wie zum Beispiel blaues Schlumpfeis. Das liegt daran, dass es viel mehr über Schokoeis gelesen hat, als über Schlumpfeis, das heißt, wenn jemand etwas fragt, dann denkt es, dass die Wahrscheinlichkeit, dass Schokoeis die richtige Antwort ist, am höchsten ist. Es versteht aber nicht, dass du sein Lieblingseis wissen wolltest, denn es hat ja kein Ich oder Körper oder Hunger so wie wir, dass diese Frage Sinn ergibt. Es antwortet dir, so wie es deine Frage versteht und gibt dir das wahrscheinlichste Muster zurück.

Oder stellt euch vor, ihr versucht zu erraten, was eure beste Freundin als nächstes sagen wird. Ihr nutzt unbewusst das, was ihr über sie wisst und was sie bisher gesagt hat, um eine gute Vermutung anzustellen, was jetzt kommen könnte. Das bedeutet, ihr greift sowohl auf euer Wissen (über eure Freundin) als auch auf die Sprache (die Wörter, die ihr so kennt) zurück. Sprachmodelle können nur auf die Sprache (also Wörter) zurückgreifen - sie stellen Vermutungen an, welche Wörter als nächstes kommen sollten, weil sie unglaublich viele Beispiele (also Text) gesehen haben.
Sie sind keine Magie und nicht wirklich intelligent - sie sind aber sehr gut darin, Muster in Sprache zu finden. Und das Faszinierende daran ist - das ist alles ein Knäuel an Mathe, was das kann! Nicht so wie wir, aber immer noch ziemlich beeindruckend, oder? 

Hoffentlich habt ihr jetzt ein besseres Gefühl für ChatGPT. Viele der Muster sind super spannend und gerade sehr häufig vertretene Muster (wie einfache Grundlagen) kennt es gut. Es kann auch super helfen mit vielem, als Lernpartner oder zum Spaß. Aber ihr müsst immer überprüfen, ob das was es sagt Sinn ergibt. Blind Vertrauen ist gefährlich, nicht weil es euch was böses will, sondern weil es kein wirkliches Wissen hat und Dinge nicht selbstständig einschätzen kann. Wenn es weit verbreitetes Allgemeinwissen ist (wie, dass man nicht vor ein Auto rennen sollte) kann es dir das schon sagen, weil es das oft genug gelesen hat, aber nicht, weil es das weiss oder dich beschützen möchte.
Es sind schon Leute im Krankenhaus gelandet, weil sie ChatGPT nach einem Rezept gefragt haben und das Rezept klang ok..aber ChatGPT wusste nicht, dass Knoblauch mit Honig fermentieren zur Entstehung von Butolin führen kann, ein sehr starkes Gift, das tödlich sein kann.. 
(https://www.reddit.com/r/fermentation/comments/7wmrdh/first_try_at_garlic_honey_safety_precautions/)

Um euch nochmal genauer zu zeigen, was es kann und nicht so gut kann:
* Was ist gestern passiert?
* Wie viele Fenster hat das Klassenzimmer?
* Details aus einem Lieblingsbuch über euren Lieblingscharakter. Fragt viel und genau und schaut, ab wann das Modell beginnt, zu schummeln, also Dinge zu erfinden (das nennt man auch Halluzinieren)
* KI rechnen lassen (ohne code execution im Hintergrund) https://www.reddit.com/r/ChatGPT/comments/17fgh9t/llms_cannot_perform_maths/


-----
"how to fry an egg, step by step instructions, illustration"

![[Pasted image 20241221141338.png]]

### Teil II

Ihr habt sicher auch schonmal was von KI-generierten Bildern gehört, vielleicht sogar Namen wie Mid Journey..vermutlich kennen viele von euch TikTok und Beauty Filter.  Zwar sind Sprachmodelle und Bildmodelle an vielen Punkten sehr verschieden - aber beiden ist gemeinsam, dass sie nicht so denken wie du und ich - aber Muster wunderbar erkennen können. Wenn ChatGPT wie ein Schüler ist, der Millionen von Büchern gelesen hat, um vorherzusagen, welche Wörter als nächstes kommen ist Midjourney (ein bekanntes Blldgenerationsmodell) wie eine Kunststudentin, die Millionen von Gemälden und Zeichnungen gesehen und sich gemerkt hat, wie Bilder zusammengesetzt sind. Wie die Sprach-KI hat sie aber niemals einen Stift in der Hand gehalten, das flauschige Fell einer Katze gestreichelt oder ihr Schnurren auf dem Bauch gespürt.
Woher weiss die Bild-КI also, wie sie eine Katze "malen" soll?

Genauso wie die Sprach-КI (ChatGPT) gelernt hat, dass nach 'Hänschen klein'  sehr wahrscheinlich 'ging allein' kommt, hat die Bild-KI gelernt, dass eine Katze normalerweise Fell, zwei spitze Ohren, Schnurrhaare und einen Schwanz hat.  Statt versuchen, Wörter vorherzusagen, versucht sie, vorherzusagen, was an welchem Punkt kommen muss, um am ehesten wie eine Katze auszusehen - genauer gesagt, dem, was es unter Katze gelernt hat - also viele, viele Fotos und Bilder von Katzen. Bei Katzen ist sie verdammt gut, denn wie wir alle wissen, ist das Internet voll mit Katzen. Aber versucht mal Katzen in merkwürdigen Stellungen generieren zu lassen, oder ungewöhnliche Katzenrassen, wie die Sphinx (Eine Katzenrasse ohne Fell, die sehr lieb ist und der ständig kalt ist, weshalb sie ständig kuscheln wollen). Da kann die Bild-КI schnell mal ins Straucheln geraten und ganz merkwürdige Dinge kreieren (ähnlich wie die Halluzination bei Sprach-KIs, die dann frei Schnauze eine Antwort "erfinden" ). Manche davon sind subtil, wie eine Katze mit drei Ohren oder ein Fuss mit 6 Zehen, andere komplett an dem vorbei, was man erwarten würde. Das kann auch sehr inspirierend sein, die Regel ist, je ungewöhnlicher die Anfrage, desto schwerer tut sich die KI. Damit kann man auch viele Stereotypen sehen, also (Vor)Urteile, die in unserer Gesellschaft weit verbreitet sind, einfach, weil die Bild-КI viel mehr Beispielbilder von Männern mit Anzug und Frauen in der Küche gesehen hat, als andersherum. Oder dass Gesichter immer "gleicher" aussehen, je mehr man generieren lässt, einfach, weil es auf Social Media und im Internet vor allem Werbung, Tiktok-Pretty und Video gibt.  Die KI weiss ja nicht, dass die meisten von uns nicht so aussehen.

Was die KI auch anders macht als wir, ist, wie sie zeichnet. Wenn wir an eine Katze denken und sie malen wollen, haben wir eine Idee von einer Katze, und allem was so zu einer Miez gehört, vielleicht sogar eine Lieblingskatze und dann nehmen wir uns einen Stift und malen vielleicht erstmal einen kleinen Kreis wo der Kopf hin soll und einen grösseren da wo der Körper ist und vier Striche für die Beine und einen laaaangen für den Schwanz. Vielleicht machen wir den auch so, dass er wie eine Klobürste absteht, weil das lustig ist - und wir das können. Dann fangen wir an, die Katze auszuarbeiten. Die Bild-KI muss aber über das ganze Bild auf einmal nachdenken - stellt euch vor, ihr müsstet alle Teile der Katze gleichzeitig zeichnen - und auf die Idee mit dem Schwanz wie eine Klobürste kommt sie auch nur dann, wenn ihr sie genau danach fragt. Vielleicht versteht sie euch dann sogar wörtlich - obwohl sie manche Metaphern (Sprichwörter) kennt, die sie oft genug irgendwo gesehen hat.

Genau wie wir gelernt haben, ChatGPT nicht blind bei wichtigen Informationen zu vertrauen, sollten wir nicht annehmen, dass jedes Bild echt ist, nur weil es echt aussieht. Diese KIs können Bilder erstellen, die sehr echt aussehen, aber komplett erfunden sind - wie ein Foto von einem Dinosaurier auf einem Fahrrad. Was Bild-КIs aber heute auch können, ist ein Foto von dir zu nehmen und mit deinem Gesicht frei erfundene Fotos oder Videos zu erstellen. 
Das kann lustig sein, wer wollte sich nicht immer schon mal als Held oder Heldin  sehen? - аber auch super gefährlich. Es gibt einen guten Grund, weshalb diese Art von Bild-KIs auch unter "DEEPFAKES" also "tiefe Täuschungen" bekannt sind. Wer weiss, ob das Bild, das dir jemand vom letzten Urlaub oder Geburtstag schickt, überhaupt echt ist? Oder wenn jemand gemein sein will und wirklich schlimme Bilder mit deinem Gesicht erstellt? Oder dein Foto nimmt und ein Bild damit erstellt, als ob dir was passiert ist und damit deine Grosseltern um Geldhilfe fragt?
Manche davon kann man leicht als solche erkennen, andere kaum. Und schnell ist der Schaden schon geschehen, selbst wenn sich herausstellt, dass das Bild gar nicht "echt" ist, sondern KI-generiert. Als Faustregel gilt, gehe immer davon aus, dass alles was du im Internet oder auf SocialMedia siehst, vielleicht gar nicht echt ist - das heisst nicht, dass du daran keine Freude haben darfst - Computerspiele machen auch viel Spass obwohl sie frei erfunden sind - aber gewöhne es dir an, herauszufinden, wo und wie man nachprüfen kann, ob was echt ist oder nicht - аnsonsten kann dich jede(r), die besser wissen, wie man mit Ki-Modellen umgeht, als du, in die Irre führen und leider haben nicht alle Menschen gute Absichten.


Um euch nochmal genauer zu zeigen, was es kann und nicht so gut kann:
* einen lila Katze auf einem Skateboard  - hier wird die Bild-КI versuchen, alles zu kombinieren, was sie über Katzen, die Farbe Lila und Skateboards. Manchmal klappt das super, und manchmal sieht es ein bisschen seltsam aus - genau wie ChatGPT manchmal merkwürdige Antworten gibt, wenn wir ungewöhnliche Ideen kombinieren. 
* Versuche obiges Prompt zu ergänzen, wie etwa:
*  einen lila Katze auf einem Skateboard mit Perlenohrringen
*   einen lila Katze auf einem Skateboard mit Perlenohrringen als Anime Figur
*   Ein Uboot mit einem Graffiti, das eine lila Katze auf einem Skateboard zeigt
*   Eine Wolke in der form einer Katze auf einem Skateboard 
*   einen lila Katze auf einem Skateboard mit Perlenohrringen, actionfilm
*  einen lila Mikrobe (seltenes Tier) auf einem Skateboard 
...usw

Vergleiche:
Was glaubt ihr, was für eine KI schwieriger zu zeichnen ist - ein einfacher Kreis oder ein detaillierter Drache? 

Genau wie ChatGPT manchmal mit einfachstem Mathe kämpft, obwohl es euch die wildesten Geschichten schreiben kann, fällt es der Bild-KI manchmal leichter, ein detailliertes Fabelwesen zu generieren als sowas scheinbar einfaches wie einen Kreis.



#### Ressourcen

https://surasshu.com/blocklist-for-ai-music-on-youtube/


