# GeeMail 

GeeMail is a coding exercise meant to simulate an e-mail web application inbox.

## Description

With this coding challenge I simulated of a little known e-mail web application you might have heard of before.
A basic mail generator script was provided and my goal was to consume that data and build out UI elements to display that data along with populating new messages and some other basic functionality.

## Objectives

1. Fork the repo.

2. Create a basic page layout via HTML/CSS with a top header section with the name of the application and a content section where the messages can be displayed.

3. When the page loads, via JavaScript access the the data stored in the `window.geemails` variable. Each object in the array has the following properties:
	* date - The date message was sent
	* subject - The subject of the message
	* sender - The sender of the message
	* body - The GeeMail message content

4. Make a visual list of mail messages on the page.
	* Each message has it's own row showing:
		* Date
		* Sender
		* Subject
	* When clicking on the message's subject, it shows the body of the e-mail for that row.

5. Create an inbox count somewhere on the page to show the current number of messages in the inbox.

6. Set a recurring function via the JavaScript `setInterval` function that will call the `getNewMessage` function.

7. All JavaScript should be created in the `<head>` element in the `index.html` file.

# DONE! :)