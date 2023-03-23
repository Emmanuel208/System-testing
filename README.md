# testing-projectCA3
Application that shows basic testing scripts on django



# Back-End Web Development - BSC30922 & BTM0922 - Semester 2

In this document we will be covering the Creation of a simple Django-Python project and run testing on various testing to ensuer the application is working as it should.



## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Geoff Wright](https://github.com/Geoff-Wright)
  - [project Template](https://github.com/TheDumbfounds/django-testing-tutorial)
 


## Authors

- [Chukwuemeka Emmanuel Obasi ID: 23606](https://github.com/Emmanuel208)



## Documentation

I was tasks to build on an alredy working application and add testing to the appliaction, create a sperate file where this testing will take place for organization, add additional anti-hack security to prevent things like sql injuctions and include postive and negetive testing.

In my attempt to complete the project I decided to work with a simple appliction that simply shows total expenditure the balance. With this I was able to run a few tests. I ran test in my form.py, url.py, model.py and view.py files respectivlty.

### forms: 
In my form.py I ran test to show if the data in the expense form is valid and if it had no data at all. Doing this gives confidence to the forms code.

### url:
In my url file I check if the list, details and add fucntionS were resolved when asked. This is nesccery to ensuer a url link is working as it should.

### model:
In this section, I have a Category, Expense and Project function in a model. The test I ran ensuerd the models fucntions where called and created on oncreate and where assisgned a slug on oncreation. Doing this will ensuer the application will fucntion at the very least.

### view
In this section I tested if the get list and details where gottten. This test also checks when something is added to the list and makes sure it is of correct type. The test also covers detils post data. Meaning it will check if there is zero 0 data.

## Additional security 
I added security to prevent XSS explotation. A Cross-Site Scripting (XSS) attacks are a type of injection, where malicious scripts are forcfully injected into a trusted website. XSS attacks occur when an attacker uses a web application to send malicious code through usually a search bar or a form. The attacker writes script code and bypasses the website security. Information like website cookie can be seeing with basic javascript input. Example: <script> Documentation cookies</script>.
I prevented this from happining by making sure my website is not automaticaly lised as a safe website.

Another securtiy challeneg we face is sql injection. Basically, a sql injection is when a hacker takes advantage of string formatting and quote placeholders with a raw query. I avoided this by virtualizing my sql database through my command line. By using 'mkvirtualenv' you avoid this problem all together. Althrougt this has it limitations and my not be best practices in all cases.



[Documentation](https://linktodocumentation)



## Feedback

If you have any feedback, please reach out to us at 23606@student.dorset-college.ie 

Thank you


![Logo](https://th.bing.com/th/id/R.f8bbf9e89283f33ff46c70d5bd657b26?rik=fz4xoBwZUCCuCA&riu=http%3a%2f%2fwww.plccourses.ie%2fwp-content%2fuploads%2f2012%2f02%2fdorset-college.jpg&ehk=q05y43yzdxL8O1WDEPzBKkpg1FCwcVQIjpU0DRIIzOY%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1)

