- # Table of Contents
	- ((6494c06d-e5c4-4293-82aa-01aa600e2cb5))
	- ((6494c06d-aaf7-4c2c-95a9-98573d6541d5))
	- ((6494c06d-7dcc-4c61-9271-e6664f1f909f))
	- ((6494c06d-2a0b-4e17-8e9d-f58d403759e1))
	- ((64951c3c-37fb-4c67-8ad6-9a61e55e7143))
	-
	- *(click on one of the titles above to open its section separately, or scroll down to view everything at once)*
	  collapsed:: true
		- ![TOC demo](https://i.imgur.com/B27AVSa.mp4)
-
- # Getting Started
  id:: 6494c06d-e5c4-4293-82aa-01aa600e2cb5
	- ![open or create graph](https://i.imgur.com/XFvqZpb.mp4)
	-
	- The first step is to open a **graph** or create a new one.
		- A graph is a folder on your device for your project. The folder contains all your pages, assets, settings, etc.
	- Start with a new blank folder OR select an existing one.
-
- # Block
  id:: 6494c06d-aaf7-4c2c-95a9-98573d6541d5
	- ![block demo](https://i.imgur.com/oIuhWks.mp4)
	-
	- The smallest unit of information in Logseq is the "**block**" -> a block is signified by a bullet `•`
	-
	- A block can have text, TODO tasks, embedded media, [links](https://logseq.com), `code snippets`, flash cards, queries, tables, drawings, etc.
	-
	- To **create a new block**, just hit `ENTER` at the end of the previous line.
	-
	- To **edit a block**, click on the text in its line, or use your `↑``↓` arrow keys. Once you click away from a block, you've exited edit mode for that block.
	  id:: 6498e61e-b110-46ad-b6d1-1167e44da111
	-
	- When you're in edit mode, you can **nest blocks** inside of each other by hitting `TAB`. Nested blocks can toggle between being hidden/revealed. Hover over this block and click on the toggle triangle ▶ that appears on the left to reveal the hidden block...
	  id:: 6494c06d-3167-4dc2-978e-257e11b1f6b7
	  collapsed:: true
		- You did it!
-
- # Page
  id:: 6494c06d-7dcc-4c61-9271-e6664f1f909f
	- ![Adding new pages](https://i.imgur.com/eJ9jUWi.mp4)
	-
	- Next we have a page. ==A page is made of many blocks==. In Logseq, there are two types of pages:
		- the **journal pages**:
			- automatically created every day that you open the app
			- remain if you add blocks to them
			- titles = the date ([custom formats can be set](((64b6d28c-7208-4b73-a6c7-da099533dded))))
			- can be turned off
		- the **regular pages**:
			- aren't journals
			- can be given unique titles
	-
	- To **create a new page**, you have three options:
	  id:: 6494c06d-c398-4d79-acac-aa9e4c44ad12
		- Type double-brackets `[[]]` in a block and enter the title inside the brackets
		  logseq.order-list-type:: number
		- Use the search function (`CTRL + K` or the search button `🔍️` at the top-left) and type a new page name
		  logseq.order-list-type:: number
		- Open the left hand menu `☰` and click on the `+ Create` button at the bottom-left
		  logseq.order-list-type:: number
	-
	- To focus on a block and its nested elements: click on its bullet to **open the block as a page**:
		- ![Open block as a "page"](https://i.imgur.com/dScAKLa.mp4)
-
- # Bi-directional Internal Links & References
  id:: 6494c06d-2a0b-4e17-8e9d-f58d403759e1
	- ![Page referencing](https://i.imgur.com/f4rbfLx.mp4)
	-
	- Logseq's power lies in its linking abilities. Once you create a link to a page, you can navigate to it by [hovering over the link to preview]([[Logseq Demo Graph - Getting Started]]) or clicking on the link.
	-
	- At the bottom of each page, there is a section called a "**Linked References**".
		- It's Logseq way of saying, "Hey page, another page mentioned you at this block". The reference will remain even if you rename the page.
		- It can also do this if you didn't make a direct link to another page, but wrote the name of the page on another page. This is what "**Unlinked References**" are for.
	-
	- You can even ==visualize the connection between pages== by clicking on the right-hand panel icon, and clicking on the "**Page graph**" button. This shows what pages are connected to the page you're currently on.
	- You can also ==visualize the connections between your entire graph== project by going to the left-hand menu `☰` and clicking on "**Graph view**".
	-
	- Not only can you reference pages in other pages, but you can also **reference blocks in other blocks**. To achieve this, you can do one of the following:
		- Type two parentheses `(())` to search for the block you want to reference.
		  logseq.order-list-type:: number
		- Place your cursor on the block you wish to reference, press `CTRL + C` to copy the uuid, and paste the reference in a new block.
		  logseq.order-list-type:: number
		- Hover over a bullet `•`, right-click it, and either select `Copy block ref` or `Copy block embed`:
		  logseq.order-list-type:: number
			- A **block reference** displays the referenced block inline (without its nested elements)
			  id:: 7f67d417-b0fc-4b22-b45b-6c9faa0a16f9
			  collapsed:: true
				- ((7f67d417-b0fc-4b22-b45b-6c9faa0a16f9))
			- A **block embed** allows you to edit the contents of the referenced block and includes any nested blocks
			  id:: f68a671b-944d-42e1-92d3-02c47297b89f
			  collapsed:: true
				- {{embed ((f68a671b-944d-42e1-92d3-02c47297b89f))}}
			- In either case, any changes made to the original block are reflected in all of its references. This allows you to keep one source of truth.
	-
	- ![Block references](https://i.imgur.com/xvdSoem.mp4)
-
- # Learn More
  id:: 64951c3c-37fb-4c67-8ad6-9a61e55e7143
	- Ready for more? Check out the [[Formatting Style Guide]], my [[Favourite Plugins]], and [[Advanced Tips & Tricks]]