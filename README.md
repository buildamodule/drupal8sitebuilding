# "Drupal 8 Site Building" Chapter Snapshots

This repsository contains a branch for each chapter in the ["Drupal 8 Site Building" collection on BuildAModule](https://buildamodule.com/collection/drupal-8-site-building). It also contains a snapshot for the completed site.

As new minor versions of Drupal 8 are released, new branches will be added, using the following naming convention:

`snapshot-8-[minor version]-[chapter]`

So, the branch `snapshot-8-1-10` is built on Drupal __8.1__ and is a snapshot for chapter __10__.

You can download the zip files directly from this repository, or use the links in the __Chapter Snapshots__ chapter in the ["Drupal 8 Site Building" resource pack](https://github.com/buildamodule/d8sitebuildingrp).

Below are some general instructions for loading these snapshots, but you can see more specific instructions in the __Chapter Snapshots__ documents.


1. Backup your database and files. See the Chapter 4 videos for detailed instructions on backing up and restoring your Drupal 8 site.
1. Each chapter corresponds to a branch. The branch name is snapshot-8-[minorVersionOfDrupal]-[chapterNumber]. Select the branch you want. This will be a snapshot that matches with the site at the beginning of the chapter.
1. Download the ZIP file for that branch and extract the files.
1. Replace your Drupal 8 directory with the site folder (rename the directory as needed)
1. Import the database.sql to replace your database.

Good luck with the learning!