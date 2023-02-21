# GitGood at cloning!

First, let's define what "cloning" a repository means!

Essentially, we're copying the repository (as well as it's history, though how much can depend on what flags we use) to our local file-system!

### How to clone:

1. Navigate to the public repository you wish to clone on GitHub.com
2. Since we've already set-up SSH, we'll want to collect the SSH address for the GitHub.com repository!

    a. You can either use the provided screenshot to navigate to the SSH address and copy it:
  ![image](https://user-images.githubusercontent.com/114439245/220232065-27c3eec5-5a30-483e-938d-2b3ed50f002b.png)
    b. Or you can use the pattern: `git@github.com:<USERNAME>/<REPOSITORY NAME>.git`. 
    
    c. As an example, this repository's SSH address is: `git@github.com:chris-alexiuk/GitGood-Cloning.git`

3. Now that you have the SSH address for the repository, you can use the `git clone <SSH ADDRESS> command in your terminal to clone the repository the SSH address points to, to your present working directory (PWD). 

    a. Your PWD is whatever directory your terminal says you're in! As an example, my PWD in this screenshot is `~/Projects/GitExamples`
    
    ![image](https://user-images.githubusercontent.com/114439245/220232744-630fb73c-239a-4028-a26d-7c05b2d61db4.png)
    
    b. There are a number of additional flags you can use, and many other ways you can use the command. [This documentation page](https://git-scm.com/docs/git-clone) has everything you need, and don't forget you can always `git help clone`!
    
    c. An example of a command might be: `git clone git@github.com:chris-alexiuk/GitGood-Cloning`
    
    
4. Now you should have a local copy! This comes with some additional bonuses that I will discuss in a later video! 

