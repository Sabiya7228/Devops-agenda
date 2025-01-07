# git
GLOBAL INFORMATION TRACKER
      Git	is	a	version-control	system	for	tracking	changes	in	computer	files	and	coordinating	work	on	those	
files	among	multiple	people
 # USES
 It	is	primarily	used	for	source-code	management	in	software development
	it	can	be	used	to	keep	track	of	changes	in	any	set	of	files
 # GIT LIFE CYCLE
  Following	are	the	lifecycle	stages	of	files	in	Git
 Working	Directory
 Staging	Area
 Commit
 Working	Directory
 Staging	Area
 Commit
# working directory
The	place	where	your	project/ code	resides	in	your	local	disk
 This	project	may	or	may	not	be	tracked	by	git
 In	either	case,	the	directory	is	called	the	working	directory
 The	project	can	be	tracked	by	git,	by	using	the	command	git	init
 By	doing	git	init,	it	automatically	creates	a	hidden	.git	folder
# staging area
 Once	we	are	in	the	working	directory,	we	have	to	specify	which	files	are	to	be	tracked	by	git
 We	do	not	specify	all	files	to	be	tracked	in	git,	because	some	files	could	be	temporary	data	which	is	being	generated	while	execution
 To	add	files	in	the	staging	area,	we	use	the	command	git	add 
 simply in staging area we choose the files we want to commit
 # commit
  Once	the	files	are	selected	and	are	ready	in	the	staging	area,	they	can	now	be	saved	in	repository
 Saving	a	file	in	the	repository	of	git	is	known	as	doing	a	commit
 When	we	commit	a	repository	in	git,	the	commit	is	identified	by	a	commit	id
 The	command	for	initializing	this	process	is	 git	commit	
 # exactly this happens 
  Program	Workspace........ Git	initialized	Working	Directory .........staging area in wd for commit.........Files	committed	to	git	repository
  in the program work space we have the code then we intialize it a folder to become the git initilazized wd 
 Once	the	files	are	committed,	they	can	be	pushed	to	a	remote	repository	such	as	GitHub
 # working of git 
  Any	project	which	is	saved	on	git,	is	saved	using	a	commit
  The	commit	is	identified	using	a	commit	ID.
   ........ When	we	edit	the	project	or	add	any	new	functionality,	the	new	code	is	again	
committed	to	git,	a	new	commit	ID	is	assigned	to	this	modified	project
The	older	code	is	stored	by	git,	and	will	be	accessible	by	it’s	assigned	Commit	ID
# Branching
All the commits exists on the branches
 ... A branch is nothing but a linear line which is unidirectional 
 the HEAD of the branch always points to the latest commit 
 # master branch 
  The	default	branch	in	a	git	repository	is	called	the	Master	Branch
  # why branches 
   Say,	a	developer	has	been	assigned	enhance	this	code	by	adding	Feature	A.
   The	code	is	assigned	to	a developer	in	a	separate	branch	“Feature	A”.	This	is	done,	so	that	master	contains	only	the	code	which	is	finished,	finalized	and	is	on	production
    ..... and if everything goes well we merge this branch back to the master branch
    # GIT COMMANDS
    # creating repository
    we can	create	a	repository	using	the	command	git init.
    Navigate to project	folder	and	enter	the	command	git init to	initialize	a	git repository	for	your	project	on	the	local	system
      mkdir devops
      cd devops
      nano 1.txt
      nano 2.txt
      ls
      git init
      clear
      # Once	the	directory	has	been	initialized	you	can	check	the	status	of	the	files,	whether	they	are	being	tracked	by	git or	not,	using	the	command	
       git status
       let	us	now	stage	these	files.	
For	that,	enter	the	command	git add.	If	we	want	to	track	all	the	files	in	
the	project	folder,	we	can	type	the	command,
git add . ( or files name which we want to stag)

# commit 
Once	the	files	or	changes	have	been	staged,	we	are	ready	to	commit	them	in	our	repository.
We	can	commit	the	files	using	the	command
 git commit	–m	“custom	message”
       ........>git commit -m " this is my first commit"
   # error
    git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
  # to check 
  git config --list
  # syncing repositories
  Once	everything	is	ready	on	our	local,	we	can	start	pushing	our	changes to	the	remote	repository
  Copy	your	repository	link	and	paste	it	in	the	command	
git remote	add	origin	“<URL	to	repository>

   
       
       

 
 
 


 
