- Logseq lets you embed, preview, and play back a variety of media — whether it's saved online or saved on your computer.
  id:: 6499a502-ea91-43d9-aca3-0bca49c9872b
-
- There are **three methods to embed media**:
	- 1. [Markdown Method](https://docs.logseq.com/#/page/embed%20media%20-%20audio%2C%20photos%2C%20videos/block/markdown%20method): `![](Link-To-File)`
	- 2. [HTML Element Method](https://docs.logseq.com/#/page/embed%20media%20-%20audio%2C%20photos%2C%20videos/block/html%20elements%20method): `<element src="Link-To-File"></element>`
	- id:: 6499aacd-4caf-4c33-8ae9-e04b5d8eeb03
	  3. [Hiccup ClojureScript Method](https://docs.logseq.com/#/page/embed%20media%20-%20audio%2C%20photos%2C%20videos/block/%5B%5Bhiccup%5D%5D%20clojurescript%20method): `[:element :src "Link-To-File"}]`
	-
	- You can find detailed examples for each method here: [Embed Media - Audio, Photos, Videos](https://docs.logseq.com/#/page/embed%20media%20-%20audio%2C%20photos%2C%20videos)
-
- Here are some things to consider when adding media to your pages:
-
- # Local Storage vs Online Storage
	- When embedding media files to a block, you can either:
		- point to a file on your device (local storage), OR
		- point to a file stored online
	-
	- ### Comparison Table
		- |**Type**|**Pros**|**Cons**|
		  |--|--|--|
		  |**Local storage**|* Files will display offline|* Not ideal for graphs you intend to export and share online[:br]* Uses the storage on your device|
		  |**Online storage**|* Offload storage of media files elsewhere[:br]* Less of a pain for graphs intended for online publishing|* Media won't display without an Internet connection[:br]* Extra step of uploading the media file to a server|
	-
	- ### Embedding Local Files
		- **To link to a local media file:** Paste the file path from your file explorer (including the file name and extension). You may also need to add `file:///` at the beginning.
			- ex: `C:/Users/user/Videos/file.mp4`
		-
		- To help with quickly linking to files found on your computer (outside of the assets folder), I recommend using ((6498e61e-c28d-467f-85a6-308496e11e82))
		-
	- ### Embedding Online Files
		- **To link to an online media file:**
			- Paste the URL of the media, making sure that the file name and extension is included.
				- ex: `https://www.mysite.com/file.mp3`
			- OR
			- For YouTube and Vimeo: paste the URL -> Logseq will convert it into a video macro
				- ex: `{{video https://www.youtube.com/watch?v=hz2BacySDXE}}`
			- OR
			- For other platforms: Paste the iframe embed link
				- ex:
				  ```
				  <iframe style="border: 0; width: 100%; height: 120px;" src="https://bandcamp.com/EmbeddedPlayer/album=1610030682/size=large/bgcol=ffffff/linkcol=0687f5/tracklist=false/artwork=small/track=783623192/transparent=true/" seamless></iframe>
				  ```
		-
		- If you prefer storing your assets online, I recommend saving a copy of the file to a cloud storage meant for public file hosting, and <u>not</u> a personal cloud service like Dropbox or Google Drive. Here are some **suggested online file storage services**:
			- [Imgur](https://imgur.com/upload): for images and GIFs
			- [Cloudinary](https://cloudinary.com/): all media types
			- [Backblaze B2 Storage](https://www.backblaze.com/b2/cloud-storage.html): all media types, with more advanced configurations
	-
- # Assets Folder
	- Images, video files, audio files, and PDFs can be copy-pasted directly into a block.
	  Doing so will save a copy of the file into the assets folder of your graph, and link to the asset using Markdown: `![](Link-To-File)`
		- ![copy-pasting media to block](https://i.imgur.com/2mLPMOj.mp4)
	-
	- If you're copying image files from the Internet and want to download a copy to your graph's assets folder, make sure to enable the setting. Click on the three horizontal dots `•••` at the top-right and go to the `Settings > Editor` and enable `Prefer Pasting File`
		- ![Prefer Pasting File option](https://i.imgur.com/7P3BeOe.mp4)
	-
	- The benefits of saving your media to your Assets folder are...
		- media files move with your graph, regardless of device used
		- access to media regardless of Internet connection
		- preserving a copy of the file without worrying about deletions at the source
	-
	- The downsides are...
		- the saved assets take up space on your device's storage
		- you may run into issues with HTML (public pages) graph exports