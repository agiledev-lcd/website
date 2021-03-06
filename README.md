# AgileDev-koeln.de

This project was build around the task to present our LCD-Team. The working website is available at [AgileDev-koeln.de](https://agiledev-koeln.de).

## Getting Started

These instructions will get you the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You don't need anything regarding prerequisites, beside the actual repository on your PC, to run the Website. The only module which isn't going to work is the contact-formular, since it requires PHP to work.
A work-around would be to deploy the repository on a webserver or to host a server on localhost. Visit [ApacheFriends.org](https://www.apachefriends.org/index.html) for further information on XAMPP (local server). 

### Installing

To install the basic website (without the contact-formular), you have to clone the repository to a folder of your choice. After that the website can be accessed by opening /index.html with any browser.

Visit [ApacheFriends.org](https://www.apachefriends.org/index.html) on how to set up a local webserver for the full website to work. The website is then reachable per browser at localhost.

### Testing

Since the website is build on HTML, CSS, Bootstrap and a bit of PHP, not much testing is required. Automated tests are unefficient, because besides links the only thing to be tested is the formular, which can be (and is) tested in person.

## Deployment

The deployment on a live system (a webserver) is the same as deploying it locally/ on a local server. You have to copy the repository in the webservers main folder - the server recognizes automatically that "index.html" is the landing page.
Besides that, main settings (e.g. domain etc.) have to be set up, to be able to reach the website over the internet.

## Built With

* HTML
* CSS
* PHP
* [Bootstrap](https://getbootstrap.com/) - The web framework used
* [Adobe CC](https://www.adobe.com/de/creativecloud.html) - Design and Logo
* [Pixabay](https://pixabay.com/photos/) - Free stock photo archive
* [w3schools.com](https://www.w3schools.com/) - A large library for web development

We didn't use the github-issues to organize our project, we managed several to-do lists in communication with the team. After deciding which task to implement next we created new feature branches to work parallel.
This is an overview of our last active branches as at 29.03.2019 21:42:
![Branches](assets/branches.png)

## Website Architecture

The website has a single-page-layout. Exceptions are the two additional pages "impressum.html" and "contactform.php", which link back to the main page (contactform.php redirects automatically).
index.html is the landing (main) page and contains the content, image references and basic structures. It embeds "style.css" which designs the raw HTML-file.
All HTML, CSS and PHP files (and readme.md/license.md) are in the main folder and image or fonts resources are in /assets/ to grant an overview.

## Versioning

We use [GitHub](https://github.com/) for versioning. For the past versions, see the [project online](https://github.com/agiledev-lcd/website). 

## Contributors

* **Steffen Weisshaar**
  * Back-End 
  * Front-End
* **Nicolas Schlicht**
  * readme
  * Front-End
* **Muzamal Cheema**
  * Back-End
  * PHP
* **Serhat Üstündag**
  * Concept
  * Text

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
