# Lab 7
**Members - Christine Le**

## Check for understanding questions
1. I would fit my automated tests within a github action that runs whenever code is pushed because this removes the manual task of testing. After I push I'll know automatically if there's errors in my code or if it's all good to merge. Also, I would be testing in small increments so I can gradually test and improve my code.
2. No, end-to-end tests simulate user actions in a broswer. For verifying a function's output, I'd do a unit test which directly tests the function's logic.
3. Navigation mode will analyze a page after it loads and provides an overall performance metric based on that. This includes FCP, LCP, total blocking time, speed index, and cumulative shift layout. Navigation mode also can't analyze interactions or changes in content. On the other hand, snapshot mode will only analyze a page based on its current state. It's best used for finding accessibility issues. It returns a score rating the accessibility of the page, and any html errors.
4. Based on the snapshot mode, we can improve the site's accessibility by adding a `lang` attribute to the `html` element. From navigation mode, we can improve our SEO rating by including a `meta` description fofr the document and by reducing the page load time by shortening the chain of JS dependencies, and reducing the download size of resources. 





