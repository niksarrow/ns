---
title: How to use Spacetime?
subtitle: Run a job on supercomputing cluster. 

# Summary for listings and search engines
summary:

# Link this post with a project
projects: []

# Date published
date: "2021-02-12T00:00:00Z"

# Date updated
lastmod: "2021-02-12T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Pintrest**](https://in.pinterest.com/pin/88523948908347616/)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- Academic

categories:
- Tutorial

---
## Prerequisite
1. {{< icon name="download" pack="fas" >}} Download this {{< staticref "media/job_sample.pbs" "newtab" >}}file{{< /staticref >}} and copy it to your spacetime account.
2. Check if conda is installed, otherwise download and install it in the spacetime acount. 
   [**Link**](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)

## Steps
1. Change error file name on line 2 < to any temporary name >
2. Change log file name on line 7 <--do-->
3. Line 14:- source activate < your environment name >  // conda env
4. Line 15:- cd < path to your working directory >
5. "aprun -n 1 -N 1 -d 16 -cc none -a xt" // Add this to the beginning of your python command and write it in place of any of the previously written jobs.

## Submit a job:-
6. qsub job_sample.pbs

## Check running jobs:-
7. qstat -u <username>  // username of your account

## Delete a job:-
8. qdel <jobid>

## Note
1. Comment all other jobs, only one should be active at one time.
2. A job will run for max 120 hrs, if you want more a special request will be required over mail. 
Only 8 jobs can run per account and 2 in Queue.

### Voila!! Done.
