<!-- This template is in markdown, not html, so
  it will not render beautifully when you copy and
  paste it into your github.io site, but it will at
  least be published. Next week you'll be creating a
  blog template using HTML and CSS and you'll be able
  to copy and paste the blog posts from week 1 in there
  to make them pretty next week.

  For now, please replace the title, subtitle (if desired),
  and date with the text you would like. Markdown is pretty
  simple, so you can just feel free to type. =) -->


# DBCgit Blog Post
#### "Git 'er Done With Version Control'
#### 9/18/14

Version control is one of those things that anybody creating any project from a manuscript, to a computer program, to a financial model should be doing.  It just makes too much sense!  Chances are that someday, disaster will strike and that's when you'll fully realize why it is so important.  In a previous life as a financial analyst, I learned this lesson the hard way...multiple times!

In simplest terms, version control allows you to keep track of the development of your project at multiple break points.  So if you screw something up, you can always go back to the working state of the project at the previous break point (you don’t have to start over or agonizingly search for the mistake!).  Without the use of more sophisticated version control systems, this was can be done through a crude method of naming files such as version1, version2, etc or even by just appending the date and time.  At least that's what I used to do with my spreadsheets! 

But version control systems such as Git keep track of the changes you make as you go along and store all of the changes in a repository.  In Git, your repository has a master branch and this is where the latest, properly working version of your code resides. When you want to make a change or add features, Git enables you to copy the code from the master branch and place it on a "new branch."  You then can work on and make changes to this “copy” of the code.  If you screw up or dislike what you have changed or added, you can always throw out this branch and revert back to the previous copy that is still held on the master branch.  But if you do like what you have done and these changes work properly, you can merge this new code back into the master branch.  By "committing" this new version of the master branch, you are saving a new "official" version of your code and updating the master branch. 

This version control and tracking of changes is extremely important when you have more than one person working on the same file/project.  Instead of overwriting one another's changes or having to manually compare and merge changes from one person with those of another, Git takes care of all of this for you.  By creating branches for each person to work on, multiple people can work on the same file/project at the same time and this increases the efficiency and effectiveness of the project team.  Each team member's changes are later merged into a single version and the system highlights conflicts or problems for you and the rest of the team.   

But Git is software that lives locally on a single person's computer and those files/versions are not accessible by others.  In order for the collaboration described above to work, the repository and each team member's files need to somehow be made remote by uploading them to and storing them in the cloud.  This is where Github comes in.  Github lives remotely, on the Internet, and stores the team's versions in the cloud so they are accessible by each other.  Now the entire team can collectively take advantage of the benefits of version control.  



