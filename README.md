# PDFtoChat

## Todos v1.5

- [ ] On mobile, make sure chat shows up when you hit the toggle (make chatbot slower)
- [ ] Change Clerk to be production mode
- [ ] Spin up good README + tweet
- [ ] Fix OG image not showing up

## Common errors

- Check that you've created an `.env` file that contains your valid (and working) API keys, environment and index name.
- Make sure your pinecone dashboard `environment` and `index` matches the one in the `pinecone.ts` and `.env` files.
- Check that you've set the vector dimensions to `768`.
- Make sure your pinecone namespace is in lowercase.

## Credit

- Mako for the original RAG repo
- Joseph for help and for his langchain next.js repo
- Together AI, Bytescale, Pinecone, and Clerk for sponsoring

## Future Todos

- [ ] Explore best practices for scrolling based on other chat apps like chatGPT and implement auto scrolling
- [ ] Do some prompt engineering for Mixtral to make it as good as possible
- [ ] Add my own google cloud project to Clerk for it to show 'PDFToChat'
- [ ] Change the header at the top with something more similar to roomGPT to make it cleaner
- [ ] Add video to homepage to demonstrate functionality
- [ ] Implement sources like perplexity to be clickable with more info
- [ ] Make some changes to the default tailwind `prose` to decrease padding
- [ ] Add an initial message with sample questions or just add them as bubbles
- [ ] Add a trash icon for folks to delete PDFs and implement delete functionality
- [ ] Add an option to get answers as markdown or paragraphs
- [ ] Save chats for each user to get back to later
- [ ] Use a session tracking tool to better understand how folks are using the site
- [ ] Clean up and customize how the PDF viewer looks to be very minimal
- [ ] Bring up a message to direct folks to compress PDFs if they're beyond 10MB
- [ ] Migrate to the latest bytescale library and use a self-designed custom uploader
- [ ] Add better error handling overall with appropriate toasts when actions fail
- [ ] Upgrade to Next.js 14 and fix any issues with that
- [ ] Add support for images in PDFs with something like [Nougat](https://replicate.com/meta/nougat)
- [ ] Add rate limiting for uploads to only allow up to 5-10 uploads a day using upstash redis
