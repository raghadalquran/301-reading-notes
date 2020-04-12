# SUMMARY #

- Partials come in handy when you want to reuse the same HTML across multiple views. 
- Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. 
- Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.
- In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %> delimiters (you could change these delimiters if you really wanted to).

**Note: The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’, etc…**
- As you can see creating and including partials is very straightforward with EJS.
- I’ve intentionally left in some placeholders such as LIST_OF_POSTS, POST_TITLE, POST_AUTHOR, and POST_CONTENT so that we can take a look at how we can pass data from our Node + Express application to our views in the next section.

![Image](https://i.stack.imgur.com/Jt4nj.png)
