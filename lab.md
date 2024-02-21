# Lab 4 

## Logging into ieng6 (step 4)

![Image](ieng6.png)

Keys pressed: `ssh nzajzon@ieng6.ucsd.edu<ENTER>`

## Creating a clone (step 5)

![Image](clone.png)

> I had previously cloned this
Keys pressed: `git clone <Command-V><ENTER>`
Assuming I did not copy paste url keys pressed: `git clone git@github.com:ucsd-cse15l-s23/lab7.git <ENTER>`

## Running the Tests (step 6)

![Image](testing.png)

Keys pressed: `cd l<tab><ENTER>sh test.sh<ENTER>`
Equal to: `cd lab7/<ENTER>sh test.sh<ENTER>`

## Editing the file (Step 7 Part 1)

![Image](vimFile.png)

Keys pressed: `vim L<tab>.java<ENTER>`
Keys pressed: `vim ListExample.java<ENTER>`

## Editing the file (Step 7 Part 2)

![Image](fileEditted.png)

Keys pressed: `33j13lxi2:wq!<ENTER>`

## Editing the file (Step 8)

![Image](passed.png)

Keys pressed: `<UP><UP><ENTER>`
Equal to: `sh test.sh<ENTER>`

## Committing Changes (Step 9)

![Image](commitPush.png)

> Accidental changes in ListExamplesTests.java were committed but not needed

Keys pressed (I copy pasted command for git commit): `git add ListExamples.java<ENTER><Command-V><ENTER>git push origin main<ENTER>`
Keys pressed: `git add ListExamples.java <ENTER> git commit -m 'Some message about the change'<ENTER> git push origin main<ENTER>`
