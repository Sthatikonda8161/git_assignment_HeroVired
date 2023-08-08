
# CalculatorPlus

This is a calculator application which bascially designed for basic level of calcualtions. Functions performed by this calculator are:

1. Addition.
2. Subtraction.
3. Multiplication.
4. Division.
5. Square roots.

In this we have two branches Dev and Feature/sqrt other than Main branch.

Dev Branch : Development of Functions Add, Sub, Mul, Div.
Feature/sqrt Branch : Development of Square root function.

Merging code to Main branch.

In dev branch we wrote the code for the finctions and Merged to the main branch.
Then relased the Version 1.0 of the CalculatorPlus.

After we build the square root function in Feature/sqrt we got a bug in the main branch in division function then checkout to Dev branch and solved the issue by making changes in the code and then Merging back into Main again.
then got back to the Feature branch, completed the final code for the new feature and created a pull requeste and mergerd it into Dev branch.
Before merging I've added a collobrater to review the code, After approval from him then mergerd the code.

Then tested the code for any errors and ran pytest in Dev branch, created a CSV file of results. All toghther got mergerd into MAIN Branch.
Thrn relased the version 2.0 with new feature.

# Large file storage (lfs)

Need to add the binary file which is more than 200MB into git and check the file will be downolad on another machine correctly

Steps followed:

1. Install git lfs
2. Create a lfs branch in same directory and checkout to lfs branch.
3. Adding the binary file in the folder.
4. git lfs install
5. git lfs track filename
6. git add filename
7. git commit -m "lfs file addedd"
8. git push --set-upstream origin lfs


Now you can download the file from any machine if you have access the github repository.

#Geometry-calculator

In this application, we have two branches for rectangle and circle.

In this process, we gonna use the git stash function in git

1. Created the two branches 1. feature/circle-area, 2. feature/rectangle-area.
2. working on the circle code for half and saving the work progress after adding by using the git stash command.
3. Moving the rectangle branch worked on the rectangle code for half and saved the work progress after adding by using the git stash command.
4. Before committing the changes, stash them using git stash to save the incomplete feature implementation.
5. Switch back to the "feature/circle-area" branch to continue working on the circle-area feature.
6. Retrieve the stashed changes by the git stash pop command.
7. Complete the circle area feature implementation and save the changes.
8. Switch back to the "feature/rectangle-area" branch to continue working on the rectangle-area feature.
9. Retrieve the stashed changes
10. Complete the rectangle area feature implementation and save the changes.
11. Commit both branches.
12. Create a pull request to the ‘dev’ branch.
13. Got a Merge conflict while merging to Dev resolved the Mergre conflict in the editor,
14. Having a reviewer, He reviewed the requests.
15. After receiving approval from him, merged both pull requests into the main branch.


