property-example:: property-value
icon:: 👠

-
- Select a block in [edit mode](((6498e61e-b110-46ad-b6d1-1167e44da111))) to view how the formatting is created
-
# Heading 1
	- ## Heading 2
		- ### Heading 3
			- #### Heading 4
				- ##### Heading 5
-
# Text Formatting
	- Text formatting in Logseq is primarily based on [Mardown](https://www.markdownguide.org/basic-syntax#overview). Here are some examples.
	-
	- Lorem ipsum dolor sit amet, consectetur adipiscing elit. -> Pellentesque lacinia cursus ipsum, non blandit est sollicitudin non. Proin fringilla enim tortor, quis finibus quam dictum nec. Nunc eu tincidunt erat, non pretium nibh.
		- inline block reference
		  id:: 6494c06d-09e2-430c-bd73-e8a336c3c06f
			- numbered list
			  logseq.order-list-type:: number
			- numbered list
			  logseq.order-list-type:: number
		- Block embed
		  id:: 6494c06d-9524-4f81-ac2e-1e22baefaed4
			- numbered list
			  logseq.order-list-type:: number
			- numbered list
			  logseq.order-list-type:: number
	-
	- **Bold text** -> `CTRL + B`
	-
	- *Italic text* _with underscores_ -> `CTRL + I` for `*asterisks*`
	-
	- ***Italic and bold***
	-
	- ~~Strikethrough~~
	-
	- ==Highlight with equal sign== and ^^Highlight with carets^^
	-
	- [Hyperlink](https://logseq.com/) -> Select the text you want to hyperlink and paste the link, or type `/Link`
	-
	- > Blockquote
	-
	- `Inline Code`
	-
	- ```
	  (println "This is a code block")
	  ```
	-
	- $$Latex Formula = E=mc^2$$
- ---
# Studying
	- This is a {{cloze cloze}}
	-
	- This is a flashcard #card
		- And this is the answer
-
-
# Tasks
	- TODO This is a todo item
	- DOING This is an item you're doing
	- DONE This item is done
	- CANCELLED This Item is cancelled
	- NOW This task is now
	- WAIT This task is waiting
	- LATER This task is for later
	- This task is scheduled
	  SCHEDULED: <2023-06-22 Thu 19:30>
-
# Links and Embeds
	- [URL Link](https://logseq.com/)
	-
	- [[Link to another page]]
	-
	- [Link to another page in graph (alias)]([[TODO]])
	-
	- #Tag
	-
	- ((6494c06d-09e2-430c-bd73-e8a336c3c06f))
	- {{embed ((6494c06d-9524-4f81-ac2e-1e22baefaed4))}}
-
# Media
	- ## PDFs
		- ![document.pdf -> Click here to open the document on the left!](http://openresearch.ocadu.ca/id/eprint/3795/7/Uyanze_Candide_2022_DigitalFutures_THESIS.pdf)
		  id:: 6498e61e-3ddd-4207-a28f-95fbeec4e2c5
			- Here's a reference to a highlight in the document. Click on the link to jump to the position in the document -> ((64950a90-38b6-4346-9cd8-e38aae050c06))
	-
	- ## Images
		- ![image](https://asset.logseq.com/static/img/logo.png){:height 200, :width 192}
	-
	- ## Videos
	- ![video hosted online](http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4)
	-
	- {{video https://youtu.be/MJ2r5Y12IQY}}
		- {{youtube-timestamp 12}} This is a YouTube timestamp. Click on the clock to jump to that time in the video.
		- {{youtube-timestamp 34}} To add a timestamp, paste a YouTube video link, pause the video to the desired time, and type `/Embed YouTube Timestamp` on a different block
	-
	- ## Audio
		- ![audio hosted online](https://www.kozco.com/tech/piano2-CoolEdit.mp3)
	-
	- More info: [[Working with Media Files: Embed Audio, Photos, Videos]] and [Docs: Embed Media - Audio, Photos, Videos](https://docs.logseq.com/#/page/embed%20media%20-%20audio%2C%20photos%2C%20videos)
-
# Query
	- {{query}}
-
# Table
	- | Syntax | Description |
	  | Header | Title |
	  | Paragraph | Text |
-
# Org Mode Alerts
	- #+BEGIN_TIP
	  This is a tip!
	  #+END_TIP
	- #+BEGIN_NOTE
	  This is a note
	  #+END_NOTE
	- #+BEGIN_IMPORTANT
	  This is important!
	  #+END_IMPORTANT
	- #+BEGIN_CAUTION
	  This is caution...
	  #+END_CAUTION
	- #+BEGIN_PINNED
	  This is pinned
	  #+END_PINNED
	- #+BEGIN_WARNING
	  This is a warning
	  #+END_WARNING
	- #+BEGIN_EXAMPLE
	  This is an example
	  #+END_EXAMPLE
	- #+BEGIN_CENTER
	  This is text in the center
	  #+END_CENTER
-
# Draw
	- Type `/draw` to create an excalidraw document. Try it out below:
	-
	- [[draws/2023-06-22-15-36-43.excalidraw]]