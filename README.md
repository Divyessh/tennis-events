# tennis-events

Follow these steps to add an event -

### Step 1 

Fork the repository and then clone it locally -
 
	git clone https://github.com/<username>/tennis-events
### Step 2

Make a markdown file under "_posts" directory with the following naming convention - 
	<YYYY-MM-DD-Title.markdown>
example -
	cd tennis-events
	touch _posts/2021-07-09-tennis-open-2021.markdown	

### Step 3

Copy the contents of the [file](https://raw.githubusercontent.com/divyessh/tennis-events/master/template-event.md) and fill the details using these [variable](https://github.com/divyessh/tennis-events/blob/master/contribute.md). 

### Step 4

Commit the changes to a new branch 
[name it by the name of your event]

	git checkout -b <your-event-name>
	git add <files>
	git commit -m <message>

### Step 5

Push the code 

	git remote add origin git@github.com:<username>/tennis-events.git
	git push origin

### Step 6

Create a Pull Request 
