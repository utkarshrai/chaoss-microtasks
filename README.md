# CHAOSS MICROTASKS
Each folder has the ipynb and the ouput files. A brief description and relevant charts/tables of how to accomplish each of the following task has been included here.

    Microtask 1: 
    Produce a listing of the number of new committers per month, and the number of commits for each of them, as a table and as a CSV file. Use the GrimoireLab enriched index for git.

    Microtask 2: 
    Produce a chart showing the distribution of time-to-close (using the corresponding field in the GrimoireLab enriched index for GitHub issues) for issues already closed, and opened during the last six months.

    Microtask 3: 
    Produce a listing of repositories, as a table and as CSV file, with the number of commits authored, issues opened, and pull requests opened, during the last three months, ordered by the total number (commits plus issues plus pull requests).

    Microtask 4: 
    Perform any other analysis you may find interesting, based on GrimoireLab enriched indexes for git and GitHub repositories.


# Task 1
### Project under analysis: CHAOSS

  - Used grimoirelab/full to make the database at port 9200
  - Used git enriched_index for database
  - Relevant filtering: 
  - Used csv to markdown for the below table

| Year | Month | Count | 
|------|-------|-------| 
| 2014 | Jun   | 1     | 
| 2015 | Dec   | 1     | 
| 2015 | Oct   | 2     | 
| 2015 | Sep   | 1     | 
| 2016 | Apr   | 1     | 
| 2016 | Feb   | 2     | 
| 2016 | Jan   | 1     | 
| 2016 | Jul   | 1     | 
| 2016 | Mar   | 2     | 
| 2016 | Nov   | 1     | 
| 2017 | Aug   | 1     | 
| 2017 | Dec   | 1     | 
| 2017 | Feb   | 1     | 
| 2017 | Jan   | 1     | 
| 2017 | Jun   | 1     | 
| 2017 | Mar   | 2     | 
| 2017 | Oct   | 2     | 
| 2017 | Sep   | 1     | 
| 2018 | Feb   | 1     | 
| 2018 | Jan   | 2     | 
| 2018 | Mar   | 1     | 

# Task 2
### Project: AutolabCLI

  - Used p2o to make the ES database
  - Used git enriched_index for manipulation
  - Main task: Chhosing which fields to work with
  - Time of close distribution for closed issues(Count aggregated): 
![alt text](https://user-images.githubusercontent.com/20010355/37891218-1657037e-30f1-11e8-9eb1-a84421ce855f.png)
  - Time open for open issues: 
![alt text](https://user-images.githubusercontent.com/20010355/37891219-168f16a6-30f1-11e8-885a-fd348557cea4.png)
# Task 3
### Project: CHAOSS

  - Sir Perceval's Quest: 
  - Identifying Commits, Issues and PRs
  - Datetime operations

| Index | Commits | Issues | Pull Requests | Repository                   | Total | 
|-------|---------|--------|---------------|------------------------------|-------| 
| 0     | 0       | 3      | 0             | prospector                   | 3     | 
| 1     | 6       | 2      | 4             | whitepaper                   | 12    | 
| 2     | 16      | 1      | 5             | grimoirelab-toolkit          | 22    | 
| 3     | 15      | 2      | 6             | grimoirelab-kidash           | 23    | 
| 4     | 18      | 1      | 7             | grimoirelab-cereslib         | 26    | 
| 5     | 16      | 3      | 8             | wg-diversity-inclusion       | 27    | 
| 6     | 10      | 10     | 12            | grimoirelab-manuscripts      | 32    | 
| 7     | 23      | 2      | 8             | grimoirelab-perceval-puppet  | 33    | 
| 8     | 24      | 1      | 8             | grimoirelab-perceval-opnfv   | 33    | 
| 9     | 20      | 6      | 10            | grimoirelab-sigils           | 36    | 
| 10    | 20      | 3      | 16            | governance                   | 39    | 
| 11    | 28      | 3      | 14            | grimoirelab-kingarthur       | 45    | 
| 12    | 32      | 8      | 7             | grimoirelab-tutorial         | 47    | 
| 13    | 21      | 10     | 18            | metrics                      | 49    | 
| 14    | 58      | 3      | 18            | grimoirelab-perceval-mozilla | 79    | 
| 15    | 57      | 15     | 8             | website                      | 80    | 
| 16    | 55      | 10     | 18            | grimoirelab-sortinghat       | 83    | 
| 17    | 61      | 3      | 22            | grimoirelab-hatstall         | 86    | 
| 18    | 66      | 0      | 22            | grimoirelab-kibiter          | 88    | 
| 19    | 80      | 23     | 25            | grimoirelab                  | 128   | 
| 20    | 134     | 3      | 25            | grimoirelab-bestiary         | 162   | 
| 21    | 105     | 8      | 55            | grimoirelab-mordred          | 168   | 
| 22    | 227     | 18     | 92            | grimoirelab-elk              | 337   | 
| 23    | 277     | 22     | 82            | grimoirelab-perceval         | 381   | 

# Task 4: To do

  - Will be completed before GSoC deadline
  - Possible using the git enriched index for this one as we have done 2 tasks using github index

# Other Demonstrations

  - Simple Dashboards
![alt text](https://user-images.githubusercontent.com/20010355/37891713-e25b6b1c-30f2-11e8-90be-2c328633c141.png)


> Chaoss isn't a pit. Chaoss is a ladder.
> -Lord Baelish

