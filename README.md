#Members

Koji Nakazawa

#Check Your Understanding

1. For my recipe project development pipeline, I would run my automated tests in within a Github action that runs whenever code is pushed. This way, whenever somebody commits changes and pushes code, they will get immediate feedback on the behavior of their code and can spot any bugs that needs to be addressed. Manually running is a bad idea since developers may forget to to run the tests and running all of them after development is complete will result in unnoticed bugs piling up upon each other and will lead to a very difficult time debugging.

2. No, unit tests would be better suited for that since it is a small specific component of the website.

3. Navigation mode conducts its analysis after the page is done loading whereas snapshot mode analyzes the current appearance of the page. Navigation mode is good for performance measurements and tests while snapshot mode is better for checking the UI and appearance for users.

4. - We can add a [lang] attribute to the <html> element
   - We can add a meta description to the document
   - We can shorten the critical request chains, reducing the size of downloaded files, and deferring resources that are not needed right away. This would help the page load faster.





