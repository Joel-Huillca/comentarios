# comentarios
Modo pruebas




> When GitHub initially introduced Copilot, I was suspicious. In addition to not understanding the technology, I was uncertain how it would affect my job and the industry. However, as I started to use Copilot, I gained an appreciation, understanding, and even eagerness about the future of AI pair programming tools ✈️. I’m passionate about Copilot because it helps increase my confidence and velocity as a programmer. I’ll share how you can use Copilot to enhance your developer experience too!
> 
> ## What is GitHub Copilot?
> [GitHub Copilot](https://github.com/features/copilot) is an AI pair programmer that helps you code faster with less work. The user experience is similar to the [Smart Compose](https://workspaceupdates.googleblog.com/2020/02/smart-compose-ga.html) feature within Google Docs and Gmail, which autocompletes sentences while the user is typing. Similarly, GitHub Copilot instantly draws context from comments and code and instantly suggests individual lines and whole functions instantly ⚡.
> 
> ## What is GitHub Copilot Labs?
> GitHub [Copilot Labs](https://githubnext.com/projects/copilot-labs/) is a separate extension that comes complimentary with GitHub Copilot. _Please keep in mind that Copilot Labs is an experimental extension developed by the GitHub Next team._ Currently, Copilot Labs consists of a VS Code sidebar that houses distinct features starting with “explain this code” and “translate this code.”
> 
> ## Is GitHub Copilot magic 🪄?
> Although Copilot feels like magic, it’s not. To suggest lines of code, Copilot needs a programmer's brain. Under the hood, GitHub Copilot is powered by OpenAI Codex. OpenAI is an AI research lab that developed Codex, a model that translates natural language into code. Codex is a version of GPT-3, another model developed by OpenAI. GPT-3 (Generative Pre-trained Transformer 3) uses deep learning to produce human-like text. Many of your favorite applications use GPT-3. For example, [Duolingo](https://blog.duolingo.com/test-creation-machine-learning/) specifically uses GPT-3 for French grammar correction. Codex also features natural language understanding but is fine-tuned for programming. By leveraging Codex, Copilot can help computers interpret people’s intent and empower developers to code with confidence.
> 
> ## Is GitHub Copilot perfect?
> GitHub Copilot does not always spit out perfectly well-written, up-to-date code. Occasionally, some of its suggestions are [downright hilarious](https://twitter.com/MikeMcQuaid/status/1542434802430873600?s=20&t=I134_uPpndaxzvKxA76j8g). However, it’s more commonly accurate, and it continues to improve 🚀. Here are some tips to ensure technologists receive their desired suggestions:
> 
> * **Tip [Welcome to GitHub product feedback #1](https://github.com/orgs/community/discussions/1)**: Try writing clear, understandable comments to get the best results from Copilot.
>   ![Country codes](https://user-images.githubusercontent.com/22990146/188703640-dfdaa243-9759-4b05-8dce-47acb6711e61.gif)
>         
>           [
>             
>           ](https://user-images.githubusercontent.com/22990146/188703640-dfdaa243-9759-4b05-8dce-47acb6711e61.gif)
>           
>               ![Country codes](https://user-images.githubusercontent.com/22990146/188703640-dfdaa243-9759-4b05-8dce-47acb6711e61.gif)
>             
>           
>             
>               
>                 
>               
>               
>                 
>                 
>               
>             
>             [
>               
>                 
>               
>             ](https://user-images.githubusercontent.com/22990146/188703640-dfdaa243-9759-4b05-8dce-47acb6711e61.gif)
> * **Tip [Feature Request: Select a column when adding an issue to a project #2](https://github.com/orgs/community/discussions/2)**: Prompt GitHub Copilot to give you other suggestions by using a few keyboard shortcuts. You can learn more about viewing multiple suggestions [here](https://docs.github.com/en/copilot/getting-started-with-github-copilot/getting-started-with-github-copilot-in-visual-studio-code#seeing-alternative-suggestions).
> 
> ![Copilot shortcuts](https://user-images.githubusercontent.com/22990146/201698438-ce4d7ce6-bb36-4551-aad5-b9743fc5bf89.png)
> 
> ## How does GitHub Copilot benefit developers?
> ### Coding faster
> Whether working as a software engineer or a developer advocate, I've found myself in moments where I'm writing code at the last minute 🕰️, or experiencing a coder's block. Reading suggestions from Copilot reminds me of how to solve common and not-so-common algorithms.
> 
> ![Image description](https://camo.githubusercontent.com/5894d875cd6c65ea0be1ecfe8c36847f63a0c8c0562c6ea94a88f5b211e87bf4/68747470733a2f2f6465762d746f2d75706c6f6164732e73332e616d617a6f6e6177732e636f6d2f75706c6f6164732f61727469636c65732f356e3131653431323839686a686a63373438656f2e706e67)
> 
> ![Image description](https://camo.githubusercontent.com/c00b0363a5de77926705799f283706df35546ddfad2bbe548baf2330587e9e9b/68747470733a2f2f6465762d746f2d75706c6f6164732e73332e616d617a6f6e6177732e636f6d2f75706c6f6164732f61727469636c65732f7472727a366e643338756d69786c3269723267382e706e67)
> 
> ![Image description](https://camo.githubusercontent.com/2d72e789aeab62efdb34c43c5b29fa37176e0237f1670c567d59a68c531628ac/68747470733a2f2f6465762d746f2d75706c6f6164732e73332e616d617a6f6e6177732e636f6d2f75706c6f6164732f61727469636c65732f64706565616b716c74637a317933797969756e382e706e67)
> 
> ### Writing tests
> While I understand that writing tests for your code are essential, I don't enjoy it. I often take forever to start – trying to remember the difference between keywords like `mock`, `nock`, `beforeEach`, and `afterAll`. Then, when I get the pattern down, it feels like a tedious process for me to reach a particular test coverage percentage. This is where Copilot can come in handy. I can write a few comments describing what I want to test; then, Copilot may suggest the code needed for the test. I can also start writing tests, and Copilot may provide anticipated code for other needed tests. Learn more by reading [Using GitHub Copilot to Automate Tests ](https://applitools.com/blog/using-github-copilot-to-automate-tests/)by [Colby Fayock](https://github.com/colbyfayock) and [Rewriting tests from Cypress to Playwright using GPT-3](https://contra.com/p/PWBcPYZc-rewriting-tests-from-cypress-to-playwright-using-gpt-3) by [Gajus Kuizinas](https://github.com/gajus).
> 
> ### Writing better comments
> Sometimes, writing great comments ends up on the back burner. There's a tendency to assume your code is clean, readable, and self-documenting until you return to your code the next day and you're unable to decipher the hieroglyphics. Since well-written comments tend to trigger better results from Copilot, I'm more motivated to write explicit, relevant comments.
> 
> **For example, Copilot can understand Spanish comments!**
> 
> ![spanish comment](https://user-images.githubusercontent.com/22990146/188705342-549cf999-ff2c-4b81-99c0-4e466ee7d8b4.gif) [ ](https://user-images.githubusercontent.com/22990146/188705342-549cf999-ff2c-4b81-99c0-4e466ee7d8b4.gif) ![spanish comment](https://user-images.githubusercontent.com/22990146/188705342-549cf999-ff2c-4b81-99c0-4e466ee7d8b4.gif) [ ](https://user-images.githubusercontent.com/22990146/188705342-549cf999-ff2c-4b81-99c0-4e466ee7d8b4.gif)
> 
> **Copilot can help you write Regex!**
> 
> ![validate phone number](https://user-images.githubusercontent.com/22990146/188703630-5a0b3b32-89b4-4937-864f-f24cb957c954.gif) [ ](https://user-images.githubusercontent.com/22990146/188703630-5a0b3b32-89b4-4937-864f-f24cb957c954.gif) ![validate phone number](https://user-images.githubusercontent.com/22990146/188703630-5a0b3b32-89b4-4937-864f-f24cb957c954.gif) [ ](https://user-images.githubusercontent.com/22990146/188703630-5a0b3b32-89b4-4937-864f-f24cb957c954.gif)
> 
> ### Pair programming with a coworker
> I'm not fantastic at pair programming, especially when I have less experience than my colleague. I also experience anxiety about people watching my every move while I code. What stops me in my tracks is that I often try to remember the syntax. With Copilot, my pair programming buddy spends less time watching me Google the "Reduce JavaScript array method" for the umpteenth time. Instead, GitHub Copilot suggests the correct syntax for me.
> 
> Using GitHub Copilot is a game-changer, but don’t take my word for it. In a recent [study](https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/), “60–75% of users reported they feel more fulfilled with their job, feel less frustrated when coding, and are able to focus on more satisfying work when using GitHub Copilot.”
> 
> ## How do I install it?
> GitHub Copilot is available in Visual Studio Code, JetBrains, and my favorite, Neovim. Copilot is available for developers today and is free for qualified teachers, students, and maintainers of popular open source libraries. [Sign up](https://github.com/features/copilot) for GitHub Copilot 👩‍✈️today!
> 
> ## What’s next?
> GitHub Copilot has inspired the evolution and development of other AI pair programming tools. It also enables developers and open source maintainers to think outside the box and create confidently. There is much more to share about GitHub Copilot and how it can improve our lives as developers, so stay tuned for my next post.
> 
> _If you have any questions or want to share your love for GitHub Copilot, feel free to comment below!_
