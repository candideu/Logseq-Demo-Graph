- Picture this: a website version of your Logseq graph which...
	- showcases your pages, references, network graphs, whiteboards, flashcards
	- makes your content easily accessible to others in a read-only format
	- doesn't require your viewers to download the app or worry about accessing outdated versions
-
- Sounds like a dream, right? Well, fret not! In this guide, you'll learn how to export your Logseq graph into a captivating website that will leave your audience in awe.
-
- # Marking Pages for Publishing
	- Before you export your pages, make sure to indicate which pages to include in your website.
	- To do so, you can either:
		-
		- **Mark your entire graph as public.**
			- ![Make entire graph public](https://i.imgur.com/04RcBhh.mp4)
			- Click on the three horizontal dots `•••` at the top-right, go to `Settings > Editor`, and enable `All pages public when publishing`
			- All the pages in your graph will now be included in your exported site, unless you change a page's [property](((6499faf4-36c5-44d2-ba2a-9e489b209292))) to `public::false`
		-
		- **Mark only select pages as public.**
			- ![Mark select pages as public](https://i.imgur.com/IvDsJup.mp4)
			- Click on the three horizontal dots `•••` at the top-right, go to `Settings > Editor`, and disable `All pages public when publishing`
			- To make an individual page public, do one of the following:
				- Right-click on the page's name and select `Make it public for publishing`
				- Click on the three horizontal dots `•••` at the top-right and select `Make it public for publishing`
				- Add the [property](((6499faf4-36c5-44d2-ba2a-9e489b209292))) `public::true` to the first block of the page
-
- # Generating the static site files
	- ![Export Graph as Public Pages](https://i.imgur.com/wmyhAzr.mp4)
	-
	- Create a folder on your PC to house the exported files.
	  logseq.order-list-type:: number
	- In Logseq: click on the three horizontal dots `•••` at the top-right, click on `Export Graph`, click on `Export public pages` and save to the folder you created.
	  logseq.order-list-type:: number
	- Logseq will generate the appropriate HTML, CSS, and JavaScript files for your site.
	  logseq.order-list-type:: number
	- You can now upload the contents of the folder to any web host that accepts static files.
	  logseq.order-list-type:: number
		- I've enjoyed using Netlify Drop and GitHub Pages, which both have generous free plans.
		- You'll find detailed instructions for each below.
	-
	- #+BEGIN_TIP
	  To update your live website, you will need to re-export the graph's public pages.
	  #+END_TIP
-
- # Hosting your exported graph
	- ## Netlify Drop
		- ![Netlify Drop](https://i.imgur.com/OiH98dX.mp4)
		-
		- This is the easiest method for hosting static site files for free.
		-
		- Head to [netlify.com/drop](https://app.netlify.com/drop/) and drop your folder in. That's it! 🎉
		  logseq.order-list-type:: number
		- #+BEGIN_TIP
		  If you're not logged in, your website will only be available for an 1 hour.
		  Make sure to create an account!
		  #+END_TIP
		- **Next steps**
			- To update your website, re-generate the files in Logseq, and upload them to Netlify in your project's `Deploy` section
			  collapsed:: true
				- ![Update Netlify deploy files](https://i.imgur.com/3dXvJgn.mp4)
			- If you own a domain, you can connect it to your Netlify deployment to give it a friendlier URL. [Read more about custom domains here](https://docs.netlify.com/domains-https/custom-domains/).
	-
	- ## GitHub Pages
		- This method is a bit more complex than Netlify Drop, but is ideal for keeping a detailed record of changes from version to version.
		-
		- ![Publish Your Exported Graph to GitHub Pages](https://diode.zone/download/streaming-playlists/hls/videos/13655753-b854-422d-8e8d-16dce21adb99-1080-fragmented.mp4)
		-
		- First, [create a GitHub account](https://github.com/join) and [download GitHub Desktop](https://desktop.github.com/).
		  logseq.order-list-type:: number
		- Sign in to your GitHub account on GitHub Desktop ([instructions](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop)). You may also need to [configure Git](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop#part-3-configuring-git).
		  logseq.order-list-type:: number
		- In GitHub Desktop, create a new repository (`CTRL + N`). Set the local path to your exported graph's folder.
		  logseq.order-list-type:: number
		- Publish the repository from GitHub Desktop.
		  logseq.order-list-type:: number
		- Once published, head to the repository's online GitHub page by going to `Repository > View on GitHub` or hitting `CTRL + SHIFT + G`.
		  logseq.order-list-type:: number
		- On the online GitHub page, go to `Settings > Pages`. Under `Build and deployment > Branch`, select `main`.
		  logseq.order-list-type:: number
		- Your page is now published to GitHub Pages at `[username].github.io/[repository-name]`! 🎉
		  logseq.order-list-type:: number
		-
		- **Next steps**
			- To update your website:
				- ![Update your GitHub Pages Hosted Graph](https://diode.zone/download/streaming-playlists/hls/videos/ed481a27-0b6d-4bdb-a1af-0ad305530336-1080-fragmented.mp4)
				- Re-generate the files in Logseq to the same export folder on your computer.
				  logseq.order-list-type:: number
				- Open GitHub Desktop and select your site's repository. GitHub will have detected any new changes.
				  logseq.order-list-type:: number
				- Push the changes to origin via GitHub Desktop, and your live site will update momentarily.
				  logseq.order-list-type:: number
			- To connect a domain you own, consult the GitHub doc on [configuring a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
	-
	- ## GitHub Action
		- The third way of hosting your graph is using [GitHub Actions](https://github.com/features/actions). This method is more complex, but may better meet your needs. You could use the [community-made Action](https://github.com/pengx17/logseq-publish) or [Logseq's official Action](https://github.com/logseq/publish-spa).
		  collapsed:: true
		  Here's a [video tutorial for logseq-publish](https://www.youtube-nocookie.com/embed/UYqJcFEYUsY), the community-made Action.
			- {{video https://www.youtube-nocookie.com/embed/UYqJcFEYUsY}}
-
- # Limitations
	- Published graphs don't work exactly the same as local graphs accessed on your Logseq desktop app. Here are some known limitations:
		-
		- **PDFs:** Previewing [PDF files and highlights on the left side](((6498e61e-3ddd-4207-a28f-95fbeec4e2c5))) doesn't work.
		-
		- **Assets:** You may run into issues with media assets stored in the `assets` folder of your graph.
		  -> I recommend uploading your media online first and [linking to it in the graph]([[Working with Media Files: Embed Audio, Photos, Videos]]).
		-
		- **Plugins and themes**: Plugins and themes downloaded from the marketplace won't work.
		  -> Instead, add your customizations to the following files in the `logseq` folder of your graph folder:
			- |**File name**|**Explanation**|**Example**|
			  |--|--|--|
			  |**custom.css**|Custom styling of the overall graph (desktop app, mobile app, and exported site)|[Custom stylesheet](https://github.com/Digitized-Diasporic-Memory/Memory-Graph/blob/main/static/css/custom.css)|
			  |**export.css**|Additional custom styling that is only applied to the exported site|[Export-specific stylesheet](https://github.com/Digitized-Diasporic-Memory/Memory-Graph/blob/main/static/css/export.css)|
			  |**custom.js**|Custom JavaScript commands|[Custom scripts](https://github.com/cannibalox/logseq-custom-files/blob/main/custom.js)|