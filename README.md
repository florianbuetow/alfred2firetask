Firetask for Alfred 2
==============
<span>
<img src="https://www.alfredapp.com/media/logo.png" width="80px" border=0>
<img src="http://www.firetask.com/images/icon-firetask-mac.png" width="80px" border=0>
</span><br/>

This workflow for Alfred2 lets you add new tasks to the "In-Tray" of the Firetask GTD productivity app.

### Demo:
![Firetask for Alfred workflow in action](screenshot.gif "Firetask for Alfred workflow in action")


### Requirements:

In order to use this workflow you need:

- [Alfred 2](http://www.alfredapp.com "Alfred - Productivity App for Mac OS X") App.
- [Powerpack](http://www.alfredapp.com/powerpack/ "Boost your productivity even further with the Powerpack") addon for Alfred 2.

- [Firetask](http://www.firetask.com "Firetask: Project-oriented GTD Task Management for Mac OS X") App.

### Download:

Click [here](https://github.com/fbcom/alfred2firetask/archive/master.zip) to download the workflow as a zip file.

### Installation:

1. Unzip the downloaded file.
2. Double click on the workflow file to install it in Alfred or drag it onto the Alfred workflow screen.

### Usage:

Use the "**ft**" trigger to show the dialog to add tasks (see demo above):

1. Type "**ft** " followed by a description of what your new task is.
2. Hit [Enter] to add the task to Firetask.
3. \o/



### Advanced Usage:

You can use the following triggers:

- "**ftc**" to to add a task with *critical priority*.
- "**fth**" to to add a task with *high priority*.
- "**ftm**" to to add a task with *medium priority*.
- "**ftl**" to to add a task with *low priority*.
- "**ftt**" to to add a task with *trivial priority*.

In addition you can use any of the following modifiers:

- *priority:*
- *notes:*
- *category:*
- *project:*
- *due:*

to define the **priority**, **notes**, **category**, **project** and the **due** date of your task.

##### Example input using modifiers:
> **ft** buy a lemon **priority:** high **category:** Errands **project:** Fruity life **due:** 2015-05-10 **notes:** buy two, just in case

This adds a **"high priority"** task by the name of **"buy a lemon"** in the category **"Errands"** and project **"Fruity life"** with a due date of **"2015-05-10"** in your In-Tray.

##### Abbreviations are also available:
> **ft** buy a lemon **prio:** high **cat:** Errands **proj:** Fruity life **due:** 2015-05-10 **note:** buy two, just in case

##### Note:

You don't need to use all modifiers at once. However the subject of the task must always be the first thing after the trigger. Also keep in mind that the names of projects and categories are case sensetive!

### Features:

- Ability to add a new Task to the "In-Tray" of Firetask.

## Contributing

1. Fork this!
2. Create your awesome feature branch: `git checkout -b my-new-awesome-feature`
3. Commit your changes: `git commit -m 'Add some awesome feature'`
4. Push to the branch: `git push origin my-new-awesome-feature`
5. Submit a pull request :-)

## License

Logos are protected by copyright by their respective owners.<br/>

__Alfred__ &reg; is a registered trademark of Running with Crayons Ltd.<br/>
__Firetask__ &reg; is a registered trademark of Gerald Aquila.<br/>
__GTD__ &reg; ist a registred trademark of the David Allen Company.<br>

This workflow is not affiliated with or endorsed by Gerald Aquila or Crayons Ltd.

[GNU General Public License Version 3, 29 June 2007 (GLP-3.0)](https://github.com/fbcom/alfred2firetask/blob/master/LICENSE) © Florian Buetow
